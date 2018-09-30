
# Calculate() function
The calculate() function performs the following calculations for a single store: 

 - Average costs
 - Average sales
 - Sum of the costs
 - Sum of the sales

## Syntax
```javascript
calculate(json_object, store, data, function)
```
## Parameters

|Name  | Data Type | Description | Notes
------|---------|-------|----
json_object | 
store  | integer | The store number.  | Valid values are 1, 2 or 3.
data | string | The data you are calculating. You can calculate costs or sales.| Valid values are "cost" or "sales".  
function | string | The function you are performing, either the sum or average of transactions. | Valid values are "sum" or "avg".

## Return value

For the function "sum", returns the total rounded to two decimal places.
For the function "avg", returns the average rounded to two decimal places.

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQzNjQ5MzA3MF19
-->