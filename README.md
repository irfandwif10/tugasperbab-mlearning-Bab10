# tugasperbab-mlearning-Bab10
## 10. Praktikum Bab 10: Unsupervised Learning & Clustering

### 1. Menentukan $k$ Optimal (Praktikum 1):
- **Elbow Method:** Mengamati grafik *inertia* (penurunan *sum of squared errors*) untuk mencari titik siku (*elbow*) sebagai indikasi jumlah *cluster* ideal.
- **Silhouette Score:** Mengukur seberapa dekat suatu titik data pada klusternya sendiri dibandingkan kluster lain. Nilai tertinggi menunjukkan kualitas pemisahan *cluster* yang paling optimal.

### 2. Segmentasi dengan Tiga Algoritma (Praktikum 2):
- **K-Means:** Cepat dan efisien untuk *cluster* berbentuk bola, namun memerlukan penentuan jumlah *cluster* ($k$) di awal.
- **Hierarchical Clustering:** Membentuk dendrogram hierarki yang baik untuk melihat relasi antar data, tetapi kurang optimal untuk dataset berukuran sangat besar.
- **DBSCAN:** Berbasis kepadatan (*density-based*), sangat andal mendeteksi bentuk non-linier dan mampu mengidentifikasi *noise points* (pencilan data) secara otomatis.
