# Concrete Compressive Strength Analysis

Analisis faktor-faktor yang memengaruhi **kuat tekan beton (Concrete Compressive Strength)** menggunakan metode **Regresi Linier Berganda** dengan Python.

Proyek ini merupakan tugas mata kuliah Analisis Data yang bertujuan untuk membangun model prediksi kuat tekan beton berdasarkan karakteristik material penyusunnya serta mengevaluasi performa model yang dihasilkan.

---

## Deskripsi Proyek

Notebook ini berisi proses analisis data secara lengkap mulai dari eksplorasi data, preprocessing, pembangunan model regresi, hingga evaluasi hasil prediksi.

Analisis dilakukan menggunakan dataset **Concrete Compressive Strength** untuk mengetahui pengaruh setiap variabel independen terhadap nilai kuat tekan beton.

---

## Dataset

Dataset yang digunakan adalah **Concrete Compressive Strength Dataset**.

Variabel yang digunakan meliputi:

- Cement
- Blast Furnace Slag
- Fly Ash
- Water
- Superplasticizer
- Coarse Aggregate
- Fine Aggregate
- Age
- Concrete Compressive Strength (Target)

---

## Tools dan Library

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

---

## Tahapan Analisis

- Import library
- Load dataset
- Exploratory Data Analysis (EDA)
- Data Understanding
- Data Preprocessing
- Analisis Korelasi
- Visualisasi Data
- Pembangunan Model Regresi Linier Berganda
- Evaluasi Model
- Interpretasi Hasil
- Kesimpulan

---

## Struktur Repository

```
concrete-compressive-strength-analysis/
│
├── student_performance_analysis.ipynb
├── Concrete_Data.csv
├── README.md
```

> **Catatan:** Sebaiknya ubah nama notebook menjadi `concrete_strength_analysis.ipynb` agar sesuai dengan isi proyek.

---

## Cara Menjalankan

1. Clone repository

```bash
git clone https://github.com/feyshakamilaa/concrete-compressive-strength-analysis.git
```

2. Masuk ke folder project

```bash
cd concrete-compressive-strength-analysis
```

3. Install library yang diperlukan

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```

4. Jalankan Jupyter Notebook

```bash
jupyter notebook
```

5. Buka notebook

```
concrete_strength_analysis.ipynb
```

---

## Metode Analisis

Metode utama yang digunakan pada proyek ini adalah **Regresi Linier Berganda** untuk menganalisis hubungan antara beberapa variabel independen terhadap nilai kuat tekan beton.

Model kemudian dievaluasi menggunakan beberapa metrik seperti:

- Coefficient of Determination (R²)
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## Hasil

Melalui analisis ini diperoleh model regresi yang dapat digunakan untuk memprediksi kuat tekan beton berdasarkan komposisi material penyusunnya. Selain itu, dilakukan interpretasi terhadap pengaruh masing-masing variabel terhadap target prediksi.

---
