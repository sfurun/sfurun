SELECT DISTINCT replacement_cost FROM film
SELECT COUNT(DISTINCT replacement_cost) FROM film 
SELECT COUNT(title) FROM film WHERE title ~~ 'T%' AND rating='G'
SELECT COUNT(country) FROM country WHERE CHAR_LENGTH(country) = 5
SELECT COUNT(city) FROM city WHERE city ~~*('%R')
