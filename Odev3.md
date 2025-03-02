## SQL ODEV 3

### SORU 1 
``` SQL
SELECT country FROM country
WHERE country LIKE 'A%a';
``` 
### SORU 2 
``` SQL
SELECT country FROM country
WHERE country LIKE '_____%n';
```
### SORU 3 
``` SQL
SELECT title FROM film
WHERE title ILIKE '%t%t%t%t';
```
### SORU 4 
``` SQL
SELECT * FROM film
WHERE (title LIKE 'C%') AND (length > 90) AND (rental_rate = 2.99);
```
