---
description: >-
  Panduan instalasi aplikasi HRM Mobile di perangkat Android dan iOS.
icon: mobile-notch
---

# Instalasi & Setup Aplikasi

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

{% stepper %}
{% step %}
### Buka Play Store
Buka **Google Play Store** di perangkat Android kamu.
{% endstep %}

{% step %}
### Cari Aplikasi
Cari **"HRM Arsitek Hijau"** di kolom pencarian.

![Play Store](https://placehold.co/600x1200/1a1a2e/ffffff?text=play-store)
{% endstep %}

{% step %}
### Install
Tap **Install**, tunggu proses selesai.
{% endstep %}

{% step %}
### Buka Aplikasi
Tap **Open** untuk menjalankan aplikasi.
{% endstep %}
{% endstepper %}

{% endtab %}

{% tab title="iOS" %}

{% stepper %}
{% step %}
### Buka App Store
Buka **App Store** di iPhone kamu.
{% endstep %}

{% step %}
### Cari Aplikasi
Cari **"HRM Arsitek Hijau"** di kolom pencarian.

![App Store](https://placehold.co/600x1200/1a1a2e/ffffff?text=app-store)
{% endstep %}

{% step %}
### Download
Tap **Dapatkan** (Get), konfirmasi dengan Face ID/Touch ID/password Apple ID.
{% endstep %}

{% step %}
### Buka Aplikasi
Tap **Buka** setelah instalasi selesai.
{% endstep %}
{% endstepper %}

{% endtab %}
{% endtabs %}

---

## Izin Aplikasi yang Diperlukan

{% hint style="info" %}
Semua izin bisa diatur ulang di **Pengaturan HP > Aplikasi > HRM Arsitek Hijau > Izin**.
{% endhint %}

| Izin | Kegunaan | Waktu Diminta |
|---|---|---|
| **Lokasi (GPS)** | Validasi lokasi saat Clock In/Out | Saat onboarding / pertama kali absen |
| **Kamera** | Foto selfie saat Clock In/Out | Saat onboarding / pertama kali absen |
| **Notifikasi** | Pengingat clock, info pengajuan, pengumuman | Saat onboarding |
| **Penyimpanan** | Download slip gaji PDF | Saat download payslip |

---

<details>
<summary><b>Distribusi Internal (MDM / TestFlight / APK Langsung)</b></summary>

Jika perusahaan menggunakan distribusi internal:
- Kamu akan menerima **email undangan** berisi link download
- Atau IT mengirimkan **link APK (Android)** / **link TestFlight (iOS)**

{% hint style="warning" %}
Untuk Android APK langsung, izinkan **Instalasi dari Sumber Tidak Dikenal** di Pengaturan HP.
{% endhint %}
</details>

<details>
<summary><b>Troubleshooting Instalasi</b></summary>

**Aplikasi tidak muncul di Play Store / App Store?**
Pastikan menggunakan akun region Indonesia, atau hubungi IT.

**Gagal install — storage penuh?**
Bersihkan storage HP, minimal perlu ~100MB ruang kosong.

**Aplikasi tidak bisa dibuka setelah install?**
Restart HP, pastikan OS memenuhi persyaratan minimal.

</details>
