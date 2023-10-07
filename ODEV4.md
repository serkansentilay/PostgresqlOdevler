### film tablosunda bulunan replacement_cost sütununda bulunan birbirinden farklı değerleri sıralayınız.
## ODEV4 1
# SELECT DISTINCT replacement_cost FROM film

### film tablosunda bulunan replacement_cost sütununda birbirinden farklı kaç tane veri vardır?
## ODEV4 2
# SELECT COUNT(DISTINCT replacement_cost) FROM film

### film tablosunda bulunan film isimlerinde (title) kaç tanesini T karakteri ile başlar ve aynı zamanda rating 'G' ye eşittir?
## ODEV4 3
# SELECT COUNT(*) FROM film
# WHERE title LIKE 'T%' AND rating='G'

### country tablosunda bulunan ülke isimlerinden (country) kaç tanesi 5 karakterden oluşmaktadır?
## ODEV4 4
# SELECT COUNT(country) FROM country
# WHERE country LIKE '_____'

### city tablosundaki şehir isimlerinin kaç tanesi 'R' veya r karakteri ile biter?
## ODEV4 5
# SELECT COUNT(*) FROM city
# WHERE city ILIKE '%r'


