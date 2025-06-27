🍎 Perbandingan Deteksi Cacat Buah Apel Menggunakan Adaptive Threshold dan Segmentasi Tepi Sobel

📋 **Deskripsi**

Program ini merupakan aplikasi sederhana berbasis Python yang bertujuan untuk melakukan **deteksi cacat pada buah apel** menggunakan teknik **computer vision** dan **image processing**, melalui dua pendekatan utama:

- **Adaptive Thresholding** untuk deteksi berbasis intensitas piksel lokal.
- **Segmentasi Tepi menggunakan operator Sobel** untuk mendeteksi batasan tegas pada cacat permukaan.

Proyek ini mengimplementasikan perbandingan visual dan kuantitatif dari kedua metode untuk mengevaluasi efektivitas masing-masing dalam mengidentifikasi area cacat pada citra buah apel.

Program dirancang untuk berjalan di lingkungan **Google Colab**, menggunakan pustaka populer seperti OpenCV, NumPy, dan Matplotlib.

---

⚙️ **Fitur Utama**

- Upload gambar buah apel (format .jpg / .png) melalui Google Colab.
- Pre-processing citra menggunakan konversi ke grayscale dan Gaussian blur.
- Deteksi cacat menggunakan:
  - **Adaptive Thresholding** dengan parameter yang dapat disesuaikan.
  - **Sobel Edge Detection** untuk mengekstraksi tepi cacat.
- Post-processing dengan **morphological operations** untuk mengurangi noise.
- Visualisasi hasil segmentasi dari kedua metode secara berdampingan.
- Analisis perbandingan hasil deteksi untuk menilai akurasi visual.

---

🔧 **Teknologi & Pustaka yang Digunakan**

- Python 3.x  
- Google Colab  
- NumPy  
- Matplotlib  
- scikit-image

---

🚀 **Cara Menjalankan Program**

1. Buka **Google Colab** dan unggah file notebook `.ipynb` dengan nama:
2. Jalankan setiap sel secara berurutan.
3. Ketika diminta, unggah gambar buah apel yang ingin dianalisis.
4. Program akan menampilkan:
- Gambar asli dan citra grayscale
- Hasil deteksi menggunakan Adaptive Threshold
- Hasil segmentasi tepi menggunakan operator Sobel
- Perbandingan visual antar metode
- Opsional: perhitungan luas area cacat

---

📊 **Contoh Output**

Program akan menghasilkan visualisasi lengkap yang mencakup:

- **Original Image**: Citra buah apel asli
- **Grayscale Image**: Hasil konversi ke skala abu-abu
- **Adaptive Threshold Result**: Mask area cacat dengan thresholding adaptif
- **Sobel Edge Result**: Deteksi tepi berdasarkan gradien
- **Comparison Overlay**: Perbandingan hasil kedua metode

---

📈 **Evaluasi**

- **Adaptive Thresholding**: Cocok untuk variasi pencahayaan, namun sensitif terhadap noise.
- **Sobel Edge Detection**: Lebih fokus pada batas cacat, namun dapat melewatkan area bertekstur halus.
- **Visual Clarity**: Hasil segmentasi ditampilkan secara berdampingan untuk kemudahan perbandingan.
- **Kelemahan**: Belum menggunakan evaluasi berbasis ground truth untuk validasi kuantitatif.

---

👨‍🎓 **Penulis**

**Ayu Widya Ningrum**  
Universitas Hasanuddin  
Program Studi Teknik Informatika  
Tugas Besar Mata Kuliah Visi Komputer

---

📄 **Lisensi**

Proyek ini dibuat untuk keperluan akademik. Bebas digunakan untuk pembelajaran dan pengembangan lanjutan dengan mencantumkan atribusi yang sesuai.

---
# Perbandingan-Deteksi-Cacat-Buah-Apel
