# Monthly Expense Tracker Web App

Monthly Expense Tracker adalah aplikasi web yang dirancang untuk membantu pengguna mencatat, mengelola, dan menganalisis pengeluaran bulanan secara otomatis dan terstruktur. Aplikasi ini memanfaatkan teknologi pemindaian struk dan integrasi digital payment untuk mempermudah proses pencatatan transaksi tanpa input manual yang merepotkan.

## Tujuan Project

Membantu pengguna memahami pola pengeluaran mereka, mengontrol keuangan pribadi, dan membuat keputusan finansial yang lebih bijak melalui data yang terorganisir dan visualisasi statistik yang informatif.

## Fitur Utama

### 1. Scan Struk Otomatis (OCR-Based Receipt Scanner)
Pengguna dapat mengunggah atau memfoto struk belanja, kemudian sistem akan:
- Mengekstrak tanggal transaksi
- Membaca total pembayaran
- Mendeteksi nama toko
- Mengelompokkan item (jika memungkinkan)
- Mengkategorikan pengeluaran secara otomatis

Teknologi yang digunakan: OCR (Optical Character Recognition) + text processing.

### 2. Integrasi E-Wallet / Mobile Banking (Opsional)
Aplikasi dapat mendeteksi transaksi langsung dari layanan pembayaran digital seperti:
- GoPay
- OVO
- DANA
- ShopeePay

Melalui:
- Import file mutasi (.csv/.xlsx)
- API integration (jika tersedia)
- Email parsing notifikasi transaksi (opsional)

Fitur ini memungkinkan pencatatan transaksi otomatis tanpa perlu input manual.

### 3. Statistik & Analisis Pengeluaran
Dashboard interaktif yang menampilkan:
- Diagram pengeluaran berdasarkan kategori (makanan, transport, hiburan, dll.)
- Grafik tren pengeluaran bulanan
- Perbandingan bulan ke bulan

Insight otomatis seperti:
- “Pengeluaran terbesar bulan ini ada di kategori Food & Beverage.”
- “Pengeluaran meningkat 18% dibanding bulan lalu.”

Visualisasi dapat berupa:
- Pie chart
- Bar chart
- Line chart
- Summary card analytics

## Value Proposition
- Hemat waktu (tidak perlu catat manual)
- Lebih akurat dengan scan otomatis
- Insight keuangan berbasis data
- Membantu budgeting & financial awareness

## Teknologi yang Bisa Digunakan
Frontend: React / Vue / Next.js
Backend: Node.js / Express atau Laravel
Database: PostgreSQL / MySQL
Tambahan: OCR Engine (Tesseract / Google Vision API)
Chart library (Chart.js / ECharts / Recharts)
Authentication (JWT / OAuth)
