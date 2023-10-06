## Aşağıdaki sorgu senaryolarını dvdrental örnek veri tabanı üzerinden gerçekleştiriniz.
## film tablosunda bulunan title ve description sütunlarındaki verileri sıralayınız.

## ODEV1 -1.
# SELECT title,description FROM film

## ODEV1 -2.
# SELECT * from film
# WHERE length > 60 AND length <75

## ODEV1 -3.
# SELECT * FROM film
# WHERE rental_rate = 0.99 AND replacement_cost =12.99 OR replacement_cost=28.99


## ODEV1 4.
# SELECT last_name FROM customer
# WHERE first_name ='Mary'

## ODEV1 5.
# SELECT * FROM film
# WHERE NOT (length >50 AND rental_rate=2.99 OR rental_rate=4.99)