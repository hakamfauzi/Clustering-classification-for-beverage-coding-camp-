# BMLP Final Submission - Labib Hakam Fauzi

Proyek ini merupakan bagian dari tugas akhir untuk program **Coding Camp by DBS Foundation** yang mencakup dua pendekatan utama dalam machine learning: **Klasifikasi** dan **Clustering**. Proyek ini mengeksplorasi teknik preprocessing, pelatihan model, dan evaluasi performa menggunakan dataset yang relevan.

## Dataset
- Dataset untuk clustering dapat diunduh pada link berikut https://www.kaggle.com/datasets/sebastianwillmann/beverage-sales/data 

## Struktur Proyek

- `[Klasifikasi]_Submission_Akhir_BMLP_Labib_Hakam_Fauzi.ipynb`  
  Notebook ini berisi proses klasifikasi menggunakan algoritma supervised learning seperti Logistic Regression, K-Nearest Neighbors, dan Random Forest.

- `[Clustering]_Submission_Akhir_BMLP_Labib_Hakam_Fauzi.ipynb`  
  Notebook ini berisi eksperimen unsupervised learning menggunakan algoritma seperti K-Means dan DBSCAN untuk melakukan segmentasi data.

---

## Teknologi dan Library

Notebook menggunakan beberapa library Python untuk analisis dan visualisasi data:
- `pandas`, `numpy` - manipulasi data
- `matplotlib`, `seaborn` - visualisasi data
- `scikit-learn` - algoritma machine learning
- `plotly`, `yellowbrick` - visualisasi tambahan untuk analisis clustering

---

## Ringkasan Proyek

### Klasifikasi
- **Tujuan**: Memprediksi label target berdasarkan fitur yang tersedia.
- **Langkah-langkah**:
  - Pembersihan data (handling missing values)
  - Visualisasi dan eksplorasi data
  - Feature scaling
  - Pelatihan dan evaluasi model (Akurasi, Confusion Matrix)

### Clustering
- **Tujuan**: Mengelompokkan data tanpa label ke dalam klaster-klaster yang bermakna.
- **Langkah-langkah**:
  - Eksplorasi dan preprocessing
  - Reduksi dimensi dengan PCA
  - Clustering menggunakan KMeans
  - Evaluasi hasil clustering dengan silhouette score dan visualisasi

---

## Hasil Evaluasi

### Klasifikasi
- Model terbaik: `Random Forest`
- Akurasi: **99%**

### Clustering
- Jumlah klaster optimal (KMeans): **3**
- Silhouette Score: **0.48**

---

## Cara Menjalankan

1. Clone repository ini:
   ```bash
   git clone https://github.com/hakamfauzi/Clustering-classification-for-beverage-coding-camp-
   cd <nama-folder>
