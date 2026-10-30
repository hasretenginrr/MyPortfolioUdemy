# 💻 Personal Portfolio & Admin Dashboard

ASP.NET Core MVC kullanılarak geliştirilen bu proje, kişisel bilgilerin, teknik yetkinliklerin, iş deneyimlerinin ve projelerin ziyaretçilere sunulmasını sağlayan dinamik bir portfolyo web uygulamasıdır.

Projenin temel amacı, kişisel portfolyo içeriklerini statik sayfalar yerine veritabanı üzerinden yönetilebilir hale getirmek ve tüm içeriklerin tek bir yönetim panelinden kontrol edilmesini sağlamaktır.

## ✨ Öne Çıkan Özellikler

### 🌐 Ziyaretçi Arayüzü

- **Kişisel Tanıtım:** Hakkımda ve kişisel bilgiler bölümü.
- **Teknik Yetkinlikler:** Kullanılan teknolojilerin ve becerilerin listelenmesi.
- **Deneyimler:** İş ve staj deneyimlerinin dinamik olarak görüntülenmesi.
- **Proje Galerisi:** Geliştirilen projelerin görselleri, açıklamaları ve bağlantıları.
- **Referanslar:** Referans bilgilerinin sunulması.
- **İletişim:** Ziyaretçilerin mesaj bırakabileceği iletişim formu.
- **Responsive Tasarım:** Farklı ekran boyutlarına uyum sağlayan kullanıcı arayüzü.

### ⚙️ Yönetim Paneli

Portfolyo içeriklerinin merkezi bir noktadan yönetilebilmesi için geliştirilen admin paneli şu özellikleri içerir:

- **Dashboard:** Genel yönetim ekranı ve istatistikler.
- **Hakkımda Yönetimi:** Kişisel tanıtım bilgilerinin düzenlenmesi.
- **Deneyim Yönetimi:** Deneyim kayıtları üzerinde CRUD işlemleri.
- **Portfolyo Yönetimi:** Projelerin eklenmesi, düzenlenmesi ve silinmesi.
- **Yetenek Yönetimi:** Teknik becerilerin yönetilmesi.
- **Referans Yönetimi:** Referans bilgilerinin düzenlenmesi.
- **Sosyal Medya Yönetimi:** Sosyal medya bağlantılarının yönetilmesi.
- **Mesaj Yönetimi:** İletişim formundan gelen mesajların görüntülenmesi ve okundu / okunmadı durumlarının değiştirilmesi.

  ## Proje Resimleri
  <img width="1862" height="885" alt="Ekran görüntüsü 2026-10-30 182339" src="https://github.com/user-attachments/assets/84f831ff-6059-46a9-9d57-9e717290e269" />

  <img width="1861" height="800" alt="Ekran görüntüsü 2026-10-30 182412" src="https://github.com/user-attachments/assets/33c44a06-2ab8-43f8-9e9e-744da1cfb9e4" />

  <img width="1838" height="806" alt="Ekran görüntüsü 2026-10-30 182419" src="https://github.com/user-attachments/assets/ee89e608-4a13-4584-9a1b-1780cad35557" />

  <img width="1788" height="842" alt="Ekran görüntüsü 2026-10-30 182433" src="https://github.com/user-attachments/assets/745a5ea6-2969-4489-ad62-74bda640d879" />

  <img width="1917" height="896" alt="Ekran görüntüsü 2026-10-30 182458" src="https://github.com/user-attachments/assets/640bf632-6f5e-4a11-99e4-4665adfa1143" />

  <img width="1877" height="845" alt="Ekran görüntüsü 2026-10-30 182503" src="https://github.com/user-attachments/assets/e7f47b62-fd2c-4853-929b-41a2039615c3" />

  <img width="1882" height="872" alt="Ekran görüntüsü 2026-10-30 182515" src="https://github.com/user-attachments/assets/e07e85a9-5c60-4f8e-9fa7-af65a7fa90e3" />

  <img width="1877" height="872" alt="Ekran görüntüsü 2026-10-30 182533" src="https://github.com/user-attachments/assets/f1f20ec9-ba53-44b0-964e-b7a9896119d5" />


## 🛠️ Teknoloji ve Araçlar

| Teknoloji | Kullanım Amacı |
|---|---|
| C# | Backend geliştirme |
| ASP.NET Core MVC | Uygulama mimarisi |
| Entity Framework Core | Veritabanı işlemleri ve ORM |
| Microsoft SQL Server | İlişkisel veritabanı |
| LINQ | Veri sorgulama |
| HTML5 & CSS3 | Arayüz geliştirme |
| JavaScript | Dinamik kullanıcı etkileşimleri |
| Bootstrap | Responsive tasarım |

## 🏗️ Proje Mimarisi

Uygulama, MVC (Model-View-Controller) mimarisi temel alınarak geliştirilmiştir.

Proje içerisinde kullanılan temel yapılar:

- **Model:** Uygulamadaki verileri ve veri yapılarını temsil eder.
- **View:** Kullanıcıya sunulan arayüzleri oluşturur.
- **Controller:** Gelen istekleri karşılar ve uygulama akışını yönetir.
- **ViewComponent:** Tekrar kullanılabilir ve dinamik arayüz bileşenleri oluşturur.
- **Entity Framework Core:** Veritabanı ile uygulama arasındaki veri işlemlerini yönetir.

Bu yapı sayesinde kullanıcı arayüzü, uygulama mantığı ve veri işlemleri birbirinden ayrılarak daha düzenli bir proje yapısı oluşturulmuştur.

## 📸 Proje Görselleri

<!-- Buraya proje ekran görüntülerini ekleyebilirsiniz. -->

## 🚀 Kurulum ve Çalıştırma

Projeyi yerel ortamınızda çalıştırmak için aşağıdaki adımları takip edebilirsiniz.

**1. Repoyu klonlayın:**

```bash
git clone REPOSITORY_URL
```

**2. Proje dizinine geçin:**

```bash
cd MyPortfolioUdemy
```

**3. Veritabanı bağlantısını yapılandırın:**

`appsettings.json` dosyasındaki bağlantı dizesini kendi SQL Server ortamınıza göre düzenleyin.

**4. Veritabanını oluşturun:**

Entity Framework Core kullanarak migration işlemlerini uygulayın:

```bash
dotnet ef database update
```

**5. Uygulamayı çalıştırın:**

```bash
dotnet run
```

## 🎯 Projenin Amacı

Bu proje, ASP.NET Core MVC ekosistemindeki temel ve orta seviye geliştirme yaklaşımlarını uygulamalı olarak kullanmak, veritabanı destekli dinamik bir web uygulaması oluşturmak ve yönetilebilir bir kişisel portfolyo altyapısı geliştirmek amacıyla hazırlanmıştır.

---

**Geliştirici:** Hasret Nisa Enginer

**GitHub:** [hasretenginrr](https://github.com/hasretenginrr)

**Portfolio:** [hasretnisaenginer.com.tr](https://hasretnisaenginer.com.tr)
