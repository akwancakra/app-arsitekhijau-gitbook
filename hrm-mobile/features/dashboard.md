---
description: >-
  Halaman utama aplikasi: ringkasan aktivitas dan akses cepat ke fitur-fitur penting.
icon: house
---

# Dashboard Home

Dashboard Home adalah halaman pertama setelah login: pusat kendali semua aktivitas HR kamu.

![Tampilan lengkap Dashboard Home](https://placehold.co/600x1200/1a1a2e/ffffff?text=dashboard-home)

---

## Komponen Dashboard

### 1. Profile Header

![Profile Header di dashboard](https://placehold.co/600x1200/1a1a2e/ffffff?text=profile-header)

Bagian paling atas menampilkan:
- **Foto profil** kamu
- **Nama lengkap** & NIP
- **Jabatan / Posisi**

---

### 2. Quick Clock Button

![Tombol Clock In besar di dashboard](https://placehold.co/600x1200/1a1a2e/ffffff?text=quick-clock)

Tombol besar untuk **Clock In** atau **Clock Out**:
- Hijau sebelum clock in: tombol **"Clock In"**
- Merah setelah clock in: berubah jadi **"Clock Out"**
- Menampilkan durasi kerja hari ini (misal: "5j 32m")

{% hint style="success" %}
Satu tap langsung absen! GPS & selfie akan diminta otomatis.
{% endhint %}

---

### 3. Today's Attendance Card

![Card status absensi hari ini](https://placehold.co/600x1200/1a1a2e/ffffff?text=today-card)

Ringkasan status absensi hari ini:
- **Status**: Hadir / Belum Absen / Terlambat / Izin
- **Clock In**: jam masuk
- **Clock Out**: jam pulang
- **Progress bar**: jam kerja vs target

---

### 4. Personal Quick Access Grid

Grid icon untuk akses cepat ke fitur pribadi:

<table data-view="cards">
  <thead><tr><th></th><th></th></tr></thead>
  <tbody>
    <tr><td><strong>Absensi</strong><br>Detail & koreksi absensi</td><td><strong>Cuti</strong><br>Saldo & pengajuan cuti</td></tr>
    <tr><td><strong>Lembur</strong><br>Pengajuan lembur</td><td><strong>Shift</strong><br>Request perubahan shift</td></tr>
    <tr><td><strong>Slip Gaji</strong><br>Lihat & download</td><td><strong>Peringatan</strong><br>Surat peringatan</td></tr>
    <tr><td><strong>SOP</strong><br>Dokumen SOP</td><td><strong>Pengumuman</strong><br>Info internal</td></tr>
    <tr><td><strong>Aset</strong><br>Aset perusahaan</td><td><strong>Kalendar</strong><br>Kalendar kerja</td></tr>
    <tr><td><strong>Organisasi</strong><br>Direktori karyawan</td><td><strong>Profile Change</strong><br>Update data profil</td></tr>
  </tbody>
</table>

---

### 5. Approver Quick Access

{% hint style="info" %}
Section ini **hanya muncul** jika kamu adalah **approver** (atasan/manager).
{% endhint %}

- **Approval Cuti**: Setujui/tolak cuti bawahan
- **Approval Lembur**: Setujui/tolak lembur
- **Approval Absensi**: Setujui/tolak koreksi absensi
- **Approval Shift**: Setujui/tolak perubahan shift
- **Profile Change Approval**

---

### 6. Upcoming Tasks

Menampilkan **2 tugas teratas** yang perlu dikerjakan:
- Nama tugas & deadline
- Status badge (&#x1F534; Pending / &#x1F7E1; In Progress / &#x1F7E2; In Review / Done)

Tap untuk lihat detail lengkap.

---

### 7. Latest Announcement

Card pengumuman **terbaru** dari HR/Management: dengan badge **NEW** jika belum dibaca.

---

### 8. Pull-to-Refresh

Tarik layar ke bawah untuk **refresh** semua data dashboard (absensi, tugas, pengumuman).
