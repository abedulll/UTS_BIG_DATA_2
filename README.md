# <div align="center">⛽ UTS Big Data: Sentiment Analysis</div>
<div align="center"><strong>Analisis Sentimen Ulasan Aplikasi MyPertamina di Google Play Store</strong></div>

---

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" alt="Colab">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="HuggingFace">
  <img src="https://img.shields.io/badge/Data%20Mining-Sentiment%20Analysis-red?style=for-the-badge" alt="Data Mining">
</p>

## 👤 Identitas Mahasiswa
* **Nama** : Abdul Rozzaq
* **NIM** : 14022300051
* **Projek**: Ujian Tengah Semester - Big Data

---

## 📝 Deskripsi Projek
Projek ini difokuskan untuk melakukan analisis sentimen terhadap ulasan pengguna pada aplikasi **MyPertamina**. Dengan mengumpulkan data ulasan dari Google Play Store dan memprosesnya menggunakan model *Natural Language Processing* (NLP), projek ini bertujuan untuk mengklasifikasikan opini masyarakat (Positif, Netral, Negatif) terhadap layanan MyPertamina secara otomatis dan objektif.

## 🚀 Fitur Utama
- **Automated Data Scraping**: Ekstraksi ribuan data ulasan terbaru aplikasi MyPertamina secara langsung dari Google Play Store.
- **Sentiment Classification**: Implementasi model NLP (*pre-trained*) dari Hugging Face untuk memprediksi dan melabeli sentimen teks Bahasa Indonesia dengan tingkat akurasi yang tinggi.
- **Comprehensive Data Visualization**: Menghasilkan berbagai metrik visual (grafik distribusi, korelasi rating, dll.) untuk mempermudah pemahaman tren kepuasan pengguna.

## 🛠️ Tech Stack
* **Bahasa Pemrograman:** Python 🐍
* **Data Scraping:** `google-play-scraper`
* **Machine Learning & NLP:** `transformers`, `torch`
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`

## 📊 Hasil Visualisasi
Projek ini dilengkapi dengan visualisasi yang tersimpan pada `grafik_sentimen.png`, mencakup:
1.  **Distribusi Sentimen**: Grafik batang yang membandingkan total ulasan berdasarkan kategori sentimennya.
2.  **Proporsi Ulasan**: Persentase komposisi sentimen dalam bentuk *Donut Chart/Pie Chart*.
3.  **Korelasi Rating & Sentimen**: *Heatmap* untuk memvalidasi keselarasan antara rating bintang (1-5) yang diberikan dengan sentimen hasil prediksi model.
4.  **Tren Sentimen (*Time Series*)**: Pergerakan dan fluktuasi sentimen pengguna dari waktu ke waktu.

## ⚙️ Cara Menjalankan
1.  Buka fail `UTS-BIG_DATA_Analisis_Aplikasi_MYPERTAMINA.ipynb` menggunakan **Google Colab** atau Jupyter Notebook.
2.  Lakukan instalasi dependensi dengan menjalankan sel pertama:
    ```bash
    pip install google-play-scraper transformers torch pandas matplotlib seaborn
    ```
3.  Jalankan seluruh sel kode secara berurutan (*Run All*). Proses ini akan secara otomatis melakukan *scraping*, menyimpan dataset ke dalam `ulasan.Mypertamina.csv`, menganalisis sentimen, dan menampilkan `grafik_sentimen.png`.

---
<div align="center">
  Disusun untuk memenuhi tugas Ujian Tengah Semester (UTS) mata kuliah Big Data.
</div>
