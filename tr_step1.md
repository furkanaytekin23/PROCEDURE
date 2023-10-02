Bu senaryoda sizlerden, size tahsis edilen makinelerde aşağıdaki talimatlar gereğince Employees tablosuna kayıtlar insert eden bir procedure oluşturmanız istenmektedir.

Veritabanı "Employees" adlı bir çalışanlar tablosu içermeli.

### 🔥 Temel Komutlar 🔥
SELECT: Veritabanı tablosundan veri çekmek için kullanılır. Hangi sütunları seçmek istediğinizi ve hangi tablodan seçmek istediğinizi belirtmelisiniz.
INSERT: Yeni kayıtları veritabanı tablosuna eklemek için kullanılır. Tablo adını ve eklemek istediğiniz sütunlara ait değerleri belirtmelisiniz.
WHERE: SQL sorgularında veriyi filtrelemek için kullanılır. Belirli bir koşulu karşılayan satırları seçmek için NEREDE koşullarını belirtmelisiniz.
CREATE: Veritabanı nesnelerini (örneğin tablolar, indeksler veya görünümler) oluşturmak için kullanılır. Oluşturmak istediğiniz nesne türünü belirtmeli ve gerekli bilgileri sağlamalısınız.
DELETE: Oluşturmuş olduğunuz veritabanındaki nesnelerden belirli bir müşteriyi delete komutu yardımıyla silebilirsiniz.

### 🚀 Uygulama Adımları 🚀

1. `su - postgres` komutuyla Postgres sunucusuna bağlanın.
2. `psql` veritabanına giriş yapın.
3. Yeni oluşturulan veritabanına bağlanmak için `\c YOUR_DATABASE_NAME;` komutunu kullanabilirsiniz.
4. id,name,surname,age,salary sütunlarına sahip Employees tablosunu oluşturun.
5. `\o /tmp/cevap` -> sorguyu kaydedeceğin alanı belirleyebilirsin.
6. Oluşturduğun Employees tablosuna kayıt insert eden bir procedure oluşturan daha sonra oluşturduğunuz procedure çalıştırıp Employees tablosuna id'si 23, adı Furkan, soyadı Aytekin, yaşı 27 ve maaşı 11000 olan çalışanı ekleyen sorguları yapın.
7. `/o` -> sorguları kaydedin.
8. Bir PostgreSQL veritabanından çıkmak için `\q` komutunu kullanabilirsiniz.
9. `cat /tmp/cevap` -> sonucu okuyabilirsin.
