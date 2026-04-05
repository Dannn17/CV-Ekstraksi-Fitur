# Ekstraksi Fitur Citra Mata Uang Rupiah

Proyek ini merupakan pemenuhan tugas mata kuliah **Computer Vision**. Fokus utama proyek ini adalah melakukan ekstraksi fitur digital dari mata uang kertas Rupiah untuk dianalisis karakteristik visualnya.

## 📋 Cakupan Tugas (Poin 1-4)
1. **Dataset:** 10 citra mata uang (Rp100k, Rp50k, Rp20k, Rp10k, Rp5k) dengan 2 variasi emisi berbeda per nominal.
2. **Fitur Ekstraksi:** - **Warna (HSV):** Mean & Std Deviasi (Hue, Saturation, Value).
   - **Tekstur (GLCM):** Contrast untuk deteksi detail cetakan.
   - **Ukuran/Bentuk:** Circularity, Area, dan Aspect Ratio.
3. **Teknologi:** Pemrograman Python menggunakan library OpenCV, NumPy, Pandas, dan Scikit-Image.
4. **Output:** Hasil ekstraksi disimpan secara otomatis ke dalam file `.xlsx`.

## 📊 Hasil Analisis Singkat
Berdasarkan data yang diperoleh:
* **Fitur Warna (Hue):** Terbukti paling efektif membedakan antar nominal uang.
* **Saturasi:** Uang emisi baru (2022) memiliki nilai saturasi lebih tinggi dibanding emisi lama.
* **Geometri:** Nilai circularity yang rendah secara konsisten memvalidasi bentuk persegi panjang pada seluruh sampel.

## 🚀 Cara Menjalankan
Klik badge **"Open in Colab"** di bagian atas file `.ipynb` untuk menjalankan koding secara langsung di Google Colab.
