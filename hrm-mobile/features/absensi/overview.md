---
description: >-
  Pengelolaan absensi harian — clock in, clock out, riwayat, dan koreksi.
icon: calendar-check
---

# Overview Absensi

Modul **Absensi** adalah fitur utama HRM Mobile untuk mencatat kehadiran harian kamu. Fitur ini mencakup clock in/out dengan verifikasi lokasi GPS dan foto selfie.

## Fitur yang Tersedia

| Fitur | Deskripsi |
|---|---|
| **Clock In** | Mencatat jam masuk kerja dengan lokasi & foto |
| **Clock Out** | Mencatat jam pulang kerja |
| **Today Status** | Ringkasan absensi hari ini |
| **Riwayat Absensi** | Daftar record absensi harian |
| **Koreksi Absensi** | Perbaiki absensi yang salah atau lupa absen |

## Alur Absensi Harian

```
Clock In (pagi) → Aktivitas Kerja → Clock Out (sore)
     │                                         │
     └── GPS + Selfie                          └── GPS + Selfie
```

> **Jam kerja normal:** Disesuaikan dengan jadwal shift masing-masing karyawan.

## Status Absensi

Setiap record absensi memiliki status:

| Status | Label | Arti |
|---|---|---|
| ✅ | **Hadir** (Present) | Clock in & clock out tepat waktu |
| 🔴 | **Terlambat** (Late) | Clock in setelah jam mulai shift |
| 🟡 | **Pulang Cepat** (Early Leave) | Clock out sebelum jam selesai shift |
| ⚪ | **Belum Absen** | Belum melakukan clock in/out |
| ❌ | **Tidak Hadir** (Absent) | Tidak ada catatan absensi |
| 🟢 | **Izin / Sakit** | Ada pengajuan cuti/sakit yang disetujui |

## Yang Kamu Butuhkan

Untuk melakukan absensi, pastikan:
1. **Koneksi internet** stabil
2. **GPS/Lokasi** aktif di HP
3. **Izin kamera** sudah diberikan
4. Berada di **lokasi kerja** yang terdaftar

![Akses Cepat Absensi dari Dashboard](.assets/images/hrm-mobile/absensi/akses-cepat.png)

***

**Lanjut ke:** [Clock In & Clock Out](clock-in-out.md)
