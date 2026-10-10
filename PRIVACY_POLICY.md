# Kebijakan Privasi / Privacy Policy — Pantau Kerja

**Terakhir Diperbarui / Last Updated:** 11 Oktober 2026  
**Pengembang Resmi / Official Developer:** Arkananta Horizon  
**Nama Aplikasi / Application Name:** Pantau Kerja (Pantau Kerja Enterprise)  
**ID Aplikasi / Application ID:** `com.arkanantahorizon.pantaukerja`  
**Kontak Resmi / Official Contact:** affan@arkananta.id | support@arkananta.id  

---

## 🇮🇩 Bahasa Indonesia

Selamat datang di **Pantau Kerja** ("Aplikasi"), solusi manajemen tenaga kerja dan produktivitas terintegrasi yang dikembangkan oleh **Arkananta Horizon**. Aplikasi ini memfasilitasi absensi presisi berbasis lokasi (*geofencing*), pemantauan rute tugas lapangan (*field task tracking*), dan pelaporan insiden operasional (*incident reporting*).

Kebijakan Privasi ini menerangkan bagaimana Arkananta Horizon mengumpulkan, mengelola, memproses, dan melindungi data pribadi Anda saat menggunakan aplikasi Pantau Kerja sesuai dengan:
1. **Google Play Developer Policy** (termasuk Location and Foreground Service Policy).
2. **Undang-Undang Republik Indonesia No. 27 Tahun 2022 tentang Perlindungan Data Pribadi (UU PDP)**.
3. **Standar Keamanan Zero-Trust Perusahaan**.

---

### 1. Informasi yang Kami Kumpulkan & Tujuan Penggunaannya

#### a. Data Lokasi (Akurat & Perkiraan)
- **Jenis Izin:** `ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION`, `FOREGROUND_SERVICE_LOCATION`.
- **Tujuan Penggunaan:**
  - Validasi radius absensi masuk/pulang kerja (*geofencing radius check*).
  - Perekaman rute patroli tugas lapangan selama shift kerja aktif via layanan latar depan (*Foreground Service*).
- **Transparansi & Batasan:**
  - Perekaman lokasi **HANYA BERJALAN** saat status absensi aktif / jam shift kerja berlangsung dengan notifikasi persisten di bilah status Android.
  - Pelacakan otomatis berhenti saat karyawan melakukan absen pulang (*Check-Out*). Kami **TIDAK PERNAH** melacak lokasi Anda di luar jam kerja.

#### b. Kamera & Data Gambar (Foto Absensi & Laporan)
- **Jenis Izin:** `CAMERA`.
- **Tujuan Penggunaan:**
  - Pengambilan foto verifikasi wajah saat melakukan absensi (*Selfie Attendance Verification*).
  - Pengambilan foto bukti insiden atau dokumentasi pekerjaan lapangan pada modul LaporPak.

#### c. Informasi Identitas Karyawan
- **Data:** Nama lengkap, alamat email kerja, nomor induk karyawan (NIK/ID Karyawan), jabatan, dan divisi kerja.
- **Tujuan Penggunaan:** Otentikasi sesi kerja dan sinkronisasi laporan tugas ke dashboard admin enterprise.

---

### 2. Keamanan & Enkripsi Data

1. **Enkripsi Saat Transit:** Semua data transaksi, koordinat lokasi, dan foto dienkripsi menggunakan protokol **HTTPS / TLS 1.3** yang ditegakkan melalui `network_security_config.xml`.
2. **Arkananta Anti-Tamper Guard:** Aplikasi dilindungi modul keamanan biner untuk memverifikasi integritas runtime dan mencegah manipulasi paket (*anti-spoofing location & anti-tampering*).
3. **Penyimpanan Aman:** Basis data lokal dilindungi sistem sandbox kernel Android dan otentikasi token API Zero-Trust.

---

### 3. Kebijakan Iklan & Pembagian Data ke Pihak Ketiga

- **0 Iklan Komersial:** Pantau Kerja 100% bebas dari segala bentuk iklan komersial.
- **Tanpa Penjualan Data:** Kami tidak pernah menjual, menyewakan, atau membagikan data identitas atau lokasi karyawan kepada jaringan periklanan pihak ketiga mana pun.
- **Penggunaan Internal Enterprise:** Data hanya dapat diakses oleh administrator resmi perusahaan Anda yang berwenang.

---

### 4. Hak Pengguna & Prosedur Penghapusan Data (Data Deletion)

Sesuai ketentuan Google Play Data Deletion Policy dan UU PDP:
- Pengguna berhak meminta informasi mengenai data yang tersimpan, koreksi data, serta permohonan penghapusan riwayat absensi atau penonaktifan akun.
- Panduan dan formulir penghapusan data tersedia secara publik di:  
  **[https://ahaffan.github.io/pantaukerja-privacy/data-deletion.html](https://ahaffan.github.io/pantaukerja-privacy/data-deletion.html)**
- Anda juga dapat mengirimkan permohonan penghapusan data resmi melalui email ke `affan@arkananta.id` atau `support@arkananta.id` dengan waktu penyelesaian maksimal **1 x 24 jam kerja**.

---

### 5. Kontak Pengembang

- **Pengembang:** Arkananta Horizon
- **Email:** `affan@arkananta.id` / `support@arkananta.id`
- **Repositori Resmi:** [https://github.com/ahaffan/pantaukerja-privacy](https://github.com/ahaffan/pantaukerja-privacy)

---
---

## 🇬🇧 English Version

Welcome to **Pantau Kerja** ("the Application"), an integrated enterprise workforce management and productivity platform developed by **Arkananta Horizon**.

This Privacy Policy describes how we collect, store, and safeguard your information in full compliance with Google Play Developer Policies and the Indonesian Personal Data Protection Law (UU PDP No. 27/2022).

---

### 1. Collected Information & Operational Purposes

#### a. Precise & Approximate Location Data
- **Permissions:** `ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION`, `FOREGROUND_SERVICE_LOCATION`.
- **Purpose:** Geofenced attendance check-in/out and field patrol route recording during active work shifts.
- **Operational Boundary:** Location tracking operates strictly during active shift hours with an active notification. Tracking ceases immediately upon check-out.

#### b. Camera & Photographic Media
- **Permission:** `CAMERA`.
- **Purpose:** Facial verification for attendance selfies and on-site operational incident photo reports (LaporPak).

#### c. Employee Profile Credentials
- **Data:** Full name, corporate email address, employee ID, and job role for authenticated enterprise access.

---

### 2. Data Security & Encryption Standards

- **Transit Encryption:** All communications are securely encrypted via **HTTPS / TLS 1.3**.
- **Anti-Tampering:** Integrated with `ArkanantaAntiTamperGuard` for runtime integrity and zero-trust verification.

---

### 3. Zero-Ad & Third-Party Disclosure Policy

- 100% commercial ad-free. Zero selling or marketing dissemination of employee telemetry.

---

### 4. Data Deletion & User Rights

- Detailed deletion instructions are accessible at:  
  **[https://ahaffan.github.io/pantaukerja-privacy/data-deletion.html](https://ahaffan.github.io/pantaukerja-privacy/data-deletion.html)**
- Requests may also be submitted to `affan@arkananta.id` with 24-hour turnaround resolution.
