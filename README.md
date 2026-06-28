# Student Performance Analysis

Analisis data performa mahasiswa menggunakan Python dengan pendekatan Exploratory Data Analysis (EDA) dan Regresi Linear Berganda. Proyek ini bertujuan untuk mengidentifikasi faktor-faktor yang memengaruhi nilai akhir siswa berdasarkan beberapa variabel seperti lama belajar, nilai sebelumnya, jam tidur, dan faktor lainnya.

## Deskripsi Proyek

Notebook ini berisi tahapan analisis data mulai dari proses persiapan data, eksplorasi data, visualisasi, pembangunan model regresi linear berganda, hingga evaluasi model.

Analisis dilakukan menggunakan dataset **Student Performance** untuk memahami hubungan antara variabel independen dengan **Performance Index** sebagai variabel dependen.

---

## Tujuan

- Melakukan Exploratory Data Analysis (EDA).
- Mengetahui hubungan antar variabel.
- Membangun model Regresi Linear Berganda.
- Mengevaluasi performa model menggunakan beberapa metrik evaluasi.
- Menginterpretasikan hasil analisis sebagai dasar pengambilan keputusan.

---

## Dataset

Dataset yang digunakan adalah **Student Performance Dataset** dengan beberapa atribut, di antaranya:

- Hours Studied
- Previous Scores
- Sleep Hours
- Sample Question Papers Practiced
- Extracurricular Activities
- Performance Index

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

1. Import Library
2. Load Dataset
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Visualisasi Data
6. Feature Selection
7. Pembangunan Model Regresi Linear Berganda
8. Evaluasi Model
9. Interpretasi Hasil
10. Kesimpulan

---

## Struktur Repository

```
student-performance-analysis/
│
├── student_performance_analysis.ipynb
├── Student_Performance.csv
├── README.md
└── requirements.txt (opsional)
```

---

## Cara Menjalankan

1. Clone repository

```bash
git clone https://github.com/feyshakamilaa/student-performance-analysis.git
```

2. Masuk ke folder project

```bash
cd student-performance-analysis
```

3. Install dependency

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```

4. Jalankan Jupyter Notebook

```bash
jupyter notebook
```

5. Buka file

```
student_performance_analysis.ipynb
```

---

## Hasil Analisis

Analisis menghasilkan model Regresi Linear Berganda yang digunakan untuk memprediksi **Performance Index** berdasarkan beberapa variabel independen.

Selain itu dilakukan evaluasi model menggunakan metrik seperti:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---
