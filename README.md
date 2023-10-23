# Swiftshop

Software Requirements Specification
for
SWIFT SHOP WEBSITE

Versi 1.0 Disetujui



Disusun Oleh :

Kelompok 4 PEMWEB Manajemen Informatika A

Adellia - 22091397002

Anna Berttria Novem Budia - 22091397004

Ainul Mufidh - 22091397028



D4 Manajemen Informatika

Fakultas Vokasi

Universitas Negeri Surabaya 2023




Daftar Isi


1.	Pendahuluan

1.1	Tujuan Penulisan Dokumen

1.2	Konvensi Dokumen

1.3	Audien yang Dituju dan Pembaca yang Disarankan

1.4	Ruang Lingkup Produk

1.5	Batasan Desain dan Implementasi

1.6	Referensi

2.	Deskripsi Keseluruhan

2.1	Deskripsi Produk

2.2	Fungsi Produk

2.3	Penggolongan Karakteristik Pengguna

2.4	Lingkungan Operasi

2.5	Dokumentasi Pengguna

3.	Kebutuhan Antarmuka Eksternal

3.1	User Interfaces

3.2	Hardware Interfaces

3.3	Software Interfaces

3.4	Communications Interfaces

4.	Persyatatan Fungsional

4.1	Katalog Produk

4.2	Manajemen Akun

4.3	Keranjang Belanja

4.4	Manajemen Pesanan

4.5	Pencarian dan Filter Produk

4.6	Integrasi Pembayaran dan Pengiriman

4.7	Manajemen Akun Pengguna

4.8	Peran Pengguna

5.	Persyaratan Non Fungsional

5.1	Persyaratan Kinerja

5.2	Persyaratan Keamanan

5.3	Atribut Kualitas Perangkat Lunak

5.4	Peraturan Bisnis

6.	Persyaratan Lainnya
   
Appendix A: Glossary

Appendix B: Analysis Models

Appendix C: To Be Determined List



1.	Pendahuluan

1.1	Tujuan Penulisan Dokumen

Tujuan pembuatan sebuah website e-commerce adalah untuk memfasilitasi dan mempromosikan aktivitas perdagangan online. Swift Shop Website memungkinkan pemilik bisnis untuk menjual produk atau layanan mereka secara online kepada pelanggan khususnya produk digital. Ini membuka peluang untuk menjangkau pelanggan di berbagai geografi tanpa batasan geografis. Melalui penjualan online, bisnis dapat meningkatkan pendapatan mereka dengan mencapai lebih banyak pelanggan potensial dan memungkinkan penjualan 24/7. Swift Shop Website dapat membantu mengurangi biaya operasional bisnis fisik, seperti biaya sewa toko, gaji staf penjualan, dan biaya pengelolaan persediaan.

Swift Shop Website memberikan kemampuan untuk melacak perilaku pelanggan, analisis penjualan, dan mengumpulkan data pelanggan. Memungkinkan bisnis untuk membuat keputusan yang lebih baik dan merancang strategi pemasaran yang lebih efektif. Swift Shop Website memberikan kenyamanan kepada pelanggan dengan memungkinkan pelanggan untuk berbelanja kapan saja, di mana saja, dan dari perangkat apa saja dengan koneksi internet. Pelanggan dapat berinteraksi dengan bisnis melalui formulir kontak, obrolan langsung, atau layanan dukungan pelanggan online yang memungkinkan pelanggan untuk mendapatkan bantuan atau informasi tambahan.

Swift Shop Website telah menjadi salah satu alat yang sangat penting bagi bisnis modern karena memberikan akses ke pasar global dan memungkinkan bisnis untuk beroperasi secara efisien di dunia maya. Dengan fitur yang canggih dan kemampuan untuk melakukan transaksi online, Swift Shop Website memungkinkan pelanggan untuk berbelanja dengan nyaman dan memungkinkan bisnis untuk memperluas jangkauan mereka.



1.2	Konvensi Dokumen

Pengembang adalah tiga mahasiswa yang sedang menyelesaikan tugas membuat website sebagai bagian dari tugas mata kuliah. Pengembang memiliki kendala waktu dan sumber daya terbatas, tetapi fokus pada pembelajaran serta panduan dari dosen pembimbing. Tujuan kami adalah untuk menyelesaikan proyek Swift Shop Website sesuai dengan persyaratan dan mendapatkan nilai yang baik dalam mata kuliah Pemrograman Web. Maka Swift Shop Website ini akan memiliki kemampuan berikut :


1.	Website akan menampilkan daftar lengkap produk beserta deskripsi, harga, dan gambar.

2.	Pengguna akan dapat membuat akun.
   
3.	Pengguna akan dapat menambahkan produk ke keranjang belanja, mengedit isi keranjang dan menyelesaikan proses pembayaran.

4.	Pengguna akan dapat mengelola pesanan mereka, termasuk melacak status pengiriman.

5.	Sistem akan memiliki kemampuan untuk mencari dan memfilter produk.

6.	Integrasi dengan gateway pembayaran eksternal dan penyedia pengiriman akan tersedia.

7.	Akun pengguna akan memiliki profil dengan kemampuan otentikasi (login/logout).

8.	Peran pengguna akan dibagi menjadi admin, pelanggan, dan penjual, dengan setiap peran memiliki akses yang berbeda sesuai dengan fungsi mereka dalam platform.



1.3	Audien yang Dituju dan Pembaca yang Disarankan

Swift Shop Website ditujukan bagi konsumen untuk berbelanja online, penjual untuk menjual produk, pengembang web untuk mengembangkan dan mengelola situs web, pengiriman dan logistik untuk mengirimkan produk, akuntansi dan keamanan pemroses pembayaran untuk transaksi online, pemasaran dan analis untuk mempromosikan dan menganalisis data juga sebagai pemerintah/regulator dan pemilik usaha/investor yang terlibat dalam pengelolaan dan pembiayaan usaha e-commerce.
