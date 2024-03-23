# Index html
```html
<body>
        <div>
        <table border="0" width="100%" width="100%">
            <tr> 
                <td height="50px" bgcolor="yellow"> Flower Shop </td>  
            </tr>
        </table>
    </div>
```
Analisis :
`Tag <body>`: Ini adalah bagian dari HTML yang menampung semua konten yang akan ditampilkan di halaman web.    
`Tag <div>`: Digunakan untuk mengelompokkan elemen-elemen HTML. Dalam konteks ini, div digunakan untuk mengelompokkan elemen yang akan dimasukkan ke dalam tabel.    
`Tag <table>`: Digunakan untuk membuat tabel di HTML.
`Attribute border="0"`: Ini menentukan bahwa tabel tidak akan memiliki garis pemisah antara sel-selnya.  
`Attribute width="100%" width="100%"`: Ini mencoba membuat tabel menutupi seluruh lebar halaman dengan memberikan 100% lebar pada tabel serta pada satu-satunya kolom yang ada.
`Tag <tr>`: Mendefinisikan baris dalam tabel.   
`Tag <td>`: Mendefinisikan sel dalam tabel. 
`Attribute height="50px"`: Ini menentukan tinggi sel menjadi 50 piksel.  
`Attribute bgcolor="yellow"`: Ini menentukan bahwa warna latar belakang sel adalah kuning.
`Teks "Flower Shop"`: Ini adalah teks yang akan ditampilkan di dalam sel tabel.

```html
    <div align="center">
        <h1> Selamat datang di flower shop </h1>
        <img src="bunga 2.jpg" width="410px" height="410px">
    </div> <br>
```
Analisis : 
`Tag <div>`: Digunakan untuk mengelompokkan elemen-elemen HTML dan dalam konteks ini, digunakan untuk mengatur penataan atau tata letak (layout) elemen-elemen yang berada di dalamnya.  
`Attribute align="center"`: Ini adalah atribut yang digunakan untuk menentukan isi dalam `<table>`untuk `rata kanan`.
`Tag <h1>`: Ini adalah tag yang digunakan untuk menampilkan teks berukuran besar sebagai judul. Di sini, teks yang ditampilkan adalah "Selamat datang di flower shop".
`Tag <img>`: Digunakan untuk menampilkan gambar di halaman web.
`Attribute src="bunga 2.jpg"`: Ini adalah atribut yang menentukan lokasi atau URL dari gambar yang akan ditampilkan. Dalam kasus ini, gambar yang disebut "bunga 2.jpg" akan ditampilkan.
`Attribute width="410px" height="410px"`: Ini adalah atribut yang menentukan lebar dan tinggi gambar dalam piksel. Dalam hal ini, gambar tersebut akan ditampilkan dengan lebar dan tinggi masing-masing 410 piksel.
`Tag <br>`: Ini adalah tag untuk membuat jeda baris (line break). Dalam konteks ini, digunakan setelah elemen `<div>` untuk memberikan jarak vertikal antara elemen `<div>` tersebut dengan elemen-elemen berikutnya.

```html
<div align="center">
            <a href="order bunga.html"> <input type="submit" value="Order Now!"> </a>
    </div> <br>
```
Analisis : 
`Attribute align="center"`: Ini adalah atribut yang digunakan untuk menentukan bahwa konten di dalam `<div>` akan dipusatkan secara horizontal di dalam halaman.  
`Tag <a>`: Ini adalah tag untuk membuat hyperlink atau tautan.  
`Attribute href="order bunga.html"`: Ini adalah atribut yang menentukan URL atau alamat tujuan ketika tautan tersebut diklik. Dalam hal ini, tautan akan mengarah ke halaman "order bunga.html". 
`Tag <input>`: Ini adalah tag untuk membuat elemen input.
`Attribute type="submit"`: Ini menentukan bahwa elemen input adalah tombol submit. 
`Attribute value="Order Now!"`: Ini adalah atribut yang menentukan teks yang akan ditampilkan pada tombol submit. Dalam hal ini, teks yang ditampilkan adalah "Order Now!".
`Tag <br>`: Ini adalah tag untuk membuat jeda baris (line break). Dalam konteks ini, digunakan setelah elemen `<div>` untuk memberikan jarak vertikal antara elemen `<div>` tersebut dengan elemen-elemen berikutnya

```html
<div>
        <table border="1">
            <tr>
                <td colspan="2" bgcolor="aqua" width="1000" align="center"> <a href="list bungaa.html"> List daftar bunga </a></td>
                <td colspan="2" bgcolor="aqua" width="1000" align="center"> <a href="order bunga.html"> Pesan Bunga </a></td>
            </tr>
```
Analisis : 
`Tag <table>`: Digunakan untuk membuat tabel di HTML. 
`Attribute border="1"`: Ini menentukan bahwa tabel akan memiliki garis pembatas di antara setiap selnya.
`Tag <tr>`: Ini adalah tag untuk mendefinisikan baris dalam tabel.
`Tag <td>`: Ini adalah tag untuk mendefinisikan sel dalam tabel. 
`Attribute colspan="2"`: Ini menentukan bahwa sel tersebut akan menggabungkan dua kolom dalam satu baris. Dalam hal ini, setiap hyperlink akan memenuhi dua kolom.  
`Attribute bgcolor="aqua"`: Ini adalah atribut yang menentukan warna latar belakang sel menjadi warna aqua.
`Attribute width="1000"`: Ini menentukan lebar sel menjadi 1000 piksel.
`Attribute align="center"`: Ini menentukan bahwa konten di dalam sel akan dipusatkan secara horizontal di dalam sel.
`Tag <a>`: Ini adalah tag untuk membuat hyperlink atau tautan.  
`Attribute href="list bungaa.html"` dan `href="order bunga.html"`: Ini adalah atribut yang menentukan URL atau alamat tujuan ketika tautan tersebut diklik. Dalam kasus ini, tautan pertama akan mengarah ke halaman "list bungaa.html", sementara tautan kedua akan mengarah ke halaman "order bunga.html"
# List bunga
```html
<body>
        <h1> List Bunga </h1>
        <table border="1"> 
            <tr> 
                <td> Bunga 1 <br> <img src="bunga 1.jpg" width="100"></td>
                <td> 
                <ul>
                    <li> Asal : <b> gunung latimojong </b></li>
                    <li> Keharuman : <b> Tahan lama </b> </li>
                    <li> harga : <b> 75.000 </b> </li>
                </ul>
```
Analisis : 
`Tag <body>`: Ini adalah bagian dari HTML yang menampung semua konten yang akan ditampilkan di halaman web.  
`Tag <h1>`: Ini adalah tag untuk menampilkan teks berukuran besar sebagai judul. Dalam hal ini, judul "List Bunga" akan ditampilkan di halaman web.  
`Tag <table>`: Digunakan untuk membuat tabel di HTML.  
`Attribute border="1"`: Ini menentukan bahwa tabel akan memiliki garis pembatas di antara setiap selnya. 
`Tag <tr>`: Ini adalah tag untuk mendefinisikan baris dalam tabel.  
`Tag <td>`: Ini adalah tag untuk mendefinisikan sel dalam tabel.  
`Teks "Bunga 1"`: Ini adalah teks yang akan ditampilkan di dalam sel tabel.  
`Tag <br>`: Ini adalah tag untuk membuat jeda baris (line break). Dalam konteks ini, digunakan untuk membuat jeda antara teks "Bunga 1" dengan gambar yang akan ditampilkan.  
`Tag <img>`: Digunakan untuk menampilkan gambar di halaman web.
` Attribute src="bunga 1.jpg"`: Ini adalah atribut yang menentukan lokasi atau URL dari gambar yang akan ditampilkan. Dalam kasus ini, gambar yang disebut "bunga 1.jpg" akan ditampilkan. 
`Attribute width="100"`: Ini menentukan lebar gambar dalam piksel. Dalam hal ini, lebar gambar akan disetel menjadi 100 piksel.
`Tag <ul>`: Ini adalah tag untuk membuat daftar yang tidak berurutan (unordered list).  
`Tag <li>`: Ini adalah tag untuk mendefinisikan item dalam daftar.  
`Teks "Asal : gunung latimojong"`: Ini adalah teks yang akan ditampilkan sebagai item pertama dalam daftar.  
`Teks "Keharuman : Tahan lama"`: Ini adalah teks yang akan ditampilkan sebagai item kedua dalam daftar.
`Teks "harga : 75.000"`: Ini adalah teks yang akan ditampilkan sebagai item ketiga dalam daftar.
`Tag <b>`: Ini adalah tag untuk memberi teks cetak tebal.

```html
<td colspan="3" align="center" bgcolor="grey"> kosong </td>
            </tr> 
```
Analisis : 
`Tag <td>`: Ini adalah tag untuk mendefinisikan sel dalam tabel.  
`Attribute colspan="3"`: Ini menentukan bahwa sel tersebut akan menggabungkan tiga kolom dalam satu baris. Dalam konteks ini, sel tersebut akan memenuhi tiga kolom.  
`Attribute align="center"`: Ini menentukan bahwa konten di dalam sel akan dipusatkan secara horizontal di dalam sel.  
`Attribute bgcolor="grey"`: Ini menentukan bahwa warna latar belakang sel tersebut adalah abu-abu (grey).  
`Teks "kosong"`: Ini adalah teks yang akan ditampilkan di dalam sel tabel.

```html
 <tr>
    <td bgcolor="red" align="center" colspan="4"> <a href="order bunga.html"> Pesan Sekarang </a></td>
            </tr>
        </table> <br>
```
Analisis : 
`Tag <tr>`: Ini adalah tag untuk mendefinisikan baris dalam sebuah tabel.
`Tag <td>`: Ini adalah tag untuk mendefinisikan sel dalam tabel.  
`Attribute bgcolor="red"`: Ini menentukan bahwa warna latar belakang dari sel tersebut adalah merah.    
`Attribute align="center"`: Ini menentukan bahwa konten di dalam sel tersebut akan dipusatkan secara horizontal di dalam sel.
`Attribute colspan="4"`: Ini menentukan bahwa sel tersebut akan menggabungkan empat kolom dalam satu baris. Dalam konteks ini, sel tersebut akan memenuhi seluruh lebar tabel karena `colspan` diatur menjadi 4, yang sesuai dengan jumlah total kolom tabel.
`Tag <a>`: Ini adalah tag untuk membuat hyperlink atau tautan.
`Attribute href="order bunga.html"`: Ini adalah atribut yang menentukan URL atau alamat tujuan ketika tautan tersebut diklik. Dalam hal ini, tautan akan mengarah ke halaman "order bunga.html".  
`Teks "Pesan Sekarang"`: Ini adalah teks yang akan ditampilkan sebagai tautan di dalam sel tabel.  
`Tag <br>`: Ini adalah tag untuk membuat jeda baris (line break). Dalam konteks ini, tag `<br>` digunakan setelah penutup tag `</table>` untuk memberikan jarak vertikal antara tabel tersebut dengan elemen-elemen berikutnya.

```html
        <a href="index.html"> kembali ke home </a>
```
Analisis : 
`Tag <a>`: Ini adalah tag untuk membuat hyperlink atau tautan.
`Attribute href="index.html"`: Ini adalah atribut yang menentukan URL atau alamat tujuan ketika tautan tersebut diklik. Dalam kasus ini, tautan akan mengarahkan pengguna ke halaman "index.html".
`Teks "kembali ke home"`: Ini adalah teks yang akan ditampilkan sebagai tautan di dalam halaman web.
# Order bunga
```html
<label for="nama"> <b> nama </b></label> <br>
        <input type="text" id="nama" required> <br> <br>
```
Analisis : 
`Tag <label>`: Ini adalah tag untuk menautkan teks deskripsi (label) dengan elemen input pada formulir HTML.    
`Attribute for="nama"`: Ini menentukan bahwa label tersebut terkait dengan elemen input yang memiliki atribut `id` bernilai "nama". Ketika label ini diklik, fokus akan dipindahkan ke elemen input yang terkait.  
`Tag <b>`: Ini adalah tag untuk memberi teks cetak tebal.
`Teks "nama"`: Ini adalah teks yang akan ditampilkan di dalam label. Dalam hal ini, teks tersebut ditampilkan dalam cetak tebal karena dikelilingi oleh tag `<b>`.
`Tag <input>`: Ini adalah tag untuk membuat elemen input dalam formulir HTML.  
`Attribute type="text"`: Ini menentukan bahwa elemen input tersebut adalah input teks.  
`Attribute id="nama"`: Ini adalah atribut yang memberikan identifikasi unik untuk elemen input. Label menggunakan atribut `for` untuk mengaitkan dirinya dengan elemen input yang memiliki id yang sama.  
`Attribute required`: Ini menentukan bahwa pengguna harus memasukkan nilai ke dalam elemen input ini sebelum mengirimkan formulir. Jika tidak, formulir tidak akan dapat disubmit.  
`Tag <br>`: Ini adalah tag untuk membuat jeda baris (line break). Dalam konteks ini, digunakan untuk membuat jeda antara elemen label, elemen input, dan elemen-elemen berikutnya dalam halaman HTML.

```html
<label for="Jenis Bunga"> Jenis Bunga : </label> <br>
        <select id="jenis bunga" name="bunga">
            <option disabled> --- Pilih Bunga --- </option>
            <option value="Bunga 1">  Bunga 1 </option>
            <option value="Bunga 2"> Bunga  2</option>
            <option value="Bunga 3">  Bunga 3</option>
            <option value="Bunga 4">  Bunga 4</option>
            <option value="Bunga 5">  Bunga 5 </option>
        </select> <br> <br>
```
Analisis : 
`Tag <label>`: Ini adalah tag untuk menautkan teks deskripsi (label) dengan elemen input pada formulir HTML.    
`Attribute for="Jenis Bunga"`: Ini menentukan bahwa label tersebut terkait dengan elemen input yang memiliki atribut `id` bernilai "Jenis Bunga". Ketika label ini diklik, fokus akan dipindahkan ke elemen input yang terkait.
`Teks "Jenis Bunga :" `: Ini adalah teks yang akan ditampilkan di dalam label, memberi petunjuk kepada pengguna tentang informasi yang diharapkan untuk diinput atau dipilih.      
`Tag <select>`: Ini adalah tag untuk membuat sebuah dropdown list atau daftar pilihan.  
`Attribute id="jenis bunga"`: Ini adalah atribut yang memberikan identifikasi unik untuk elemen dropdown list ini.      
`Attribute name="bunga"`: Ini adalah atribut yang memberikan nama untuk elemen dropdown list ini, yang akan digunakan ketika formulir dikirimkan.      
`Tag <option>`: Ini adalah tag untuk menentukan pilihan dalam dropdown list.  
`Attribute disabled`: Ini menandakan bahwa opsi tersebut tidak dapat dipilih oleh pengguna. Ini digunakan untuk opsi pertama yang berfungsi sebagai label atau instruksi untuk pengguna.      
`Teks "--- Pilih Bunga ---" `: Ini adalah teks yang ditampilkan sebagai opsi pertama dalam dropdown list, memberikan instruksi kepada pengguna untuk memilih salah satu opsi yang tersedia.
`Attribute value="Bunga 1"`: Ini menentukan nilai yang akan dikirimkan ke server ketika opsi tersebut dipilih. Dalam hal ini, nilai yang akan dikirim adalah "Bunga 1".
`Teks "Bunga 1" `: Ini adalah teks yang akan ditampilkan sebagai pilihan pertama dalam dropdown list.      
Selanjutnya, langkah-langkah 3 (untuk membuat opsi dalam dropdown list) diulang untuk setiap pilihan yang tersedia dalam dropdown list.
`Tag <br>`: Ini adalah tag untuk membuat jeda baris (line break). Dalam konteks ini, digunakan untuk membuat jeda antara elemen label, dropdown list, dan elemen-elemen berikutnya dalam halaman HTML.

```html
		<b>Jenis Pembayaran:</b><br>
        <input type="radio" name="jk"><label>Tunai</label>
        <input type="radio" name="jk"><label>Transfer</label><br><br>
        
        <b>Alamat Pengiriman:</b><BR>
        <textarea cols="35" rows="7"></textarea><br><br>
        
        <b>Waktu Pengiriman:</b><br>
        <input type="checkbox"><label>Pagi</label>
        <input type="checkbox"><label>Siang</label>
        <input type="checkbox"><label>Sore</label>
        <input type="checkbox"><label>Malam</label>
        <br><br>

        <input type="submit" value="Pesan">
        <input type="reset" value="Hapus">
        <br><br>
        <hr>

        <a href="list.html">Lihat Daftar Bunga</a><br>
        <a href="index.html">Kembali ke Home</a>

    </form>
</body>
</html>
```
Analisis :
    - `<input type="radio" name="jk">`: Elemen input radio digunakan untuk memilih jenis pembayaran.
    - `<label>Tunai</label>`: Elemen label digunakan untuk memberikan deskripsi opsi "Tunai" pada elemen radio.
    - `<label>Transfer</label>`: Elemen label digunakan untuk memberikan deskripsi opsi "Transfer" pada elemen radio.
    - Fungsi: Elemen radio ini memungkinkan pengguna untuk memilih antara pembayaran "Tunai" atau "Transfer".
    - `<textarea cols="35" rows="7"></textarea>`: Elemen textarea digunakan untuk memasukkan alamat pengiriman.
    - Fungsi: Elemen textarea ini memungkinkan pengguna untuk memasukkan alamat pengiriman dengan lebih banyak ruang teks daripada elemen input biasa.
    - `<input type="checkbox">`: Elemen input checkbox digunakan untuk memilih waktu pengiriman.
    - `<label>Pagi</label>`, `<label>Siang</label>`, `<label>Sore</label>`, `<label>Malam</label>`: Elemen label digunakan untuk memberikan deskripsi opsi waktu pengiriman pada elemen checkbox.
    - Fungsi: Elemen checkbox ini memungkinkan pengguna untuk memilih beberapa opsi waktu pengiriman, seperti "Pagi", "Siang", "Sore", dan "Malam".
    - `<input type="submit" value="Pesan">`: Elemen input submit digunakan sebagai tombol "Pesan" untuk mengirimkan formulir pemesanan.
    - `<input type="reset" value="Hapus">`: Elemen input reset digunakan sebagai tombol "Hapus" untuk menghapus data yang dimasukkan dalam formulir.
    - Fungsi: Tombol "Pesan" akan mengirimkan data formulir ke server atau pemrosesan selanjutnya. Tombol "Hapus" akan menghapus data yang dimasukkan dalam formulir dan mengembalikan ke keadaan awal.
    - `<a href="list.html">Lihat Daftar Bunga</a>`: Elemen anchor (`<a>`) digunakan untuk membuat tautan ke halaman "list.html" yang menampilkan daftar bunga.
    - `<a href="index.html">Kembali ke Home</a>`: Elemen anchor (`<a>`) digunakan untuk membuat tautan ke halaman "index.html" yang merupakan halaman beranda.
    - Fungsi: Tautan ini memungkinkan pengguna untuk beralih antara halaman "list.html" dan "index.html" dengan mengklik tautan tersebut.