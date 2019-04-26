## BAB I
**PENDAHULUAN** <br>
&emsp;**1.1.**	**Tujuan**<br>
&emsp;&emsp;Tujuan pembuatan SDD (Software Design Description) ini adalah untuk menjelaskan langkah langkah desain dan proses-proses dalam pembuatan sistem aplikasi yang akan diterapkan pada Aplikasi Pendataan Terpusat dan Informasi Produk Usaha Kerupuk Indramayu PD. Sri Tanjung dan juga memberi definisi kebutuhan untuk sistem, spesifikasi kebutuhan fungsional.<br>
&emsp;&emsp;Fungsi utama dari Aplikasi ini adalah menyediakan informasi barang di jaringan Internet, yang dapat diakses oleh Public dan Member, mempermudah perusahaan dalam merekap laporan keuangan, sarana perhitungan kasir pada perusahaan serta dapat digunakan juga sebagai sarana transaksi pembelian barang oleh Member yang sudah terdaftar.<br>
&emsp;&emsp;Secara ringkas fungsi aplikasi ini dapat dituliskan sebagai berikut:<br>
&emsp;&emsp;&emsp;1.	Admin dapat menginputkan fitur kategori kerupuk, profil dari perusahaan dan kegiatan yang berlangsung diperusahaan dagang Sri Tanjung tersebut sehingga dapat dilihat oleh user.<br>
&emsp;&emsp;&emsp;2.	Admin dapat melihat rekap laporan transaksi yang dilakukan oleh kasir.<br>
&emsp;&emsp;&emsp;3.	Aplikasi kasir harus mendaftar terlebih dahulu di admin perushaan.<br>
&emsp;&emsp;&emsp;4.	Pada halaman website, setelah kita melakukan login maka aplikasi tersebut akan memberikan detail daftar olahan kerupuk, harga dari kerupuk dan ukuran dari masing-masing kemasan kerupuk.<br>
&emsp;&emsp;&emsp;5.	Pembeli harus melakuakan konfirmasi pembelian terlebih dahulu setelah memilih produk olahan kerupuk yang ingin dibeli pada aplikasi website.<br>
&emsp;&emsp;&emsp;6.	Pembeli melakukan pembayaran setelah konfirmasi pemesanan menu – menu yang dibeli di aplikasi kasir sebagai bukti pembayaran.<br>
&emsp;&emsp;&emsp;7.	Apliaksi kasir login, kemudian melakukan proses perhitungan pembayaran untuk pembeli.<br>
&emsp;&emsp;&emsp;8.	Setelah melakukan transaksi kasir dapat melihat laporan pendapatan yang telah dilakukan kasir terhadap pemesanan yang dilakukan oleh pembeli. <br>

&emsp;**1.2.**	**Ruang Lingkup**<br>
<p>Hasil dari SDD ini adalah aplikasi yang berbasis web, yang digunakan untuk membantu manajemen di PD. Sri Tanjung dalam hal:</p>
<ul>
<li>mencatat kategori dan produk yang akan ditampilkan di website.</li>
<li>mencatat laporan transaksi pembelian barang.</li>
<li>mencatat kegiatan yang dilakukan di PD. Sri Tanjung.</li>
</ul>

&emsp;**1.3.**	**Gambaran umum dokumen**<br>
Penulisan dokumen ini dibagi menjadi beberapa bab sebagai berikut:

* Bab 1, 
adalah Pendahuluan yang menjelaskan mengenai tujuan perangkat lunak,
ruang lingkup, serta gambaran umum dokumen.

* Bab 2,
adalah Deskripsi Umum, yang berisi tentang gambaran umum mengenai
perspektif produk, manfaat produk, karakteristik user dan stakeholder, batasan,
serta asumsi dan ketergantungan yang digunakan.

* Bab 3,
adalah Software Design, yang menyediakan spesifikasi, kebutuhan,
antarmuka, kebutuhan fungsional dan non functional, lingkungan operasi, dan
batasan perancangan, permodelan proses, permodelan data, struktur data,
spesifikasi program dan desain interface. <br>
<br>


## BAB II
**DESKRIPSI UMUM** <br>
&emsp;**2.1.**	**Prespektif Produk**<br>
&emsp;&emsp;Produk dari SDD ini adalah sebuah aplikasi yang berbasis web, yang akan dijalankan dan berfungsi sebagai Online Store, seperti yang telah dijelaskan pada Pendahuluan. Produk ini akan dapat diakses dari browser yang berjalan pada sistem operasi Windows maupun
Linux. <br>

&emsp;**2.2.**	**Manfaat Produk**<br>
&emsp;&emsp;Manfaat yang didapat manajemen dalam menggunakan sistem atau aplikasi ini adalah:<br>
* Memudahkan proses pencatatan transaksi.
* Memudahkan pihak menajemen untuk melakukan checking dan pencatatan terhadap transaksi pembayaran dan transaksi pengiriman.
* Menyediakan informasi mcngenai kategori dan detail barang dengan lebih baik (rapi, terstruktur).
* Pencarian daftar barang, harga tiap barang dengan lebih akurat dan lengkap.
* Mempermudah proses manajemen stok barang.
* Mempercepat transaksi pembelian maupun transaksi pengiriman.


&emsp;**2.3.**	**Prespektif Produk dan Stakeholder**<br>
<p>User yang terlibat adalah sebagai berikut:</p>
<ul>
<li>Admin</li>
<li>Kasir</li>
<li>User</li>
</ul>

&emsp;**2.4.**	**Batasan-batasan**<br>
* Aplikasi yang berjalan berfungsi sebagai : online shop, pendataan terpusat, berfungsi penghitungan otomatis

* Masalah kesulitan masih di bagian penggunaan user interface karena aplikasi digunakan secara offline dan online

* Transaksi masih menggunakan manual yaitu upload bukti pembayaran

* Aplikasi kemungkinan hanya di gunakan anatara user admin, kasir dengan agen

* Sekuriti penggunaan masih belum di ketahui kesalahanya


&emsp;**2.5.**	**Asumsi**<br>
* Public atau Member dalam mengunakan Aplikasi pengolahan data ini dianggap sudah paham,
dapat mengoperasikan komputer serta dapat melakukan navigasi atau browsing
dengan benar. 

* Setiap Member mempunyai login dan password, dan tidak ada pertukaran
password antar member. 

* Sudah tersedia sarana koneksi ke Internet, sarana jaringan komputer, dan sarana
penunjang jaringan lainnya.
<br>
<br>

## BAB III
**SOFTWARE DESIGN** <br>

&emsp;**3.1.**	**Kebutuhan Fungsional**<br>
&emsp;&emsp;Kebutuhan fungsional (Functional Requirements) ini adalah kebutuhan utama yang diharapkan dari sistem ini, yang terkait langsung dengan sistem ini. Kebutuhan fungsional dari sistem ini adalah sebagai berikut: <br>
1. Pencatatan Kategori dan Produk Barang
2. Transaksi Pembelian Online
3. Manajemen Stok Barang
4. Pencatatan Pembayaran dan Pengiriman <br>
&emsp;&emsp;**3.1.1.**	**Spesifikasi yang diharapkan pada Kategori dan Produk Barang:**<br>
* Sistem harus dapat mencatat, menambah dan menghapus kategori barang
* Setiap kategori barang mempunyai satu atau lebih produk barang.
* Satu barang hanya dapat didefinisikan dalam satu kategori.
* Produk barang dapat disertai foto thumbnail, harga, dan spesifikasi detailnya. <br>
&emsp;&emsp;**3.1.2.**	**Spesifikasi yang diharapkan pada Transaksi Pembelian Online:**<br>
* Member harus dapat membeli produk secara online dengan memasukkan barang
yang dibeli kedalam keranjang belanja (shoping cart)
* Member harus dapat mengetahui jumlah yang harus dibayarkan ditambah dengan biaya pengiriman yang sudah ditentukan.
* Penetapan biaya pengiriman ditentukan dengan sederhana (ditampilkan tabel
biaya kirim sederhana) <br>
&emsp;&emsp;**3.1.3.**	**Spesifikasi yang diharapkan pada Manajemen Stock Barang:**<br>
* Sistem harus dapat mengurangi jumlah stok barang atas barang yang sudah
dikirimkan ke pembeli.
* Penambahan atau retur stock dilakukan oleh administrator dengan cara sederhana dengan mengupdata data jumlah stock pada tabel produk. <br>
&emsp;&emsp;**3.1.4.**	**Spesifikasi yang diharapkan pada Pencatatan Pembayaran dan Pengiriman:**<br>
* Sistem harus dapat melakukan pencatatan pembayaran atas pembelian, dengan
asumsi dilakukan oleh administrator setelah melakukan check saldo secara
manual.
* Sistem harus dapat melakukan pencatatan pengiriman barang atas pembelian,
dengan asumsi dilakukan oleh administrator setelah menerima tanda bukti
pengiriman (delivery order) secara manual dari pihak expedisi. <br>

&emsp;**3.2.**	**Kebutuhan Non Fungsional**<br>
<p>Kebutuhan yang mendukung kelancaran sistem ini didefinisikan sebagai berikut:</p>
<ul>
<li>Availability: online 24 jam, dengan asumsi koneksi Internet dan jaringan berjalan normal</li>
<li>Reliability: sistem data reliabel berhubungan dengan jumlah stock atau keberadaan stock barang.</li>
<li>Ergonomy: user friendly dengan memperhatikan hal yang berhubungan dengan Human Computer Interaction</li>
<li>Portability: dapat diakses dengan berbagai macam browser (IE, Mozilla, dll) Windows</li>
<li>Memory: Minimum memory untuk server aplikasi 1 Gb, untuk client browser 256 MB</li>
<li>Response time: tidak terukur</li>
<li>Security: Login dan validasi password</li>
</ul>

&emsp;**3.3.**	**Kebutuhan Antarmuka (interface)**<br>
&emsp;&emsp;Antarmuka dalam penerapan aplikasi dibagi menjadi dua, yaitu: <br>
1. Hardware Interface : adalah kebutuhan perangkat keras yang harus dipenuhi untuk implementasi sistem online store:
* Web Server
* Database Server
2. Software Interface: kebutuhan software untuk implementasi sistem online store:
* Apache
* PHP
* MSSQL atau Laragon <br>

&emsp;**3.5.**	**Batasan Perancangan**<br>
<p>Perancangan sistem pada PD. Sri Tanjung ini adalah berbasi web, dan bahasa pemrograman dilakukan dengan menggunakan bahasa pemrograman Html, Css, PHP dan Java.</p>