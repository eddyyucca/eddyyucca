# 🚀 TradingMetrics-AI

> Developed by Eddy Adha Saputra

Alat analisis teknikal untuk trading crypto dengan visualisasi berwarna, rekomendasi manajemen risiko, dan fitur live monitoring.

[![GitHub](https://img.shields.io/badge/GitHub-TradingMetrics--AI-black?style=flat&logo=github)](https://github.com/eddyyucca/TradingMetrics-AI)
[![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat&logo=python)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-F16061?style=flat&logo=ko-fi&logoColor=white)](https://ko-fi.com/eddyyucca)

## ✨ Fitur

- 📊 Analisis multi-indikator (RSI, MACD, Bollinger Bands, dll)
- 💹 Support untuk 20+ cryptocurrency populer (BTC, ETH, BNB, dll)
- 🎯 Rekomendasi entry point dan exit levels
- ⚠️ Manajemen risiko dengan multiple stop loss
- 📈 Take profit berdasarkan volatilitas
- 🎨 Output berwarna di terminal
- 🔄 **NEW:** Mode live monitoring untuk pantau beberapa aset sekaligus
- 📱 **NEW:** Tampilan tabel keputusan trading real-time
- ⏱️ **NEW:** Interval refresh yang dapat disesuaikan

## 🗂 Struktur Kode

```
TradingMetrics-AI/
│
├── main.py              # Program utama dengan analisis single crypto
├── main2.py             # Program baru dengan fitur live monitoring
├── analysis.py          # Logika analisis teknikal
├── decision.py          # Sistem pengambilan keputusan
├── requirements.txt     # Dependencies
└── README.md            # Dokumentasi
```

### Penjelasan File

- `main.py`: User interface dan logika utama program original
- `main2.py`: **NEW!** Versi baru dengan fitur live monitoring dan tabel keputusan
- `analysis.py`: Fungsi-fungsi analisis teknikal
- `decision.py`: Algoritma keputusan trading
- `tradingmetrics_config.json`: File konfigurasi untuk menyimpan aset yang dipantau

## 🛠 Teknologi

- Python 3.8+
- Pandas untuk analisis data
- PyGecko API untuk data market
- Tabulate untuk tampilan tabel
- Threading untuk monitoring live
- Colorama & Termcolor untuk visualisasi

## 📦 Instalasi

1. Pastikan Python 3.8+ terinstall

```bash
python --version
```

2. Clone repository

```bash
git clone https://github.com/eddyyucca/TradingMetrics-AI.git
cd TradingMetrics-AI
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

## 🚀 Cara Penggunaan

### Versi Original

```bash
python main.py
```

### Versi Baru dengan Live Monitoring

```bash
python main2.py
```

### Menu Utama (Versi Baru)

Pilih opsi yang tersedia:

1. **Analisis Single Crypto** - Analisis mendalam untuk satu aset
2. **Mode Live Monitoring** - Pantau beberapa aset secara real-time
3. **Kelola Aset yang Dipantau** - Tambah/hapus aset untuk monitoring
0. **Keluar** - Keluar dari program

### Analisis Single Crypto

- Pilih dari 20 cryptocurrency populer
- Pilih timeframe (15m, 30m, 1h, 4h)
- Lihat analisis detail dan keputusan trading
- Opsi untuk menambahkan ke daftar pantauan live

### Mode Live Monitoring

- Pantau beberapa aset secara bersamaan
- Tabel keputusan trading yang update secara otomatis
- Diurutkan berdasarkan tingkat keyakinan tertinggi
- Refresh otomatis dengan interval yang dapat disesuaikan

### Kelola Aset yang Dipantau

- Tambah aset baru untuk dipantau
- Hapus aset dari daftar pantauan
- Atur interval refresh data (minimal 30 detik)

## 📊 Contoh Output Live Monitoring

```
=== LIVE TRADING DECISIONS ===
Last Update: 2025-03-04 01:10:25
+------------+------------+------------+------------+------------+------------+-------------------+
| Coin       | Harga      | Aksi       | Keyakinan  | Timeframe  | Volatilitas| Waktu Update     |
+============+============+============+============+============+============+===================+
| BTC/USDT   | $65,890.12 | STRONG_BUY | 95.7%      | 1h         | 2.31%      | 01:10:22         |
+------------+------------+------------+------------+------------+------------+-------------------+
| ETH/USDT   | $3,127.45  | BUY        | 78.3%      | 15m        | 3.45%      | 01:10:23         |
+------------+------------+------------+------------+------------+------------+-------------------+
| SOL/USDT   | $128.67    | HOLD       | 62.1%      | 4h         | 4.82%      | 01:10:24         |
+------------+------------+------------+------------+------------+------------+-------------------+
| DOGE/USDT  | $0.1432    | SELL       | 82.5%      | 30m        | 5.67%      | 01:10:25         |
+------------+------------+------------+------------+------------+------------+-------------------+
```

## 🔄 Fitur Tambahan

- **Penyimpanan Konfigurasi**: Aset yang dipantau dan interval refresh disimpan antar sesi
- **Pemantauan Multi-Timeframe**: Pantau aset yang sama di berbagai timeframe sekaligus
- **Peringkat Keputusan**: Keputusan trading diurutkan berdasarkan keyakinan tertinggi
- **User Interface yang Lebih Baik**: Menu terstruktur dengan navigasi yang jelas

## 📡 Sumber Data

Program ini menggunakan CoinGecko API untuk mendapatkan data cryptocurrency, mengatasi masalah SSL/API yang umum terjadi pada API lain.

## ⚠️ Disclaimer

- Ini adalah alat analisis teknikal, bukan rekomendasi trading
- Selalu gunakan manajemen risiko yang baik
- Past performance tidak menjamin hasil di masa depan
- DYOR (Do Your Own Research)

## 📄 Lisensi

MIT License - lihat file [LICENSE](LICENSE) untuk detail

## 🤝 Kontribusi

Kontribusi selalu diterima! Feel free untuk membuat pull request atau melaporkan issues.

## 👨‍💻 Developer

**Eddy Adha Saputra**

[![GitHub](https://img.shields.io/badge/GitHub-eddyyucca-black?style=flat&logo=github)](https://github.com/eddyyucca)
[![Email](https://img.shields.io/badge/Email-eddyyucca%40gmail.com-red?style=flat&logo=gmail)](mailto:eddyyucca@gmail.com)
[![Ko-Fi](https://img.shields.io/badge/Support%20Me%20on%20Ko--fi-F16061?style=flat&logo=ko-fi&logoColor=white)](https://ko-fi.com/eddyyucca)

---

<p align="center">
  <a href="https://ko-fi.com/eddyyucca">
    <img src="https://storage.ko-fi.com/cdn/kofi3.png?v=3" alt="Buy Me A Coffee at ko-fi.com" height="45">
  </a>
</p>

Made with ❤️ in Indonesia
