# Analisis Penjualan dan Profit Menggunakan Power BI

Proyek ini merupakan Ujian Akhir Semester (UAS) untuk mata kuliah Inteligensia Bisnis pada Program Studi D3 Sistem Informasi, Fakultas Ilmu Komputer, Universitas Pembangunan Nasional "Veteran" Jakarta. Tujuan utama dari proyek ini adalah membangun *dashboard* interaktif untuk menganalisis performa penjualan, tren profitabilitas, dan memberikan rekomendasi bisnis berbasis data.

---

## 📊 Informasi Dataset
* **Nama Dataset:** Superstore Sales Dataset
* **Sumber:** Kaggle Sample Data
* **Periode Data:** 3 Januari 2014 - 30 Desember 2017
* **Cakupan Geografis:** United States (49 Negara Bagian, 531 Kota, 4 Region)
* **Domain Bisnis:** Retail (B2C & B2B)

---

## 🛠️ Alat dan Teknologi
1. **Google Colab (Python / Pandas):** Digunakan untuk proses *Data Cleaning*, seperti mengubah tipe data menjadi *datetime*, memeriksa *missing value*, dan memastikan dataset bersih sebelum divisualisasikan.
2. **Microsoft Power BI:** Digunakan untuk membangun visualisasi data dan *dashboard* interaktif.

---

## 💡 Insight Utama
* **Tren Penjualan & Margin:** Penjualan tumbuh konsisten dari $484K (2014) menjadi $733K (2017), akan tetapi margin profit secara keseluruhan hanya berada di angka 12,5%.
* **Masalah Profitabilitas:** Pemberian diskon yang berlebihan (>30%) menjadi penyebab utama rusaknya profitabilitas, hingga menghasilkan margin negatif mencapai -119%.
* **Kinerja Wilayah:** Region Central membutuhkan perhatian khusus karena menyumbang 14,9% dari total penjualan, namun hanya menghasilkan sekitar 7,9% dari total profit.
* **Performa Produk:** Kategori *Technology* merupakan penyumbang profit tertinggi (145K), diikuti oleh *Office Supplies* (122,49K). Sebaliknya, sub-kategori *Tables* dan *Bookcases* justru merugikan perusahaan dengan margin negatif.
* **Segmen Pelanggan:** Segmen *Consumer* memberikan kontribusi penjualan terbesar pada hampir seluruh kategori produk.

---

## 🎯 Rekomendasi Bisnis
Berdasarkan hasil analisis *dashboard*, berikut adalah strategi yang direkomendasikan untuk meningkatkan profit perusahaan:
1. **Evaluasi Kebijakan Diskon:** Optimalkan pemberian diskon, terutama pada produk-produk yang memiliki profit margin rendah seperti *Tables*, *Bookcases*, dan *Supplies*.
2. **Fokus Produk Unggulan:** Prioritaskan penjualan, strategi pemasaran, dan pengelolaan persediaan pada kategori *Technology* dan *Office Supplies*.
3. **Fokus Segmen Pasar:** Pusatkan upaya pemasaran pada segmen *Consumer* karena segmen ini memiliki potensi pasar terbesar dan memberikan kontribusi penjualan tertinggi.
4. **Perbaikan Kinerja Region Central:** Lakukan evaluasi menyeluruh terhadap strategi harga, promosi, dan biaya operasional di wilayah Central untuk meningkatkan profitabilitas.
5. **Evaluasi Produk Merugi:** Kurangi fokus penjualan atau pertimbangkan untuk menghentikan produk yang terus-menerus menghasilkan profit negatif (seperti *Tables* dan *Bookcases*) jika tidak ada perbaikan setelah dievaluasi.

---
