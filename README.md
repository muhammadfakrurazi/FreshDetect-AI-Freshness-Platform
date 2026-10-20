# FreshDetect V3.0 - AI Freshness Detection Platform
Aplikasi web modern berbasis AI YOLOv8 untuk mengukur tingkat kesegaran bahan pangan secara instan dan mencegah food waste.

## 📁 Struktur Direktori
```text
Rice Detection/
├── backend/
│   ├── models/
│   ├── .env
│   ├── .env.example
│   ├── app.py
│   ├── requirements.txt
│   └── yolov8n.pt
├── js/
│   ├── app.js
│   └── history.js
├── css/
│   └── style.css
├── .gitignore
├── index.html            <-- Beranda & Hero Showcase (© 2026 FreshDetect V3.0)
├── deteksi.html          <-- Upload Citra / Kamera / Preset Sampel (Algoritma Kalibrasi 2026)
├── hasil.html            <-- Hasil Analisis AI & Panduan Penyimpanan (Audit Log 2026)
├── riwayat.html          <-- Riwayat Scan & Ekspor Excel (SheetJS 2026)
├── manifest.json         <-- PWA Manifest & App Config 2026
└── README.md
```

## 🚀 Cara Menjalankan

### 1. Backend Flask & Model AI
```bash
cd backend
python -m venv venv
# Aktifkan virtual environment:
# Windows: venv\Scripts\activate
# Linux/macOS: source venv/bin/activate
pip install -r requirements.txt
python app.py
```
Backend berjalan pada: `http://localhost:5000`

### 2. Frontend
Buka file `index.html` langsung melalui browser atau gunakan Live Server:
```bash
npx serve .
# atau VS Code Live Server
```

## 🛠️ Tech Stack & Standar Kepatuhan
- **Frontend**: HTML5, Tailwind CSS, Lucide Icons, SheetJS (XLSX).
- **Backend**: Python 3.10+, Flask, Flask-CORS, OpenCV, Pillow.
- **AI/ML**: Ultralytics YOLOv8 (`yolov8n.pt` / custom trained freshness weight).
- **Standar Validasi**: Algoritma Kalibrasi 2026 & Protokol Mutu ISO 22000.
- **Hak Cipta**: © 2026 FreshDetect V3.0. Automated Bio-Freshness Analytics.
