---
title: Doable – Hesap silme / Account deletion
---

# Hesap silme / Account deletion

[English version below](#english)

Bu sayfa Muhammet Emre Kemancı'nın geliştirdiği **Doable** uygulaması içindir.

## Türkçe

### Uygulamadan sil

1. Doable uygulamasını aç ve giriş yap.
2. Profil sekmesini aç.
3. Hesap satırına dokun.
4. "Hesabı sil" seçeneğine dokun.
5. Onayla. İnternet bağlantın açık olmalı.

```
Profil ─► Hesap ─► Hesabı sil ─► Onayla ─► Giriş ekranı
```

### Uygulamaya erişemiyorsan

1. k.emre.k25@gmail.com adresine giriş e-postanla yaz.
2. Konuya "Hesap silme" yaz.
3. Talebini en geç 30 gün içinde işleriz ve sana bildiririz.

### Silinen veriler

- Hesabın, e-posta adresin ve adın.
- Buluttaki bütün görevler, kategoriler, takvimler, etkinlikler, günlük kayıtlar ve ayarlar.
- Bildirim adresin (push token).
- Cihazdaki Doable veritabanı (uygulamadan silersen).

Silme işlemi kalıcıdır ve geri alınamaz.

### Kalan veriler

| Veri | Süre |
|---|---|
| Çökme raporları (Firebase Crashlytics) | En fazla 90 gün, sonra kendiliğinden silinir |
| Giriş ve güvenlik kayıtları (Supabase, Cloudflare) | Sağlayıcının kısa süreli günlük süresi kadar |
| Reklam verisi (Google AdMob) | Google'ın kendi politikasına göre |

Yalnız çıkış yapmak hesabını silmez. Apple ile giriş yaptıysan bağlantıyı iPhone Ayarlar → [adın] → Apple ile Giriş bölümünden de kaldırabilirsin.

## English

### Delete in the app

1. Open the Doable app and sign in.
2. Open the Profile tab.
3. Tap Account.
4. Tap "Delete account".
5. Confirm. You must be online.

```
Profile ─► Account ─► Delete account ─► Confirm ─► Sign-in screen
```

### If you cannot open the app

1. Email k.emre.k25@gmail.com from your sign-in address.
2. Use the subject "Account deletion".
3. We process the request within 30 days and tell you.

### Data we delete

- Your account, email address and name.
- All tasks, categories, calendars, events, daily logs and settings in the cloud.
- Your push token.
- The Doable database on your device (when you delete in the app).

Deletion is permanent. You cannot undo it.

### Data we keep

| Data | Period |
|---|---|
| Crash reports (Firebase Crashlytics) | Up to 90 days, then deleted automatically |
| Sign-in and security logs (Supabase, Cloudflare) | The provider's short log period |
| Ad data (Google AdMob) | Under Google's own policy |

Signing out does not delete your account. If you used Apple sign-in, you can also remove the link in iPhone Settings → [your name] → Sign in with Apple.
