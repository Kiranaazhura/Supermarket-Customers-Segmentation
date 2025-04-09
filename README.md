# Supermarket-Customers-Segmentation

## Latar Belakang

Supermarket merupakan bisnis ritel yang sangat kompetitif, dimana kepuasaan pelanggan dan strategi pemasaran yang efektif menjadi kunci kesuksesan. Dengan meningkatnya persaingan dan perubahan perilaku pelanggan, supermarket perlu memahami karakteristik pelanggan untuk meningkatkan penjualan, loyalitas, dan efisiensi operasional. Analisis perilaku pelanggan adalah salah satu cara bagi perusahaan untuk mendapatkan pemahaman lebih baik mengenai selera pasar dan menciptakan kesempatan bisnis baru. 

LRFM Analysis adalah teknik segmentasi pelanggan yang mirip dengan RFM (Recency, Frequency, Monetary), tetapi dengan penambahan dimensi baru, yaitu Length. LRFM adalah singkatan dari:

`L (Length):` Mengukur durasi atau panjang hubungan antara pelanggan dan perusahaan, biasanya dihitung sebagai selisih antara tanggal pembelian pertama dan terakhir. Indikator ini menunjukkan loyalitas atau kesetiaan jangka panjang pelanggan terhadap merek atau produk.

`R (Recency):` Mengukur seberapa baru atau terkini transaksi terakhir yang dilakukan oleh pelanggan. Semakin kecil nilainya, semakin baru transaksi tersebut, yang menunjukkan bahwa pelanggan masih aktif.

`F (Frequency):` Mengukur seberapa sering pelanggan melakukan transaksi dalam periode waktu tertentu. Pelanggan yang sering bertransaksi cenderung lebih loyal.

`M (Monetary):` Mengukur total nilai atau jumlah uang yang dihabiskan oleh pelanggan selama periode waktu tertentu. Semakin tinggi nilainya, semakin berharga pelanggan tersebut bagi perusahaan.

## Rumusan Masalah
Berdasarkan latar belakang yang telah diuraikan, analisis yang akan dilakukan sebagai berikut:
1. Bagaimana karakteristik segmentasi pelanggan supermarket dengan LRFM?
2. Bagaimana performa penjualan antar-segmen pelanggan, serta produk apa yang paling dominan pada masing-masing segmen?
3. Seberapa besar pengaruh pemberian diskon terhadap monetary dan frekuensi pelanggan?
4. Bagaimana distribusi jumlah pelanggan dan total penjualan melalui berbagai kanal (store, web, dan katalog)?
5. Bagaimana efektiVitas kampanye/promosi yang dilakukan?
6. Bagaimana distribusi komplain pelanggan?

## Penjelasan Kolom
|Nama Kolom|Deskripsi|
|-----------|---------|
|ID|Pengenal unik pelanggan|
|Year_Birth|Tahun lahir pelanggan|
|Education|Tingkat pendidikan pelanggan|
|Marital_Status|Status pernikahan pelanggan|
|Income|Pendapatan rumah tangga tahunan pelanggan|
|Kidhome|Jumlah anak-anak dalam rumah tangga pelanggan|
|Teenhome|Jumlah remaja dalam rumah tangga pelanggan|
|Dt_Customer|Tanggal pendaftaran pelanggan sebagai member supermarket|
|Recency|Jumlah hari sejak pembelian terakhir pelanggan|
|MntWines|Jumlah yang dibelanjakan untuk wine dalam 2 tahun terakhir|
|MntFruits|Jumlah yang dibelanjakan untuk buah dalam 2 tahun terakhir|
|MntMeatProducts|Jumlah yang dibelanjakan untuk daging dalam 2 tahun terakhir|
|MntFishProducts|Jumlah yang dibelanjakan untuk ikan dalam 2 tahun terakhir|
|MntGoldProds|Jumlah yang dibelanjakan untuk emas dalam 2 tahun terakhir|
|NumDealsPurchases|Jumlah pembelian yang dilakukan dengan diskon|
|AcceptedCmp1-5|1 Jika pelanggan menerima penawaran pada promosi 1-5, 0 jika tidak|
|Response|1 Jika pelanggan menerima penawaran pada promosi terakhir, 0 jika tidak|
|Complain|1 Jika pelanggan ada keluhan dalam 2 tahun terakhir, 0 jika tidak|

## Link Tableu
[Tableu Supermarket](https://public.tableau.com/views/SupermarketCustomersSegmentation/Cover?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
