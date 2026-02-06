# 🏥 E-Governance Portal | PKM Kiarapedes v2.0

![Status](https://img.shields.io/badge/Status-Active-emerald)
![Version](https://img.shields.io/badge/Version-2.0.0-blue)
![Platform](https://img.shields.io/badge/Platform-GitHub_Pages-black)

**Satu Data PKM Kiarapedes** adalah ekosistem aplikasi manajemen internal yang dirancang untuk mendigitalisasi alur kerja medis dan administratif. Sistem ini mengintegrasikan pengarsipan, manajemen SDM, dan analisis data dalam satu dashboard terpusat.



---

## 🚀 Fitur Utama

* **Centralized Gateway (SSO):** Sistem login satu pintu untuk semua modul aplikasi menggunakan *LocalStorage persistence*.
* **E-Arsip Digital:** Manajemen dokumen dinamis dengan fitur QR-Code generator dan ekspor PDF otomatis.
* **SIMPEG Integration:** Database kepegawaian terpadu untuk monitoring SDM secara real-time.
* **Live Analytics:** Dashboard dengan grafik sparkline (Chart.js) yang menampilkan tren data langsung dari *Cloud Database*.
* **Cloud Sync:** Terkoneksi secara penuh dengan Google Sheets via Google Apps Script (GAS) API.

---

## 🛠️ Arsitektur Teknologi

Sistem ini dibangun dengan pendekatan *Serverless Architecture* untuk menjamin kecepatan dan biaya operasional nol (0):

| Layer | Teknologi |
| :--- | :--- |
| **Frontend** | HTML5, Tailwind CSS, JavaScript (ES6+) |
| **Animation** | FontAwesome 6, Glassmorphism UI |
| **Charting** | Chart.js (Interactive & Sparkline) |
| **Backend/DB** | Google Apps Script (GAS) & Google Sheets |
| **Hosting** | GitHub Pages |

---

## 📂 Struktur Repositori

```text
├── index.html           # Portal Utama & Dashboard SSO
├── e-arsip.html         # Modul Manajemen Arsip & Surat
├── simpeg.html          # Modul Sistem Informasi Kepegawaian
├── analisis-data.html   # Modul Visualisasi & Laporan Statistik
└── README.md            # Dokumentasi Sistem
