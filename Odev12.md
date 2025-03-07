## SQL ÖDEV 12
### SORU 1
``` SQL
SELECT COUNT(*) FROM film
WHERE length >
(
	SELECT AVG(length) FROM film
);
```
### SORU 2
``` SQL
SELECT COUNT(*) FROM film
WHERE rental_rate =
(
	SELECT MAX(rental_rate) FROM film
);
```
### SORU 3
``` SQL
SELECT * FROM film
WHERE 
(rental_rate =
	(
	SELECT 
	MIN(rental_rate) 
	FROM film
	)
)
AND
(
	replacement_cost =
	(
	SELECT 
	MIN(replacement_cost) 
	FROM film
	)
);
```
### SORU 4
``` SQL
SELECT payment.customer_id ,customer.first_name , customer.last_name, COUNT(payment.customer_id) AS Sum 
FROM customer 
INNER JOIN payment ON customer.customer_id = payment.customer_id 
GROUP BY customer.first_name , customer.last_name, payment.customer_id
ORDER BY sum DESC ;
```
