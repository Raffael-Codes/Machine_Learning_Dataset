# Tugas Machine Learning - Sign Language MNIST Classification

Repositori ini berisi kumpulan kodingan Jupyter Notebook untuk tugas mata kuliah Machine Learning, yang berfokus pada klasifikasi gambar bahasa isyarat menggunakan dataset Sign Language MNIST dari Kaggle.

## 👨‍🎓 Identitas Mahasiswa
* **Nama** : [Masukkan Nama Lengkap Anda di sini]
* **NIM** : [Masukkan NIM Anda di sini]
* **Kelas** : [Masukkan Kelas Anda di sini]

## 📝 Deskripsi Proyek
Proyek ini bertujuan untuk membangun dan melatih model *Deep Learning* menggunakan pustaka **TensorFlow** dan **Keras** untuk mengenali abjad bahasa isyarat (American Sign Language). 

Beberapa tahapan yang dilakukan dalam tugas ini meliputi:
1. Pengenalan antarmuka Jupyter Notebook.
2. Memuat dan menyiapkan (preprocessing) dataset gambar berskala abu-abu (grayscale).
3. Melakukan *reshaping* dan normalisasi data gambar.
4. Membangun model jaringan saraf tiruan (Neural Network / CNN).
5. Melatih model dan mengevaluasi tingkat akurasi (Loss & Accuracy).

## 📂 Struktur File
File kodingan utama yang ada di dalam repositori ini:
* `00_jupyterlab.ipynb` : Pengenalan lingkungan Jupyter Notebook.
* `01_mnist.ipynb` : Pelatihan dasar model pada dataset MNIST.
* `02_asl.ipynb` : Persiapan data dan pelatihan model dasar pada dataset Sign Language.
* *(File .ipynb dan .png lainnya yang mendukung proses pelatihan model).*

> **Catatan:** Dataset `.csv` tidak disertakan di repositori ini karena ukuran file yang terlalu besar untuk batas standar GitHub, namun kodingan sudah disesuaikan agar bisa langsung dijalankan dengan dataset lokal di folder yang sama.

## 🚀 Cara Menjalankan Kodingan
Jika ingin menjalankan ulang kodingan ini di komputer lokal:
1. Pastikan Python dan Jupyter Notebook sudah terinstal.
2. Instal *library* yang dibutuhkan dengan menjalankan perintah:
   `pip install pandas numpy matplotlib tensorflow`
3. Unduh dataset Kaggle dari tautan berikut: [Sign Language MNIST](https://www.kaggle.com/datasets/datamunge/sign-language-mnist)
4. Ekstrak file dataset dan letakkan `sign_mnist_train.csv` serta `sign_mnist_test.csv` di folder yang sama dengan file kodingan `.ipynb`.
5. Buka Jupyter Notebook dan jalankan sel kode dari atas ke bawah.
