# 🌸 Clustering Dataset Iris Menggunakan Algoritma K-Means 🌸

Clustering adalah salah satu pendekatan fundamental dalam bidang *unsupervised learning* yang bertujuan untuk mengelompokkan data tanpa menggunakan label yang telah ditentukan sebelumnya. Dalam metode ini, algoritma secara otomatis menganalisis struktur dan pola dari data, lalu memisahkannya ke dalam kelompok atau klaster berdasarkan kemiripan karakteristik. Konsep ini sangat penting dalam eksplorasi data karena memungkinkan kita untuk menemukan insight tersembunyi, seperti segmentasi pelanggan dalam pemasaran, pengelompokan dokumen dalam pencarian informasi, atau bahkan dalam bidang biologi seperti pengklasifikasian spesies tanaman berdasarkan sifat morfologisnya. Salah satu keunggulan clustering adalah kemampuannya mengungkap keteraturan dalam data kompleks yang mungkin tidak tampak secara kasat mata.

Salah satu dataset paling terkenal dan historis dalam dunia machine learning adalah *Iris dataset*, yang diperkenalkan oleh Ronald A. Fisher pada tahun 1936. Dataset ini telah menjadi standar de facto dalam eksperimen klasifikasi dan clustering karena sifatnya yang bersih, sederhana, namun secara statistik cukup kompleks. Dataset ini terdiri dari 150 observasi bunga Iris yang terbagi merata ke dalam tiga spesies yang berbeda: **Iris setosa**, **Iris versicolor**, dan **Iris virginica**. Masing-masing observasi memiliki empat fitur numerik, yaitu panjang dan lebar dari kelopak (petal) serta sepal (daun kelopak) bunga. Keempat fitur ini, jika dianalisis secara mendalam, mengandung pola-pola tersembunyi yang memungkinkan kita membedakan setiap spesies secara kuantitatif. Hal inilah yang menjadikan Iris dataset sangat cocok untuk dijadikan bahan studi kasus dalam algoritma clustering seperti K-Means.

Algoritma **K-Means** adalah salah satu teknik clustering yang paling populer karena kesederhanaannya serta efisiensinya dalam membagi data ke dalam sejumlah kelompok berdasarkan jarak Euclidean ke titik pusat yang disebut *centroid*. Proses K-Means dimulai dengan memilih sejumlah klaster *k*, lalu menginisialisasi centroid secara acak. Selanjutnya, setiap titik data akan dihitung jaraknya terhadap seluruh centroid, dan diklasifikasikan ke dalam cluster dengan jarak terdekat. Setelah semua data terkelompok, centroid akan diperbarui berdasarkan rata-rata posisi seluruh titik dalam cluster tersebut. Proses ini akan terus berulang hingga centroid stabil dan tidak banyak berubah lagi. Meski terdengar sederhana, algoritma ini memiliki banyak aplikasi mulai dari segmentasi pelanggan, pengenalan pola visual, hingga sistem rekomendasi berbasis kemiripan fitur. Tantangan dalam K-Means adalah dalam memilih nilai *k* yang optimal, karena jika nilai ini salah, hasil clustering bisa tidak mencerminkan pola sebenarnya dalam data.

Dalam konteks proyek ini, saya menerapkan algoritma K-Means untuk mengelompokkan data dari dataset Iris tanpa menggunakan label spesiesnya. Dengan menggunakan dua komponen utama dari analisis dimensi, yaitu PCA (*Principal Component Analysis*), saya mereduksi fitur menjadi dua dimensi agar hasil pengelompokan bisa divisualisasikan dengan baik. Hasilnya menunjukkan bahwa meskipun tanpa label, algoritma dapat mengelompokkan data sesuai pola yang cukup dekat dengan klasifikasi aslinya. Hal ini menunjukkan bagaimana *unsupervised learning* bisa digunakan dalam situasi dunia nyata di mana label tidak tersedia atau sulit didapatkan.

---

### 🌼 Visualisasi Tiga Spesies *Iris*

| 🌿 *Iris setosa* | 🌹 *Iris versicolor* | 🌷 *Iris virginica* |
|:--:|:--:|:--:|
| <img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/Irissetosa1.jpg" width="200"/> | <img src="https://upload.wikimedia.org/wikipedia/commons/4/41/Iris_versicolor_3.jpg" width="200"/> | <img src="https://upload.wikimedia.org/wikipedia/commons/9/9f/Iris_virginica.jpg" width="200"/> |

Spesies *Iris setosa* ditandai dengan ukuran kelopak yang kecil dan warna yang cerah. *Iris versicolor* memiliki ciri khas ukuran yang sedang dan bentuk kelopak agak lebih melebar. Sementara itu, *Iris virginica* biasanya memiliki petal yang lebih panjang dan bentuk bunga yang lebih besar secara keseluruhan. Meskipun secara visual cukup jelas perbedaannya, secara statistik kita memerlukan analisis fitur agar bisa membedakan ketiganya dalam skala besar secara otomatis.

---

🧠 **Teknologi yang digunakan**: Python • Scikit-Learn • Pandas • Matplotlib  
✍️ **Penulis**: Riza Haryadi  
📬 **Email**: rizaharyadi13@gmail.com  
🌍 **Lokasi**: Indonesia  

> _“Data yang tidak dipetakan ibarat hutan yang belum dijelajahi – penuh potensi tapi tak terjamah.”_ 🌿
