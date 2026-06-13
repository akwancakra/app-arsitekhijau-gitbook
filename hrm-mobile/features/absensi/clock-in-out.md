---
description: >-
  Panduan lengkap cara melakukan Clock In dan Clock Out.
icon: clock
---

# Clock In & Clock Out

{% tabs %}
{% tab title="🟢 Clock In" %}

Clock In dilakukan saat kamu **tiba di tempat kerja** di awal shift.

{% stepper %}
{% step %}
### Tap Tombol Clock In
Buka aplikasi HRM Mobile, di **Dashboard Home** tap tombol **Clock In** (ikon hijau besar).

![Tombol Clock In di dashboard](https://placehold.co/600x400/1a1a2e/ffffff?text=tombol-clock-in)
{% endstep %}

{% step %}
### Tunggu Deteksi Lokasi
Sistem akan **mendeteksi lokasi GPS** kamu secara otomatis. Pastikan GPS HP aktif.

![Modal Clock In — deteksi lokasi dan kamera](https://placehold.co/600x400/1a1a2e/ffffff?text=modal-clock-in)
{% endstep %}

{% step %}
### Ambil Foto Selfie
Tap ikon **Kamera** untuk mengambil foto selfie sebagai bukti kehadiran.
{% endstep %}

{% step %}
### Konfirmasi Clock In
(Opsional) Tambahkan catatan jika perlu, lalu tap **Clock In** untuk mengonfirmasi.
{% endstep %}
{% endstepper %}

{% hint style="success" %}
✅ Clock In berhasil! Tombol dashboard berubah jadi **Clock Out** (merah), status jadi **"Active"**, durasi kerja mulai terhitung.
{% endhint %}

{% endtab %}
{% tab title="🔴 Clock Out" %}

Clock Out dilakukan saat kamu **pulang** setelah shift selesai.

{% stepper %}
{% step %}
### Tap Tombol Clock Out
Di Dashboard Home, tap tombol **Clock Out** (ikon merah besar).

![Tombol Clock Out di dashboard](https://placehold.co/600x400/1a1a2e/ffffff?text=tombol-clock-out)
{% endstep %}

{% step %}
### Deteksi Lokasi & Selfie
Sistem mendeteksi lokasi GPS, lalu ambil **foto selfie**.
{% endstep %}

{% step %}
### Konfirmasi Clock Out
(Opsional) Tambahkan catatan, lalu tap **Clock Out** untuk mengonfirmasi.
{% endstep %}
{% endstepper %}

{% hint style="success" %}
✅ Clock Out berhasil! Status berubah jadi **"Completed"**, durasi kerja tercatat.
{% endhint %}

{% endtab %}
{% endtabs %}

---

## Tips & Troubleshooting

<details>
<summary><b>GPS Error</b> — GPS tidak mendeteksi lokasi</summary>

1. Pastikan **GPS/Lokasi** HP aktif
2. Coba ke **luar ruangan** agar sinyal kuat
3. **Restart** aplikasi
</details>

<details>
<summary><b>Foto Gagal</b> — Kamera tidak bisa mengambil foto</summary>

- Periksa **izin kamera** di Pengaturan HP → Aplikasi → HRM → Kamera → **Izinkan**
- Restart aplikasi
</details>

<details>
<summary><b>Tombol Clock Tidak Muncul</b> — Tombol tidak terlihat di dashboard</summary>

- Pastikan **sudah login** dan **koneksi internet** stabil
- Tarik layar ke bawah untuk **refresh** dashboard
</details>

<details>
<summary><b>Lokasi Tidak Sesuai</b> — Terdeteksi di luar area kerja</summary>

- Pastikan kamu berada di **area kantor yang terdaftar**
- Jika lokasi benar tapi masih error, hubungi IT
</details>

<details>
<summary><b>Lupa Clock Out</b> — Sudah clock in tapi lupa clock out</summary>

Gunakan fitur **Koreksi Absensi → Past Day Correction**. Pilih tipe **Lupa Clock Out** dan isi waktu pulang yang benar.
</details>

{% hint style="warning" %}
Clock In & Clock Out hanya bisa **1 kali per hari**. Jika ada kesalahan, gunakan **Koreksi Absensi** untuk memperbaikinya.
{% endhint %}
