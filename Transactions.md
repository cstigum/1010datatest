#	Transactions
The transactions JSON object represents each transaction at each store. The transaction object contains the following fields:

Field name | Type | Description | Notes
-------|---------|---------|------
transid | string | The unique identification number of the transaction. | 
account | string | The account number related to the transaction. 
store |  string | The store number of the transaction.| Can be "1", "2", or "3". This number is read as text from the input file, but is cast as an integer.
date | string | The date of the transaction.
sku | string | The sku of the transaction. 
units | string | The number of units contained in the transaction.
sales | string | The sales price of the transaction. | This number is read as text from the input file, but is cast as a float for the purpose of calculations. 
cost | string | The cost of the transaction. | This number is read as text from the input file, but is cast as a float for the purpose of calculations.


> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbNzUzOTg1NjldfQ==
-->