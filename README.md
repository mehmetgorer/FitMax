# FitMax - Spor Salonu Otomasyonu Web Uygulaması

FitMax, spor salonları için geliştirilmiş ASP.NET Core MVC tabanlı bir web otomasyon projesidir. Proje; kullanıcı üyeliği, salon paketleri, eğitmen yönetimi, özel ders süreçleri, ürün satışı, sepet, cüzdan ve admin paneli gibi temel spor salonu yönetim ihtiyaçlarını tek bir sistem altında toplamayı amaçlar.

Bu uygulama sadece bir tanıtım web sitesi değil; aynı zamanda üyelerin sisteme kayıt olabildiği, salon üyelik paketlerini inceleyebildiği, spor ürünlerini sepete ekleyip satın alma sürecini yönetebildiği, cüzdanına bakiye yükleyebildiği ve eğitmenlerle özel ders süreçlerini takip edebildiği kapsamlı bir spor salonu otomasyonudur.

## Proje Amacı

FitMax projesinin temel amacı, bir spor salonunun dijital ortamda hem müşteri tarafını hem de yönetim tarafını kontrol edebilmesini sağlamaktır.

Kullanıcı tarafında üyelik oluşturma, giriş yapma, ürünleri görüntüleme, ürünleri sepete ekleme, cüzdan bakiyesi yönetme, salon paketlerini inceleme ve kişisel profil bilgilerini takip etme gibi işlemler yapılabilir.

Admin tarafında ise üyeler, eğitmenler, ürünler, siparişler, salon paketleri ve yetkiler yönetilebilir. Böylece spor salonu yöneticileri sistemdeki kullanıcıları, satış süreçlerini, ürün stoklarını ve eğitmen işlemlerini merkezi bir panel üzerinden kontrol edebilir.

## Öne Çıkan Özellikler

- Kullanıcı kayıt ve giriş sistemi
- ASP.NET Identity ile kimlik doğrulama
- Rol bazlı kullanıcı yönetimi
- Admin paneli
- Üye yönetimi
- Eğitmen yönetimi
- Eğitmen fiyatı ve ders yönetimi
- Salon üyelik paketleri
- Ürün listeleme, arama ve kategori filtreleme
- Sepete ürün ekleme
- Sepette adet artırma / azaltma
- Sipariş tamamlama akışı
- Cüzdan sistemi
- Cüzdana bakiye yükleme
- Cüzdan hareketleri takibi
- Teslim edilen ve teslim edilmeyen sipariş takibi
- Kullanıcı profil sayfası
- Eğitmen profil ve bilgi güncelleme sayfası
- Admin tarafında ürün stok ve satış durumu yönetimi
- Admin tarafında sipariş teslimat takibi
- Admin tarafında salon paketleri yönetimi
- Admin tarafında yetki / rol yönetimi
- Dashboard üzerinde temel raporlama kartları

## Kullanıcı Modülleri

### Üyelik Sistemi

Kullanıcılar sisteme kayıt olabilir, giriş yapabilir ve kendi hesapları üzerinden işlem yapabilir. Kayıt olan kullanıcılar varsayılan olarak üye rolünde başlar. Admin paneli üzerinden gerekli durumlarda eğitmen veya admin yetkileri verilebilir.

### Ürün ve Sepet Sistemi

Kullanıcılar ürünler sayfasından spor ekipmanlarını ve sporcu besinlerini görüntüleyebilir. Ürünler kategoriye göre filtrelenebilir ve arama alanı üzerinden sorgulanabilir. Kullanıcılar ürünleri sepete ekleyebilir, sepette ürün adetlerini değiştirebilir ve sipariş sürecini tamamlayabilir.

### Cüzdan Sistemi

Kullanıcıların sistem içinde kullanabileceği bir cüzdan yapısı bulunmaktadır. Kullanıcılar cüzdanlarına bakiye yükleyebilir ve yapılan işlemleri hareketler tablosu üzerinden takip edebilir.

### Kullanıcı Profil Sayfası

Kullanıcı profil sayfasında paket bilgileri, fiziksel bilgiler, teslim edilen / teslim edilmeyen siparişler ve geçmiş / gelecek özel ders bilgileri görüntülenebilir.

### Eğitmen Sayfası

Eğitmen rolündeki kullanıcılar kendi eğitmen sayfalarına erişebilir. Bu sayfada kişisel açıklama, sosyal medya bilgileri ve profil fotoğrafı gibi bilgiler güncellenebilir. Ayrıca eğitmenle ilişkili sipariş ve özel ders bilgileri takip edilebilir.

## Admin Paneli

FitMax projesinde yönetim işlemleri için ayrı bir admin paneli bulunmaktadır. Admin paneli üzerinden spor salonunun temel operasyonları yönetilebilir.

Admin panelinde bulunan ana bölümler:

- Dashboard
- Eğitmenler
- Üyeler
- Ürünler
- Siparişler
- Salon paketleri
- Yetkiler / rol yönetimi

### Dashboard

Admin ana sayfasında aktif üye sayısı, son 14 günlük aktif ders sayısı ve toplam ürün stoğu gibi temel istatistikler görüntülenir. Ayrıca iletişim mesajları da tablo halinde listelenir.

### Eğitmen Yönetimi

Admin, sistemdeki eğitmenleri listeleyebilir, eğitmenlerin derslerini görüntüleyebilir, fiyatlarını düzenleyebilir, kazançlarını takip edebilir ve gerekli durumlarda eğitmen yetkisini kaldırabilir.

### Üye Yönetimi

Admin, sistemdeki üyeleri görüntüleyebilir. Üyelerin cüzdan bilgilerine erişebilir, aboneliklerini iptal edebilir, kullanıcıları pasifleştirebilir veya eğitmen rolüne geçirebilir.

### Ürün Yönetimi

Admin ürünleri listeleyebilir, yeni ürün ekleyebilir, ürün detaylarını görüntüleyebilir, ürünlerin satış durumunu takip edebilir ve ürün silebilir.

### Sipariş Yönetimi

Admin, teslim edilen ve teslim edilmeyen siparişleri ayrı tablolarda görüntüleyebilir. Teslim edilmeyen siparişler teslim edildi olarak işaretlenebilir. Teslim edilen siparişler için detay bilgileri görüntülenebilir.

### Salon Paketleri Yönetimi

Admin, salon üyelik paketlerini listeleyebilir, yeni paket tanımlayabilir, paketleri düzenleyebilir veya silebilir.

### Yetki Yönetimi

Admin, kullanıcıların rollerini yönetebilir. Kullanıcılar admin rolüne eklenebilir veya mevcut admin yetkileri kaldırılabilir.

## Kullanılan Teknolojiler

- ASP.NET Core MVC
- C#
- Entity Framework Core
- SQL Server
- ASP.NET Identity
- AutoMapper
- Dependency Injection
- Repository Pattern
- Unit of Work Pattern
- Razor Views
- HTML
- CSS
- JavaScript
- Bootstrap / Admin template yapısı

## Mimari Yapı

Proje katmanlı mimari yaklaşımıyla geliştirilmiştir. Katmanların birbirinden ayrılması sayesinde kodun bakımı, geliştirilmesi ve genişletilmesi daha kolay hale getirilmiştir.

Proje 4 ana katmandan oluşmaktadır:

### 1. Entity Katmanı

Uygulamadaki temel veri modelleri, entity sınıfları, view model yapıları ve servis arayüzleri bu katmanda yer alır.

Örnek entity yapıları:

- Product
- Cart
- CartLine
- Package
- Wallet
- WalletDetail
- PrivateLesson
- Contact

### 2. Data Access Katmanı

Veritabanı bağlantısı, DbContext, Identity kullanıcı sınıfları, repository yapıları, migration dosyaları ve Unit of Work işlemleri bu katmanda bulunur.

Bu katman, uygulamanın SQL Server veritabanı ile iletişimini yönetir.

### 3. Service Katmanı

İş kuralları ve uygulama servisleri bu katmanda yer alır. Controller tarafındaki işlemler doğrudan veritabanına bağlanmak yerine servisler üzerinden yönetilir.

Örnek servisler:

- AccountService
- ProductService
- CartService
- WalletService
- PackageService
- TrainerService
- PrivateLessonService
- ContactService

### 4. Presentation Katmanı

Kullanıcıya gösterilen MVC arayüzü bu katmanda bulunur. Controller, View, ViewComponent, static dosyalar ve uygulama başlangıç dosyaları bu katmanda yer alır.

## Proje Yapısı

```text
FitMax
├── Domains
│   └── FitMax.Entity
│       ├── Entities
│       ├── Interfaces
│       ├── IService
│       ├── UnitOfWorks
│       └── ViewModels
│
├── Infrastructures
│   ├── FitMax.DataAccess
│   │   ├── Contexts
│   │   ├── Identity
│   │   ├── Migrations
│   │   ├── Repositories
│   │   └── UnitOfWorks
│   │
│   └── FitMax.Service
│       ├── Extensions
│       ├── Mapping
│       └── Services
│
└── Presentation
    └── FitMax.Mvc
        ├── Controllers
        ├── Models
        ├── ViewComponents
        ├── Views
        ├── wwwroot
        ├── appsettings.json
        └── Program.cs
Veritabanı

Proje SQL Server veritabanı ile çalışmaktadır. Entity Framework Core Code First yaklaşımı ve migration yapısı kullanılarak veritabanı tabloları oluşturulmuştur.

Uygulamada kullanıcı ve rol yönetimi için ASP.NET Identity altyapısı kullanılmaktadır.

Not: Güvenlik nedeniyle gerçek veritabanı bağlantı bilgileri repoya eklenmemelidir. appsettings.json içinde örnek bir connection string bırakılmalı, gerçek bağlantı bilgileri local ortamda veya environment variable üzerinden yönetilmelidir.

Kurulum

Projeyi local ortamda çalıştırmak için aşağıdaki adımlar izlenebilir.

1. Repoyu klonlayın
git clone https://github.com/kullanici-adiniz/FitMax.git
cd FitMax
2. Veritabanı bağlantısını ayarlayın

Presentation/FitMax.Mvc/appsettings.json dosyasında connection string alanını kendi SQL Server bağlantınıza göre düzenleyin.

"ConnectionStrings": {
  "ConnStr": "Data Source=YOUR_SERVER;Initial Catalog=FitMaxKey;User ID=YOUR_USER;Password=YOUR_PASSWORD;TrustServerCertificate=true"
}
3. Migration işlemlerini çalıştırın

Package Manager Console veya terminal üzerinden migration işlemlerini çalıştırabilirsiniz.

dotnet ef database update
4. Projeyi çalıştırın
dotnet run --project Presentation/FitMax.Mvc

Uygulama local ortamda aşağıdaki benzer adreslerden çalışacaktır:

https://localhost:7193
http://localhost:5064
Ekran Görüntüleri
Ana Sayfa

Üyelik Sayfası

Ürünler

Sepet

Cüzdan

Kullanıcı Paneli

Admin Dashboard

Admin Ürün Yönetimi

Admin Sipariş Yönetimi

Admin Yetki Yönetimi

Geliştirici Notları

Bu proje eğitim ve portföy amacıyla geliştirilmiştir. Projede katmanlı mimari, servis yapısı, repository pattern, Unit of Work, ASP.NET Identity ve Entity Framework Core gibi backend geliştirme pratikleri uygulanmıştır.

Frontend tarafında kullanıcı ve admin işlemleri için Razor View yapısı kullanılmıştır. Admin paneli üzerinden temel yönetim işlemleri yapılabilirken, kullanıcı tarafında üyelik, ürün, sepet, cüzdan ve profil süreçleri yönetilebilmektedir.

FitMax - Gym Automation Web Application

FitMax is an ASP.NET Core MVC based gym automation web application. The project aims to manage both the customer-facing website and the administrative operations of a gym in a single system.

It includes user registration, authentication, membership packages, trainer management, private lesson tracking, product listing, shopping cart, wallet balance management, order tracking and an admin management panel.

Project Purpose

The main purpose of FitMax is to digitalize the core operations of a gym.

On the user side, members can register, log in, browse products, add products to the cart, manage their wallet balance, view gym packages and track their personal information.

On the admin side, gym managers can manage users, trainers, products, orders, gym packages and role permissions through a centralized admin panel.

Key Features
User registration and login
Authentication with ASP.NET Identity
Role-based user management
Admin dashboard
Member management
Trainer management
Trainer pricing and lesson management
Gym membership packages
Product listing, search and category filtering
Shopping cart operations
Increase / decrease product quantity in cart
Order completion flow
Wallet system
Add balance to wallet
Wallet transaction history
Delivered and undelivered order tracking
User profile page
Trainer profile update page
Product stock and sales status management
Order delivery management
Gym package management
Admin role management
Basic dashboard reporting
User Modules
Membership System

Users can register, log in and manage their accounts. Newly registered users start as standard members. Admins can assign trainer or admin roles when needed.

Product and Cart System

Users can browse fitness products and supplements, filter them by category and search products by name. Products can be added to the cart, quantities can be updated and the order process can be completed.

Wallet System

The application includes a wallet structure. Users can add balance to their wallets and track wallet transactions.

User Profile Page

The user profile page displays membership package information, physical information, delivered / undelivered orders and past / upcoming private lessons.

Trainer Page

Trainer users can access their own trainer page. They can update their description, social media links and profile image. Trainer-related orders and private lessons can also be tracked.

Admin Panel

FitMax includes a separate admin panel for management operations.

The admin panel includes:

Dashboard
Trainers
Members
Products
Orders
Gym packages
Roles / permissions
Dashboard

The dashboard displays basic statistics such as active member count, active private lessons in the last 14 days and total product stock. Contact messages are also listed in a table.

Trainer Management

Admins can list trainers, view trainer lessons, update trainer prices, track earnings and remove trainer permissions when necessary.

Member Management

Admins can view members, access wallet information, cancel subscriptions, deactivate users or assign trainer roles.

Product Management

Admins can list products, add new products, view product details, track stock and sales status and delete products.

Order Management

Admins can view delivered and undelivered orders in separate tables. Undelivered orders can be marked as delivered, and delivered orders can be inspected in detail.

Gym Package Management

Admins can list, create, update and delete gym membership packages.

Role Management

Admins can manage user roles by assigning or removing admin permissions.

Technologies Used
ASP.NET Core MVC
C#
Entity Framework Core
SQL Server
ASP.NET Identity
AutoMapper
Dependency Injection
Repository Pattern
Unit of Work Pattern
Razor Views
HTML
CSS
JavaScript
Bootstrap / Admin template structure
Architecture

The project was developed using a layered architecture approach. This structure makes the codebase easier to maintain, extend and test.

The project consists of 4 main layers:

1. Entity Layer

Contains entity models, view models, service interfaces and domain-related structures.

Example entities:

Product
Cart
CartLine
Package
Wallet
WalletDetail
PrivateLesson
Contact
2. Data Access Layer

Contains database context, Identity classes, repositories, migrations and Unit of Work implementation.

This layer manages communication with the SQL Server database.

3. Service Layer

Contains business logic and application services. Controllers communicate with this layer instead of directly accessing the database.

Example services:

AccountService
ProductService
CartService
WalletService
PackageService
TrainerService
PrivateLessonService
ContactService
4. Presentation Layer

Contains the ASP.NET Core MVC user interface. Controllers, views, view components, static files and application startup files are located in this layer.

Project Structure
FitMax
├── Domains
│   └── FitMax.Entity
│       ├── Entities
│       ├── Interfaces
│       ├── IService
│       ├── UnitOfWorks
│       └── ViewModels
│
├── Infrastructures
│   ├── FitMax.DataAccess
│   │   ├── Contexts
│   │   ├── Identity
│   │   ├── Migrations
│   │   ├── Repositories
│   │   └── UnitOfWorks
│   │
│   └── FitMax.Service
│       ├── Extensions
│       ├── Mapping
│       └── Services
│
└── Presentation
    └── FitMax.Mvc
        ├── Controllers
        ├── Models
        ├── ViewComponents
        ├── Views
        ├── wwwroot
        ├── appsettings.json
        └── Program.cs
Database

The project uses SQL Server as its database. Entity Framework Core migrations are used to create and update the database schema.

ASP.NET Identity is used for user and role management.

Note: Real database credentials should not be committed to the repository. Keep only a sample connection string in appsettings.json and manage real credentials locally or with environment variables.

Installation
1. Clone the repository
git clone https://github.com/your-username/FitMax.git
cd FitMax
2. Configure the database connection

Update the connection string in Presentation/FitMax.Mvc/appsettings.json.

"ConnectionStrings": {
  "ConnStr": "Data Source=YOUR_SERVER;Initial Catalog=FitMaxKey;User ID=YOUR_USER;Password=YOUR_PASSWORD;TrustServerCertificate=true"
}
3. Apply database migrations
dotnet ef database update
4. Run the project
dotnet run --project Presentation/FitMax.Mvc

The application will run locally on a similar address:

https://localhost:7193
http://localhost:5064
Screenshots
Home Page

Registration Page

Products

Cart

Wallet

User Panel

Admin Dashboard

Admin Product Management

Admin Order Management

Admin Role Management

Developer Notes

This project was developed for educational and portfolio purposes. It demonstrates layered architecture, service-based business logic, repository pattern, Unit of Work, ASP.NET Identity and Entity Framework Core usage in an ASP.NET Core MVC application.

The user interface was developed using Razor Views. The user side includes membership, product, cart, wallet and profile operations, while the admin side provides management features for users, trainers, products, orders, packages and roles.


README’ye koyacağın görseller için benim seçmem:

```txt
home.png                  → Ana sayfa hero
register.png              → Üyelik formu
products.png              → Ürün listeleme
cart.png                  → Sepet
wallet.png                → Cüzdan
user-panel.png            → Kullanıcı paneli
admin-dashboard.png       → Admin ana sayfa
admin-trainers.png        → Eğitmen yönetimi
admin-products.png        → Ürün yönetimi
admin-orders.png          → Sipariş yönetimi
admin-roles.png           → Yetki yönetimi
## Ekran Görüntüleri / Screenshots

### 1. Ana Sayfa
![Screenshot 1](Screenshots/1.png)

### 2. Ana Sayfa - İçerik Bölümü
![Screenshot 2](Screenshots/2.png)

### 3. Programlar Bölümü
![Screenshot 3](Screenshots/3.png)

### 4. Eğitmenler Bölümü
![Screenshot 4](Screenshots/4.png)

### 5. Salon Paketleri
![Screenshot 5](Screenshots/5.png)

### 6. Üyelik Sayfası
![Screenshot 6](Screenshots/6.png)

### 7. Kullanıcı Paneli
![Screenshot 7](Screenshots/7.png)

### 8. Ürünler Sayfası
![Screenshot 8](Screenshots/8.png)

### 9. Ürün Listeleme
![Screenshot 9](Screenshots/9.png)

### 10. Sepet
![Screenshot 10](Screenshots/10.png)

### 11. Cüzdana Bakiye Yükleme
![Screenshot 11](Screenshots/11.png)

### 12. Sipariş Geçmişi
![Screenshot 12](Screenshots/12.png)

### 13. Cüzdan Sayfası
![Screenshot 13](Screenshots/13.png)

### 14. Admin Dashboard
![Screenshot 14](Screenshots/14.png)

### 15. Admin Eğitmen Yönetimi
![Screenshot 15](Screenshots/15.png)

### 16. Admin Üye Yönetimi
![Screenshot 16](Screenshots/16.png)

### 17. Admin Ürün Yönetimi
![Screenshot 17](Screenshots/17.png)

### 18. Admin Sipariş Yönetimi
![Screenshot 18](Screenshots/18.png)

### 19. Admin Salon Paketleri
![Screenshot 19](Screenshots/19.png)

### 20. Admin Yetki Yönetimi
![Screenshot 20](Screenshots/20.png)

### 21. Eğitmen Profil Güncelleme
![Screenshot 21](Screenshots/21.png)

### 22. Şifre Yenileme
![Screenshot 22](Screenshots/22.png)
