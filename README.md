# Spesifikasi Eksperimen
- Jumlah data: 50.000 baris
- Jumlah fitur: 28 fitur numerik
- Rasio target: 65% kelas 0 dan 35% kelas 1
- Pembagian data: 80% data latih dan 20% data uji
- Lingkungan pengujian: Google Colab
- Framework: Apache Spark MLlib
- Algoritma: Logistic Regression dan Random Forest
- Mode Spark: Local

# Metrik Evaluasi
- Accuracy
- F1-Score
- Area Under ROC Curve (AUC)
- Waktu pelatihan
- Waktu pengujian dan evaluasi

# Cara Menjalankan
1. Instal Python dan Java yang kompatibel dengan versi PySpark.
2. Instal pustaka dengan perintah `pip install -r requirements.txt`.
3. Jalankan program `analisis_spark_mllib.py`.
4. Amati hasil evaluasi yang ditampilkan di terminal.

Program menggunakan data sintetis yang dibuat secara acak. Hasilnya tidak mewakili pengujian menggunakan dataset Higgs Boson asli.

Eksperimen ini berjalan dalam mode lokal dan tidak mengukur skalabilitas klaster multi-node.

