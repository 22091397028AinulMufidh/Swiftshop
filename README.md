# Swiftshop
<div align="center">
<h2>Software Requirements Specification for</h2>
<h1>Swiftshop Website E-commerce</h1>

Versi 1.0 Disetujui


Disusun Oleh :

Kelompok 4 PEMWEB Manajemen Informatika A

Adellia - 22091397002

Anna Berttria Novem Budia - 22091397004

Ainul Mufidh - 22091397028


D4 Manajemen Informatika

Fakultas Vokasi

Universitas Negeri Surabaya 2023
</div>


<h2>Daftar Isi</h2>

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


<h2>1. Pendahuluan</h2>

<h3>1.1	Tujuan Penulisan Dokumen</h3>
<div align="justify">

Tujuan pembuatan sebuah website e-commerce adalah untuk memfasilitasi dan mempromosikan aktivitas perdagangan online. Swift Shop Website memungkinkan pemilik bisnis untuk menjual produk atau layanan mereka secara online kepada pelanggan khususnya produk digital. Ini membuka peluang untuk menjangkau pelanggan di berbagai geografi tanpa batasan geografis. Melalui penjualan online, bisnis dapat meningkatkan pendapatan mereka dengan mencapai lebih banyak pelanggan potensial dan memungkinkan penjualan 24/7. Swift Shop Website dapat membantu mengurangi biaya operasional bisnis fisik, seperti biaya sewa toko, gaji staf penjualan, dan biaya pengelolaan persediaan.

Swift Shop Website memberikan kemampuan untuk melacak perilaku pelanggan, analisis penjualan, dan mengumpulkan data pelanggan. Memungkinkan bisnis untuk membuat keputusan yang lebih baik dan merancang strategi pemasaran yang lebih efektif. Swift Shop Website memberikan kenyamanan kepada pelanggan dengan memungkinkan pelanggan untuk berbelanja kapan saja, di mana saja, dan dari perangkat apa saja dengan koneksi internet. Pelanggan dapat berinteraksi dengan bisnis melalui formulir kontak, obrolan langsung, atau layanan dukungan pelanggan online yang memungkinkan pelanggan untuk mendapatkan bantuan atau informasi tambahan.

Swift Shop Website telah menjadi salah satu alat yang sangat penting bagi bisnis modern karena memberikan akses ke pasar global dan memungkinkan bisnis untuk beroperasi secara efisien di dunia maya. Dengan fitur yang canggih dan kemampuan untuk melakukan transaksi online, Swift Shop Website memungkinkan pelanggan untuk berbelanja dengan nyaman dan memungkinkan bisnis untuk memperluas jangkauan mereka.
</div>


<h3>1.2	Konvensi Dokumen</h3>

Pengembang adalah tiga mahasiswa yang sedang menyelesaikan tugas membuat website sebagai bagian dari tugas mata kuliah. Pengembang memiliki kendala waktu dan sumber daya terbatas, tetapi fokus pada pembelajaran serta panduan dari dosen pembimbing. Tujuan kami adalah untuk menyelesaikan proyek Swift Shop Website sesuai dengan persyaratan dan mendapatkan nilai yang baik dalam mata kuliah Pemrograman Web. Maka Swift Shop Website ini akan memiliki kemampuan berikut :


<div align="justify">

1.	Website akan menampilkan daftar lengkap produk beserta deskripsi, harga, dan gambar.

2.	Pengguna akan dapat membuat akun.
   
3.	Pengguna akan dapat menambahkan produk ke keranjang belanja, mengedit isi keranjang dan menyelesaikan proses pembayaran.

4.	Pengguna akan dapat mengelola pesanan mereka, termasuk melacak status pengiriman.

5.	Sistem akan memiliki kemampuan untuk mencari dan memfilter produk.

6.	Integrasi dengan gateway pembayaran eksternal dan penyedia pengiriman akan tersedia.

7.	Akun pengguna akan memiliki profil dengan kemampuan otentikasi (login/logout).

8.	Peran pengguna akan dibagi menjadi admin, pelanggan, dan penjual, dengan setiap peran memiliki akses yang berbeda sesuai dengan fungsi mereka dalam platform.
</div>


<h3>1.3	Audien yang Dituju dan Pembaca yang Disarankan</h3>
<div align="justify">
Swift Shop Website ditujukan bagi konsumen untuk berbelanja online, penjual untuk menjual produk, pengembang web untuk mengembangkan dan mengelola situs web, pengiriman dan logistik untuk mengirimkan produk, akuntansi dan keamanan pemroses pembayaran untuk transaksi online, pemasaran dan analis untuk mempromosikan dan menganalisis data juga sebagai pemerintah/regulator dan pemilik usaha/investor yang terlibat dalam pengelolaan dan pembiayaan usaha e-commerce.
</div>


<h3>1.4 Ruang Lingkup Produk</h3>

Lingkup pada Swift Shop Website dapat mencakup fitur berikut :

1.	Katalog Produk.

2.	Manajemen Akun.

3.	Keranjang Belanja.

4.	Manajemen Pesanan.

5.	Pencarian dan Filter Produk.

6.	Integrasi Pembayaran dan Pengiriman.

7.	Manajemen Akun Pengguna.


<h3>1.5 Batasan Desain dan Implementasi</h3>

Keterbatasan desain dan implementasi pada Swift Shop Website meliputi :

1.	Keamanan Data Pelanggan : Perlindungan data pribadi dan pembayaran.

2.	Antarmuka Pengguna yang Intuitif : Navigasi yang mudah dipahami.

3.	Kinerja Situs Web : Waktu pemuatan cepat dan kinerja bagus.

4.	Ketersediaan : Pemantauan yang kuat dan rencana pemulihan.

5.	Manajemen persediaan : Memantau inventaris produk.

6.	Integrasi Dengan Sistem Pembayaran : Metode pembayaran yang didukung.

7.	Peralatan Memenuhi : Akses di beberapa perangkat.

8.	Analisis dan Pemantauan : Alat pelacakan perilaku pengguna.


<h3>1.6	Referensi</h3>

Referensi yang digunakan dalam dokumen hasil analisis adalah sebagai berikut :

1.	Artikel/Jurnal Ilmiah

2.	Referensi Website Penjualan


<h2>2.	Deskripsi Keseluruhan</h2>

<h3>2.1	Deskripsi Produk</h3>
<div align="justify">

Swift Shop Website adalah platform online yang dirancang khusus untuk melakukan transaksi jual beli produk atau layanan melalui internet. Website ini adalah bentuk perdagangan elektronik (e-commerce) yang memungkinkan bisnis untuk menjual produk atau layanan kepada pelanggan dengan menggunakan website sebagai saluran utama. Swift Shop Website memiliki katalog produk yang mencantumkan produk atau layanan yang dijual oleh bisnis. Setiap produk akan disertai dengan gambar, deskripsi, harga, dan detail lainnya yang dapat membantu pelanggan dalam memahami produk tersebut. Fitur Keranjang yang memungkinkan pelanggan untuk memilih produk atau layanan yang ingin mereka beli dan menampungnya dalam "keranjang belanja" virtual. Memungkinkan pelanggan untuk melanjutkan penjelajahan dan mengevaluasi barang-barang yang mereka pilih sebelum melakukan pembayaran.

Formulir dan proses pembayaran yang aman. Pelanggan dapat memilih metode pembayaran yang beragam, seperti kartu kredit, transfer bank, atau pembayaran melalui layanan pembayaran pihak ketiga seperti PayPal. Setelah pelanggan menyelesaikan pembayaran, sistem Swift Shop Website akan mengelola pesanan tersebut dengan melibatkan pengelolaan inventaris, pembuatan faktur, pemrosesan pesanan, dan pelacakan pengiriman. Keamanan adalah aspek penting dari website e-commerce yang mencakup perlindungan terhadap pencurian data pribadi pelanggan, seperti informasi kartu kredit, serta keamanan dalam proses pembayaran. Sistem Manajemen Konten (CMS) Sistem manajemen konten memungkinkan pemilik website untuk dengan mudah mengelola dan memperbarui konten, termasuk informasi produk, deskripsi, harga, dan gambar.

Bisnis dapat dengan mudah menjalankan kampanye promosi, diskon, atau penawaran khusus melalui Swift Shop Website untuk menarik pelanggan. Swift Shop Website dapat diintegrasikan dengan sistem back-end yang mencakup manajemen persediaan, manajemen pesanan, dan pemrosesan pembayaran untuk mengotomatiskan proses bisnis. Dengan memungkinkan pelanggan untuk melacak status pesanan mereka dan mengajukan pertanyaan melalui website, bisnis dapat memberikan pelayanan pelanggan yang lebih baik.
</div>


<h3>2.2	Fungsi Produk</h3>

<div align="justify">
Beberapa fungsi yang ada pada Swift Shop Website, antara lain :

1.	Pendaftaran pengguna dengan verifikasi email : Fitur ini memungkinkan pengguna  membuat akun dengan mengisi informasi pribadi  dan memverifikasi alamat email  melalui link verifikasi yang dikirimkan melalui email.

2.	Daftar produk dengan informasi rinci : Menampilkan daftar lengkap produk beserta gambar, deskripsi, harga, dan informasi lainnya sehingga pengguna dapat  dengan mudah menemukan produk.

3.	Keranjang : Memungkinkan pengguna  menambahkan produk ke keranjang, mengubah jumlah produk, dan mengeluarkan produk dari keranjang.

4.	Proses checkout dengan opsi pembayaran : Memungkinkan pengguna untuk melanjutkan  proses checkout setelah menambahkan produk ke keranjang. Ini juga harus mencakup berbagai pilihan pembayaran, seperti kartu kredit, transfer bank, atau pembayaran melalui sistem pembayaran pihak ketiga.

5.	Kelola pesanan pelanggan : Setelah pembelian berhasil, pengguna akan dapat melihat riwayat pesanan, status pengiriman, dan detail pembayaran.

6.	Cari dan filter produk berdasarkan kategori : Fitur pencarian  memungkinkan pengguna mencari produk berdasarkan kata kunci dan memfilter produk berdasarkan kategori atau atribut lainnya, seperti harga, merek, atau ukuran.

7.	Sistem pemrosesan pembayaran yang aman : Menyediakan sistem pemrosesan pembayaran yang aman dan terenkripsi untuk melindungi data keuangan pengguna.

8.	Kelola akun dan profil pengguna : Pengguna  dapat mengelola informasi akun mereka, termasuk alamat pengiriman, kata sandi, dan preferensi lainnya.

9.	Integrasi dengan gateway pembayaran dan penyedia pengiriman : Integrasikan dengan layanan gateway pembayaran seperti PayPal, Stripe, dan penyedia pengiriman seperti FedEx atau UPS untuk mengelola pembayaran dan pengiriman produk secara efisien.
</div>


<h3>2.3	Penggolongan Karakteristik Pengguna</h3>

<div align="justify">
Tingkatan kelas dalam Swift Shop Website mengatur hak akses dan persyaratan berikut :

1.	Pengunjung : Hanya dapat melihat produk dan informasi umum, tidak perlu registrasi.

2.	Pengguna Terdaftar : Dapat menambahkan produk ke keranjang dan mengelola akun setelah pendaftaran.

3.	Pelanggan : Setelah melakukan pembelian, dapat menyelesaikan proses pembayaran dan melacak pesanan.

4.	Anggota Premium/Berlangganan : Dapatkan akses eksklusif dengan berlangganan atau membayar biaya tambahan.

5.	Admin/Staff Toko : Pengelolaan website dan pesanan, hanya oleh personel yang berwenang.

6.	Pemilik Toko : Kewenangan penuh untuk mengelola bisnis e-commerce.
</div>


![SharedScreenshot](https://github.com/22091397028AinulMufidh/Swiftshop/assets/124455536/34f29fd6-7621-4850-bb33-d22b4846200f)


<h3>2.4	Lingkungan Operasi</h3>

<div align="justify">
Perangkat lunak berbasis web ini dapat diakses melalui berbagai perangkat seperti laptop, ponsel dan sebagainya. Sistem operasi yang digunakan juga kompatibel dengan dengan berbagai sistem operasi seperti windows, mac OS,android. Dan dapat diakses melalui web versi terbaru atau yang paling umum digunakan saat ini.
</div>

<h3>2.5	Dokumentasi Pengguna</h3>

<div align="justify">
Dokumentasi pengguna pada Swift Shop Website harus mencakup panduan singkat tentang pendaftaran, navigasi, pencarian produk, pengelolaan keranjang belanja, proses checkout, manajemen akun, pengembalian dan garansi, bantuan, kebijakan privasi, tata cara pengaduan, dan tutorial video. Dokumentasi ini akan mudah diakses dan terus diperbarui.
</div>


<h2>3. Persyatatan Fungsional</h2>
   
<h3>3.1	Katalog Produk</h3>

<h4>3.1.1 Deskripsi dan Prioritas</h4>

Deskripsi: Fitur ini mencakup daftar lengkap produk dengan deskripsi, harga, dan gambar.

Prioritas: Tinggi.

 
<h4>3.1.2 Urutan Stimulus/Respon</h4>

Stimulus: Pengguna mengakses halaman produk.

Respon: Tampilan daftar produk dengan informasi terperinci.

 
<h4>3.1.3 Persyaratan Fungsional</h4>

1.	Fitur harus mampu menampilkan daftar produk dengan judul, deskripsi, harga, gambar, dan ketersediaan.

2.	Pengguna harus dapat mengurutkan dan mengelompokkan produk berdasarkan kategori atau fitur lainnya.

3.	Fitur pencarian produk harus memungkinkan pengguna mencari produk berdasarkan kata kunci.
   

<h3>3.2	Manajemen Akun</h3>


<h4>3.2.1 Deskripsi dan Prioritas</h4>

Deskripsi: Memungkinkan pengguna untuk membuat akun.

Prioritas: Tinggi.
 
<h4>3.2.2 Urutan Stimulus/Respon</h4>

Stimulus: Pengguna memilih opsi “Membuat Akun”.

Respon: Formulir pendaftaran dan konfirmasi akun.
 
<h4>3.2.3 Persyaratan Fungsional</h4>

1.	Pengguna harus dapat membuat akun dengan mengisi informasi pribadi seperti nama, alamat email, dan kata sandi.

2.	Sistem harus mengirimkan email verifikasi ke pengguna untuk mengaktifkan akun mereka.

3.	Pengguna yang sudah terdaftar harus dapat masuk ke akun mereka dengan otentikasi yang aman.


<h4>3.3.2 Urutan Stimulus/Respon</h4>

Stimulus: Pengguna menambahkan produk ke keranjang.
 
Respon: Produk ditambahkan ke keranjang.
 
Stimulus: Pengguna mengklik "Selesaikan Pembelian."
 
Respon: Langkah-langkah pembayaran.


<h4>3.3.3 Persyaratan Fungsional</h4>

1.	Pengguna harus dapat membuat akun dengan mengisi informasi pribadi seperti nama, alamat email, dan kata sandi.

2.	Sistem harus mengirimkan email verifikasi ke pengguna untuk mengaktifkan akun mereka.

3.	Pengguna yang sudah terdaftar harus dapat masuk ke akun mereka dengan otentikasi yang aman.


<h3>3.4	Manajemen Pesanan</h3>


<h4>3.4.1	Deskripsi dan Prioritas</h4>

Deskripsi: Pengguna dapat mengelola pesanan mereka, termasuk melacak status pengiriman.
 
Prioritas: Tinggi.


3.4.2	Urutan Stimulus/Respon

	Stimulus: Pengguna mengakses halaman manajemen pesanan.
 
	Respon: Tampilan daftar pesanan dan status pengiriman.
 
3.4.3	Persyaratan Fungsional
1.	Pengguna harus dapat membuat akun dengan mengisi informasi pribadi seperti nama, alamat email, dan kata sandi.
2.	Sistem harus mengirimkan email verifikasi ke pengguna untuk mengaktifkan akun mereka.
3.	Pengguna yang sudah terdaftar harus dapat masuk ke akun mereka dengan otentikasi yang aman.

3.5	Pencarian dan Filter Produk

3.5.1	Deskripsi dan Prioritas

	Deskripsi: Sistem memiliki kemampuan untuk mencari dan memfilter produk.
 
	Prioritas: Sedang.
 
3.5.2	Urutan Stimulus/Respon

	Stimulus: Pengguna melakukan pencarian produk.
 
	Respon: Hasil pencarian dengan produk yang sesuai.
 3.5.3	Persyaratan Fungsional
1.	Pengguna harus dapat membuat akun dengan mengisi informasi pribadi seperti nama, alamat email, dan kata sandi.
2.	Sistem harus mengirimkan email verifikasi ke pengguna untuk mengaktifkan akun mereka.
3.	Pengguna yang sudah terdaftar harus dapat masuk ke akun mereka dengan otentikasi yang aman.
   
3.6	Integrasi Pembayaran dan Pengiriman

3.6.1	Deskripsi dan Prioritas
 
	Deskripsi: Integrasi dengan gateway pembayaran eksternal dan penyedia pengiriman akan tersedia.
 
	Prioritas: Tinggi
 
 Urutan Stimulus/Respon
 
	Stimulus: Pengguna memilih opsi pembayaran.
 
	Respon: Pilihan pembayaran dan pengisian detail pembayaran.
 
	Stimulus: Pengguna memilih opsi pengiriman.
 
	Respon: Pilihan pengiriman dan estimasi biaya.
 
3.6.3	Persyaratan Fungsional

1.	Pengguna harus dapat membuat akun dengan mengisi informasi pribadi seperti nama, alamat email, dan kata sandi.
2.	Sistem harus mengirimkan email verifikasi ke pengguna untuk mengaktifkan akun mereka.
3.	Pengguna yang sudah terdaftar harus dapat masuk ke akun mereka dengan otentikasi yang aman.
   
3.7	Manajemen Akun Pengguna

3.7.1	Deskripsi dan Prioritas

	Deskripsi: Akun pengguna akan memiliki profil dan otentikasi.
 
	Prioritas: Sedang.
 
3.7.2	Urutan Stimulus/Respon

	Stimulus: Pengguna mengakses halaman produk.
 
	Respon: Tampilan daftar produk dengan informasi terperinci.
 
3.7.3	Persyaratan Fungsional

1.	Pengguna harus dapat membuat akun dengan mengisi informasi pribadi seperti nama, alamat email, dan kata sandi.
2.	Sistem harus mengirimkan email verifikasi ke pengguna untuk mengaktifkan akun mereka.
3.	Pengguna yang sudah terdaftar harus dapat masuk ke akun mereka dengan otentikasi yang aman.
   
3.8	Peran Pengguna

3.8.1	Deskripsi dan Prioritas

	Deskripsi: Ada peran pengguna seperti admin, pelanggan, dan penjual.
 
	Prioritas: Sedang.
 
3.8.2	Urutan Stimulus/Respon

	Stimulus: Pengguna memilih peran (misalnya, pelanggan atau penjual) saat mendaftar.
 
	Respon: Hak akses sesuai peran yang dipilih.
 
4.8.3 Persyaratan Fungsional
1.	Pengguna harus dapat membuat akun dengan mengisi informasi pribadi seperti nama, alamat email, dan kata sandi.
2.	Sistem harus mengirimkan email verifikasi ke pengguna untuk mengaktifkan akun mereka.
3.	Pengguna yang sudah terdaftar harus dapat masuk ke akun mereka dengan otentikasi yang aman
   
4.	Persyaratan Non Fungsional
   
4.1	Persyaratan Kinerja

Website yang kami kembangkan memiliki beberapa kebutuhan yang berkaitan dengan kinerja website seperti waktu respons, kecepatan pemrosesan, kapasitas, dan efisiensi jaringan yang dijelaskan sebagai berikut :
1.	Waktu untuk membuka halaman harus di bawah 3 detik.
2.	Sistem harus mampu menangani minimal 500 pengguna secara bersamaan.
3.	Keamanan data harus dipastikan dengan mengenkripsi data pelanggan.
4.	Antarmuka pengguna harus intuitif dan responsif.
   
4.2	Persyaratan Keamanan

Persyaratan keamanan Swift Shop Website melibatkan enkripsi data, perlindungan data pelanggan, manajemen akses, pemantauan aktivitas, perlindungan aplikasi, dan kebijakan kata sandi kuat. Juga, perlindungan terhadap penipuan dan kecurangan, pemantauan ketersediaan, pemeliharaan rutin, serta pelatihan staff dalam praktik keamanan. Dengan ini, Swift Shop Website akan menjaga keamanan data dan kepercayaan pelanggan.

4.3 Atribut Kualitas Perangkat Lunak

![tabel 2](https://github.com/22091397028AinulMufidh/Swiftshop/assets/124547755/92b1ced0-e563-451a-be1d-c3e98d8ccfed)

4.4	Peraturan Bisnis

Berikut beberapa aturan bisnis yang diterapkan dalam Swift Shop Website:

1.	Kebijakan pengembalian dan harga yang jelas.
2.	Privasi data pelanggan dan kualitas produk yang baik.
3.	Layanan pelanggan yang responsif dan pengamanan transaksi.
4.	Informasi produk yang lengkap dan pemantauan ketersediaan.
5.	Kepatuhan hukum dan kredibilitas yang terpercaya.

5.	Persyaratan Lainnya
   
1.	Persyaratan Basis Data
   
Mencakup persyaratan yang berkaitan dengan cara data disimpan, diakses dan dikelola pada sistem Swift Shop Website, yaitu:

-	Struktur Basis Data: Mencakup pengelolaan data produk, pelanggan, stok, harga dan transaksi disimpan di dalamnya.
-	Keamanan Basis Data: Mencakup pengelolaan perlindungan informasi pelanggan dan transaksi.
-	Integritas Basis Data: Mencakup pengelolaan sistem yang berinteraksi dengan data seperti melakukan pembaruan data ketika pembelian dilakukan.
  
2.	Persyaratan Internalisasi
   
Dukungan bahasa pada Swift Shop Website memprioritaskan pada penggunaan bahasa Indonesia dan juga bahasa Inggris. Terdapat rencana untuk menambahkan beberapa bahasa agar dapat diakses oleh berbagai negara. Harga produk dalam Swift Shop juga dapat diubah menjadi mata uang lokal tiap pengguna dan kemungkinan dapat melakukan pengiriman ke berbagai negara dengan biaya pengiriman yang telah ditentukan.

3.	Persyaratan Resmi
   
Mencakup persyaratan pada Swift Shop Website yang wajib dilakukan sesuai dengan peraturan hukum yang berlaku, yaitu:

-	Kebijakan Privasi: Mencakup pengelolaan privasi yang harus dipenuhi mengenai perlindungan data pelanggan.
-	Kepatuhan Hukum: Mematuhi peraturan perdagangan bidang elektronik serta perlindungan pelanggan telah sesuai dengan yang berlaku di wilayah yang akan dijalankan.
-	Syarat dan Ketentuan: Menguraikan peraturan yang wajib diikuti oleh konsumen saat melakukan pembelian pada Swift Shop Website.

4.	Gunakan kembali Tujuan Untuk Proyek
   
-	Tujuan Pengguna: Pembuatan situs web swift shop diharapkan mampu memberikan kemudahan dalam berbelanja, produk xiaomi terbaru dan pengalaman pembeli yang nyaman.
-	Tujuan Bisnis: Dengan adanya situs web swift shop diharapkan mampu meningkatkan jangkauan pasar, menaikkan jumlah penjualan, dan branding yang lebih kuat.
-	Tujuan Teknis: Dapat melakukan perbaikan operasional, keamanan, dan skala akses sistem yang lebih luas.

Appendix A: Glossary

![Appendix glossary](https://github.com/22091397028AinulMufidh/Swiftshop/assets/124547755/c7170a11-2f28-44ec-9cfc-6c20dcaae0cf)

Appendix B: Analysis Models

1.	Data Flow Diagram (DFD)

-	Data Flow Diagram Level 0

![dfd level 0 revisi drawio](https://github.com/22091397028AinulMufidh/Swiftshop/assets/124547755/eca2772f-5c81-43e1-92dd-e6431518aee7)


-	Data Flow Diagram Level 1 Bagian 1

![dfd level 1 revisii drawio](https://github.com/22091397028AinulMufidh/Swiftshop/assets/124547755/e835545e-30d1-4d2a-a1c7-5b1c34486774)

-	Data Flow Diagram Level 1 Bagian 2

![dfd 2 1 revisii](https://github.com/22091397028AinulMufidh/Swiftshop/assets/124547755/5111a80b-ac7e-4d93-9334-f0786defcd05)

2.	Entity Relationship Diagram (ERD)
   
![ERD](https://github.com/22091397028AinulMufidh/Swiftshop/assets/124547755/af6f2eaf-141c-4c3d-b215-ec16059c89eb)

3.	Class Diagram
   
![Class Diagram](https://github.com/22091397028AinulMufidh/Swiftshop/assets/124547755/627e811f-0569-4df5-b377-47962c56f64e)

4.	Use Cae

![Use Case](https://github.com/22091397028AinulMufidh/Swiftshop/assets/124547755/8a702ef6-80b0-48cb-b024-3fcab2fef7d8)

5.	Flowchart

![Flowchart](https://github.com/22091397028AinulMufidh/Swiftshop/assets/124547755/5c65c5b9-78bb-42db-9083-bd3d9a1e85a9)

Appendix C: To Be Determined List

Pada Swift Shop Website terdapat beberapa hal yang masih perlu diperjelas dan ditentukan sebelum proses pengembangan dimulai, yaitu : 

1.	Desain Antarmuka Pengguna (UI/UX): Rincian tentang tampilan dan pengalaman pengguna, termasuk warna, tata letak, ikon, dan elemen navigasi.
2.	Spesifikasi Teknis: Teknologi dan bahasa pemrograman yang akan digunakan serta pemilihan kerangka kerja atau platform e-commerce.
3.	Keamanan Data dan Pembayaran: Bagaimana data pelanggan akan dilindungi dan metode pembayaran yang akan digunakan.
4.	Manajemen Produk dan Persediaan: Cara mengelola produk, manajemen stok, dan proses unggah produk.
5.	Integrasi Pihak Ketiga: Apakah akan mengintegrasikan layanan pihak ketiga seperti pembayaran atau penyedia pengiriman.
6.	Pemeriksaan dan Uji Coba: Rencana pemeriksaan dan uji coba produk sebelum peluncuran.
7.	Kebijakan Pengembalian dan Layanan Pelanggan: Rincian kebijakan pengembalian dan bagaimana layanan pelanggan akan dijalankan.
8.	Pengelolaan Proyek: Rencana manajemen proyek, termasuk pembagian tugas dan jadwal.
9.	Pemasaran dan Peluncuran: Strategi pemasaran dan pengukuran kesuksesan peluncuran.
10.	Peraturan dan Kepatuhan Hukum: Pematuhan terhadap regulasi dan hukum yang berlaku, seperti privasi data dan perpajakan e-commerce.

PENJELASAN CODINGAN:

LOGIN DAN SIGNUP

Penjelasan HTML Login dan signup:

a.	&lt;!DOCTYPE html&gt;

Sebuah pernyataan yang mengidentifikasi bahwa pada halaman web ini menggunakan dokumen HTML yang paling terbaru

b.	&lt;html lang=”en”&gt;


Sebuah elemen akar/root dari dokumen HTML yang di dalamnya terdapat semua elemen HTML dan seluruh konten halaman web. Kemudian lang=”en yang menandakan bahwa isi web ini ditulis dengan bahasa inggris

c.	&lt;head&gt;

Sebuah elemen kepala dari dokumen HTML yang berisikan informasi penting untuk pengaturan dan analisis halaman web sepeti tautan file ke CSS dan judul halaman. Yang berisikan:

•	&lt;meta charset="UTF-8"&gt;

Sebuah elemen untuk menentukan karakter set (encoding) dalam dokumen HTML. Deklarasi charset=”UTF-8” merupakan format encoding yang berguna agar halaman web mampu menampilkan teks dalam beragam bahasa dengan tepat.

•	&lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;

Sebuah elemen meta untuk mengatur tampilan web dan konten pada halaman akan menyesuaikan dengan lebar perangkat, kemudian halaman web 1.0 yang artinya web akan ditampilkan pada ukuran aslinya tanpa perbesaran atau perkecilan.

•	&lt;title>Membuat Form Login</title&gt;

Sebuah elemen <tittle> untuk menetapkan judul yang akan ditampilkan pada tab peramban web yang membantu pengguna dan server lebih efektif saat mengenali isi dari halaman web dengan 

•	&lt;link rel="stylesheet" href="./style.css"&gt;

Sebuah elemen <link> yang menghubungkan halaman web dengan file CSS eksternal, dengan penjelasan:
-rel="stylesheet" : Membuktikan bahwa file yang dihubungkan merupakan file CSS untuk mengubah atau mengendalikan tampilan halaman web
-href="./style.css": Menentukan lokasi atau URL dari file CSS eksternal untuk mengatur halaman tampilan halaman web sehingga “style.css” harus berada tepat dengan direktori yang sama dengan halaman web.


d.	&lt;body&gt;

Sebuah bagian yang memuat isi utama dari sebuah elemen web yang isinya akan muncul kepada pengguna ketika mengakses halaman web. Dengan ketentuan:

•	&lt;div class="wrapper"&gt;

Sebuah elemen yang menggunakan atribut class dengan nilai “wrapper” yang mengelompokkan atau mengatur tata letak konten di dalamnya. 

•	&lt;div class="title-text"&gt;

Sebuah elemen yang merupakan turunan dari sebelumnya, berfungsi mengelompokkan teks-teks di dalamnya.

•	&lt;div class="title login"&gt;

Berfungsi untuk memberikan judul “Form Login”

•	&lt;div class="title signup"&gt;

Berfungsi untuk memberikan judul “Form Registrasi”

•	&lt;div class="form-container"&gt;

Berfungsi untuk mengelompokkan elemen-elemen yang ada dalam formulir

•	&lt;div class="slide-controls"&gt;

Berfungsi untuk mengumpulkan elemen yang berhubungan dengan tombol Login dan Daftar
 
•	&lt;input type="radio" name="slide" id="login" checked&gt;

Sebuah elemen input dengan dua atribut yairu “name” dengan nilai “slide” dan “id” dengan nilai “login” dan ditandai sebagai “checked” yang berarti apabila pilihan pertama login, maka akan terpilih secara otomatis saat membuka halaman

•	&lt;input type="radio" name="slide" id="signup"&gt;

Sebuah elemen  input radio tetapi pilihan kedua yang disebut “daftar” dan dapat dipilih apabila ingin mendaftar

•	&lt;label for="login" class="slide login">Login</label&gt;

Sebuah elemen label yang berkaitan dengan input login yang berfungsi untuk memasukkan kata sandi saat melakuka login

•	&lt;label for="signup" class="slide signup">Daftar</label&gt;

Sebuah elemen label yang berkaitan dengan input sign up yang berfungsi untuk membuat akun baru atau melakukan pendaftaran apabila belum memiliki akun

•	&lt;div class="slider-tab"></div&gt;

Sebuah elemen div yang disebut slider tab dan digunakan untuk mwngontrol atau menunujukkan bagian tab atau geser pada halaman web, namun elemen ini kosong yang berarti tidak ada kontennya

•	&lt;div class="form-inner"&gt;

Berfungsi sebagai tempat di mana seluruh formular login disimpan di dalamnya

•	&lt;form action="#" class="login"&gt;

Sebuah elemen formular dengan tanda pagar di dalamnya dan memiiki label login yang digunakan untuk mengumpulkan informasi login dari pengguna, seperti email dan kata sandi

•	&lt;div class="field"&gt;

Sebuah elemen div dengan atribut field yang digunakan untuk mengelompokkan elemen dalam formular, seperti email dan kata sandi.

•	&lt;input type="text" placeholder="Masukkan Email Anda" required&gt;

Sebuah elemen input teks yang bisa digunakan untuk menuliskan email yang wajib diisi sebelum mengirimkan formulir

•	&lt;input type="password" placeholder="Masukkan Kata Sandi Anda" required&gt;

Sebuah elemen input tipe sandi yang bisa digunakan untuk mengisi kata sandi yang wajib diisi sebelum mengirimkan formulir

•	&lt;div class="pass-link"><a href="#">Lupa password?</a></div&gt;

Sebuah elemen div yang berkaitan dengan “lupa password” dan digunakan apabila seseorang lupa kata sandi dan ingin meresetnya

•	&lt;div class="field btn"&gt;

Berfungsi untuk mengelompokkan tombol dalam formulir

•	&lt;div class="btn-layer"></div&gt;

Merupakan elemen kosong yang berfungsi untuk membuat efek visual/layer sehingga tombol terlibat lebih manarik

•	&lt;input type="submit" value="Login"&gt;

Sebuah elemen input yang digunakan untuk mengirimkan formulir. Dengan memiliki atribut type yang diatur menjadi submit, sehingga dapat mengirimkan data formuir dan kata “Login” sebagai label yang dapat dilihat oleh pengguna

•	&lt;div class="signup-link">Buat akun <a href="">Daftar sekarang</a></div&gt;

Sebuah elemen div yang berkaitan dengan “signup-link” dan digunakan sebagai opsi kepada pengguna yangbelum punya akun untuk mendaftar

e.	&lt;form&gt;

Sebuah elemen awal formulir yang digunakan untuk mengumpulkan data dari pengguna. Dengan ketentuan:

•	&lt;form action="#" class="signup"&gt;

Berisikan atribut action yang menandakan URL atau alamat tujuan yang akan menerima informasi pengguna masukkan dalam formulir setelah klik tombol kirim. Tanda pagar disini mengartikan bahwa informasi yang telah dikirim  akan diproses di halaman yang sama.  Class signup berfungsi meberikan gaya tertentu pada formulir melalui CSS

•	&lt;div class="field"&gt;

Berfungsi untuk mengumpulkan elemen input ke dalam field sehingga tampilan formulir terlihat lebih rapi dan teratur

•	&lt;input type="text" placeholder="Masukan Nama" required&gt;

Sebuah elemen dengan tipe teks yang berarti pengguna wajib memasukkan teks. Dengan menggunakan atribut “placeholder” akan memunculkan pesan yang muncul di kotak sebelum pengguna memasukkan informasi. Dan menggunakan atribut “required” yang berarti wajib diisi sebelum mengirimkan formulir

•	&lt;div class="field btn"&gt;

Berfungsi untuk mengumpulkan tombol pendaftaran ke dalam field terpisah, sehingga dapat diubah tampilannya melalui CSS

•	&lt;input type="submit" value="Daftar"&gt;

Sebuah tombol daftar yang berfungsi untuk mengirimkan informasi yang telah diiisi pengguna ke tempat yang sudah ditentukan pada atribut action

•	&lt;div class="signup-link">Sudah punya akun? &lt;a href=""&gt;Login&lt;/a&gt; &lt;/div&gt;

Sebuah tautan yang berfungsi membantu pengguna menuju halaman link. Dengan memiliki class “signuplink” maka tampilannya dapat diatur menggunakan CSS

f.	&lt;/form&gt;
Sebuah penutup dari elemen formulir sebelumnya

g.	   &lt;/div&gt;

  &lt;/div&gt;
  
&lt;/div&gt;

Sebuah penutup tiga elemen &ltdivgt;
 yang setiap penutupnya mengakhiri satu tingkat wadah.

 h.	 &lt;script src="./script.js"&gt;&lt;/script&gt;
 
Sebuah bagian JavaScript yang berfungsi mengaitkan kemudian dapat menjalankan file script eksternal yang disebut “script.js” ke halaman web. 

i.	&lt;/body&gt;

Sebuah elemen penutup bagian tubuh dokumen html dan mnutup bagian yang berisikan konten

j. 	&lt;/html&gt;

Sebuah elemen penutup untuk seluruh dokumen html dan halaman web


Penjelasan CSS Login dan Signup

1.	Mengimpor huruf poppins

@import url('https://fonts.googleapis.com/css?family=Poppins:400,500,600,700&display=swap');

Sebuah perintah untuk mengimpor huruf Poppins dari google fonts ke dalam situs web. Dengan ketentuan: 

•	Berisikan alamat web yang menuju ke file CSS yang  berisi informasi tentang jenis huruf poppins dengan berbagai ketebalan

•	Menggunakan display=swap yang berarti apabila jenis huruf belum ada di perangkat pengguna, maka perubahan jenis hurufnya akan terjadi tanpa gangguan yang mencolok

2.	/* Aturan CSS untuk semua elemen */
   
*{
  margin: 0;
  
  padding: 0;
  
  box-sizing: border-box;
  
  font-family: 'Poppins', sans-serif;
  
}

Sebuah aturan CSS yang mempengaruhi aturan semua elemen di halaman. Dengan ketentuan:

•	Margin 0 yang berarti menghilangkan ruang kosong di sekitar elemen luar

•	Padding 0 yang berarti konten di dalam html akan berbatasan langsung dengan tepi elemen dalam

•	Mengatur kotak elemen sehingga dapat mencakup padding dan batas

•	Menggunaka jenis huruf poppins dan sans-serf

3.	 /* Aturan CSS untuk elemen html dan body */
   
html, body{

  display: grid;
  
  height: 100%;
  
  width: 100%;
  
  place-items: center;
  
  background-image: linear-gradient(62deg, #ffe396 0%, #ffb347 100%);
  
}

Sebuah aturan CSS yang mengatur tampilan elemen <body> seperti warna, posisi, ukuran. Dengan ketentuan:

•	Mengatur tata letak grid seperti sebuah tabel

•	Menggunakan tinggi dan lebar 100% yang mengisi seluruh halaman web

•	Mengatur konten agar selalu tepat di tengah halaman

•	Menggunakan backgroundlinear dengan warna gradient yaitu oranye tua dan oranye muda

4.	/* Aturan CSS untuk teks yang dipilih oleh pengguna */
   
::selection{

  background: #1a75ff;
  
  color: #fff;
  
}

Sebuah pseudo elemen CSS yang dapat memilih teks ketika menggeser kursor di atas teks halaman web. Dengan ketentuan:

•	Background teks yang dipilih berwarna biru tua

•	Teks yang dipilih berubah menjadi warna putih

5.	/* Aturan CSS untuk elemen dengan kelas "wrapper" */
   
.wrapper{

  overflow: hidden;
  
  max-width: 390px;
  
  background: #fff;
  
  padding: 30px;
  
  border-radius: 15px;
  
  box-shadow: rgb(38, 57, 77) 0px 20px 30px -10px;
  
}

Sebuah selector CSS yang menentukan gaya yang akan diterapkan pada elemen-elemen yang memiliki class wrapper.  Dengan aturan:

•	Apabila konten melebihi batas maka akan disembunyikan

•	Lebar maksimal elemen 390 piksel

•	Background berwarna putih

•	Padding sekitar konten sebesar 30 piksel

•	Sudut elemen menjadi melengkung dengan radius 15 piksel

•	Menentukan warna bayangan dengan warna (merah, hijau, biru)

•	Jarak bayangan horizontal 0 piksel

•	Jarak bayangan vertical 20 piksel

•	Penyebaran bayangan 30 piksel

•	Penurunan bayangan -10 piksel

6.	/* Aturan CSS untuk elemen dengan kelas "title-text" dalam "wrapper" */
   
.wrapper .title-text{

  display: flex;
  
  width: 200%;
  
}

Sebuah selector CSS yang mengatur tampilan elemen clss tittle-text dan berada pada class wrapper. Dengan ketentuan:

•	Mengendalikan penataan dan mengatur posisinya lebih flexible

•	Lebar elemen menjadi 2x lipat lebih lebar dari biasanya

7.	/* Aturan CSS untuk elemen dengan kelas "title" dalam "wrapper" */
   
.wrapper .title{

  width: 50%;
  
  font-size: 35px;
  
  font-weight: 600;
  
  text-align: center;
  
  transition: all 0.6s cubic-bezier(0.68,-0.55,0.265,1.55);

}

Sebuah selector CSS yang mengatur elemen class title dalam wrapper. Dengan ketentuan:

•	Lebar elemenmenjadi setengah dari lebar elemen wrapoer yang ada di sekitarnya

•	Ukuran teks 35 piksel

•	Ketebalan teks 600 

•	Teks dalam title akan berada di tengah elemen

•	Mengatur animasi bergerak selama 0,6 detik

8.	/* Aturan CSS untuk elemen dengan kelas "slide-controls" dalam "wrapper" */
   
.wrapper .slide-controls{

  position: relative;
  
  display: flex;
  
  height: 50px;
  
  width: 100%;
  
  overflow: hidden;
  
  margin: 30px 0 10px 0;
  
  justify-content: space-between;
  
  border: 1px solid lightgrey;
  
  border-radius: 15px;
  
}

Sebuah selector CSS yang mengatur tampilan elemen HTML class slide-controls dan berada pada class wrapper. Dengan ketentuan:

•	Elemen berada di posisi yang asli

•	Tata letak elemen dapat diatur secara fleksibel

•	Tinggi elemen 50 piksel

•	Lebar elemen hingga mencakup seluruh elemen “wrapper”

•	Menyembunyikan ekonten apabila melebihi batas

•	Margin dengan jarak atas 30 piksel, jarak bawah 10 piksel, tanpa jarak kanan kiri

•	Garis batas ketebalan 1 piksel dan warna abu abu muda

•	Sudut bulat elemen ukuran jari-jari 15 piksel

9.	/* Aturan CSS untuk elemen dengan kelas "slide" dalam "slide-controls" */
    
.slide-controls .slide{

  height: 100%;
  
  width: 100%;
  
  color: #fff;
  
  font-size: 18px;
  
  font-weight: 500;
  
  text-align: center;
  
  line-height: 48px;
  
  cursor: pointer;
  
  z-index: 1;
  
  transition: all 0.6s ease;
  
}

Sebuah selector CSS yang mengatur tampilan elemen HTML class slide dan berada pada class slide controls. Dengan ketentuan:

•	Tinggi elemen menjadi 100% dari class slide controls

•	Lebar elemen menjadi 100% dari class slide controls

•	Ukuran fonts 18 piksel

•	Ketebalan fonts ukuran 500

•	Teks berpusat pada elemen

•	Jarak antara garis teks (tinggi baris) 48 piksel

•	Indeks z elemen menjadi 1 dan memengaruhi tumpukan tampilan elemen apabila ada elemen yang tumpeng tindih

•	Transisi perubahan warna, lebar, tinggi posisi elemen dengan durasi 0,6 detik

10.	/* Aturan CSS untuk elemen label dengan kelas "signup" dalam "slide-controls" */
.slide-controls label.signup{

  color: #000;
  
}

Sebuah selector CSS mengatur tampilan elemen label dengan kelas signup dan terletal di class slide-controls. Dengan ketentuan:

•	Teks menggunakan warna hitam

11.	/* Aturan CSS untuk elemen dengan kelas "slider-tab" dalam "slide-controls" */
.slide-controls .slider-tab{

  position: absolute;
  
  height: 100%;
  
  width: 50%;
  
  left: 0;
  
  z-index: 0;
  
  border-radius: 15px;
  
  background: -webkit-linear-gradient(left,#f6e3b4,#eccd89,#f6b375, #f07706);
  
  transition: all 0.6s cubic-bezier(0.68,-0.55,0.265,1.55);
  
}

Sebuah selector CSS yang mengatur tampilan elemen class slider-tab dan berada pada class slide controls. Dengan ketentuan:

•	Elemen berada di tempat relatif

•	Tinggi elemenn 100% dan mengisi seluruh ketinggian yang berisi slider-tab 

•	Lebar elemen setengah dari elemen yang berisi slider tab

•	Elemen berada dari sisi kiri elemen yang memiliki class slide controls

•	Elemen berada  di bawah eleen lain yang memiliki indeks z lebih tinggi

•	Sudut lengkung elemen 15 piksel

•	Background linear dan berwarna gradien oranye

•	Perubahan animasi pada elemen terjadi 0,6 detik yang dimulai lambat berakhir cepat

12.	/* Aturan CSS untuk input radio yang tersembunyi */
    
input[type="radio"]{

  display: none;
  
}

Sebuah selector CSS yang mengatur tampilan elemen input radio yang memiliki atribut type dengan nilai radio. Dengan ketentuan:

•	Menyembunyikan input radio dan tidak akan terlihat oleh pengguna, tetapi digunakan pada pengolahan atau logika JavaScript

13.	/* Aturan CSS tampilan elemen dengan class .slider-tab saat pilihan "signup" dicentang */
    
#signup:checked ~ .slider-tab {

  left: 50%;
  
}

Memberikan efek visual yang mengindikasikan pilihan yang dipilih. Dengan ketentuan:

•	Elemen akan bergeser ke kiri sejauh 50% ketika pilihan signup dicentang

14.	/* Aturan CSS tampilan label dengan class .signup saat pilihan "signup" dicentang */
    
#signup:checked ~ label.signup {

  color: #fff; 
  
  cursor: default; 
  
  user-select: none; 
  
}

Mengubah tampilan label class signup ketika dicentang. Dengan ketentuan:

•	Warna teks putih

•	Kursor mouse menjadi kursor default

•	Mencegah pemilihan teks oleh pengguna

15.	/* Aturan CSS tampilan label dengan class .login saat pilihan "signup" dicentang */
#signup:checked ~ label.login {

  color: #000; 
  
Sebuah selector CSS yang merubah tampilan label class login ketika pilihan signup dicentang. Dengan ketentuan:

•	Warna teks hitam

16.	/* Aturan tampilan label dengan class .signup saat pilihan "login" dicentang */

#login:checked ~ label.signup {

  color: #000; 
  
}

Sebuah selector CSS yang merubah tampilan label signup ketika pengguna memilih opsi login. Dengan ketentuan:

•	Warna teks hitam

17.	/* Aturan CSS tampilan label dengan class .login saat pilihan "login" dicentang */
    
#login:checked ~ label.login {

  cursor: default;
  
  user-select: none; 
  
}

Sebuah selector CSS yang mengubah tampilan label class login ketika pengguna memilih opsi login. Dengan ketentuan:

•	Kursor mouse menjadi kursor default

•	Mencegah pemilihan teks oleh pengguna

18.	/* Aturan CSS untuk elemen dengan class “.form-container” dalam “wrapper” */
    
.wrapper .form-container {

  width: 100%; 
  
  overflow: hidden; 
  
}

Sebuah selector CSS yang mengatur tampilan elemen class .form-container dan berada pada class wrapper. Dengan ketentuan:

•	Lebar menjadi 100%

•	Konten yang melebihi lebar akan disembunyikan

19.	/* Aturan CSS untuk elemen dengan class .form-inner dalam .form-container */
    
.form-container .form-inner {

  display: flex; 
  
  width: 200%; 
  
}

Sebuah selector CSS yang mengatur tampilam elemen dengan class form-inner dan berada pada class .form-container. Dengan ketentuan:

•	Isi diatur dengan tata letak yang fleksibel

•	Lebar diatur dua kali lebih lebar dari aslinya

20.	/* Aturan CSS untuk elemen form dalam .form-inner */
    
.form-container .form-inner form {

  width: 50%; 
  
  transition: all 0.6s cubic-bezier(0.68,-0.55,0.265,1.55); 
  
}

Sebuah selector CSS yang mengatur tampilan elemen yang berada pada class form-inner. Dengan ketentuan:

•	Lebar form menjadi  50% dari .form-inner

•	Efek transisi 0,6 detik dengan kurva waktu cubic-bezier

21.	/* Aturan CSS untuk elemen .field dalam form */
    
.form-inner form .field {

  height: 50px; 
  
  width: 100%; 
  
  margin-top: 20px; 
  
}

Sebuah selector CSS yang mengatur tampilan elemen dengan class field dalam form. Dengan ketentuan:

•	Tinggi 50 piksel
•	Lebar 100% mengisi seluruh halaman web
•	Margin jarak atas 20 piksel

22.	/* Aturan CSS untuk elemen input dalam .field dalam form */
    
.form-inner form .field input {

  height: 100%; 
  
  width: 100%; 
  
  outline: none; 
  
  padding-left: 15px;
  
  border-radius: 15px; 
  
  border: 1px solid lightgrey; 
  
  border-bottom-width: 2px; 
  
  font-size: 17px; 
  
  transition: all 0.3s ease; 
  
}

Sebuah selector CSS yang mengatur tampilan elemen input dengan class field dalam form. Dengan ketentuan:

•	Tinggi elemen  menjadi 100% dari class form

•	Lebar elemen menjadi 100% dari class form

•	Garis tepi dihilangkan 

•	Memberikan ruang tambahan sepanjang 15 piksel di sisi kiri elemen

•	Sudut bulat 15 piksel

•	Ketebalan garis tepi 1 piksel dan berwarna abu-abu muda

•	Ketebalan garis tepi bagian bawah 2 piksel

•	Ukuran font 17 piksel

•	Efek transisi berdurasi 0,3 detik

23.	/* Aturan CSS untuk input dalam fokus */
    
.form-inner form .field input:focus {

  border-color: #1a75ff; 
  
}

Sebuah selector CSS yang mengatur tampilan input dalam focus ketika diklik ataupun dipilih. Dengan ketentuan:

•	Warna tepi input berubah menjadi biru saat input dalam fokus

24.	/* Aturan CSS untuk teks placeholder dalam input */
    
.form-inner form .field input::placeholder {

  color: #999; /* Mengatur warna teks placeholder menjadi abu-abu (#999) */
  
  transition: all 0.3s ease; /* Efek transisi selama 0.3 detik */
  
}

Sebuah selector CSS yang mengatur tampilan teks petunjuk pada input. Dengan ketentuan:

•	Warna teks petunjuk abu abu

•	Efek transisi berdurasi 0,3 detik

25.	/* Aturan CSS teks placeholder input saat dalam fokus */
    
form .field input:focus::placeholder {

  color: #1a75ff; 
  
}

Sebuah selector CSS yang mengatur tampilan teks petunjuk saat input pada mode fokus. Dengan ketentuan:

•	Warna teks biru saat input mode fokus

26.	/* Aturan CSS elemen class .pass-link */
    
.form-inner form .pass-link {

  margin-top: 5px; 
  
}

Sebuah selector CSS yang mengatur tampilan elemen dengan class .pass-link. Dengan ketentuan:

•	Margin atas berjarak 5 piksel

27.	/* Aturan CSS untuk elemen dengan class .signup-link */
    
.form-inner form .signup-link {

  text-align: center; 
  
  margin-top: 30px; 
  
}

Sebuah selector CSS yang mengatur tampilan elemen dengan class .signup-link. Dengan ketentuan:

•	Teks berada di pusat tengah horizontal

•	Margin atas berjarak 30 piksel

28.	/* Aturan CSS untuk tautan dalam elemen dengan class .pass-link dan .signup-link */
    
.form-inner form .pass-link a,

.form-inner form .signup-link a {

  color: #1a75ff; 
  
  text-decoration: none; 
  
}

Sebuah selector CSS yang mengatur tampilan tautan pada elemen class .pass-link dan signup-link. Dengan ketentuan:

•	Warna tautan menjadi biru

•	Dekorasi tautan seperti garis bawah akan dihapus

29.	/* Aturan CSS untuk tautan saat  (hover) dalam elemen dengan class .pass-link dan .signup-link */
    
.form-inner form .pass-link a:hover,

.form-inner form .signup-link a:hover {

  text-decoration: underline; 
  
}

Sebuah selector CSS yang mengatur tautan saat ditahan atau hover pada elemen class. Dengan ketentuan:

•	Garis bawah muncul ketika tautan dipilih atau hover

30.	/* Aturan CSS untuk elemen dengan class .btn */
    
form .btn {

  height: 50px; 
  
  width: 100%; 
  
  border-radius: 15px; 
  
  position: relative; 
  
  overflow: hidden; 
  
}

Sebuah selector CSS yang mengatur tampilan elemen pada class.btn. Dengan ketentuan:

•	Tinggi elemen 50 piksel

•	Lebar 100%

•	Sudut bulat sebesar 15 piksel

•	Posisi elemen akan relative mengikuti aliran dokumen html

•	Konten yang melebihi elemen akan disembunyikan

31.	/* Aturan CSS untuk lapisan (layer) tombol */
    
form .btn .btn-layer {

  height: 100%; 
  
  width: 300%; 
  
  position: absolute; 
  
  left: -100%; 
  
  background: -webkit-linear-gradient(right, #f6e3b4, #eccd89, #f6b375, #f07706); 
  
  border-radius: 15px; 
  
  transition: all 0.4s ease; 
  
}

32.	/* Aturan CSS untuk tombol input submit */
    
form .btn:hover .btn-layer {

  left: 0; 
  
}

Sebuah selector CSS yang mengatur tampilan lapisan tombol saat dihover. Dengan ketentuan:

•	Lapisan bergeser ke posisi awal yaitu ke kiri saat tombol dihover

33.	/* Aturan CSS untuk tombol input submit */
    
form .btn input[type="submit"] {

  height: 100%; 
  
  width: 100%; 
  
  z-index: 1; 
  
  position: relative; 
  
  background: none; 
  
  border: none; 
  
  color: #fff; 
  
  padding-left: 0; 
  
  border-radius: 15px; 
  
  font-size: 20px; 
  
  font-weight: 500; 
  
  cursor: pointer; 

}

Sebuah selector CSS yang mengatur tampilan tombol input submit. Dengan ketentuan:

•	Tinggi elemen mengisi keseluruhan hingga 100%

•	Lebar elemen mengisis keseluruhan hingga 100%

•	Z-index 1 yang berarti berada di atas elemen dengan z-index 0 tetapi di bawah elemen dengan index yang lebih tinggi dari 1.

•	Posisi elemen akan relative mengikuti aliran dokumen html

•	Latar belakang dihapus

•	Garis tepi dihapus

•	Teks berwarna putih

•	Padding jarak kiri menjadi 0

•	Sudut bulat sebesar 15 piksel

•	Ukuran font sebesar 20 piksel

•	Ketebalan font 500

•	Kursor diubah menjadi tanda panah ketika diarahkan

Penjelasan JS Login dan Signup

a.	Pemilihan Elemen HTML

•	const loginText = document.querySelector(".title-text .login");

Mencari elemen yang  memiliki class CSS tittle-text dan login kemudian menyimpannya  pada variabel logintext

•	const loginForm = document.querySelector("form.login");

Mencari elemen &lt;form&gt; dengan class CSS login kemudian menyimpannya pada variabel loginForm

•	const loginBtn = document.querySelector("label.login");

Mencari elemen &lt;label&gt; dengan class CSS login kemudian menyimpannya pada variabel loginBtn

•	const signupBtn = document.querySelector("label.signup");

Mencari elemen &lt;label&gt; dengan class CSS signup kemudian menyimpannya pada variabel signupBtn

•	const signupLink = document.querySelector("form .signup-link a");

Mencari elemen &lt;a&gt; yang berada dalam elemen dengan class CSS signup-link pada elemen &lt;form&gt; kemudian menyimpannya pada variabel signupLink

b.	Fungsi untuk tombol signup

signupBtn.onclick = (() =&gt; {

  loginForm.style.marginLeft = "-50%";
  
  loginText.style.marginLeft = "-50%";
  
});

Pada bagian ini menjelaskan apa yang akan terjadi ketika mengklik tombol daftar. Dengan ketentuan:

•	Merubah jarak kiri (marginleft) dari elemen-elemen loginForm dan loginText menjadi -50%

•	Elemen akan bergeser ke kiri dan menghasilkan efek transisi dengan menggesernya ke luar tampilan

c.	Fungsi untuk tombol login

loginBtn.onclick = (() =&gt; {

  loginForm.style.marginLeft = "0%";
  
  loginText.style.marginLeft = "0%";
  
});

Pada bagian ini menjelaskan apa yang akan terjadi ketika mengklik tombol login. Dengan ketentuan:

•	Merubah margin kiri dari elemen-elemen loginForm dan loginText menjadi 0%

•	Elemen akan kembali ke posisi awal.

d.	Fungsi untuk tautan signup

signupLink.onclick = (() =&gt; {

  signupBtn.click();
  
  return false;
  
});

Pada bagian ini menjelaskan apa yang akan terjadi ketika mengklik tautan signup. Dengan ketentuan:

•	Melakukan Tindakan klik pada tautan signup degan perintah click()

•	Menghentikan aksi saat mengklik tautan dengan mengembalikan nilai false untuk mencegah pengguna dialihkan ke tautan halaman lain.



<h2>CONTACT</h2>

<h3>PENJELASAN HTML CONTACT</h3>

<div align="justify">

1. &lt;!DOCTYPE html: Ini adalah deklarasi dokumen HTML yang mengindikasikan versi dokumen.&gt;

2. &lt;html: Ini adalah elemen root (utama) dari halaman web.&gt;

3. &lt;head: Bagian ini berisi informasi tentang halaman, seperti judul, tautan CSS, dan pengaturan responsif.&gt;

4. &lt;meta name="viewport" content="width=device-width, initial-scale=1.0": Meta tag ini digunakan untuk mengatur tampilan halaman agar responsif terhadap ukuran perangkat.&gt;

5. &lt;title&gt;Contact Page&lt;/title&gt;: Ini adalah judul halaman yang akan ditampilkan di tab peramban.

6. &lt;link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css"&gt;: Ini adalah tautan ke file CSS Font Awesome, yang mengandung ikon-ikon yang akan digunakan di halaman.

7. &lt;link rel="stylesheet" type="text/css" href="contact.css"&gt;: Ini adalah tautan ke file eksternal CSS (style.css) yang akan mengatur tampilan halaman.

8. &lt;body&gt;: Ini adalah elemen yang berisi konten halaman yang akan ditampilkan kepada pengguna.

9. &lt;section class="contact"&gt;: Ini adalah bagian utama halaman yang memiliki kelas "contact" untuk memudahkan pengaturan tampilan.

10. &lt;div class="content"&gt;: Ini adalah sebuah div (kontainer) yang berisi judul dan deskripsi halaman.

11. &lt;h2&gt;Contact Us&lt;/h2&gt;: Ini adalah judul halaman "Contact Us."

12. &lt;p&gt;Kami siap membantu masalah Anda.&lt;/p&gt;: Ini adalah deskripsi atau teks informasi yang menjelaskan tujuan halaman.

13. &lt;div class="container"&gt;: Ini adalah div yang berfungsi sebagai kontainer untuk mengelompokkan elemen-elemen kontak.

14. &lt;div class="contactInfo"&gt;: Ini adalah div yang berisi informasi kontak.

15. &lt;div class="box"&gt;: Ini adalah kotak kontak yang berisi ikon dan teks.

16. &lt;div class="icon"&gt;: Ini adalah div untuk ikon kontak.

17. &lt;i class="fas fa-map-marker" aria-hidden="true"&gt;&lt;/i&gt;: Ini adalah ikon alamat menggunakan Font Awesome.

18. &lt;div class="text"&gt;: Ini adalah div yang berisi teks informasi kontak.

19. &lt;h3&gt;Address&gt;/h3&gt;: Ini adalah judul untuk alamat.

20. &lt;p&gt;Jl. Ketintang, Ketintang, &lt;br&gt;Kec. Gayungan, Kota Surabaya, &lt;br&gt;Jawa Timur (60230)&lt;/br&gt;&lt;/p&gt;: Ini adalah alamat fisik dengan garis baru (line break) untuk pemformatan yang baik.

21. Selanjutnya, terdapat informasi kontak lainnya seperti email dan nomor telepon yang disusun dengan cara yang serupa.

22. &lt;div class="contactForm"&gt;: Ini adalah div yang berisi formulir kontak.

23. &lt;form&gt;: Ini adalah elemen form yang digunakan untuk mengelola masukan pengguna.

24. &lt;h2&gt;Send Message&lt;/h2&gt;: Ini adalah judul formulir "Send Message."

25. Terdapat beberapa &lt;div class="inputBox"&gt; yang berisi kotak masukan untuk nama lengkap, alamat email, pesan, dan tombol "Send."

26. required="required": Ini adalah atribut yang menandakan bahwa masukan tersebut wajib diisi sebelum mengirim pesan.
</div>


<h3>PENJELASAN CSS CONTACT</h3>

1. @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700;800;900&display=swap');: Ini adalah aturan untuk mengimpor font dari Google Fonts. Font yang diimpor adalah "Poppins" dengan berbagai varian beratnya.

2. *: Ini adalah selektor universal yang memengaruhi semua elemen dalam dokumen HTML. Ini digunakan untuk mengatur beberapa properti dasar untuk semua elemen.

3. margin: 0; padding: 0; box-sizing: border-box;: Ini adalah aturan untuk mengatur margin, padding, dan model kotak (box-sizing) untuk semua elemen. Dalam hal ini, margin dan padding diatur menjadi 0, dan model kotak diatur sebagai "border-box," yang berarti ukuran elemen mencakup padding dan border.

4. font-family: 'Poppins', sans-serif;: Ini mengatur jenis font default untuk dokumen. Font "Poppins" digunakan sebagai font utama, dan "sans-serif" digunakan sebagai alternatif jika "Poppins" tidak tersedia.

5. .contact: Ini adalah selector untuk elemen dengan kelas "contact." Ini mengatur tampilan wadah utama "contact."

6. min-height: 100vh;: Ini mengatur ketinggian minimum elemen dengan kelas "contact" menjadi setidaknya 100% dari tinggi viewport.

7. display: flex; flex-direction: column; justify-content: center; align-items: center;: Ini mengatur elemen dengan kelas "contact" sebagai flex container dengan tata letak kolom. Kontennya akan berada di tengah-tengah vertikal dan horizontal.

8. background-color: #fff;: Ini mengatur latar belakang elemen dengan kelas "contact" menjadi putih.

9. .content: Ini adalah selector untuk elemen dengan kelas "content." Ini mengatur tampilan konten dalam wadah "contact."

10. max-width: 800px;: Ini mengatur lebar maksimum konten agar tidak melebihi 800 piksel.

11. .contact h2: Ini mengatur tampilan judul "Contact Us" dalam elemen dengan kelas "contact."

12 .contact p: Ini mengatur tampilan teks deskripsi dalam elemen dengan kelas "contact."
