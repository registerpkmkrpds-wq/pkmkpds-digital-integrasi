# 🛡️ Integrated Health Intelligence System (IHIS) v3.1

### [PKM Kiarapedes - Digital Transformation Unit]

IHIS v3.1 adalah ekosistem manajemen berbasis web yang dibangun untuk memfasilitasi audit data klinis dan finansial secara presisi.

## 🔐 Protokol Keamanan Data
- **Session Layer:** Autentikasi berbasis Local-Token (Sesi berakhir otomatis saat logout).
- **Encryption:** Seluruh data yang diolah bersifat *Client-Side* (Tidak ada data yang dikirim ke server pihak ketiga).
- **Audit Trail:** Sinkronisasi antar modul menggunakan `localStorage` dengan validasi silang (Cross-Check Validation).

## 📊 Business Logic Integrasi
Dashboard ini menggunakan logika **"Denormalized Data Flow"**:
1. Modul **Analitik Medis** berfungsi sebagai *Data Collector*.
2. Modul **Finance Intel** berfungsi sebagai *Data Auditor* (Mengkonsumsi data dari kolektor).
3. Modul **Command Center** berfungsi sebagai *Executive Summary*.

## 🚀 Deployment Strategis
Untuk hasil terbaik, jalankan sistem pada:
- **Environment:** Chrome/Edge Chromium v110+.
- **Display:** Resolusi minimal 1920x1080 (Optimized for Large Monitor Command Center).
