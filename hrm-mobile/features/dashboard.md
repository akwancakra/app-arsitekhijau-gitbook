---
description: >-
  Halaman utama aplikasi — ringkasan aktivitas dan akses cepat ke fitur-fitur penting.
icon: house
---

# Dashboard Home

Dashboard Home adalah halaman pertama yang kamu lihat setelah login. Ini adalah pusat kendali semua aktivitas HR kamu.

![Tampilan Dashboard Home](.assets/images/hrm-mobile/dashboard/dashboard-home.png)

## Komponen Dashboard

### 1. Profile Header

Di bagian paling atas, kamu akan melihat:
- **Foto profil** kamu
- **Nama lengkap**
- **NIP / Employee ID**
- **Jabatan / Posisi**

### 2. Quick Clock Button

Tombol besar untuk **Clock In** atau **Clock Out**:
- Sebelum clock in: tombol bertuliskan **"Clock In"** (warna hijau)
- Setelah clock in: tombol berubah menjadi **"Clock Out"** (warna merah)
- Menampilkan durasi kerja hari ini (misal: "5j 32m")

![Quick Clock Button](.assets/images/hrm-mobile/dashboard/quick-clock.png)

### 3. Today's Attendance Card

Ringkasan status absensi hari ini:
- **Status**: Hadir / Belum Absen / Izin / Sakit / Terlambat
- **Clock In time**: jam masuk
- **Clock Out time**: jam pulang (jika sudah)
- **Progress bar**: perbandingan jam kerja vs target

### 4. Personal Quick Access Grid

Grid icon untuk akses cepat ke fitur-fitur pribadi:

| Icon | Fitur | Fungsi |
|---|---|---|
| 📋 | **Absensi** | Detail absensi & koreksi |
| 🏖️ | **Cuti** | Saldo & pengajuan cuti |
| ⏰ | **Lembur** | Pengajuan lembur |
| 🔄 | **Shift** | Request perubahan shift |
| 📄 | **Slip Gaji** | Lihat & download payslip |
| ⚠️ | **Peringatan** | Surat peringatan |
| 📖 | **SOP** | Dokumen SOP |
| 📢 | **Pengumuman** | Pengumuman internal |
| 💼 | **Aset** | Aset perusahaan |
| 📅 | **Kalendar** | Kalendar kerja |
| 👥 | **Organisasi** | Direktori karyawan |
| 📝 | **Profile Change** | Request update profil |

### 5. Approver Quick Access (khusus approver)

Jika kamu adalah approver (atasan / manager), akan muncul section tambahan:

| Icon | Fitur |
|---|---|
| ✅ | **Approval Cuti** |
| ✅ | **Approval Lembur** |
| ✅ | **Approval Absensi** |
| ✅ | **Approval Shift** |
| ✅ | **Profile Change Approval** |

### 6. Upcoming Tasks

Menampilkan **2 tugas teratas** yang perlu dikerjakan:
- Nama tugas
- Deadline
- Status (Pending / In Progress / In Review / Done)

Tap tugas untuk melihat detail lengkap.

### 7. Latest Announcement

Card pengumuman **terbaru** dari HR / Management:
- Judul pengumuman
- Tanggal terbit
- Preview konten singkat

Tap untuk membaca pengumuman selengkapnya. Jika ada pengumuman yang belum dibaca, akan muncul badge **"NEW"**.

### 8. Pull-to-Refresh

Tarik layar ke bawah untuk **merefresh** semua data dashboard (absensi, tugas, pengumuman).

***

**Lanjut ke:** [Overview Absensi](absensi/overview.md)
