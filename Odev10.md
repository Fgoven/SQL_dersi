## SQL ÖDEV 10

## SORU 1
``` SQL
SELECT city.city,country.country FROM city
LEFT JOIN country ON city.country_id = country.country_id;
```

``` SQL
SELECT city.city,country.country FROM country
LEFT JOIN city ON city.country_id = country.country_id;
```
## SORU 2
``` SQL
SELECT payment.payment_id, customer.first_name,customer.last_name FROM customer
RIGHT JOIN payment ON customer.customer_id = payment.customer_id;
```
``` SQL
SELECT payment.payment_id, customer.first_name,customer.last_name FROM payment
RIGHT JOIN customer ON customer.customer_id = payment.customer_id;
```

## SORU 3
``` SQL
SELECT rental.rental_id, customer.first_name,customer.last_name FROM customer
FULL JOIN rental ON customer.customer_id = rental.customer_id;
```
