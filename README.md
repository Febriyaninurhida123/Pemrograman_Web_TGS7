# Pemrograman_Web_TGS7
```
Febriyani Nurhida
312210222
TI.22.A2
```

## Index

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV. Febriyani Nurhida</title>
    <link rel="stylesheet" href="style.css"> <!-- External CSS -->
    <link rel="shortcut icon" type="image/png" href="gambar/1.png"> <!-- Corrected type -->
    <style>
          header {
            text-align: center;
            padding: 5px;
            background-color: #fc8ce7;
            color: #fff;
        }
        html, body {
            height: 100%;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
        }

        .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
        }

        .logo img {
            height: 100px;
            width: 100px;
            border-radius: 50%;
            border: 2px solid #fc8ce7;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        nav ul li a:hover {
            color: #ff6f61;
        }

        main {
            flex: 1;
            padding: 20px;
        }

        .welcome h1 {
            color: #fc8ce7;
        }

        .about-me {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .about-me h2 {
            color: #fc8ce7;
        }

        .social-links {
            margin-top: 20px;
        }

        .social-links img {
            width: 30px;
            height: 30px;
            margin-right: 10px;
            border-radius: 5px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #fc8ce7;
            color: #fff;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <img src="gambar/mbi.jpg" alt="Profil Picture">
            </div>
            <nav>
                <ul>
                    <li><a href="profil.html">Profilku</a></li>
                    <li><a href="kegiatan.html">Kegiatanku</a></li>
                    <li><a href="foto.html">Fotoku</a></li>
                    <li><a href="mailto:sutarmiprihatna@gmail.com">Kirim Email</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section class="welcome">
            <h1>Halo, Saya Febriyani!</h1>
            <p>Halo teman-teman! Selamat datang di websiteku yang serba pink ini, lol!</p>
            <p>Di sini, saya akan memperkenalkan diri dan berbagi berbagai kegiatan seru yang saya lakukan.</p>
            <p>Jangan lupa juga melihat koleksi foto-foto lucu dan mengirimkan email ke saya!</p>
        </section>

        <section class="about-me">
            <h2>Tentang Saya</h2>
            <p>
                Hai semua! Nama saya Febriyani Nurhida. Saya adalah seorang yang hobi masak dan juga senang berkarya di dunia digital.
                Selain itu, saya juga gemar bermain game dan menghabiskan waktu dengan keluarga dan teman-teman.
                Saya senang berbagi cerita dan pengalaman dengan semua orang, jadi jangan ragu untuk menghubungi saya!
            </p>
            <p>Anda juga bisa menemukan saya di:</p>
            <div class="social-links">
                <a href="https://youtube.com/@febriyaninurhida?si=TbGL2Y5ALt-jqYHU" target="_blank"><img src="gambar/yt.jpg" alt="YouTube Logo"></a>
                <a href="https://www.instagram.com/febriyani_1732/" target="_blank"><img src="gambar/instagram.jpg" alt="Instagram Logo"></a>
                <a href="https://www.tiktok.com/@hi_mbi?is_from_webapp=1&sender_device=pc" target="_blank"><img src="gambar/tiktok.png" alt="TikTok Logo"></a>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 CV. Febriyani. Semua hak dilindungi.</p>
    </footer>
</body>
</html>
```

### Hasil
![aku1](https://github.com/Febriyaninurhida123/Pemrograman_Web_TGS7/assets/90132092/cb8176d0-a928-4fe4-b08a-c041aa89bd58)

## Profil
```
<!DOCTYPE html>
<html>
<head>
    <title>Profil Febriyani Nurhida</title>
    <style>
        body {
            font-family: Verdana, sans-serif;
            background-color: #D7E7F3;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #fc8ce7;
            color: white;
            text-align: center;
            padding: 10px 0;
        }

        footer {
            background-color: #fc8ce7;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        h1 {
            text-align: center;
            color: white;
        }

        table {
            width: 80%;
            margin: 0 auto;
            border-collapse: collapse;
            background-color: #fff;
            margin-bottom: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        th, td {
            padding: 8px;
            text-align: left;
            border: none;
        }

        img {
            width: 200px;
            border-radius: 10px 10px 0 0;
            display: block;
            margin: 0 auto; /* Center the image */
        }

        .container {
            text-align: center;
        }

        a.button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #fc8ce7;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 20px;
        }

        a.button:hover {
            background-color: #ff6f61;
        }
    </style>
</head>
<body>
    <header>
        <h1>Profilku</h1>
        
    </header>
    <div class="container">
        <table border="0" cellpadding="8">
            
            <tr>
                <td colspan="2" align="center"><img src="gambar/mbi.jpg" alt="Profil Picture"></td>
            </tr>
            <tr>
                <td align="right"><font size="2"><b>Nama: </b></td>
                <td align="center"><font size="2">Febriyani Nurhida</td>
            </tr>
            <tr>
                <td align="right"><font size="2"><b>Tempat/Taggal lahir: </b></td>
                <td align="left"><font size="2">Solo, 17 Februari 2003</td>
            </tr>
            <tr>
                <td align="right"><font size="2"><b>Agama: </b></td>
                <td align="left"><font size="2">Alhamdulillah Islam</td>
            </tr>
            <tr>
                <td align="right"><font size="2"><b>Gol. Darah: </b></td>
                <td align="left"><font size="2">Bilang Jangan Ya</b></td>
            </tr>
            <tr>
                <td align="right"><font size="2"><b>Pekerjaan: </b></td>
                <td align="left"><font size="2">Belum Tau</td>
            </tr>
            <tr>
                <td align="right"><font size="2"><b>Hobi: </b></td>
                <td align="left"><font size="2">Sosmed an</td>
            </tr>
        </table>
        <a href="index.html" class="button">Kembali ke halaman utama</a>
    </div>
    <footer>
        <p>&copy; 2024 CV. Febriyani. Semua hak dilindungi.</p>
    </footer>
</body>
</html>
```

### Hasil
![aku2](https://github.com/Febriyaninurhida123/Pemrograman_Web_TGS7/assets/90132092/8f34c0ba-dc53-4efa-9dba-5ec9216a1e64)

## Kegiatan
```
<!DOCTYPE html>
<html>
<head>
    <title>Kegiatanku</title>
    <style>
        body {
            font-family: Verdana, sans-serif;
            background-color: white;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #fc8ce7;
            color: white;
            text-align: center;
            padding: 10px 0;
        }

        footer {
            background-color: #fc8ce7;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        h1 {
            text-align: center;
            color: white;
        }

        table {
            width: 80%;
            margin: 0 auto;
            border-collapse: collapse;
            background-color: #fff;
            margin-bottom: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Menambahkan bayangan */
        }

        th, td {
            padding: 8px;
            text-align: left; /* Mengubah alignment */
            border: none; /* Menghapus border */
        }

        img {
            width: 231px;
            height: 149px;
            display: block;
            margin: 0 auto; /* Menengahkan gambar */
            border-radius: 10px 10px 0 0; /* Melengkungkan sudut atas */
        }

        .container {
            text-align: center;
        }

        /* Tombol Kembali ke halaman utama */
        a.button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #fc8ce7;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 20px;
        }

        a.button:hover {
            background-color: #ff6f61;
        }
    </style>
</head>
<body>
    <header>
        <h1>Kegiatanku</h1>
    </header>

        <table>
            <tr>
                <td><img src="gambar/pantai.jpg" width="231" height="149"></td>
                <td bgcolor="white">
                    <font size="2">
                        <p><b>Kegiatanku Saat Pergi Berlibur Ke Pantai Bersama Keluarga</b></p>
                        <p>Aku dan keluargaku memutuskan untuk menikmati waktu lbur setelah lebaran ke Pantai. Letaknya tak jauh dari rumahku. sekitar satu jam an. aku sangat gembira.</p>
                    </font>
                </td>
            </tr>
        </table>
        <table>
            <tr>
                <td><img src="gambar/drama.jpg" width="231" height="149"></td>
                <td bgcolor="white">
                    <font size="2">
                        <p><b>Kegiatanku saat Masih SMP  Mengikuti drama berjudul Snow White</b></p>
                        <p>aku semenjak SMP sudah tertarik dengan dunia peran. Saat itu aku ditunjuk untuk memerankan salah satu karakter antagonis yaitu penihir yang memberi apel merah ke snow white.</p>
                    </font>
                </td>
            </tr>
        </table>
        <table>
            <tr>
                <td><img src="gambar/lomba.jpg" width="231" height="149"></td>
                <td bgcolor="white">
                    <font size="2">
                        <p><b>Kegiatanku saat SMP Mengikuti berbagai perlombaan salah satunya  adalah lomba puisi</b></p>
                        <p>saat itu aku masih menginjak kelas dua SMP. aku dan temanku pergi ke pendopo garut untuk mengikuti lomba bahasa ibu. aku mengikuti cabang lomba baca puisi bahasa sunda.</p>
                    </font>
                </td>
            </tr>
        </table>
        <p class="container">
            <a href="index.html" class="button">Kembali ke halaman utama</a>
        </p>
    </center>
    <footer>
        <p>&copy; 2024 CV. Febriyani. Semua hak dilindungi.</p>
    </footer>
</body>
</html>
```

### Hasil
![aku3](https://github.com/Febriyaninurhida123/Pemrograman_Web_TGS7/assets/90132092/4e75b42b-389e-48fb-b0ed-829994261963)

## Foto
```
<!DOCTYPE html>
<html>
<head>
    <title>Foto-Foto</title>
    <style>
        body {
            font-family: Verdana, sans-serif;
            background-color: white;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #fc8ce7;
            color: white;
            text-align: center;
            padding: 10px 0;
        }

        footer {
            background-color: #fc8ce7;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        h1 {
            text-align: center;
            color: white;
        }

        table {
            width: 80%;
            margin: 0 auto;
            border-collapse: collapse;
            background-color: white;
            margin-bottom: 20px;
        }

        th, td {
            padding: 8px;
            text-align: center;
            border: 1px solid black;
        }

        img {
            width: 231px;
            height: 149px;
        }

        /* Tambahkan ini untuk membuat tombol berada di tengah */
.container {
    text-align: center;
}

/* Ubah ini untuk mengatur tombol */
a.button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #fc8ce7;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 20px; /* Menambahkan jarak atas */
}

a.button:hover {
    background-color: #ff6f61;
}

    </style>
</head>
<body>
    <header>
        <h1>Fotoku</h1>
    </header>

    <table>
        <tr>
            <td><img src="gambar/jogja.jpg" alt="Foto 1"></td>
            <td><img src="gambar/flower.jpg" alt="Foto 2"></td>
        </tr>
        <tr>
            <td>Study Tour</td>
            <td>Myself</td>
        </tr>
    </table>
    <table>
        <tr>
            <td><img src="gambar/brosist.jpg" alt="Foto 3"></td>
            <td><img src="gambar/mamah.jpg" alt="Foto 4"></td>
        </tr>
        <tr>
            <td>My Brother and Sister</td>
            <td>With Mamah</td>
        </tr>
    </table>
    <div class="container">
        <a href="index.html" class="button">Kembali ke Halaman Utama</a>
    </div>
    
    <footer>
        <p>&copy; 2024 CV. Febriyani. Semua hak dilindungi.</p>
    </footer>
</body>
</html>
```

### Hasil
![aku4](https://github.com/Febriyaninurhida123/Pemrograman_Web_TGS7/assets/90132092/1588047e-2a86-430e-bf5e-80dee1bacb99)


## Email
![aku5](https://github.com/Febriyaninurhida123/Pemrograman_Web_TGS7/assets/90132092/d2731919-a2ea-49e1-9b9f-07d1db46e06c)

## Sekian, Terima Kasih
