# 📊 Telco Customer Churn Prediction & Retention Strategy

## 📌 Latar Belakang Bisnis
Proyek ini bertujuan untuk memprediksi pelanggan perusahaan telekomunikasi yang berpotensi berhenti berlangganan (*churn*) menggunakan Machine Learning. Biaya untuk mencari pelanggan baru jauh lebih mahal daripada mempertahankan pelanggan lama. Dengan mengetahui pelanggan mana yang akan *churn*, perusahaan dapat memberikan promo retensi yang tepat sasaran dan mencegah kerugian pendapatan (*revenue leakage*).

## 🛠️ Tools & Technologies
* **Bahasa Pemrograman:** Python
* **Libraries:** Pandas, Scikit-Learn, Matplotlib, Seaborn
* **Environment:** Google Colab / Jupyter Notebook

## 📈 Key Results & Business Impact
* Melakukan **Data Cleaning & EDA** pada 7.000+ data pelanggan, menemukan pola bahwa pelanggan baru (usia langganan 10-30 bulan) sangat rentan untuk *churn*.
* Membangun model **Random Forest Classifier** sebagai *baseline* klasifikasi.
* Melakukan optimasi bisnis melalui **Threshold Tuning** (menurunkan batas sensitivitas AI menjadi 30%).
* **Hasil Akhir:** Model berhasil menurunkan angka pelanggan kabur yang gagal terdeteksi (*False Negatives*) dari **196 orang menjadi hanya 99 orang** (penurunan kerugian hampir 50%).

## 📂 Struktur Repository
* `[Portofolio_1]_Customer_Churn_Prediction.ipynb`: Berisi baris kode utama, eksplorasi data, pelatihan model Machine Learning, dan visualisasi *Confusion Matrix*.
* `Telco-Customer-Churn.csv`: Dataset mentah pelanggan yang digunakan untuk analisis.

---
*Dibuat oleh Wisma Jaya Laksana - Mahasiswa S1 Pendidikan Teknik Informatika dan Komputer, Universitas Negeri Jakarta.*
