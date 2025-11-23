# 🍽️ Average Restaurant: Data-Driven Sales Analysis for Restaurant Performance Optimization
## 🚀 Project Overview

<p align="center">  
<img src="https://cdn-icons-png.flaticon.com/512/3075/3075977.png" alt="Restaurant Icon" width="300"/>  
</p>

---
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Python](https://img.shields.io/badge/Python-3.10-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Data%20Science](https://img.shields.io/badge/Field-Data%20Science-orange)
![Tableau](https://img.shields.io/badge/Visualization-Tableau-blueviolet)


## 📁 Repository Outline
- `README.md` — Dokumentasi utama project  
- `P0M1_yudhistira.ipynb` — Notebook analisis data penjualan restoran  
- `P0M1_yudhistira_dataset.csv` — Dataset mentah  
- `sales_restaurant_clean.csv` — Dataset setelah data cleaning  
- `assignment-rubics.png` — Rubrik penilaian  

---

## 🎯 Problem Background
Dalam industri restoran yang sangat kompetitif, keputusan berbasis data menjadi kunci untuk meningkatkan performa penjualan dan efisiensi operasional.  
Data penjualan dapat membantu owner memahami:

- Produk paling laris  
- Kota dengan pendapatan tertinggi  
- Manajer dengan kontribusi terbesar  
- Tren pendapatan dari waktu ke waktu  
- Pola rata-rata dan varians pendapatan  

Analisis ini memberikan pondasi kuat bagi pengambilan keputusan bisnis yang lebih terukur dan strategis.

---

## 🎯 Project Output
Proyek ini menghasilkan:

- 📊 Analisis rata-rata pendapatan keseluruhan & per kota  
- 🍔 Identifikasi produk makanan atau minuman paling laris  
- 🧑‍💼 Penilaian kontribusi setiap manajer  
- 📈 Dashboard interaktif menggunakan **Tableau**  

Insight ini dapat digunakan owner restoran untuk evaluasi performa, alokasi sumber daya, serta pengambilan keputusan strategis berbasis data.

---

## 📊 Data Overview
**Dataset:** `P0M1_yudhistira_dataset.csv`  
- **Jumlah Baris:** 254  
- **Jumlah Kolom:** 8  
- **Missing Value:** Tidak ada  

Dataset berisi informasi terkait:  
- Kota  
- Produk  
- Manajer  
- Kuantitas  
- Pendapatan  
- Tanggal pemesanan  

Data telah melalui proses cleaning dan hasilnya disimpan pada file `sales_restaurant_clean.csv`.

---

## ⚙️ Methodology

### 1️⃣ Statistik Deskriptif  
Untuk mengetahui rata-rata, varians, dan distribusi pendapatan & kuantitas.

### 2️⃣ Statistik Inferensial (ANOVA)  
Mengetahui apakah terdapat perbedaan signifikan pendapatan antar kota.

### 3️⃣ Visualisasi Data  
Menggunakan Matplotlib & Tableau untuk memetakan pola penjualan dan tren pendapatan.

---

## 🧠 Insight Utama

- **Lisbon** menjadi kota dengan pendapatan tertinggi, dipengaruhi oleh performa beberapa restoran yang secara konsisten menghasilkan revenue besar.
- **Paris & Berlin** menunjukkan pola pendapatan yang stabil namun relatif rendah, sehingga berpotensi menjadi fokus utama untuk strategi peningkatan performa.
- Produk yang paling sering dibeli berasal dari kategori **makanan cepat saji**, menunjukkan preferensi konsumen terhadap menu yang cepat, mudah, dan terjangkau (*high-demand & affordable*).
- Varians pendapatan antar kota tergolong tinggi, mengindikasikan perbedaan efektivitas manajemen dan potensi optimasi strategi berdasarkan lokasi.
---

## 💡 Business Recommendation
Berdasarkan hasil analisis deskriptif, tren waktu, dan uji ANOVA, berikut rekomendasi strategis yang dapat diterapkan oleh restoran:
- **Optimalkan strategi pemasaran di Paris & Berlin**, karena kedua kota menunjukkan performa pendapatan yang lebih rendah dibanding kota lainnya. Fokuskan promosi lokal, evaluasi lokasi, serta perbaikan operasional cabang.
- **Fokus pada kategori makanan terlaris** untuk meningkatkan volume penjualan, misalnya melalui bundling, upselling, atau peningkatan tampilan menu.
- **Terapkan best practice dari manajer berperforma tinggi** ke seluruh cabang untuk meningkatkan konsistensi operasional dan produktivitas antar-manajer.
- **Pantau tren pendapatan secara berkala** (bulanan/mingguan) untuk mendeteksi perubahan pola penjualan dan mengambil keputusan cepat berbasis data.

---

## 🧩 Tech Stack
- Python  
- Pandas  
- Numpy  
- Matplotlib  
- Scipy  
- Statsmodels  
- Tableau  

---

## 📚 Reference
- Dataset: Kaggle  
- Dashboard Tableau:  
  https://public.tableau.com/app/profile/yudhistira.pandu.dewonoto/viz/DashboardRestaurant_17575156728100/DashboardRestaurant

---

<p align="center">  
<img src="https://cdn-icons-png.flaticon.com/512/2920/2920283.png" alt="Food Icon" width="120"/>  
</p>

