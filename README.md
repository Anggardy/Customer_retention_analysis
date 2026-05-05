# 📊 Project Overview: Customer Retention Analysis Retail Shop

## Business Problem
### Masalah
Biaya akuisisi pelanggan baru (CAC) terus meningkat. Saya ingin beralih fokus ke Customer Retention. Kita perlu tahu apakah pelanggan yang berbelanja di awal tahun (Januari - Maret) masih melakukan transaksi di akhir tahun, atau apakah mereka hanya mencoba sekali lalu menghilang.

### Tujuan
- Melakukan analisis cohort terhadap tiap pelanggan.

## Alur Kerja
- Import data
- Clean data (Merubah format)
- Melakukan analisis Cohort
- Visualisasi

## Tech Stack & Tools
- Bahasa : Python
- Tools : Google Colab
- Konsep : Cohort Analysis

## Insight
![Heatmap_Retention_Analysis](/image.png)  
Berdasarkan hasil analisis yang telah dilakukan, terlihat bahwa hampir di semua lini tidak ada customer yang memiliki retention rate di atas 50%. Nilai tertinggi hanya terjadi pada pembelian pertama di bulan Februari pada bulan kedua. Hal ini mengindikasikan bahwa hanya sedikit customer yang customer yang berbelanja berulang. Nilai terkecil didapat pada bulan Mei di bulan ke-2 dan ke-3, kemudian bulan Juni di bulan ke-2 dengan retention rate hanya 2%.  

## Rekomendasi
- Perlu dilakukan analisis yang lebih mendalam pada bulan tertentu, misalnya bulan Mei dan bulan Juni mengapa penurunannya bisa sangat rendah.
- Buat sebuah program tiap bulan seperti pemberian voucher belanja dan sejenisnya atau untuk menekan anggaran, lakukan program ini pada bulan-bulan tertentu.
