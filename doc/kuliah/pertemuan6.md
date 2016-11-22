# Denial of Service (DoS)
“Denial of Service (DoS) attack” merupakan sebuah usaha (dalam bentuk serangan) untuk melumpuhkan sistem yang dijadikan target sehingga sistem tersebut tidak dapat menyediakan servis-servisnya (denial of service) atau tingkat servis menurun dengan drastis. Cara untuk melumpuhkan dapat bermacam-macam dan akibatnya pun dapat beragam. Sistem yang diserang dapat menjadi “bengong” (hang, crash), tidak berfungsi atau turun kinerjanya (karena beban CPU tinggi).
     Serangan ini berbeda dengan kejahatan pencurian data atau kejahatan memonitor inforamasi yang lalu lalang. Dalam serangan DoS tidak ada yang dicuri, tapi hal ini dapat mengakibatkan kerugian financial. Sebagai contoh apabila sistem yang diserang merupakan server yang menangani transaksi “commerce”, maka apabila server tersebut tidak berfungsi, transaksi tidak dapat dilangsungkan. Bayangkan apabila sebuah bank diserang oleh bank saingan dengan melumpuhkan outlet ATM (Anjungan Tunai Mandiri, Automatic Teller Machine) yang dimiliki oleh bank tersebut. Atau sebuah credit card merchant server yang diserang, sehingga tidak dapat menerima pembayaran melalui credit card.
Selain itu, serangan DoS sering digunakan sebagai bagian dari serangan lainnya. Misalnya, dalam serangan IPspoofing (seolah serangan datang dari tempat lain dengan nomor IP milik orang lain), seringkali DoS digunakan untuk membungkam server yang akan dispoof.

## KLASIFIKASI SERANGAN DOS

Denial Of Service Attack adalah serangan yang paling sering digunakan daripada serangan yang lain, hal ini dikarenakan mudahnya untuk melakukannya, exploits-nya pun banyak ditemukan di internet. Siapapun bisa men-down kan sebuah website dengan hanya menggunakan simple command prompt. Tujuan utama serangan ini adalah membuat suatu sistem crash & karena overload sehingga tidak bisa diakses atau mematikan service.


Beberapa klasifikasi serangan DoS:

1.   Land Attack

Land attack merupakan serangan kepada sistem dengan menggunakan program yang bernama “land”. Program land menyerang server yang dituju dengan mengirimkan packet palsu yang seolah-olah berasal dari server yang dituju. Dengan kata lain, source dan destination dari packet dibuat seakan-akan berasal dari server yang dituju. Akibatnya server yang diserang menjadi bingung.

2.   Latierra

Program latierra merupakan “perbaikan” dari program land, dimana port yang digunakan berubah-ubah sehingga menyulitkan bagi pengamanan.

3.   Ping Broadcast (Smurf)

Salah satu mekanisme serangan yang baru-baru ini mulai marak digunakan adalah menggunakan ping ke alamat broadcast, ini yang sering disebut dengan smurf. Seluruh komputer (device) yang berada di alamat broadcast tersebut akan menjawab. Jika sebuah sistem memiliki banyak komputer (device) dan ping broadcast ini dilakukan terus menerus, jaringan dapat dipenuhi oleh respon-respon dari device-device tersebut. Akibatnya jaringan menjadi lambat.

4.   Ping of Death (PoD)

Ping-o-death sebetulnya adalah eksploitasi program ping dengan memberikan packet yang ukurannya besar ke sistem yang dituju. Beberapa sistem UNIX ternyata menjadi hang ketika diserang dengan cara ini. Program ping umum terdapat di berbagai operating system, meskipun umumnya program ping tersebut mengirimkan packet dengan ukuran kecil (tertentu) dan tidak memiliki fasilitas untuk mengubah besarnya packet. Salah satu implementasi program ping yang dapat digunakan untuk mengubah ukuran packet adalah program ping yang ada di sistem Windows 95.


# Solusi Masalah
Denial of service adalah Suatu metode yang sudah putus asa mencoba berbagai data. Cara kerja dari denial service adalah Membuat register biasa terhadap server melebihi kapasitas pelayanan service sehingga server tidak bisa melayani permintaan lainnya. Dalam deniel of service ada yang disebut dengan Distributor DOS. Distributor DOS adalah Kumpulam orang orang yang melakukan DOS.
Kapasitas layanan Web dapat dicontohkan dengan X. .Jika Petrik membuuat request sebanyak X maka spongebob tiak dilayani, Tapi server masih hidup hanya saja sibuk melayani Petrik. 
Apa yang perlu dipersiapkan penyerang :
1.      Hanya req sebanyak x
2.      Jika belum bisa mencapai x maka panggil teman teman bergabunglah denagn teman teman dan membentuk distributor DOS.
## Kesimpulan                                                        
                Kesimpulan Denial of service adalah Suatu metode yang sudah putus asa mencoba berbagai data. Cara kerja dari denial service adalah Membuat register biasa terhadap server melebihi kapasitas pelayanan service sehingga server tidak bisa melayani permintaan lainnya. Karena dengan denial of service server bisa diserang dengan beberapa kali dengan satu pc.
## Saran
            Lebih membanyak ilmu dan mencari referensi lain untuk bahan praktek denial of service. karena denail of service sangat penting dalam pengamanan ataupun penyerang suatu server atau website.
            
* Nama : Tentri May Simbolon
* Npm : 1144027
* Kelas : D4 Teknik Informatika 3C
* Kampus : Politeknik Pos Indonesia

## Referensi : Matakuliah Keamanan Jaringan
## Link Plagiarisme
Smallseotools : https://drive.google.com/open?id=0B7tQon2iaQFdRGFZY3NoM3habGM 
Duplichecker: https://drive.google.com/open?id=0B7tQon2iaQFdVjlLRk4xUE5UdUE 
