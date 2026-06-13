---
description: >-
  Pertanyaan umum dan pemecahan masalah seputar aplikasi.
icon: circle-question
---

# ❓ FAQ / Troubleshooting

{% tabs %}
{% tab title="🔑 Login & Akun" %}

<details>
<summary><b>Lupa password, bagaimana?</b></summary>

1. Tap **Lupa Password?** di halaman login
2. Masukkan email perusahaan kamu
3. Cek inbox atau folder Spam untuk link reset password

> 💡 **Info:** Link reset password memiliki masa berlaku terbatas. Jika tidak menerima email, hubungi IT Support.
</details>

<details>
<summary><b>Gagal login — "Email atau password salah"</b></summary>

- Pastikan email menggunakan domain perusahaan (`@arsitekhijau.com`)
- Cek apakah **caps lock** tidak aktif
- Jika masih gagal, gunakan **Lupa Password** untuk reset
- Jika semua cara gagal, hubungi IT Support
</details>

<details>
<summary><b>Akun terkunci karena salah password berkali-kali</b></summary>

Hubungi **IT Support** untuk membuka kunci akun: `it@arsitekhijau.com`

Sertakan:
- Nama lengkap & NIP
- Waktu kejadian

</details>

{% endtab %}
{% tab title="📋 Absensi" %}

<details>
<summary><b>Lupa clock in, bagaimana?</b></summary>

Gunakan fitur **Koreksi Absensi → Past Day Correction**:

{% stepper %}
{% step %}
### Buka menu Absensi
Dari Dashboard, tap icon **📋 Absensi**
{% endstep %}
{% step %}
### Pilih Koreksi Absensi
Tap **Koreksi Absensi**, pilih **Past Day Correction**
{% endstep %}
{% step %}
### Isi detail koreksi
Pilih tanggal, tipe koreksi (Lupa Clock In), dan waktu yang benar
{% endstep %}
{% step %}
### Kirim dan tunggu approval
Tulis alasan jelas, kirim, tunggu atasan menyetujui
{% endstep %}
{% endstepper %}

</details>

<details>
<summary><b>Lupa clock out — gaji dipotong?</b></summary>

Segera ajukan **Koreksi Absensi → Past Day Correction** dengan tipe **Lupa Clock Out**. Selama belum dikoreksi, sistem menghitung durasi tidak lengkap — potensi pemotongan ada sampai dikoreksi dan di-approve.
</details>

<details>
<summary><b>GPS error saat clock in</b></summary>

1. Pastikan **GPS/Lokasi** HP aktif
2. Coba ke **luar ruangan** agar sinyal GPS kuat
3. **Restart** aplikasi
4. Jika masih error, gunakan fitur **Koreksi Absensi**
</details>

<details>
<summary><b>Lokasi tidak terdeteksi / tidak sesuai</b></summary>

Pastikan kamu berada di **area kantor yang terdaftar** di sistem. Jika lokasi sudah benar tapi tetap error, hubungi IT untuk pengecekan koordinat kantor di sistem.
</details>

{% endtab %}
{% tab title="🏖️ Cuti & Lembur" %}

<details>
<summary><b>Saldo cuti tidak muncul / tidak sesuai</b></summary>

Saldo cuti dikelola oleh **HR Department**. Hubungi HR jika ada ketidaksesuaian — data saldo di aplikasi langsung mengambil dari database HR.
</details>

<details>
<summary><b>Pengajuan cuti ditolak, kenapa?</b></summary>

Cek **alasan penolakan** dari approver. Umumnya karena:
- Alasan operasional (banyak yang cuti di waktu sama)
- Kuota cuti tidak mencukupi
- Pengajuan terlalu dekat dengan tanggal cuti

Ajukan ulang setelah memperbaiki sesuai masukan approver.
</details>

<details>
<summary><b>Lembur belum di-approve setelah beberapa hari</b></summary>

Hubungi **atasan langsung** kamu. Approver mungkin:
- Belum melihat notifikasi
- Sedang tidak masuk kantor
- Notifikasi tertumpuk

Kamu juga bisa melihat status request di tab **Requests**.
</details>

{% endtab %}
{% tab title="🔔 Notifikasi" %}

<details>
<summary><b>Tidak mendapat notifikasi dari aplikasi</b></summary>

Cek tiga hal ini:
1. **Izin notifikasi** di Pengaturan HP → Aplikasi → HRM → Notifikasi → **ON**
2. **Pengaturan dalam aplikasi** → Account → Pengaturan → Notifikasi → **ON**
3. **Mode Jangan Ganggu (DND)** → pastikan tidak aktif

> 💡 Di Android, pastikan channel notifikasi tidak di-mute secara manual.
</details>

<details>
<summary><b>Notifikasi clock reminder tidak muncul</b></summary>

1. Buka **Account → Clock Reminder**
2. Pastikan toggle **Aktifkan Clock Reminder** = ON
3. Pastikan **jam** sudah diatur dengan benar (misal: Clock In 07:45)
4. Pastikan izin notifikasi di HP sudah diberikan

</details>

{% endtab %}
{% tab title="🛠️ Teknis" %}

<details>
<summary><b>Aplikasi lambat / loading terus</b></summary>

1. Cek **koneksi internet** (ganti WiFi ke data atau sebaliknya)
2. **Tutup dan buka ulang** aplikasi
3. **Clear cache** di Pengaturan HP → Aplikasi → HRM → Clear Cache
4. Jika masih lambat, **restart HP**
</details>

<details>
<summary><b>Update OTA gagal</b></summary>

1. Cek **koneksi internet** stabil
2. Pastikan **penyimpanan HP** mencukupi (minimal ~100MB kosong)
3. Tutup dan buka ulang aplikasi, cek update lagi
4. Jika masih gagal, tunggu beberapa jam dan coba lagi — server update mungkin sibuk
</details>

<details>
<summary><b>Aplikasi force close / crash</b></summary>

{% stepper %}
{% step %}
### Restart HP
Matikan dan nyalakan kembali perangkat
{% endstep %}
{% step %}
### Update aplikasi
Buka Play Store / App Store, cek apakah ada update versi terbaru
{% endstep %}
{% step %}
### Clear data aplikasi
Jika masih crash: Pengaturan HP → Aplikasi → HRM → Clear Data (hati-hati: kamu perlu login ulang)
{% endstep %}
{% step %}
### Laporkan ke IT
Jika semua gagal, hubungi IT dengan:
- Screenshot error
- Tipe HP & versi OS
- Langkah sebelum crash terjadi
{% endstep %}
{% endstepper %}

</details>

<details>
<summary><b>Bagaimana update aplikasi dari Play Store / App Store?</b></summary>

Buka **Play Store** (Android) atau **App Store** (iOS), cari **"HRM Arsitek Hijau"**, tap **Update** jika tersedia. Untuk update minor, gunakan fitur **OTA Update** di dalam aplikasi.
</details>

{% endtab %}
{% tab title="🔒 Keamanan" %}

<details>
<summary><b>HP hilang / dicuri, apa yang harus dilakukan?</b></summary>

**Segera** laporkan ke IT Support untuk:
1. Me-**reset sesi login** aktif
2. **Memblokir akses** akun dari perangkat tersebut
3. Membantu kamu setup ulang di HP baru

> 🚨 Jangan tunda — semakin cepat dilaporkan, semakin aman data kamu.
</details>

<details>
<summary><b>Lupa PIN aplikasi</b></summary>

1. Di halaman lock screen, tap **Lupa PIN?**
2. Masukkan **password akun** untuk verifikasi
3. Buat **PIN baru** (6 digit)
4. Selesai — kamu langsung masuk aplikasi

</details>

<details>
<summary><b>Biometric tidak berfungsi</b></summary>

1. Pastikan **fingerprint / FaceID** sudah terdaftar di Pengaturan HP
2. Restart aplikasi
3. Jika masih error, gunakan **PIN** sebagai alternatif
4. Coba nonaktifkan dan aktifkan ulang biometric di **Account → PIN Settings**

</details>

{% endtab %}
{% endtabs %}

---

{% hint style="success" icon="headphones" %}
### Tidak menemukan jawaban?

Hubungi tim support kami:
- **IT Support**: `it@arsitekhijau.com`
- **HR Department**: `hr@arsitekhijau.com`

Sertakan **nama, NIP, versi aplikasi, tipe HP & OS, dan screenshot** masalah untuk penanganan lebih cepat.
{% endhint %}
