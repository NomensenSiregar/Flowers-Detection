
# 🌸 Flower Classification using CNN

Proyek ini bertujuan untuk membangun **model klasifikasi gambar bunga** menggunakan **Convolutional Neural Network (CNN)**. Dataset gambar bunga dilatih menggunakan arsitektur CNN sederhana untuk mengenali berbagai jenis bunga seperti dandelion, daisy, rose, sunflower, dan tulip.

Notebook ini dikembangkan menggunakan **Google Colab** dan menggunakan **TensorFlow** serta **Keras** untuk membangun dan melatih model klasifikasi citra.

---

## 🎯 Tujuan Proyek

- Membangun model klasifikasi citra bunga berbasis CNN
- Melatih model menggunakan dataset bunga multi-kelas
- Mengukur performa model dengan metrik akurasi dan loss
- Visualisasi hasil pelatihan dan pengujian

---

## ✅ Fitur Utama

- 📦 Dataset bunga 5 kelas (dandelion, daisy, rose, sunflower, tulip)
- 🧠 Arsitektur CNN dari awal (custom)
- 📈 Visualisasi akurasi dan loss model
- 🖼️ Uji coba klasifikasi terhadap gambar uji
- 💾 Simpan dan load model dalam format `.h5`

---

## 🛠️ Teknologi & Library

- Python 3
- Google Colab
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

---

## 📁 Struktur Notebook

| Bagian | Deskripsi |
|--------|-----------|
| 1. Import Library | Mengimpor semua library yang dibutuhkan |
| 2. Load Dataset | Menggunakan `image_dataset_from_directory` |
| 3. Preprocessing | Resize, batching, dan normalisasi gambar |
| 4. Build Model | CNN dengan beberapa layer Conv2D dan MaxPooling |
| 5. Training | Model dilatih selama beberapa epoch |
| 6. Evaluation | Visualisasi akurasi dan loss |
| 7. Save & Load Model | Menyimpan model ke file `.h5` dan menguji kembali |
| 8. Predict Image | Mengklasifikasi gambar uji tunggal dan menampilkan prediksi kelas |

---

## 🚀 Cara Menjalankan

1. Buka notebook di Google Colab  
   [Klik di sini](https://colab.research.google.com/drive/1HuI73YVbe0i4LUdq2ioe_4kpCpoH-P1y?usp=sharing)

2. Jalankan semua sel dari atas ke bawah

3. Pastikan dataset tersedia dalam format folder dengan struktur:
   ```
   dataset/
     ├── dandelion/
     ├── daisy/
     ├── rose/
     ├── sunflower/
     └── tulip/
   ```

4. Lihat hasil klasifikasi dan visualisasi training

---

## 🖼️ Contoh Output

```
Gambar: tulip.jpg  
Prediksi Model: 🌷 Tulip (Confidence: 95.3%)
```

---

## 📈 Hasil Training (Contoh)

| Epoch | Akurasi | Loss |
|-------|---------|------|
| 1     | 72%     | 0.61 |
| 10    | 91%     | 0.22 |

Grafik akurasi dan loss divisualisasikan menggunakan `matplotlib`.

---

## 💡 Pengembangan Selanjutnya

- Fine-tuning dengan pretrained model (VGG16, MobileNet)
- Augmentasi gambar
- Deploy model ke Streamlit atau Flask
- Integrasi ke aplikasi mobile atau web

---

## 📜 Lisensi

Proyek ini bersifat open-source dan bebas digunakan untuk keperluan pendidikan dan eksperimen.

---

## 👤 Kontributor

- [Nomensen Siregar](https://github.com/NomensenSiregar)
