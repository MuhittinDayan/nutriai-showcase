# NutriAI

**Yapay zekâ destekli fitness ve beslenme mobil uygulaması**

NutriAI; beslenme takibi, egzersiz kaydı, su tüketimi, kilo değişimi, haftalık analizler ve yapay zekâ destekli kişisel önerileri tek bir mobil deneyimde birleştiren cross-platform bir sağlık uygulamasıdır.

> Bu repository, NutriAI projesi için hazırlanmış public tanıtım reposudur. Uygulamanın kaynak kodu, backend yapısı, veritabanı migration dosyaları ve gizli anahtarları güvenlik nedeniyle private tutulmaktadır.

## Proje Özeti

NutriAI, kullanıcının sağlık hedeflerine göre kişiselleştirilmiş takip ve öneri deneyimi sunar. Uygulamada kullanıcı; günlük öğünlerini, su tüketimini, egzersizlerini, kilosunu ve haftalık ilerlemesini takip edebilir. Yapay zekâ tarafında yemek görseli analizi, haftalık içgörü üretimi ve plan önerileri için güvenli bir backend akışı kullanılmıştır.

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

| Dashboard | Öğün Takibi | AI Kamera |
| --- | --- | --- |
| ![Dashboard](assets/screenshots/dashboard2.jpg) | ![Öğün Takibi](assets/screenshots/meal.jpg) | ![AI Kamera](assets/screenshots/aicamera.jpg) |

| Analiz Sonucu | Egzersiz | Su Takibi |
| --- | --- | --- |
| ![Analiz Sonucu](assets/screenshots/analizsonucu.jpg) | ![Egzersiz](assets/screenshots/exercise.jpg) | ![Su Takibi](assets/screenshots/water.jpg) |

| Kilo Takibi | Profil Menüsü | Haftalık Analizler |
| --- | --- | --- |
| ![Kilo Takibi](assets/screenshots/weight.jpg) | ![Profil Menüsü](assets/screenshots/profile2.jpg) | ![Haftalık Analizler](assets/screenshots/analytics.png) |

| Ana Plan | AI İçgörüleri | Profil Özeti |
| --- | --- | --- |
| ![Ana Plan](assets/screenshots/dashboard.jpg) | ![AI İçgörüleri](assets/screenshots/aisuggestion.jpg) | ![Profil Özeti](assets/screenshots/profile.jpg) |

## Mimari Yaklaşım

NutriAI'de mobil istemci, kullanıcı deneyimi ve state yönetiminden sorumludur. Kimlik doğrulama, veritabanı, güvenli yapay zekâ geçidi, kota kontrolü ve abonelik doğrulama gibi hassas süreçler backend tarafında yönetilir.

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

## Güvenlik Notu

Bu public tanıtım reposunda aşağıdaki içerikler yer almaz:

- Kaynak kodu
- `.env` dosyaları
- API anahtarları
- Supabase migration dosyaları
- Edge Function kaynak kodu
- Veritabanı şeması ve RLS policy detayları
- Abonelik veya yapay zekâ kota iş kuralları

## Demo

Demo video/GIF bağlantısı buraya eklenecek:

```text
Demo: yakında eklenecek
```

## CV İçin Kısa Açıklama

**NutriAI | Yapay Zekâ Destekli Fitness ve Beslenme Mobil Uygulaması**  
React Native, Expo, TypeScript, Supabase, PostgreSQL, Gemini API ve RevenueCat kullanarak yapay zekâ destekli yemek analizi, kişiselleştirilmiş beslenme planı, egzersiz/su/kilo takibi, haftalık analizler ve premium erişim akışlarına sahip cross-platform mobil uygulama geliştirdim.

## Geliştirici

Muhittin Dayan
