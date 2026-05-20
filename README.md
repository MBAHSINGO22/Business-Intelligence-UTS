<h1 align="center">Healthcare Data Cleaning using Python</h1>

<p align="center">
  Project pembersihan dan preprocessing data kesehatan menggunakan Python
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Processing-yellow?style=for-the-badge">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
</p>

<hr>

<h2>📌 Tentang Project</h2>

<p>
Project ini berfokus pada proses data cleaning dan preprocessing dataset kesehatan menggunakan Python.
Tahapan pembersihan data dilakukan untuk meningkatkan kualitas dataset agar siap digunakan dalam proses analisis data, visualisasi, maupun machine learning.
</p>

<p>
Proses data cleaning sangat penting karena data mentah sering kali memiliki missing value, data duplikat, inkonsistensi format, dan noise yang dapat mempengaruhi hasil analisis.
</p>

<hr>

<h2>🎯 Tujuan Project</h2>

<ul>
  <li>Membersihkan dataset kesehatan dari data yang tidak valid</li>
  <li>Menangani missing value</li>
  <li>Menghapus data duplikat</li>
  <li>Melakukan standarisasi format data</li>
  <li>Mempersiapkan dataset untuk analisis dan machine learning</li>
</ul>

<hr>

<h2>🛠 Teknologi yang Digunakan</h2>

<ul>
  <li>Python</li>
  <li>Pandas</li>
  <li>NumPy</li>
  <li>Jupyter Notebook</li>
</ul>

<hr>

<h2>⚙️ Fitur Utama</h2>

<ul>
  <li>Import dataset kesehatan</li>
  <li>Pengecekan missing value</li>
  <li>Pembersihan data kosong</li>
  <li>Penghapusan data duplikat</li>
  <li>Perbaikan format data</li>
  <li>Analisis struktur dataset</li>
  <li>Export dataset hasil cleaning</li>
</ul>

<hr>

<h2>📂 Struktur Project</h2>

<pre>
project-folder/
│
├── Data_Cleaning_Kesehatan.ipynb
└── README.md
</pre>

<hr>

<h2>🚀 Instalasi</h2>

<p>Clone repository:</p>

<pre>
git clone https://github.com/username/nama-repository.git
</pre>

<p>Masuk ke folder project:</p>

<pre>
cd nama-repository
</pre>

<p>Install dependency:</p>

<pre>
pip install pandas numpy
</pre>

<hr>

<h2>▶️ Cara Menjalankan</h2>

<ol>
  <li>Buka file <b>Data_Cleaning_Kesehatan.ipynb</b> menggunakan Jupyter Notebook atau Google Colab</li>
  <li>Jalankan seluruh cell notebook secara berurutan</li>
  <li>Lihat proses pembersihan data</li>
  <li>Gunakan dataset hasil cleaning untuk analisis lanjutan</li>
</ol>

<hr>

<h2>📊 Tahapan Data Cleaning</h2>

<ul>
  <li>Import dataset</li>
  <li>Pemeriksaan struktur data</li>
  <li>Pengecekan missing value</li>
  <li>Pembersihan nilai kosong</li>
  <li>Penghapusan data duplikat</li>
  <li>Standarisasi format data</li>
  <li>Validasi dataset hasil cleaning</li>
</ul>

<hr>

<h2>💻 Contoh Kode</h2>

<pre>
import pandas as pd

data = pd.read_csv("dataset_kesehatan.csv")

data.isnull().sum()

data.drop_duplicates(inplace=True)
</pre>

<hr>

<h2>📈 Pengembangan Selanjutnya</h2>

<ul>
  <li>Integrasi visualisasi data kesehatan</li>
  <li>Implementasi machine learning</li>
  <li>Analisis prediksi kesehatan</li>
  <li>Pembuatan dashboard interaktif</li>
  <li>Automasi preprocessing dataset</li>
</ul>

<hr>

<h2>👨‍💻 Author</h2>

<p>
Eugenius Kriswinar Adi Cahya
</p>

<hr>

<h2>📄 License</h2>

<p>
Project ini dibuat untuk kebutuhan pembelajaran dan penelitian.
</p>
