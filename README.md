# Web Project Backend

Bu proje, kullanıcıların market ürünlerini kategori bazında görüntüleyip online sipariş verebileceği bir platform olarak tasarlanmıştır. 
Platform, kullanıcı dostu bir deneyim sağlamak için modern web teknolojileriyle geliştirilmiştir.

## 📁 İçerik

- [🚀 Özellikler](#-özellikler)
- [🔧 Kurulum](#-kurulum)
- [📖 Kullanım](#-kullanımı)
- [📂 Dosya Yapısı](#-dosya-yapısı)
- [📜 Lisans](#-lisans)

---

## 🚀 Özellikler

- RESTful API ile veri yönetimi
- Kullanıcı yönetimi (kimlik doğrulama ve yetkilendirme)
- Sipariş ve ürün yönetimi
- Kategori ve kampanya API'leri
- Teslimat takibi ve kurye yönetimi
- Veritabanı ve medya dosyaları için Strapi CMS entegrasyonu

---

## 🔧 Kurulum

### Gereksinimler

- Node.js (>= 14.x)
- NPM veya Yarn paket yöneticisi
- PostgreSQL (veya başka bir veritabanı)

### Adımlar

1. Projeyi klonlayın:
   ```bash
   git clone https://github.com/gokaydervisoglu/web_backend.git
   cd web_backend
   ```
2. Bağımlılıkları yükleyin:
    ```bash
   npm install
   npm run build
   ```
3. Uygulamayı Başlatın:
    ```bash
   npm run develop
   ```
4. Uygulama, tarayıcınızda http://localhost:1337 adresinde çalışacaktır.

---

## 📖 Kullanımı

Uygulama aşağıdaki ana sayfalardan oluşmaktadır:

- Kullanıcı Yönetimi: Kayıt, giriş, yetkilendirme.
- Ürün Yönetimi: Ürünlerin listelenmesi, eklenmesi, düzenlenmesi ve silinmesi.
- Sipariş Yönetimi: Sipariş oluşturma ve takibi.
- Kategori ve Kampanyalar: API üzerinden dinamik yönetim.
- Teslimat Yönetimi: Kuryelerin görevlerini takip etmesi ve güncellemesi.

---

## 📂 Dosya Yapısı
 ```bash
web_backend/
├── config/                  # Yapılandırma dosyaları
│   ├── database.ts          # Veritabanı yapılandırması
│   ├── server.ts            # Sunucu yapılandırması
├── src/
│   ├── api/                 # API ile ilgili modüller
│   │   ├── product/         # Ürün yönetimi
│   │   ├── order/           # Sipariş yönetimi
│   │   ├── user/            # Kullanıcı yönetimi
│   │   └── ...              # Diğer modüller
│   ├── extensions/          # Strapi genişletmeleri
│   ├── admin/               # Yönetici paneli ayarları
│   └── index.ts             # Giriş noktası
├── public/                  # Medya dosyaları
├── .env                     # Çevre değişkenleri
├── package.json             # Proje bağımlılıkları
└── README.md                # Proje dokümantasyonu
  ```
---

## 📜 Lisans
Bu proje MIT Lisansı ile lisanslanmıştır.

  

