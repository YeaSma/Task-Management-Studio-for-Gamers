# Task-Management-Studio-for-Gamers
Bu proje, bir oyuncu grubunun kendi içindeki iş akışını, görev dağılımlarını ve iş ilerlemelerini dinamik olarak yönetebilmesi, ekip üyelerinin birbirleriyle iş birliği içinde çalışabilmesi amacıyla geliştirilmiş web tabanlı bir yönetim sistemidir.

## 🚀 Proje Tanıtım Videosu
Ekampüs proje gönderim kriterlerine uygun olarak hazırlanan, uygulamanın tüm fonksiyonlarını ve işleyişini anlatan tanıtım videosuna aşağıdaki bağlantıdan ulaşabilirsiniz:

▶️ [Proje Tanıtım Videosu](https://youtu.be/Y3pl5CxdU-I)

## 📸 Uygulama Ekran Görüntüleri

<img width="1917" height="912" alt="register" src="https://github.com/user-attachments/assets/a7428ca6-4134-4ee0-878a-ff01117b9266" />

<img width="1918" height="912" alt="login" src="https://github.com/user-attachments/assets/bc5a4223-cfdc-4405-8b42-0db92379e87d" />

<img width="1917" height="917" alt="main_menu" src="https://github.com/user-attachments/assets/c76bffa8-9b0b-441e-b922-f75140d03acd" />

<img width="1918" height="907" alt="edit" src="https://github.com/user-attachments/assets/a1d9d317-2994-4953-ba34-927908e34e32" />


## ✨ Özellikler

* **Kullanıcı Yönetimi:** Güvenli kullanıcı kaydı, Bcrypt altyapılı şifreli giriş ile oturum açma ve kapama işlemleri.
* **Gelişmiş Görev Yönetimi (CRUD):** Ekip liderleri veya üyeleri tarafından yeni görevlerin oluşturulması, detaylı açıklamaların girilmesi, öncelik ve durum güncellemelerinin yapılması ile görevlerin silinebilmesi.
* **Ekip İçi İş Birliği ve Davet Sistemi:** Görevlerin altına diğer ekip üyelerini ortak (katılımcı) olarak davet edebilme, davetlerin anlık onay/ret süreçleri.
* **Dinamik Karanlık Mod (Dark Mode):** Tarayıcı yerel depolaması (localStorage) ile entegre çalışan, kullanıcı tercihini hafızada tutan göz yormayan gece teması.
* **Gelişmiş UI/UX Dokunuşları:** Uzun metinlerin tabloda taşmasını engelleyen `text-truncate` yapısı, üzerine gelindiğinde açılan ipucu kutucukları (tooltip), işletim sisteminden bağımsız modern kaydırma çubukları (scrollbar) ve bütünleşik form odaklanma (focus) tasarımları.

## 🛠️ Kullanılan Teknolojiler

* **Backend:** Yalın PHP (Herhangi bir harici kütüphane veya framework kullanılmamıştır)
* **Database:** MySQL 
* **Frontend:** HTML5, CSS3, BootStrap 5, JavaScript (Vanilla JS)

## 💻 Kurulum ve Lokal Çalıştırma

1. Bu depoyu (repository) bilgisayarınıza klonlayın veya ZIP olarak indirin.
2. Klasörü yerel sunucunuzun (XAMPP, WampServer vb.) `htdocs` veya `www` dizinine taşıyın.
3. Tarayıcınızdan `phpMyAdmin` paneline giriş yapın ve `wtp_proje` adında bir veritabanı oluşturun.
4. Proje klasöründe yer alan SQL veritabanı şemasını oluşturduğunuz veritabanına aktarın (import edin).
5. `db.php` dosyasını açarak yerel veritabanı bağlantı ayarlarınızı (host, kullanıcı adı, şifre) kontrol edin.
6. Tarayıcınızın adres çubuğuna `http://localhost/wtp_proje` yazarak uygulamayı çalıştırmaya başlayabilirsiniz.
