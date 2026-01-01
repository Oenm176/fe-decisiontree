# Proyek Feature Enggineering Decision Tree

Repositori ini berisi kode dan analisis untuk Tugas Kelompok UAS mata kuliah Feature Enggineering. Proyek ini berfokus pada pemrosesan data, normalisasi fitur, dan klasifikasi menggunakan algoritma Decision Tree.

## 👥 Anggota Kelompok

Proyek ini dikerjakan oleh tim yang terdiri dari 4 orang:

| No. | Nama Mahasiswa | NIM | Username |
| :---: | :--- | :--- | :--- |
| 1. | **Krispinus Gonsaga** | 5241811004 | [@username](https://github.com/username) |
| 2. | **Nabila anggelia** | 5241811014 | [@username](https://github.com/username) |
| 3. | **Hartono Adji Susanto**| 5241811018 | [@username](https://github.com/username) |
| 4. | **Azhara Kumala Dewi** | 5241811019 | [@username](https://github.com/username) |


## 📂 Struktur Proyek

Struktur direktori disusun untuk memudahkan alur kerja (pipeline) data science:

```text
├── data/                  # Menyimpan dataset mentah (raw data)
│   ├── cleveland.csv      # Dataset Penyakit Jantung (Cleveland)
│   └── glass.csv          # Dataset Identifikasi Kaca (Glass Identification)
│
├── materi_pendukung/      # Referensi teori dan panduan tugas
│   ├── Feature Quality Analysis .pdf
│   ├── Feature Scaling.pdf
│   └── Tugas Kelompok UAS.pdf
│
├── notebooks/             # Jupyter Notebooks (jalankan secara berurutan)
│   ├── 1.data_cleasing.ipynb      # Pembersihan data (handling missing values, dll)
│   ├── 2.data_normalization.ipynb # Skala fitur (Scaling/Normalization)
│   └── 3.decision_tree.ipynb      # Pemodelan dan evaluasi Decision Tree
│
├── venv/                  # Virtual Environment (di-ignore oleh git)
├── requirements.txt       # Daftar library python yang dibutuhkan
└── README.md              # Dokumentasi proyek