### Cara Menempatkan CSS
terdapat 3 cara untuk menempatkan CSS untuk HTML kita, antara lain:
1. Embed / Internal <br>
Embed atau internal CSS ini dilakukan dengan menambahkan tag `<style>...</style>` pada bagian `head` HTML. Contoh:
<img width="536" alt="image" src="https://user-images.githubusercontent.com/111165036/190846265-f5923704-be8e-4a88-8467-b75af96ef192.png">

2. Inline <br>
Inline dilakukan dengan menambahkan attribut `style` pada tag HTML yang ingin diberikan CSS. Contoh:
<img width="502" alt="image" src="https://user-images.githubusercontent.com/111165036/190846389-1b19fe0a-07d3-4d7c-acc6-910bcc48565b.png">

3. External <br>
Penambahan CSS pada HTML dengan cara external akan dilakukan dengan mengaitkan file `.css` kita pada file `.html` menggunakan tag `<link>...</link>` pada bagian `head` HTML kita. Contoh:

- isi dari `index.html`
<img width="548" alt="image" src="https://user-images.githubusercontent.com/111165036/190846434-a24435d8-7538-4e78-81b6-9c2d88753831.png">
- isi dari `style.css`
<img width="548" alt="image" src="https://user-images.githubusercontent.com/111165036/190846460-311be2bc-0bff-48a4-a48b-d83de33eac41.png">
> Dalam contoh `external` di atas kita mengaitkan file `index.html` kita pada file `style.css` yang berada pada satu folder

### Font Styling
- Font-Family
Mengatur `jenis` font yang digunakan.
```
    <p style="font-family: 'Courier New', Courier, monospace;">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
    <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
```
> Hasil:
<img width="727" alt="image" src="https://user-images.githubusercontent.com/111165036/190848002-557a35bf-2398-413d-97fa-0902da8152f6.png">
- Font-Size
Mengatur `ukuran` font. Satuan yang digunakan dalam properti ini adalah px, %, dan em.
```
    <p style="font-size: large;">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
    <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
```
> Hasil:
<img width="723" alt="image" src="https://user-images.githubusercontent.com/111165036/190848650-06351787-696f-4cf3-a839-af211f35e3e3.png">
- Font-Weight
Mengatur `ketebalan` font. Contoh value yang dapat diisi dalam properti ini adalah lighter, normal, angka 100-900, bold, dan bolder.
```
    <p style="font-weight: 700;">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
    <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
```
> Hasil:
<img width="717" alt="image" src="https://user-images.githubusercontent.com/111165036/190848159-87004e68-6d8f-466d-b003-68e1106c7cab.png">
- Font-Variant
Mengubah font menjadi `small-caps`. Contoh value dalam properti ini adalah normal dan small-caps
```
    <p style="font-variant: small-caps;">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
    <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
```
> Hasil:
<img width="703" alt="image" src="https://user-images.githubusercontent.com/111165036/190848246-058a5569-0a79-47b1-b67b-de865cbd8852.png">
- Font-Style
Mengubah font menjadi bercetak `miring`. Contoh value lain yang dapat diisi dalam properti ini adalah normal dan oblique.
```
    <p style="font-style: italic;">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
    <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
```
> Hasil:
<img width="710" alt="image" src="https://user-images.githubusercontent.com/111165036/190848277-c40c2294-779a-4fa1-b50d-93d4d172fcbf.png">
- Line Height
Mengatur `spasi` antar baris. Selain ditulis dengan angka, kita dapat juga menggunakan value normal, satuan px, dan satuan em.
```
    <p style="line-height: 4;">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
    <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
```
> Hasil:
<img width="716" alt="image" src="https://user-images.githubusercontent.com/111165036/190848303-af68510f-a745-4fdb-821b-ff53bbcb9de6.png">

### Text Styling
#### Komentar
Pemberian komentar dapat sangat bermanfaat untuk memahami kode yang kita tulis. Kita dapat dengan mudah membuat komentar dengan shortcut `ctrl`+`/`.
```
    <!-- INI JUDUL HALAMAN -->
    <title>Blog Pribadi</title>
```
#### Color
properti color digunakan untuk menspesifikkan warna teks. Terdapat 3 cara untuk menunjukkan warnanya, yakni nama warna (red, yellow, dll), hexadecimal (#ffffff, #ededed), dan RGB (rgb(0,50,175)). Contoh:
```
<h1 style="color: red;">HELLO WORLD!</h1>
```
>Hasil:
<img width="202" alt="image" src="https://user-images.githubusercontent.com/111165036/190849162-5e50841c-a5be-474b-bd1a-0358fd58e17c.png">

#### Text-Align
Digunakan untuk mengatur format paragraf / teks, seperti menjadi rata kiri, kanan, tengah, ataupun kanan-kiri. Contoh:
```
    <p style="text-align: center;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus eaque autem quas! Nam nihil ipsum reprehenderit eum eos officia unde ab, similique tenetur maiores quod odio neque nesciunt, impedit quia optio accusantium necessitatibus nisi corporis quidem deserunt laudantium. Non, ea excepturi? Illo impedit velit adipisci, eaque, ullam doloremque commodi, iure quod voluptatem provident nobis perspiciatis odit distinctio sequi itaque fugiat similique nesciunt quo architecto accus</p>
    <p style="text-align: justify;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus eaque autem quas! Nam nihil ipsum reprehenderit eum eos officia unde ab, similique tenetur maiores quod odio neque nesciunt, impedit quia optio accusantium necessitatibus nisi corporis quidem deserunt laudantium. Non, ea excepturi? Illo impedit velit adipisci, eaque, ullam doloremque commodi, iure quod voluptatem provident nobis perspiciatis odit distinctio sequi itaque fugiat similique nesciunt quo architecto accus</p>
    <p style="text-align: left;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus eaque autem quas! Nam nihil ipsum reprehenderit eum eos officia unde ab, similique tenetur maiores quod odio neque nesciunt, impedit quia optio accusantium necessitatibus nisi corporis quidem deserunt laudantium. Non, ea excepturi? Illo impedit velit adipisci, eaque, ullam doloremque commodi, iure quod voluptatem provident nobis perspiciatis odit distinctio sequi itaque fugiat similique nesciunt quo architecto accus</p>
    <p style="text-align: right;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus eaque autem quas! Nam nihil ipsum reprehenderit eum eos officia unde ab, similique tenetur maiores quod odio neque nesciunt, impedit quia optio accusantium necessitatibus nisi corporis quidem deserunt laudantium. Non, ea excepturi? Illo impedit velit adipisci, eaque, ullam doloremque commodi, iure quod voluptatem provident nobis perspiciatis odit distinctio sequi itaque fugiat similique nesciunt quo architecto accus</p>
```
>Hasil:
<img width="731" alt="image" src="https://user-images.githubusercontent.com/111165036/190849298-fbcef9c5-d290-41d1-968a-f3dacff43808.png">

#### Text-Indent
Digunakan untuk memberi indentasi pada paragraf / teks. Value dalam properti ini bisa dalam satuan px atau %.
```
    <p style="text-indent: 100px;">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
    <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
```
>Hasil:
<img width="715" alt="image" src="https://user-images.githubusercontent.com/111165036/190849525-515e19a8-f472-4fd7-b6d1-79e7ae77f213.png">

#### Text-Decoration
Mengatur dekorasi pada teks, seperti garis bawah, garis tengah, dll. Contoh:
```
    <p style="text-decoration: underline;">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
    <p style="text-decoration: line-through;">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
```
>Hasil:
<img width="718" alt="image" src="https://user-images.githubusercontent.com/111165036/190849487-a5d407ad-2b2d-479b-a983-0d5c31affb1d.png">

#### Text-Transform
Mengubah jenis huruf menjadi huruf kapital / tidak kapital
```
    <p style="text-transform: capitalize;">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
    <p style="text-transform:lowercase;">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
```
>Hasil:
<img width="728" alt="image" src="https://user-images.githubusercontent.com/111165036/190849632-e35f59d6-ed15-4b23-83bd-3f0281396abb.png">

#### Letter-Spacing
Mengatur spasi antar huruf. Properti ini dapat diisi dengan value normal ataupun angka dengan satuan px.
```
    <p style="letter-spacing: 10px;">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
    <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
```
>Hasil:
<img width="724" alt="image" src="https://user-images.githubusercontent.com/111165036/190849694-ec6da650-5e88-4780-9435-e1c0f4e25541.png">

#### Word-Spacing
Mengatur spasi antar kata. Kita dapat menggunakan value normal ataupun angka dengan satuan px, seperti contoh di bawah
```
    <p style="word-spacing: 10px;">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
    <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
```
>Hasil:
<img width="729" alt="image" src="https://user-images.githubusercontent.com/111165036/190849716-54ff82ed-fc79-4f5d-9632-2450ecc1705b.png">

### CSS Background
#### Background-Color
Mengatur warna pada background.
```
    <p style="background-color: red;">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
```
>Hasil:
<img width="728" alt="image" src="https://user-images.githubusercontent.com/111165036/190850245-100732ba-874f-48ff-aad8-f804357192c7.png">

#### Background-Image
Mengatur gambar yang akan digunakan pada background. file `background_bahan.jpg` dapat didownload pada file yang terlampir pada modul.
```
    <p style="background-image: url('background_bahan.jpg'); height: 100px;">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
```
>Hasil:
<img width="726" alt="image" src="https://user-images.githubusercontent.com/111165036/190850375-393c9c0b-6813-43ff-8a69-43422f56ae7b.png">

#### Background-Position
Mengatur posisi gambar pada background
```
    <p style="background-image: url('background_bahan.jpg'); height: 100px; background-position: center;">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
    <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
```
>Hasil:
<img width="731" alt="image" src="https://user-images.githubusercontent.com/111165036/190850428-e4db7f8b-5717-44f4-93d2-5e73a79e6b81.png">

#### Background-Repeat
Mengatur jenis pengulangan gambar pada background
```
<body  style="background-image: url('background_bahan.jpg'); height: 100px; background-position: center; background-repeat: repeat; color: white;">
    <p">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>
    <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti quae quod ipsa ipsum expedita, sunt velit veniam odio molestiae aliquam nam mollitia consequatur voluptatum, 
    </p>

    <h1 style="text-decoration: underlined;">HELLO WORLD!</h1>
</body>
```
>Hasil:
<img width="728" alt="image" src="https://user-images.githubusercontent.com/111165036/190850522-c602f739-009e-46b3-b105-39a0639e4c0d.png">

### CSS Pseudo Class
Pseudo-class di CSS digunakan untuk mendefinisikan keadaan khusus dari suatu elemen. Pseudo-class ini dapat ditulis dengan sintaks berikut: `selector:pesudo-class { property: value; }`. Terdapat banyak Pesudo-class, yakni link, hover, active, visited, dll. Contoh:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <style>
        div {
            background-color: green;
            color: white;
            padding: 25px;
            text-align: center;
        }
        div:hover {
            background-color: blue;
        }
    </style>
</head>
<body>
    <p>Arahkan mouse ke elemen div di bawah ini untuk mengubah warna backgroung:</p>
    <div>Arahkan mouse padaku</div>
</body>
</html>
```
>Hasil: Apabila mouse berada di luar area div, maka akan berwarna hijau. Sedangkan, apabila di dalam area div, maka akan berwarna biru
<img width="732" alt="image" src="https://user-images.githubusercontent.com/111165036/190851375-57765ea9-9712-4653-b36c-27134bca1ff3.png">
<img width="732" alt="image" src="https://user-images.githubusercontent.com/111165036/190851379-8684efe1-f576-49a4-b2bd-facb636f25e8.png">


### CSS Specificity
Jika ada dua atau lebih aturan CSS yang bertentangan dan mengarah ke elemen yang sama, browser akan mengikuti beberapa aturan untuk menentukan mana yang paling spesifik.

Spesifikasi bisa di anggap seperti skor/peringkat untuk menentukan style mana yang akan diterapkan ke dalam suatu elemen.
```
        h1 {
            background-color: blue;
        }
        h1 {
            background-color: red;
        }
```
> Hasil: CSS diatas mengatur background-color untuk tag h1 dengan 2 warna yang berbeda. Dalam hal ini browser akan menampilkan background-color berwarna merah
<img width="728" alt="image" src="https://user-images.githubusercontent.com/111165036/190851502-0faca1d9-8cb5-47d6-8135-5b7de0eb1a9d.png">

## BASIC LAYOUTING
### Element Block & Inline
Setiap tag pada HTML berada di dalam sebuah KOTAK. Properti display pada CSS mengatur perilaku dari kotak tersebut.
#### Display
Setiap tag pada HTML berada di dalam sebuah KOTAK. Properti display pada CSS mengatur perilaku dari kotak tersebut. Contoh value dalam properti ini antara lain:
- inline
- block
- inline-block
- none
#### Block
Tag HTML yang berjenis block element akan memisahkan diri dari tag di sekitarnya. Jadi halaman HTML akan menjadi terbagi-bagi, atau menjadi blok. Contoh tag HTML yang  berupa block antara lain:
- h1-h6
- p
- ol
- ul
- li
- dll
#### Inline
Kalau tag berjenis inline element, tidak akan membuat blok sendiri, tidak terpisah dari tag di sekitarnya. Tag jenis ini akan menyatu dengan tag yang ada di sekitarnya. Juga, tidak membuat baris baru. Contoh tag HTML yang  berupa inline antara lain:
- b
- a
- button
- textarea
- strong
- dll

### CSS Dimensi
Properti di bawah ini digunakan untuk mengatur tinggi dan lebar dari suatu elemen. Contoh:
- Width
- Height
```
<img src="background_bahan.jpg" alt="" style="width: 400px; height: 200px;">
```
> Hasil: gambar `background_bahan.jpg` akan ditampilan dengan lebar 400px dan tinggi 200px, sebagai berikut:
<img width="731" alt="image" src="https://user-images.githubusercontent.com/111165036/190851901-c0ad3a2a-62b7-4422-b826-bb3da19be2b8.png">

### CSS Overflow
Properti ini akan mengontrol apa yang akan terjadi apabila konten berukuran lebih besar dari area yang ada.
- Visible : default konten akan keluar jika tidak cukup
- Auto : akan memunculkan scroll jika dibutuhkan
- Hidden : menyembunyikan konten
- Scroll : selalu memunculkan scroll meskipun konten cukup

### CSS Box Model
Dalam CSS, design dan layouting digambarkan dalam box model
- Setiap elemen di halaman berada di dalam sebuah box (kotak)
- Bisa mengatur ukuran dan posisi kotak tersebut
- Bisa memberi warna / gambar sebagai background kotak tersebut
