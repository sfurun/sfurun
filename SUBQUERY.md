SELECT COUNT(*) as filmSayısı FROM film WHERE length > (SELECT ROUND(AVG(length)) FROM film)

SELECT COUNT(*) as filmSayısı FROM film WHERE rental_rate = (SELECT (MAX(rental_rate)) FROM film)

SELECT COUNT(*) as filmSayısı FROM film WHERE rental_rate = (SELECT (MIN(rental_rate)) FROM film) AND replacement_cost = (SELECT (MIN(replacement_cost)) FROM film)

SELECT (SELECT customer_id, COUNT(customer_id) FROM payment GROUP BY customer_id) FROM payment  
