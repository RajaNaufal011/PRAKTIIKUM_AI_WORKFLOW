# PRAKTIIKUM_
Raja Naufal Fadhil_2306020

## **Analisis dan Prediksi Penjualan Produk dengan Kecerdasan Buatan**

### **Deskripsi Proyek**
Proyek ini bertujuan untuk mengimplementasikan kecerdasan buatan (AI) dalam menganalisis serta memprediksi penjualan produk. Proses yang dilakukan mencakup pembuatan dataset, pembersihan data, pelatihan model AI menggunakan *Decision Tree Classifier*, serta visualisasi hasil prediksi.

### **Tahapan Implementasi**
1. **Pembuatan Dataset**  
   - Dataset dibuat dalam format CSV yang berisi informasi produk, jumlah penjualan, stok, dan harga satuan.

2. **Pembersihan dan Pengolahan Data**  
   - Memastikan data dalam kondisi bersih, lengkap, dan siap digunakan untuk pelatihan model AI.

3. **Pelatihan Model AI**  
   - Menggunakan algoritma *Decision Tree Classifier* untuk memprediksi apakah suatu produk perlu di-*restock* berdasarkan data penjualan yang tersedia.

4. **Prediksi dan Visualisasi**  
   - Menggunakan model yang telah dilatih untuk membuat prediksi serta menyajikan visualisasi hubungan antara jumlah terjual, stok, dan keuntungan.

---

### **Cara Menjalankan Kode di Google Colab**

#### **1. Membuka Google Colab**
- Akses Google Colab melalui peramban.
- Pilih opsi "Unggah" dan unggah file `praktikum_ai.ipynb`.

#### **2. Menjalankan Notebook**
- Jalankan setiap sel kode secara berurutan.
- Jika terdapat dependensi tambahan yang diperlukan, jalankan perintah berikut di dalam sel kode:
  ```python
  !pip install scikit-learn
  ```

#### **3. Mengakses File di Google Drive (Opsional)**
- Jika dataset atau model tersimpan di Google Drive, hubungkan akun dengan perintah berikut:
  ```python
  from google.colab import drive
  drive.mount('/content/drive')
  ```

---


