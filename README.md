# **Assignment -2**
Nomor 1 <br>
Membandingkan 3 model machine learning untuk memprediksi nasabah yang akan keluar, dengan dataset & tools: <br>
a. Data: SC_HW1_bank_data<br>
b. Library: Pandas, Numpy, Scikit-learn<br>
Yang harus dilakukan: persiapan data dan lakukan normalisasi data. Lalu pembuatan 3 model dan dijelaskan dengan melatih model serta mengevaluasi performna model.<br>
Melakukan perbandingan terhadap 3 model dan pilih model yang terbaik serta dokumentasi hasil perbandingan <br>

Nomor 2 <br>
Melakukan clustering dengan segmentasi data menggunakan KMeans Clustering, dengan dataset & tools: <br>
a. Data: cluster_s1<br>
b. Library: Pandas, Numpy, Scikit-learn, Matplotlib, Seaborn<br>
Melakukan analisi jumlah clustering yang optimal dengan metode elbow lalu terapkan KMeans Clustering serta menambahkan label cluster ke DataFrame.<br>
Plot hasil clustering dengan seaborn serta menunjukkan perbedaan antar cluster.<br>

Nomor 3<br>
Memprediksi harga rumah California menggunakan Neural Network (MLP) dengan tool: Framework: Tensorflow-Keras, Library: (Pandas, Numpy, Scikit-learn, Matplotlib), Dataset: California House Price<br>
Mempersiapkan data dengan cara Konversi data ke DataFrame, Split data (train/val/test), Standarisasi & normalisasi data<br>
Melakukan pembuatan model 2 hidden layer (30 neuron, ReLU), Tentukan epoch dan batch size lalu muat ulang model dengan prediksi data baru<br>

Nomor 4 <br>
Tugas ini menggunakan Multilayer Perceptron (MLP) dalam PyTorch untuk mendeteksi transaksi penipuan kartu kredit. Dataset diolah dengan Pandas, dipisah menjadi train dan test set menggunakan Scikit-learn, lalu dilatih menggunakan GPU. Model dilatih dengan binary cross-entropy dan dioptimasi dengan Adam. Jika akurasi di bawah 95%, dilakukan fine-tuning.<br>
Hyperparameters dikonfigurasi sebelum training (contohny. learning rate, epochs), sedangkan parameters dipelajari model selama training (misalny. bobot, bias).
Total trainable parameters sama dengan keseluruhan parameter karena semua parameter dioptimasi.
