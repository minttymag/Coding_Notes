# SQL in 10 MINS - 4th Edition Notes(from 2017)

L2 - Retrieving Data

1. DISTINCT can't be parital.
2. LIMIT & OFFSET: LIMIT secifies the number of rows to return. LIMIT with an OFFSET specifies where to start from.

SELECT prod_name 
FROM Products 
LIMIT 5 OFFSET 5;

Output: Instructs supported DBMSs Return five rows starting from row 5.
CAUTION: Row 0 - The first row retrieved is row 0. As such, LIMIT 1 OFFSET 1 will retrieve the second row.






