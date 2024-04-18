# Dataset Performence Student

Dataset ini berisi data performa siswa dalam berbagai mata pelajaran. Data ini digunakan untuk mengidentifikasi pola dalam performa siswa menggunakan metode clustering.

## Deskripsi Dataset

- **Nama Dataset**: Performence Student
- **Sumber Dataset**: (https://archive.ics.uci.edu/dataset/320/student+performance)
- **Jumlah Sampel**: [649]
- **Jumlah Fitur**: [33]

## Metode Clustering

### 1. KMeans

Metode KMeans adalah salah satu metode clustering yang paling umum digunakan. Algoritma ini mengelompokkan data ke dalam k kelompok berdasarkan pusat kelompok yang diinisialisasi secara acak. Setiap sampel data diberikan label berdasarkan kelompok yang memiliki pusat terdekat.

### 2. Agglomerative Clustering

Agglomerative Clustering adalah metode clustering hierarkis di mana setiap sampel dimulai sebagai satu kelompok dan secara berurutan digabungkan menjadi kelompok yang lebih besar berdasarkan jarak antara kelompok-kelompok tersebut.

### 3. DBSCAN

DBSCAN (Density-Based Spatial Clustering of Applications with Noise) adalah metode clustering yang mengelompokkan titik-titik data yang dekat menjadi satu kelompok berdasarkan kepadatan data di sekitarnya.

## Penggunaan

Untuk menggunakan dataset ini dan menerapkan metode clustering, ikuti langkah-langkah berikut:

1. Unduh dataset dari [https://archive.ics.uci.edu/dataset/320/student+performance].
2. Lakukan pra-pemrosesan data, seperti normalisasi atau pengelompokkan fitur yang relevan.
3. Terapkan metode clustering yang diinginkan (KMeans, Agglomerative Clustering, atau DBSCAN) pada dataset.
4. Evaluasi hasil clustering menggunakan metrik evaluasi yang sesuai, seperti silhouette score atau Davies-Bouldin index.
5. Interpretasikan hasil clustering untuk memahami pola-pola yang terdapat dalam data performa siswa.

## Referensi

- https://scikit-learn.org/stable/modules/clustering.html#k-means
- https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html
- https://stackabuse.com/bytes/agglomerative-hierarchical-clustering-with-scikit-learn/
- https://www.reneshbedre.com/blog/dbscan-python.html
