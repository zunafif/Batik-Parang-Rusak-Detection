# Batik-Parang-Rusak-Detection

Sistem deteksi ini digunakan untuk menentukan jenis batik yaitu parang rusak/non-parang rusak
Sistem ini menggunakan total 4 metode :
1. Metode Kirsch dan Robinson untuk mendeteksi tepian citra
2. Geometric Invaraint Moment untuk mendapatkan fitur bentuk citra yang sudah dideteksi tepinya
3. K-NN untuk menentukan jenis batik yang diuji

Dataset berupa data citra batik parang. Terbagi menjadi 2, yaitu :
1. Training : 115 citra batik
2. Testing : 50 citra batik

File final analisis digunakan untuk melakukan analisis perbedaan performa antara metode deteksi tepi Kirsch dan Robinson. Terdapat database yang digunakan untuk melakukan pengujian performa yang dilakukan secara manual di Excel

File final GUI adalah produk akhir yang bisa dijalankan pada web dengan bantuan tools anvil.works

Source code GUI di anvil.works : https://anvil.works/build#clone:GEC2QKGYLT2DSN2J=DFJMO4YLADMJTKQTBW2MJQJ2
