# 📊 Clustering and Classification with K-Means

Repository ini berisi implementasi machine learning untuk melakukan proses **clustering** dan **klasifikasi** data menggunakan Python dalam format Jupyter Notebook (`.ipynb`). Dataset yang dipakai yaitu dataset SyntheticBeverage yang diambil dari open data Kaggle.

## 🔍 Deskripsi

- Clustering menggunakan algoritma **K-Means** untuk membentuk *cluster* dari dataset berdasarkan fitur utamanya.
- Setelah proses clustering, dilakukan tahap **klasifikasi** dengan beberapa algoritma klasifikasi untuk mencari model dengan akurasi terbaik. Klasifikasi dilakukan untuk mengelompokkan data ke dalam kelas yang relevan berdasarkan hasil clustering sebelumnya. Hasil yang akan didapat akan terjadi overfitting dikarenakan model terlalu mempelajari data.
- Dataset yang digunakan merupakan dataset Synthetic Beverages. Dikarenakan dataset terlalu besar, maka dari itu saya melakukan pemotongan dataset. Dan hanya memakai 20 ribu baris data.

## 🛠 Teknologi dan Library

- Python 3
- Jupyter Notebook
- `scikit-learn`
- `pandas`
- `matplotlib`
- `seaborn`

## 📁 Struktur Folder

```
.
├── clustering/            # Notebook untuk proses clustering dengan K-Means
├── classification/        # Notebook untuk model klasifikasi
├── dataset/               # Dataset yang digunakan
└── README.md
```

## 🚀 Cara Menjalankan

1. Clone repository ini:
   ```bash
   Lahen194/ProjekMachineLearning-SyntheticBeverages.git
   ```
2. Buka folder project dan jalankan Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Jalankan notebook dalam folder `clustering/` terlebih dahulu, lalu lanjutkan ke `classification/`.
4. Dataset tidak perlu diupload ke lokal. Karena dataset dapat diakses dengan gdrive.

## 🧠 Tujuan Proyek

Mengeksplorasi pemrosesan data dengan pendekatan unsupervised dan supervised learning secara berurutan untuk memahami struktur data dan melakukan prediksi. Projek ini dilakukan untuk memenuhi penugasan pembelajaran 'Machine Learning Pemula' dicoding.

## 📌 Catatan

- Pastikan dataset sudah tersedia di folder `data/`.
- Proyek ini dapat dikembangkan lebih lanjut dengan evaluasi model, hyperparameter tuning, atau visualisasi hasil clustering lebih mendalam.
- Projek ini berhasil mendapat 5 bintang dari reviewer tim Dicoding.
