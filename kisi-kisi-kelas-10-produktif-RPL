# kisi-kisi-kelas-10-produktif-RPL
MATERI UJI PRAKTERK PHP
## 1.  PERULANGAN
### - FOR
```php
<?php

for($i = 0; $i < 10; $i++){
    echo "<h2>Ini perulangan ke-$i</h2>";
}

?>
```

Veriabel  `$i`  dalam perulangan  _For_  berfungsi sebagai  _counter_  yang menghitung berpa kali ia akan mengulang.

Hitungan akan dimulai dari nol (`0`), karena kita memberikan nilai  `$i = 0`.

Lalu, perulangan akan diulang selama nilai  `$i`  lebih kecil dari  `10`. Artinya, perulangan ini akan mengulang sebanyak  `10x`.

Maksud dari  `$i++`  adalah nilai  `$i`  akan ditambah  `1`  disetiap kali melakukan perulangan.

### - WHILE
```php
<?php 

$ulangi = 0;

while($ulangi < 10){
    echo "<p>Ini adalah perulangan ke-$ulangi</p>";
    $ulangi++;
}

?>
```
Perulangan  _while_  akan terus mengulang selama nilai  `$ulangi`  lebih kecil dari  `10`.

Lalu di dalam perulangan kita melakukan  _increment_  nilai  `$ulangi`  dengan  `$ulangi++`. Artinya: Tambah 1 disetiap pengulangan.
### - DO/WHILE
```php
<?php 

$ulangi = 10;

do {
    echo "<p>ini adalah perulangan ke-$ulangi</p>";
    $ulangi--;
} while ($ulangi > 0);

?>
```
Perulangan  _Do/While_  sama seperti perulangan  _while_. Ia juga tergolong dalam  _uncounted loop_.

Perbedaan  _Do/While_  dengan  _while_  terletak pada cara iya memulai pengulangan.

Perulangan  _Do/While_  akan selalu melakukan pengulangan sebanyak 1 kali, kemudian melakukan pengecekan kondisi.

Sedangkan perulangan  _while_  akan mengecek kondisi terlebih dahulu, baru melakukan pengulangan.
### - FOREACH
```php
<?php
$books = [
    "Panduan Belajar PHP untuk Pemula",
    "Membangun Aplikasi Web dengan PHP",
    "Tutorial PHP dan MySQL",
    "Membuat Chat Bot dengan PHP"
];

echo "<h5>Judul Buku PHP:</h5>";
echo "<ul>";
foreach($books as $buku){
    echo "<li>$buku</li>";
}
echo "</ul>";

?>
```
Perulangan _foreach_ sama seperti perulangan _for_. Namun, ia lebih khusus digunakan untuk mecetak array.
## 1.  PERCABANGAN
### - IF/ELSE
Bentuk yang paling sederhana dari percabganan adalah “If” saja.

Biasanya digunakan saat hanya ada satu tindakan yang harus dilakukan.

Bentuknya seperti ini:

```php
<?php

if (<kondisi>){
    // eksekusi kode ini
}
```

Jika kondisi benar, maka eksekusi kode yang ada di dalamnya.  `<kondisi>`  bisa kita isi dengan nilai  _boolean_  atau kita busa buat pernyataan untuk menghasilkan nilai  _boolean_.

Contoh:

```php
<?php
$total_belanja = 150000;

if($total_belanja > 100000){
    echo "Anda dapat hadiah!";
}
```
## 3.  ARRAY
## Apa itu Array?

Array adalah salah satu struktur data yang berisi sekumpulan data dan memiliki indeks. Indeks digunakan untuk mengakses nilai array.

Indeks array selalu dimulai dari nol (`0`).

Contoh:

![Array](https://www.petanikode.com/img/php/array/array.png)

Jadi, apabila kita ingin menampilkan “Hardisk 2TB”, maka kita harus mengampil indeks yang ke-0.

Untuk leblih jelasnya, mari kita coba…

## 2. Membuat Array di PHP

Array di PHP dapat kita buat dengan fungsi  `array()`  dan tanda kurung kotak  `[]`.

Contoh:

```php
<?php

// membuat array kosong
$buah = array();
$hobi = [];

// membuat array sekaligus mengisinya
$minuman = array("Kopi", "Teh", "Jus Jeruk");
$makanan = ["Nasi Goreng", "Soto", "Bubur"];

// membuat array dengan mengisi indeks tertentu
$anggota[1] = "Dian";
$anggota[2] = "Muhar";
$anggota[0] = "Petani Kode";
```

Cukup mudah bukan.

Oya, array dapat kita isi dengan tipe data apa saja. Bahkan dicampur juga boleh.

Contoh:

```php
<?php

$item = ["Bunga", 123, 39.12, true];
```

## 3. Menampilkan isi Array

Untuk menampilkan isi array, kita bisa mengaksesnya melalui indeks.

Contoh:

```php
<?php
// membuat array
$barang = ["Buku Tulis", "Penghapus", "Spidol"];

// menampilkan isi array
echo $barang[0]."<br>";
echo $barang[1]."<br>";
echo $barang[2]."<br>";
```

Hasilnya:

![Menampilkan Array](https://www.petanikode.com/img/php/array/menampilkan-array.png)

Tapi cara ini kurang efektif, karen akita mencetak satu per satu. Nanti kalau datanya ada 1000, berarti harus ngetik peritnah  `echo`  sebanyak 1000.

Lalu bagaimana donk?

Biasanya kita menggunakan perulangan.

Contoh:

```php
<?php
// membuat array
$barang = ["Buku Tulis", "Penghapus", "Spidol"];

// menampilkan isi array dengan perulangan for
for($i=0; $i < count($barang); $i++){
    echo $barang[$i]."<br>";
}
```

Kita bisa menggunakan fungsi  `count()`  untuk menghitung banyaknya isi array. Pada contoh di atas isi array sebanyak 3, maka perulangan akan dilakukan sebanyak 3x.

Hasilnya:

![Menampilkan Array](https://www.petanikode.com/img/php/array/menampilkan-array.png)
