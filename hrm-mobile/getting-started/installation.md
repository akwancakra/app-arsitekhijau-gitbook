---
description: >-
  Panduan instalasi aplikasi HRM Mobile di perangkat Android dan iOS.
icon: mobile-notch
---

# 📲 Instalasi & Setup Aplikasi

## Persyaratan Sistem

| Platform | Minimal OS | Catatan |
|---|---|---|
| **Android** | Android 7.0 (API 24) | Google Play Services diperlukan |
| **iOS** | iOS 15.0+ | iPhone 8 atau lebih baru |
| **Koneksi Internet** | Stabil (4G / WiFi) | Untuk login dan sinkronisasi data |

---

## Instalasi Aplikasi

{% tabs %}
{% tab title="Android" %}

![Google Play Store - HRM Arsitek Hijau](https://placehold.co/600x1200/1a1a2e/ffffff?text=play-store)

1. Buka **Google Play Store** di perangkat kamu
2. Cari **"HRM Arsitek Hijau"**
3. Tap **Install**
4. Tunggu hingga proses instalasi selesai
5. Tap **Open** untuk membuka aplikasi

{% endtab %}

{% tab title="iOS" %}

![App Store - HRM Arsitek Hijau](https://placehold.co/600x1200/1a1a2e/ffffff?text=app-store)

1. Buka **App Store** di iPhone kamu
2. Cari **"HRM Arsitek Hijau"**
3. Tap **Dapatkan** (Get)
4. Konfirmasi dengan Face ID / Touch ID / password Apple ID
5. Tap **Buka** setelah instalasi selesai

{% endtab %}
{% endtabs %}

---

{% details title="Distribusi Internal (MDM / TestFlight / APK Langsung)" %}
Jika perusahaan menggunakan distribusi internal:

- Kamu akan menerima **email undangan** berisi link download
- Atau IT akan mengirimkan **link APK (Android)** / **link TestFlight (iOS)**
- Ikuti petunjuk di email untuk instalasi

{% hint style="warning" %}
Untuk Android APK langsung, izinkan **Instalasi dari Sumber Tidak Dikenal** di Pengaturan HP.
{% endhint %}
{% enddetails %}

---

## 🔐 Izin Aplikasi yang Diperlukan

{% hint style="info" %}
**Semua izin** bisa diatur ulang kapan saja di **Pengaturan HP → Aplikasi → HRM Arsitek Hijau → Izin**.
{% endhint %}

| Izin | Kegunaan | Waktu Diminta |
|---|---|---|
| **📍 Lokasi (GPS)** | Validasi lokasi saat Clock In/Out | Saat onboarding / pertama kali absen |
| **📸 Kamera** | Foto selfie saat Clock In/Out | Saat onboarding / pertama kali absen |
| **🔔 Notifikasi** | Pengingat clock, info pengajuan, pengumuman | Saat onboarding |
| **📁 Penyimpanan** | Download slip gaji PDF | Saat download payslip |

---

{% details title="❓ Troubleshooting Instalasi" %}

**Aplikasi tidak muncul di Play Store / App Store?**
- Pastikan kamu menggunakan akun dengan region Indonesia
- Atau hubungi IT untuk link distribusi internal

**Gagal install (storage penuh)?**
- Bersihkan storage HP, minimal butuh ~100MB ruang kosong

**Aplikasi tidak bisa dibuka setelah install?**
- Restart HP, coba buka lagi
- Pastikan OS memenuhi persyaratan minimal

{% enddetails %}

---

**Lanjut ke:** [Login & Registrasi](login.md)
