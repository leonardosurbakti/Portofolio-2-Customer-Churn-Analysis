# Portofolio-2-Customer-Churn-Analysis
## Latar Belakang
Sebuah toko olahraga menjuak berbagai kebutuhan olahraga, seperti Baju, Jaket, Sepatu, dan Tas. Toko ini didirikan dan mulai berjualan mulai tahun 2013 sehingga sudah memiliki pelanggan tetap, dan terus melakukan berbagai strategi untuk mendapat pelanggan baru sampai saat ini

Di awal tahun 2019, manajer toko tersebut memutuskan untuk melakukan analisis untuk mengetahui churn custmer toko tersebut. Churn customer adalah pelanggan yang sudah tidak bertransaksi ke tokonya lagi sampai dengan 6 bulan terakhir dari update data terakhir yang tersedia. Dataset yang digunakan adalah data transaksi toko dari tahun 2013 sampai dengan 2019 dalam bentuk csv dengan jumlah baris 100.000 baris data.

Pengolahan data dimulai dengan cleaning data yang akan digunakan. Beberapa hal yang dilakukan selama data cleaning adalah:
- Mengubah kolom First_Transaction ke dalam bentuk datetime
- Mengubah kolom Last_Transaction ke dalam bentuk datetime
- Menghapus kolom yang tidak diperlukan, seperti no dan Row_Num 

Setelah melakukan data cleaning, selanjutnya adalah data eksplorasi dan data visualisasi. Data eksplorasi dilakukan dengan melakukan analisis untuk menjawab beberapa pertanyaan bisnis yang berhubungan dengan dataset, seperti:
- Bagaimana jumlah proses penarikan pelanggan dari tahun ke tahun?
- Bagaimana perkembangan jumlah transaksi yang tercatat dari tahun ke tahun?
- Bagaimana tren rata-rata jumlah transaksi yang terjadi setiap tahun untuk setiap jenis barang yang tersedia di toko?
- Bagaimana kondisi churn customer dari setiap barang di toko?
