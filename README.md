# 🧠 Deteksi Penyakit Parkinson dengan Machine Learning

Proyek ini merupakan eksperimen machine learning untuk mendeteksi penyakit **Parkinson** menggunakan dataset `parkinson.csv` (dimensi: 22 fitur, 2 kelas: **PD** atau **Healthy**).
Dataset dibagi menjadi:

* **100 sampel pertama** → Training set
* **95 sampel sisanya** → Testing set

## 🔍 Algoritma yang Diuji

* **K-Nearest Neighbors (KNN)**
* **Naive Bayes**
* **Decision Tree**
* **Random Forest**

## ⚙️ Teknologi & Library

* Python 3.x
* Pandas
* scikit-learn

## 📜 Alur Eksperimen

1. **Load Dataset**
   Membaca data `parkinson.csv` menggunakan `pandas`.

2. **Split Data**

   * Training set: 100 sampel pertama
   * Testing set: 95 sampel berikutnya

3. **Train Model**
   Menerapkan 4 algoritma berbeda untuk klasifikasi.

4. **Evaluate Model**
   Mengukur akurasi dan menampilkan laporan klasifikasi (`classification_report`).

## 📊 Hasil Eksperimen

| Algoritma     | Akurasi    |
| ------------- | ---------- |
| **KNN**       | **64.21%** |
| Random Forest | 61.05%     |
| Naive Bayes   | 49.47%     |
| Decision Tree | 37.89%     |

## 💡 Kesimpulan

* **KNN** memberikan hasil terbaik pada eksperimen ini, meskipun akurasi masih perlu ditingkatkan.
* **Random Forest** cukup kompetitif, namun masih kalah dari KNN.
* **Naive Bayes** dan **Decision Tree** kurang optimal untuk dataset ini.
* Perlu eksplorasi metode **balancing data** atau **feature engineering** untuk meningkatkan performa.

