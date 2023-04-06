1#SORU - country tablosunda bulunan country sütunundaki ülke isimlerinden 'A' karakteri ile başlayıp 'a' karakteri ile sonlananları sıralayınız.

1#CEVAP - SELECT country FROM country
WHERE country LIKE 'A%a';

1#<img width="960" alt="1" src="https://user-images.githubusercontent.com/129968939/230511149-8db1a00f-2c2e-4e9b-a0b1-e0b8cf1e37ea.png">

2#SORU - country tablosunda bulunan country sütunundaki ülke isimlerinden en az 6 karakterden oluşan ve sonu 'n' karakteri ile sonlananları sıralayınız.

2#CEVAP - SELECT country FROM country
WHERE country LIKE '%_____n';

2#<img width="960" alt="2" src="https://user-images.githubusercontent.com/129968939/230511538-e3278a21-95de-4ab6-8eb9-83606bf2b640.png">

3#SORU - film tablosunda bulunan title sütunundaki film isimlerinden en az 4 adet büyük ya da küçük harf farketmesizin 'T' karakteri içeren film isimlerini sıralayınız.

3#CEVAP - SELECT title FROM film
WHERE title ILIKE ('%t%t%t%t');

3#<img width="960" alt="3" src="https://user-images.githubusercontent.com/129968939/230512116-bdc9b8e2-b216-4a9d-98c3-780d65c53806.png">

4#SORU - film tablosunda bulunan tüm sütunlardaki verilerden title 'C' karakteri ile başlayan ve uzunluğu (length) 90 dan büyük olan ve rental_rate 2.99 olan verileri sıralayınız.

4#CEVAP - SELECT * FROM film
WHERE title LIKE 'C%' AND length > 90 AND rental_rate = 2.99;

4#<img width="960" alt="4" src="https://user-images.githubusercontent.com/129968939/230512748-79ff86e6-f0db-4377-8678-e2206edab6b9.png">
