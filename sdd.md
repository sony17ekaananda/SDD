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
&emsp;&emsp;&emsp;8.	Setelah melakukan transaksi kasir dapat melihat laporan pendapatan yang telah dilakukan kasir terhadap pemesanan yang dilakukan oleh pembeli. <br> <br>



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
spesifikasi program dan desain interface.
<p>2.3 Karakteristik User</p>
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

<p>3.2 Kebutuhan Non Fungsional</p>
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
<p>3.5 Batasan Perancangan</p>
<p>Perancangan sistem pada PD. Sri Tanjung ini adalah berbasi web, dan bahasa pemrograman dilakukan dengan menggunakan bahasa pemrograman Html, Css, PHP dan Java.</p>