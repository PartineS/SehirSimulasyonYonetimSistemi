# Şehir Yönetim Sistemi

Bu proje, şehir simülasyonu ve yönetimi için geliştirilmiş kapsamlı bir SQL veritabanı sistemidir.

## 📋 Proje Açıklaması

Şehir Yönetim Sistemi, modern bir şehrin çeşitli bileşenlerini ve hizmetlerini yönetmek için tasarlanmış bir veritabanı sistemidir. Bu sistem şehir planlaması, altyapı yönetimi ve vatandaş hizmetlerini kapsamlı bir şekilde yönetmek için kullanılabilir.

## 🏗️ Veritabanı Yapısı

Sistem aşağıdaki ana bileşenleri içerir:

### 🚗 Ulaşım ve Trafik
- **Otoparklar**: Şehirdeki otopark bilgileri ve kapasiteleri
- **Araclar**: Kayıtlı araç bilgileri
- **TopluTasimaAraclari**: Otobüs, metro vb. toplu taşıma araçları
- **Feribotlar**: Su ulaşımı için feribot bilgileri
- **İskeleler**: Feribot iskelesi lokasyonları
- **Rotalar**: Ulaşım rotaları
- **TrafikCezalari**: Trafik ceza kayıtları

### 🏥 Sağlık Sistemi
- **Hastaneler**: Şehirdeki hastane bilgileri
- **Hastalar**: Hasta kayıtları
- **HastaKayitlari**: Hastane başvuru ve tedavi kayıtları

### 🎓 Eğitim Sistemi
- **Okullar**: Okul bilgileri (Binalar tablosu içinde)
- **Ogrenciler**: Öğrenci kayıtları

### 📚 Kültür ve Sosyal Hizmetler
- **Kutuphaneler**: Kütüphane bilgileri
- **KutuphaneKullanicilari**: Kütüphane üye kayıtları

### 🏢 Şehir Yönetimi
- **Sehirler**: Şehir bilgileri
- **Ilceler**: İlçe bilgileri
- **Binalar**: Şehirdeki bina kayıtları
- **Calisanlar**: Belediye çalışanları
- **IsYerleri**: İş yeri kayıtları

### 🛡️ Güvenlik
- **SucKayitlari**: Suç kayıtları ve güvenlik verileri

### ⚡ Altyapı
- **AltyapiHizmetleri**: Su, elektrik, doğalgaz vb. altyapı hizmetleri

## 📊 Views ve Raporlar

- **OtoparkUcretleri**: Otopark ücretlerinin hesaplanması için görünüm

## 🚀 Kullanım

1. SQL Server Management Studio veya benzeri bir veritabanı yönetim aracında `sehiryönetimsistemi.sql` dosyasını çalıştırın
2. Veritabanı ve tablolar otomatik olarak oluşturulacaktır
3. Sistem şehir yönetimi verilerini kaydetmek ve analiz etmek için hazır hale gelecektir

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