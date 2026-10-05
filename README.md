# Algoritma-giri-ak-
Kullanıcı giriş süreci için algoritma ve akış diyagramı
Algoritma Tasarımı ve Akış Diyagramı
Proje Hakkında

Bu projede bir web uygulamasındaki kullanıcı giriş sürecinin algoritması tasarlanmış ve akış diyagramı ile gösterilmiştir.

Amaç, kullanıcı giriş işlemi sırasında oluşabilecek durumları adım adım analiz etmek ve bu süreci standart akış diyagramı sembolleri kullanarak görselleştirmektir.

Giriş Sistemi Kuralları

Sistemin çalışma mantığı şu şekildedir:

Öncelikle hesabın kilitli olup olmadığı kontrol edilir.
Hesap kilitliyse kullanıcıya "Hesap geçici olarak kilitlendi." mesajı gösterilir ve işlem sonlandırılır.
Hesap kilitli değilse kullanıcıdan e-posta ve şifre bilgileri alınır.
Alanlardan biri boş bırakılmışsa kullanıcı uyarılır ve başarısız giriş sayacı artırılmaz.
Alanlar doluysa girilen bilgilerin doğru olup olmadığı kontrol edilir.
Bilgiler doğruysa başarılı giriş gerçekleştirilir.
Bilgiler yanlışsa başarısız giriş sayısı 1 artırılır.
Başarısız giriş sayısı 3'e ulaşırsa hesap kilitlenir.
Sayaç 3'e ulaşmadıysa kullanıcıya bilgilerin hatalı olduğu bildirilir ve yeni giriş denemesi yapılır.

Bu kurallar ödevde belirtilen iş kurallarına göre oluşturulmuştur.

Sayaç

Başlangıçta başarısız giriş sayısı:

0

olarak kabul edilir.

Boş alan bırakılması başarısız giriş olarak değerlendirilmez. Yalnızca girilen bilgilerin yanlış olması durumunda sayaç 1 artırılır.

Akış Diyagramı Sembolleri

Akış diyagramında aşağıdaki semboller kullanılmıştır:

Oval: Başlangıç / Bitiş
Paralelkenar: Girdi / Çıktı
Dikdörtgen: İşlem / Sayaç güncelleme
Elmas: Karar / Koşul
Ok: İşlem akışının yönü




Kullanılan Dosyalar
README.md → Proje açıklaması
akış-diyagramı.png → Hazırlanan akış diyagramı
Test Edilen Durumlar

Akış aşağıdaki senaryolar dikkate alınarak tasarlanmıştır:

Hesap zaten kilitli
E-posta alanının boş olması
Şifre alanının boş olması
Doğru giriş bilgileri
İlk yanlış giriş
İkinci yanlış giriş
Üçüncü yanlış giriş ve hesabın kilitlenmesi
Hesap kilitlendikten sonra tekrar giriş yapılması




Sonuç

Bu çalışma ile kullanıcı giriş sürecinin algoritmik düşünme, karar yapıları, sayaç kullanımı ve akış diyagramı oluşturma açısından modellenmesi amaçlanmıştır.

Bu projede uygulama kodu yazılmamış, yalnızca algoritma ve akış diyagramı tasarlanmıştır.
