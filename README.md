# -patika-Sql-blob-main-odev2.sql

-- 1.soru

SELECT * FROM film
WHERE replacement_cost between 12.99 AND 16.99;

-- 2. soru

SELECT first_name, last_name FROM actor
WHERE first_name in ('Penelope', 'Nick', 'Ed')

-- 3.soru

SELECT * 
FROM film
WHERE rental_rate IN (0.99, 2.99, 4.99) 
AND replacement_cost IN (12.99, 15.99, 28.99)
