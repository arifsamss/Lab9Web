# Pemograman Web
~~~
Nama  : Arif Samsudin
NIM   : 311910255
Kelas : TI 19 C1
~~~
# 1. Persiapan
Buat folder baru dengan nama lab9_php_modular pada docroot webserver
(htdocs)
![1  Buat folder](https://user-images.githubusercontent.com/81839328/121774727-f3808900-cbad-11eb-87c2-3c9a66a8d06c.JPG)

# 2. Buat file baru dengan nama header.php
~~~
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Contoh Modularisasi</title>
<link href="style.css" rel="stylesheet" type="text/stylesheet"
media="screen" />
</head>
<body>
<div class="container">
<header>
<h1>Modularisasi Menggunakan Require</h1>
</header>
<nav>
<a href="home.php">Home</a>
<a href="about.php">Tentang</a>
<a href="kontak.php">Kontak</a>
</nav>
~~~
![2  header](https://user-images.githubusercontent.com/81839328/121774895-ca142d00-cbae-11eb-9307-17263c9aa25c.JPG)


# 3. Buat file baru dengan nama footer.php
~~~
<footer>
<p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
</footer>
</div>
</body>
</html>
~~~
![3  footer](https://user-images.githubusercontent.com/81839328/121774920-e1531a80-cbae-11eb-80d0-624cdb364060.JPG)

# 4. Buat file baru dengan nama home.php
~~~
<?php require('header.php'); ?>
<div class="content">
<h2>Ini Halaman Home</h2>
<p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
~~~
![4  home](https://user-images.githubusercontent.com/81839328/121774964-0ba4d800-cbaf-11eb-9c3a-e2e45ed53e4f.JPG)

# 5. Buat file baru dengan nama about.php
~~~
<?php require('header.php'); ?>
<div class="content">
<h2>Ini Halaman About</h2>
<p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
~~~
![5  about](https://user-images.githubusercontent.com/81839328/121775249-aa7e0400-cbb0-11eb-8514-ce384ade7e74.JPG)
