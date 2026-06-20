# 📚 Kütüphane Yönetim Sistemi

Java ve MySQL kullanılarak geliştirilmiş masaüstü tabanlı bir Kütüphane Yönetim Sistemi uygulamasıdır. Bu proje sayesinde kitapların, öğrencilerin ve ödünç alma işlemlerinin merkezi bir sistem üzerinden yönetilmesi amaçlanmıştır.

## 🚀 Proje Hakkında

Kütüphanelerde gerçekleştirilen temel işlemleri dijital ortama taşımak amacıyla geliştirilmiştir. Sistem; kitap ekleme, öğrenci yönetimi, kitap ödünç verme ve iade işlemlerini kolaylaştırarak kütüphane süreçlerinin daha verimli şekilde yönetilmesini sağlar.

Uygulama Java Swing teknolojisi kullanılarak geliştirilmiş olup veriler MySQL veritabanında saklanmaktadır.

---

## ✨ Özellikler

### Kullanıcı Yönetimi
- Kullanıcı kayıt olma
- Kullanıcı giriş sistemi
- Kimlik doğrulama işlemleri

### Kitap Yönetimi
- Yeni kitap ekleme
- Kitap bilgilerini güncelleme
- Kitap silme
- Kitap stok takibi
- Tüm kitapları görüntüleme

### Öğrenci Yönetimi
- Öğrenci kayıt işlemleri
- Öğrenci bilgilerini güncelleme
- Öğrenci silme
- Öğrenci listeleme

### Ödünç Alma Sistemi
- Kitap ödünç verme
- Teslim tarihi belirleme
- Kitap iade işlemleri
- Aktif ödünç kayıtlarını görüntüleme

### Raporlama
- Tüm ödünç alma kayıtlarını görüntüleme
- Gecikmiş kitapları listeleme
- Sistem istatistiklerini görüntüleme
- Grafik destekli yönetim paneli

---

## 🛠️ Kullanılan Teknolojiler

- Java
- Java Swing
- MySQL
- JDBC
- NetBeans IDE
- JFreeChart
- Git & GitHub

---

## 🗄️ Veritabanı Yapısı

Projede MySQL veritabanı kullanılmaktadır.

Başlıca tablolar:

- users
- student_details
- book_details
- issue_book_details

Bu tablolar sayesinde kullanıcı, öğrenci, kitap ve ödünç alma işlemleri yönetilmektedir.

---

## 📂 Proje Mimarisi

```text
src/
│
├── JFrame/
│   ├── LoginPage
│   ├── SignUpPage
│   ├── HomePage
│   ├── ManageBooks
│   ├── ManageStudent
│   ├── IssueBook
│   ├── ReturnBook
│   ├── ViewAllRecord
│   ├── DefaulterList
│   └── DBConnection
│
└── library_management_system/
    └── Main
```

---

## ⚙️ Kurulum

### 1. Projeyi Klonlayın

```bash
git clone https://github.com/kullaniciadi/library-management-system.git
```

### 2. Veritabanını Oluşturun

MySQL üzerinde aşağıdaki isimde bir veritabanı oluşturun:

```sql
CREATE DATABASE library_ms;
```

Gerekli tabloları oluşturduktan sonra proje ile bağlantıyı sağlayabilirsiniz.

### 3. Veritabanı Bağlantısını Düzenleyin

`DBConnection.java` dosyasında bulunan bağlantı bilgilerini kendi MySQL ayarlarınıza göre güncelleyin.

```java
jdbc:mysql://localhost:3306/library_ms
```

### 4. Projeyi Çalıştırın

Projeyi NetBeans IDE üzerinden açarak çalıştırabilirsiniz.

---

## 🎯 Projenin Amacı

Bu proje;

- Nesne yönelimli programlama prensiplerini uygulamak,
- Veritabanı yönetimi konusunda deneyim kazanmak,
- Java Swing ile masaüstü uygulama geliştirmek,
- JDBC kullanarak veritabanı işlemlerini yönetmek,
- Gerçek dünyadaki kütüphane süreçlerini dijitalleştirmek

amacıyla geliştirilmiştir.

---

## 🔒 Gelecekte Yapılması Planlanan Geliştirmeler

- Rol bazlı yetkilendirme sistemi
- Barkod desteği
- Kitap arama ve filtreleme
- E-posta bildirim sistemi
- REST API entegrasyonu
- Docker desteği
- Web tabanlı sürüm geliştirilmesi

---

