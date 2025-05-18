Kanker payudara merupakan salah satu jenis kanker yang paling umum di kalangan wanita di seluruh dunia. Deteksi dini sangat penting untuk meningkatkan peluang kesembuhan dan mengurangi angka kematian. Oleh karena itu, pengembangan model klasifikasi yang efektif untuk membedakan antara tumor ganas dan jinak menjadi sangat penting. Dalam penelitian ini, kami akan menggunakan dataset Breast Cancer Wisconsin (Diagnostic) untuk membangun model klasifikasi menggunakan algoritma Naive Bayes dan K-Nearest Neighbors (KNN).
Dataset yang digunakan adalah Breast Cancer Wisconsin (Diagnostic), yang terdiri dari 569 sampel dengan 30 fitur. Fitur-fitur ini dihitung dari gambar digital aspirasi jarum halus (FNA) dari massa payudara dan menggambarkan karakteristik dari inti sel yang ada dalam gambar. Diagnosis ditandai sebagai 'M' untuk ganas (malignant) dan 'B' untuk jinak (benign).

Statistik Dasar:

Jumlah Sampel: 569
Jumlah Fitur: 30
Fitur Utama:ID number & Diagnosis (M = malignant, B = benign)
10 fitur real-valued untuk setiap inti sel:
1. Radius
2. Texture
3. Perimeter
4. Area
5. Smoothness
6. Compactness
7. Concavity
8. Concave points
9. Symmetry
10. Fractal dimension
Masalah utama yang ingin diselesaikan adalah mengklasifikasikan tumor payudara sebagai ganas (malignant) atau jinak (benign) berdasarkan fitur-fitur yang diambil dari citra histopatologi. Dengan menggunakan algoritma pembelajaran mesin, kami bertujuan untuk menciptakan model yang dapat membantu dalam diagnosis
