LBYS Mobil Uygulaması

Bu proje, staj kapsamında geliştirilen Laboratuvar Bilgi Yönetim Sistemi (LBYS) uygulamasıdır.
Flutter & Firebase altyapısı kullanılarak hazırlanmıştır.

Uygulamada üç farklı rol bulunmaktadır:

  -Yönetici
  
  -Doktor
  
  -Laborant

Test Kullanıcıları

Uygulamaya giriş yapmak için hazır test kullanıcıları mevcuttur:

Rol     	  E-posta                	Şifre

Doktor	-  test@doktor.com          	123456

Yönetici -	deneme@yonetici.com    	  123456

Laborant -	laborant@laborant.com 	  123456

Laborant -	selin@laborant.com 	      123456

Özellikler

Rol tabanlı erişim (doktor, laborant, yönetici için farklı paneller)

Hasta yönetimi: Hasta ekleme, listeleme ve rol bazlı yönlendirme

Cihazdan veri simülasyonu: Firebase’deki device_results koleksiyonundan hasta ID’sine göre test sonuçlarını çekme

Gerçekçi senaryo: Normalde cihazlardan QR kod ile otomatik veri aktarımı yapılır, ancak bu projede simülasyon amaçlı Firebase üzerinden tek tuşla veriler çekilmektedir.

Test kolaylığı: İki hastanın kan değerleri özellikle boş bırakıldı, böylece laborant panelinde manuel giriş/test senaryosu yapılabilir.

Uygulamayı Çalıştırma
Mobil (Android/iOS)

Depoyu klonlayın veya ZIP olarak indirin.

Proje klasöründe terminal açın.

Flutter bağımlılıklarını indirin:

flutter pub get


Telefonunuzu USB ile bağlayın veya emülatör açın.

Uygulamayı çalıştırın:

flutter run

Not: Web sürümünde tüm özellikler çalışır, Firebase bağlantısı aynıdır.

Proje Hakkında

Flutter (Dart) ile yazılmıştır.

Firebase Authentication & Firestore veritabanı kullanılmaktadır.

> Not: Projede yer alan bazı büyük dosyalar (örn. google-services.json, lock dosyaları vb.) GitHub üzerinde boyutlarından dolayı **önizlenememektedir**. 
Bu durum projenin çalışmasına engel değildir; projeyi indirdiğinizde tüm dosyalar eksiksiz şekilde çalışır.
