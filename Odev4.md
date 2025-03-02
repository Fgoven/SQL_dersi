## SQL ÖDEV 4

### SORU 1
``` SQL
SELECT DISTINCT replacement_cost FROM film;
```
### SORU 2
``` SQL
SELECT COUNT(DISTINCT replacement_cost) FROM film;
```
### SORU 3
``` SQL
SELECT COUNT(*) FROM film
WHERE title LIKE 'T%' AND rating='G';
```
### SORU 4
``` SQL
SELECT COUNT(*) FROM country
WHERE country LIKE '_____';
```
### SORU 5
``` SQL
SELECT COUNT(*) FROM city
WHERE city ILIKE '%R';
``` 
