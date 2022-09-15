# CSS BOX MODEL (56-61)
Di dalam CSS, apabila berbicara mengenai desain dan layout (tata letak) maka kita dapat menggunakan Box Model. Box Model ini pada dasarnya merupakan kotak yang membungkus setiap elemen HTML. Coba perhatikan gambar di bawah ini:<br><br>

<img src="https://drive.google.com/uc?export=view&id=1-88ZyQ4Ewfn0BvwM8gIR_MNq39IgxG3w" alt="css-box-model"><br>

Berikut merupakan penjelasan setiap bagiannya:

<ul>
<li> <b> Margin </b> : Area transparan di sekitar kotak (di luar border)

<li> <b> Padding </b> : Area transparan di dalam kotak (antara content dan border)

<li> <b> Border </b> : Batas di sekeliling content dan padding

<li> <b> Content </b> : Konten sebenarnya di dalam box, bisa berupa teks atau gambar
</ul>


### Margin
Margin memiliki beberapa property sebagai berikut:
<ul>
<li> margin-top : untuk mengatur margin atas
<li> margin-bottom : untuk mengatur margin bawah
<li> margin-right : untuk mengatur margin right
<li> margin-left : untuk mengatur margin left
<li> margin : untuk mengatur margin atas, kanan, bawah, kiri
</ul>


Sedangkan nilai yang dapat digunakan dalam margin:<br>
1. <b>auto</b> : Memberikan ukuran margin secara otomatis.</li>
    ```css
    margin-top: auto;
    ```

2. <b>ukuran</b> :  Menggunakan angka dengan diakhiri satuan tertentu (px, pt, cm, dst). Dapat bernilai negatif.
    ```css
    margin-left: 20px;
    ```
3. <b>persentase</b> : Mengatur margin dengan perhitungan persentase
    ```css
    margin-right: 5%;
    ```

### Padding
Padding memiliki beberapa property sebagai berikut:
<ul>
<li> padding-top : untuk mengatur padding atas
<li> padding-bottom : untuk mengatur padding bawah
<li> padding-right : untuk mengatur padding right
<li> padding-left : untuk mengatur padding left
<li> padding : untuk mengatur padding atas, kanan, bawah, kiri
</ul>


Sedangkan nilai yang dapat digunakan dalam padding <br>

1. <b>ukuran</b> :  Menggunakan angka dengan diakhiri satuan tertentu (px, pt, cm, dst)
    ```css
    padding-left: 20px;
    ```
2. <b>persentase</b> : Mengatur padding dengan perhitungan persentase
    ```css
    padding-right: 5%;
    ```


### Border
border memiliki beberapa property sebagai berikut:
<ul>
<li> border-top : untuk mengatur border atas
<li> border-bottom : untuk mengatur border bawah
<li> border-right : untuk mengatur border right
<li> border-left : untuk mengatur border left
<li> border : untuk mengatur border atas, kanan, bawah, kiri
</ul>


Terdapat beberapa style pada border, berikut merupakan contohnya:
- dotted - Border titik-titik
- dashed - Border putus-putus
- solid - Border solid
- none - Tidak ada border
- hidden - Border tersembunyi


# CSS FLOAT(62)
Float merupakan properti pada CSS untuk mengatur posisi sebuah elemen. Sebuah elemen dapat dipaksa untuk berada di sebelah kiri atau kanan dari parent/pembungkusnya dengan menggunakan properti ini.

### Text Wrapping
Membuat teks mengelilingi gambar / elemen lain<br>

### Image Gallery
Membuat serangkaian gambar menjadi galeri<br>

### Multi-column Layout
Membuat halaman memiliki beberapa kolom


# CSS POSITION (63-65)
Properti posisi menentukan jenis metode penentuan posisi yang digunakan untuk suatu elemen.
Terdapat 5 posisi berbeda
- static
- relative
- absolute
- fixed

### position: static;
Secara default, elemen HTML memiliki posisi static. Posisi ini tidak terpengaruh oleh properti top, right, bottom, left.


# Tailwind (66-69)


