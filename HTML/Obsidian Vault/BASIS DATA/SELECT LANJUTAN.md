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

## Kesimpulan

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
## Kesimpulan
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
## Kesimpulan
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
## Kesimpulan

# >=
## Struktur Query
```MYSQL
SELECT * FROM [nama_tabel] WHERE kolom1 nilai1 <= nilai2;
```
## Contoh Query
```MYSQL
SELECT * FROM [nama_tabel] WHERE harga_rental <= 100000;
```
## Hasil

## Analisis
## Kesimpulan

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
## Kesimpulan

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
### Hasil

### Analisis

### Kesimpulan

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
### Hasil

### Analisis
### Kesimpulan

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
### Hasil

### Analisis
### Kesimpulan

## IN + AND + OPERATOR
### Struktur Query

### Contoh Query

### Hasil

### Analisis
### Kesimpulan