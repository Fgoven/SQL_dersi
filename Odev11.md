## SQL ÖDEV 11
### SORU 1 
```SQL
(
SELECT first_name FROM actor
)
UNION
(
SELECT first_name FROM customer
);

```
### SORU 2
```SQL
(
SELECT first_name FROM actor
)
INTERSECT
(
SELECT first_name FROM customer
);
```
### SORU 3 
```SQL
(
SELECT first_name FROM actor
)
EXCEPT
(
SELECT first_name FROM customer
);
```
### SORU 4
```SQL
--- UNION ALL 
(
SELECT first_name FROM actor
)
UNION ALL
(
SELECT first_name FROM customer
);
--- INTERSECT ALL (Same result as Soru 2, so "ALL" keyword is meaningless for INTERSECT
(
SELECT first_name FROM actor
)
INTERSECT ALL
(
SELECT first_name FROM customer
);

--- EXCCEPT ALL
(
SELECT first_name FROM actor
)
EXCEPT ALL
(
SELECT first_name FROM customer
);
```
