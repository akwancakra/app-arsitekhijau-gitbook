---
description: >-
  Pengelolaan absensi harian: clock in, clock out, riwayat, dan koreksi.
icon: calendar-check
---

# Overview Absensi

Modul **Absensi** adalah fitur utama HRM Mobile untuk mencatat kehadiran harian kamu. Fitur ini mencakup clock in/out dengan verifikasi lokasi GPS dan foto selfie.

{% hint style="info" %}
Jam kerja normal menyesuaikan dengan jadwal shift masing-masing karyawan. Pastikan kamu mengetahui jadwal shift sebelum melakukan absensi.
{% endhint %}

## Fitur yang Tersedia

{% table data-view="cards" %}
| Sub-page | Deskripsi |
| --- | --- |
| **Clock In / Clock Out** | Mencatat jam masuk dan pulang kerja dengan verifikasi GPS & foto selfie |
| **Riwayat Absensi** | Daftar record absensi harian lengkap dengan detail jam dan status |
| **Koreksi Absensi** | Perbaiki absensi yang salah atau lupa absen: same day & past day |
{% /table %}

## Alur Absensi Harian

```
Clock In (pagi) → Aktivitas Kerja → Clock Out (sore)
     │                                         │
     └── GPS + Selfie                          └── GPS + Selfie
```

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

![Akses cepat ke menu absensi dari halaman dashboard utama](https://placehold.co/600x400/1a1a2e/ffffff?text=akses-cepat)

***

