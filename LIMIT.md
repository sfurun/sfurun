1 - SELECT title, length FROM film WHERE title ~~ ('%n') ORDER By length DESC LIMIT 5
2 - SELECT title, length FROM film WHERE title ~~ ('%n') ORDER By length ASC LIMIT 5
3 - SELECT last_name length FROM customer WHERE store_id = '1' ORDER By length DESC LIMIT 4
