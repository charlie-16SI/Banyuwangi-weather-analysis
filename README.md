# 🌤️ Analisis Data Cuaca BMKG Banyuwangi (2010–2024)

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk melakukan pembersihan data (*data cleaning*), penanganan nilai hilang (*missing value imputation*), serta analisis eksploratif data cuaca harian di Kabupaten Banyuwangi berdasarkan data Badan Meteorologi, Klimatologi, dan Geofisika (BMKG).

## 🛠️️ Metodologi & Alur Kerja
1. **Data Cleaning**: Mengidentifikasi dan mengganti kode placeholder BMKG (seperti `8888`, `9999`, dan `-`) menjadi nilai `NaN`.
2. **Imputasi Data**: Mengisi nilai hilang menggunakan teknik pemulihan deret waktu (*time series imputation*).
3. **Feature Engineering**: Ekstraksi komponen tanggal menjadi elemen tahun, bulan, dan hari untuk analisis musiman.
4. **Analisis Korelasi & EDA**: Mengukur hubungan antarvariabel cuaca seperti suhu rata-rata (`TAVG`), kelembapan (`RH_avg`), dan curah hujan (`RR`).

## 🔑 Temuan Utama (Insights)
- *(Tuliskan 2-3 poin temuan paling menarik dari analisis Anda, misalnya tren kenaikan suhu harian atau bulan dengan curah hujan tertinggi)*.

## 🚀 Cara Menjalankan Notebook
1. Clone repositori ini:
   ```bash
   git clone [https://github.com/username-anda/bmkg-weather-analysis.git](https://github.com/username-anda/bmkg-weather-analysis.git)
