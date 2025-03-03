## SQL Dersi ÖDEV 7

### SORU 1 
``` SQL
SELECT rating FROM film
GROUP BY rating;
```
### SORU 2 
``` SQL
SELECT replacement_cost, COUNT(*) FROM film
GROUP BY replacement_cost
HAVING COUNT(*) > 50;
--ORDER BY replacement_cost; Optional
-- ORDER BY COUNT(*); Optional
```
### SORU 3 
``` SQL
SELECT store_id, COUNT(*) FROM customer
GROUP BY store_id;
```
### SORU 4 
``` SQL
SELECT country_id, COUNT(city) FROM city
GROUP BY country_id
ORDER BY COUNT(city) DESC
LIMIT 1;
```
