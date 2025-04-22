# Regularized-Regression
menyimpan code model lasso &amp; ridge regression prediksi boston house price

# Regularized Regression Model - Boston Housing Price Prediction

## 🏠 Project Overview

Proyek ini bertujuan untuk memprediksi **harga rumah di Boston** menggunakan **metode regresi regularisasi** seperti **Ridge**, **Lasso**. Dataset yang digunakan adalah **Boston Housing Dataset** yang terkenal dalam dunia data science.

### 🎯 Objective

Membangun model regresi yang dapat memprediksi harga rumah berdasarkan fitur-fitur lingkungan dan demografis, serta mengurangi overfitting dengan teknik regularisasi.

## 📊 Dataset

Fitur-fitur yang digunakan antara lain:
- `crim`: Tingkat kriminalitas per kapita
- `zn`: Proporsi tanah untuk residensial
- `indus`: Proporsi area non-retail
- `chas`: Dekat sungai atau tidak
- `nox`: Konsentrasi nitrogen oksida
- `rm`: Jumlah rata-rata kamar per rumah
- `age`: Proporsi pemilik rumah yang sudah tua
- `dis`: Jarak ke pusat bisnis
- `rad`: Indeks akses ke jalan raya
- `tax`: Pajak properti
- `ptratio`: Rasio murid-guru
- `black`: Proporsi penduduk kulit hitam
- `lstat`: Persentase status sosial rendah
- **Target**: `medv` (Median harga rumah dalam $1000-an)

## ⚙️ Langkah Analisis
1. Load dan eksplorasi data
2. Pembagian data (train-validation-test)
3. Pemeriksaan multikolinearitas
4. Model:
   - Ridge Regression
   - Lasso Regression
5. Evaluasi model menggunakan RMSE, MAE dan MAPE

## 🛠️ Tools & Library
- Python
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn

## 💡 Insight
Dengan regularisasi, model menjadi lebih robust terhadap multikolinearitas dan overfitting.

## 🚀 How to Run

Clone repository ini, jalankan digoogle colab/Jupyter notebook.
