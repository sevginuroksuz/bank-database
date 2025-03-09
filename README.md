# Banka Veri Tabanı Yönetim Sistemi

Bu proje, bankacılık işlemlerinin güvenli ve hızlı bir şekilde yürütülmesini sağlamak amacıyla geliştirilmiş bir **Banka Veri Tabanı Yönetim Sistemi**dir. Müşteriler, hesaplar, şubeler ve işlemler arasındaki ilişkileri düzenli bir yapıda saklamayı hedefler.

## 📌 Proje Tanımı

Banka veri tabanı, **müşteriler, şubeler, hesaplar ve varlıklar** gibi önemli finansal bileşenleri kapsar. Bankacılık sektöründe **güvenlik, hız ve erişilebilirlik** kritik öneme sahiptir. Bu proje, veri tabanı yönetimini optimize ederek işlemlerin **güvenli ve verimli bir şekilde** gerçekleşmesini sağlar.

## 📋 Özellikler

- **Müşteri ve hesap yönetimi** (Bireysel ve ortak hesaplar desteklenir)
- **Şube ve ATM ilişkileri** (Bir şube birden fazla ATM'ye sahip olabilir)
- **İşlem yönetimi** (Transferler, ödemeler ve kredi işlemleri gibi çeşitli finansal işlemler)
- **Yetkilendirme ve güvenlik** (Kullanıcı girişleri ve güvenlik soruları ile koruma)
- **Varlık-İlişki (ER) Diyagramları** (Chen ve Kazayağı modelleri kullanılmıştır)
- **İlişkisel Şema** (MySQL Workbench ile tersine mühendislik yapılarak oluşturulmuştur)

## 🏗 Kullanılan Teknolojiler

- **Veritabanı Yönetim Sistemi:** MySQL
- **Modelleme:** Chen Diyagramı & Kazayağı Modeli
- **Güvenlik:** Yetkilendirme sistemleri, güvenlik soruları ve şifreleme yöntemleri
- **Veri Tabanı Yönetimi:** SQL sorguları ve tablolar arası ilişkiler

## 📁 Veritabanı Şeması

Projenin veritabanı şeması aşağıdaki temel tabloları içerir:

- **Müşteriler (MUSTERI)**
- **Hesaplar (HESAP)**
- **Şubeler (SUBE)**
- **İşlemler (ISLEM)**
- **ATM'ler (ATM)**
- **Kullanıcı Yetkilendirme (KULLANICI_GIRIS, KULLANICI_GUVENLIK_SORU)**

İlişkiler detaylı şekilde **ER Diyagramı ve ilişkisel şema** ile ifade edilmiştir.

## 🚀 Kurulum

Projeyi çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

1. **MySQL Server** ve **Workbench** kurulu olmalıdır.
2. `banka_veritabani.sql` dosyasını MySQL'e aktarın.
3. SQL sorgularını çalıştırarak veritabanını oluşturun.
4. Yetkilendirme ve veri güvenliği için kullanıcı tablolarını güncelleyin.
5. Sistemi test etmek için örnek veri ekleyerek sorguları deneyin.

## 📜 İş Kuralları

- Bir müşteri **birden fazla hesaba sahip olabilir** (ortak hesap desteği)
- Bir hesap **birden fazla müşteriye ait olabilir**
- Bir şubenin **birden fazla ATM'si olabilir**
- Bir şubenin **birden fazla yöneticisi olabilir**
- Her işlem **bir müşteri hesabına bağlıdır**
- Güvenlik nedeniyle **şifreler ve kritik bilgiler ayrı tablolarda tutulur**

## 📚 Kaynakça

- [ER Diagram for Banking System - Tutorial](https://www.tutorialandexample.com/er-diagram-for-banking-system-in-dbms)
- [Database Schema Examples](https://www.scaler.com/topics/er-diagram-for-bank-database/)
- [GitHub - Online Banking Systems](https://github.com/yash2003shah/Online-Banking-System)

## ✨ Katkıda Bulunma

Projeye katkıda bulunmak isterseniz **pull request** açabilir veya **issue** oluşturarak önerilerinizi paylaşabilirsiniz. 🎯

---

**📌 Hazırlayan:**  
👩‍💻 **Sevgi Nur Öksüz**  
📅 **2023**  
📌 **Bursa Teknik Üniversitesi - Bilgisayar Mühendisliği**
