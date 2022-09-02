# Teknologi Informasi (4-8)

<ul type="disc">
    <li>Software Development</li>
    <ul type="circle">
        <li>Apple Development</li>
        <li>Web Development</li>
        <ul type="square">
            <li>Front-End</li>
            <li>Fullstack</li>
            <li>Back-End</li>
            <li>Dev Ops</li>
        </ul>
        <li>Android Development</li>
        <li>Games Development</li>
        <li>Dekstop Development</li>
        <li>Embeded Development</li>
        <li>Cloud Development</li>
    </ul>
    <li>Games</li>
    <li>Keamanan Siber</li>
    <li>Sistem Informasi</li>
    <li>Bahasa Pemograman</li>
    <li>Jaringan Komputer</li>
    <li>Multimedia</li>
    <li>Algoritma & Teori</li>
    <li>UI & UX</li>
    <li>Internet of Things</li>
    <li>Data Scientist</li>
    <li>Kecerdasan Buatan (AI)</li>
</ul>

# HTML CSS & JS (15)

### HTML (Hyper Text Markup Language)

HTML adalah bahasa markup yang digunakan untuk membuat Halaman web. HTML adalah markup yang digunakan untuk mendefinisikan struktur halaman web. Seperti misalnya membuat elemen paragraf, gambar, link dan lain sebagainya. HTML tersusun atas elemen-elemen HTML. Elemen html didefinisikan dengan tag-tag HTML.

### CSS (Cascading Style Sheet)

CSS adalah bahasa yang digunakan untuk mengatur tampilan elemen-elemen HTML. Dengan CSS, kita dapat memberikan warna background, border, mengatur posisi elemen, ukuran font dan lain sebagainya.

### JS (JavaScript)

Javascript adalah bahasa pemrograman (berjalan pada web browser) yang digunakan untuk membuat halaman web yang lebih interaktif. Beberapa fungsi yang bisa anda tambahkan menggunakan Javascript seperti misalnya menampilkan elemen tertentu hanya pada browser tertentu saja, membuat fitur yang memungkinkan pengguna untuk dapat menyesuaikan ukuran font pada blog, dan lain sebagainya.

# Evolusi Website (16)

#### Youtube

##### 2005

<img src="https://www.versionmuseum.com/images/websites/youtube-website/webp/youtube-website%5E2005%5Ehomepage.webp" alt="Gambar-Youtube-2005" title="Gambar-Youtube-2005" width="700">

##### 2012

<img src="https://www.versionmuseum.com/images/websites/youtube-website/webp/youtube-website%5E2012%5Ehomepage.webp" alt="Gambar-Youtube-2005" title="Gambar-Youtube-2005" width="700">

##### 2019

<img src="https://www.versionmuseum.com/images/websites/youtube-website/webp/youtube-website%5E2019%5Ehomepage.webp" alt="Gambar-Youtube-2005" title="Gambar-Youtube-2005" width="700">

Referensi: https://www.versionmuseum.com/

# Text Editor (18)

Notepad++

<img src="https://notepad-plus-plus.org/images/logo.svg" alt="Gambar-Youtube-2005" title="Gambar-Youtube-2005" width="200">

Visual Studio Code

<img src="https://storage.googleapis.com/kotakode-prod-public/images/8b5b4ffa-a442-40b0-8e98-01a8c967a1bf-vscode.png" alt="Gambar-Youtube-2005" title="Gambar-Youtube-2005" width="200">

Sublime Text

<img src="https://cdn.worldvectorlogo.com/logos/sublime-text.svg" alt="Gambar-Youtube-2005" title="Gambar-Youtube-2005" width="200">

Atom

<img src="https://www.nesabamedia.com/wp-content/uploads/2019/08/Atom-Logo-1.png" alt="Gambar-Youtube-2005" title="Gambar-Youtube-2005" width="200">

# Kerangka HTML (19)

    <!DOCTYPE html>

DOCTYPE adalah suatu deklerasi yang digunakan untuk mengidentifikasi jenis dokumen HTML yang digunakan sehingga browser dapat menentukan bagaimana memperlakukan kode tersebut.
DOCTYPE sendiri berguna untuk memberitahu programer, HTML versi berapa yang digunakan dan juga membantu programer untuk dapat menggunakan tag-tag HTML dengan benar.

    <html>

Tag ini merupakan sebagai tanda awal dari sebuah dokumen html. jadi sebelem kita memasukan head, title, dan body kita harus memasukan tag html terlebih dahulu.

    <head>

HEAD berisi informasi-informasi yang menjelaskan tentang dokumen HTML,seperti judul dokumen, basis URL suatu dokumen, hubungan antar dokumen dalam HTML, dan indeks suatu dokumen.

    <title>

Meskipun tag ini termasuk kepada bagian tag HEAD tetapi TITLE merupakan bagian dari kerangka html karena untuk membuat judul pada suatu halaman HTML kita membutuhkannya. TITLE bukan bagian dari teks dokumen dan tidak boleh mengandung tag-tag lain. TITLE biasanya ditampilkan oleh browser pada title bar dari jendela browser dan berfungsi sebagai label untuk jendela dari browser tersebut.

    <body>

Tag yang merupakan init dari kerangka html ini merupakan elemen terbesar di dalam dokumen HTML. Bagian ini bukan hanya untuk memasukkan informasi atau isi dokumen tetapi juga bisa memberikan format tertentu pada suatu kelompok teks, membuat tabel, form dan lain sebagainya.

Contoh

    <!DOCTYPE html>

    <html>

    <head>

        <title> Judul Halaman </title>

    </head>

    <body> Isi Halaman </body>

    </html>

# Bagian `<head>`

### Judul Halaman

Tag `<title>` mendefinisikan judul dokumen. Judul harus berupa teks saja, dan ditampilkan di bilah judul browser atau di tab halaman.

    <title></title>

### CSS

Atribut HTML `<style>` digunakan untuk menambahkan CSS ke elemen, seperti warna, font, ukuran, dan lainnya.

    <style></style>

### JavaScript

Tag `<script>` digunakan untuk menyematkan script client-side. Tag `<script>` juga dapat berisi pernyataan skrip, atau menunjuk ke file skrip eksternal melalui atribut src.

    <script></script>

### Meta

Tag `<meta>` mendefinisikan metadata tentang dokumen HTML.

Tag `<meta>` selalu masuk ke dalam elemen `<head>`, dan biasanya digunakan untuk menentukan set karakter, deskripsi halaman, kata kunci, penulis dokumen, dan pengaturan viewport.

    <meta></meta>

# Meta(21)

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="belajar buat web">
  <meta name="keywords" content="HTML, CSS, JavaScript">
  <meta name="author" content="Kurnia Cahya">
</head>

# Bagian <body> (22)

### Text

    <h1>, <h2>, <h3>, <h4>, <h5>, <h6>, <p>, ...

### Pendukung / Atribut Text

    <br>, <hr>, <em>, <strong>, ...

### Gambar

    <img>

### Hyperlink

    <a>

### List (Bullets & Numbering)

    <ul>, <ol>, <li>, <dl>, <dt>, <dd>

# Bagian <body> (23)

### Tabel

    <table>, <thead>, <tbody>, ...

### Form

    <form>, <input>, <select>, <button>, ...

### Script

    <script>

### Object

    <object>

### Grouping

    <div>, <span>

# (24)

### Komentar

\<!-- ini komentar dan tidak akan terbaca oleh program -->

### Struktur Tag

    <namatag atribut="nilai"> ==> <body bgcolor="yellow" id="background" class="classq">

### Atribut Global

#### Accesskey

Menentukan tombol pintas untuk mengaktifkan/memfokuskan elemen. Shortcut pada setiap browser berbeda.

<ul>
    <li>Edge, IE, Chrome, Safari, Opera 15+: [ALT] + <em>accesskey</em></li>
    <li>Opera prior version 15: [SHIFT] [ESC] + <em>accesskey</em></li>
    <li>Firefox: [ALT] [SHIFT] + <em>accesskey</em></li>
</ul>

    <a href="https://www.youtube.com/" accesskey="c">Youtube</a>

<a href="https://www.youtube.com/" accesskey="c" target="_blank">Youtube</a>

#### Class

Menentukan satu atau lebih nama kelas untuk suatu elemen (mengacu pada class dalam tag style).

    <!DOCTYPE html>
    <html>
    <head>
        <style>
            h1.intro {
            color: blue;
            }

            p.important {
            color: green;
            }
        </style>
    </head>
    <body>
        <h1 class="intro">Header 1</h1>
        <p>Paragraf.</p>
        <p class="important">Contoh isi paragraf</p>
    </body>
    </html>

#### Id

Menentukan id dari suatu elemen.

    <label for="nama">Nama:</label>
    <input id="nama">

#### Dir

Menentukan arah teks untuk konten dalam elemen.

    <element dir="ltr|rtl|auto">

#### Lang

Menentukan bahasa dari konten elemen.

    <p lang="en">This is a paragraph.</p>

#### Style

Menentukan style CSS sebaris untuk sebuah elemen.

    <h1 style="color:blue;text-align:center;">This is a header</h1>

#### Tabindex

Menentukan urutan elemen saat menekan tombol "TAB". Untuk ke element selanjutnya klik "TAB", untuk ke elemnt sebelumnya klik "SHIFT+TAB".

    <div tabindex="3">W3Schools</div><br>
    <div tabindex="2">Google</div><br>
    <div tabindex="1">Microsoft</div>

#### Title

Menentukan informasi tambahan tentang suatu elemen. Gerakkan mouse ke arah title dan tunggu hingga nilai dari title muncul.

    <p><abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
    <p title="Free Web tutorials">W3Schools.com</p>

# Text `<html>` (26)

#### Bold

    <b></b>
    <strong></strong>

#### Italic

    <i></i>
    <em></em>

#### Underline

    <u></u>
    <ins></ins>

# Heading `<html>` (27)

    <h1>ini adalah heading 1</h1>
    <h2>ini adalah heading 2</h2>
    <h3>ini adalah heading 3</h3>
    <h4>ini adalah heading 4</h4>
    <h5>ini adalah heading 5</h5>
    <h6>ini adalah heading 6</h6>

# List(28)

Ordered List: list yang memiliki urutan. Tipe list terdiri dari A, I, 1.

    <ol type="A">
        <li>Item 1</li>
        <li>Item 2</li>
    </ol>

<ol type="A">
    <li>Item 1</li>
    <li>Item 2</li>
</ol>

Unordered List: list yang tidak memiliki urutan. Tipe list terdiri dari circle, square, disc.

    <ul type="circle">
        <li>Item 1</li>
        <li>Item 2</li>
    </ul>

<ul type="circle">
    <li>Item 1</li>
    <li>Item 2</li>
</ul>

# Hyperlink(29)

Hyperlink merupakan salah satu tag HTML yang mampu membantu user menuju informasi lainnya.

    <a href="" target="">Hyperlink!</a>

External Link = `<a href="https://www.youtube.com/">Youtube!</a>`

Internal Link = `<a href="../page/admin.html">Admin Page!</a>`

Page Anchor = `<a href="#about">About!</a>`

Contoh perbedaan tiap nilai pada atribut `target`: https://syedmaqsoodblr.github.io/Stack-Overflow-Answers/HTML%20Frames/iframe.html

# Image(29)

Img merupakan salah satu tag HTML untuk menyematkan gambar di halaman web.

    <img src="image.jpg" alt="Kalimat Alternatif" title="Judul" width="500" height="333">

Nilai pada atribut `src` berupa path local atau link ke gambar yang dituju. Nilai pada atribut `alt` merupakan kalimat pengganti ketika gambar yang dituju tidak ada. Nilai pada atribut `title` akan muncul ketika kursor diarahkan ke gambar. Sedangkan `height` dan `width` merupakan ukuran gambar.
