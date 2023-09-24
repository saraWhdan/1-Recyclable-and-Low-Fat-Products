# 1-Recyclable-and-Low-Fat-Products
Problem Link:https://leetcode.com/problems/recyclable-and-low-fat-products/description/?envType=study-plan-v2&envId=top-sql-50
## Solution

```sql
select product_id 
from Products
where low_fats ='y' AND recyclable = 'y'
```
