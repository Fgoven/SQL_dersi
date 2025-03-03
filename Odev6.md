## SQL Dersi Ödev 6

### SORU 1
``` SQL
SELECT ROUND((AVG(rental_rate)),4) FROM film;
```
### SORU 2
``` SQL
SELECT COUNT(*) FROM film
WHERE title LIKE 'C%';
```
### SORU 3
``` SQL
SELECT MAX(length) FROM film
WHERE rental_rate = 0.99;
```
### SORU 4
``` SQL
SELECT COUNT(DISTINCT (replacement_cost)) FROM film
WHERE length > 150;
``` 
