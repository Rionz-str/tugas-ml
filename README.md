# Genetic Disorder Machine Learning

## 1. Deskripsi Proyek

Proyek ini merupakan penerapan Machine Learning untuk melakukan klasifikasi *Genetic Disorder* berdasarkan data pasien.

Tujuan proyek adalah membangun dan membandingkan beberapa model klasifikasi untuk memprediksi kategori `Genetic Disorder` berdasarkan karakteristik dan informasi yang tersedia pada dataset pasien.

Algoritma yang digunakan adalah Decision Tree, Random Forest, dan Logistic Regression.

## 2. Dataset

Dataset berisi informasi pasien yang berkaitan dengan kelainan genetik.

Target prediksi:

`Genetic Disorder`

Kolom target yang tidak digunakan sebagai fitur:

`Disorder Subclass`

Dataset awal berisi 22.083 baris dan 45 kolom, termasuk kolom `Genetic Disorder` dan `Disorder Subclass`.

Dataset memiliki fitur numerik dan kategorikal serta sejumlah nilai kosong, sehingga diperlukan proses preprocessing sebelum pelatihan model.

Catatan: asal-usul dan sumber dataset perlu diverifikasi sebelum hasil digunakan untuk penelitian.

## 3. Metode

Algoritma yang digunakan adalah:

- Decision Tree Classification
- Random Forest Classification
- Logistic Regression

Target:

`Genetic Disorder`

Fitur yang digunakan mencakup informasi pasien, faktor genetik, hasil pemeriksaan, dan gejala yang tersedia pada dataset.

Kolom `Disorder Subclass` tidak digunakan sebagai fitur input karena target prediksi yang dipilih adalah `Genetic Disorder`.

Kolom identitas pasien dan fitur lain yang berpotensi menyebabkan *data leakage* perlu diperiksa agar tidak membuat hasil evaluasi menjadi terlalu optimistis.

## 4. Tools dan Library

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 5. Tahapan Analisis

1. Import library.
2. Membaca dataset.
3. Memeriksa struktur dan kualitas data.
4. Menangani nilai yang kosong.
5. Melakukan encoding pada fitur kategorikal.
6. Melakukan scaling pada fitur numerik.
7. Menentukan fitur dan target.
8. Membagi data menjadi training dan testing.
9. Melatih model Decision Tree.
10. Melatih model Random Forest.
11. Melatih model Logistic Regression.
12. Melakukan prediksi menggunakan setiap model.
13. Membandingkan hasil evaluasi.
14. Menampilkan confusion matrix.
15. Menyusun kesimpulan berdasarkan hasil pengujian.

## 6. Evaluasi

Model dievaluasi menggunakan metrik berikut:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Precision, recall, dan F1-score digunakan untuk melihat performa model dalam memprediksi kelas-kelas Genetic Disorder. Confusion matrix digunakan untuk melihat perbandingan antara label aktual dan hasil prediksi.

Nilai evaluasi dicatat berdasarkan hasil eksekusi notebook. Model terbaik ditentukan setelah hasil pengujian dibandingkan, bukan berdasarkan asumsi sebelum pengujian.

## 7. Batasan

Hasil klasifikasi bergantung pada kualitas, kelengkapan, dan karakteristik dataset. Nilai kosong, ketidakseimbangan kelas, serta pemilihan fitur dapat memengaruhi performa model.

Dataset pasien juga dapat mengandung informasi pribadi. Identitas pasien perlu dihilangkan atau dilindungi sebelum dataset dibagikan secara publik.

Hasil model ini digunakan untuk tujuan pembelajaran Machine Learning dan bukan sebagai pengganti diagnosis atau keputusan medis profesional.

## 8. Kesimpulan

Proyek ini menerapkan Machine Learning untuk mengklasifikasikan `Genetic Disorder` berdasarkan data pasien. Tiga algoritma, yaitu Decision Tree, Random Forest, dan Logistic Regression, digunakan untuk membandingkan performa model melalui metrik evaluasi klasifikasi.

Kesimpulan akhir mengenai model dengan performa terbaik ditentukan berdasarkan hasil evaluasi yang diperoleh setelah seluruh proses dijalankan.
