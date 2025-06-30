# ✨ <ins> SQL</ins>
> _**Veritabanı dilidir**_
  
> _**SQL(Structed Query Language)**_

Mysql Linux tabanlı websitelerinde
Postresql kurumsal websiteleri
Microsoft SQLserver .net sitelerinde 

| Veri Tipi Kategorisi                     | Açıklama                                                               | Örnek Tipler                              |
|------------------------------------------|------------------------------------------------------------------------|-------------------------------------------|
| Sayısal (Numeric) Veri Tipleri           | Sayılarla ilgili hesaplamalarda kullanılır.                           | `INT`, `SMALLINT`, `BIGINT`, `DECIMAL(p,s)`, `NUMERIC(p,s)`, `FLOAT`, `REAL` |
| Metinsel (Character/String) Veri Tipleri | Harf, kelime ve metinleri saklamak için kullanılır.                   | `CHAR(n)`, `VARCHAR(n)`, `TEXT`           |
| Tarih ve Zaman Veri Tipleri              | Tarih ve saat bilgilerini tutmak için kullanılır.                     | `DATE`, `TIME`, `DATETIME`, `TIMESTAMP`, `YEAR` |
| Mantıksal (Boolean) Veri Tipi            | Doğru/yanlış gibi iki değer arasında seçim için kullanılır.           | `BOOLEAN`, bazı sistemlerde `BIT`         |
| İkili (Binary) Veri Tipleri              | Görsel, ses gibi dosyalar veya şifreli veriler için idealdir.         | `BINARY`, `VARBINARY`, `BLOB`             |
| Özel (Special) Veri Tipleri              | Belirli veritabanlarına özgü daha az yaygın tiplerdir.                | `ENUM`, `SET`, `XML`, `JSON`, `GEOGRAPHY`, `UUID` |


| Fonksiyon              | Açıklama                                                  |
|------------------------|-----------------------------------------------------------|
| `AVG()`                | Sayıların ortalamasını hesaplar.                          |
| `COALESCE(a, b, ...)`  | İlk boş olmayan değeri döndürür.                          |
| `COUNT()`              | Satır sayısını döndürür.                                   |
| `LENGTH()`             | Metnin karakter uzunluğunu döndürür.                      |
| `LOWER()` / `UPPER()`  | Metni küçük/büyük harfe çevirir.                          |
| `MAX()`                | En büyük değeri bulur.                                     |
| `MIN()`                | En küçük değeri bulur.                                     |
| `NOW()`                | Geçerli tarih ve zamanı getirir.                          |
| `ROUND(n, d)`          | Sayıyı belirtilen basamağa yuvarlar.                      |
| `SUBSTRING(str, s, l)` | Belirli konumdan itibaren metnin bir parçasını alır.     |
| `SUM()`                | Sayısal sütundaki değerlerin toplamını verir.             |

 


|Örnek Kod|Açıklama|
|------------------------|-----------------------------------------------------------|
| Elma getir         | Select Elma from Manav| 
| Tüm elmaları getir | Select * from Manav|
| Tüm meyvelerden bir çeşit getir | Select Distinct Meyve * from Manav|
| 1 kilo elma verin | Select Elma from Manav Where kg=5|
|çilekleri meyve bölümüne yerleştirip fiyatı 50 yazın | INSERT INTO meyve (meyve_türü, adet) VALUES ('çilek', 50);|
|meyveleredn muz olanların fiyatını 15 yap |UPDATE meyve_sepeti SET fiyat = 15 WHERE meyve_türü = 'muz';|
|kavunları kaldır|DELETE FROM meyve_sepeti WHERE meyve_türü = 'kavun';|
|tropikal meyveleri ekle |CREATE TABLE tropikal_meyveler (  meyve_türü NVARCHAR(50),  fiyat DECIMAL(18, 0));|















  