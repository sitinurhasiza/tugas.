# Anatomi CSS

## Kode Program

```css
P {
Color: red;
}
```

## Penjelasan
- Tag `<p>` adalah selector yang ingin di modifikasi.
- property adalah `color` pada komponen textnya
- property values adalah `red` kita mau modifikasi seperti apa warnanya

## Kesimpulan
warna teks (text color) dari elemen HTML yang memiliki tag P akan diubah menjadi merah (red).
  

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
  ![[Cuplikan layar 2024-04-29 194852.png]]

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
## Border-Radius
### Kode 
```css

button{
        border-radius: 20px;
        width:150px;
        height:50px;
      }
      ```
>[!note] Penjelasan: 
>Border-radius adalah properti CSS yang digunakan untuk mengatur radius sudut dari elemen kotak seperti div, span, atau elemen lainnya. Dengan menggunakan border-radius, Anda dapat membuat sudut-sudut elemen menjadi melengkung dengan menggambar lengkungan di setiap sudutnya. Properti ini memberikan fleksibilitas dalam menciptakan tampilan yang lebih menarik dan estetis pada elemen-elemen kotak. Anda dapat mengatur radius sudut dengan menggunakan nilai piksel, persentase, atau kombinasi dari keduanya.
### Before
![[WhatsApp Image 2024-03-04 at 12.05.59.jpeg]]
>[!faq]- Tidak memakai `border-radius`:
 -Tanpa menggunakan `border-radius`, elemen kotak akan memiliki sudut-sudut yang tajam dan persegi.
-Tampilan elemen dapat terlihat lebih sederhana dan minimalis.
 -Jika tidak diperlukan penampilan dengan sudut melengkung, penggunaan `border-radius` tidak diperlukan, sehingga memudahkan dalam pengaturan gaya dan tata letak elemen lainnya.

### After
![[WhatsApp Image 2024-03-04 at 12.05.58.jpeg]]
>[!faq]- Memakai `border-radius`:
 -Menggunakan `border-radius` dapat memberikan elemen kotak tampilan yang lebih menarik dengan sudut-sudut yang melengkung.
-Lengkungan sudut dapat membuat elemen terlihat lebih lembut, ramah, dan estetis.
 -Anda dapat mengatur radius sudut dengan nilai piksel atau persentase, serta mengkombinasikan nilai untuk setiap sudut secara terpisah.



  

## Padding-Left
### Kode
```css

button{
   width:150px;
   height:50px;
   padding-left:20px;
}
```
>[!note] Penjelasan: 
>Padding-left adalah properti CSS yang digunakan untuk mengatur ruang kosong (padding) di sebelah kiri elemen. Nilai padding-left menentukan jarak antara tepi kiri elemen (content box) dengan konten yang ada di dalamnya atau dengan tepi elemen yang berada di sebelah kiri (misalnya, border atau margin elemen tetangga di sebelah kiri). Properti ini memungkinkan pengaturan ruang kosong di sebelah kiri elemen untuk mencapai tata letak yang diinginkan atau memberikan ruang tambahan antara elemen tetangga di sebelah kiri. Nilai padding-left dapat dinyatakan dalam piksel, persentase, atau unit lainnya.
### Before
![[WhatsApp Image 2024-03-04 at 12.05.59.jpeg]]
>[!faq]- Tidak memakai `padding-left`:

-Tanpa menggunakan `padding-left`, elemen akan tidak memiliki ruang kosong di sebelah kiri.
-Hal ini dapat membuat elemen terlihat lebih rapat dengan elemen tetangga atau konten di dalamnya.
-Jika tidak diperlukan ruang tambahan di sebelah kiri elemen, penggunaan `padding-left` tidak diperlukan, sehingga memudahkan dalam pengaturan tata letak elemen lainnya.
### After
![[WhatsApp Image 2024-03-04 at 12.06.00.jpeg]]
>[!faq]- Memakai `padding-left`:
 -Dengan menggunakan `padding-left`, Anda dapat memberikan ruang kosong di sebelah kiri elemen.
-Properti ini memungkinkan Anda untuk mengatur jarak antara tepi kiri elemen dengan konten di dalamnya atau dengan elemen tetangga di sebelah kiri.
-Penggunaan `padding-left` berguna untuk mencapai tata letak yang diinginkan atau memberikan ruang tambahan di sebelah kiri elemen.
>[!note] Penjelasan:


## Font-Size

### Kode
```css
button{
   width:150px;
   height:50px;
   font-size:20px;
}
```
>[!note] Penjelasan: 
>Font-size adalah properti CSS yang digunakan untuk mengatur ukuran teks pada elemen. Properti ini menentukan ukuran relatif atau absolut dari teks yang ditampilkan. Nilai font-size dapat dinyatakan dalam berbagai unit, seperti piksel (px), em (em), persen (%), atau unit lainnya. Dengan menggunakan font-size, Anda dapat mengatur teks menjadi lebih kecil atau lebih besar untuk mencapai tampilan yang diinginkan. Ukuran teks yang tepat dapat membantu meningkatkan keterbacaan dan mempengaruhi tata letak keseluruhan elemen di dalam dokumen web.
### Before

![[WhatsApp Image 2024-03-04 at 12.05.59.jpeg]]
>[!faq]- Tidak memakai `font-size`:
-Tanpa menggunakan `font-size`, ukuran teks akan mengikuti nilai default yang ditetapkan oleh browser.
-Hal ini dapat mengakibatkan ukuran teks yang tidak sesuai dengan kebutuhan atau preferensi yang diinginkan.
-Jika tidak ada kebutuhan khusus untuk mengatur ukuran teks, penggunaan `font-size` tidak diperlukan.
  
### After
![[WhatsApp Image 2024-03-04 at 12.05.59 (1).jpeg]]
>[!faq]- Memakai `font-size`:
-Dengan menggunakan `font-size`, Anda dapat mengatur ukuran teks pada elemen sesuai dengan kebutuhan.
-Properti ini memungkinkan Anda untuk mengontrol ukuran relatif atau absolut dari teks yang ditampilkan.
-Dengan menentukan nilai font-size yang tepat, Anda dapat mencapai tampilan teks yang sesuai dengan desain atau preferensi Anda.

# Text
## Text Align 

### Penjelasan
- `p` adalah sebuah selektor CSS yang menargetkan elemen HTML `<p>` (paragraf).
- `text-align: center;` adalah sebuah properti CSS yang menentukan penataan teks di dalam elemen yang dipilih. Nilai `center` menyebabkan teks di dalam elemen paragraf tersebut terpusat secara horizontal.

### Kode Program
```css
p{

   text-align: center;

}
```
### Hasil
![[text align.png]]
### Kesimpulan

Kesimpulannya, program CSS tersebut secara khusus menargetkan elemen paragraf `<p>` pada halaman web dan mengatur penataan teks di dalamnya agar terpusat secara horizontal. Dengan demikian, semua teks yang berada di dalam elemen paragraf akan ditampilkan dengan penataan terpusat secara horizontal.
## Text Decoration

### Penjelasan
- `p` adalah selektor CSS yang menargetkan elemen paragraf `<p>`.
- `text-decoration: underline;` adalah properti CSS yang menetapkan dekorasi garis bawah pada teks di dalam elemen yang dipilih. Dengan nilai `underline`, teks di dalam elemen paragraf akan memiliki garis bawah.
### Kode Program
```css
p{

   text-decoration: underline;

}
```
### Hasil
![[text decoration.png]]
### Kesimpulan
Kesimpulannya, program CSS tersebut mengubah tampilan teks pada elemen paragraf `<p>` dengan menambahkan dekorasi garis bawah pada teks di dalamnya. Sehingga, semua teks yang berada di dalam elemen paragraf akan ditampilkan dengan garis bawah.

## Text Transform

### Penjelasan
- `p` adalah selektor CSS yang menargetkan elemen paragraf `<p>`.
- `text-transform: uppercase;` adalah properti CSS yang mengubah teks di dalam elemen yang dipilih menjadi huruf kapital (uppercase).
### Kode Program
```css
p{

   text-transform: uppercase;

}
```
### Hasil
![[text transform.png]]
### Kesimpulan
Dengan menggunakan kode CSS `p { text-transform: uppercase; }`, setiap teks yang terdapat di dalam elemen paragraf `<p>` pada halaman web akan diubah menjadi huruf kapital (uppercase). Ini berarti semua teks tersebut akan ditampilkan dalam format huruf besar tanpa memperhatikan huruf aslinya.


# Cara pemanggilan CSS

## In-line

In-line merupakan salah satu cara untuk memanggil css yaitu dengan cara memanggilnya kedalam baris yang sama dengan tag yang ingin di modifikasi contoh
### Kode Program

```html

<p style="color: red;">Welcome CSS</p>

```

<p style="color: red;">Welcome CSS</p>

  
### Hasil
![[merah.png]]
  
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

  ![[Cuplikan layar 2024-04-29 194852.png]]

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

p{

    font-family: 'Courier New', Courier, monospace;

    }
```
### Hasil
![[merah1.png]]
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
![[hijau1.png]]
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

    <p class="over">HASIZA</p>

</body>

```

#### Hasil
![[Cuplikan layar 2024-04-29 201343.png]]
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

    <p class="under">Hasiza</p>

</body>

```

#### Hasil
![[text decoration.png]]

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

    <p class="through">HASIZA</p>

</body>

```

#### Hasil
![[Cuplikan layar 2024-04-29 205912.png]]

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

![[Cuplikan layar 2024-04-29 210216.png]]

  

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

    background-image: url("acica.jpeg");

}

</style>

</head>

<body>

<p>Hello World!</p>

</body>

```

  

### Hasil

![[Cuplikan layar 2024-04-29 211558.png]]

  

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

    background-image: url("acica.jpeg");

    background-repeat: no-repeat;

}

</style>

</head>

<body>

<p>Hello World!</p>

</body>

```

### Hasil

![[Cuplikan layar 2024-04-29 211749.png]]

  
  

### Kesimpulan

Background-repeat adalah properti yang digunakan untuk mengulang gambar latar belakang atau tidak.


## Background-attachament
### Penjelasan

Properti `background-attachment` digunakan untuk mengontrol apakah gambar latar belakang akan tetap diam (`fixed`) atau akan bergulir bersamaan dengan konten (`scroll`) saat pengguna menggulir halaman. Dalam contoh ini, gambar latar belakang tetap diam bahkan saat halaman digulir.

### Kode program

```css
<!DOCTYPE html>

  

<html>

    <head>

  

        <style>

        body {

     background-image: url("acica.jpeg");

     background-repeat: no-repeat;

     background-attachment: local;

        }

        </style>

        </head>

        <body>

        <p>Hello World!</p>

        </body>
```

### Hasil
![[Cuplikan layar 2024-04-29 212723.png]]


### Kesimpulan
background tersebut digunakan untuk menambahkan gambar tetapi halaman tersebut tdk dapat digulir ke halaman berikutnya

# FONT

## Font-Size
### Penjelasan
font-size merupakan properti css yang digunakan untuk mengatur ukuran font.
### Kode program

[](https://github.com/nayah14/MateriCSS/blob/main/CSS/Pengenalan%20CSS.md#kode-program-8)

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
    <p class="size">HASIZA</p>
</body>
```

### Hasil
![[Cuplikan layar 2024-04-30 000144.png]]
### Kesimpulan
font-size merupakan properti yang digunakan untuk mengatur seberapa besar atau kecil ukuran font yang di inginkan.

## font-weight
Penjelasan font-weight adalah properti CSS yang dapat mengubah ketebalan sebuah teks.
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
    <p class="weight">HASIZA</p>
</body>
```

### Hasil
![[Cuplikan layar 2024-04-29 213454.png]]

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
    <p class="style">HASIZA</p>
</body>
```

### Hasil
![[Cuplikan layar 2024-04-29 213532.png]]
### Kesimpulan
font-style digunakan untuk mengatur gaya dari sebuah teks
## font-family

### Penjelasan
font-family adalah property CSS yang dapat mengubah jenis font suatu text.
### Kode Program

```css
.family {
font-family: 'Courier New' , Courier, monospace
}
```

### Hasil
![[Cuplikan layar 2024-04-29 213707.png]]
### Kesimpulan
Font-family adalah property CSSS yg digunakan untuk mengatur jenis text.Font-family juga dapat menampung beberapa nama font sesuai selera,jika font pertama tidak terbaca maka font selanjutnya akan dijalankan,Nama font harus dipisah dengan tanda koma

# Box-Model
## border
### penjelasan
Border (batas) dalam CSS adalah garis yang mengelilingi suatu elemen HTML. Border dapat digunakan untuk memberikan tampilan visual yang jelas dan terpisah antara elemen-elemen di dalam halaman web. Ada tiga properti utama yang dapat digunakan untuk mengatur border suatu elemen:

1. `border-width`: Mengatur lebar border.
2. `border-style`: Mengatur jenis atau gaya border, seperti solid, dashed, dotted, double, dsb.
3. `border-color`: Mengatur warna border.
4. `boder-radius`: membuat sudut elemen HTML menjadi melengkung daripada tajam.

### kode program
```css
Button {
border-color: red;
}
```

### Hasil
![[Cuplikan layar 2024-04-29 214120.png]]

### kesimpulan
kesimpulan kode tersebut `div { border-color: red; }` adalah bahwa semua elemen `<div>` pada halaman web akan memiliki border dengan warna merah. Dengan kode tersebut, setiap elemen `<div>` akan memiliki border dengan lebar default (biasanya 1 piksel), gaya default (biasanya solid), namun warna bordernya akan diatur menjadi merah. Ini berarti elemen `<div>` akan memiliki garis pinggiran berwarna merah mengelilingi seluruh elemennya.

## Margin
### penjelasan
Margin dalam CSS adalah ruang kosong di sekeliling elemen HTML yang digunakan untuk mengatur jarak antara elemen dengan elemen lainnya atau dengan batas-batas luar halaman web. Ada empat properti margin yang dapat digunakan:

1. `margin-top`: Mengatur jarak atas elemen.
2. `margin-right`: Mengatur jarak kanan elemen.
3. `margin-bottom`: Mengatur jarak bawah elemen.
4. `margin-left`: Mengatur jarak kiri elemen.

### kode program
```css
img{
    
    margin-left: 600px;
    }
```

### Hasil
![[Cuplikan layar 2024-04-29 234610.png]]
### kesimpulan
Kesimpulan dari kode CSS `div { margin-left: 600px; }` adalah bahwa semua elemen `<img>` pada halaman web akan memiliki margin sebesar 600 piksel di sisi kanan. Dengan kode tersebut, setiap elemen `<img>` akan memiliki ruang kosong (margin) sebesar 600 piksel di sisi kiri, yang berarti elemen-elemen tersebut akan terpisah dengan elemen lain di sebelah kanannya sejauh 600 piksel. Ini akan memengaruhi tata letak (layout) dari elemen-elemen `<img>` tersebut dalam halaman web.

## Padding
### penjelasan

`padding` digunakan dalam CSS untuk menentukan ruang kosong di sekeliling konten suatu elemen HTML. Properti `padding` dapat diatur secara terpisah untuk setiap sisi elemen, yaitu atas (top), kanan (right), bawah (bottom), dan kiri (left). Properti `padding` digunakan dalam CSS untuk menentukan ruang kosong di sekeliling konten suatu elemen HTML. Properti `padding` dapat diatur secara terpisah untuk setiap sisi elemen, yaitu atas (top), kanan (right), bawah (bottom), dan kiri (left). Ini berarti elemen yang diatur akan memiliki padding sebagai berikut:

- `padding-left: 10px;` : Padding sebesar 10 piksel di sisi kiri elemen.
- `padding-bottom: 10px;` : Padding sebesar 10 piksel di sisi bawah elemen.
- `padding-right: 10px;` : Padding sebesar 10 piksel di sisi kanan elemen.
- `padding-top: 10px;` : Padding sebesar 10 piksel di sisi atas elemen.

### kode program

```css
Img {

    padding-left: 200px;

    }
```

### Hasil
![[Cuplikan layar 2024-04-29 234700.png]]
### kesimpulan
Kesimpulan dari kode CSS `div { padding-left: 100px; }` adalah bahwa semua elemen `<img>` pada halaman web akan memiliki padding sebesar 100 piksel di sisi kiri. Dengan kode tersebut, setiap elemen `<img>` akan memiliki ruang kosong 100 piksel di sisi kiri, yang berarti konten di dalam elemen tersebut akan tergeser ke kiri sejauh 10p piksel dari batas kiri elemen. Jadi, setiap elemen `<img>` akan memiliki padding sebesar 100 piksel di sisi kiri elemen.

# Tantangann Box model

## Kode Program

```html
<!DOCTYPE html>

<html lang="en">

    <head>

        <title>CSS</title>

        <link rel="stylesheet" href="web.css">

    </head>

    <body bgcolor="purple">

        <span> <img src="acica.jpeg" width="270px" height=270px" align="right">

        <p>Selamat Datang<br>

        <b>di web Alwi Assegaf</p></b>

        </span>

        <button>Klik!</button>

    </body>

    </html>
```

```css
p{

   font-size:50px ;

   font-style:italic ;

   margin-top: 100px;

   margin-left: 50px;

   color: white;

}

img{

    margin-right: 130px;

    margin-top:-1px;

    border: 5px solid white;

    border-radius: 1500% 1500%;

}

button{

    background-color: purple;

    width:150px;

    height:60px;

    border-width: 2px;

    border-style:solid 50px;

    border-color: orangered;

    color: orangered;

    margin-bottom:20px ;

    margin-left: 300px;

}
```

## Hasil
![[Cuplikan layar 2024-04-29 233553.png]]

## Kesimpulan
Paragraf :

- `Teks besar dan miring` : Ukuran font 75px dan gaya font `italic` membuat teks paragraf menonjol dan terlihat formal.
- `Font klasik` : Penggunaan font `'times new roman'` memberikan kesan klasik dan elegan.
- `Margin besar` : Margin atas 150px, bawah 100px, kiri 50px, dan kanan 100px memberikan jarak yang besar antara paragraf dan elemen lainnya.
- `Warna biru pastel` : Warna `aliceblue` memberikan kesan lembut dan dingin pada teks.

image :

- `Margin kanan besar`: Margin kanan 200px memberikan spasi yang lebar antara gambar dan elemen lain di sebelah kanan.
- `Margin atas negatif`: Margin atas -50px kemungkinan digunakan untuk menaikkan posisi gambar agar sejajar dengan bagian atas paragraf.
- `Garis tepi tebal`: Border 10px membuat garis tepi gambar tebal dan terlihat jelas.
- `Sudut membulat ekstrem`: Border radius 1500px membuat sudut gambar membulat hampir menjadi lingkaran penuh.

button :

- `Warna ungu`: Background color `purple` memberikan kesan profesional dan modern pada tombol.
- `Ukuran sedang`: Lebar 100px dan tinggi 50px membuat tombol berukuran sedang dan mudah diklik.
- `Garis tepi oranye`: Border width 2px dan color `orangered` membuat garis tepi tombol berwarna oranye dan terlihat jelas.


# Transition
## Transition-property
### Penjelasan
adalah atribut yang digunakan untuk transisi yang apabila kursor didekatkan maka transisi akan berfungsi.
### Kode Program
```css
<html>

<head>

<style>

div {

  width: 100px;

  height: 100px;

  background: red;

  transition-property: width;

  transition-duration: 2s;

}

  

div:hover {

  width: 300px;

}

</style>

</head>

<body>

<div></div>

</body>

</html>
```

### Hasil
![[Cuplikan layar 2024-04-29 220849.png]]

## Transition-duration
### Penjelasan
Properti ini `transition-duration`menentukan berapa detik (s) atau milidetik (ms) yang diperlukan untuk menyelesaikan efek transisi.
### Kode Program
```css
<html>

<head>

<style>

div {

  width: 100px;

  height: 100px;

  background: red;

  transition-property: width;

  transition-duration: 5s;

}

  

div:hover {

  width: 300px;

}

</style>

</head>

<body>

<div></div>

</body>

</html>
```

### Hasil

![[Screenshot20.png]]

## Transition-timing function
### Penjelasan
Properti `transition-timing-function`menentukan kurva kecepatan efek transisi. Properti ini memungkinkan efek transisi untuk mengubah kecepatan sepanjang durasinya
### Kode program
```css
<!DOCTYPE html>

<html>

<head>

<style>

div {

  width: 100px;

  height: 100px;

  background: blueviolet;

  transition: width 2s;

  transition-timing-function: linear;

}

  

div:hover {

  width: 300px;

}

</style>

</head>

<body>

<div></div>

</body>

</html>
```

### Hasil
![[Cuplikan layar 2024-04-29 221016.png]]
# Tantangan Transition

## Penjelasan
1. `body`:
    - `background-color: rgb(248, 210, 163);`: Menetapkan warna latar belakang body menjadi warna oranye (dinyatakan dalam format RGB).
    - `width: 100%;`: Membuat body mengisi lebar penuh layar.
2. `.container`:
    - `display: contents;`: Membuat kontainer tersebut memiliki perilaku seperti tidak ada kontainer. Artinya, anak-anak langsung dari kontainer akan ditata sesuai dengan tata letak induknya.
    - `align-items: flex-end;`: Menetapkan item dalam kontainer untuk diatur di bagian bawah kontainer.
    - `flex-direction: row;`: Menjadikan anak-anak kontainer diatur dalam satu baris horizontal.
    - `justify-content: space-around;`: Membuat ruang sekitar item dalam kontainer secara merata.
3. `.box-2`:
    - `font-size: 75px;`: Menetapkan ukuran font sebesar 75 piksel.
    - `font-family: 'arial';`: Menggunakan jenis font Arial.
    - `margin-top: 150px; margin-bottom: 100px; margin-left: 50px; margin-right: 100px;`: Menetapkan jarak antara box dan elemen lain di sekitarnya.
    - `color: rgb(104, 104, 104);`: Menetapkan warna teks menjadi abu-abu tua.
4. `.box-1`:
    - `margin-right: 200px; margin-top: -30px;`: Menetapkan jarak dari sisi kanan dan atas box-1.
    - `border: 10px solid white; border-radius: 1500px 1500px;`: Menambahkan border putih dengan ketebalan 10 piksel dan radius sudut sebesar 1500 piksel.
5. `button`:
    - `background-color: lightblue; width: 150px; height: 50px;`: Menetapkan warna latar belakang, lebar, dan tinggi tombol.
    - `border-width: 2px; color: rgb(138, 138, 229); border-color: rgba(73, 134, 240, 0.29);`: Menetapkan ketebalan border, warna teks, dan warna border (dalam format RGBA) tombol.
    - `margin-bottom: 20px; margin-left: 400px;`: Menetapkan jarak bawah dan kiri tombol.
6. `button:hover`:
    - `background-color: lightcyan; font-weight: bolder; transition: all 0.3s ease-in;`: Menetapkan efek saat tombol dihover, seperti perubahan warna latar belakang dan penambahan ketebalan font. Ini menggunakan transisi selama 0.3 detik untuk menciptakan perubahan yang mulus.

## Kode Program

```html
<!DOCTYPE html>

<html>

<head>

    <title>tantangan transition</title>

    <link rel="stylesheet" href="acica.css">

</head>

<body>

    <div class="container">

        <div>

            <img class="box-1" src="unduhan.jpg" width="350px" height="350px" align="right">

            <p class="box-2"> Selamat Datang <br><b>

            di web Hasiza !</b>

            <p>

        </div>

        <button> klik saya </button>

    </div>

</body>

</html>
```

```css
body {

    background-color: rgb(248, 210, 163);

    width: 100%;

  }

  .container {

    display: contents;

    align-items: flex-end;

    flex-direction: row;

    justify-content: space-around;

  }

  .box-2 {

    font-size: 75px;

    font-family: 'arial';

    margin-top: 150px;

    margin-bottom: 100px;

    margin-left: 50px;

    margin-right: 100px;  

    color: rgb(104, 104, 104);

  }

  .box-1 {

    margin-right: 200px;

    margin-top: -30px;  

    border: 10px solid white;

    border-radius: 1500px 1500px;

  }

  button {

    background-color: lightblue;

    width: 150px;

    height: 50px;

    border-width: 2px;

    color: rgb(138, 138, 229);

    border-color: rgba(73, 134, 240, 0.29);

    margin-bottom: 20px;

    margin-left: 400px;

  }

  button:hover {

    background-color: lightcyan;

    font-weight: bolder;

    transition: all 0.3s ease-in;

  }
```

## Hasil
![[Cuplikan layar 2024-04-29 232443.png]]
## Kesimpulan

Latar belakang body akan memiliki warna `RGB (248, 210, 163)` yang merupakan kombinasi dari merah, hijau, dan biru. Lebar body akan setara dengan 100% lebar viewport (area tampilan browser). Elemen dengan kelas `"container"` akan memiliki tata letak kontennya yang diatur secara fleksibel, dengan elemen-elemen yang diatur dalam baris. Konten dalam elemen dengan kelas `"container"` akan diatur agar berada di bagian bawah `(align-items: flex-end)` dan memiliki ruang kosong merata di sekitarnya `(justify-content: space-around).` Elemen dengan kelas "box-2" akan memiliki ukuran `font 75 piksel`, menggunakan jenis `font Arial`, dan memiliki `margin atas, bawah, kiri, dan kanan` yang masing-masing telah ditentukan. Elemen dengan kelas "box-1" akan memiliki `margin kanan 200 piksel`, `margin atas -30 piksel` (mendorong elemen ke atas), border dengan `ketebalan 10 piksel`, dan radius lengkungan `border sebesar 1500 piksel` pada sudut-sudutnya. Tombol akan memiliki latar belakang warna `lightblue`, `lebar 150 piksel`, `tinggi 50 piksel`, `ketebalan border 2 piksel`, `warna teks RGB (138, 138, 229)`, `warna border RGBA (73, 134, 240, 0.29)`, dan `margin bawah dan kiri` yang telah ditentukan. Saat tombol dihover, latar belakangnya akan berubah menjadi lightcyan, teksnya akan menjadi lebih tebal, dan akan ada efek transisi selama `0.3 detik` dengan fungsi `timing ease-in`.

# Transform

### Penjelasan
`Transform` adalah untuk mengubah tampilan elemen HTML, seperti menggeser, memutar, atau mengubah ukurannya ketika di klik. Ini adalah cara untuk membuat animasi sederhana atau mengatur posisi elemen dengan lebih fleksibel, atau lebih singkatnya mengubah gaya pada suatu elemen HTML ketika diklik.

### Kode Program
```css
<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="acica.css">
    </head>
    </head>
    <body>
          <p>Klik untuk merubah dirimu menjadi lebih baik</p>
          <button class="tombol">KLIK!!!</button>
       </div>
    </body>
</html>

```

```css
.tombol {

    background-color: blue;

    color: white;

    border: none;

    width: 180px;

    height: 40px;

    font-size: 15px;

    border: 30px;

}

.tombol:hover {

    background-color: yellow;

    color: black;

    border: none;

    width: 160px;

    height: 40px;

    font-size: 20px;

    font-family: 'Segoe UI';

    font-weight: bold;

    border-radius: 30px;

    transition: all 0.3s ease-in;

  

}

.tombol:active {

    transform: scale(0.15);

}
```

### Hasil
![[Cuplikan layar 2024-04-29 222614.png]]


# Flexbox

## FLEX-CONTAINER
### Penjelasan
Flex container adalah elemen induk yang mengatur tata letak flex item-nya. flexbox yaitu memberikan container kemampuan untuk mengatur panjang, lebar, dan posisi item-item yang berada di dalamnya agar memaksimalkan ruang yang ada. Pengaturan ini sangat penting bagi seorang frontend developer untuk membuat sebuah website yang nyaman dilihat di berbagai device dengan berbagai macam resolus.

1. flex-direction :Menentukkan arah (direction) yang akan diberlakukan untuk item-item yang ada pada container flexbox.
2. flex-wrap :Digunakan untuk mendefinisikan bahwa elemen item di dalam container flexbox tidak harus disejajarkan dalam satu baris.
3. justify-content :Digunakan untuk mensejajarkan item-item diantara flexbox agar container dari flexbox tersebut bisa mendistribusikan ruang kosong yang tersisa ketika item flex dalam satu baris tersebut tidak flexsibel atau meskipun flexsibel tapi sudah mencapai batas ukuran maksimum.
4. align-items :Mendefinisikan bagaimana item-item pada container flex tersebut diletakkan sepanjang garis tegak lurus pada sumbu utama (cross-axis).
5. align-content :Digunakan untuk mensejajarkan garis flex container ketika ada ruang kosong secara garis tegak lurus pada sumbu utama (cross-axis).

### Kode Program
```css
.contrainer {

     display: flex;

     height: 100vh;

     justify-content: space-around ;

     align-items: center  ;

     background-color: blanchedalmond;

    }
```

### Hasil

![[Screenshot26 (4) 1.png]]

## FLEX-ITEM

### Penjelasan

 Dalam konteks Flexbox, elemen-elemen dianggap sebagai flex items (item fleksibel), dan mereka diatur dalam satu dimensi (baris atau kolom) menggunakan properti-properti Flexbox.  1. flex-grow: Properti ini menentukan sejauh mana flex item akan memperluas ruang tersedia dalam flex container.  2. flex-shrink: Properti ini menentukan sejauh mana flex item akan menyusut jika ruang tidak cukup dalam flex container.  3. flex-basis: Properti ini menentukan ukuran awal (basis) flex item sebelum fleks container membagi ruang yang tersedia.  4. flex: Properti singkat flex digunakan untuk menggabungkan flex-grow, flex-shrink, dan flex-basis dalam satu deklarasi.

### Kode Program

```css
.item {
    width: 100px;
    margin-right: 10px;
    margin-bottom: 10px;
    height: 100px;
    background-color: red;
    display: flex;
}
```

### Hasil
![[Screenshot26 (4) 1.png]]
### Kesimpulan

Kesimpulannya, dalam CSS Flexbox, elemen-elemen dianggap sebagai flex items (item fleksibel) dan dapat diatur menggunakan properti-properti Flexbox.

# Tantangan Flexbox

## Penjelasan

1. : Ini adalah deklarasi tipe dokumen HTML yang menunjukkan bahwa dokumen ini adalah dokumen HTML5.
2. `<html lang="en">:` Ini adalah elemen root (akar) dari dokumen HTML. lang="en" menunjukkan bahwa bahasa yang digunakan dalam dokumen adalah bahasa Inggris.
3. `<head>:` Elemen `<head>` digunakan untuk menyediakan informasi tentang dokumen, seperti judul (title) dan referensi ke file eksternal seperti stylesheet (CSS).
4. `<title>:` Elemen `<title>` digunakan untuk menentukan judul dokumen yang akan ditampilkan di bilah judul browser.
5. `<link rel="stylesheet" href="tugasflex.css">:` Elemen `<link>` digunakan untuk menghubungkan dokumen HTML dengan file eksternal CSS. Dalam contoh ini, file CSS yang disebut "tugasflex.css" akan digunakan untuk mengatur tampilan halaman.
6. `<body bgcolor="purple">:` Elemen `<body>` digunakan untuk mengelilingi konten utama halaman web. `bgcolor="purple"` adalah atribut yang digunakan untuk mengatur warna latar belakang body menjadi ungu (purple).
7. `<div class="main-container">:` Elemen `<div>` adalah elemen blok yang digunakan untuk mengelompokkan dan mengatur konten. class="main-container" adalah atribut kelas yang memberikan nama kelas "main-container" pada elemen ini. Kelas ini nantinya dapat digunakan dalam CSS untuk mengatur tampilan elemen ini.
8. `<div class="hero-container">:` Elemen `<div>` dengan kelas "hero-container" digunakan untuk mengelompokkan konten yang terkait dengan bagian hero atau bagian utama halaman.
9. `<div class="item p">:` Elemen `<div>` dengan kelas `"item p"` digunakan untuk mengelompokkan konten dan memberikan atribut kelas "p".
10. `<p>:` Elemen `<p>` digunakan untuk menampilkan paragraf teks. Di dalam elemen ini, terdapat teks "Selamat Datang" dan "di Web Adel" yang ditampilkan dalam beberapa baris yang dipisahkan oleh tag `<br>`. Teks "Web Adel" ditampilkan dengan teks tebal menggunakan tag `<b>`.
11. `<button>:` Elemen `<button>` digunakan untuk membuat tombol. Di sini, tombol ditampilkan dengan teks "klik saya".
12. `<span class="img">:` Elemen `<span>` digunakan untuk mengelompokkan dan memanipulasi bagian teks atau elemen lainnya dalam dokumen. Di sini, elemen span memiliki atribut kelas "img".
13. `<img src="abrar.JPG" width="350px" height="350px" align="right">:` Elemen `<img>` digunakan untuk menampilkan gambar dalam halaman. Atribut src menentukan sumber gambar (dalam hal ini, "abrar.JPG"), sedangkan atribut width dan height mengatur lebar dan tinggi gambar. Atribut align="right" mengatur posisi gambar ke sebelah kanan.

## Kode Program

```css
<!DOCTYPE html>

<html lang="en">

<head>

    <title>Document</title>

    <link rel="stylesheet" href="acica.css">

</head>

<body bgcolor="purple">

    <div class="main-container">

    <div class="hero-container">

        <div class="item p">

           <p> Selamat Datang <br>

            di<b>Web Hasiza</b> </P>

            <button> klik!! </button>

        </div>

        <div>

            <span class="img">

                <img src="cica.jpeg" width="350px" height="350px" align="right">

            </span>

    </div>

    </div>

</div>

</body>

</html>
```

```css
.main-container {

    display:flex;

    height: 100vh;

    justify-content: space-around ;

    align-items: center  ;

    background-color: purple;

}

.hero-container {

    display:flex;

    height: 100vh;

    justify-content: space-between;

    align-items: center  ;

    background-color: purple;

}

.item {

    width: 500px;

    height: 250px;

    background-color: none;

}

  

.p {

    font-size: 65px;

    font-family: 'arial';

    margin-top: 40px;

    margin-bottom: 100px;

    margin-left: 50px;

    margin-right: 100px;  

    color: aliceblue;

}

img {

    margin-right: 100px;

    margin-top: -10px;  

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

    margin-left: 290px;  

    box-shadow: 20px;

}

button:hover {

    background-color: orange;

    color: white;

    width: 150px;

    transition: all 0.3s esse-in;

    cursor: pointer;

}

button:active {

    transform:scale(0.5);

}
```

## Hasil
![[Cuplikan layar 2024-04-29 231556.png]]

# Position

## Position relative

### Penjelasan

`position: relative` adalah properti CSS yang digunakan untuk menetapkan posisi elemen pada halaman web relatif terhadap posisinya sendiri.

### Kode program

```css
.box { position: relative; top: 10px; left: 10px; width: 100px; height: 100px; background-color: red; }
```

### Hasil


![[Screenshot25 (3).png]]

### Kesimpulan

memungkinkan pengguna untuk mengatur posisi elemen dengan properti top, right, bottom, atau left

## Position absolute

### Penjelasan

`position: absolute` akan dikeluarkan dari normal flow, yang berarti elemen tersebut tidak akan memengaruhi posisi elemen lain di halaman.

### Kode program

```css
.box { position: absolute; top: 10px; left: 10px; width: 100px; height: 100px; background-color: red; }
```

### Hasil

![[Screenshot26 (3).png]]

### Kesimpulan
hanya berpengaruh pada elemen yang diatur, tidak akan berpengaruh pada posisi elemen lain.

## Position fixed
### Penjelasan
`position: fixed` adalah properti CSS yang digunakan untuk menetapkan posisi elemen pada halaman web tetap dalam posisi tertentu di layar

### Kode program
```css
.box {
  position: fixed;
  width: 100px;
  height: 100px;
  background-color: red;
}
```

### Hasil

![[Screenshot27.png]]

### Kesimpulan
Untuk menetapkan posisi suatu elemen

## Position sticky

### Penjelasan

Posisi sticky adalah cara efektif untuk mengubah posisi elemen dengan kecil atau sedikit, seperti menyesuaikan posisi elemen dengan kursor atau mengubah posisi elemen dalam layout.

### Kode program

```css
.box {
  position: sticky;
  top: 10px;
  width: 100px;
  height: 100px;
  background-color: red;
}
```

### Hasil

![[Screenshot28 (2).png]]

### Kesimpulan

`position: sticky` akan bergulir seperti normal hingga mencapai titik tertentu

# Tantangan Position
## Penjelasan

- `position: static;`: Kontainer tersebut memiliki posisi statis.
- `display: flex;`: Anak-anak dari kontainer akan diatur dalam satu baris, berdasarkan sumbu utama yang secara default akan menjadi horizontal.
- `flex-direction: column;`: Anak-anak dari kontainer akan diatur dalam satu kolom.
- `width: 100%;`: Kontainer akan mengisi lebar penuh dari elemen induknya.
- `height: 580px;`: Tinggi kontainer ditetapkan pada 580 piksel.
- `background-color: rgba(122, 122, 247, 0.628);`: Warna latar belakang kontainer diatur sebagai nilai RGBA.
- `width: 250px;`: Lebar box ditetapkan pada 250 piksel.
- `height: 350px;`: Tinggi box ditetapkan pada 350 piksel.
- `background-color: white;`: Warna latar belakang box diatur sebagai putih.
- `align-items: center;`: Anak-anak dari box akan dipusatkan secara horizontal.
- `align-content: center;`: Konten di dalam box akan dipusatkan secara vertikal.
- `border-radius: 10px;`: Sudut box akan dibulatkan sebesar 10 piksel.
- `align-self: center;`: Box akan dipusatkan di dalam kontainer secara horizontal.
- `margin-top: 150px;`: Jarak antara bagian atas kontainer dan bagian atas box ditetapkan pada 150 piksel.
- `margin-bottom: 200px;`: Jarak antara bagian bawah kontainer dan bagian bawah box ditetapkan pada 200 piksel.

## Kode Program

```html
<!DOCTYPE html>

<html>

<head>

    <title>POSITION</title>

    <link rel= "stylesheet" href="acica.css">

</head>

<body>

    <div class="container">

        <div class="box">

            <img class="item box-1" src="saya.jpeg" alt="Gambar">

            <p> <img class="icon" src="jempol.jpeg"></p>

            <p class="item box-2">Saturday, April 27, 2024</p>

            <h1 class="item box-3">The standard chunk of <br>Lorem Ipsum</h1>

            <p class="item box-4">Sed posuere consectetur est at lobortis.<br>Aeneen eu leo quam</p>

            <p class="box-5"><b>Read more </b> <img class="item-1" src="panah.jpeg"></p>

        </div>

    </div>

</body>

</html>
```

```css
.container {

    position: static;

    display: flex;

    flex-direction: column;

    width: 100%;

    height: 580px;

    background-color: rgba(122, 122, 247, 0.628);

}

.box {

    width: 250px;

    height: 350px;

    background-color: white;

    align-items: center;

    align-content: center;

    border-radius: 10px;

    align-self: center;

    margin-top: 150px;

    margin-bottom: 200px;

}

  

.item {

    width: 100%;

    color: black;

}

  

.box-1 {

    height: 225px;

    width: 100%;

    border-radius: 10px 10px 0px 0px;

}

  

.box-2 {

    font-size: 10px;

    margin-left: 10px;

    margin-top: 10px;

    padding-top: 10px;

    font-family: Arial, Helvetica, sans-serif;

}

  

.box-3 {

    font-size: 18px;

    margin-left: 10px;

    margin-top: 10px;

    padding-top: 10px;

    font-family: Arial, Helvetica, sans-serif;

}

  

.box-4 {

    font-size: 11px;

    font-family: Arial, Helvetica, sans-serif;

    margin-left: 10px;

}

  

.box-5 {

    background-color: rgb(193, 193, 193);

    padding-left: 20px;

    padding-bottom: 10px;

    padding-top: 10px;

    margin-bottom: 90px ;

    font-family: Arial, Helvetica, sans-serif;

    border-radius: 0px 0px 10px 10px;

    font-size: small;

}

  

.item-1 {

    width: 10px;

    padding-left: 130px;

}

  

.icon {

   background-color: skyblue;

   position: relative;

   left: 200px;

   bottom: 35px;

   width: 30px;

   height: 30px;

   border-radius: 1500px;

}
```

## Hasil

![[Cuplikan layar 2024-04-29 224957.png]]

## Kesimpulan

- Kontainer tersebut memiliki posisi statis dan akan mengisi lebar penuh dari elemen induknya.
- Tinggi kontainer ditetapkan pada 580 piksel, dengan latar belakang berwarna RGBA (122, 122, 247, 0.628).
- Anak-anak dari kontainer akan diatur dalam satu kolom, sehingga properti `flex-direction: column;` diterapkan.
- Lebar box ditetapkan pada 250 piksel dan tinggi pada 350 piksel, dengan latar belakang berwarna putih.
- Isi dari box akan dipusatkan secara horizontal dan vertikal dengan properti `align-items: center;` dan `align-content: center;`.
- Sudut box dibulatkan sebesar 10 piksel dan box itu sendiri akan dipusatkan di dalam kontainer secara horizontal dengan menggunakan `align-self: center;`.
- Terdapat juga penyesuaian margin, di mana jarak antara bagian atas kontainer dan bagian atas box ditetapkan pada 150 piksel,  dan jarak antara bagian bawah kontainer dan bagian bawah box ditetapkan pada 200 piksel.