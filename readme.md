# 🏥 PKM Kiarapedes Digital Ecosystem (Dark Luxury Edition)

![Version](https://img.shields.io/badge/version-2.1.0-emerald)
![Platform](https://img.shields.io/badge/platform-GitHub_Pages-blue)
![Theme](https://img.shields.io/badge/theme-Dark_Glassmorphism-purple)

Sistem integrasi layanan kesehatan digital untuk **UPTD Puskesmas Kiarapedes**. Dibangun dengan estetika *Dark Luxury Glassmorphism* yang modern, efisien, dan responsif.

## 🚀 Fitur Utama
Sistem ini terdiri dari tiga aplikasi utama yang saling terintegrasi dalam satu portal:

* **Kepegawaian Digital (Sistem Informasi Kepegawaian):** Manajemen database pegawai, monitoring SIP/STR, dan analisis beban kerja (Supabase Backend).
* **Arsip Digital :** Digitalisasi surat menyurat, manajemen dokumen akreditasi, dan verifikasi dokumen via QR Code.
* **Analisis Data:** Dashboard analisis data PWS (Pemantauan Wilayah Setempat) yang mengintegrasikan data dari **ASIK** dan **e-Puskesmas**.

## 🛠️ Teknologi yang Digunakan
- **Frontend:** HTML5, Tailwind CSS, Font Awesome 6.
- **Styling:** Custom CSS (Glassmorphism 2.0 & Dark Glossy Effect).
- **Database:** Supabase (PostgreSQL) untuk sinkronisasi data real-time.
- **Charts:** Chart.js untuk visualisasi data eksekutif.
- **Hosting:** GitHub Pages.

## 📂 Struktur File
```text
/
├── index.html        # Dashboard Utama (Portal Hub)
├── simpeg.html       # Modul Manajemen Kepegawaian
├── e-arsip.html      # Modul Administrasi & Surat
├── analisis.html     # Modul Audit Data ASIK/e-Puskesmas
├── style.css         # Framework CSS Glassmorphism Terpusat

└── assets/           # Folder gambar, logo, dan ikon
