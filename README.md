# Image Classification Hama
Proyek ini berisi model klasifikasi gambar yang telah dikembangkan menggunakan TensorFlow. Model kemudian dikonversi ke format TensorFlow.js untuk digunakan di web, dan ke TensorFlow Lite untuk digunakan di aplikasi mobile

## 🔧 Tools & Frameworks
- Python
- TensorFlow
- TensorFlow.js Converter
- TensorFlow Lite

## 📁 Struktur Folder
submission
├───tfjs_model
| ├───group1-shard1of1.bin
| └───model.json
├───tflite
| ├───model.tflite
| └───label.txt
├───saved_model
| ├───saved_model.pb
| └───variables
├───notebook.ipynb
├───README.md
└───requirements.txt

## 🚀 Cara Menjalankan
1. Buka file `notebook.ipynb` di Google Colab.
2. Jalankan seluruh sel untuk mempelajari proses training dan konversi model.
3. Untuk melihat model di browser, buka `tfjs_model/model.json` menggunakan TensorFlow.js di proyek web.
4. Untuk penggunaan mobile, file `.tflite` dan `label.txt` dapat diintegrasikan dalam proyek Android/iOS.

## 🔄 Konversi Model
Model TensorFlow dikonversi ke dua format:
- **TensorFlow.js** menggunakan `tensorflowjs_converter`
- **TensorFlow Lite** menggunakan `TFLiteConverter`

## 📌 Catatan
Pastikan semua file sudah sesuai struktur di atas saat melakukan deployment atau submission. Untuk menjalankan proyek di local environment, install dependensi yang tertera di `requirements.txt`
