# Eksplorasi
## Penjelasan

Filter dalam konteks CSS mengacu pada properti yang digunakan untuk memberikan efek visual pada elemen HTML. Filter memungkinkan Anda untuk memanipulasi tampilan elemen, seperti gambar, teks, atau latar belakang, dengan berbagai cara, termasuk mengubah warna, memperbaiki atau memperburuk kejelasan, serta memberikan efek artistik.
### 1. **Filter Efek pada Gambar:**
Dengan CSS, Kita dapat menerapkan filter untuk memberikan efek visual pada gambar, seperti grayscale, blur, atau peningkatan kecerahan.

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Filter Effect</title>
<style>
    .filtered-image {
        filter: grayscale(100%) blur(5px) brightness(120%);
    }
</style>
</head>
<body>

<img src="gambar.jpg" alt="Gambar" class="filtered-image">

</body>
</html>
```

Dalam contoh di atas, filter grayscale, blur, dan brightness diterapkan pada gambar dengan kelas CSS `.filtered-image`.

### 2. **Filter Hover:**
Kita juga dapat menerapkan filter hanya ketika pengguna mengarahkan kursor ke elemen dengan menggunakan pseudo-class `:hover`.

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Filter Hover</title>
<style>
    .filtered-image {
        filter: grayscale(100%);
        transition: filter 0.3s ease-in-out;
    }
    .filtered-image:hover {
        filter: none;
    }
</style>
</head>
<body>

<img src="gambar.jpg" alt="Gambar" class="filtered-image">

</body>
</html>
```

Dalam contoh ini, gambar akan berubah dari keadaan grayscale ke keadaan normal ketika pengguna mengarahkan kursor ke gambar tersebut.

### 3. **Filter Efek pada Background:**
Selain pada gambar, Kita juga dapat menerapkan filter pada latar belakang elemen HTML.

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Filter Background</title>
<style>
    .background {
        background-image: url('gambar.jpg');
        background-size: cover;
        filter: blur(5px) brightness(80%);
        height: 300px;
    }
</style>
</head>
<body>

<div class="background"></div>

</body>
</html>
```

Dalam contoh di atas, efek blur dan peningkatan kecerahan diterapkan pada latar belakang sebuah div.

Dengan menggunakan CSS, Anda dapat dengan mudah menerapkan filter untuk memberikan efek visual yang menarik pada elemen-elemen HTML dalam halaman web Anda.

## Contoh Contoh FILTER
Berikut adalah beberapa properti filter umum dalam CSS:

1. **grayscale()**: Mengonversi elemen menjadi gambar hitam-putih dengan tingkat keabuan tertentu. Nilai 0% menghasilkan gambar berwarna penuh, sedangkan nilai 100% menghasilkan gambar hitam-putih.   

2. **blur()**: Memberikan efek blur pada elemen dengan jarak tertentu. Nilai yang diterima adalah dalam satuan piksel, di mana semakin tinggi nilai, semakin buram elemen tersebut.

3. **brightness()**: Mengatur tingkat kecerahan elemen. Nilai 100% mempertahankan kecerahan asli, sementara nilai di atas 100% akan membuat elemen menjadi lebih terang dan nilai di bawah 100% akan membuatnya menjadi lebih gelap.

4. **contrast()**: Mengatur tingkat kontras elemen. Nilai 100% mempertahankan kontras asli, sementara nilai di atas 100% meningkatkan kontras dan nilai di bawah 100% mengurangi kontras.

5. **sepia()**: Memberikan elemen efek warna sephia dengan tingkat tertentu. Nilai 0% membuat elemen tetap berwarna asli, sementara nilai 100% menghasilkan efek sephia penuh.

6. **saturate()**: Mengatur tingkat saturasi warna elemen. Nilai 100% mempertahankan saturasi asli, sementara nilai di atas 100% meningkatkan saturasi dan nilai di bawah 100% mengurangi saturasi.

7. **hue-rotate()**: Memutar roda warna elemen sebesar sudut tertentu. Nilai diukur dalam derajat, di mana 0deg mempertahankan warna asli, sementara nilai positif atau negatif akan merotasi warna sesuai dengan arah jarum jam atau berlawanan arah jarum jam.

8. **invert()**: Membalikkan warna elemen, di mana nilai 0% mempertahankan warna asli dan nilai 100% menghasilkan efek negatif lengkap.

Dengan menggunakan properti filter ini, Kita dapat memberikan efek visual yang menarik dan meningkatkan tampilan elemen dalam halaman web yang kalian buat.