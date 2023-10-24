# Swiftshop
<div align="center">
<h2>Software Requirements Specification for</h2>
<h1>Swiftshop Website E-commerce</h1>

<h3>Versi 1.0 Disetujui</h3>


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

<h3>1.	Pendahuluan</h3>

1.1	Tujuan Penulisan Dokumen

1.2	Konvensi Dokumen

1.3	Audien yang Dituju dan Pembaca yang Disarankan

1.4	Ruang Lingkup Produk

1.5	Batasan Desain dan Implementasi

1.6	Referensi

<h3>2.	Deskripsi Keseluruhan</h3>

2.1	Deskripsi Produk

2.2	Fungsi Produk

2.3	Penggolongan Karakteristik Pengguna

2.4	Lingkungan Operasi

2.5	Dokumentasi Pengguna

<h3>3.	Kebutuhan Antarmuka Eksternal</h3>

3.1	User Interfaces

3.2	Hardware Interfaces

3.3	Software Interfaces

3.4	Communications Interfaces

<h3>4.	Persyatatan Fungsional</h3>

4.1	Katalog Produk

4.2	Manajemen Akun

4.3	Keranjang Belanja

4.4	Manajemen Pesanan

4.5	Pencarian dan Filter Produk

4.6	Integrasi Pembayaran dan Pengiriman

4.7	Manajemen Akun Pengguna

4.8	Peran Pengguna

<h3>5.	Persyaratan Non Fungsional</h3>

5.1	Persyaratan Kinerja

5.2	Persyaratan Keamanan

5.3	Atribut Kualitas Perangkat Lunak

5.4	Peraturan Bisnis

<h3>6.	Persyaratan Lainnya</h3>
   
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


<h4>3.4.2	Urutan Stimulus/Respon</h4>

Stimulus: Pengguna mengakses halaman manajemen pesanan.

Respon: Tampilan daftar pesanan dan status pengiriman.
 
<h4>3.4.3	Persyaratan Fungsional</h4>

1.	Pengguna harus dapat membuat akun dengan mengisi informasi pribadi seperti nama, alamat email, dan kata sandi.
2.	Sistem harus mengirimkan email verifikasi ke pengguna untuk mengaktifkan akun mereka.
3.	Pengguna yang sudah terdaftar harus dapat masuk ke akun mereka dengan otentikasi yang aman.

<h3>3.5	Pencarian dan Filter Produk</h3>

<h4>3.5.1	Deskripsi dan Prioritas</h4>

Deskripsi: Sistem memiliki kemampuan untuk mencari dan memfilter produk.
 
Prioritas: Sedang.
 
<h4>3.5.2	Urutan Stimulus/Respon</h4>

Stimulus: Pengguna melakukan pencarian produk.
 
Respon: Hasil pencarian dengan produk yang sesuai.

<h4>3.5.3	Persyaratan Fungsional</h4>
 
1.	Pengguna harus dapat membuat akun dengan mengisi informasi pribadi seperti nama, alamat email, dan kata sandi.
2.	Sistem harus mengirimkan email verifikasi ke pengguna untuk mengaktifkan akun mereka.
3.	Pengguna yang sudah terdaftar harus dapat masuk ke akun mereka dengan otentikasi yang aman.
   
<h3>3.6	Integrasi Pembayaran dan Pengiriman</h3>

<h4>3.6.1	Deskripsi dan Prioritas</h4>
 
Deskripsi: Integrasi dengan gateway pembayaran eksternal dan penyedia pengiriman akan tersedia.
 
Prioritas: Tinggi

<h5>Urutan Stimulus/Respon</h5>
 
	Stimulus: Pengguna memilih opsi pembayaran.
 
	Respon: Pilihan pembayaran dan pengisian detail pembayaran.
 
	Stimulus: Pengguna memilih opsi pengiriman.
 
	Respon: Pilihan pengiriman dan estimasi biaya.
 
<h4>3.6.3	Persyaratan Fungsional</h4>

1.	Pengguna harus dapat membuat akun dengan mengisi informasi pribadi seperti nama, alamat email, dan kata sandi.
2.	Sistem harus mengirimkan email verifikasi ke pengguna untuk mengaktifkan akun mereka.
3.	Pengguna yang sudah terdaftar harus dapat masuk ke akun mereka dengan otentikasi yang aman.

   
<h3>3.7	Manajemen Akun Pengguna</h3>

<h4>3.7.1	Deskripsi dan Prioritas</h4>

Deskripsi: Akun pengguna akan memiliki profil dan otentikasi.
 
Prioritas: Sedang.
 
<h4>3.7.2	Urutan Stimulus/Respon</h4>

Stimulus: Pengguna mengakses halaman produk.
 
Respon: Tampilan daftar produk dengan informasi terperinci.
 
<h4>3.7.3	Persyaratan Fungsional</h4>

1.	Pengguna harus dapat membuat akun dengan mengisi informasi pribadi seperti nama, alamat email, dan kata sandi.
2.	Sistem harus mengirimkan email verifikasi ke pengguna untuk mengaktifkan akun mereka.
3.	Pengguna yang sudah terdaftar harus dapat masuk ke akun mereka dengan otentikasi yang aman.
   
<h3>3.8	Peran Pengguna</h3>

<h4>3.8.1	Deskripsi dan Prioritas</h4>

	Deskripsi: Ada peran pengguna seperti admin, pelanggan, dan penjual.
 
	Prioritas: Sedang.
 
<h4>3.8.2	Urutan Stimulus/Respon</h4>

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
   
<h4>1.	Persyaratan Basis Data</h4>
   
Mencakup persyaratan yang berkaitan dengan cara data disimpan, diakses dan dikelola pada sistem Swift Shop Website, yaitu:

-	Struktur Basis Data: Mencakup pengelolaan data produk, pelanggan, stok, harga dan transaksi disimpan di dalamnya.
-	Keamanan Basis Data: Mencakup pengelolaan perlindungan informasi pelanggan dan transaksi.
-	Integritas Basis Data: Mencakup pengelolaan sistem yang berinteraksi dengan data seperti melakukan pembaruan data ketika pembelian dilakukan.
  
<h4>2.	Persyaratan Internalisasi</h4>
<div align="justify">
Dukungan bahasa pada Swift Shop Website memprioritaskan pada penggunaan bahasa Indonesia dan juga bahasa Inggris. Terdapat rencana untuk menambahkan beberapa bahasa agar dapat diakses oleh berbagai negara. Harga produk dalam Swift Shop juga dapat diubah menjadi mata uang lokal tiap pengguna dan kemungkinan dapat melakukan pengiriman ke berbagai negara dengan biaya pengiriman yang telah ditentukan.
</div>
<h4>3.	Persyaratan Resmi</h4>

Mencakup persyaratan pada Swift Shop Website yang wajib dilakukan sesuai dengan peraturan hukum yang berlaku, yaitu:

-	Kebijakan Privasi: Mencakup pengelolaan privasi yang harus dipenuhi mengenai perlindungan data pelanggan.
-	Kepatuhan Hukum: Mematuhi peraturan perdagangan bidang elektronik serta perlindungan pelanggan telah sesuai dengan yang berlaku di wilayah yang akan dijalankan.
-	Syarat dan Ketentuan: Menguraikan peraturan yang wajib diikuti oleh konsumen saat melakukan pembelian pada Swift Shop Website.

<h4>4.	Gunakan kembali Tujuan Untuk Proyek</h4>
   
-	Tujuan Pengguna: Pembuatan situs web swift shop diharapkan mampu memberikan kemudahan dalam berbelanja, produk xiaomi terbaru dan pengalaman pembeli yang nyaman.
-	Tujuan Bisnis: Dengan adanya situs web swift shop diharapkan mampu meningkatkan jangkauan pasar, menaikkan jumlah penjualan, dan branding yang lebih kuat.
-	Tujuan Teknis: Dapat melakukan perbaikan operasional, keamanan, dan skala akses sistem yang lebih luas.

Appendix A: Glossary

![Appendix glossary](https://github.com/22091397028AinulMufidh/Swiftshop/assets/124547755/c7170a11-2f28-44ec-9cfc-6c20dcaae0cf)

Appendix B: Analysis Models

<h3>1.	Data Flow Diagram (DFD)</h3>

<h5>Data Flow Diagram Level 0</h5>

![dfd level 0 revisi drawio](https://github.com/22091397028AinulMufidh/Swiftshop/assets/124547755/eca2772f-5c81-43e1-92dd-e6431518aee7)


<h5>Data Flow Diagram Level 1 Bagian 1</h5>

![dfd level 1 revisii drawio](https://github.com/22091397028AinulMufidh/Swiftshop/assets/124547755/e835545e-30d1-4d2a-a1c7-5b1c34486774)

<h5>Data Flow Diagram Level 1 Bagian 2</h5>

![dfd 2 1 revisii](https://github.com/22091397028AinulMufidh/Swiftshop/assets/124547755/5111a80b-ac7e-4d93-9334-f0786defcd05)

<h3>2.	Entity Relationship Diagram (ERD)</h3>
   
![ERD](https://github.com/22091397028AinulMufidh/Swiftshop/assets/124547755/af6f2eaf-141c-4c3d-b215-ec16059c89eb)

<h3>3.	Class Diagram</h3>
   
![Class Diagram](https://github.com/22091397028AinulMufidh/Swiftshop/assets/124547755/627e811f-0569-4df5-b377-47962c56f64e)

<h3>4.	Use Cae</h3>

![Use Case](https://github.com/22091397028AinulMufidh/Swiftshop/assets/124547755/8a702ef6-80b0-48cb-b024-3fcab2fef7d8)

<h3>5.	Flowchart</h3>

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

<h1>PENJELASAN CODINGAN:</h1>

<h2>HOME PAGE</h2>

&lt;!DOCTYPE html&gt; deklarasi dokumen HTML yang mengidentifikasi jenis dokumen sebagai HTML5, versi terbaru dari HTML.

&lt;html lang="en"&gt; elemen pembuka dokumen HTML. Di dalamnya, lang="en" mengindikasikan bahwa dokumen menggunakan bahasa Inggris.

&lt;head&gt; bagian kepala dokumen HTML, yang berisi informasi meta dan tautan ke sumber  eksternal.

&lt;meta charset="UTF-8"&gt; menetapkan karakter encoding dokumen ke UTF-8, dengan metode yang umum digunakan untuk mendukung karakter internasional.

&lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt; Elemen meta ini digunakan untuk mengatur tampilan responsif halaman web, dengan mengatur lebar viewport (layar) ke lebar perangkat (width=device-width) dan tingkat zoom awal (initial-scale) ke 1.0. Ini membantu agar halaman web dapat tampil dengan baik pada berbagai perangkat.

&lt;link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css"&gt; Ini adalah tautan ke sebuah berkas CSS eksternal yang disediakan oleh Font Awesome melalui CDN Cloudflare. Font Awesome adalah kumpulan ikon yang dapat digunakan dalam desain web.

&lt;link rel="stylesheet" href="https://unpkg.com/boxicons@latest/css/boxicons.min.css"&gt; Ini adalah tautan ke berkas CSS eksternal yang disediakan oleh Boxicons melalui unpkg CDN. Boxicons juga adalah koleksi ikon yang dapat digunakan dalam desain web.

&lt;link rel="stylesheet" href="style.css"&gt; tautan ke berkas CSS lokal yaitu "style.css." Berkas CSS ini harus ada di direktori yang sama dengan file HTML yang akan digunakan untuk mengatur tampilan dan gaya visual halaman web.

&lt;link rel="stylesheet" href="cards.css"&gt; Ini adalah tautan ke berkas CSS lokal lainnya bernama "cards.css." Sama seperti sebelumnya, berkas CSS ini juga harus ada di direktori yang sama dengan file HTML dan digunakan untuk mengatur tampilan khusus pada elemen kartu (cards) pada menu product yang menampilkan sebuah produk agar terlihat lebih rapi dan terstruktrur.

&lt;title>Home</title&gt; Elemen ini mengatur judul halaman web. Judul ini akan ditampilkan di bilah judul browser atau tab, serta digunakan ketika pengguna menyimpan halaman sebagai bookmark atau berbagi tautan di media sosial.


<h4>Header Home Page</h4>

Selanjutnya yaitu &lt;body&gt;, dalam dokumen HTML elemen body biasanya berisi elemen-elemen yang akan tampil di bagian atas halaman web, seperti header.

&lt;header&gt; Ini adalah elemen yang digunakan untuk menentukan bagian header halaman web. Header biasanya berisi logo, menu navigasi, dan elemen-elemen lain yang muncul di bagian atas halaman.

&lt;a href="" class="logo"><i class="fas-fa-untensils">swiftshop</i></a&gt;: Ini adalah elemen anchor <a> yang digunakan untuk menampilkan logo atau nama situs web Anda. Dalam kode ini, Anda menggunakan ikon Font Awesome yang memiliki kesalahan penulisan ("fas-fa-untensils" seharusnya "fas fa-utensils") dan nama "swiftshop." 

&lt;nav class="navbar"&gt; Ini adalah elemen &lt;nav&gt; yang digunakan untuk mengelompokkan elemen-elemen menu navigasi.

&lt;a class="active" href="index.html">Home</a&gt; elemen anchor yang menghubungkan ke halaman "index.html" dan disertai dengan atribut class="active", yang biasanya digunakan untuk menandai halaman saat berada di sebuah halaman web..

&lt;a class="navbar-dropdown" href="">Products</a&gt; elemen anchor untuk menu "Products.

&lt;ul class="dropdown"&gt; elemen daftar tak berurutan (unordered list) yang digunakan untuk membuat submenu.

&lt;li>&lt;a href="smartphone.html">Smartphone</a&gt;</li&gt; Ini adalah elemen daftar dengan tautan ke halaman "smartphone.html." Ini adalah salah satu opsi dalam submenu "Products." Anda dapat menambahkan lebih banyak elemen daftar untuk produk lainnya.

&lt;a href="service.html">Services</a&gt; Ini adalah elemen anchor untuk menu "Services," yang menghubungkan ke halaman "service.html."

&lt;a href="contact.html">Contacts</a&gt; Ini adalah elemen anchor untuk menu "Contacts," yang menghubungkan ke halaman "contact.html."

&lt;a href="about.html">About</a&gt; Ini adalah elemen anchor untuk menu "About," yang menghubungkan ke halaman "about.html."

&lt;div class="icons"&gt; Ini adalah elemen div yang berisi ikon-ikon yang mungkin digunakan dalam header.

&lt;i class="fas fa-bars" id="menu-bars"></i&gt; Ini adalah elemen ikon Font Awesome yang mewakili ikon menu (garis tiga). ID "menu-bars" digunakan untuk mengidentifikasi ikon yang ada di navbar.

&lt;a href="#" class="fas fa-heart"></a&gt; Ini adalah elemen anchor yang menampilkan ikon hati dari Font Awesome dan akan digunakan untuk menambahkan barang ke daftar keinginan.

&lt;a href="checkout.html" class="fas fa-shopping-cart"></a&gt; Ini adalah elemen anchor yang menampilkan ikon keranjang belanja dari Font Awesome. Tautan ini menghubungkan ke halaman "checkout.html," di mana pengguna dapat melakukan proses pembelian.


<h3>Section Home Page</h3>

Elemen ini terdapat beberpa bagian dari halaman beranda (home) dalam situs web Anda. &lt;section&gt; merupakan elemen yang menampilkan konten beranda (home) dengan elemen-elemen seperti teks promosi, judul, gambar, dan tombol pemesanan. 

&lt;section class="home" id="home"&gt; elemen section yang memiliki atribut class dengan nilai "home" untuk mengatur gaya dari bagian beranda (home). Atribut id "home" juga memberikan tanda penanda untuk pengaitan ke bagian tertentu dalam halaman web.

&lt;div class="home-slider"&gt; div yang digunakan untuk mengelompokkan elemen-elemen yang termasuk dalam slider beranda (home slider).

&lt;div class="wrapper"&gt; div yang berfungsi sebagai pembungkus untuk mengatur tata letak konten dalam slider.

&lt;div class="slide"&gt; div yang mewakili satu slide dalam slider beranda.

&lt;div class="content"&gt; div yang berisi teks promosi, judul, deskripsi, dan tombol pemesanan.

&lt;span>our special offers</span&gt; elemen span yang menampilkan teks "our special offers" (penawaran istimewa).

&lt;h3>Smartphone</h3&gt; elemen h3 yang menampilkan judul "Smartphone" (judul promo).

&lt;p>Dapatkan Segera Koleksi Gadget Terbaru dan Favorit Anda dengan Harga Mulai Dari Rp 1 Jutaan, Promo Spesial Diskon Akhir Tahun Buruan Cek Jangan Sampai Ketinggalan.</p&gt; elemen p yang berisi deskripsi sebuah konten promosi.

&lt;a href="login.html" class="btn" id="btn-order">order now</a&gt; elemen anchor &lt;a&gt; yang menghubungkan ke halaman "login.html" dan menampilkan tombol dengan teks "order now". Atribut class "btn" digunakan untuk mengatur tampilan tombol, dan atribut id "btn-order" dapat digunakan untuk tujuan JavaScript atau CSS.

&lt;div class="image"&gt; Ini adalah div yang berisi gambar yang mungkin berupa gambar promosi atau ilustrasi yang sesuai dengan promo ini.

&lt;img src="./assets/promosi-gif.gif" alt=""&gt; Ini adalah elemen gambar &lt;img&gt; yang menampilkan gambar dengan atribut src yang mengarah ke berkas "promosi-gif.gif" dalam direktori "assets." Atribut alt digunakan untuk teks alternatif yang muncul jika gambar tidak dapat ditampilkan, tetapi dalam contoh ini, itu masih kosong.


<h3>Section Promotion</h3>
&lt;section class="about" id="promotion"&gt; elemen section yang memiliki atribut class "about" untuk mengatur gaya dan tampilan dari bagian ini. Atribut id "promotion" digunakan untuk mengidentifikasi bagian ini secara unik.


&lt;h3 class="sub-heading">our gadget</h3&gt; merupakan judul sub dalam bagian promosi gadget, dengan teks "our gadget."

&lt;h1 class="heading">popular gadget</h1&gt; judul utama dalam bagian promosi, dengan teks "popular gadget."

&lt;div class="content"&gt; div yang berisi konten promosi.

&lt;h3>mega sale smartphone</h3&gt; Ini ialah subjudul yang menggambarkan promo "mega sale smartphone."

&lt;p id="deskripsi">Teknologi terkini dan inovasi terbaik hanya ada di gadget kami! ... teknologi yang luar biasa!</p&gt; Ini adalah paragraf yang memberikan deskripsi promosi dan fitur gadget yang ditawarkan. Terdapat atribut id "deskripsi," yang mungkin digunakan untuk tujuan JavaScript atau CSS tertentu.

&lt;a href="login.html" class="btn" id="btn-about">learn more</a&gt; elemen anchor yang menghubungkan ke halaman "login.html" dan menampilkan tombol dengan teks "learn more". Atribut class "btn" digunakan untuk mengatur tampilan tombol, dan atribut id "btn-about" digunakan untuk mengatur tampilan tombol secara unik..

&lt;div class="row"&gt; div yang digunakan untuk mengelompokkan elemen dalam baris horizontal.

&lt;div class="image-promotion"&gt; merupakan div yang berisi gambar promosi.

&lt;img src="./assets/content-promosi.gif" alt=""&gt; adalah elemen gambar &lt;img&gt; yang menampilkan gambar promosi dengan atribut src yang mengarah ke berkas "content-promosi.gif" dalam direktori "assets." Atribut alt digunakan untuk teks alternatif jika gambar tidak dapat ditampilkan.


<h3>Section About Promotion</h3>

&lt;section class="about" id="about"&gt; elemen section yang memiliki atribut class "about" untuk mengatur tampilan dan gaya bagian ini, dan atribut id "about" digunakan untuk identifikasi unik.

&lt;h3 class="sub-heading">about us</h3&gt; judul sub yang menyampaikan bahwa bagian ini adalah tentang informasi "about us" (tentang kami).

&lt;h1 class="heading">why choose us?</h1&gt; judul utama yang menjelaskan "why choose us?" (mengapa memilih kami?).

&lt;div class="row"&gt; div yang digunakan untuk mengelompokkan elemen dalam satu baris horizontal.

&lt;div class="image"&gt; div yang berisi gambar. Dalam kasus ini, itu menampilkan gambar smartphone.

&lt;img src="./assets/smarphone.png" alt=""&gt; elemen gambar &lt;img&gt; yang menampilkan gambar smartphone dengan atribut src yang mengarah ke berkas "smartphone.png" dalam direktori "assets." Atribut alt digunakan untuk teks alternatif jika gambar tidak dapat ditampilkan.

&lt;div class="content"&gt; div yang berisi konten berisi informasi tentang smartphone.

&lt;h3>best smartphone in the country</h3&gt; subjudul yang menjelaskan bahwa smartphone yang ditawarkan adalah yang terbaik di negara.

&lt;p>Xiaomi 12T 5G hadir dengan kinerja gahar serta kamera yang tak kalah tajam... Core).</p&gt; Ini adalah paragraf yang memberikan deskripsi tentang produk, dalam hal ini, spesifikasinya.

&lt;div class="icons-container"&gt; div yang digunakan untuk mengelompokkan ikon-ikon dan teks yang menjelaskan poin-poin penting.

&lt;div class="icons"&gt; div yang berisi satu set ikon dan teks yang menjelaskan poin penting.

&lt;i class="fas fa-shipping-fast"></i&gt; elemen ikon dari Font Awesome yang menunjukkan pengiriman cepat.

&lt;span>free delivery</span&gt; teks yang menjelaskan bahwa pengiriman gratis. Ini diikuti oleh dua div lainnya dengan ikon dan teks yang menjelaskan poin-poin seperti pembayaran mudah dan layanan 24/7.

&lt;a href="login.html" class="btn" id="btn-about">learn more</a&gt; merupakan elemen anchor yang menghubungkan ke halaman "login.html" dan menampilkan tombol dengan teks "learn more". Atribut class "btn" digunakan untuk mengatur tampilan tombol, dan atribut id "btn-about" digunakan untuk mengatur tampilan tombol secara unik.


<h3>Section Review</h3>
atribut class "review" digunakan untuk mengatur tampilan dan gaya bagian ini, dan atribut id "review" digunakan untuk identifikasi unik.

&lt;h3 class="sub-heading">customer's review</h3&gt; judul sub yang menyampaikan bahwa bagian ini adalah tentang ulasan pelanggan.

&lt;h1 class="heading">what the say</h1&gt; judul utama yang menampilkan pertanyaan "what they say".

&lt;div class="swiper-container review-slider"&gt; div yang yang digunakan untuk menampilkan konten review dari user.. 

&lt;div class="swiper-wrapper"&gt; div yang berisi elemen-elemen yang akan menjadi bagian dari slider.

&lt;div class="swiper-slide slide"&gt; div yang mewakili satu slide dalam slider.

&lt;div class="fas fa-quote-right"></div&gt; elemen ikon dari Font Awesome yang menampilkan tanda kutip (quote right).

&lt;div class="user"&gt; div yang berisi informasi tentang pengguna yang memberikan ulasan.

&lt;img src="./assets/photo1.jpg" alt=""&gt; elemen gambar &lt;img&gt; yang menampilkan foto pengguna yang memberikan ulasan. Gambar tersebut diarahkan ke berkas "photo1.jpg" dalam direktori "assets." Atribut alt digunakan untuk teks alternatif jika gambar tidak dapat ditampilkan.

&lt;div class="user-info"&gt; div yang berisi informasi tambahan tentang pengguna.

&lt;h3>Caroline</h3&gt; elemen judul level 3 &lt;h3&gt; yang menampilkan nama pengguna yang memberikan ulasan.

&lt;div class="stars"&gt; Ini adalah div yang berisi ikon-ikon bintang yang menggambarkan peringkat atau penilaian pengguna.

Di bawah div ini, terdapat beberapa elemen &lt;i&gt; yang menggambarkan bintang-bintang dengan perbedaan jumlah tergantung pada peringkat yang diberikan pengguna. Lalu ada elemen &lt;p&gt; Ini adalah elemen paragraf yang berisi ulasan dari pengguna tentang produk atau layanan. Ulasan ini menjelaskan mengapa mereka menganggap produk tersebut bagus.


<h3>Footer Section</h3>

&lt;section class="footer"&gt; elemen section yang berisi footer halaman web Anda, yaitu bagian yang berisi tautan bantuan, tautan cepat, informasi kontak, tautan media sosial, dan hak cipta.

&lt;div class="footer-container"&gt; div yang digunakan untuk mengelompokkan konten dalam footer.

Terdapat tiga blok &lt;div class="box"&gt; yang berisi tautan-tautan:

- Blok pertama berjudul "get help" dan berisi tautan ke halaman FAQ, pengiriman, pengembalian, status pembayaran, dan kebijakan privasi.
- Blok kedua berjudul "quick links" dan berisi tautan ke beranda, produk, layanan, ulasan, dan halaman "about."
- Blok ketiga berjudul "contact info" dan berisi nomor telepon, alamat email, dan alamat fisik beserta kota dan negara. Tautan email memiliki class "lower" yang  digunakan untuk mengubah tampilan tautan.

&lt;div class="social-media" id="follow"&gt; adalah div yang berisi tautan ke berbagai platform media sosial seperti Facebook, Instagram, Twitter, YouTube, dan LinkedIn. Masing-masing tautan dibuka dalam tab atau jendela baru (atribut target="_blank") untuk mengarahkan pengunjung ke halaman tab baru pada media sosial.

Di bagian bawah footer, ada elemen &lt;div class="copyright"&gt; yang menampilkan hak cipta dan tahun, yang dalam contoh ini menyatakan "All Right Reserved © copyright 2023 by swiftshop."

&lt;script src="script.js"></script&gt; elemen yang menghubungkan ke berkas JavaScript eksternal "script.js." Ini digunakan untuk menambahkan fungsi-fungsi JavaScript khusus ke halaman web. Juga, elemen &lt;script&gt; ini berada di bagian akhir sebelum penutup &lt;/body&gt;.

&lt;/body&gt; dan &lt;/html&gt; Ini merupakan penutup dari halaman HTML


<h2>Halaman Menu Product</h2>

Pada halaman menu product ini tampilan navbar nya sama seperti pada tampilan halaman home namun perbedaan dari halaman product ini ialah halaman product digunakan khusus untuk menampilkan produk-produk yang ingin dijual dan memudahkan pengguna dalam mencari produk yang mereka inginkan.

main adalah elemen HTML &lt;main&gt; yang digunakan untuk mengelompokkan konten utama halaman web.

Terdapat beberapa blok produk yang diatur dalam baris-baris yang terdiri dari tiga kolom &lt;div class="card-column"&gt; dalam setiap baris. Setiap blok produk memiliki struktur yang serupa:

&lt;div class="card"&gt; adalah div yang digunakan sebagai sebuah wadah atau tempat dalam menampilkan gambar seluruh produk.

&lt;img src="./assets/produk2.jpg" alt="" class="img-responsive"&gt; elemen gambar &lt;img&gt; yang menampilkan gambar produk dengan atribut src yang mengarah ke berkas gambar "produk2.jpg" dalam direktori "assets." Atribut alt digunakan untuk teks alternatif jika gambar tidak dapat ditampilkan. Kelas "img-responsive" mungkin digunakan untuk mengatur responsifitas gambar.

&lt;h3>Redmi Note 11</h3&gt; adalah elemen judul level 3 yang menampilkan nama produk.

&lt;span class="price">Rp. 2.899.000</span&gt; elemen yang menampilkan harga produk.

&lt;div class="stars"&gt; adalah div yang berisi ikon-ikon bintang yang menggambarkan peringkat atau penilaian produk.

Di bawah div ini, terdapat beberapa elemen &lt;i&gt; yang menggambarkan bintang-bintang dengan perbedaan jumlah tergantung pada peringkat produk.
&lt;button type="button" class="btn btn-primary spacercart"&gt; elemen tombol <button> dengan atribut type="button". Kelas "btn" dan "btn-primary" yang  digunakan untuk mengatur tampilan tombol. Kelas "spacercart" digunakan untuk mengatur spasi antara tombol dan konten produk.

&lt;img src="./assets/shopping-cart.png" alt="" class="cart"&gt; Ini adalah elemen gambar <img> yang menampilkan ikon keranjang belanja. Atribut src mengarah ke berkas gambar "shopping-cart.png" dalam direktori "assets." Atribut alt digunakan untuk teks alternatif jika gambar tidak dapat ditampilkan.

Lalu ada gambar ikon keranjang, terdapat teks "Add to Cart," yang digunakan untuk menambahkan produk ke dalam keranjang.


<h2>Style css</h2>

<h4>(*) Ini adalah selektor universal yang mengatur properti untuk semua elemen dalam halaman web.</h4>

- font-family: 'Nunito Sans', sans-serif; mengatur font utama yang akan digunakan di seluruh halaman.
- margin: 0;, padding: 0;, dan box-sizing: border-box; menghilangkan margin dan padding bawaan serta mengatur model kotak elemen.
- text-decoration: none; menghilangkan dekorasi teks seperti garis bawah dari tautan.
- outline: none; menghilangkan outline saat elemen menerima fokus.
- border: none; menghilangkan semua border elemen.
- text-transform: capitalize; mengubah teks menjadi huruf kapital setiap kata.
- transition: all .2s linear; mengatur transisi animasi untuk semua elemen dengan durasi 0.2 detik dan efek linear.

<h4>html: Ini adalah selektor untuk elemen HTML.</h4>

- font-size ⇒ 62.5%; mengatur ukuran font menjadi 62.5% dari ukuran font dasar (biasanya 16px), sehingga memudahkan penggunaan unit rem.
- overflow-x ⇒ hidden; menghilangkan scroll horizontal.
- scroll-padding-top ⇒ 5.5rem; mengatur jarak saat menggulir ke elemen dengan atribut id. Ini digunakan untuk menyesuaikan posisi tampilan saat menggunakan scroll smooth.
- scroll-behavior ⇒ smooth; memberikan efek scroll halus ketika menggulir ke elemen dengan atribut id.
- header ⇒ selektor untuk elemen header. Dalam hal ini, kode mengatur tampilan header seperti warna latar belakang, padding, display, dan lainnya.

header .logo ⇒ selektor untuk elemen logo di dalam header. Kode mengatur tampilan logo, warna, dan ukuran font.
header .navbar a ⇒ selektor untuk tautan di dalam navbar header. Kode mengatur tampilan tautan seperti ukuran font, warna, padding, dan lainnya.
header .icons i, header .icons a ⇒ selektor untuk ikon dan tautan di dalam elemen icons di header. Kode mengatur tampilan ikon dan tautan, termasuk ukuran, warna, dan efek hover.
header .icons i:hover, header .icons a:hover ⇒ aturan yang mengatur tampilan ikon dan tautan ketika dihover. Ini termasuk perubahan warna dan rotasi ikon.
header .icons #menu-bar ⇒ selektor untuk ikon menu bar yang mungkin digunakan untuk menu responsif, meskipun dalam kode yang Anda bagikan, id yang benar adalah menu-bars.


<h3>Dropdown menu css</h3>

- ul ⇒ selektor yang mengatur elemen ul (unordered list) di dalam halaman web. 

- list-style ⇒ none; menghilangkan tanda bullet pada daftar (list-style).
- background: #ffa500; mengatur latar belakang daftar dengan warna oranye (#ffa500).
- ul li ⇒ selektor untuk elemen-elemen li (list item) di dalam daftar ul. Kode ini mengatur elemen-elemen ini untuk ditampilkan secara horizontal (inline-block) dan posisi relatif.

ul li a ⇒ selektor untuk tautan di dalam elemen li. Kode ini mengatur tampilan tautan, termasuk warna teks, padding, dekorasi teks, ukuran font, dan margin atas.

.navbar ul.dropdown li ⇒ selektor khusus untuk tautan yang berada di dalam dropdown. Dalam kode ini, tautan dropdown juga diatur untuk ditampilkan sebagai blok (display: block;).

.navbar ul.dropdown ⇒ selektor khusus untuk daftar dropdown yang muncul ketika menu dihover. Dalam kode ini:

- width: 10%; mengatur lebar dropdown.
- background: #fff; mengatur latar belakang dropdown dengan warna putih (#fff).
- position: absolute; mengatur posisi dropdown secara absolut.
- z-index: 999; memberikan indeks z tinggi agar dropdown muncul di atas elemen-elemen lain.
- display: none; mengatur dropdown untuk disembunyikan secara default.
- border-radius: 5px; mengatur sudut dengan radius 5px.
- margin-left: 80px; mengatur jarak dari sisi kiri saat muncul.
- ul li a:hover: digunakan untuk mengatur tampilan tautan saat dihover. Dalam kode ini, latar belakang tautan akan berubah menjadi oranye (#ffa500).

.navbar:hover ul.dropdown: digunakan mengatur dropdown muncul saat menu navbar dihover (menu utama). Dalam kode ini, dropdown yang sebelumnya memiliki display: none; akan menjadi display: block; saat menu utama dihover.


<h4>Search Content</h4>

.search-box: adalah selektor untuk elemen dengan kelas "search-box," yang digunakan untuk membungkus elemen-elemen yang terkait dengan pencarian. Dalam kode ini:

- height: 100vh; mengatur tinggi elemen menjadi setinggi viewport (tinggi layar) pengguna.
- display: flex; mengatur tampilan elemen sebagai flex container.
- justify-content: center; mengatur konten agar tengah secara horizontal.
- align-items: center; mengatur konten agar tengah secara vertikal.
- background: #fff; mengatur latar belakang elemen dengan warna putih (#fff).
- margin-top: -180px; dan margin-bottom: -200px; memberikan margin atas dan bawah negatif, yang digunakan untuk mengatur posisi elemen.
  
.content-box: adalah selektor untuk elemen dengan kelas "content-box," yang mungkin digunakan untuk mengelilingi kotak pencarian atau elemen-elemen terkait lainnya. Dalam kode ini:

- height: 100vh; mengatur tinggi elemen menjadi setinggi viewport (tinggi layar) pengguna.
- display: flex; mengatur tampilan elemen sebagai flex container.
- height: 40px; mengatur tinggi elemen menjadi 40px (namun, ini bisa menggantikan tinggi elemen tersebut).
- cursor: pointer; mengubah kursor mouse saat berada di atas elemen menjadi tanda panah.
- padding: 10px 20px; memberikan padding elemen dengan ukuran tertentu.
- background: #fff; mengatur latar belakang elemen dengan warna putih (#fff).
- border: 1px solid orange; mengatur border elemen dengan warna oranye dan lebar 1px.
- border-radius: 30px; mengatur sudut elemen dengan radius 30px.
- box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1); memberikan bayangan elemen untuk efek lembut. Bayangan ini memiliki horizontal offset 0, vertikal offset 10px, blur radius 25px, dan - warna bayangan dengan opasitas 0.1.
  
.content-box input: selektor untuk elemen input yang mungkin digunakan dalam kotak pencarian. Dalam kode ini, lebar elemen input diatur menjadi 500px.

.content-box a .fas: adalah selektor untuk ikon dengan kelas "fas" yang mungkin ada di dalam elemen dengan kelas "content-box." Dalam kode ini, warna ikon diatur menjadi oranye dan ukuran fontnya adalah 18px.


<h3>Home Slider</h3>

section: Ini adalah selektor umum untuk elemen-elemen section di halaman web Anda. Dalam kode ini:

padding: 2rem 9%; memberikan padding pada semua sisi elemen section. Padding adalah 2 rem pada sisi atas dan bawah serta 9% pada sisi kiri dan kanan.
section:nth-child(even): Ini adalah selektor untuk elemen section dengan indeks genap (urutan kedua, keempat, dst.). Dalam kode ini:

- background: #fff; memberikan latar belakang putih pada elemen section dengan indeks genap.
- #gadget: Ini adalah selektor untuk elemen dengan ID "gadget." Dalam kode ini:
- margin-top: 50px; memberikan margin atas sebesar 50px pada elemen dengan ID "gadget."
  
.home .home-slider .slide: Ini adalah rangkaian selektor untuk elemen-elemen yang mungkin digunakan dalam bagian slider di halaman "home." Dalam kode ini:

- display: flex; mengatur tampilan elemen menjadi flex container.
- align-items: center; mengatur elemen agar berada di tengah secara vertikal.
- justify-content: center; mengatur elemen agar berada di tengah secara horizontal.
- flex-wrap: wrap; mengatur elemen agar dapat membalut ke baris berikutnya jika tidak cukup lebar.
- gap: 2rem; memberikan jarak 2 rem antara elemen-elemen dalam flex container.
- padding-top: 9rem; memberikan padding atas sebesar 9 rem.
- 
.home .home-slider .slide .content: Ini adalah selektor untuk elemen dengan kelas "content" yang mungkin ada dalam slider. Dalam kode ini:

flex: 1 1 45rem; mengatur elemen agar memiliki pertumbuhan fleksibel (1), pertahanan fleksibel (1), dan lebar maksimal 45 rem.
.home .home-slider .slide .image: Ini adalah selektor untuk elemen dengan kelas "image" yang mungkin ada dalam slider. Dalam kode ini:

flex: 1 1 45rem; mengatur elemen agar memiliki pertumbuhan fleksibel (1), pertahanan fleksibel (1), dan lebar maksimal 45 rem.
.home .home-slider .slide .image img: Ini adalah selektor untuk gambar yang mungkin ada dalam elemen dengan kelas "image." Dalam kode ini:

width: 100%; mengatur lebar gambar menjadi 100% dari lebar elemen yang mengandungnya.
.home .home-slider .slide .content span: Ini adalah selektor untuk elemen <span> yang mungkin ada dalam elemen dengan kelas "content" dalam slider. Dalam kode ini:

color: #ffa600fa; mengatur warna teks menjadi oranye.
.home .home-slider .slide .content h3: Ini adalah selektor untuk elemen heading h3 yang mungkin ada dalam elemen dengan kelas "content" dalam slider. Dalam kode ini:

color: #ec3e2bfd; mengatur warna teks menjadi ungu.
.home .home-slider .slide .content p: Ini adalah selektor untuk elemen paragraf yang mungkin ada dalam elemen dengan kelas "content" dalam slider. Dalam kode ini:

- color: #666; mengatur warna teks menjadi abu-abu.
- font-size: 16px; mengatur ukuran teks menjadi 16px.
- padding: .5rem 0; memberikan padding di atas dan bawah teks sebesar 0.5 rem.
- margin-right: 45px; memberikan margin di sisi kanan teks sebesar 45px.
- text-align: justify; mengatur teks menjadi rata kiri-kanan.


<h3>Button Slider</h3>

.btn Selector:
- margin-top: 1rem;: Menambahkan margin atas sebesar 1 rem ke elemen-elemen dengan kelas .btn.
- display: inline-block;: Membuat elemen-elemen dengan kelas .btn menjadi elemen inline-block, yang memungkinkan elemen tersebut mengalir secara horizontal.
- font-size: 15px;: Mengatur ukuran font teks dalam elemen-elemen dengan kelas .btn menjadi 15 piksel.
- color: #fff;: Mengatur warna teks menjadi putih (#fff).
- background: #ec3e2bfd;: Mengatur warna latar belakang menjadi warna semi-transparan (#ec3e2bfd).
- border-radius: .5rem;: Membulatkan sudut tombol dengan radius border sebesar 0,5 rem.
- cursor: pointer;: Mengubah kursor menjadi ikon tangan (pointer) saat dihover di atas elemen-elemen dengan kelas .btn.
- padding: .8rem 3rem;: Mengatur padding (jarak antara teks dan tepi tombol) sebesar 0,8 rem pada bagian atas dan bawah serta 3 rem pada bagian kiri dan kanan.
- justify-content: center;: Properti ini biasanya digunakan untuk wadah flex (flex containers), dan tidak umumnya digunakan untuk elemen inline-block seperti tombol.
- margin-left: 55px;: Menambahkan margin kiri sebesar 55px ke elemen-elemen dengan kelas .btn.
  
.btn:hover Selector:
- background: #ffa600fa;: Mengubah warna latar belakang menjadi warna oranye semi-transparan (#ffa600fa) ketika elemen-elemen dengan kelas .btn dihover (disorot dengan kursor mouse).
  
#btn-order Selector:
- margin-left: 0;: Mengganti properti margin kiri untuk elemen dengan ID btn-order dan mengatur nilainya menjadi 0.


<h3>Ukuan gambar produk</h3>

.box img Selector:
- width: 24%;: Mengatur lebar gambar produk menjadi 24% dari lebar kontainer yang mengandungnya.
- display: inline-flex;: Mengubah tampilan gambar menjadi elemen inline-flex, yang memungkinkan elemen gambar untuk mengalir secara horizontal.
  
.cart Selector:
- width: 18px;: Mengatur lebar ikon keranjang belanja (cart) menjadi 18 piksel.
- margin-right: 5px;: Menambahkan margin sebesar 5 piksel pada sisi kanan ikon keranjang belanja.
  
Harga Produk:

.price Selector:
- font-size: 15px;: Mengatur ukuran font teks untuk harga produk menjadi 15 piksel.
- font-family: 'Times New Roman', Times, serif;: Menentukan jenis font untuk harga produk.
- font-weight: bold;: Mengatur teks harga produk menjadi tebal.
  
.card span Selector:
- color: orangered;: Mengubah warna teks yang berada dalam elemen <span> di dalam elemen dengan kelas .card menjadi oranye merah (orangered). Ini mungkin digunakan untuk menunjukkan elemen tertentu dalam kartu produk.
Bintang pada Produk:

.stars Selector:
- color: rgb(250, 233, 1);: Mengatur warna teks atau ikon bintang pada produk menjadi warna yang didefinisikan oleh nilai RGB (merah, hijau, biru) dengan nilai 250, 233, 1.


<h3>Konten Promosi</h3>

.content Selector:
- float: left;: Mengatur elemen dengan kelas .content untuk mengapung ke kiri sehingga kontennya akan muncul di sebelah kiri halaman.
- width: 60%;: Mengatur lebar elemen dengan kelas .content menjadi 60% dari lebar kontainer yang mengandungnya.
- margin-top: 70px;: Menambahkan margin atas sebesar 70 piksel ke elemen dengan kelas .content.
- text-align: justify;: Mengatur teks dalam elemen tersebut menjadi rata kanan dan kiri (justifikasi).
  
section h3 Selector:
- font-size: 35px;: Mengatur ukuran font teks untuk elemen h3 yang berada dalam elemen <section> menjadi 35 piksel.
- color: #ffa500;: Mengatur warna teks untuk elemen h3 menjadi oranye (kode warna: #ffa500).

section #deskripsi Selector:
- font-size: 16px;: Mengatur ukuran font teks untuk elemen dengan ID deskripsi yang berada dalam elemen <section> menjadi 16 piksel.
- color: #666;: Mengatur warna teks untuk elemen tersebut menjadi abu-abu tua (kode warna: #666).
- margin-right: 100px;: Menambahkan margin sebesar 100 piksel pada sisi kanan elemen dengan ID deskripsi.
- line-height: 1.9;: Mengatur jarak antara baris (line-height) menjadi 1.9, yang akan memberikan ruang ekstra antara baris teks.
- margin-top: 10px;: Menambahkan margin atas sebesar 10 piksel ke elemen dengan ID deskripsi.
  
section .image-promotion img Selector:
- float: right;: Mengatur gambar yang berada dalam elemen dengan kelas .image-promotion untuk mengapung ke kanan.
- width: 85%;: Mengatur lebar gambar promosi menjadi 85% dari lebar elemen yang mengandungnya.


<h3>Konten promosi about</h3>

.about Selector:
- margin-top: 50px;: Menambahkan margin atas sebesar 50 piksel ke elemen dengan kelas .about.
  
.about .row Selector:
- display: flex;: Mengubah elemen dengan kelas .row menjadi wadah flex untuk mengatur elemen-elemen anaknya.
- flex-wrap: wrap;: Memungkinkan elemen-elemen anak dalam .row untuk melilit saat mencapai batas lebar wadah.
- gap: 1.5rem;: Menambahkan jarak sebesar 1.5 rem antara elemen-elemen anak.
- align-items: center;: Memastikan elemen-elemen anak selaras secara vertikal.
  
.about .row .image Selector:
- flex: 1 1 45rem;: Mengatur elemen dengan kelas .image agar memiliki fleksibilitas, dengan basis ukuran awal 45rem (rem adalah unit yang bergantung pada ukuran font).
  
.about .row .image img Selector:
- width: 80%;: Mengatur lebar gambar yang ada dalam elemen .image menjadi 80% dari lebar elemen yang mengandungnya.
  
.about .row .content Selector:
- flex: 1 1 45rem;: Mengatur elemen dengan kelas .content agar memiliki fleksibilitas, dengan basis ukuran awal 45rem.
  
.about .row .content h3 Selector:
- color: #192a56;: Mengatur warna teks judul h3 menjadi biru tua (#192a56).
- font-size: 3rem;: Mengatur ukuran font teks h3 menjadi 3 rem (unit relatif terhadap ukuran font root).
  
.about .row .content p Selector:
- color: #666;: Mengatur warna teks deskripsi menjadi abu-abu tua (#666).
- font-size: 1.5rem;: Mengatur ukuran font teks deskripsi menjadi 1.5 rem.
- line-height: 2;: Mengatur tinggi baris (line-height) menjadi dua kali ukuran font teks.
  
.about .row .content .icons-container Selector:
- display: flex;: Mengubah elemen dengan kelas .icons-container menjadi wadah flex.
- gap: 1rem;: Menambahkan jarak sebesar 1 rem antara elemen-elemen anak.
- flex-wrap: wrap;: Memungkinkan elemen anak melilit saat mencapai batas lebar wadah.
- padding: 1rem 0;: Menambahkan padding 1 rem pada bagian atas dan bawah.
- margin-top: 0.5rem;: Menambahkan margin atas sebesar 0.5 rem.
  
.about .row .content .icons-container .icons:hover Selector:
- border: .1rem solid #ffa500;: Ketika elemen .icons dihover, menambahkan garis tepi (border) sebesar 0.1 rem dengan warna oranye (#ffa500).
  
.about .row .content .icons-container .icons Selector:
- background: #fff;: Mengatur latar belakang elemen .icons menjadi putih (#fff).
- border-radius: .5rem;: Membulatkan sudut elemen .icons dengan radius border 0.5 rem.
- border: .1rem solid rgba(0,0,0,.2);: Menambahkan border sebesar 0.1 rem dengan warna dan transparansi tertentu.
- display: flex;: Mengubah elemen .icons menjadi wadah flex.
- align-items: center;: Memastikan elemen-elemen anak dalam .icons selaras secara vertikal.
- justify-content: center;: Memastikan elemen-elemen anak dalam .icons selaras secara horizontal.
- gap: 1rem;: Menambahkan jarak sebesar 1 rem antara elemen-elemen anak.
- flex: 1 1 17rem;: Mengatur elemen .icons agar memiliki fleksibilitas, dengan basis ukuran awal 17rem.
- padding: 1.5rem 1rem;: Menambahkan padding sebesar 1.5 rem pada bagian atas dan bawah serta 1 rem pada sisi kiri dan kanan.
  
.about .row .content .icons-container .icons i Selector:
- font-size: 2.5rem;: Mengatur ukuran font ikon (misalnya ikon Font Awesome) menjadi 2.5 rem.
- color: #ffa600fa;: Mengatur warna ikon menjadi oranye muda semi-transparan (#ffa600fa).
  
.about .row .content .icons-container .icons span Selector:
- font-size: 1.5rem;: Mengatur ukuran font teks yang berada dalam elemen <span> menjadi 1.5 rem.
- color: #192a56;: Mengatur warna teks menjadi biru tua (#192a56).
  
#btn-about Selector:
- margin-left: -2px;: Menambahkan margin kiri sebesar -2 piksel ke elemen dengan ID btn-about.


<h3>Review user</h3>

.review Selector:
- background: #fff;: Mengatur latar belakang elemen dengan kelas .review menjadi putih (#fff).
- margin-top: 50px;: Menambahkan margin atas sebesar 50 piksel ke elemen dengan kelas .review.
  
.review .slide Selector:
- padding: 2rem;: Menambahkan padding sebesar 2 rem di sekitar elemen dengan kelas .slide.
- color: #192a56;: Mengatur warna teks dalam elemen .slide menjadi biru tua (#192a56).
- border: .1rem solid rgba(0,0,0,.2);: Menambahkan border sebesar 0.1 rem dengan warna dan transparansi tertentu.
- border-radius: .5rem;: Membulatkan sudut elemen dengan kelas .slide dengan radius border 0.5 rem.
- position: relative;: Mengatur elemen .slide sebagai elemen posisi relatif.
- width: 30%;: Mengatur lebar elemen .slide menjadi 30% dari lebar kontainer yang mengandungnya.
- display: inline-block;: Mengatur elemen .slide sebagai elemen inline-block.
- margin-right: 20px;: Menambahkan margin kanan sebesar 20 piksel di antara elemen .slide.
- align-items: center;: Memastikan elemen .slide selaras secara vertikal.
- justify-content: center;: Memastikan elemen .slide selaras secara horizontal.
- background: #fff;: Mengatur latar belakang elemen .slide menjadi putih (#fff).
  
.review .slide .fa-quote-right Selector:
- position: absolute;: Mengatur elemen dengan kelas .fa-quote-right sebagai elemen posisi absolut.
- top: 2.5rem; right: 2.5rem;: Mengatur posisi elemen .fa-quote-right di atas kanan elemen .slide.
- font-size: 2.5rem;: Mengatur ukuran font ikon kutipan menjadi 2.5 rem.
- color: #ccc;: Mengatur warna ikon kutipan menjadi abu-abu (#ccc).
  
.review .slide .user Selector:
- display: flex;: Mengubah elemen dengan kelas .user menjadi wadah flex.
- gap: 1.5rem;: Menambahkan jarak sebesar 1.5 rem antara elemen-elemen anak.
- align-items: center;: Memastikan elemen-elemen anak dalam .user selaras secara vertikal.
- padding-bottom: 1.5rem;: Menambahkan padding sebesar 1.5 rem di bagian bawah elemen .user.
  
.review .slide .user img Selector:
- height: 7rem;: Mengatur tinggi gambar pengguna menjadi 7 rem.
- width: 7rem;: Mengatur lebar gambar pengguna menjadi 7 rem.
- border-radius: 50%;: Membulatkan sudut gambar pengguna dengan radius border setengah lingkaran.
- object-fit: cover;: Memastikan gambar pengguna diatur dengan baik untuk mengisi kotaknya.
  
.review .slide .user h3 Selector:
- color: #192a56;: Mengatur warna teks judul pengguna menjadi biru tua (#192a56).
- font-size: 2rem;: Mengatur ukuran font teks judul pengguna menjadi 2 rem.
  
.review .slide .user i Selector:
- font-size: 1.3rem;: Mengatur ukuran font ikon (jika ada) dalam elemen .user menjadi 1.3 rem.
- color: #ffa600fa;: Mengatur warna ikon menjadi oranye muda semi-transparan (#ffa600fa).
  
.review .slide p Selector:
- font-size: 1.5rem;: Mengatur ukuran font teks ulasan menjadi 1.5 rem.
- line-height: 1.5;: Mengatur tinggi baris (line-height) menjadi 1.5 kali ukuran font teks.
- text-align: justify;: Mengatur teks ulasan menjadi rata kanan dan kiri (justifikasi).
- color: #666;: Mengatur warna teks ulasan menjadi abu-abu tua (#666).
  
.review .swiper-container .review-slider Selector:
- display: flex;: Mengubah elemen dengan kelas .review-slider menjadi wadah flex.
- display: inline-flex;: Mengubah elemen dengan kelas .review-slider menjadi elemen inline-flex.


<h3>Footer Section</h3>

.footer .footer-container Selector:
- display: grid;: Mengubah elemen dengan kelas .footer-container menjadi wadah grid.
- grid-template-columns: repeat(auto-fit, minmax(20rem, 1fr));: Menentukan grid dengan kolom yang akan menyesuaikan dengan lebar layar (auto-fit) dengan lebar minimum 20 rem, dan fraksi 1 (1fr) yang memungkinkan elemen-elemen untuk mengisi ruang yang tersedia secara merata.
- gap: 3.2rem;: Menambahkan jarak antara elemen-elemen anak sebesar 3.2 rem.
- margin-top: 60px;: Menambahkan margin atas sebesar 60 piksel pada elemen dengan kelas .footer-container.
- margin-bottom: 20px;: Menambahkan margin bawah sebesar 20 piksel pada elemen dengan kelas .footer-container.
  
#contact a Selector:
- text-decoration: none;: Menghilangkan dekorasi tautan (misalnya, garis bawah) untuk tautan yang berada dalam elemen dengan ID contact.
  
#follow Selector:
- margin-left: 30px;: Menambahkan margin kiri sebesar 30 piksel pada elemen dengan ID follow.

.lower Selector:
- text-transform: lowercase;: Mengubah semua teks dalam elemen dengan kelas .lower menjadi huruf kecil.

.footer .footer-container .box h3 Selector:
- padding: .5rem 0;: Menambahkan padding sebesar 0.5 rem di atas dan bawah judul h3 dalam elemen dengan kelas .box.
- font-size: 2rem;: Mengatur ukuran font judul h3 menjadi 2 rem.
- color: #192a56;: Mengatur warna teks judul h3 menjadi biru tua (#192a56).
  
.footer .footer-container .box a Selector:
- display: block;: Mengubah tautan dalam elemen dengan kelas .box menjadi elemen blok.
- padding: .5rem 0;: Menambahkan padding sebesar 0.5 rem di atas dan bawah tautan.
- font-size: 16px;: Mengatur ukuran font teks tautan menjadi 16 piksel.
- color: #666;: Mengatur warna teks tautan menjadi abu-abu tua (#666).

.footer .footer-container .box a:hover Selector:
- color: #ffa600fa;: Ketika tautan dihover, mengubah warna teks tautan menjadi oranye muda semi-transparan (#ffa600fa).
- text-decoration: underline;: Menambahkan garis bawah pada tautan saat dihover.

.footer .copyright Selector:
- text-align: center;: Mengatur teks hak cipta menjadi rata tengah.
- border-top: .1rem solid rgba(0,0,0,.1);: Menambahkan border di atas elemen hak cipta dengan ketebalan 0.1 rem dan warna transparan.
- font-size: 1.5rem;: Mengatur ukuran font teks hak cipta menjadi 1.5 rem.
- color: #192a56;: Mengatur warna teks hak cipta menjadi biru tua (#192a56).
- padding: .5rem;: Menambahkan padding sebesar 0.5 rem pada elemen hak cipta.
- padding-top: 2rem;: Menambahkan padding atas sebesar 2 rem pada elemen hak cipta.
- margin-top: 2rem;: Menambahkan margin atas sebesar 2 rem pada elemen hak cipta.
- margin-bottom: -1rem;: Mengurangi margin bawah sebesar 1 rem pada elemen hak cipta.


<h3>About Page</h3>

.about-page p Selector:
- color: black;: Mengatur warna teks paragraf (p) pada halaman "About" menjadi hitam.

.about-page .card h6 Selector:
- font-size: 22px;: Mengatur ukuran font untuk teks judul h6 dalam elemen dengan kelas .card menjadi 22 piksel.

.about-page .card p Selector:
- font-size: 16px;: Mengatur ukuran font untuk teks paragraf dalam elemen dengan kelas .card menjadi 16 piksel.
- color: #ffa500;: Mengatur warna teks teks paragraf dalam elemen dengan kelas .card menjadi oranye (#ffa500).
- font-weight: bold;: Mengatur teks paragraf dalam elemen dengan kelas .card menjadi tebal (bold).

.about-page Selector:
- margin-top: 100px;: Menambahkan margin atas sebesar 100 piksel pada elemen dengan kelas .about-page.
- font-size: 24px;: Mengatur ukuran font teks dalam elemen dengan kelas .about-page menjadi 24 piksel.
- justify-content: center;: Memastikan kontennya selaras secara horizontal.
- align-items: center;: Memastikan kontennya selaras secara vertikal.
- text-align: center;: Mengatur teks dalam elemen dengan kelas .about-page menjadi rata tengah.

.about-page hr Selector:
- margin-top: 12px;: Menambahkan margin atas sebesar 12 piksel pada elemen hr (garis horizontal).
- border: 0.5px solid rgb(226, 226, 226); Mengatur elemen hr dengan ketebalan 0.5 piksel dan warna border yang sesuai.


<h3>Logo Social Media</h3>

.social-media Selector:
- display: flex;: Mengatur elemen dengan kelas .social-media sebagai kontainer flexbox, yang akan memudahkan penataan elemen-elemen anak di dalamnya secara horisontal.
- text-align: center;: Mengatur teks dalam elemen dengan kelas .social-media menjadi rata tengah.
- margin-left: 100px;: Menambahkan margin kiri sebesar 100 piksel pada elemen dengan kelas .social-media.
- float: right;: Mengatur elemen tersebut agar mengapung ke kanan. Namun, ini mungkin tidak diperlukan jika Anda sudah menggunakan flexbox.

.social-media h3 Selector:
- font-size: 2rem;: Mengatur ukuran font untuk teks judul (h3) menjadi 2 rem.
- color: #192a56;: Mengatur warna teks judul menjadi biru tua (#192a56).

.social-media img Selector:
- width: 30px;: Mengatur lebar gambar menjadi 30 piksel.
- margin-top: 10px;: Menambahkan margin atas sebesar 10 piksel pada gambar.
- margin-left: 2px;: Menambahkan margin kiri sebesar 2 piksel pada gambar.

.social-media img:hover Selector:
- border: 2px solid #ffa500;: Ketika gambar dihover, menambahkan border dengan ketebalan 2 piksel dan warna oranye (#ffa500).
- border-radius: 50%;: Membulatkan sudut gambar dengan radius border setengah lingkaran.
- color: #ffa500;: Mengatur warna teks gambar menjadi oranye (#ffa500).

@media (max-width:991px):

html{ font-size: 55%; }: Mengatur ukuran font menjadi 55% dari ukuran default saat lebar layar maksimum mencapai 991 piksel.
header{ padding: 1rem 2rem; }: Mengatur padding pada elemen header menjadi 1 rem pada bagian atas dan bawah serta 2 rem pada sisi kiri dan kanan.
@media (max-width:768px):

header .icons #menu-bars{ display: inline-block; }: Mengubah tampilan menu-bars menjadi inline-block saat lebar layar maksimum mencapai 768 piksel.
header .navbar{ ... }: Menetapkan gaya untuk elemen dengan kelas .navbar ketika lebar layar maksimum mencapai 768 piksel. Ini termasuk menetapkan posisi absolut, mengatur warna latar belakang, dan menambahkan batas atas dan bawah.
header .navbar a{ ... }: Menetapkan gaya untuk tautan dalam elemen dengan kelas .navbar ketika lebar layar maksimum mencapai 768 piksel. Ini termasuk menetapkan tampilan blok, padding, ukuran font, dan warna latar belakang.


<h3>Halaman about html</h3>

mewakili halaman "Meet The Team."  mencakup judul, garis pemisah, dan daftar anggota tim.

&lt;h2>Meet The Team</h2&gt; judul halaman "Meet The Team" yang mungkin akan ditampilkan di atas daftar anggota tim.

&lt;hr&gt; elemen garis horizontal yang digunakan untuk memisahkan judul dari daftar anggota tim.

&lt;div class="card-row spacercontent"&gt; wadah (container) untuk baris kartu (card) yang akan menampilkan anggota tim.

&lt;div class="card-column"&gt; kolom kartu yang akan menampilkan detail masing-masing anggota tim. Ada tiga kolom kartu yang akan menampilkan tiga anggota tim.

&lt;div class="card"&gt; elemen div dengan kelas "card" yang mewakili kartu anggota tim. Setiap kartu mencakup gambar, nama, dan jurusan dari anggota tim.

&lt;img src="./assets/ainul.png" alt="" class="img-responsive"&gt; gambar anggota tim (dalam hal ini, Ainul) dengan atribut src yang menunjukkan sumber gambar. Atribut alt digunakan untuk deskripsi alternatif gambar (biasanya digunakan untuk aksesibilitas).

&lt;h6>Ainul</h6&gt; judul atau nama anggota tim

&lt;p>;Manajemen Informatika</p&gt; informasi tambahan tentang anggota tim, seperti jurusan mereka (dalam hal ini, Manajemen Informatika).


<h3>Card css</h3>

* { box-sizing: border-box; }:

Mendefinisikan box model global, yang memastikan bahwa panjang dan lebar elemen mencakup padding dan border, serta margin.

.card img Selector:
- width: 200px; height: 200px; Mengatur lebar dan tinggi gambar dalam kartu (card) menjadi 200 piksel.
- justify-content: center; untuk mengatur konten gambar ke tengah dalam kartu (tetapi ini biasanya digunakan untuk elemen yang memiliki display: flex;, bukan untuk gambar).
- margin-left: 10px;: Menambahkan margin kiri sebesar 10 piksel pada gambar.

.card-row Selector:
- width: 100%;: Mengatur lebar baris kartu menjadi 100% dari wadah induknya.
- margin: 10px;: Menambahkan margin sebesar 10px di sekitar baris kartu.
- padding-left: 50px; padding-right: 40px;: Menambahkan padding kiri sebesar 50px dan padding kanan sebesar 40px pada baris kartu.
- margin-bottom: 50px;: Menambahkan margin bawah sebesar 50px pada baris kartu.
- overflow: auto;: Jika konten melebihi lebar baris kartu, maka akan ada bilah geser horizontal.

.card-column Selector:
- width: 25%;: Mengatur lebar kolom kartu menjadi 25% dari baris kartu, yang memungkinkan 4 kolom kartu dalam satu baris.
- float: left;: Mengatur elemen kolom kartu untuk mengapung ke kiri sehingga mereka sejajar satu sama lain.
- padding: 0 16px;: Menambahkan padding nol di atas dan bawah, dan 16px di sisi kiri dan kanan kolom kartu.
- margin-left: 80px;: Menambahkan margin kiri sebesar 80px pada kolom kartu.

.card Selector:
- background-color: white;: Mengatur latar belakang kartu menjadi putih.
- padding: 16px;: Menambahkan padding sebesar 16px di dalam kartu.
- box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.4);: Menambahkan bayangan pada kartu untuk memberikan efek tiga dimensi.
- border-radius: 10px;: Mengatur sudut kartu menjadi lebih melengkung dengan radius border sebesar 10px.
- margin-top: 50px; margin-bottom: 10px;: Menambahkan margin atas sebesar 50px dan margin bawah sebesar 10px pada kartu.
- text-align: center;: Mengatur teks dalam kartu menjadi rata tengah.

.card:hover Selector:
- border: 2px solid #ffa200;: Ketika kartu dihover, menambahkan border dengan ketebalan 2px dan warna oranye (#ffa200).
- box-shadow: 0 8px 16px 0 rgba(189, 2, 2, 0.4);: Mengubah bayangan kartu saat dihover.
- animation: infinite;: Menerapkan animasi dengan efek yang tak berujung.
- transition: all 0.2s step-start;: Menambahkan efek transisi dengan durasi 0.2 detik dan efek "step-start".

.card h6 Selector:
- color: black;: Mengatur warna teks judul h6 menjadi hitam.
- margin-top: 10px;: Menambahkan margin atas sebesar 10px pada judul h6.

.card p Selector:
- margin-left: 20px;: Menambahkan margin kiri sebesar 20px pada teks paragraf (p).

.about-page h2 Selector:
- font-weight: bold;: Mengatur tebal huruf pada judul h2.
- color: grey;: Mengatur warna teks judul h2 menjadi abu-abu.


<h2>LOGIN DAN SIGNUP</h2>

<h3>Penjelasan HTML Login dan signup:</h3>

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


<h3>Penjelasan CSS Login dan Signup</h3>

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

<h3>Penjelasan JS Login dan Signup</h3>

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

<div align="justify">

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

12. .contact p: Ini mengatur tampilan teks deskripsi dalam elemen dengan kelas "contact."

13. .contactInfo: Ini adalah selector untuk elemen dengan kelas "contactInfo." Ini mengatur tampilan wadah informasi kontak.

14. .box: Ini adalah selector untuk elemen dengan kelas "box," yang digunakan untuk mengelompokkan ikon dan teks dalam informasi kontak.

15. .icon: Ini mengatur tampilan ikon dalam elemen dengan kelas "box."

16. .text: Ini mengatur tampilan teks informasi dalam elemen dengan kelas "box."

17. .text h3: Ini mengatur tampilan judul informasi dalam elemen dengan kelas "box."

18. .contactForm: Ini adalah selector untuk elemen dengan kelas "contactForm." Ini mengatur tampilan formulir kontak.

19. .contactForm h2: Ini mengatur tampilan judul formulir dalam elemen dengan kelas "contactForm."

20. .inputBox: Ini adalah selector untuk elemen dengan kelas "inputBox," yang digunakan untuk mengelompokkan masukan dalam formulir kontak.

21. .inputBox input, .inputBox textarea: Ini mengatur tampilan input dan textarea dalam elemen dengan kelas "inputBox."

22. .inputBox label: Ini mengatur tampilan label animasi yang melayani sebagai placeholder untuk input.

23. .inputBox input:focus + label, .inputBox input:valid + label, .inputBox textarea:focus + label, .inputBox textarea:valid + label: Ini mengatur tampilan label animasi ketika input dalam fokus atau memiliki nilai yang valid.

24. .inputBox input[type="submit"]: Ini mengatur tampilan tombol "Submit" dalam formulir kontak.

25. @media (max-width: 991px): Ini adalah media query yang mengaktifkan gaya khusus untuk layar berukuran lebih kecil (maksimum lebar 991 piksel).

26. .contact, .content, .contactForm: Ini mengatur tampilan elemen dengan kelas "contact," "content," dan "contactForm" saat media query aktif.

27. .contactInfo: Ini mengatur tampilan wadah informasi kontak dalam mode layar kecil.

28. .box: Ini mengatur tampilan kotak informasi dalam mode layar kecil.
</div>


<h3>PENJELASAN HTML CHECKOUT</h3>

<div align="justify">

1. Deklarasi Dokumen HTML: &lt;!DOCTYPE html&gt; menunjukkan bahwa halaman ini menggunakan HTML5, versi terbaru dari bahasa pemrograman web.

2. Elemen HTML Utama:

   • &lt;html lang="en&gt;: Mengawali dokumen HTML.
   
   • &lt;head&gt;: Ini adalah bagian kepala halaman yang berisi informasi metadata dan pengaturan penting.
   
   • &lt;body&gt;: Ini adalah tempat konten utama halaman web, yang akan dilihat oleh pengguna.

3. Metadata:

   • &lt;meta charset="UTF-8"&gt;: Mengatur karakter set ke UTF-8, sehingga teks dalam berbagai bahasa dapat ditampilkan dengan benar.

   • &lt;meta http-equiv="X-UA-Compatible" content="IE=edge"&gt;: Mengatur kompatibilitas dengan Internet Explorer.

   • &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;: Mengatur tampilan responsif agar sesuai dengan berbagai perangkat.

4. Judul Halaman: &lt;title&gt;Checkout&lt;/title&gt; menunjukkan judul yang akan ditampilkan di tab browser.

5. Stylesheet Eksternal: &lt;link rel="stylesheet" href="checkout.css"&gt; menghubungkan halaman dengan file CSS eksternal "checkout.css" untuk mengatur tampilan halaman.

6. Konten Utama:

   • &lt;header&gt;: Bagian ini menampilkan judul toko "SwiftShop" dan jumlah item dalam keranjang belanja.

   • &lt;div class="list"&gt;: Ini adalah daftar produk yang akan ditampilkan di halaman. Produknya dikelompokkan menjadi beberapa kategori seperti Handphone, iPad, Jam, TV, dan Laptop.

   • Setiap produk dalam kategori memiliki elemen berikut:
   
   	- Gambar produk.
   
   	- Nama produk.
   
	- Harga produk.

	- Tombol "Add To Cart" yang memanggil fungsi JavaScript addToCart dengan ID produk sebagai argumen saat diklik.

7. Keranjang Belanja:

   • &lt;div class="cart"&gt;: Ini adalah bagian yang menunjukkan apa yang ada di keranjang belanja.

   • &lt;ul class="listCart"&gt;: Ini adalah daftar item dalam keranjang belanja.

   • &lt;div class="checkOut"&gt;: Menampilkan total harga produk dalam keranjang belanja dan tombol "Close" untuk menutup keranjang belanja.

8. JavaScript Eksternal: &lt;script src="checkout.js"&gt;&lt;/script&gt; menghubungkan halaman dengan file JavaScript eksternal "checkout.js" yang akan mengatur interaksi pengguna seperti menambahkan produk ke keranjang dan menghitung total harga.
</div>


<h3>PENJELASAN CSS CHECKOUT</h3>

<div align="justify">

1. Reset CSS:

   • Ini adalah aturan CSS yang mengatur ulang tampilan default dari semua elemen HTML di halaman web.

   • * berlaku untuk semua elemen HTML.

   • margin: 0 menghilangkan margin, yaitu ruang di luar elemen.

   • padding: 0 menghilangkan padding, yaitu ruang di dalam elemen.

   • box-sizing: border-box mengubah model kotak elemen sehingga lebar dan tinggi elemen mencakup border dan padding.

2. Mengatur Tampilan Awal Halaman:

   • Ini adalah aturan CSS yang mengatur tampilan awal halaman web.

   • background-color: #fff mengatur latar belakang halaman menjadi warna putih.

   • font-family: system-ui mengatur jenis font umum menjadi "system-ui."

   • margin: 0 menghilangkan margin pada elemen <body>.

3. Container:

   • Ini adalah aturan CSS untuk mengatur elemen dengan kelas "container."

   • max-width: 1000px mengatur lebar maksimum elemen menjadi 1000px.

   • margin: 0 auto memposisikan elemen di tengah secara horizontal.

   • transition: 0.5s memberikan efek transisi selama 0,5 detik saat ada perubahan pada elemen.

   • padding: 20px menambahkan padding sebesar 20px di sisi kiri dan kanan elemen untuk memberikan ruang.

4. Header:

   • Ini adalah aturan CSS yang mengatur tampilan bagian atas halaman, seperti header.

   • display: flex mengubah header menjadi kontainer fleksibel.

   • justify-content: space-between membuat elemen dalam header tersebar dengan sejumlah ruang di antara mereka.

   • align-items: center memposisikan elemen secara vertikal di tengah header.

   • margin-top: 50px memberikan margin atas sebesar 50px.

   • padding: 0 20px memberikan padding 0px di atas dan bawah, dan 20px di sisi kiri dan kanan header.

5. Gaya Ikon Keranjang Belanja:

   • Ini adalah aturan CSS yang mengatur tampilan ikon keranjang belanja.

   • position: relative memberikan posisi relatif pada elemen tersebut.

   • header .shopping img mengatur lebar gambar ikon keranjang belanja menjadi 40px.

   • header .shopping span mengatur latar belakang merah untuk angka item dalam keranjang, membuatnya berbentuk bulat, dan memposisikan teks di tengah.

   • position: absolute memungkinkan elemen angka item untuk ditempatkan secara absolut dengan koordinat tertentu.

   • top: -5px dan right: -10px mengatur posisi angka item.

   • padding: 3px 10px memberikan padding 3px di atas dan bawah, serta 10px di sisi kiri dan kanan angka item.

6. Daftar Produk (List):

   • Ini adalah aturan CSS yang mengatur tampilan daftar produk dengan layout grid.

   • display: grid mengubah daftar produk menjadi grid.

   • grid-template-columns: repeat(3, 1fr) mengatur tiga kolom per baris, dan fr (fraksi) memberikan ruang yang sama untuk setiap kolom.

   • gap: 30px memberikan jarak 30px di antara item dalam daftar produk.

   • margin-top: 50px memberikan margin atas sebesar 50px.

   • padding: 0 20px memberikan padding 0px di atas dan bawah, dan 20px di sisi kiri dan kanan daftar produk.

7. Gaya Judul Kategori:

   • Ini adalah aturan CSS yang mengatur tampilan judul kategori dalam daftar produk.

   • grid-column: span 3 membuat judul kategori menjangkau semua tiga kolom.

   • text-align: center memposisikan teks judul di tengah.

   • margin: 20px 0 memberikan margin atas 20px dan margin bawah 0.

   • font-size: 1.5rem mengatur ukuran font judul kategori menjadi 1.5 rem.

8. Gaya Setiap Item Produk dalam Daftar:

   • Ini adalah aturan CSS yang mengatur tampilan setiap item produk dalam daftar.

   • text-align: center memposisikan teks di tengah item.

   • background-color: #FFA500 mengatur latar belakang item menjadi oranye.

   • padding: 20px memberikan padding 20px di dalam item.

   • border-radius: 30px membuat item berbentuk bulat dengan sudut 30px.

   • box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2) memberikan efek bayangan.

   • letter-spacing: 1px mengatur jarak antar huruf dalam teks.

   • position: relative memberikan posisi relatif pada item tersebut.

   • overflow: hidden menghindari potongan teks yang berlebihan.

   • display: flex mengatur item dalam tata letak fleksibel.

   • flex-direction: column mengatur item dalam kolom.

   • align-items: center memposisikan item secara vertikal di tengah.

9. Gaya Gambar Produk:

   • Ini adalah aturan CSS yang mengatur tampilan gambar produk dalam setiap item.

   • max-width: 100% membuat gambar mengisi seluruh lebar item.

   • height: auto menjaga aspek gambar sehingga tinggi disesuaikan.

   • object-fit: cover mengatur gambar agar sesuai dengan ukuran kotak gambar.

   • margin: 0 0 20px memberikan margin 0px di atas dan samping, dan 20px di bawah gambar.

   • border-radius: 30px membuat gambar berbentuk bulat dengan sudut 30px.

10. Gaya Judul Produk:

    • Ini adalah aturan CSS yang mengatur tampilan judul produk dalam setiap item.

    • font-weight: bold membuat teks produk menjadi tebal.

    • margin: 0 0 10px memberikan margin 0px di atas dan samping, dan 10px di bawah judul.

    • white-space: nowrap menghindari pemotongan teks yang terlalu panjang.

    • overflow: hidden menghindari potongan teks yang berlebihan.

    • text-overflow: ellipsis mengatur teks yang melebihi ukuran untuk memotong dan menampilkan elipsis.

    • font-size: 1rem mengatur ukuran font judul produk menjadi 1 rem.

11. Gaya Harga Produk:

    • Ini adalah aturan CSS yang mengatur tampilan harga produk dalam setiap item.

    • margin: 0 0 10px memberikan margin 0px di atas dan samping, dan 10px di bawah harga.

12. Gaya Tombol "Add To Cart":
    • Ini adalah aturan CSS yang mengatur tampilan tombol "Add To Cart" dalam setiap item.

    • background-color: #1C1F25 mengatur latar belakang tombol menjadi warna gelap.

    • color: #fff mengatur warna teks tombol menjadi putih.

    • width: 100% membuat tombol mengisi seluruh lebar item.

    • padding: 5px 0 memberikan padding 5px di atas dan bawah tombol.

    • border-radius: 30px membuat tombol berbentuk bulat dengan sudut 30px.

    • margin-top: 10px memberikan margin di atas tombol "Add To Cart" sebesar 10px.

13. Tampilan Keranjang Belanja:

    • Ini adalah aturan CSS yang mengatur tampilan keranjang belanja.

    • position: fixed membuat keranjang belanja tetap saat digulir.

    • top: 0 memposisikan keranjang di bagian atas halaman.

    • right: -100% awalnya memposisikan keranjang di luar layar, dengan lebar 500px.

    • background-color: #d3d3d3 mengatur latar belakang keranjang belanja menjadi abu-abu.

    • height: 100vh mengisi tinggi keranjang belanja dengan tinggi tampilan pengguna.

    • transition: 0.5s memberikan efek transisi selama 0,5 detik saat ada perubahan pada keranjang.

14. Tampilan Keranjang Belanja Saat Aktif:

    • Ini adalah aturan CSS yang mengatur tampilan keranjang belanja saat menjadi aktif.

    • .active .cart mengatur tampilan keranjang belanja yang memiliki kelas "active."

    • left: calc(100% - 500px) menggeser masuk keranjang belanja saat aktif hingga menutupi 500px di sebelah kanan layar.

15. Menggeser Konten Saat Keranjang Belanja Aktif:

    • Ini adalah aturan CSS yang menggeser konten halaman saat keranjang belanja aktif.

    • .active .container mengatur kontainer dengan kelas "active."

    • transform: translateX(-200px) menggeser konten sejauh -200px ke kiri saat keranjang belanja aktif.

16. Gaya Judul dalam Keranjang Belanja:

    • Ini adalah aturan CSS yang mengatur tampilan judul dalam keranjang belanja.

    • color: #000 mengatur warna teks judul menjadi hitam.

    • font-weight: 100 mengatur ketebalan teks judul.

    • margin: 0 menghilangkan margin pada judul.

    • padding: 0 20px memberikan padding 0px di atas dan bawah, dan 20px di sisi kiri dan kanan judul.

    • height: 80px mengatur tinggi judul menjadi 80px.

    • display: flex mengubah judul menjadi kontainer fleksibel.

    • align-items: center memposisikan teks judul secara vertikal di tengah.

17. Gaya Bagian "Checkout" dalam Keranjang Belanja:

    • Ini adalah aturan CSS yang mengatur tampilan bagian "Checkout" dalam keranjang belanja.

    • position: absolute memungkinkan elemen "Checkout" ditempatkan secara absolut di bagian bawah keranjang.

    • bottom: 0 memposisikan elemen di bagian bawah keranjang.

    • width: 100% membuat elemen "Checkout" mengisi seluruh lebar keranjang.

    • display: grid mengubah elemen "Checkout" menjadi grid.

    • grid-template-columns: repeat(2, 1fr) mengatur dua kolom dengan lebar yang sama dalam elemen "Checkout."

18. Gaya Tombol "Checkout" dan "Lanjutkan Belanja" dalam Keranjang Belanja:

    • Ini adalah aturan CSS yang mengatur tampilan tombol "Checkout" dan "Lanjutkan Belanja" dalam keranjang belanja.

    • background-color: #E8BC0E mengatur warna latar belakang tombol "Checkout" menjadi kuning.

    • width: 100% membuat tombol mengisi seluruh lebar elemen "Checkout."

    • height: 70px mengatur tinggi tombol sebesar 70px.

    • display: flex mengubah tombol menjadi kontainer fleksibel.

    • justify-content: center memposisikan teks tombol secara horizontal di tengah tombol.

    • align-items: center memposisikan teks tombol secara vertikal di tengah tombol.

    • font-weight: bold mengatur ketebalan teks tombol.

    • cursor: pointer mengubah kursor menjadi tanda panah saat diarahkan ke tombol.

19. Gaya Daftar Produk dalam Keranjang Belanja:

    • Ini adalah aturan CSS yang mengatur tampilan daftar produk dalam keranjang belanja.

    • display: grid mengubah daftar produk dalam keranjang menjadi grid.

    • grid-template-columns: 100px repeat(3, 1fr) mengatur tiga kolom dengan kolom pertama lebarnya 100px, dan tiga kolom sisanya memiliki lebar yang sama.

    • color: #000 mengatur warna teks daftar produk menjadi hitam.

    • row-gap: 10px memberikan jarak 10px di antara item dalam daftar keranjang belanja.

20. Gaya Gambar Produk dalam Daftar Keranjang Belanja:

    • Ini adalah aturan CSS yang mengatur tampilan gambar produk dalam daftar keranjang belanja.

    • display: flex mengubah gambar menjadi kontainer fleksibel.

    • justify-content: center memposisikan gambar di tengah secara horizontal.

    • align-items: center memposisikan gambar di tengah secara vertikal.

21. Gaya Tombol "Remove" dalam Daftar Keranjang Belanja:

    • Ini adalah aturan CSS yang mengatur tampilan tombol "Remove" dalam daftar keranjang belanja.

    • background-color: #fff5 mengatur warna latar belakang tombol "Remove" menjadi putih dengan sedikit keabu-abuan.

    • border: none menghilangkan border tombol "Remove."

22. Gaya Jumlah Produk dalam Keranjang Belanja:

    • Ini adalah aturan CSS yang mengatur tampilan jumlah produk dalam daftar keranjang belanja.

    • margin: 0 10px memberikan margin 0px di atas dan samping, dan 10px di sisi kiri dan kanan jumlah produk.
</div>


<h3>PENJELASAN JAVA SCRIPT CHECKOUT</h3>

<div align="justify">

1. Inisialisasi Variabel: Kode pertama adalah untuk menginisialisasi sejumlah variabel yang digunakan dalam aplikasi, seperti elemen-elemen DOM (Document Object Model) dan array products yang berisi informasi produk.

2. Event Listener: Dua event listener ditambahkan untuk mengontrol tampilan keranjang belanja. Ketika elemen dengan kelas .shopping diklik, kelas CSS 'active' ditambahkan ke elemen <body>, sehingga menampilkan keranjang belanja. Ketika elemen dengan kelas .closeShopping diklik, kelas 'active' dihapus, menyembunyikan keranjang belanja.

3. Array products: Ini adalah array yang berisi informasi produk, termasuk id, name, image, dan price.

4. Array listCarts: Ini adalah array yang digunakan untuk menyimpan barang-barang yang ditambahkan ke keranjang belanja. Setiap elemen dalam array ini adalah objek produk dengan properti tambahan quantity yang menyimpan jumlah barang yang ditambahkan.

5. addToCart Function: Fungsi ini digunakan untuk menambahkan produk ke keranjang belanja. Jika produk sudah ada dalam keranjang, maka kuantitasnya ditingkatkan. Jika belum ada, produk ditambahkan ke keranjang. Fungsi isInCategory digunakan untuk memeriksa apakah produk termasuk dalam kategori tertentu.

6. reloadCart Function: Fungsi ini digunakan untuk memperbarui tampilan keranjang belanja. Itu menghapus konten keranjang belanja saat ini dan membangun ulangnya dengan item-item yang ada dalam array listCarts.

7. changeQuantity Function: Fungsi ini memungkinkan pengguna untuk mengubah jumlah produk dalam keranjang belanja. Jika jumlah diatur ke 0, item dihapus dari keranjang.

8. filterProducts Function: Fungsi ini memungkinkan pengguna untuk memfilter produk berdasarkan kategori. Ini menyembunyikan atau menampilkan item sesuai dengan kategori yang dipilih.

9. isInCategory Function: Fungsi ini digunakan untuk memeriksa apakah produk berada dalam kategori tertentu berdasarkan itemId.

10. Event Listener untuk Navigasi Kategori: Event listener ini mengatur penggunaan kategori tertentu dengan mengklik elemen &lt;h2&gt; yang mewakili kategori.

11. initApp Function: Ini adalah fungsi yang menginisialisasi aplikasi dengan menambahkan produk ke daftar. Setiap produk direpresentasikan sebagai elemen &lt;div&gt; dalam daftar dengan tombol "Add to Cart".

12. Panggilan initApp Function: Di akhir kode, fungsi initApp dipanggil untuk memulai aplikasi dengan menambahkan produk ke daftar awal.
</div>
