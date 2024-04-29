# Anatomi CSS

## Kode Program

```css

CSS

p{

color:red;

}

```

## Hasil

  
  

## Penjelasan

1. p merupakan selector yang dimana selector adalah sebuah penanda yang digunakan untuk memberikan tanda terhadap tag html yang ingin di modifikasi

2. color merupakan property yang di mana property digunakan untuk menambahkan atau mengatur ukuran teks, jenis font, warna teks, warna background, dan sebagainya

3. red adalah nilai dari property

  

# Percobaan Pertama

## Kode Program

```html

<!DOCTYPE html>

<html>

    <head>

        <title>Belajar CSS 1</title>

        <style>

            p {

                color: red;

            }

        </style>

    </head>

    <body>

        <p>Welcome CSS</p>

    </body>

</html>

```

## Hasil

  

## Penjelasan

1. <!DOCTYPE html>: Mendefinisikan jenis dokumen HTML yang digunakan, dalam hal ini HTML5.

2. `<html>`: Elemen utama yang memuat seluruh konten dokumen.

3. `<head>`: Bagian yang berisi informasi tambahan tentang dokumen, seperti judul dan link ke stylesheet eksternal.

4. `<title>`: Menentukan judul halaman web yang akan ditampilkan di tab browser.

5. `<style>`: Bagian di mana Anda dapat menambahkan aturan CSS untuk mengubah tampilan elemen HTML di halaman.

6. `p { color: red; }`: Aturan CSS yang mengubah warna teks pada semua elemen `<p>` menjadi merah.

7. `<body>`: Bagian yang berisi konten aktual halaman web, seperti teks, gambar, atau elemen lainnya.

8. `<p>Welcome CSS</p>` : Elemen paragraf dengan teks "Welcome CSS", yang akan ditampilkan dengan warna merah karena aturan CSS yang telah ditentukan sebelumnya.

  
  
  

# Percobaan Kedua

## Kode CSS

```CSS

         button {

            font-size: 20px;

            border:none;

            width: 150px;

            height: 50px;

            font-family:'sans-serif';

        }

```

## Font-size

### Before

![gambar](gambar/before.png)

### After

![gambar](gambar/after_font-size.png)

  

>[!faq]- Apa itu font-size?

>Font-size adalah property CSS yang berfungsi untuk mengatur ukuran font.

  

## Border

### Before

![gambar](gambar/before.png)

  

### After

![gambar](gambar/after_border.png)

  

>[!faq]- Apa itu Border?

>Border merupakan property CSS yang berguna untuk mengatur garis pinggir dari tombol.

  
  

## Font-family

### Before

![gambar](gambar/before.png)

### After

![gambar](gambar/after_font-family.png)

  

>[!faq]- Apa itu font-family?

>font-family adalah property CSS yang berfungsi untuk mengubah jenis font.

  

# Cara pemanggilan CSS

## In-line

In-line merupakan salah satu cara untuk memanggil css yaitu dengan cara memanggilnya kedalam baris yang sama dengan tag yang ingin di modifikasi contoh

  

### Kode Program

```html

<p style="color: red;">Welcome CSS</p>

```

<p style="color: red;">Welcome CSS</p>

  

### Hasil

  

### Penjelasan

  

> [!NOTE] Penjelasan

> *In-line CSS*: Dalam metode ini, CSS ditulis langsung di dalam tag HTML menggunakan atribut style. Ini berguna ketika Anda ingin menerapkan gaya yang spesifik hanya untuk satu elemen.

## Internal

  

### Kode Program

```HTML

<html>

    <head>

        <title>Belajar CSS 1</title>

        <style>

            p {

                color: red;

            }

        </style>

    </head>

    <body>

        <p>Welcome CSS</p>

    </body>

</html>

```

  

<html>

    <head>

        <title>Belajar CSS 1</title>

        <style>

            p {

                color: red;

            }

        </style>

    </head>

    <body>

        <p>Welcome CSS</p>

    </body>

</html>

### Hasil

  

### Penjelasan

  

> [!NOTE] Penjelasan

> *Internal CSS*: Dalam metode ini, CSS ditulis di dalam tag `<style>` di dalam elemen `<head>` dokumen HTML. Ini berguna ketika Anda memiliki beberapa halaman yang memerlukan gaya yang sama. Dengan menggunakan internal CSS, Anda dapat menetapkan gaya sekali dan akan berlaku untuk seluruh halaman tersebut.

  

## External

### Kode Program

Kode Program HTML yang dimana ini adalah tempat css di panggil dengan menggunakan metode external

```html

<html>

    <head>

        <title>Belajar CSS2</title>

        <link rel="stylesheet" href="belajar css1.css">

    </head>

    <body>

        <p>Welcome CSS</p>

    </body>

</html>

```

tampilan

<html>

    <head>

        <title>Belajar CSS2</title>

        <link rel="stylesheet" href="belajar css1.css">

    </head>

    <body>

        <p>Welcome CSS</p>

    </body>

</html>

  

```css

Kode Program CSS

CSS

p{

    color: red;

}

```

  

### Hasil

### Penjelasan

  

> [!NOTE] Penjelasan

> *External CSS*: Dalam metode ini, CSS ditulis dalam file terpisah dengan ekstensi .css, dan kemudian dihubungkan dengan dokumen HTML menggunakan tag <link>. Hal ini memisahkan struktur konten (HTML) dari presentasi (CSS), membuatnya lebih mudah untuk memelihara dan memperbarui gaya di seluruh situs web Anda

  

# ID SELECTOR

## Penjelasan

- `<!DOCTYPE html>` : Mendefinisikan tipe dokumen sebagai HTML versi 5.

- `<html`: Menandakan awala dan akhir dari dokumen HTML.

- `<head>`: Berisi informasi tambahan tentang dokumen HTML.

- `<title>CSS</title>`: Menentukan judul dokumen yang akan di tampilkan di web browser.

- `<link rel="stylesheet" href="style.css>`: Menautkan dokumen HTML dengan file CSS eksternal bernama `style.css`, sehingga dokumen HTML dapat menerapkan gaya ynag di definisikan dalam file CSS tersebut.

- `<body>`: Berisi konten yang akan di tampilkan di website.

- Elemen `<p id="hijau"> ini warna hijau</p>` memiliki atribut `id` yang menentukan identitas uniknya dalam dokumen HTML. Dengan demikian, fungsi dari atribut `id` ini adalah untuk memberikan cara yang unik untuk merujuk atau menargetkan elemen tersebut dalam CSS, dan memberikan warna hijau pada teks sesuai perintah pada CSS.

  

## Kode Progam

```HTML

<!DOCTYPE html>

<html>

<head>

    <title>Document</title>

    <link rel="stylesheet" href="style.css">

</head>

<body>

    <p style="font-size: 48px;">Welcome CSS</p>

    <h1>Hallo RPL</h1>

    <p id="hijau"> Ini Warna Hijau</p>

</body>

</html>

```

```css

#hijau {

    color:green;

}

```

  

## Hasil

![gambar](aset/selector.png)

  
  

## Kesimpulan

Jadi nama ID selector harus unik di dalam dokumen HTML. Artinya, hanya boleh ada satu elemen dengan ID tertentu dalam satu halaman web. Jika ada beberapa elemen dengan ID yang sama, hal itu tidak valid dan dapat menyebabkan masalah dalam tata letak serta perilaku halaman web. Sebagai rekomendasi, sebaiknya gunakan ID selector dengan bijak dan pastikan setiap ID unik di halaman web yang di buat..

  

# TEXT

## Text-decoration

### Overline

  

#### Penjelasan

text-decoration overline merupakan properti CSS yang digunakan untuk memberi garis di atas  teks.

#### Kode program

```css

<head>

    <title>Text</title>

    <style>

        .over {

    text-decoration: overline;

    }

    </style>

</head>

<body>

    <p class="over">ALYA</p>

</body>

```

#### Hasil

![gambar](gambar/overline.png)

  
  

#### Kesimpulan

overline merupakan salah satu jenis garis pada teks dekorasi yang berguna untuk memberi garis atas pada teks.

### Underline

  

#### Penjelasan

Text-decoration underline merupakan properti CSS yang memberi garis bawah pada teks.

#### Kode program

```css

<head>

    <title>Text</title>

    <style>

        .under {

    text-decoration: underline;

    }

    </style>

</head>

<body>

    <p class="under">ALYA</p>

</body>

```

#### Hasil

![gambar](gambar/underline.png)

  

#### Kesimpulan

underline merupakan salah satu jenis garis yang memberikan garis bawah pada teks.

### Line-through

  

#### Penjelasan

text-decoration line-through merupakan dekorasi garis di tengah atau teks tercoret.

#### Kode program

```css

<head>

    <title>Text</title>

    <style>

        .through {

    text-decoration: line-through;

    }

    </style>

</head>

<body>

    <p class="through">ALYA</p>

</body>

```

#### Hasil

![gambar](gambar/through.png)

  

#### Kesimpulan

line-through adalah salah satu jenis garis di CSS yang memberi kesan tercoret pada teks atau garis tengah pada teks.

# BACKGROUND

## Background-color

### Penjelasan

background-color merupakan properti css yang mengatur warna latar belakang halaman.

### Kode program

```css

<head>

<style>

body {

    background-color: lightblue;

}

</style>

</head>

<body>

<p>Hello World!</p>

</body>

```

### Hasil

![gambar](gambar/bgcolor.png)

  

### Kesimpulan

merupakan properti CSS yang memberikan warna pada latar belakang web.

## Background-image

### Penjelasan

Background-image dalam CSS adalah properti yang digunakan untuk menentukan gambar yang akan digunakan sebagai latar belakang dari suatu elemen.

### Kode program

```css

<head>

<style>

body {

    background-image: url("mawar.png");

}

</style>

</head>

<body>

<p>Hello World!</p>

</body>

```

  

### Hasil

![gambar](gambar/bgimage.png)

  

### Kesimpulan

merupakan properti CSS yang dapat mengatur gambar pada latar belakang web.

## Background-repeat

### Penjelasan

Background-repeat adalah properti yang digunakan untuk mengatur gambar latar belakang yang digunakan apakah ingin di ulang atau tidak.

### Kode program

```css

<head>

<style>

body {

    background-image: url("mawar.png");

    background-repeat: no-repeat;

}

</style>

</head>

<body>

<p>Hello World!</p>

</body>

```

### Hasil

![gambar](gambar/bgrepeat.png)

  
  

### Kesimpulan

Background-repeat adalah properti yang digunakan untuk mengulang gambar latar belakang atau tidak.

## Background-attachament

### Penjelasan

  

### Kode program

### Hasil

### Kesimpulan

# FONT

## font-size

### Penjelasan

font-size merupakan properti css yang digunakan untuk mengatur ukuran font.

### Kode program

```css

<head>

    <title>font</title>

    <style>

        .size {

    font-size: 100px;

    }  

    </style>

</head>

<body>    

    <p class="size">ALYA</p>

</body>

```

### Hasil

![gambar](gambar/fontsize.png)

  
  

### Kesimpulan

font-size merupakan properti yang digunakan untuk mengatur seberapa besar atau kecil ukuran font yang di inginkan.

## font-weight

### Penjelasan

font-weight adalah properti CSS yang dapat mengubah ketebalan sebuah teks.

### Kode program

```css

<head>

    <title>font</title>

    <style>

        .weight {

    font-weight:bolder;

    }

    </style>

</head>

<body>    

    <p class="weight">ALYA</p>

</body>

```

### Hasil

![gambar](gambar/fontweight.png)

  

### Kesimpulan

font-weight adalah properti yang digunakan untuk mengatur ketebalan teks sesuai keinginan.

## font-style

### Penjelasan

font-style merupakan properti CSS yang mengatur gaya dari teks, seperti kemiringan.

### Kode program

```css

<head>

    <title>font</title>

    <style>

        .style {

    font-style:italic;

    }

    </style>

</head>

<body>    

    <p class="style">ALYA</p>

</body>

```

### Hasil

![gambar](gambar/fontstyle.png)

### Kesimpulan

jadi, font-style digunakan untuk mengatur gaya dari sebuah teks.

## font-family

### Penjelasan

font-family adalah properti CSS yang dapat mengubah jenis font suatu text.

### Kode program

```css

<head>

    <title>font</title>

    <style>

        .family {

    font-family: 'Courier New', Courier, monospace;

    }

    </style>

</head>

<body>    

    <p class="family">ALYA</p>

</body>

```

### Hasil

![gambar](gambar/fontfamily.png)

  

### Kesimpulan

jadi, font-family adalah properti CSS yang digunakan untuk mengatur jenis teks. Font-family juga dapat menampung beberapa nama font sesuai selera, jika font pertama tidak terbaca maka font selanjutnya akan di jalankan. Nama font harus dipisah dengan tanda koma.

# BOX MODEL

## PADDING

### Penjelasan

padding adalah sebuah properti CSS yang digunakan untuk menentukan jarak antara konten elemen dan garis batas elemen tersebut. Properti padding dapat diatur pada semua direksi, yaitu atas, bawah, kiri, dan kanan. Untuk mengatur padding pada direksi tertentu, gunakan properti padding-top, padding-bottom, padding-left, dan padding-right.

1. `padding-top`: Properti ini digunakan untuk menentukan jarak antara konten elemen dan garis atas elemen tersebut.

2. `padding-bottom`: Properti ini digunakan untuk menentukan jarak antara konten elemen dan garis bawah elemen tersebut.

3. `padding-left`: Properti ini digunakan untuk menentukan jarak antara konten elemen dan garis kiri elemen tersebut.

4. `padding-right`: Properti ini digunakan untuk menentukan jarak antara konten elemen dan garis kanan elemen tersebut.

### Kode Program

```css

.button1 {

   background-color: pink;

   width: 100px;

   height: 50px;

   border: 5px solid palevioletred;

   border-radius: 10px 15px;

   padding-left: 0px;

   padding-bottom: 50px;

   padding-right: 50px;

   padding-top: 50px;

```

### Hasil

![gambar](aset/padding.png)

  
  

### Kesimpulan

Properti padding adalah properti CSS yang digunakan untuk menentukan jarak antara konten elemen dan garis batas elemen tersebut.

## MARGIN

### Penjelasan

margin adalah properti CSS yang digunakan untuk menentukan jarak antara elemen dan elemen lainnya atau antara elemen dan area konten halaman. Properti margin dapat diatur pada semua direksi, yaitu atas, bawah, kiri, dan kanan. Untuk mengatur padding pada direksi tertentu, gunakan properti margin-top, margin-bottom, margin-left, dan margin-right.

1. `margin-top`: menetapkan margin atas elemen, yang merupakan spasi di atas elemen.

2. `margin-bottom`: menetapkan margin bawah elemen, yang merupakan spasi di bawah elemen.

3.  `margin-left`: mengatur margin kiri elemen, yang merupakan spasi di sebelah kiri elemen.

4. `margin-right`: menetapkan margin kanan elemen, yang merupakan spasi di sebelah kanan elemen.

  

### Kode Program

```css

.button2 {

    background-color: pink;

    width: 100px;

    height: 50px;

    border: 0px;

    margin-top: 600x;

    margin-bottom: 600px;

    margin-left: 500px;

    margin-right: 100px;

}

```

### Hasil

![gambar](aset/margin.png)

  

### Kesimpulan

margin adalah properti singkatan untuk mengatur margin elemen di empat arah atas, kanan, bawah, dan kiri.

  

## BORDER

### Penjelasan

Properti dalam CSS digunakan untuk mengatur batas elemen.  

1. `border-width` : Properti ini digunakan untuk mengatur lebar perbatasan, dapat diatur ke nilai panjang, seperti piksel

2. `border-style` : Properti ini digunakan untuk mengatur gaya perbatasan, dapat diatur ke nilai seperti solid, putus-putus, garis lurus, atau tidak ada.

3. `border-color` : Properti ini digunakan untuk mengatur warna perbatasan, dapat diatur ke nama warna, kode warna heksadesimal.

### Kode Program

```css

button {

    border-color: lightcoral;

    border-width: 10px;

    border-style: solid;

}

```

### Hasil

![gambar](aset/border.png)

### Kesimpulan

1. `border-width` mengatur lebar garis. Contoh nilai yang dapat digunakan adalah `thin`, `medium`, `thick`, atau nilai numerik dalam piksel (`px`), sentimeter (`cm`), atau unit lainnya.

2. `border-style` mengatur gaya garis. Beberapa nilai yang umum digunakan adalah `solid` (garis solid), `dashed` (garis putus-putus), `dotted` (garis titik-titik), `double` (garis ganda), dll.

3. `border-color` mengatur warna garis. Nilai yang dapat digunakan adalah nama warna seperti `red`, `blue`, `green`, kode hex seperti `#FF0000`, `#00FF00`, `#0000FF`, atau nilai lain seperti `rgb(255, 0, 0)`.

# Latihan box model

## Penjelasan

1. p { ... }: Ini adalah pemilih elemen yang mengatur tata letak dan gaya teks pada halaman web. Dalam kode ini, properti dan nilai yang digunakan adalah :

- f`ont-size: 75px;` -> Mengatur ukuran font menjadi 75 piksel.

- font-family: 'arial'; -> Mengatur jenis font menjadi Arial.

- margin-top: 150px; -> Mengatur jarak antara teks dan elemen di atasnya menjadi 150 piksel.

- margin-bottom: 100px; -> Mengatur jarak antara teks dan elemen di bawahnya menjadi 100 piksel.

- margin-left: 50px; -> Mengatur jarak antara teks dan elemen di sebelah kiri menjadi 50 piksel.

- margin-right: 100px; -> Mengatur jarak antara teks dan elemen di sebelah kanan menjadi 100 piksel.

- color: aliceblue; -> Mengatur warna teks menjadi aliceblue.

  

2. img { ... }: Ini adalah pemilih elemen gambar pada halaman web. Dalam kode ini, properti dan nilai yang digunakan adalah:

- margin-right: 200px; -> Mengatur jarak antara gambar dan elemen di sebelah kanan menjadi 200 piksel.

- margin-top: -30px; -> Mengatur jarak antara gambar dan elemen di atasnya menjadi -30 piksel (agar gambar terlihat lebih bawah).

- border: 10px solid white; -> Mengatur border gambar menjadi 10 piksel dengan warna putih.

- border-radius: 1500px 1500px; -> Mengatur sudut pada border gambar menjadi bulat.

3. button { ... }: Ini adalah pemilih elemen tombol pada halaman web. Dalam kode ini, properti dan nilai yang digunakan adalah:

- background-color: purple; -> Mengatur warna latar belakang tombol menjadi ungu.

- width: 150px; -> Mengatur lebar tombol menjadi 150 piksel.

- height: 50px; -> Mengatur tinggi tombol menjadi 50 piksel.

- border-width: 2px; -> Mengatur lebar border tombol menjadi 2 piksel.    

- color: orange; -> Mengatur warna teks tombol menjadi orange.

- border-color: orange; -> Mengatur warna border tombol menjadi orange.    

- margin-bottom: 20px; -> Mengatur jarak antara tombol dan elemen di bawahnya menjadi 20 piksel.

- margin-left: 390px; -> Mengatur jarak antara tombol dan elemen di sebelah kiri menjadi 390 piksel

## Kode Program

```html

<!DOCTYPE html>

<html lang="en">

<head>

    <title> LATIHAN </title>

    <link rel="stylesheet" href="latihan1.css">

</head>

<body bgcolor="purple">

    <span>

        <img src="abrar.JPG" width="350px" height="350px" align="right">

        <p> Selamat Datang <br><b>

                di web ALYA !</b>

        <p>

    </span>

    <button> klik saya </button>

</body>

</html>

```

  

```css

p {

    font-size: 75px;

    font-family: 'arial';

    margin-top: 150px;

    margin-bottom: 100px;

    margin-left: 50px;

    margin-right: 100px;  

    color: aliceblue;

}

img {

    margin-right: 200px;

    margin-top: -30px;  

    border: 10px solid white;

    border-radius: 1500px 1500px;

}

button {

    background-color: purple;

    width: 150px;

    height: 50px;

    border-width: 2px;

    color: orange;

    border-color: orange;

    margin-bottom: 20px;

    margin-left: 390px;  

}

```

## Hasil

  

# Pseudo-classes

  

##  Hover

- `button:hover`: adalah pseudo-class selector yang menargetkan tombol (button) ketika pengguna mengarahkan kursor ke atasnya (hover) atau diklik.

- `background-color: red;`: Properti ini menetapkan warna latar belakang tombol menjadi merah ketika tombol sedang di-hover.

- `color: white;`: Properti ini menetapkan warna teks pada tombol menjadi putih ketika tombol di-hover.

- `height: 100px;`: Properti yang digunakan untuk membuat  tinggi (height) tombol menjadi 100 piksel ketika tombol di-hover.

- `width: 100px;`: Properti yang digunakan untuk membuat lebar (width) tombol menjadi 100 piksel ketika tombol di-hover.

  

## Kode Program

```html

<!DOCTYPE html>

  

<html>

  

<head>

  

    <title>Latihan</title>

  

    <link rel="stylesheet" href="latihan.css">

  

</head>

  

<body>

  

    <p class="text">Klik Untuk Mendapatkannya!</p>

  

    <button class="button">klik ❤️ ini!</button>

  

</body>

  

</html>

```

```css

button:hover {

  

    background-color: blueviolet;

  

    color: white;

  

    width: 150px;

  

    transition: all 0.3s ease-in;

  

}

```

# FLEXBOX

## Flex-container

### Penjelasan

- `display: flex;` properti yang membantu kita untuk mengatur tata letak elemen-elemen di dalamnya dengan menggunakan properti-properti seperti `flex-direction, justify-content,align-items` dan properti lainnya yang terkait dengan model tata letak flexbox.

- `flex-direction: column;` : Mengatur tata letak dari flex container menjadi vertikal, sehingga flex items di atur dari atas ke bawah.

- `flex-direction: column-reverse;`: Mengatur tata letak dari flex container menjadi vertikal terbaik, sehingga flex items di atur dari bawah ke atas.

-

### Kode Program

### Hasil

  

## Flex-item

### Penjelasan

### Kode Program

### Hasil

# POSITION

  
  

# ujian css

bg image berada didalam container

  

# tantangan praktikum