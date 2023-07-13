# capstone_project_modul2_data_analysis_supermarket_customer

# **Latar Belakang**

Seorang pemilik supermarket **ingin mengetahui kinerja supermarketnya secara umum**. Di sisi lain, pemilik supermarket **ingin meluncurkan sebuah produk baru dalam kategori wine** sehingga pemilik supermarket **ingin mengetahui *customer behavior* pelanggannya yang sering membeli wine**.

# **Pernyataan Masalah**
Pemilik supermarket **ingin mengetahui *customer behavior* dari pelanggan yang sering membeli produk wine di supermarketnya** sehingga dengan adanya informasi ini bisa memudahkan supermarket untuk melakukan segmenting ketika hendak meluncurkan produk wine terbarunya. 

sebagai seorang Data Analyst, kita akan mencoba menjawab pertanyaan berikut: 
1. **Bagaimana segmentasi pelanggan yang sering membeli produk wine di supermarket?**
2. **Bagaimana pengaruh promosi terhadap minat beli produk wine?**
3. **Dimana pelanggan paling sering membeli produk wine?**

# **Untuk menjawab Pernyataan masalah, kita telah melakukan data analysis yang prosesnya bisa dilihat langsung pada file Jupyter Notebook**

Setelah melakukan proses analisis, kita mendapatkan beberapa insight yaitu:

- Wine merupakan produk yang paling banyak dibeli dalam 2 tahun terakhir di Supermarket. Keseluruhan konsumen telah mengeluarkan uang sebesar 680029 dollar untuk membeli wine.
- Income pelanggan dan pembelian wine mempunyai korelasi yang positif dan kuat sebesar 0.83. Artinya semakin tinggi Income maka akan semakin tinggi tingkat konsumtif terhadap produk wine.
- Semakin banyak jumlah anggota keluarga, maka semakin rendah tingkat konsumtif terhadap produk wine.
- Pelanggan dengan ID 737, 3174, 5536, 1103, 5547, 8362, 3009, 1665, 9743, 11088, 4580, 4943, 9260, 7431, 3138, 4475, 6292, 10140, 10133, 8732, 8545, 203, 7962, 7919, 6932, 9499, 6248, 1763, 1204, 9298, 3725, 7899, 2926, 7999, dan 5236 merupakan 35 pelanggan yang paling konsumtif terhadap produk wine dengan total spent produk wine sebesar 46958 dollar (sekitar 6.9% dari total pembelian wine)

Adapun *customer behavior* yang membeli produk wine di supermarket yaitu:

**Segmentasi pelanggan yang sering membeli produk wine di supermarket**

Secara umum:

- Pelanggan dengan rentang usia 62-83 tahun
- Pelanggan dengan pendidikan akhir PhD atau Graduation
- Pelanggan dengan status pernikahan menikah atau bercerai
- Pelanggan dengan Income Class Upper atau Middle (Income diatas $52,200 pertahun)
- pelanggan yang tidak mempunyai anak kecil tapi mempunyai 1 atau 2 anak remaja
<br><br>

Untuk menentukan target konsumen secara lebih spesifik, berikut adalah urutan dari general hingga spesifik:

- Pelanggan yang tidak mempunyai anak kecil
- Pelanggan yang tidak mempunyai anak kecil tapi mempunyai 1 atau 2 anak remaja
- Pelanggan yang tidak mempunyai anak kecil tapi mempunyai 1 atau 2 anak remaja dan termasuk kedalam Middle atau Upper Income Class
- Pelanggan yang tidak mempunyai anak kecil tapi mempunyai 1 atau 2 anak remaja dan termasuk kedalam Middle atau Upper Income Class dengan pendidikan terakhir Graduation atau PhD
- Pelanggan yang tidak mempunyai anak kecil tapi mempunyai 1 atau 2 anak remaja dan termasuk kedalam Middle atau Upper Income Class dengan pendidikan terakhir Graduation atau PhD dengan status menikah atau bercerai
- Pelanggan yang tidak mempunyai anak kecil tapi mempunyai 1 atau 2 anak remaja dan termasuk kedalam Middle atau Upper Income Class dengan pendidikan terakhir Graduation atau PhD dengan status menikah atau bercerai dengan rentang usia 62-83 tahun



**pengaruh promosi terhadap minat beli produk wine**

- Promosi berjalan efektif, semakin banyak pelanggan menerima promosi, semakin konsumtif pelanggan tersebut terhadap produk wine meskipun berdasarkan uji hipotesis mediannya tidak berbeda signifikan
- Masih ada pelanggan yang tidak menerima promosi sama sekali, hal ini perlu untuk diminimalisir karena semakin banyak promosi yang diterima pelanggan, maka akan bisa meningkatkan pembelian produk wine
- Promo ke 5 menjadi promo yang paling banyak diterima oleh konsumen yang paling konsumtif terhadap produk wine
- Promo ke 3 menjadi promo yang paling sedikit diterima oleh konsumen yang paling konsumtif terhadap produk wine dengan perbedaan hampir 6x lipat


**Tempat pembelian wine terbanyak**

- Berdasarkan data 100 pelanggan pembeli wine terbanyak, pelanggan paling banyak membeli wine di Supermarket langsung daripada melalui website atau katalog
- Pelanggan paling sedikit membeli wine melalui katalog
- Secara korelasi, jumlah kunjungan website terhadap pembelian melalui website memiliki korelasi negatif dan lemah. Artinya, kunjungan website hampir tidak berpengaruh terhadap pembelian melalui website

# **Rekomendasi**

- Apabila ingin melakukan segmentasi pelanggan yang mempunyai minat tinggi terhadap produk wine, maka karakteristik pelanggan tersebut adalah :
    
    - Pelanggan dengan rentang usia 62-83 tahun
    - Pelanggan dengan pendidikan akhir PhD atau Graduation
    - Pelanggan dengan status pernikahan menikah atau bercerai
    - Pelanggan dengan Income Class Upper atau Middle (Income diatas $52,200 pertahun)
    - pelanggan yang tidak mempunyai anak kecil tapi mempunyai 1 atau 2 anak remaja
<br><br>
- Apabila ingin melakukan segmentasi pelanggan yang lebih spesifik, maka pilihlah pelanggan dengan karakteristik tidak mempunyai anak kecil tapi mempunyai 1 atau 2 anak remaja dan termasuk kedalam Middle atau Upper Income Class dengan pendidikan terakhir Graduation atau PhD dengan status menikah atau bercerai dengan rentang usia 62-83 tahun
- Gunakan data pelanggan yang paling konsumtif terhadap produk wine sebagai target untuk ditawari produk wine baru yang akan diluncurkan. Kita bisa memberi perlakuan atau penawaran khusus kepada para pelanggan tersebut dengan harapan pelanggan tersebut akan membeli produk wine yang baru dan semakin loyal dengan Supermarket kita.
- Wine adalah produk yang paling banyak dibeli di Supermarket selama 2 tahun terakhir sehingga hal ini dapat memperkecil kemungkinan produk wine yang akan diluncurkan tidak laku.
- Promo ke 5 menjadi promo yang paling banyak diterima oleh konsumen yang paling konsumtif terhadap produk wine sehingga promo ini harus lebih digencarkan lagi saat proses peluncuran produk wine baru.
- Masih ada pelanggan yang tidak menerima promosi sama sekali, hal ini perlu untuk diminimalisir karena semakin banyak promosi yang diterima pelanggan, maka akan bisa meningkatkan pembelian produk wine dan produk produk lainnya.
- Berdasarkan data, pelanggan paling banyak melakukan pembelian wine di Supermarket langsung. Maka dari itu, kita perlu memperhatikan kebersihan supermarket, tata letak produk wine baru yang akan diluncurkan, dan juga desain promosi sehingga bisa menarik minat konsumen untuk membeli produk wine
- Minat pembelian produk wine melalui website dan katalog masih kecil sehingga mungkin perlu adanya pemerhatian lebih terhadap website dan katalog yang Supermarket punya.
- Kinerja pelayanan terhadap pelanggan sejauh ini sangat memuaskan. Dari 2239 pelanggan, hanya 21 orang yang mengajukan komplain (sekitar 0.94%). Tapi kinerja pelayanan itu dirasa perlu terus dipertahankan bahkan ditingkatkan agar konsumen bisa tetap loyal terhadap Supermarket kita.
- Bulan Mei dan Agustus menjadi Bulan dengan penambahan konsumen baru yang paling tinggi, akan tetapi dari bulan Mei-Juli terjadi penurunan yang sangat signifikan meskipun dari bulan Juli-Agustus terjadi kenaikan yang signifikan juga (121 pelanggan baru). sehingga apabila ingin meluncurkan produk wine baru, ada baiknya peluncuran produk dilakukan pada bulan Juli-Agustus
