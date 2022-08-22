# Evolusi Website (16)

Youtube

[ Gambar ]

Referensi: https://www.versionmuseum.com/

# Text Editor (18)

Notepad++

[ Gambar ]

Visual Studio Code

[ Gambar ]

Sublime Text

[ Gambar ]

Atom

[ Gambar ]

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

# (24)

### Komentar

\<!-- ini komentar dan tidak akan terbaca oleh program -->

### Struktur Tag

    <namatag atribut="nilai"> ==> <body bgcolor="yellow" id="background" class="classq">

### Atribut Global

###### Accesskey

Menentukan tombol pintas untuk mengaktifkan/memfokuskan elemen. Shortcut pada setiap browser berbeda.

<ul>
    <li>Edge, IE, Chrome, Safari, Opera 15+: [ALT] + <em>accesskey</em></li>
    <li>Opera prior version 15: [SHIFT] [ESC] + <em>accesskey</em></li>
    <li>Firefox: [ALT] [SHIFT] + <em>accesskey</em></li>
</ul>

    <a href="https://www.youtube.com/" accesskey="c">Contoh</a>

<a href="https://www.youtube.com/" accesskey="c">Contoh</a><br>

###### Class

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

###### Id

Menentukan id dari suatu elemen.

    <label for="nama">Nama:</label>
    <input id="nama">

###### Dir

Menentukan arah teks untuk konten dalam elemen.

    <element dir="ltr|rtl|auto">

###### Lang

Menentukan bahasa dari konten elemen.

    <p lang="en">This is a paragraph.</p>

###### Style

Menentukan style CSS sebaris untuk sebuah elemen.

    <h1 style="color:blue;text-align:center;">This is a header</h1>

###### Tabindex

Menentukan urutan elemen saat menekan tombol "TAB". Untuk ke element selanjutnya klik "TAB", untuk ke elemnt sebelumnya klik "SHIFT+TAB".

    <div tabindex="3">W3Schools</div><br>
    <div tabindex="2">Google</div><br>
    <div tabindex="1">Microsoft</div>

###### Title

Menentukan informasi tambahan tentang suatu elemen. Gerakkan mouse ke arah title dan tunggu hingga nilai dari title muncul.

    <p><abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
    <p title="Free Web tutorials">W3Schools.com</p>

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
