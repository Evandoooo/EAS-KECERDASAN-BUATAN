# Program Sistem Klasifikasi Nilai Rupiah Menggunakan Convolutional Neural Network (CNN) 

## Pendahuluan:

Proyek ini bertujuan untuk mengembangkan model Convolutional Neural Network (CNN) pada dataset citra untuk menyelesaikan masalah klasifikasi gambar nilai rupiah. CNN dipilih karena keunggulannya dalam mengenali pola visual dalam gambar, seperti tepi, tekstur, dan bentuk yang kompleks.

## Deskripsi:

Proyek ini menggunakan dataset citra yang telah disediakan. Dataset tersebut dibagi menjadi data latih, validasi, dan uji untuk memastikan model dapat digeneralisasi dengan baik. CNN dirancang dengan beberapa lapisan konvolusi, pooling, dan fully connected untuk mengekstraksi fitur penting dari gambar dan melakukan klasifikasi.

## Metodologi:

### Pemrosesan Data:

- Memuat dataset dan membaginya menjadi set latih, validasi, dan uji.
- Normalisasi citra untuk mempercepat konvergensi model.
- Augmentasi data untuk meningkatkan keragaman dataset dan mencegah overfitting.

### Arsitektur CNN:

- Membangun arsitektur CNN dengan beberapa lapisan konvolusi, pooling, dan fully connected.
- Menggunakan fungsi aktivasi seperti ReLU untuk memperkenalkan non-linearitas.
- Mengaplikasikan dropout untuk mengurangi overfitting.

 ### Pelatihan Model:

- Menggunakan optimizers seperti Adam atau SGD.
- Melatih model dengan backpropagation untuk meminimalkan fungsi loss.
- Memantau kinerja model dengan set validasi dan menyesuaikan hyperparameter jika diperlukan.

### Evaluasi Model:

- Menggunakan metrik seperti akurasi, presisi, recall, dan F1-score untuk mengevaluasi kinerja model.
- Menggunakan confusion matrix untuk memahami kesalahan klasifikasi.

## Kesimpulan:

Proyek ini menunjukkan bagaimana CNN dapat digunakan untuk tugas klasifikasi gambar dengan akurasi yang baik. Hasil evaluasi menunjukkan bahwa model memiliki kemampuan yang kuat dalam mengenali dan mengklasifikasikan citra dengan benar.
