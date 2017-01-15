# RADIUS
## Latar Belakang
*	Pengertian Radius dan Fungsi Radius
*	Karakteristik Radius
*	Struktur paket data Radius
*	Proses-proses yang ada pada Radius

## Isi
## Pengertian Radius
Radius ( Remote authentic loction Dial-in ) adalah sebuah protokol keamanan computer dimana digunakan untuk melakukan autentikasi, otorisasi dan juga berfungsi jika ada pendafataran akun pengguna secara terpusat atau berada dalam satu titik pusat untuk mengakses jaringan. Fungsi lain dari radius yaitu menyediakan mekanisme keamanan, missal jika user ingin masuk dalam sebuah akses internet kita diminta untukmemasukkan username dan password, nah itu bergunan untuk mangakses keamanan jaringan. 
Sebagai Contoh : Jika kita ingin login hotspot dari poltekpos maka akan diminta user dan password, Nah itu sebagai bentuk untuk bias mengakses keamanan jaringan poltekpos.

## Karakteristik Radius
Karakteristik dari Radius adalah sebagi berikut:
*	Berbasis UDP Protocol
*	Dapat diletakan dimana saja 
*	Menggunakan Remote Acces Server (RAS) untuk pengontro akses.

## Struktur Paket Data Radius
*	Code
Digunakan untuk membedakan setiap tipe pesan radius yang dikirimkan pada paket. Berikut code-code tersebut :
* 1. Access-Request
* 2. Access-Accept
* 3. Access-Reject
* 4. Accounting-Request
* 5.Accounting-Response
* 11.Access-Challenge
* 12. Status-Server
* 13. Status-Client
* 255. Reserved

* Identifier
Bertujuan untuk mencocokan permintaan paket.
Length
Panjangnya dua octet, berfungsi untuk memberikan info mengenai panjang paket
Authenticator
Panjangnya 19 oktet, yang lbh digunakan pada algoritma password
Attributes
Attributes ini berisikan infrmasi yang ada pada oaket yang dibawa oleh radius, missal id, passoword, alamat IP dll.

## Proses-proses yang ada pada Radius
*	Authentication
Proses verifikasi user untuk memastikan adanya user yang memiliki hak akses. Biasanya meminta user dipasangkan dan bias lebih kompleks login.
Contoh Analoginya : Kamppus kita Politeknik Pos Indonesia dijaga oleh satpam, apabila ada orang ataupun mahasiswa yang ingin masuk kedalam kampus, pertama kali yg dilakukan satpam ialah mengidentifikasi siapa-siapaja aja yg orang yang masuk kelar dari kampus politeknik pos Indonesia, jika ada orang asing yang ingin masuk, bisa aja satpama tidak memperbolehkannya masuk, namun jika sudah dikenal maka akan diperbolehkan masul, demikian juga dengan perangkat remote acces terhadap pengguna yang ingin masuk kedalam jaringan.

*	Authorization
Pembelian hak akses terhadap user yang sudah diverifikasi untuk mengakses jaringan, jadi setelah perangkat diperbolehkan masuk maka perangakat diberikan batasan hak-hak yang diterima oleh pengguna tersebut.

*	Accounting
Penghitungan penggunaan jumlah Bandwitch yang dipakai user. Jadi setiap fasilitas AAA diaktifkan acconting bertugas untuk menghitung setiap transaksi yersebut pada keamanan server.

## Kesimpulan
Jadi kesimpulan dari tulisan ini adalah Radius digunaka sebagai mekaniskem keamanan jaringan untuk mengetahui setiap user pengguna yang ingin masuk dalam sebuat jaringan/jaringan hotspot. 

## Saran 
Radius ini penting untuk kita yang setiap saat bergantung pada jaringan internet, jadi kita harus lebuh memahami bagaimana cara untuk membuat keamanan pada jaringan kita sendiri.

* Nama : Tentri May Simbolon
* NPM : 1144027
* Kelas : D4 Teknik Informatika 3C
* Kampus : Politeknik Pos Indonesia
