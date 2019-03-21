<p style="text-align: center;"><strong>BAB I</strong></p>
<p style="text-align: center;"><strong>PENDAHULUAN</strong></p>
<p><strong>1.1 Tujuan</strong></p>
<p>Dokumen ini akan menyajikan deskripsi rinci tentang Aplikasi Penjualan Olahan Mangga Indramayu Berbasis Mobile (MANGOLINESHOP) yang akan dikembangkan. Dokumen akan menjelaskan mengenai spesifikasi pada aplikasi Mangolineshop seperti fitur sistem, antarmuka sistem, sistem apa yang akan dilakukan, apa saja kendala pada saat aplikasi beroperasi, dana bagaiman system akan bereaksi pada saat sedang digunakan oleh pemakai atau user.</p>
<p><strong>1.2&nbsp;Lingkup</strong></p>
<p>Dokumen ini menyediakan acuan untuk pengendalian tentang aplikasi Mangolineshop. Adapun ruang lingkup pembuatan aplikasi ini adalah berbasis mobile yang memilih beberapa fasilitas yang ada yaitu:</p>
<ol>
<li>Admin untuk mengelola data CRUD (Create, Read, Update, Delete) yang ada pada fitur- fitur aplikasi Mangolineshop seperti input produk olahan mangga, mendaftarkan akun kasir dan akun penjual, dan memonitoring laporan keuangan.</li>
<li>Kasir sebagai tempat perhitungan pada transaksi pembelian yang dilakukan oleh pelanggan dan dapat memonitoring hasil pendapatan pada hari ini.</li>
<li>Penjual sebagai wadah untuk produk olahan mangga yang di Mangolineshop tersebut agar pelanggan dapat memesan produk yang ada dan data yang dipesan akan di tampung pada chart pesanan yang akan dikonfirmasi jika jadi memesan dan dapat dibatalkan jika tidak jadi dipesan yang dilakukan oleh penjual.</li>
</ol>
<ul>
<li><strong>Definisi, akronim, singkatan</strong></li>
</ul>
<p>Adapun definisi dari dokumen tersebut adalah :</p>
<table>
<tbody>
<tr>
<td width="37">
<p>No</p>
</td>
<td width="163">
<p>Akronim</p>
</td>
<td width="266">
<p>Singkatan</p>
</td>
</tr>
<tr>
<td width="37">
<p>1.</p>
</td>
<td width="163">
<p>SPMP</p>
</td>
<td width="266">
<p>Software Project Management Plan</p>
</td>
</tr>
<tr>
<td width="37">
<p>2.</p>
</td>
<td width="163">
<p>SRS</p>
</td>
<td width="266">
<p>Software Requirements Specifications</p>
</td>
</tr>
<tr>
<td width="37">
<p>3.</p>
</td>
<td width="163">
<p>SDD</p>
</td>
<td width="266">
<p>Software Design Document</p>
</td>
</tr>
<tr>
<td width="37">
<p>4.</p>
</td>
<td width="163">
<p>DFD</p>
</td>
<td width="266">
<p>Data Flow Diagram</p>
</td>
</tr>
<tr>
<td width="37">
<p>5.</p>
</td>
<td width="163">
<p>IEEE</p>
</td>
<td width="266">
<p>International Institute of Electronic and Electrical Engineers</p>
</td>
</tr>
<tr>
<td width="37">
<p>6.</p>
</td>
<td width="163">
<p>CRUD</p>
</td>
<td width="266">
<p>Create, Read, Update, dan Delete</p>
</td>
</tr>
<tr>
<td width="37">
<p>7.</p>
</td>
<td width="163">
<p>Mangolineshop</p>
</td>
<td width="266">
<p>Aplikasi Penjualan Olahan Mangga Indramayu Berbasis Website</p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<ul>
<li><strong>Referensi</strong></li>
</ul>
<ol>
<li><em> IEEE Std 830-1998 IEEE Recommended Practice for Software Requirements Specifications.</em></li>
</ol>
<p>&nbsp;</p>
<ul>
<li><strong>Overview</strong></li>
</ul>
<p>Penulisan dokumen SRS ini dibagi menjadi beberapa bab sebagai berikut:</p>
<p><strong>BAB </strong><strong>I </strong>berisi pendahuluan, menjelaskan mengenai tujuan pembuatan dokumenSRS, lingkup, definisi (akronim, atau singkatan), referensi, dan Overview.</p>
<p><strong>BAB</strong> <strong>II </strong>menjelaskan keseluruhan deskripsi dari Aplikasi Penjualan Olahan Mangga Indramayu Berbasis Website (MANGOLINESHOP). Deskripsi umum tersebut memberikan gambaran lengkap mengenai semua fungsi yang akan dilakukan oleh sistem.</p>
<p><strong>BAB </strong><strong>III </strong>berisi penjelasan detail dari&nbsp; masing-masing kebutuhan lain yang spesifik.</p>
<p><strong>BAB </strong><strong>IV </strong>berisikan tentang uraian mengenai informasi pendukung dalam pembuatan proyek Aplikasi Aplikasi Penjualan Olahan Mangga Indramayu Berbasis Website.</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><strong>BAB II</strong></p>
<p><strong>GAMBARAN UMUM</strong></p>
<p>Aplikasi Penjualan Olahan Mangga Indramayu Berbasis Website (MANGOLINESHP) adalah salah satu jenis aplikasi perangkat lunak yang dapat digunakan untuk membantu proses penjualan olahan secara online. Selama ini pemasaran olahan mangga khas Indramayu dipasarkan secara konvensional yaitu dijual di toko sekitar Indramayu saja. Pemasaran olahan mangga Indramayu pun kurang berkembang karena pembeli harus datang ke toko. Oleh karena itu olahan mangga&nbsp; khas Indramayu pun yang mengenal hanya orang-orang yang singgah atau berwisata ke Indramayu saja. Sehingga kami berinisiatif untuk membuat sebuah wadah yang didalamnya terdapat lapak-lapak penjual olahan mangga dalam bentuk aplikasi berbasis website. Dibuatnya aplikasi ini kami bisa membantu pemasaran dari penjual olahan mangga Indramayu serta mempromosikan tentang keberagaman olahan mangga yang ada di Indramayu.</p>
<p><strong>&nbsp;2.1.2 Antarmuka pengguna</strong></p>
<p>Aplikasi Mangolineshop menggunakan antarmuka berbasis website. Dimana antarmuka website digunakan untuk admin dan pembeli.</p>
<p>&nbsp;<strong>2.1.3 Antarmuka perangkat keras</strong></p>
<ol style="list-style-type: lower-alpha;">
<li>Laptop</li>
<li>Processor Core i3 or higher</li>
<li>Penyimpanan(Hardisk) Minimal 4 GB free space</li>
<li>Monitor resolusi 1240 x 768 colors 5</li>
<li>Ke<strong>y</strong>board dan mouse compatible with windows</li>
</ol>
<p>&nbsp;<strong>2.1.4 Antarmuka perangkat lunak</strong></p>
<ol style="list-style-type: lower-alpha;">
<li>Windows 10 or higher</li>
<li>Laravel</li>
<li>Corel Draw X7</li>
<li>Database Mysql</li>
<li>Adobe XD</li>
<li>Sublime Text 3</li>
</ol>
<p><strong>2.1.5 Antarmuka komunikasi</strong></p>
<ol style="list-style-type: lower-alpha;">
<li>Paket Data</li>
<li>Wifi</li>
<li>Modem</li>
<li>Laptop</li>
</ol>
<p><strong>2.1.6 Batasan Memori</strong></p>
<ol style="list-style-type: lower-alpha;">
<li>RAM yang kami gunakan adalah minimal 4 gb.</li>
<li>Memori yang dibutuhkan aplikasi minimal 50 mb.</li>
</ol>
<p><strong>2.1.7 Operasi &ndash; operasi</strong></p>
<ol style="list-style-type: lower-alpha;">
<li>Input data pembeli</li>
<li>Input data penjual</li>
<li>Input data produk olahan mangga Indramayu</li>
<li>Input pesanan</li>
<li>Update data pembeli</li>
<li>Update data penjual</li>
<li>Update data produk olahan mangga</li>
<li>Tampilan hasil penjualan harian</li>
<li>Laporan hasil penjualan</li>
</ol>
<p><strong>2.1.8 Kebutuhan Adaptasi</strong></p>
<p>Kebutuhan adaptasi yang diperlukan pada saat pengembangan aplikasi dengan menggunakan fungsi update data agar memudahkan admin dalam mengkoreksi pengetikan yang salah.</p>
<p><strong>2.2 Fungsi &ndash; fungsi produk</strong></p>
<ol style="list-style-type: lower-alpha;">
<li>Memudahkan pelayanan mangolineshop dalam mencatat pesanan pembeli.</li>
<li>Memberi tahu pembeli mengenai produk olahan mangga yang habis dan yang tidak.</li>
<li>Memudahkan penjual untuk melihat pendapatan maupun laporan keuangan produk olahan mangga.</li>
</ol>
<p><strong>2.3 Karakteristik Pengguna</strong></p>
<ol style="list-style-type: lower-alpha;">
<li>Pengguna mampu membaca dan menulis.</li>
<li>Pengguna mengerti cara menggunakan PC dengan sistem operasi setidaknya windows.</li>
<li>Mengerti cara menggunakan browser pada PC.</li>
</ol>
<p><strong>2.4 Batasan &ndash; batasan</strong></p>
<ol style="list-style-type: lower-alpha;">
<li>Berjalan pada platform website</li>
<li>Sementara aplikasi ini hanya untuk produk olahan mangga Indramayu</li>
<li>Aplikasi ini tidak untuk layanan pesan antar</li>
</ol>
<p><strong>2.5 Asumsi &ndash; asumsi dan keterkaitan</strong></p>
<p>Aplikasi Mangolineshop ini dapat dikembangkan lagi dengan menambah banyak penjual, dan penambahan super admin untuk konfirmasi mangolineshop mana saja yang boleh menggunakan aplikasi ini. Sehingga aplikasi ini dapat digunakan oleh banyak penjual olahan mangga yang ingin menggunakan aplikasi ini.</p>
<p><strong>2.6 Kebutuhan &ndash; kebutuhan penyeimbang</strong></p>
<p>a. Customer Requirements</p>
<p>Customer Requirements adalah analisis yang dilakukan terhadap pembeli agar dapat mengetahui apa saja kebutuhan pembeli sehingga pengembang dapat membuat sistem yang sesuai dengan kebutuhan pembeli.</p>
<p>b. Detil Requirements</p>
<p>Detil Requirements adalah suatu analisis yang terdiri dari properti dan fungsionalitas spesifik yang diekspresikan dalam bentuk yang detail.</p>
<p>&nbsp;</p>
<p><strong>BAB III</strong></p>
<p><strong>KEBUTUHAN LAIN YANG SPESIFIK</strong></p>
<p><strong>3.1 Performa</strong></p>
<ol style="list-style-type: lower-alpha;">
<li>Respon program kurang 30 detik.</li>
<li>Berjalan pada browser apapun.</li>
</ol>
<p><strong>3.2 Keamanan Aplikasi</strong></p>
<ol style="list-style-type: lower-alpha;">
<li>Validasi username dan password harus sesuai dengan yang didaftarkan sehingga tidak terjadi kesalahan login pada aplikasi Mangolineshop.</li>
</ol>
<p>&nbsp;</p>
<p style="text-align: center;"><strong>BAB IV</strong></p>
<p style="text-align: center;"><strong>INFORMASI PENDUKUNG</strong></p>
<p>Informasi yang kami dapatkan, yaitu dari beberapa situs website, dan mitra Mangolineshop.</p>