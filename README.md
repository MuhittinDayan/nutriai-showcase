<p align="center">
  <img src="assets/icon.png" alt="NutriAI Logo" width="120">
</p>

<h1 align="center">NutriAI</h1>

<p align="center">
  Yapay zekâ destekli fitness ve beslenme mobil uygulaması
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-iOS%20%7C%20Android-2D5016" alt="Platform">
  <img src="https://img.shields.io/badge/Status-Private%20Source-C8A84B" alt="Private Source">
  <img src="https://img.shields.io/badge/Showcase-Public-198AC7" alt="Showcase">
</p>

## Proje Hakkında

NutriAI; beslenme takibi, egzersiz kaydı, su tüketimi, kilo değişimi, haftalık analizler ve yapay zekâ destekli kişisel önerileri tek bir mobil deneyimde birleştiren cross-platform bir sağlık uygulamasıdır.

Bu repository, NutriAI için hazırlanmış **public tanıtım reposudur**. Uygulamanın kaynak kodu, backend yapısı, veritabanı migration dosyaları, iş kuralları ve gizli anahtarları güvenlik ve fikri mülkiyet nedeniyle private tutulmaktadır.

## Ürün Kapsamı

NutriAI, kullanıcının sağlık hedeflerine göre kişiselleştirilmiş takip ve öneri deneyimi sunar. Uygulama; günlük öğün kayıtlarını, su tüketimini, egzersizleri, kilo ilerlemesini ve haftalık sağlık trendlerini tek merkezden yönetir. Yapay zekâ tarafında yemek görseli analizi, haftalık içgörü üretimi ve plan önerileri için güvenli bir backend akışı kullanılmıştır.

## Öne Çıkan Özellikler

- Yapay zekâ destekli yemek analizi ve kalori/makro tahmini
- Kişiselleştirilmiş beslenme planı ve öğün önerileri
- USDA FoodData Central tabanlı besin arama deneyimi
- Egzersiz kaydı, aktif antrenman akışı ve kalori hesabı
- Günlük su takibi ve haftalık tüketim özeti
- Kilo kaydı, grafikler ve hedef bazlı ilerleme analizi
- Haftalık analiz ekranı ve yapay zekâ destekli öneriler
- Bildirimler, haftalık kontrol akışı ve motivasyon kartları
- Android Health Connect ile adım verisi entegrasyonu
- Premium erişim, deneme süreci ve yapay zekâ kullanım kotası

## Teknoloji Stack'i

| Alan | Teknolojiler |
| --- | --- |
| Mobil | React Native, Expo, Expo Router |
| Dil | TypeScript |
| Backend | Supabase Auth, PostgreSQL, Supabase Edge Functions |
| Yapay Zekâ | Gemini API |
| Veri Yönetimi | TanStack Query |
| Besin Verisi | USDA FoodData Central API |
| Abonelik | RevenueCat |
| Bildirim | Expo Notifications |
| Sağlık Verisi | React Native Health Connect |
| Build | EAS Build |

## Ekran Görüntüleri

<table>
  <tr>
    <td align="center"><strong>Dashboard</strong><br><img src="assets/screenshots/dashboard2.jpg" alt="Dashboard" width="180"></td>
    <td align="center"><strong>Öğün Takibi</strong><br><img src="assets/screenshots/meal.jpg" alt="Öğün Takibi" width="180"></td>
    <td align="center"><strong>AI Kamera</strong><br><img src="assets/screenshots/aicamera.jpg" alt="AI Kamera" width="180"></td>
  </tr>
  <tr>
    <td align="center"><strong>Analiz Sonucu</strong><br><img src="assets/screenshots/analizsonucu.jpg" alt="Analiz Sonucu" width="180"></td>
    <td align="center"><strong>Egzersiz</strong><br><img src="assets/screenshots/exercise.jpg" alt="Egzersiz" width="180"></td>
    <td align="center"><strong>Su Takibi</strong><br><img src="assets/screenshots/water.jpg" alt="Su Takibi" width="180"></td>
  </tr>
  <tr>
    <td align="center"><strong>Kilo Takibi</strong><br><img src="assets/screenshots/weight.jpg" alt="Kilo Takibi" width="180"></td>
    <td align="center"><strong>Profil Menüsü</strong><br><img src="assets/screenshots/profile2.jpg" alt="Profil Menüsü" width="180"></td>
    <td align="center"><strong>Haftalık Analizler</strong><br><img src="assets/screenshots/analytics.png" alt="Haftalık Analizler" width="180"></td>
  </tr>
  <tr>
    <td align="center"><strong>Ana Plan</strong><br><img src="assets/screenshots/dashboard.jpg" alt="Ana Plan" width="180"></td>
    <td align="center"><strong>AI İçgörüleri</strong><br><img src="assets/screenshots/aisuggestion.jpg" alt="AI İçgörüleri" width="180"></td>
    <td align="center"><strong>Profil Özeti</strong><br><img src="assets/screenshots/profile.jpg" alt="Profil Özeti" width="180"></td>
  </tr>
</table>

## Mimari Yaklaşım

NutriAI'de mobil istemci; kullanıcı deneyimi, ekran akışları ve state yönetiminden sorumludur. Kimlik doğrulama, veritabanı işlemleri, güvenli yapay zekâ geçidi, kota kontrolü ve abonelik doğrulama gibi hassas süreçler backend tarafında yönetilir.

```mermaid
flowchart LR
    A[React Native Mobil Uygulama] --> B[Supabase Auth]
    A --> C[PostgreSQL Veritabanı]
    A --> D[Supabase Edge Function]
    D --> E[Gemini API]
    D --> F[RevenueCat Doğrulama]
    A --> G[USDA FoodData Central]
    A --> H[Health Connect]
```

## Repository Kapsamı

Bu repository yalnızca ürün tanıtımı ve portfolyo sunumu amacıyla hazırlanmıştır. Aşağıdaki içerikler public olarak paylaşılmaz:

- Kaynak kodu
- `.env` dosyaları
- API anahtarları
- Supabase migration dosyaları
- Edge Function kaynak kodu
- Veritabanı şeması ve RLS policy detayları
- Abonelik veya yapay zekâ kota iş kuralları

## Demo

Demo video/GIF bağlantısı eklendiğinde bu alanda paylaşılacaktır.

```text
Demo: yakında eklenecek
```

## Fikri Mülkiyet

NutriAI; tasarım, ürün fikri, ekran görüntüleri, marka adı ve uygulama kapsamı dahil olmak üzere Muhittin Dayan tarafından geliştirilmiş özel bir projedir. Bu repository'de yer alan materyaller yalnızca portfolyo ve tanıtım amacıyla görüntülenebilir.

Kaynak kodu ve uygulamanın ticari/teknik içeriği için herhangi bir kullanım, kopyalama, dağıtma, yeniden üretme veya türev çalışma izni verilmemektedir.

## Geliştirici

**Muhittin Dayan**

© 2026 Muhittin Dayan. Tüm hakları saklıdır.
