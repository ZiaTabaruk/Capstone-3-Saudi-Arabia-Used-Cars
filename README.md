# Saudi Arabia Used Cars

![{BC475939-D6FF-4B32-9769-8B3E273C943A}](https://github.com/user-attachments/assets/c73c2b0a-578c-46bb-bd8f-fd78f24e5fcb)

## Latar Belakang
Arab Saudi adalah negara terbesar di Timur Tengah dengan populasi sekitar **34 juta jiwa**, di mana **42% dari penduduknya merupakan warga negara asing**. Populasi warga asing yang signifikan ini meningkatkan kebutuhan akan berbagai barang dan jasa, termasuk kendaraan. Harga bahan bakar yang sangat murah di Arab Saudi, yang termasuk paling rendah di dunia, mendorong tingginya penggunaan mobil pribadi di negara tersebut.

Dalam beberapa tahun terakhir, pasar mobil bekas di Arab Saudi terus tumbuh seiring dengan perubahan ekonomi dan preferensi konsumen. Banyak konsumen beralih ke mobil bekas sebagai pilihan yang lebih terjangkau dibandingkan membeli mobil baru. Faktor-faktor seperti kondisi keuangan yang berubah-ubah dan kebutuhan mobilitas sehari-hari juga menjadi pendorong utama peningkatan permintaan terhadap mobil bekas.

Meskipun pasar mobil bekas berkembang, ia tetap dipengaruhi oleh fluktuasi harga berdasarkan merek, jenis transmisi, kapasitas mesin, jarak tempuh, dan tahun produksi. Ini membuat penentuan harga mobil bekas menjadi tantangan bagi penjual dan pembeli. Di tengah kondisi pasar yang tidak menentu ini, prediksi harga mobil bekas menjadi semakin penting untuk membantu dalam pengambilan keputusan yang tepat terkait jual-beli kendaraan.

## Pemangku Kepentingan
Marketplace Platform

Sebagai penyedia layanan jual-beli mobil bekas, marketplace bertanggung jawab untuk menyediakan alat atau model prediksi harga yang akurat. Marketplace juga harus memastikan harga yang ditawarkan kompetitif dan sesuai dengan kondisi pasar untuk memaksimalkan transaksi dan keuntungan.

## Rumusan Masalah
Salah satu tantangan utama yang dihadapi **marketplace mobil bekas di Arab Saudi** adalah menetapkan **harga yang tepat** untuk mobil bekas, sehingga tidak terlalu tinggi yang dapat mengurangi minat konsumen, atau terlalu rendah yang bisa menyebabkan kerugian bagi penjual. Marketplace harus mempertimbangkan berbagai faktor, seperti **tipe mobil**, **jarak tempuh**, **jenis transmisi**, dan **fitur tambahan**, untuk mencapai **harga yang kompetitif dan optimal**. Dalam konteks **dataset ini** yang mencakup **5624 data mobil bekas**, terdapat informasi penting yang mempengaruhi **harga jual**. Oleh karena itu, diperlukan **metode atau model** yang dapat menghasilkan **estimasi harga yang akurat dan adil**, sehingga dapat membantu marketplace menentukan **harga yang transparan** dan sesuai dengan **kondisi pasar**.

## Tujuan
Berdasarkan tantangan dalam penentuan **harga mobil bekas**, marketplace membutuhkan **alat atau model prediksi** yang dapat memproyeksikan **harga jual optimal** untuk mobil bekas. Alat ini akan membantu penjual dalam **menentukan harga yang tepat** dengan mempertimbangkan berbagai faktor seperti **jenis mobil**, **kondisi mesin**, **tahun produksi**, **jarak tempuh**, dan **opsi tambahan** lainnya. Dengan adanya **prediksi harga yang akurat**, diharapkan keputusan yang diambil oleh para pemangku kepentingan akan lebih mudah dan menguntungkan, baik dari segi **persaingan pasar** maupun **potensi keuntungan**. **Prediksi yang transparan dan adil** akan membantu meningkatkan **transaksi** dan **kepercayaan** antara penjual dan pembeli, serta mendorong **pertumbuhan bisnis** marketplace secara keseluruhan.

## Pendekatan Analitik
Permasalahan ini akan dianalisis dengan meninjau data untuk menemukan pola-pola fitur yang membedakan satu mobil bekas dari yang lain. Langkah awal dilakukan melalui eksplorasi data guna mengungkap perbedaan antara fitur-fitur seperti tipe mobil, jarak tempuh, jenis transmisi, dan opsi tambahan. Eksplorasi ini bertujuan memberikan wawasan mendalam mengenai faktor-faktor yang memengaruhi harga mobil bekas.

Setelah pola-pola tersebut diidentifikasi, langkah berikutnya adalah merancang model regresi untuk memprediksi harga mobil bekas secara akurat. Model ini akan membantu marketplace menentukan harga yang kompetitif, mencegah terjadinya harga yang terlalu tinggi atau terlalu rendah. Dengan estimasi harga yang lebih tepat, diharapkan keputusan jual-beli dapat dilakukan secara lebih efisien dan menguntungkan bagi penjual maupun pembeli.

## Kesimpulan
Model Gradient Boosting Regressor dengan pemilihan fitur otomatis menunjukkan performa yang cukup baik dalam memprediksi harga mobil. Setelah melalui tahap preprocessing data dan hyperparameter tuning, model ini menggunakan fitur-fitur yang paling signifikan seperti tahun pembuatan, ukuran mesin, dan jarak tempuh untuk memaksimalkan akurasi prediksi. Meskipun terjadi sedikit penurunan performa setelah tuning dengan nilai R-Square sebesar 0.3367, model ini tetap mampu memberikan wawasan penting tentang faktor-faktor utama yang memengaruhi harga kendaraan. Dengan peningkatan lebih lanjut dalam penanganan outlier dan tuning parameter yang lebih tepat, model ini diharapkan dapat membantu perusahaan dalam meningkatkan keakuratan prediksi harga dan mengoptimalkan strategi harga kendaraan di pasar.

## Rekomendasi
Bisnis:

- Optimalisasi Harga: Berdasarkan hasil model, fitur-fitur seperti tahun pembuatan, ukuran mesin, dan jarak tempuh memiliki pengaruh besar terhadap harga kendaraan. Perusahaan dapat menggunakan informasi ini untuk mengoptimalkan harga kendaraan yang lebih kompetitif, terutama dengan mempertimbangkan kondisi kendaraan yang lebih baru dan dengan spesifikasi mesin yang lebih baik.

- Strategi Pemasaran Berdasarkan Fitur Utama: Perusahaan dapat memfokuskan strategi pemasaran pada fitur-fitur yang paling penting dalam menentukan harga kendaraan. Misalnya, mempromosikan kendaraan dengan jarak tempuh rendah dan mesin bertenaga besar untuk meningkatkan minat pelanggan di segmen premium.

- Pemanfaatan Prediksi untuk Strategi Harga: Marketplace dapat menggunakan hasil prediksi ini untuk memastikan harga yang ditawarkan adil dan kompetitif, meningkatkan kepercayaan antara penjual dan pembeli, serta mengoptimalkan transaksi.

Segmentasi Pelanggan Berdasarkan Rentang Harga: Karena model masih mengalami kesulitan dalam memprediksi rentang harga yang sangat tinggi dan rendah, perusahaan bisa menggunakan hasil analisis ini untuk merancang strategi khusus untuk setiap segmen harga, baik untuk kendaraan dengan harga terjangkau maupun kendaraan mewah.


Modeling:

- Penanganan Outlier: Nilai MAPE yang sangat tinggi mengindikasikan adanya outlier atau data dengan distribusi yang tidak normal. Disarankan untuk melakukan pembersihan data lebih lanjut atau menerapkan metode penanganan outlier yang lebih baik agar prediksi lebih akurat.

- Tuning Hyperparameter Lebih Lanjut: Proses tuning yang dilakukan pada model Gradient Boosting Regressor belum memberikan peningkatan signifikan. Disarankan untuk menggunakan metode tuning lain seperti GridSearchCV atau mencoba range parameter yang lebih luas untuk meningkatkan performa model.

- Eksperimen dengan Model Lain: Meskipun Gradient Boosting telah digunakan, disarankan untuk mencoba model alternatif seperti XGBoost atau Random Forest yang memiliki performa kompetitif dan bisa memberikan hasil yang lebih baik pada data regresi.

- Penerapan Feature Engineering: Menambahkan fitur-fitur baru yang relevan, seperti riwayat perbaikan atau status kepemilikan kendaraan, dapat membantu meningkatkan akurasi prediksi dan menangkap aspek-aspek yang belum diperhitungkan dalam model saat ini.
