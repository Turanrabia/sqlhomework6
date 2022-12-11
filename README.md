# sqlhomework6
-- film tablosunda bulunan rent_rate sütunundaki değerlerin ortalaması nedir?
-- film tablosunda bulunan filmlerden kaç tanesi 'C' karakteri ile başlar?
-- film tablosunda bulunan filmlerden rent_rate değeri 0.99 a eşit olan en uzun (uzunluk) film kaç dakikadır?
-- film tablosunda bulunan filmlerin uzunluğu 150 dakikadan büyük olanlarına ait kaç farklı replace_cost değeri vardır?

 Filmden AVG (rental_rate) SEÇİN ;
 Filmden COUNT (başlık) SEÇİN WHERE Ad LIKE ' C % ' ; 
 Filmden MAX ( uzunluk ) SEÇİN Rental_rate = 0 . 99 ;
 SAYI SEÇİN ( UZUNLUK > 150 OLDUĞUNDA FİLMDEN FARKLI değiştirme_maliyeti ;
