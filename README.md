1- test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.  
```sh
SELECT ROUND(AVG(rental_rate),3) FROM film;
```
2- Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.  
```sh
insert into employee (name, birthday, email) values ('Lammond', '1998-09-16', 'llarsen1c@github.com');
insert into employee (name, birthday, email) values ('Hercules', '2014-03-24', 'hyaneev1d@senate.
```
3- Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.  
```sh
UPDATE employee SET name = 'Barış' WHERE id < 6;
```
4- Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.  
```sh
DELETE FROM employee WHERE id < 6;
```
