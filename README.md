# sql_patika_odev_9   www.patika.dev
patika ödev  ---sql_patika_odev_9
--answer 1
SELECT city.city, country.country FROM city
INNER JOIN country ON city.country_id = country.country_id;

--answer 2
SELECT first_name, last_name, payment_id FROM customer
INNER JOIN payment ON customer.customer_id = payment.customer_id;

-- answer 3
SELECT first_name, last_name, rental_id FROM customer
INNER JOIN rental ON customer.customer_id = rental.customer_id;
