<html>
<body>
<body><div align="center"><h1>Software Requirement Spesification</h1></div>
<p align="center"><b>Version 1.0 </b><br>
<p align="center">4 Maret 2018<br><br>
<p align="center">
<img src="https://2.bp.blogspot.com/-dxdRgMQGbLk/WpA-Tp2rNGI/AAAAAAAAAh8/3_jBWFb7Cf48033QvB34D2WCwoN2sxZLgCLcBGAs/s1000/index.png"/>
</p>

<br><p align="center"><b> APLIKASI PEMESANAN MAKANAN BERBASIS ANDROID </b><br>

<p align="center"><b>Kelompok 4</b><br>
 Irin Windiyati 			(1603173)<br>
 Dina Micela				  (1603066)<br>
 Nunung Nurhayati			(1603081)<br>
 Yoshie Pangestu    	(1603089)<br><br><br>

<p align="center"><b>Jurusan Teknik Informatika</b><br>
<p align="center"><b>Politeknik Negeri Indramayu</b><br>
<p align="center"><b>2018</b><br><br>
</p>
</body>
</html>


### BAB I : Pendahuluan
#### 1.1 Tujuan
Tujuan dari penulisan dokumen Softaware Requirement Specification (SRS) untuk mempermudah mengembangkan perangkat lunak yang kami buat dan memberikan gambaran yang spesifik dari kebutuhan softaware. Spesifikasi kebutuhan tersebut termasuk dari segi perangkat lunak dan perangkat keras,untuk memberikan gambaran dan penjelasan mengenai pembuatan produk termasuk kebutuhan fungsional hingga non-fungsional, dan kebutuhan antar muka mulai dari antar muka pengguna hingga antar muka komunikasi.

#### 1.2 Lingkup
Ruang lingkup dalam membangun aplikasi yaitu Delivery online menggunakan smartphone. Aplikasi ini perlu dibuatkannya karena untuk mempermudah penjual dan pembeli dalam bertransaksi jarak jauh.

#### 1.3 Definisi, Akronim, Singkatan

Singkatan | Definisi 
| ------ | ------ |
| SRS | Merupakan singkatan dari Software Requirement Specfication |
| Webserver | Webserver sebuah software yang memberikan layanan berbasis data dan berfungsi menerima permintaan dari HTTP atau HTTPS pada klien yang dikenal dan biasanya kita kenal dengan nama web browser (Mozilla Firefox, Google Chrome) dan untuk mengirimkan kembali yang hasilnya dalam bentuk beberapa halaman web dan pada umumnya akan berbentuk dokumen HTML. |
| SPMP | Merupakan singkatan dari Software Project Management Plan. |

#### 1.4 Referensi
IEEE. IEEE Std 830-1998 Praktik yang Direkomendasikan IEEE untuk Persyaratan Perangkat Lunak
Spesifikasi. IEEE Computer Society, 1998.

#### 1.5 Overview

Pada dokumen ini memberikan penjelasan tentang gambaran umum, termasuk karakterisitik pengguna proyek ini, hardware produk, dan persyaratan fungsional seperti data siswa/guru pada instansi yag terkait yang digunakan untuk persyaratan penginputan data. Gambaran umum ini dibahasan pada bagian 2 yang terdiri dari prespektif produk,antarmuka sistem, antarmuka pengguna,antarmuka perangkat keras,antarmuka perangkat lunak sampe anatrmuka komunikasi. Hal ini juga dapat memberikan suatu kebutuhan yang terdapat pada aplikasi Ayo Mangan!.

### BAB II : Gambaran Umum

#### 2.1 Perspektif produk
Produk yang dirancang merupakan sebuah perangkat lunak berbasis android
dimana akan dapat digunakan secara online oleh pihak-pihak berkepentingan.

#### 2.1.1 Antarmuka sistem
<div style="text-align:center"><img src="http://i66.tinypic.com/1z4g5zb.png"/></div>

#### 2.1.2 Antarmuka pengguna
#### * Kurir
<div style="text-align:center"><img src="http://i67.tinypic.com/2dh7038.png"/></div>
Sebelum Kurir memulai tracking kurir harus memilih list orderan terlebih dahulu.
<div style="text-align:center"><img src="http://i66.tinypic.com/2ngr6vd.png"/></div>
Proses tracking
<div style="text-align:center"><img src="http://i64.tinypic.com/jrvinp.png"/></div>
Setelah pesanan diterima oleh customer, kurir harus mengkonfirmasi kepada seller bahwa pesanan telah sampai/diterima.

#### * Seller
<div style="text-align:center"><img src="http://i66.tinypic.com/2ap5cj.jpg"/></div>

-	Profil toko : untuk mengetahui informasi toko, seller dapat mengedit informasi tokonya sendiri.
-	Alamat saya : alamat seller/toko
-	Produkku : menampilkan seluruh jenis makanan yg sudah di upload
-	Tambah produk baru : untuk mengupload menu baru
-	Kurirku : untuk mengecek posisi kurir.

#### * Costomer
<div style="text-align:center"><img src="http://i68.tinypic.com/4lodug.png"/></div>
Customer memilih menu makanan
<div style="text-align:center"><img src="http://i64.tinypic.com/n2hedg.png"/></div>
Setelah memilih salah satu menu, lalu customer oder jenis menu makanan
<div style="text-align:center"><img src="http://i65.tinypic.com/35c2wrl.png"/></div>
Customer memasukan jumlah orderan dan alamat orderan.

#### * Admin
<div style="text-align:center"><img src=http://i67.tinypic.com/nmhkcz.png"/></div>


#### 2.1.3 Antarmuka perangkat keras
Kebutuhan minimum perangkat keras yang dapat digunakan untuk mendukung aplikasi adalah :
- PC
- Mouse
- Keyboard
- Smartphone 

#### 2.1.4 Antarmuka perangkat lunak
- Aplikasi dapat diakses jika terhubung dengan internet dan memiliki OS android
- Webserver
Untuk Web admin dapat di akses menggunakan semua jenis browser, dan harus menggunakan akses internet untuk mengakses data pada Firebase.


#### 2.1.5 Antarmuka komunikasi
Yang dibutuhkan hanya sebuah komputer server dan satu atau
beberapa komputer client yang terhubung secara client-server dalam
lingkup jaringan Internet atau intranet berbasis protokol Transmission
Control Protocol/Internet Protocol (TCP/IP).

#### 2.1.6 Batasan-batasan Memori
- RAM yang kami gunakan adalah 8Gb, tapi untuk kapassitas minimum 4Gb
- Kapasitas minimum memori yang dibutuhkan untuk aplikasi minimal 512Mb

#### 2.1.7 Operasi-operasi
- Login melalui aplikasi, masuk sebagai customer, kurir dan seller
- Seller dapat mengupload foto makanan dan menginput data menu makanan melalui aplikasi
- Login melalui web, masuk sebagai admin untuk mengelola data seller
- Kurir dapat tracking alamat customer melalui aplikasi
- Customer dapat mengorder makanan melalui aplikasi, tracking kurir dan konfirmasi orderan telah sampai.

#### 2.1.8 Kebutuhan-kebutuhan dalam tahapan Adaptasi
Untuk promosi aplikasi ini dilakukan melalui sosial media, agar pengguna dapat mengetahui informasi aplikasi tersebut.

#### 2.2 Spesifikasi kebutuhan fungsional

2.2.1 Customer

Deskripsi :
Customer akan login terlebih dahulu kemudian memilih makanan yang akan diorder, setelah menginput data yang diperlukan maka customer dapat mengorder. setelah itu customer dapat tracking kurir untuk memastikan posisi orderan dan setelah barang sampai maka customer akan melakukan konfirmasi melalui aplikasi bahwa orderan telah sampai.

#### 2.3. Spesifikasi kebutuhan non-fungsional
-	Ganti password.
-	Tampilan layout service.
-	Lupa password.
- Edit profile.

#### 2.4 Karakteristik Pengguna
Untuk mengoperasikan aplikasi ini tidak diperlukan tingkat pendidikan tinggi, namun pengguna cukup memahami cara menggunakan smartphone dan penggunaan dalam sebuah aplikasi ini.
karakteristik pengguna dari aplikasi Ayo Mangan  adalah semua yang ingin menggunakan aplikasi ini diantaranya pedagang perumahan, maupun yang sudah memiliki tempat berjualan dan masyarakat  yang membedakan adalah pengguna yang berinteraksi dengan aplikasi yang dihubungkan dengan hak akses dan  autentifikasi sesuai aturan yang terdapat pada aplikasi ini, dimana aplikasi ini cara kerja nya ialah memesan makanan lewat online.

#### 2.5 Batasan-batasan.
Pengembangan Aplikasi pemesanan makanan berbasis mobile ini memiliki keterbatasan-keterbatasan yaitu sebagai berikut  :
-	Sistem Sistem Administrasi pemesanan makanan ini akan di buat menggunakan Android studio, MySql, PHP, dan html
-	Aplikasi bersifat android
- Pengembangan aplikasi Ayo Mangan ini akan meliputi pengelolaan data-data yang ada diadmin yang meliputi data toko, dan seller

#### 2.6 Asumsi dan ketergantungan/keterkaitan.
- Admin bisa melihat sistem secara keseluruhan dan dapat merubah data-data seller, Admin hanya mengatur data-data seller 
- Seller atau Owner bisa melihat sistem secara keseluruhan dan dapat merubah data-data tokonya sendiri
- Bagian costumer mempunyai wewenang untuk melakukan pemesanan makanan serta konfirmasi jika orderan telah sampai.

#### 2.7 kebutuhan-kebutuhan penyeimbang.

### BAB III : Kebutuhan Spesifik.

#### 3.1 External Interface Requirements

Kebutuhan akan pengelolaan/management pada suatu instansi sangatlah penting dengan menimbang beberapa aspek yang saling mendukung, pada hal ini tertuju pada pebisnis rumahan yang berdomisili di Indramayu dimana penerapan management/pengelolaan pemesanan nya sudah semestinya menggunakan komputerisasi untuk dapat memperkecil terjadinya human error pada pengerjaannya. Seller dan Customer yang bersangkutan sangatlah terbantu untuk meningkatkan efesiensi waktu dikarenakan fitur dari aplikasi ini menunjang kedua pihak antara seller dan customer untuk dapat berjual-beli jarak jauh tanpa harus face to face, dengan ini juga kedua pihak antara seller dan cutomer dapat memantau kurir yang memngantarkan orderan melalui fitur tracking di dalam aplikasi.

Kebutuhan akan pengelolaan/management pemasaran  pada suatu pembisnis di bidang kuliner sangatlah penting dengan menimbang beberapa aspek yang saling mendukung, pada hal ini tertuju pada pedagang rumahan maupun yang sudah memiliki tempat jualan/lapak dimana penerapan management/pengelolaan pemasaran sudah semestinya menggunakan komputerisasi untuk dapat menghindari  terjadinya kesalahan dalam pelayanan secara manual, pedagang rumahan sangatlah terbantu untuk meningkatkan perekonomian di era global. Selain hal demikian, management/pengelolaan pemesanan makanan yang terkomputerisasi dapat membantu masyarakat yang malas keluar rumah untuk mencari makan yang  dimana harus mendatangi rumah makan dan mengantri , sekarang bisa menggunakan cara praktis dengan cara pemesanan makanan melalui aplikasi “AYO MANGAN”

#### 3.2 Kebutuhan Non Fungsional
Dalam sistem informasi ini, kebutuhan yang mendukung kelancaran
fungsi-fungsi utama dapat didefinisikan pada Tabel 1.

|  Availability 			|  24 jam nonstop, kecuali ada maintenance / perbaikan sistem.   	|
|---------------------|-----------------------------------------------------------------|
|  Reliability 			  |  Kegagalan yang ditolerir sekitar 5%.			  	                  |
|  Ergonomy 			    |  Sistem informasi ini harus user friendly.			 	              |
|  Portability 			  |  Aplikasi ini berjalan pada platform atau sistem operasi apa    |
|  				            |  saja yang mendukung aplikasi berbasis android.		              |
|  Response 			    |  Time Tidak lebih dari 10 detik.				                        |
|  Safety				      |  Menggunakan secure socket layer dgn sertifikasi. 		          |
|  Security 				  |  Login (manajemen user) dan validasi data sangat penting  	    |
|                     |  karena menyangkut pembayaran secara online.		                |
|  Bahasa				      |  Menggunakan bahasa Indramayu, kecuali ada penambahan 	        |
|   Komunikasi			  |  Fasilitas untuk menggunakan bahasa lain selain bahasa Indonesia|


#### 3.3 Detail Persyaratan Non-Fungsional
#### 3.3.1 Struktur data logis
<div style="text-align:center"><img src=http://i67.tinypic.com/11bj66a.jpg"/></div>
  
### Entitas Data Customer
|  Data Item   |   Type   |        Deskripsi                                                            |
|--------------|----------|-----------------------------------------------------------------------------|
| Id_pembeli   | Varchar  | Sebagai identitas unik untuk membedakan antara customer-customer yg lainnya |
| No hp        | Varchar  | Nomor Hp customer                                                           |
| Nama         | Varchar  | Nama customer                                                               |
| Email        | Varchar  | Email untuk registrasi akun                                                 |
| Alamat       | Varchar  | Alamat customer                                                             |
| Keranjang    | Varchar  | Untuk menampung orderan                                                     |

#### Entitas Data Seller
|  Data Item   |   Type   |          Deskripsi                                                          |
|--------------|----------|-----------------------------------------------------------------------------|
| Id_toko      | Varchar  | Sebagai identitas untuk membedakan antara toko-toko yg lainnya, agar tidak  |
|              |          | terjadi kesamaan nama toko.                                                 |
| Id_penjual   | Varchar  | Sebagai identitas unik untuk membedakan antara seller-seller yg lainnya     |
| No_hp        | Varchar  | Nomor hp Seller                                                             |
| Nama         | Varchar  | Nama Seller                                                                 |
| Email        | Varchar  | Email untuk registrasi akun                                                 |

#### Entitas Data Admin
|   Data Item  |   Type   |         Deskripsi                                                           |
|--------------|----------|-----------------------------------------------------------------------------|
| Id_admin     | Varchar  | Sebagai identitas unik untuk membedakan antara admin-admin yg lainnya       |
| Nama         | Varchar  | Nama admin                                                                  |
| No_hp        | Varchar  | Nomor hp admin                                                              |

#### Entitas Data Kurir
|   Data Item  |   Type   |         Deskripsi                                                           |
|--------------|----------|-----------------------------------------------------------------------------|
| Id_kurir     | Varchar  | Sebagai identitas unik untuk membedakan antara kurir-kurir yg lainnya       |
| No_hp        | Varchar  | Nomor hp kurir                                                              |
| Nama         | Varchar  | Nama kurir                                                                  |
