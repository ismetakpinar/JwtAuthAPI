# JwtAuthAPI

ASP.NET Core 8 kullanılarak geliştirilmiş JWT Authentication ve Authorization API projesi.

## Proje Özellikleri

- Kullanıcı Kayıt Olma (Register)
- Kullanıcı Giriş Yapma (Login)
- BCrypt ile Şifre Hashleme
- JWT Token Üretimi
- Rol Bazlı Yetkilendirme (Admin / User)
- Swagger JWT Entegrasyonu
- Entity Framework Core
- SQL Server Veritabanı

## Kullanılan Teknolojiler

- ASP.NET Core 8
- Entity Framework Core
- SQL Server
- JWT Bearer Authentication
- BCrypt.Net
- Swagger (OpenAPI)

## Endpointler

### Kimlik Doğrulama İşlemleri

```http
POST /api/Auth/register
```

Yeni kullanıcı oluşturur.

```http
POST /api/Auth/login
```

Kullanıcı giriş yapar ve JWT Token döndürür.

### Yetkilendirme Testleri

```http
GET /api/Test/secure
```

Geçerli JWT Token gerektirir.

```http
GET /api/Test/admin
```

Sadece Admin rolündeki kullanıcılar erişebilir.

## JWT Yapısı

Proje içerisinde:

- Authentication (Kimlik Doğrulama)
- Authorization (Yetkilendirme)
- Claims
- Role Based Authorization

konuları uygulanmıştır.

## Güvenlik

- Kullanıcı şifreleri BCrypt kullanılarak hashlenmektedir.
- JWT Token doğrulama işlemleri yapılmaktadır.
- Rol bazlı erişim kontrolü uygulanmaktadır.

## Öğrenilen Konular

Bu proje kapsamında aşağıdaki konular uygulanmıştır:

- ASP.NET Core Web API
- Entity Framework Core
- SQL Server
- JWT Authentication
- JWT Authorization
- Claims
- Role Based Authorization
- BCrypt Password Hashing
- Swagger Authorization
- Dependency Injection (DI)

## Geliştirici

İsmet Akpınar
