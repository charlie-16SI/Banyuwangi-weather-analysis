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

## 🔑 Temuan Utama (Key Insights)

- 🌧️ **Pola Curah Hujan Musiman**: Puncak curah hujan tertinggi di Banyuwangi terjadi pada bulan **[misal: Desember – Februari]** dengan rata-rata **[misal: XX mm/hari]**, sedangkan periode terkering terjadi pada bulan **[misal: Agustus – September]**.
- 🌡️ **Korelasi Suhu & Kelembapan**: Terdapat korelasi negatif yang kuat ($r = \mathbf{-0.XX}$) antara Suhu Rata-rata (`TAVG`) dan Kelembapan Udara (`RH_avg`), di mana lonjakan suhu harian selalu diikuti dengan penurunan kelembapan udara secara signifikan.
- 📉 **Kualitas Data & Cleansing**: Berhasil membersihkan dan mengimputasi **[misal: X%]** data hilang yang menggunakan kode *placeholder* BMKG (`8888`, `9999`, `-`) sehingga distribusi data deret waktu (2010–2024) kembali konsisten.
- ☀️️ **Tren Suhu Ekstrem**: Fluktuasi suhu maksimum harian (`TX`) tercatat mencapai titik tertinggi sebesar **[misal: 35.2°C]** pada bulan **[misal: Oktober]**.
