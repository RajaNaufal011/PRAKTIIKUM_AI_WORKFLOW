# PRAKTIIKUM_AI_WORKFLOW
Raja Naufal Fadhil_2306020
Deskripsi Proyek
Proyek ini bertujuan untuk mengimplementasikan kecerdasan buatan (AI) dalam menganalisis serta memprediksi penjualan produk. Proses pengembangannya mencakup beberapa tahapan utama sebagai berikut:

Pembuatan Dataset – Menyusun dataset penjualan dalam format CSV yang memuat informasi terkait produk, jumlah penjualan, stok, dan harga satuan.
Pembersihan dan Pengolahan Data – Melakukan pemrosesan data guna memastikan kelengkapan, kebersihan, serta kesiapan dataset untuk digunakan dalam model AI.
Pelatihan Model AI – Menerapkan algoritma Decision Tree Classifier untuk memprediksi kebutuhan restock produk berdasarkan data penjualan yang tersedia.
Prediksi dan Visualisasi – Menggunakan model yang telah dilatih untuk melakukan prediksi serta menyajikan visualisasi hubungan antara jumlah penjualan, stok, dan keuntungan.
Instruksi Menjalankan Kode di Google Colab
Membuka Google Colab

Akses Google Colab melalui peramban.
Pilih opsi "Unggah" dan unggah file praktikum_ai.ipynb.
Menjalankan Notebook

Jalankan setiap sel kode secara berurutan.
Jika terdapat dependensi tambahan yang diperlukan, eksekusi perintah berikut pada sel kode:
python
Copy
Edit
!pip install scikit-learn
Mengakses File di Google Drive (Opsional)

Jika dataset atau model tersimpan di Google Drive, hubungkan akun dengan perintah berikut:
python
Copy
Edit
from google.colab import drive
drive.mount('/content/drive')
Pastikan seluruh dependensi telah terinstal dan file yang diperlukan telah diunggah dengan benar agar kode dapat dijalankan tanpa kendala. Jika terjadi masalah, periksa kembali dependensi dan ketersediaan file di Google Colab.
