# AND
## Struktur Query
```mysql
SELECT kolom1,kolom2 FROM [nama_tabel] WHERE kolom1="nilai" AND kolom2="nilai2";
```
## Contoh Query
```mysql
SELECT warna,pemilik FROM mobil WHERE warna="BIRU" AND pemilik="HASIZA";
```
## Hasil

## Analisis
- SELECT *: Bagian kueri ini menentukan bahwa Anda ingin mengambil semua kolom dari tabel.
- FROM mobil: Ini menunjukkan bahwa Anda menanyakan tabel "mobil".
- WHERE warna="Hitam" AND pemilik="Ibrahim": Ini adalah kondisi untuk memfilter baris. Ini menetapkan bahwa Anda hanya menginginkan baris yang kolom "warna" sama dengan "Hitam" dan kolom "pemilik" sama dengan "Ibrahim".
## Kesimpulan
"SELECT * FROM mobil WHERE warna='Hitam' AND pemilik='Ibrahim'" adalah bahwa perintah tersebut akan mengambil semua data dari tabel "mobil" yang memiliki nilai kolom "warna" sama dengan "Hitam" dan nilai kolom "pemilik" sama dengan "Ibrahim", perintah ini akan mengembalikan semua baris dari tabel "mobil" yang memenuhi kedua kriteria tersebut. 
# OR
## Struktur Query
```MYSQL
SELECT kolom1,kolom2 FROM [nama_tabel] WHERE kolom1="nilai" AND kolom2="nilai2";
```

## Contoh Query
```MYSQL
SELECT warna,pemilik FROM mobil WHERE warna="BIRU" OR pemilik="HASIZA";
```
## Hasil

## Analisis
- Kolom "warna" memiliki nilai "Hitam".
- Kolom "pemilik" memiliki nilai "Ibrahim".
Dalam hal ini, perintah `SELECT *`digunakan untuk mengambil semua kolom (semua atribut) dari tabel "mobil". `FROM mobil`menunjukkan bahwa tabel yang dimaksud adalah “mobil”. Kondisi `WHERE`digunakan untuk memfilter baris-baris dalam tabel "mobil". Operator OR menunjukkan bahwa setidaknya salah satu kondisi harus dipenuhi agar baris tersebut diambil. Jadi, baris akan diambil jika warna mobil adalah "Hitam" atau jika pemilik mobil adalah "Ibrahim".
## Kesimpulan
Kesimpulan "SELECT * FROM mobil WHERE warna='Hitam' OR pemilik='Ibrahim'; adalah bahwa Anda sedang mencari semua data dari tabel "mobil" di mana nilai kolom "warna" sama dengan "Hitam" atau nilai kolom "pemilik" sama dengan "Ibrahim".
# BETWEEN 
## Struktur Query
```MYSQL
SELECT * FROM [nama_tabel] WHERE kolom1 BETWEEN nilai1 AND nilai2;
```
## Contoh Query
```MYSQL
SELECT * FROM mobil WHERE harga_rental BETWEEN 50000 AND 100000;
```
## Hasil

## Analisis
- SELECT : Ini merupakan bagian dari perintah SELECT yang digunakan untuk menentukan kolom mana yang ingin Anda ambil dari tabel. Dalam hal ini, tanda "" digunakan untuk mengambil semua kolom yang ada di tabel "mobil".
- FROM mobil : Ini menentukan bahwa data akan diambil dari tabel bernama "mobil".
- WHERE harga_rental BETWEEN 100000 AND 150000 : Ini adalah klausul WHERE yang digunakan untuk memfilter baris yang akan diambil berdasarkan kondisi tertentu. Dalam hal ini, kondisi yang digunakan adalah "harga_rental BETWEEN 100000 AND 150000".
- Operator BETWEEN digunakan untuk memeriksa apakah nilai kolom "harga_rental" berada di antara dua angka yang diberikan, yaitu 100.000 dan 150.000.
## Kesimpulan
Kesimpulan "SELECT * FROM mobil WHERE harga_rental BETWEEN 100000 AND 150000;" adalah bahwa perintah tersebut digunakan untuk mengambil semua data dari tabel "mobil" yang memenuhi kondisi harga_rental berada di antara 100.000 dan 150.000. 
# NOT BETWEEN
## Struktur Query
```MYSQL
SELECT * FROM [nama_tabel] WHERE kolom1 BETWEEN nilai1 AND nilai2;
```
## Contoh Query
```MYSQL
SELECT * FROM mobil WHERE harga_rental NOT BETWEEN 100000 AND 1500000;
```
## Hasil

## Analisis
- `SELECT `: Bagian ini menentukan bahwa Anda ingin mengambil semua kolom dari tabel yang ditentukan.
- FROM mobil: Ini menunjukkan bahwa Anda menanyakan tabel bernama mobil.
- WHERE harga_rental NOT BETWEEN 100000 AND 150000: Ini adalah kondisi yang memfilter baris. Ini hanya memilih baris yang nilai kolomnya `harga_rental`tidak berada dalam kisaran 100.000 dan 150.000.
## Kesimpulan
Kesimpulan "SELECT * FROM mobil WHERE harga_rental NOT BETWEEN 100000 AND 150000;" adalah bahwa perintah tersebut digunakan untuk mengambil semua data dari tabel "mobil" di mana harga_rental tidak berada di antara 100.000 dan 150.000. 

# <=
## Struktur
```mysql
SELECT * FROM mobil WHERE harga_rental <= 50000;
```
## Contoh
```mysql
SELECT * from mobil WHERE harga_rental <= 50000;
```
## Hasil

## Analisis
- SELECT *: Bagian kueri ini digunakan untuk menentukan kolom yang ingin Anda ambil. Tanda bintang `(*)`adalah karakter wildcard yang mewakili semua kolom dalam tabel "mobil".
- FROM mobil: Menentukan tabel tempat Anda ingin mengambil data, dalam hal ini, tabel "mobil".
- WHERE harga_rental <= 50000: Ini adalah kondisi yang memfilter baris berdasarkan kriteria tertentu. Dalam hal ini, ia hanya memilih baris yang nilai di kolom "harga_rental" kurang dari atau sama dengan 50000.
## Kesimpulan
Kesimpulan "SELECT * FROM mobil WHERE harga_rental <= 50000;" adalah bahwa Anda mencari semua data dari tabel "mobil" di mana nilai kolom "harga_rental" kurang dari atau sama dengan 50000.
# >=
## Struktur

```mysql
SELECT * FROM mobil WHERE harga_rental >= 50000;
```
## Contoh

```mysql
SELECT * FROM mobil WHERE harga_rental >= 50000;
```
## Hasil

## Analisis
 - SELECT digunakan untuk memilih kolom atau data yang ingin ditampilkan dalam hasil query.
- Tanda bintang ('*')  setelah kata kunci SELECT menunjukkan bahwa semua kolom dalam tabel "mobil" akan ditampilkan dalam hasil query.
- FROM digunakan untuk menentukan tabel yang akan digunakan dalam query. Dalam kasus ini, tabel yang digunakan adalah "mobil".
- WHERE digunakan untuk melakukan filter atau seleksi pada baris-baris data yang memenuhi kondisi tertentu.
- Kondisi harga_rental >= 50000 menunjukkan bahwa hanya baris-baris data yang memiliki nilai harga_rental yang lebih besar atau sama dengan 50000 yang akan ditampilkan.
## Kesimpulan
Perintah SQL SELECT * FROM mobil WHERE harga_rental >= 50000; digunakan untuk mengambil semua data (semua kolom) dari tabel "mobil" di mana nilai pada kolom "harga_rental" lebih besar atau sama dengan 50000.
# <> ATAU !=
## Struktur Query
```MYSQL
SELECT * FROM [nama_tabel] where kolom1 <> nilai1;

SELECT * FROM [nama_tabel] where kolom1 != nilai1;
```
## Contoh Query
```MYSQL
SELECT * FROM mobil where harga_rental <> 100000;

SELECT * FROM mobil where harga_rental != 50000;
```
## Hasil

## Analisis
- SELECT : Ini menentukan bahwa Anda ingin memilih semua kolom dari tabel.
- FROM mobil : Ini menentukan nama tabel "mobil" dari mana Anda ingin mengambil datanya.
- WHERE harga_rental <> 50000 : Ini adalah kondisi yang memfilter baris. Ini hanya memilih baris dimana nilai di kolom "harga_rental" tidak sama dengan 50000.
## Kesimpulan
Kesimpulan dari  "SELECT * FROM mobil WHERE harga_rental <> 50000;" adalah bahwa pernyataan tersebut akan mengembalikan semua baris dari tabel "mobil" di mana nilai kolom "harga_rental" tidak sama dengan 50000.
# TANTANGAN LOGIN
## IN
### Struktur Query
```MYSQL
SELECT * FROM [nama_tabel] WHERE [nama_kolom1] IN("nilai1","nilai2");
```
### Contoh Query
```MYSQL
SELECT * FROM mobil WHERE warna IN("Silver","Merah");
```
## Hasil

## Analisis
1. SELECT * FROM mobil : Pernyataan ini memilih semua kolom dari tabel "mobil".
2. WHERE warna IN ('Silver', 'Merah') : WHERE digunakan untuk menerapkan kondisi pada hasil query. kondisi yang diterapkan adalah "warna IN ('Silver', 'Merah')", yang berarti hanya baris dengan nilai kolom "warna" yang sama dengan 'Silver' atau 'Merah' yang akan diambil.
## Kesimpulan
Query ini akan mengambil semua baris dari tabel "mobil" di mana nilai kolom "warna" adalah 'Silver' atau 'Merah'. query ini akan mengembalikan semua informasi tentang mobil-mobil yang memiliki warna 'Silver' atau 'Merah'. Hasilnya akan berupa kumpulan baris yang mewakili mobil-mobil dengan warna yang sesuai dengan kriteria tersebut.

## IN + AND
### Struktur Query
```MYSQL
SELECT * FROM [nama_tabel]
-> WHERE [nama_kolom1] IN ("nilai1","nilai2")
-> AND [nama_kolom2] = nilai;
```
### Contoh Query
```MYSQL
SELECT * FROM [nama_tabel]
-> WHERE warna IN ("Silver","Merah")
-> AND harga_rental = 50000;
```
## Hasil

## Analisis
1. SELECT * FROM mobil : memilih semua kolom (*) dari tabel "mobil".
2. WHERE warna in('Hitam','Silver') AND harga_rental = 50000 : Pernyataan WHERE digunakan untuk menerapkan kondisi pada hasil query. terdapat dua kondisi yang diterapkan :
- Kondisi pertama adalah "warna IN ('Hitam', 'Silver')", yang berarti hanya baris dengan nilai kolom "warna" yang sama dengan 'Hitam' atau 'Silver' yang akan diambil.
- Kondisi kedua adalah "harga_rental = 50000" , yang berarti hanya baris dengan nilai kolom "harga_rental" yang sama dengan 50000 yang akan diambil.
## Kesimpulan
Kesimpulan dari SQL tersebut adalah mencari semua entri (baris) dalam tabel "mobil" di mana nilai kolom "warna" adalah 'Hitam' atau 'Silver', dan nilai kolom "harga_rental" adalah 50000. query tersebut akan mengembalikan semua data mobil yang memiliki warna 'Hitam' atau 'Silver' dan memiliki harga rental sebesar 50000.


## IN + OR
### Struktur Query
```MYSQL
SELECT * FROM [nama_tabel]
-> WHERE [nama_kolom1] IN ("nilai1","nilai2")
-> OR [nama_kolom2] = nilai;
```
### Contoh Query
```MYSQL
SELECT * FROM [nama_tabel]
-> WHERE warna IN ("Hitam","Merah")
-> OR harga_rental = 150000;
```
## Hasil

## Analisis
- SELECT * : Ini memilih semua kolom dari tabel.
- FROM mobil : Ini menentukan nama tabel sebagai "mobil" dari mana data akan diambil.
- WHERE warna IN ('Hitam', 'Silver') : Kondisi ini memfilter baris berdasarkan nilai pada kolom "warna". Ini memilih baris di mana kolom "warna" memiliki nilai 'Hitam' atau 'Silver'.
- OR harga_rental = 50000 : Kondisi ini memfilter lebih lanjut baris-baris tersebut dengan memilih baris-baris yang kolom "harga_rental"-nya bernilai 50000.
## Kesimpulan
Kesimpulan SQL adalah untuk mengambil semua data dari tabel "mobil" dimana warna mobil adalah 'Hitam' atau 'Silver', atau harga rental mobil adalah 50000. menggabungkan kondisi OR antara warna mobil dan harga rental, hasilnya akan mencakup semua mobil yang memiliki warna 'Hitam' atau 'Silver', dan juga mobil dengan harga rental sebesar 50000, termasuk mobil yang memenuhi salah satu atau kedua kondisi tersebut.

## IN + AND + OPERATOR
## Struktur
```mysql
select * from nama_tabel
-> where nama_kolom in('nilai1','nilai2')
-> AND nama_kolom > nilai3
```
```mysql
select * from nama_tabel
-> where nama_kolom in('nilai1','nilai2')
-> AND nama_kolom > nilai3
```
## Contoh

```mysql
 SELECT * FROM mobil
-> WHERE warna in('Hitam','Silver')
-> AND harga_rental > 50000;
```
```mysql
 SELECT * FROM mobil
-> WHERE warna in('Hitam','Silver')
-> AND harga_rental > 50000;
```

## Hasil
]] 

## Analisis
- Tabel yang diambil tidak disebutkan secara eksplisit dalam pernyataan, hanya disebutkan sebagai `nama_tabel`.
- Kondisi pertama adalah `nama_kolom` harus sama dengan 'nilai1' atau 'nilai2', yang didefinisikan dengan klausa `IN ('nilai1', 'nilai2')`.
- Kondisi kedua adalah `nama_kolom` harus lebih besar dari `nilai3`.
- Perlu diperhatikan bahwa penggunaan `nama_tabel` dan `nama_kolom` tidak spesifik dalam contoh ini. Dalam implementasi yang sebenarnya, Anda akan mengganti `nama_tabel` dengan nama tabel yang sebenarnya dan `nama_kolom` dengan nama kolom yang relevan dalam tabel tersebut.
- - Tabel yang diambil adalah `mobil`.
- Kondisi pertama adalah `warna` harus sama dengan 'Hitam' atau 'Silver', yang didefinisikan dengan klausa `IN ('Hitam', 'Silver')`.
- Kondisi kedua adalah `harga_rental` harus lebih besar dari 50000.
- Hasil dari pernyataan ini akan mengembalikan semua kolom dari baris-baris yang memenuhi kedua kondisi tersebut.
##  Kesimpulan
kedua pernyataan SQL ini digunakan untuk mengambil data dari tabel tertentu dengan beberapa kondisi, yang didefinisikan dengan klausa WHERE.

# TANTANGAN
# LIKE
## Mencari Awalan 
### Struktur 
```mysql
SELECT * FROM mobil
-> WHERE pemilik LIKE 'ib%';
```
## Contoh
```mysql
SELECT * FROM mobil
-> WHERE pemilik LIKE 'ib%';
```
## Hasil 


### Analisis
1. SELECT * FROM mobil : Ini akan mengambil semua kolom dari tabel mobil.
2. WHERE pemilik LIKE '%m' : Ini akan memfilter data hanya untuk mobil yang dimiliki oleh pemilik yang nama terakhirnya adalah 'm' atau berisi huruf 'm'. Tanda persen '%' digunakan sebagai wildcard untuk mencari nama pemilik yang mengakhiri dengan 'm' atau berisi huruf 'm' di mana saja.
### Kesimpulan
Query ini akan mengambil data dari tabel mobil yang dimiliki oleh pemilik dengan nama terakhir 'm' atau berisi huruf 'm'. Hasil dari query ini akan menampilkan semua kolom dari tabel mobil yang memenuhi
## Mencari awalan & akhiran
### Struktur

```mysql
SELECT * FROM mobil
-> WHERE pemilik LIKE 'b%m';
```
### Contoh
```mysql
SELECT * FROM mobil
-> WHERE pemilik LIKE 'b%m';
```

### Hasil

### Analisis
1. SELECT * FROM mobil : Ini akan mengambil semua kolom dari tabel mobil.
2. WHERE pemilik LIKE 'b%m' : Ini akan memfilter data hanya untuk mobil yang dimiliki oleh pemilik yang nama awalnya dimulai dengan huruf 'b' dan nama terakhirnya berakhir dengan huruf 'm'. Tanda persen '%' digunakan sebagai wildcard untuk mencari nama pemilik yang dimulai dengan huruf 'b' dan mengikuti dengan karakter apapun, lalu diakhiri dengan huruf 'm'.
### Kesimpulan
tabel mobil yang dimiliki oleh pemilik dengan nama awal dimulai dengan huruf 'b' dan nama terakhir berakhir dengan huruf 'm'. Hasil dari query ini akan menampilkan semua kolom dari tabel mobil
## Mencari total karakter
### Struktur
```mysql
SELECT * FROM mobil
-> WHERE pemilik LIKE 'I__';
```

```mysql
 SELECT * FROM mobil
-> WHERE pemilik LIKE '___';
```
### Contoh
```mysql
SELECT * FROM mobil
-> WHERE pemilik LIKE 'I__';
```

```mysql
 SELECT * FROM mobil
-> WHERE pemilik LIKE '___';
```
### Hasil



### Analisis
- * SELECT _ :_ Bagian ini memerintahkan database untuk mengambil semua kolom dari `mobil`tabel.
- *FROM mobil:* Ini menentukan tabel dari mana data akan diambil. Dalam hal ini, itu adalah `mobil`meja.
- *WHERE pemilik LIKE 'I__'* : Klausa ini memfilter hasil berdasarkan nilai di `pemilik`kolom. Operator `LIKE`digunakan untuk pencocokan pola.
- pemilik: Ini mengacu pada kolom nama yang berisi informasi pemilik.
- 'I__': Ini adalah pola yang harus dicocokkan. Tanda kutip tunggal menunjukkan string literal. Di sini, 'I__' mewakili pemilik yang namanya dimulai dengan huruf 'I' diikuti dengan dua garis bawah (dua karakter apa saja).

- *SELECT _:_ Instruksi ini meminta untuk memilih semua kolom (atribut) dari tabel mobil.
- *FROM mobil:* Ini menentukan tabel tempat data akan diambil, yaitu tabel mobil.
- *WHERE pemilik LIKE '_':* Ini adalah klausa WHERE yang memfilter data berdasarkan kriteria tertentu.
- *pemilik:* Ini adalah nama kolom yang akan difilter. Biasanya ini mewakili nama pemilik kendaraan.
- *MENYUKAI '_'* :
- *LIKE*: Operator yang digunakan untuk mencari pola tertentu dalam string.
- *'_'*: Adalah pola pencarian yang digunakan.
- ___ - Mencocoki *tiga karakter apapun* (wildcard).
### Kesimpulan
- *(LIKE 'I__' ): Mencari pemilik yang **diawali dengan huruf "I", diikuti oleh dua karakter apapun*. Ini akan mengembalikan pemilik dengan nama minimal 3 karakter.
- *(LIKE '_' ): Mencari pemilik yang memiliki nama dengan **panjang tepat 3 karakter apapun*.
## Kombinasi
### Struktur
```mysql
SELECT * FROM mobil
-> WHERE pemilik LIKE '__r%';
```

```mysql
SELECT * FROM mobil
-> WHERE pemilik LIKE '_b%';
```
### Contoh
```mysql
SELECT * FROM mobil
-> WHERE pemilik LIKE '__r%';
```

```mysql
SELECT * FROM mobil
-> WHERE pemilik LIKE '_b%';
```
### Hasil


### Analisis
- Mencari semua data dari tabel mobil (SELECT *).
- Di mana nilai pada kolom pemilik (WHERE pemilik LIKE '__r%'):
- *LIKE*: Operator untuk mencari pola dalam string.
- *'__r%'*: Pola pencarian yang digunakan.
- __ : Mencocoki dua karakter apapun (wildcard).
- r : Mencari huruf "r" secara literal.
- % : Mencocoki nol karakter atau lebih karakter apapun.

- Mencari semua data dari tabel mobil (`SELECT` *).
- Di mana nilai pada kolom pemilik (`WHERE pemilik LIKE '_b%'`):
- *LIKE*: Operator untuk mencari pola dalam string.
- *'_b%': Pola pencarian yang digunakan.
- `_` : Mencocoki satu karakter apapun.
- `b` : Mencari huruf "b" secara literal.
- % : Mencocoki nol karakter atau lebih karakter apapun.
### Kesimpulan
- *(LIKE '__r%' ): Mencari pemilik yang namanya **berakhiran dengan huruf "r"*. Ini akan mengembalikan pemilik dengan nama minimal 3 karakter.
- *(LIKE '_b%' ): Mencari pemilik yang namanya memiliki huruf "b" di **posisi kedua*. Ini akan mengembalikan pemilik dengan nama minimal 3 karakter.
## NOT LIKE
### Struktur
```mysql
SELECT * FROM mobil WHERE peminjam NOT LIKE 'A%';
```
### Contoh
```mysql
SELECT * FROM mobil WHERE peminjam NOT LIKE 'A%';
```
### Hasil

### Analisis
1. SELECT * FROM mobil : Ini akan mengambil semua kolom dari tabel mobil.
2. WHERE peminjam NOT LIKE 'A%' : Ini akan memfilter data hanya untuk mobil yang saat ini tidak dipinjam oleh peminjam yang nama awalnya dimulai dengan huruf 'A'. Tanda persen '%' digunakan sebagai wildcard untuk mencari nama peminjam yang dimulai dengan huruf 'A' dan mengikuti dengan karakter apapun. Tanda negasi 'NOT' digunakan untuk mengecualikan peminjam dengan nama awal yang dimulai dengan huruf 'A'.
### Kesimpulan
Kesimpulan "SELECT * FROM mobil WHERE peminjam NOT LIKE 'A%'" adalah bahwa query tersebut akan mengembalikan semua data dari tabel "mobil" dimana nilai kolom "peminjam" tidak dimulai dengan huruf 'A'.

# NULL & NOT NULL
## Mencari data kosong
### Struktur
```sql
SELECT * FROM mobil WHERE peminjam IS NULL;
```
### Contoh
```sql
SELECT * FROM mobil WHERE peminjam IS NULL;
```
### Hasil

### Analisis
- *SELECT _:_ Menginstruksikan untuk memilih semua kolom (atribut) dari tabel mobil.
- *FROM mobil:* Mendefinisikan tabel tempat data akan diambil, yaitu tabel mobil.
- *WHERE peminjam IS NULL:* Ini adalah klausa WHERE yang memfilter data berdasarkan kondisi tertentu.
- *peminjam:* Merujuk pada kolom pada tabel mobil yang kemungkinan berisi nama peminjam kendaraan.
- *IS NULL:* Operator perbandingan yang mengecek apakah nilai pada kolom peminjam adalah NULL.
### Kesimpulan
- Perintah ini hanya mengembalikan mobil dengan kolom peminjam bernilai *NULL* (tidak ada data peminjam).
- Perintah ini membantu dalam mengidentifikasi mobil yang tersedia untuk dipinjam.
- Hasilnya bergantung pada data yang ada di kolom peminjam pada tabel mobil.
## Mencari data yang tidak kosong
### Struktur
```sql
SELECT * FROM mobil WHERE peminjam IS NOT NULL;
```
### Contoh
```sql
SELECT * FROM mobil WHERE peminjam IS NOT NULL;
```
### Analisis
1. SELECT *: Ini adalah klausa SELECT yang digunakan untuk memilih semua kolom dari tabel "mobil". Dengan menggunakan tanda bintang (*), kita memilih semua kolom yang ada dalam tabel.
2. FROM mobil: Ini adalah klausa FROM yang menentukan tabel yang akan digunakan dalam kueri. Dalam hal ini, tabel yang digunakan adalah "mobil".
3. WHERE peminjam IS NOT NULL: Ini adalah klausa WHERE yang digunakan untuk menerapkan kondisi pada kueri. Kondisi yang diterapkan di sini adalah "peminjam IS NOT NULL", yang berarti hanya baris-baris di mana kolom "peminjam" tidak kosong atau memiliki nilai yang tidak NULL akan dipilih.
### Kesimpulan
Digunakan untuk mengambil semua baris dari tabel  "mobil"  di mana kolom  "peminjam"  memiliki nilai yang tidak NULL. Hasilnya akan berisi semua kolom dari baris-baris ini.

# ORDER BY
## Mengurutkan data dari terkecil
### Struktur
```sql
SELECT * FROM mobil ORDER BY pemilik ASC;
```
### Contoh
```sql
SELECT * FROM mobil ORDER BY pemilik ASC;
```
### Hasil
### Analisis
- `SELECT * FROM mobil`: Memilih semua kolom dari tabel `mobil`.
- `ORDER BY pemilik ASC`: Mengurutkan hasil berdasarkan kolom `pemilik` secara naik (ascending), artinya hasilnya akan disusun dari nilai `pemilik` yang terkecil ke terbesar.
### Kesimpulan
Pernyataan SQL tersebut akan menghasilkan semua baris dari tabel `mobil`, diurutkan berdasarkan nilai kolom `pemilik` dari yang terkecil ke yang terbesar. Ini berarti baris dengan nilai `pemilik` terkecil akan muncul terlebih dahulu dalam hasil, sedangkan baris dengan nilai `pemilik` terbesar akan muncul terakhir.
## Mengurutkan data dari terbesar
### Struktur
```sql
SELECT * FROM mobil ORDER BY peminjam DESC;
```
### Contoh
```sql
SELECT * FROM mobil ORDER BY peminjam DESC;
```
### Hasil
### Analisis
- `SELECT * FROM mobil`: Memilih semua kolom dari tabel `mobil`.
- `ORDER BY peminjam DESC`: Mengurutkan hasil berdasarkan kolom `peminjam` secara menurun (descending), artinya nilai terbesar `peminjam` akan muncul terlebih dahulu di hasil.
### Kesimpulan
ernyataan SQL tersebut akan menghasilkan semua baris dari tabel `mobil`, diurutkan berdasarkan nilai kolom `peminjam` dari yang terbesar ke yang terkecil. Ini berarti baris dengan nilai `peminjam` terbesar akan muncul terlebih dahulu dalam hasil, sedangkan baris dengan nilai `peminjam` terkecil akan muncul terakhir.

## Membatasi Data Yang Tampil
## Struktur Query

## Contoh Query 

## Hasil

## Analisis

## Kesimpulan
# DISTINCT
## Struktur
```sql
SELECT DISTINCT(pemilik) FROM mobil;
```
## Contoh
```sql
SELECT DISTINCT (harga_rental) FROM mobil ORDER BY harga_rental DESC;
```
## Hasil
## Analisis
- Perintah ini akan mengambil nilai unik dari kolom `pemilik` dari tabel `mobil`.
- Klausa `DISTINCT` digunakan untuk memastikan bahwa setiap nilai yang dikembalikan hanya muncul satu kali.
- Hasil dari perintah ini akan berisi daftar pemilik mobil yang unik, tanpa duplikasi.
- Perintah ini akan mengambil nilai unik dari kolom `harga_rental` dari tabel `mobil`.
- Klausa `DISTINCT` digunakan untuk memastikan bahwa setiap nilai yang dikembalikan hanya muncul satu kali.
- Klausa `ORDER BY harga_rental DESC` mengurutkan hasil berdasarkan `harga_rental` secara menurun (descending), sehingga nilai terbesar akan muncul terlebih dahulu.
- Hasil dari perintah ini akan berisi daftar harga rental yang unik, tanpa duplikasi, yang diurutkan dari harga rental tertinggi ke terendah.
## Kesimpulan
kedua pernyataan SQL ini digunakan untuk mengambil nilai unik dari kolom tertentu dari tabel `mobil`, dengan perintah pertama mengambil pemilik mobil yang unik, dan perintah kedua mengambil harga rental yang unik dan diurutkan dari harga tertinggi ke terendah.

# CONCAT,CONCAT_WS,AS
## Struktur Query

## Menggabungkan kolom tanpa pemisah

### Struktur

```sql

SELECT CONCAT(colom1,colom2) FROM nama tabel;

```

### Contoh

```sql

SELECT CONCAT (pemilik,warna) FROM mobil;

```

### Hasil

### Analisis

- `SELECT` digunakan untuk memilih kolom yang ingin ditampilkan.

- `CONCAT()` menggabungkan dua nilai string menjadi satu.

- `pemilik` dan `warna` adalah kolom dari tabel `mobil`.

### Kesimpulan

perintah tersebut akan menggabungkan nilai dari kolom "pemilik" dan "warna" dalam tabel "mobil" menjadi satu string untuk setiap baris dalam tabel tersebut. Hasilnya akan berupa satu kolom baru yang bernama "CONCAT" yang berisi hasil penggabungan tersebut.

## Menggabungkan kolom dengan pemisah

### Struktur

```sql

SELECT CONCAT_WS ("-",colom1,colom2,colom3) FROM nama tabel ;

```

### Contoh

```sql

SELECT CONCAT_WS ("-",no_plat,no_mesin,id_mobil) FROM mobil;

```

### Hasil

### Analisis

- **`SELECT`** digunakan untuk memilih kolom yang ingin ditampilkan.

- **`CONCAT_WS`** berfungsi untuk menggabungkan beberapa nilai string menjadi satu string, dipisahkan dengan separator yang ditentukan.

    - **`WS`** artinya "With Space" (dengan spasi).

    - **`"-"`** adalah pembatas yang digunakan dalam kueri ini (bisa diganti dengan karakter lain).

- **`no_plat`, `no_mesin`, dan `id_mobil`** adalah kolom dari tabel `mobil`.

### Kesimpulan

kesimpulan dari `SELECT CONCAT_WS("-", no_plat, no_mesin, id_mobil) FROM mobil;` adalah bahwa Anda sedang menggabungkan kolom no_plat, no_mesin, dan id_mobil dalam tabel mobil menjadi satu string dengan menggunakan tanda hubung (-) sebagai pemisah.

## Memberikan nama kolom alias

### Struktur

```sql

SELECT CONCAT_WS ("+",namacolom1,colom2) AS COLLAB FROM nama tabel;

```

### Contoh

```sql

SELECT CONCAT_WS ("+",pemilik,peminjam) AS COLLAB FROM mobil;

```

### Hasil

### Analisis

- **`SELECT`** digunakan untuk memilih kolom yang ingin ditampilkan.

- **`CONCAT_WS`** berfungsi untuk menggabungkan dua nilai string menjadi satu string, dipisahkan dengan separator yang ditentukan.

    - **`WS`** artinya "With Space" (dengan spasi).

    - **`+`** adalah pembatas yang digunakan dalam kueri ini (bisa diganti dengan karakter lain).

- **`pemilik` dan `peminjam`** adalah kolom dari tabel `mobil`.

- **`AS COLLAB`** memberi alias pada kolom baru sebagai "COLLAB".

### Kesimpulan

Kesimpulan dari pernyataan SQL `SELECT CONCAT_WS("+", pemilik, peminjam) AS COLLAB FROM mobil;` adalah bahwa Anda sedang menggabungkan kolom pemilik dan peminjam dalam tabel mobil menjadi satu string dengan menggunakan tanda tambah (+) sebagai pemisah.

# VIEW 
## Struktur Query
Membuat Tabel Virtual
```mysql
Create View Info_no_plat AS Select id_mobil, no_plat, pemilik, peminjam from mobil Where pemilik = "Ibrahim";
```


```mysql
Create View Info_no_plat AS 
→ Select id_mobil, no_plat, pemilik, peminjam 
→ from mobil_rental 
→ Where pemilik = "Ibrahim";
```


Menampilkan Tabel Virtual
```mysql
Select From Info_no_plat;
```


```mysql
Select From Info_no_plat;
```

Menghapus Tabel Virtual
```mysql
Drop View info_no_plat:
```


```mysql
Drop View info_no_plat:
```

## Analisis
- **`CREATE VIEW`** digunakan untuk membuat view baru.

- **`info_no_plat`** adalah nama view yang dibuat.

- **`SELECT`** digunakan untuk memilih kolom yang ingin ditampilkan dalam view.

- **`id_mobil`, `no_plat`, `pemilik`, dan `peminjam`** adalah kolom yang ditampilkan dalam view.

- **`FROM`** menunjukkan tabel sumber data, yaitu `mobil`.

- **`WHERE`** digunakan untuk menyaring data berdasarkan kondisi, yaitu `pemilik = "Ibrahim"`.

### Kesimpulan

Kesimpulan dari `CREATE VIEW info_no_plat AS SELECT id_mobil, no_plat, pemilik, peminjam FROM mobil WHERE pemilik = "Ibrahim";` adalah bahwa Anda sedang membuat sebuah view dengan nama "info_no_plat". View ini akan menampilkan kolom-kolom id_mobil, no_plat, pemilik, dan peminjam dari tabel mobil hanya untuk baris-baris di mana nilai kolom pemilik adalah "Ibrahim".
# TANTANGAN VIEW

  

# AGREGASI

## Sum

Perintah SUM digunakan untuk menghitung total dari nilai-nilai numerik dalam suatu kolom. Ini sering digunakan bersama dengan pernyataan SELECT untuk mengambil hasil agregasi dari data dalam tabel.

### Struktur

```sql

SELECT SUM(nama_colom) AS total

FROM nama_table

WHERE kondisi_opsional;

```

### Contoh

```sql

SELECT SUM(harga_rental) FROM mobil;

```

### Hasil
### Analisis

- `SELECT`: Digunakan untuk mengambil data dari database.

- `SUM()`: Fungsi agregat dalam SQL yang digunakan untuk menghitung jumlah nilai dalam kolom.

- `harga_rental`: Ini adalah nama kolom yang ingin Anda hitung jumlahnya.

- `FROM mobil`: Menentukan tabel dari mana Anda ingin mengambil datanya, dalam hal ini, tabel bernama `mobil`.

### Kesimpulan

Kesimpulan dari pernyataan SQL `SELECT SUM(harga_rental) FROM mobil;` adalah bahwa Anda ingin menghitung jumlah total harga rental dari semua mobil yang ada dalam tabel "mobil".

## Count

Perintah COUNT digunakan untuk menghitung jumlah baris yang memenuhi suatu kondisi atau untuk menghitung jumlah baris dalam suatu tabel.

### Struktur

```sql

SELECT COUNT(*) AS jumlah

FROM nama_tabel

WHERE kondisi_opsional;

```

### Contoh

```sql

SELECT COUNT(pemilik) FROM mobil;

```

  

```sql

SELECT COUNT(peminjam) FROM mobil;

```

### Hasil

### Analisis

**pemilik**

- `SELECT` : Kata kunci ini digunakan untuk mengambil data dari database.

- `COUNT()` : Ini adalah fungsi agregat yang menghitung jumlah baris yang dikembalikan oleh kueri. Dalam hal ini, ia akan menghitung jumlah nilai bukan nol pada kolom "pemilik".

- `pemilik` : Ini nama kolomnya. Fungsi ini `COUNT()`akan menghitung jumlah nilai bukan nol di kolom ini.

- `FROM mobil` : Ini menentukan tabel dari mana data akan diambil. Dalam hal ini, itu adalah tabel "mobil".

**peminjam**

- `SELECT`: Kata kunci ini digunakan untuk mengambil data dari database.

- `COUNT(peminjam)`: Fungsi ini menghitung jumlah nilai bukan nol pada kolom yang ditentukan, dalam hal ini, "peminjam".

- `FROM mobil`: Ini menentukan tabel untuk mengambil data, dalam hal ini, tabel bernama "mobil".

### Kesimpulan

**pemilik**

Kesimpulan dari `SELECT COUNT(pemilik) FROM mobil;` adalah bahwa Anda ingin menghitung jumlah entri unik dalam kolom "pemilik" dari tabel "mobil".

  

**peminjam**

Kesimpulan dari `SELECT COUNT(peminjam) FROM mobil;` adalah bahwa Anda ingin menghitung jumlah entri unik dalam kolom "peminjam" dari tabel "mobil". Hasilnya akan memberikan jumlah peminjam mobil yang terdaftar dalam tabel.

## Min

Fungsi MIN digunakan menemukan nilai minimum dalam suatu kolom. Fungsi ini berguna ketika kita ingin mengetahui nilai terkecil dalam satu set data.

### Struktur

```sql

SELECT MIN(nama_colom) AS nilai_minimum

FROM nama_tabel

WHERE kondisi_opsional;

```

### Contoh

```sql

SELECT MIN(harga_rental) AS MINIMAL FROM mobil;

```

### Hasil

### Analisis

- `SELECT`: Menunjukkan bahwa ingin mengambil data dari database.

- `MIN(harga_rental)`: Menghitung nilai minimum kolom `harga_rental`.

- `AS MINIMAL`: Menetapkan alias `MINIMAL` pada hasil fungsi `MIN(harga_rental)`.

- `FROM mobil`: Menentukan tabel `mobil`untuk mengambil data.

### Kesimpulan

Kesimpulan dari `SELECT MIN(harga_rental) AS MINIMAL FROM mobil;` adalah bahwa Anda ingin mencari nilai terkecil (minimum) dari kolom "harga_rental" dalam tabel "mobil".

## Max

Fungsi MAX digunakan untuk menemukan nilai maksimum dari suatu kolom. Fungsi ini berguna ketika kita ingin mengetahui nilai terbesar dalam satu set data.

### Struktur

```sql

SELECT MAX(nama_colom) AS nilai_maksimum

FROM nama_tabel

WHERE kondisi_opsional;

```

### Contoh

```sql

SELECT MAX(harga_rental) AS MAXIMAL FROM mobil;

```

### Hasil

### Analisis

- `SELECT`: Digunakan untuk mengambil data dari database.

- `MAX(harga_rental)`: Fungsi ini menghitung nilai maksimum kolom 'harga_rental' dan mengambil nilai tertinggi yang ada di kolom itu.

- `AS MAXIMAL`: Mengubah nama hasil perhitungan `MAX(harga_rental)`menjadi 'MAXIMAL'. Itu adalah alias untuk hasilnya.

### Kesimpulan

Kesimpulan dari pernyataan SQL ini adalah bahwa Anda ingin mencari nilai terbesar (maksimum) dari kolom `"harga_rental" dalam tabel "mobil"` . Hasilnya akan disajikan dengan menggunakan alias "MAXIMAL" dalam kolom hasil.

## AVG

Fungsi agregasi yang digunakan untuk menghitung nilai rata-rata

### Struktur

```sql

SELECT AVG(nama_colom) AS rata_rata

FROM nama_tabel

WHERE kondisi_opsional;

```

### Contoh

```sql

SELECT AVG(harga_rental) AS RATA_RATA FROM mobil;

```

### Hasil

### Analisis

- `SELECT AVG(harga_rental)`: Ini adalah perintah SQL yang digunakan untuk mengambil nilai rata-rata dari kolom `harga_rental`. `AVG()` adalah fungsi agregat yang digunakan untuk menghitung rata-rata dari sekumpulan nilai.

- `AS RATA_RATA`: Menggunakan kata kunci `AS` untuk memberi nama pada hasil rata-rata. Dalam hal ini, hasil rata-rata dari `harga_rental` akan dinamai `RATA_RATA`.

- `FROM mobil`: Ini adalah bagian dari perintah SQL yang menunjukkan bahwa data diambil dari tabel bernama `mobil`. Jadi, perintah ini mengambil nilai rata-rata dari kolom `harga_rental` dari tabel `mobil`.

### Kesimpulan

Kesimpulan dari pernyataan SQL `SELECT AVG(harga_rental) AS RATA_RATA FROM mobil;` adalah bahwa Anda ingin menghitung nilai rata-rata (average) dari kolom "harga_rental" dalam tabel "mobil".