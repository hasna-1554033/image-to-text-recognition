# image-to-text-recognition

Proyek ini bertujuan untuk mengonversi teks yang terdapat dalam gambar menjadi bentuk digital menggunakan teknologi Optical Character Recognition (OCR). Untuk meningkatkan akurasi hasil ekstraksi teks, proyek ini membandingkan dua pendekatan algoritmik yang berbeda, yaitu Convolutional Neural Network (CNN) dan Support Vector Machine (SVM). Berikut adalah alur pengerjaan proyek:

Langkah Pemrosesan Citra 
Pemrosesan citra dilakukan disesuaikan dengan masing-masing gambar yang tersedia. Hal ini dipengaruhi oleh adanya noise yang berbeda-beda, namun langkah-langkah preprocessing dilakukan memiliki satu garis besar yang sama. 
1. Konversi Format Gambar 
Mengkonversian format warna pada citra dilakukan untuk standarisasi pemrosesan citra. 
2. Penerapan Model OCR 
Menerapkan Optical Character Recognition atau OCR dengan dua algoritma yang berbeda, yaitu SVM dan CNN. Hal ini dilakukan untuk mendeteksi teks yang terdapat pada citra. 
3. Pengolahan Hasil dan Visualisasi
Setelah teks telah terdeteksi menggunakan SVM atau CNN, teks yang terdapat dalam citra akan ditandai dengan bounding box dengan detail teks kecil diatasnya sebagai output dari hasil deteksi model. 
4. Evaluasi Hasil 
Menghitung Character Error Rate (CER) dan Word Error Rate (WER) untuk mengukur tingkat kesalahan antara hasil konversi dibandingkan dengan teks asli.
