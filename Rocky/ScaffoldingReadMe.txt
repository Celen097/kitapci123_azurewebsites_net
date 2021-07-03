#############################
##                         ##
##      PROJE İÇERİĞİ      ##
##                         ##
#############################

Projede kullanılan diller:

- C#
- HTML
- CSS
- JS

Projede kullanılan teknolojiler:

- Azure Cloud Storage
- Azure Cloud Database
- .NET Core

Proje Mimarisi : 

- MVC

Proje Özeti:

  Yönetim, kullanıcı ve ziyaretçi taraflı kitap listeleme sistemi.

Proje Açıklaması:

  Projede kullanılan veritabanı MS SQL , yapı Helper class'lar ile MVC(Model-View-Controller).

  Sistem içerisinde yetkilendirme DB'te tutulan yetki anahtarlarıyla sağlanmış, erişim yetkisi controller'lardan AUTH token denetimi ile yapılmıştır.

  Tablolar:
	- Blog
	- Kategori
	- Tür
	- Ürün 
	- Kullanıcı
	- Yetki düzeyleri
	- Kullanıcı yetki düzeyi eşlemesi
	- Login kayıtları
	- Log sırasında kullanıcıya atanan session tokenları
  olarak ayrı tablolar halinde tutlmuştur.

  Anasayfa için tüm modelleri çeken bir homeVM controller diğer sayfalar için ayrı ayrı controllerlar ve modeller bulunmaktadır.

  Sistem dahili bağlantı bilgileri JSON olarak tutulmakta ve sistem dahilinde email ile session apileri kurulu bulunmaktadır. API anahtarları alındığı takdirde servisler çalışır hale gelir.

  WC Class'ı sistem geneli tanımlama yapmak için mevcuttur.

  DB'de manuel oluşturulmuş tablo bulunmamakta. Migration eklenip "update-database" yöntemi ile tablolar otomatik oluşturulmuştur. 
