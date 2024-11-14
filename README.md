<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Perpustakaan UNTAN</title>
    <link href="css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background-image: url("picture/Winners 2013.jpeg");
            background-size: cover;
            color: black;
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        h1 {
            color: blue;
            text-align: center;
            text-decoration: underline;
        }
        h2, h3, h4, h5, h6 {
            color: darkblue;
        }
        p {
            color: red;
        }
        section {
            padding: 20px;
            margin: 20px 0;
            border-radius: 5px;
        }
        .section1 {
            background-color: yellow;
        }
        .section2 {
            background-color: lightgreen;
        }
        .section3 {
            background-color: lightcoral;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: lightgray;
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <nav class="navbar navbar-default">
        <div class="container-fluid">
            <div class="navbar-header">
                <a class="navbar-brand" href="#">Perpustakaan UNTAN</a>
            </div>
            <ul class="nav navbar-nav">
                <li><a href="#home">Beranda</a></li>
                <li><a href="#pemesanan">Pemesanan Buku</a></li>
                <li><a href="#perpanjangan">Perpanjangan Buku</a></li>
                <li><a href="#tabel">Tabel Bahan Buku</a></li>
                <li><a href="#anggota">Anggota Perpustakaan</a></li>
            </ul>
        </div>
    </nav>




    <title>Contoh Halaman HTML</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h1 {
            color: #4CAF50;
        }
    </style>
</head>
<body>
    <h1>Selamat Datang Di Perpustakaan Tri anita saragih (222201027)</h1>
    <p>Perkenalkan nama Tri anita saragih ,Nim :222201027Program Studi D3 Perpustakaan Mata kuliah Pemrograman Web. Ini merupakan perpustakaan homepage pertama saya</p>

    <hr/>

    <h2>Berikut ini gambar dari Perpustakaan Untan</h2>
    <img src="https://asset-2.tstatic.net/tribunpontianakwiki/foto/bank/images/perpustakaan-universitas-tanjungpura-pontianak.jpg" >

   <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Video YouTube</title>
</head>
<body>
    <h1>Video profi Perpustakaan Untan</h1>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/Iqhk0z3SIug" frameborder="0" allowfullscreen></iframe>
</body>

    <h2>Audio</h2>
    <audio controls>
        <source src="music.mp3" type="audio/mpeg">
        <source src="music.ogg" type="audio/ogg">
        Browser Anda tidak mendukung tag audio.
    </audio>
<h2>Formulir Perpustakaan Untan</h2>
    
    <form action="#" method="post">
        <table>
            <tr>
                <th>Nama</th>
                <td><input type="text" name="nama" required></td>
            </tr>
            <tr>
                <th>NIM</th>
                <td><input type="text" name="nim" required></td>
            </tr>
            <tr>
                <th>Alamat</th>
                <td><textarea name="alamat" rows="3" required></textarea></td>
            </tr>
            <tr>
                <th>Jenis Kelamin</th>
                <td>
                    <input type="radio" name="jenis_kelamin" value="Laki-laki" required> Laki-laki
                    <input type="radio" name="jenis_kelamin" value="Perempuan" required> Perempuan
                </td>
            </tr>
            <tr>
                <th>Email</th>
                <td><input type="email" name="email" required></td>
            </tr>
            <tr>
                <th>No HP</th>
                <td><input type="text" name="no_hp" required></td>
            </tr>
            <tr>
                <th>Tempat Lahir</th>
                <td><input type="text" name="tempat_lahir" required></td>
            </tr>
            <tr>
                <th>Tanggal Lahir</th>
                <td><input type="date" name="tanggal_lahir" required></td>
            </tr>
        </table>
        <br>
        <input type="submit" value="Submit">
    </form>

</body>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabel Bahan Buku</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #4CAF50;
            color: white;
        }
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <h1>Daftar Bahan Buku</h1>
    <table>
        <thead>
            <tr>
                <th>No</th>
                <th>Judul Buku</th>
                <th>Pengarang</th>
                <th>Penerbit</th>
                <th>Tahun Terbit</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>Pemrograman Web Dasar</td>
                <td>Andi Saputra</td>
                <td>Media Press</td>
                <td>2020</td>
            </tr>
            <tr>
                <td>2</td>
                <td>Pengenalan HTML dan CSS</td>
                <td>Budi Santoso</td>
                <td>Ilmu Komputer</td>
                <td>2021</td>
            </tr>
            <tr>
                <td>3</td>
                <td>JavaScript untuk Pemula</td>
                <td>Siti Rahmawati</td>
                <td>Edu Books</td>
                <td>2019</td>
            </tr>
            <tr>
                <td>4</td>
                <td>Database dan SQL</td>
                <td>Joko Widodo</td>
                <td>Tech Press</td>
                <td>2022</td>
            </tr>
        </tbody>
    </table>
</body>
<body>
<h2>Formulir Pemesanan Buku</h2>
    
    <form action="#" method="post">
        <table>
            <tr>
                <th>Nama</th>
                <td><input type="text" name="nama" required></td>
            </tr>
            <tr>
                <th>Nomor Anggota Perpustakaan</th>
                <td><input type="text" name="nomor anggota perpustakaan" required></td>
            </tr>
            <tr>
                <th>Tanggal Pemesanan</th>
                <td><textarea name="Tanggal Pemesanan" rows="3" required></textarea></td>
            </tr>
            <tr>
                <th>Jenis Kelamin</th>
                <td>
                    <input type="radio" name="jenis_kelamin" value="Laki-laki" required> Laki-laki
                    <input type="radio" name="jenis_kelamin" value="Perempuan" required> Perempuan
                </td>
            </tr>
            <tr>
                <th>Email</th>
                <td><input type="email" name="email" required></td>
            </tr>
            <tr>
                <th>No HP</th>
                <td><input type="text" name="no_hp" required></td>
            </tr>
            <tr>
                <th>Penulis Buku</th>
                <td><input type="text" name="Penulis Buku" required></td>
            </tr>
            <tr>
                <th>No ISBN</th>
               <td><input type="text" name="no isbn" required></td>
            </tr>
             <tr>
                <th>Judul Buku Yang Dipesan</th>
                <td><input type="text" name="judul buku yang dipesan" required></td>
            </tr>
        </table>
        <br>
        <input type="submit" value="Submit">
    </form>

</body>
<h2>Formulir Perpanjangan peminjaman buku </h2>
    
    <form action="#" method="post">
        <table>
            <tr>
                <th>Nama</th>
                <td><input type="text" name="nama" required></td>
            </tr>
            <tr>
                <th>Nomor Anggota Perpustakaan</th>
                <td><input type="text" name="nomor anggota perpustakaan" required></td>
            </tr>
            <tr>
                <th>Tanggal Pemesanan</th>
                <td><textarea name="Tanggal Peminjamanan" rows="3" required></textarea></td>
            </tr>
          
            <tr>
                <th>Email</th>
                <td><input type="email" name="email" required></td>
            </tr>
            <tr>
                <th>No Telepon</th>
                <td><input type="text" name="no telepon" required></td>
            </tr>
           
            <tr>
                <th>No ISBN</th>
                <td><input type="text" name="no isbn" required></td>
            </tr>
             <tr>
                <th>Tanggal Perpanjangan Buku</th>
                <td><input type="date" name="Tanggal perpanjangan buku" required></td>
            </tr>
        </table>
        <br>
        <input type="submit" value="Submit">
    </form>
    <body>
        <h1> Pengertian HTML dan CSS </h1>
        <p>HTML adalah bahasa markup standar yang digunakan untuk membuat struktur dan konten halaman web. Dalam HTML, pengembang web mendefinisikan elemen-elemen seperti teks, gambar, tautan, formulir, dan elemen lainnya yang membentuk tampilan halaman web. HTML menggunakan tag-tag untuk menandai elemen-elemen ini sehingga peramban web tahu cara menampilkan mereka.</p>
    
        <p>CSS adalah bahasa stylesheet yang digunakan untuk mengontrol tata letak dan tampilan halaman web. Dengan CSS, Anda dapat mengatur warna, ukuran, spasi, jenis font, dan banyak properti tata letak lainnya untuk elemen-elemen HTML. Penggunaan CSS memungkinkan pemisahan antara struktur dan tata letak, sehingga HTML dapat fokus pada struktur konten, sementara CSS mengontrol cara konten tersebut ditampilkan.</p> 
 </body>       
</html>

