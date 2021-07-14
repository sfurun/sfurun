SELECT ROUND(AVG(rental_rate),3) as ortalama FROM film
SELECT COUNT(*) as say FROM film WHERE title ~~ ('C%')
SELECT MAX(length) as maks FROM film WHERE rental_rate = 0.99
SELECT COUNT(replacement_cost) as say FROM film WHERE length > 150
