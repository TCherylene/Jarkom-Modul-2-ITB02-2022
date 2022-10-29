# Jarkom-Modul-2-ITB02-2022

Anggota kelompok:

1. Asima Prima Yohana Tampubolon - 5027201009
2. Cherylene Trevina - 5027201033
3. Fatih Rian Hibatul Hakim - 5027201066

Daftar Isi:

* [Bentuk Topologi](#bentuk-topologi)
* [Nomor 1](#nomor-1)
* [Nomor 2](#nomor-2)
* [Nomor 3](#nomor-3)
* [Nomor 4](#nomor-4)
* [Nomor 5](#nomor-5)
* [Nomor 6](#nomor-6)
* [Nomor 7](#nomor-7)
* [Nomor 8](#nomor-8)
* [Nomor 9](#nomor-9)
* [Nomor 10](#nomor-10)
* [Nomor 11](#nomor-11)
* [Nomor 12](#nomor-12)
* [Nomor 13](#nomor-13)
* [Nomor 14](#nomor-14)
* [Nomor 15](#nomor-15)
* [Nomor 16](#nomor-16)
* [Nomor 17](#nomor-17)

# Bentuk Topologi

Berikut adalah topologi yang kami gunakan:

![Topologi](images/topologi.png)

# Nomor 1

WISE akan dijadikan sebagai DNS Master, Berlint akan dijadikan DNS Slave, dan Eden akan digunakan sebagai Web Server. Terdapat 2 Client yaitu SSS, dan Garden. Semua node terhubung pada router Ostania, sehingga dapat mengakses internet (1).

# Jawaban1

abc

# Nomor 2

Untuk mempermudah mendapatkan informasi mengenai misi dari Handler, bantulah Loid membuat website utama dengan akses wise.yyy.com dengan alias www.wise.yyy.com pada folder wise (2).

# Jawaban2

abc

# Nomor 3

Setelah itu ia juga ingin membuat subdomain eden.wise.yyy.com dengan alias www.eden.wise.yyy.com yang diatur DNS-nya di WISE dan mengarah ke Eden (3).

# Jawaban3

abc

# Nomor 4

Buat juga reverse domain untuk domain utama (4).

# Jawaban4

abc

# Nomor 5

Agar dapat tetap dihubungi jika server WISE bermasalah, buatlah juga Berlint sebagai DNS Slave untuk domain utama (5).

# Jawaban5

abc

# Nomor 6

Karena banyak informasi dari Handler, buatlah subdomain yang khusus untuk operation yaitu operation.wise.yyy.com dengan alias www.operation.wise.yyy.com yang didelegasikan dari WISE ke Berlint dengan IP menuju ke Eden dalam folder operation (6).

# Jawaban6

abc

# Nomor 7

Untuk informasi yang lebih spesifik mengenai Operation Strix, buatlah subdomain melalui Berlint dengan akses strix.operation.wise.yyy.com dengan alias www.strix.operation.wise.yyy.com yang mengarah ke Eden (7).

# Jawaban7

abc

# Nomor 8

Setelah melakukan konfigurasi server, maka dilakukan konfigurasi Webserver. Pertama dengan webserver www.wise.yyy.com. Pertama, Loid membutuhkan webserver dengan DocumentRoot pada /var/www/wise.yyy.com (8).

# Jawaban8

abc

# Nomor 9

Setelah itu, Loid juga membutuhkan agar url www.wise.yyy.com/index.php/home dapat menjadi menjadi www.wise.yyy.com/home (9).

# Jawaban9

abc

# Nomor 10

Setelah itu, pada subdomain www.eden.wise.yyy.com, Loid membutuhkan penyimpanan aset yang memiliki DocumentRoot pada /var/www/eden.wise.yyy.com (10).

# Jawaban10

abc

# Nomor 11

Akan tetapi, pada folder /public, Loid ingin hanya dapat melakukan directory listing saja (11).

# Jawaban11

abc

# Nomor 12

Tidak hanya itu, Loid juga ingin menyiapkan error file 404.html pada folder /error untuk mengganti error kode pada apache (12).

# Jawaban12

abc

# Nomor 13

Loid juga meminta Franky untuk dibuatkan konfigurasi virtual host. Virtual host ini bertujuan untuk dapat mengakses file asset www.eden.wise.yyy.com/public/js menjadi www.eden.wise.yyy.com/js (13).

# Jawaban13

abc

# Nomor 14

Loid meminta agar www.strix.operation.wise.yyy.com hanya bisa diakses dengan port 15000 dan port 15500 (14)

# Jawaban14

abc

# Nomor 15

dengan autentikasi username Twilight dan password opStrix dan file di /var/www/strix.operation.wise.yyy (15)

# Jawaban15

abc

# Nomor 16

dan setiap kali mengakses IP Eden akan dialihkan secara otomatis ke www.wise.yyy.com (16).

# Jawaban16

abc

# Nomor 17

Karena website www.eden.wise.yyy.com semakin banyak pengunjung dan banyak modifikasi sehingga banyak gambar-gambar yang random, maka Loid ingin mengubah request gambar yang memiliki substring “eden” akan diarahkan menuju eden.png. Bantulah Agent Twilight dan Organisasi WISE menjaga perdamaian! (17)

# Jawaban17

abc
