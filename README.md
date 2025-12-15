# RFM Model Implementation for Global Superstore Customer Segmentation
Proyek ini melakukan segmentasi pelanggan menggunakan metode RFM (Recency, Frequency, Monetary) untuk mendukung strategi pemasaran yang lebih tepat sasaran. Analisis dilengkapi dengan penerapan model machine learning dan visualisasi interaktif melalui dashboard untuk membantu pengambilan keputusan berbasis data.
# Anggota
<br />1	Rizal Afandi                 - M004D5Y1738 
<br />2	Muhammad Aflah Ghozi Susanto - M004D5Y1199 
<br />3	Ahmad Haydar Alfarizqi	     - M004D5Y0095
# Latar Belakang
Perubahan perilaku pasar di era digital menuntut strategi pemasaran yang lebih cerdas dan tepat sasaran. Namun, banyak perusahaan masih menggunakan promosi massal yang kurang relevan dengan karakteristik pelanggan, sehingga menimbulkan inefisiensi biaya dan rendahnya tingkat konversi. Untuk mengatasinya, diperlukan peralihan menuju pengambilan keputusan berbasis data melalui segmentasi pelanggan yang lebih actionable. Metode RFM (Recency, Frequency, Monetary) menjadi solusi efektif karena mampu mengukur nilai pelanggan secara kuantitatif. Dengan dukungan algoritma Machine Learning dan dashboard visualisasi, analisis pelanggan dapat dilakukan dengan lebih cepat dan akurat untuk mendukung strategi personalized marketing.

# Tujuan
Proyek ini bertujuan untuk:

<br />Menerapkan analisis RFM (Recency, Frequency, Monetary) untuk mengukur nilai pelanggan berdasarkan perilaku transaksi mereka, sehingga dapat memberikan pemahaman kuantitatif mengenai tingkat kedekatan, aktivitas, dan kontribusi pelanggan terhadap perusahaan.
<br />Mengembangkan model segmentasi pelanggan yang akurat dan representatif menggunakan algoritma clustering seperti K-Means dan mengevaluasi bagaimana setiap algoritma membentuk kelompok pelanggan yang memiliki karakteristik serupa.
<br />Menyajikan hasil analisis dan segmentasi pelanggan melalui dashboard interaktif, sehingga wawasan yang dihasilkan dapat divisualisasikan secara jelas, mudah dipahami, dan mendukung pengambilan keputusan yang cepat, tepat, dan berbasis data.

# Detail Pemodelan Clustering
Dataset yang digunakan adalah dataset Online Retail Dataset dari kaggle
Dilakukan tahapan pre-processing data untuk membersihkan dan menyiapkan data agar siap diolah
Dilakukan perhitungan skor RFM untuk mendapatkan nilai Recency, Frequency, dan Monetary setiap pelanggan
Algoritma yang dipilih adalah K-Means dengan Silhouette Score 0.589 dengan pertimbangan visualisasi pemisahan cluster yang lebih baik
Cluster diinterpretasikan berdasarkan karakteristik Recency, Frequency, dan Monetary
File model di Link ini.

# Dashboard
   <img width="1919" height="943" alt="Screenshot 2025-12-15 121759" src="https://github.com/user-attachments/assets/36a45d1f-3167-4f45-abc8-70f1a998861d" />
    
# Deployment & Integrasi
Dashboard ini dikembangkan menggunakan Streamlit dan di-hosting melalui Streamlit Cloud. Sistem ini terintegrasi penuh dengan repositori GitHub, sehingga menerapkan prinsip Continuous Deployment: setiap perubahan kode atau syntax pada file .py di GitHub akan langsung memicu pembaruan otomatis pada live dashboard secara real-time.

# Langkah-Langkah Penggunaan
Dashboard memiliki tiga bagian utama:
Executive Overview: Ringkasan secara umum mengenai proyek, dataset, serta eksplorasi dataset secara umum
Dashboard RFM: Eksplorasi dataset pelanggan berdasarkan cluster
Prediksi Insight: Menginput data RFM pelangan untuk menentukan cluster dan rekomendasi
Untuk menentukan cluster pelanggan, dibutuhkan data Recency, Frequency, dan Monetary pelanggan. Masukkan data bagian "Prediksi Insight" lalu klik "Analisis Sekarang" untuk melihat cluster pelanggan dan prediksi yang sesuai.

# Teknologi & Library

| Kategori            | Tools / Library                                              |
|---------------------|--------------------------------------------------------------|
| Bahasa              | Python                                                       |
| Data Processing     | Pandas, NumPy                                                |
| Visualisasi         | Matplotlib, Seaborn                                          |
| ML Preprocessing    | StandardScaler, MinMaxScaler, PCA                            |
| Clustering          | KMeans, Fuzzy C-Means (scikit-fuzzy)                         |
| Evaluasi Model      | Silhouette Score                                             |
| Tools Tambahan      | Yellowbrick (KElbowVisualizer), Google Colab                 |

