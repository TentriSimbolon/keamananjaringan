## Latar Belakang Masalah :
1. Pengertian Snort
2. Mode Pengoperasian Snort
3. Cara Instal Snort

## Isi
## Snort
Snort adalah Sebuat sistem software yang berupa opensource GNU, dimana pengguna dapat menggunakannya secara bebas dan tidak berbayar, selain itu Snort juga dapat kita ubah bentuknya sesuai dengan modifikasi yang kita inginkan. Snort digunakan untuk mengamati apa aja aktivitas atau kegiatan yang berjalan pada sebuah jaringan komputer. Snort mempunyai peraturan yang sangat mudah dipahami oleh pengguna, oleh karena itu Snort sangat efisien digunakan untuk pendeteksian dan pencatatan terhadap serangan yang datang pada komputer.

## Mode Pengoperasian Snort
* Sniffer Mode
Mode berfungsi untuk melihat semua paket yang mask pada jaringan komputer dimana Snort diletakkan. jadi semua paket akan selalu ditampilakn pada layar monitor secara detail begitu juga dengan waktu kapan paket tersebut masuk pada jaringan komputer.

* Packet Logger Mode
Mode ini digunakan untuk mencatat sekaligus menyimpan data-data paket yang lewat pada lalu lintas jaringan. Data-data tersebut digunakan untuk membuat analisa terhadap data-data yang dicatat atau disimpan.

## Cara Instal Snort
Install beberapa paket yang dibutuhkan snort.
~~~
# yum install libdnet libdnet-devel pcre pcre-devel gcc make flex byacc bison kernel-devel libxml2-devel wget -y
~~~

Membuat Folder untuk tempat instalasi.
~~~
# mkdir /usr/local/src/snort
# cd /usr/local/src/snort
~~~

Instalasi Libpcap.
~~~
# wget http://www.tcpdump.org/release/libpcap-1.3.0.tar.gz -O libpcap.tar.gz
# tar zxvf libpcap.tar.gz
# cd libpcap-*
# ./configure && make && make install
# echo “/usr/local/lib” >> /etc/ld.so.conf
# ldconfig -v
~~~

Instalasi DAQ.
~~~
# wget https://www.snort.org/downloads/snort/daq-2.0.6.tar.gz -O daq.tar.gz
# tar zxvf daq.tar.gz
# cd daq-*
# ./configure && make && make install
# ldconfig -v
~~~

Membuat user dan group untuk snort.
~~~
# groupadd snort
# useradd -g snort snort
~~~

Masuk ke folder dan instalasi snort.
~~~
# cd /usr/local/src/snort
# wget https://www.snort.org/downloads/snort/snort-2.9.9.0.tar.gz -O snort.tar.gz
# tar zxvf snort.tar.gz
# cd snort-2*
# ./configure –prefix /usr/local/snort –enable-sourcefire && make && make install
~~~

## Kesimpulan
Jadi Snort merupakan sebuah open source yang digunakan untuk melakukan pencegehan dan sekaligus pendeteksian atas serangan-serangan yang dating pada jaringan computer kita.

## Saran
Lebih memaksimalkan praktek dalam memahami cara penggunaan Snort ini untuk Kemanan jaringan kita sendiri.
<br>
* Nama : Tentri May Simbolon
* NPM : 1144027
* Kelas : D4 Teknik Informatika 3C
* Kampus : Politeknik Pos Indonesia