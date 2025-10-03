# Şehir Simülasyon Yönetim Sistemi

Bu proje, şehir simülasyonu ve yönetimi için geliştirilmiş kapsamlı bir SQL veritabanı sistemidir.

## 📋 Proje Açıklaması

Şehir Simülasyon Yönetim Sistemi, modern bir şehrin çeşitli bileşenlerini ve hizmetlerini yönetmek için tasarlanmış bir veritabanı sistemidir. Bu sistem şehir planlaması, altyapı yönetimi ve vatandaş hizmetlerini kapsamlı bir şekilde yönetmek için kullanılabilir.

## 🏗️ Veritabanı Yapısı

Sistem aşağıdaki ana bileşenleri içerir:

### 🚗 Ulaşım ve Trafik
- **Otoparklar**: Şehirdeki otopark bilgileri ve kapasiteleri
- **Araçlar**: Kayıtlı araç bilgileri
- **TopluTaşımaAraçları**: Otobüs, metro vb. toplu taşıma araçları
- **Feribotlar**: Su ulaşımı için feribot bilgileri
- **İskeleler**: Feribot iskelesi lokasyonları
- **Rotalar**: Ulaşım rotaları
- **TrafikCezaları**: Trafik ceza kayıtları

### 🏥 Sağlık Sistemi
- **Hastaneler**: Şehirdeki hastane bilgileri
- **Hastalar**: Hasta kayıtları
- **HastaKayıtları**: Hastane başvuru ve tedavi kayıtları

### 🎓 Eğitim Sistemi
- **Okullar**: Okul bilgileri (Binalar tablosu içinde)
- **Öğrenciler**: Öğrenci kayıtları

### 📚 Kültür ve Sosyal Hizmetler
- **Kütüphaneler**: Kütüphane bilgileri
- **KütüphaneKullanıcıları**: Kütüphane üye kayıtları

### 🏢 Şehir Yönetimi
- **Şehirler**: Şehir bilgileri
- **İlçeler**: İlçe bilgileri
- **Binalar**: Şehirdeki bina kayıtları
- **Çalışanlar**: Belediye çalışanları
- **İşYerleri**: İş yeri kayıtları

### 🛡️ Güvenlik
- **SuçKayıtları**: Suç kayıtları ve güvenlik verileri

### ⚡ Altyapı
- **AltyapıHizmetleri**: Su, elektrik, doğalgaz vb. altyapı hizmetleri

## 📊 Views ve Raporlar
- **OtoparkUcretleri**: Otopark ücretlerinin hesaplanması için görünüm

## 🖼️ Veritabanı Diyagramları

### Crowsfoot Notasyonu
Veritabanındaki tablolar ve ilişkiler Crowsfoot notasyonu ile gösterilmiştir:

![Crowsfoot Notation](https://i.imgur.com/2UMpO2W.png)

### ER Diyagramı
Genel veritabanı ilişkilerini gösteren ER diyagramı:

![ER Diagram](https://i.imgur.com/6OnRuP5.png)

## 🚀 Kullanım
1. SQL Server Management Studio veya benzeri bir veritabanı yönetim aracında `Sehir Simulasyon Yonetim Sistemi.sql` dosyasını çalıştırın.
2. Veritabanı ve tablolar otomatik olarak oluşturulacaktır.
3. Sistem şehir simülasyonu ve yönetimi verilerini kaydetmek ve analiz etmek için hazır hale gelecektir.

## 💻 Teknik Özellikler
- **Veritabanı**: Microsoft SQL Server
- **Uyumluluk Seviyesi**: 160 (SQL Server 2019+)
- **Karakter Kodlaması**: Türkçe karakterler desteklenir
- **Veri Bütünlüğü**: Foreign key kısıtlamaları ile veri tutarlılığı sağlanır

## 📝 Lisans
Bu proje açık kaynak kodludur ve MIT lisansı altında dağıtılmaktadır.

## 👨‍💻 Geliştirici
Proje geliştirilme aşamasında olup, katkıda bulunmak isteyenler için açıktır.

---

*Bu proje Türkiye'deki şehir yönetimi ihtiyaçları göz önünde bulundurularak geliştirilmiştir.*
