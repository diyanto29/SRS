<p align="center"><strong>SOFTWARE REQUIREMENTS SPECIFICATIONS</strong></p>
<p align="center"><strong>APLIKASI PENJUALAN </strong><strong>OLAHAN </strong></p>
<p align="center"><strong>BUAH MANGGA</strong> <strong>INDRAMAYU BERBASIS MOBILE</strong></p>
<p align="center"><strong>TIKB2293 PROYEK II </strong></p>
<p align="center">Diajukan untuk Memenuhi Persyaratan Mata Kuliah Proyek II</p>
<p align="center">&nbsp;<img src="https://github.com/diyanto29/SPMP-TIC17-5/blob/master/Gambar/POLINDRA.png?raw=true" alt="" width="512" height="512" /></p>
<p><strong>&nbsp;</strong></p>
<p align="center">Disusun Oleh:</p>
<p align="center">Dianto&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (1703077)</p>
<p align="center">Agung Yoga&nbsp;&nbsp; (1703063)</p>
<p align="center">Juan Juliyanto (1703065)</p>
<p align="center">&nbsp;</p>
<p align="center">&nbsp;</p>
<p align="center"><strong>D3 TEKNIK INFORMATIKA</strong></p>
<p align="center"><strong>POLITEKNIK NEGERI INDRAMAYU</strong></p>
<p align="center"><strong>&nbsp;</strong></p>
<p align="center">Jl. Lohbener Lama No.08, Lohbener, Indramayu, Legok, Lohbener, Kabupaten Indramayu, Jawa Barat 45252, Indonesia</p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<h1>KATA PENGANTAR</h1>
<p>&nbsp;</p>
<p style="text-align: left;">Puji syukur kehadirat Allah swt yang telah melimpahkan rahmat-Nya sehingga aplikasi ini dapat diselesaikan tepat pada waktunya dengan judul &ldquo;Aplikasi Penjualan Olahan Mangga Indramayu Berbasis Mobile &rdquo;. Aplikasi ini disusun demi memenuhi Tugas Mata Kuliah Proyek II Program Studi Teknik Informatika Diploma III Politeknik Negeri Indramayu.</p>
<p style="text-align: left;">Harapan kami, aplikasi ini menjadi salah satu media yang menarik untuk dikunjungi dan mudah dipahami oleh seluruh pengunjungnya. Akhirnya penyusun mengucapkan banyak terima kasih, khususnya kepada:</p>
<ol style="text-align: left;">
<li>Ibu Munengsih Sari Bunga, S.Kom., M.Eng selaku Ketua Jurusan Teknik Informatika Politeknik Negeri Indramayu.</li>
<li>Bapak Adi Suheryadi S.ST., M.Kom., selaku dosen wali kelas D3TI.2C dan dosen pembimbing I.</li>
<li>Bapak Eka Ismantohadi, S.Kom.,M.Eng selaku dosen pembimbing II.</li>
<li>Bapak Kurnia Adi Cahyanto, S.T.,M.Kom selaku dosen pembimbing III.</li>
<li>Orang tua dan keluarga yang selalu memberikan dukungan kepada saya baik itu moril maupun materil.</li>
<li>Rekan-rekan D3TI.2C, yang selalu memberikan keceriaan disetiap harinya sehingga saya tidak merasa terbebani dengan adanya tugas ini.</li>
</ol>
<p style="text-align: left;">Penyusun mengharapkan saran-saran dari para pembaca sebagai masukan yang berguna bagi penyempurnaan aplikasi ini. Semoga aplikasi ini bermanfaat bagi kita semua.</p>
<p style="text-align: left;"><br /> <br /> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Indramayu, 10 Februari 2019<br /> <br /> <br /> <br /> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Penulis</p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>RINGKASAN </strong></p>
<p>Aplikasi Penjualan Olahan Mangga Indramayu Berbasis Mobile (MANGOLINESHP) adalah salah satu jenis aplikasi perangkat lunak yang dapat digunakan untuk membantu proses penjualan olahan secara online. Selama ini pemasaran olahan mangga khas Indramayu dipasarkan secara konvensional yaitu dijual di toko sekitar Indramayu saja. Pemasaran olahan mangga Indramayu pun kurang berkembang karena pembeli harus datang ke toko. Oleh karena itu olahan mangga&nbsp; khas Indramayu pun yang mengenal hanya orang-orang yang singgah atau berwisata ke Indramayu saja. Sehingga kami berinisiatif untuk membuat sebuah wadah yang didalamnya terdapat lapak-lapak penjual olahan mangga dalam bentuk aplikasi berbasis mobile. Dibuatnya aplikasi ini kami bisa membantu pemasaran dari penjual olahan mangga Indramayu serta mempromosikan tentang keberagaman olahan mangga yang ada di Indramayu dan membantu pembeli untuk membeli olahan mangga tanpa harus datang ketoko.</p>
<p>Aplikasi Penjualan Olahan Mangga Indramayu Berbasis Mobile ini dibangun dengan menggunakan Java Android Studio dengan didukung basis data MYSQL.</p>
<p><strong>Kata kunci&nbsp;&nbsp;&nbsp;&nbsp; : </strong>Aplikasi Penjualan Mobile Android</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><strong><br /> </strong></p>
<p><strong>&nbsp;</strong></p>
<p align="center"><strong>DAFTAR ISI</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>HALAMAN JUDUL............................................................................................... i</strong></p>
<p><strong>KATA PENGANTAR.................................................................................... </strong></p>
<p><strong>RINGKASAN......................................................................................................... ii</strong></p>
<p><strong>DAFTAR ISI.......................................................................................................... v</strong></p>
<p><strong>DAFTAR TABEL................................................................................................. vi</strong></p>
<p><strong>DAFTAR GAMBAR............................................................................................ vii</strong></p>
<p><strong>BAB I </strong><strong>PENDAHULUAN</strong></p>
<ul>
<li>Gambaran Proyek..............................................................................</li>
<li>Dokument-dokumen dalam proyek........................................................... 1</li>
</ul>
<p>1.3&nbsp;&nbsp; Evolusi SPMP........................................................................................... 1</p>
<p>1.4&nbsp;&nbsp; Material Acuan.......................................................................................... 2</p>
<p>1.5&nbsp;&nbsp; Definisi dan Akronim............................................................................... 2</p>
<p>&nbsp;</p>
<p><strong>BAB II </strong><strong>ORGANISASI PROYEK</strong></p>
<p>2.1&nbsp;&nbsp; Model Proses............................................................................................. 1</p>
<p>2.2&nbsp;&nbsp; Struktur Organisasi................................................................................... 2</p>
<p>2.3&nbsp;&nbsp; Batasan dan Antarmuka Organisasi.......................................................... 2</p>
<p>2.4&nbsp;&nbsp; Lingkungan Hidup.................................................................................... 1</p>
<p>&nbsp;</p>
<p ><strong>BAB II</strong><strong>I</strong> <strong>PROSES MANAJERIAL</strong></p>
<p>3.1&nbsp;&nbsp; Tujuan dan prioritas manajemen............................................................... 1</p>
<p>3.2&nbsp;&nbsp; Asumsi-asumsi, ketergantungan/keterkaitan, dan batasan-batasan.......... 2</p>
<p>3.3&nbsp;&nbsp; Manajemen resiko..................................................................................... 2</p>
<p>3.4&nbsp;&nbsp; Mekanisme monitoring dan kontroling..................................................... 1</p>
<p>3.5&nbsp;&nbsp; Perencanaan staf........................................................................................ 1</p>
<p>&nbsp;</p>
<p><strong>BAB I</strong><strong>V</strong> <strong>PROSES TEKNIS</strong></p>
<p>4.1&nbsp;&nbsp; Metoda, tool, dan teknik........................................................................... 1</p>
<p>4.2&nbsp;&nbsp; Dokumentasi perangkat lunak................................................................... 2</p>
<p>4.3&nbsp;&nbsp; Fungsi-fungsi pendukung proyek............................................................. 2</p>
<p>&nbsp;</p>
<p><strong>BAB </strong><strong>V</strong> <strong>PAKET PEKERJAAN</strong></p>
<p>5.1&nbsp;&nbsp; Mekanisme Monitoring dan Kontroling......................................................... 1</p>
<p>5.2&nbsp;&nbsp; Ketergantungan dan Keterkaitan............................................................... 2</p>
<p>5.3&nbsp;&nbsp; Kebutuhan Sumber Daya.............................................................................. 2</p>
<p>5.4&nbsp;&nbsp; Alokasi budget dan sumber daya................................................................... 1</p>
<p>5.5&nbsp;&nbsp; Ketergantungan dan Keterkaitan............................................................... 2</p>
<p>5.3&nbsp;&nbsp; Jadwal........................................................................................................ 2</p>
<p><strong>BAB </strong><strong>VI</strong> <strong>PENUTUP</strong></p>
<p>6.1&nbsp;&nbsp; Kesimpulan................................................................................................. 1</p>
<p>6.2&nbsp;&nbsp; Saran......................................................................................................... 2</p>
<p><strong>BAB VII REFERNSI</strong></p>
<p><strong>BAB VIII LAMPIRAN</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p>&nbsp;</p>
<p><strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>DAFTAR TABEL</strong></p>
<p><strong><br /> </strong></p>
<p><strong>DAFTAR GAMBAR</strong></p>
<p><strong><br /> </strong></p>
<p><strong>&nbsp;</strong></p>
<p align="center"><strong>BAB I</strong></p>
<p align="center"><strong>PENDAHULUAN</strong></p>
<p><strong>&nbsp;</strong></p>
<ul>
<li><strong>Tujuan</strong></li>
</ul>
<p>Dokumen ini akan menyajikan deskripsi rinci tentang Aplikasi Penjualan Olahan Mangga Indramayu Berbasis Mobile (MANGOLINESHP) yang akan dikembangkan. Dokumen akan menjelaskan mengenai spesifikasi pada aplikasi Mangolineshop seperti fitur sistem, antarmuka sistem, sistem apa yang akan dilakukan, apa saja kendala pada saat aplikasi beroperasi, dana bagaiman system akan bereaksi pada saat sedang digunakan oleh pemakai atau user.</p>
<p>&nbsp;</p>
<ul>
<li><strong>Lingkup</strong></li>
</ul>
<p>Dokumen ini menyediakan acuan untuk pengendalian tentang aplikasi Mangolineshop. Adapun ruang lingkup pembuatan aplikasi ini adalah berbasis mobile yang memilih beberapa fasilitas yang ada yaitu:</p>
<ol>
<li>Kasir sebagai tempat perhitungan pada transaksi pembelian yang dilakukan oleh pelanggan dan dapat memonitoring hasil pendapatan pada hari ini.</li>
<li>Penjual sebagai wadah untuk produk olahan mangga yang di Mangolineshop tersebut agar pelanggan dapat memesan produk yang ada dan data yang dipesan akan di tampung pada chart pesanan yang akan dikonfirmasi jika jadi memesan dan dapat dibatalkan jika tidak jadi dipesan yang dilakukan oleh penjual.</li>
<li>Pembeli sebagai orang yang membeli produk yang tersedia didalam aplikasi mangoline ini, yang membantu dalam proses pembelian dan pemlihan produk olahan mangga yang kita inginkan.</li>
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
<p>Aplikasi Penjualan Olahan Mangga Indramayu Berbasis Mobile</p>
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
<p><strong>BAB</strong> <strong>II </strong>menjelaskan keseluruhan deskripsi dari Aplikasi Penjualan Olahan Mangga Indramayu Berbasis Mobile (MANGOLINESHOP). Deskripsi umum tersebut memberikan gambaran lengkap mengenai semua fungsi yang akan dilakukan oleh sistem.</p>
<p><strong>BAB </strong><strong>III </strong>berisi penjelasan detail dari&nbsp; masing-masing kebutuhan lain yang spesifik.</p>
<p><strong>BAB </strong><strong>IV </strong>berisikan tentang uraian mengenai informasi pendukung dalam pembuatan proyek Aplikasi Aplikasi Penjualan Olahan Mangga Indramayu Berbasis Mobile.</p>
<p>&nbsp;</p>
<p>&nbsp;</p>