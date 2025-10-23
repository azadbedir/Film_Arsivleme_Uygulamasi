🎥 Java Film Arşivi Uygulaması

Bu proje, Java dilinde Nesne Yönelimli Programlama (OOP) ilkelerini kullanarak hazırlanmış basit bir Film Arşivi Yönetim Sistemi uygulamasıdır.
Kullanıcı, sistemde filmler oluşturabilir, bunları arşive ekleyebilir ve listeleyebilir.
Projede kalıtım (inheritance), polimorfizm (çok biçimlilik), enkapsülasyon (encapsulation) ve sınıf tabanlı tasarım gibi temel OOP kavramları uygulanmıştır.

🧩 Proje Yapısı
src/
│
├── Film.java              # Temel film sınıfı (ad, tür, yönetmen gibi ortak özellikler)
├── SinemaFilmi.java       # Film sınıfından türeyen alt sınıf (örnek: vizyon tarihi, süre, hasılat)
├── FilmArsivi.java        # Film nesnelerini yönetir (ekleme, listeleme, arama işlemleri)
└── Main.java              # Programın ana çalışma noktası (kullanıcı etkileşimi burada başlar)

⚙️ Kullanılan OOP Kavramları
Kavram	Kullanıldığı Yer	Açıklama
Class (Sınıf)	Film, SinemaFilmi, FilmArsivi	Her biri farklı bir sorumluluğu temsil eder.
Inheritance (Kalıtım)	SinemaFilmi → Film	Sinema filmi, film sınıfının özelliklerini miras alır.
Encapsulation (Kapsülleme)	private değişkenler ve get/set metotları	Veriler dış erişime karşı korunur.
Polymorphism (Çok Biçimlilik)	toString() metodu gibi override işlemleri	Aynı metodun farklı sınıflarda farklı davranması sağlanır.
Composition (Bileşim)	FilmArsivi içinde Film nesnelerinin tutulması	Nesnelerin bir arada yönetilmesi sağlanır.
🚀 Çalıştırma Talimatları

Tüm .java dosyalarını aynı dizinde bulundur.

Terminali aç ve şu komutları sırayla çalıştır:

javac *.java
java Main


Program açıldığında, film ekleme veya listeleme gibi seçenekleri kullanarak sistemi test edebilirsin.

🧠 Öğrenme Kazanımları

Bu proje ile şunlar öğrenilebilir:

Nesne tabanlı düşünme yaklaşımı

Sınıf ve nesne kavramları

Kalıtım ve polimorfizm mantığı

Java’da liste, dizi ve sınıf ilişkilerinin kurulması
