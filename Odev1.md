# SQL_dersi 
## *Patika.dev/Kodluyoruz* **SQL Dersi Ödevleri** için hazırlanmıştır
---
### Soru 1

``` SQL 
SELECT title,description FROM film
``` 

### Soru 2
``` SQL
SELECT * FROM film
WHERE length > 60 AND length < 75;
```
### Soru 3
``` SQL
SELECT * FROM film
WHERE rental_rate = 0.99 AND replacement_cost = 12.99 OR replacement_cost = 28.99;
```
### Soru 4
``` SQL
SELECT first_name,last_name FROM customer
WHERE first_name = 'Mary'

-- Result is 'Smith'
```
### Soru 5
``` SQL
SELECT * FROM film
WHERE NOT length > 50 AND (rental_rate != 2.99 OR rental_rate != 4.99);
```
