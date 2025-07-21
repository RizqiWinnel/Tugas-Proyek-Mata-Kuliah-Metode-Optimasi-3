# Tugas-Proyek-Mata-Kuliah-Metode-Optimasi-3
Title: Optimasi Parameter Support Machine Learning dengan Menggunakan Particle Swarm Optimization

Proyek ini bertujuan untuk melakukan optimasi hyperparameter pada algoritma Support Vector Machine (SVM) guna meningkatkan performa klasifikasi. Dataset yang digunakan adalah food_items.csv, yang berisi informasi nutrisi berbagai item makanan, dengan tujuan untuk mengklasifikasikan kategori makanan.

Metode optimasi yang akan diimplementasikan adalah Particle Swarm Optimization (PSO). PSO akan digunakan untuk mencari kombinasi parameter optimal untuk SVM (khususnya parameter C dan gamma untuk kernel RBF) yang dapat memaksimalkan akurasi klasifikasi pada data validasi.

Tahapan utama dalam proyek ini:

Studi literatur dan pemahaman algoritma SVM dan PSO.
Persiapan data: memuat dataset, melakukan pre-processing yang diperlukan (seperti encoding, scaling, dan pemisahan data).
Implementasi algoritma Particle Swarm Optimization (PSO).
Integrasi PSO dengan model SVM untuk mengevaluasi setiap set parameter.
Pelatihan dan evaluasi model SVM dengan parameter hasil optimasi.
Analisis hasil dan kesimpulan.
