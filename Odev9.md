## SQL Dersi ÖDEV 9

### SORU 1 
``` SQL
SELECT city, country FROM country
INNER JOIN city ON country.country_id = city.country_id;
```

### SORU 2 
``` SQL
SELECT payment_id, customer.first_name, customer.last_name FROM payment
INNER JOIN customer ON customer.customer_id = payment.customer_id;
```

### SORU 3 
``` SQL
SELECT rental_id, customer.first_name, customer.last_name FROM rental
INNER JOIN customer ON customer.customer_id = rental.customer_id;
```
