<p>1.2 Ruang Lingkup</p>
<p>Hasil dari SDD ini adalah aplikasi yang berbasis web, yang digunakan untuk membantu manajemen di PD. Sri Tanjung dalam hal:</p>
<ul>
<li>mencatat kategori dan produk yang akan ditampilkan di website.</li>
<li>mencatat laporan transaksi pembelian barang.</li>
<li>mencatat kegiatan yang dilakukan di PD. Sri Tanjung.</li>
</ul>


## 1.3 Gambaran umum dokumen
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


## 2.4 Batasan - batasan
* Aplikasi yang berjalan berfungsi sebagai : online shop, pendataan terpusat, berfungsi penghitungan otomatis

* Masalah kesulitan masih di bagian penggunaan user interface karena aplikasi digunakan secara offline dan online

* Transaksi masih menggunakan manual yaitu upload bukti pembayaran

* Aplikasi kemungkinan hanya di gunakan anatara user admin, kasir dengan agen

* Sekuriti penggunaan masih belum di ketahui kesalahanya


## 2.5 Asumsi
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