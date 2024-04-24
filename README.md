# Patika Turizm Acente Otomasyon Sistemi

Bu proje, Patika Turizm Acentesi'nin günlük operasyonlarını dijitalleştirmek ve müşteri rezervasyon süreçlerini optimize etmek amacıyla geliştirilmiş bir otomasyon sistemidir. Sistem, admin ve acente çalışanı olmak üzere iki farklı kullanıcı türünü desteklemektedir.

## Kullanılan Teknolojiler

- Java programlama dili
- Swing GUI kütüphanesi
- MySQL veritabanı

## Kurulum

1. Projenin GitHub deposunu klonlayın:

```
git clone https://github.com/Ceiberon/TurizimAcentaSistemi.git
```

2. MySQL veritabanını oluşturun ve `db.sql` dosyasındaki tabloları içe aktarın.

3. Proje dosyalarını Java geliştirme ortamınızda (IDE) açın.

4. Veritabanı bağlantı ayarlarınızı `DatabaseConnection.java` dosyasında güncelleyin.

5. Projeyi çalıştırın.

## Özellikler

### Admin

- Yeni kullanıcı ekleme, silme, güncelleme
- Kullanıcıların rollerine göre filtreleme
- Acente çalışanlarını listeleme

### Acente Çalışanı (Personel)

- Otel ekleme, listeleme
- Oda ekleme, listeleme
- Dönem ekleme, listeleme
- Fiyat yönetimi
- Oda arama
- Rezervasyon işlemleri

## Veritabanı Yapısı

- **user**: Admin ve personel kullanıcı bilgilerini içerir.
- **otel**: Otellerin bilgilerini içerir.
- **season**: Otellere ait sezon bilgilerini içerir.
- **pension_type**: Otellere ait pansiyon tiplerini içerir.
- **room**: Otellere ait oda bilgilerini içerir.
- **reservation**: Rezervasyon bilgilerini içerir.

Proje tanıtım videosu:
https://www.youtube.com/watch?v=OOSJdJ8kkv0
admin panel girişi :
Emirhan
3707
employee giriş paneli
ASDAS
ASDAS
