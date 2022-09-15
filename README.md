==========Konsep Jaringan Komputer==========

Konsep Jaringan Komputer :

Jaring-jaring (Web) -> TSS
Komunikasi antar host
Berbagi resources
Efektifitas Waktu
Efisiensi Biaya

Kesimpulan : Jaringan Komputer adalah
sebuah sistem yang menghubungkan satu host
dengan host lainnya sehingga setiap host
tersebut dapat berkomunikasi.

Jenis-Jenis Jaringan
Komputer :
- Personal Area Network (jaringan komunikasi satu perangkat dengan yg lain dalam jarak dekat)
*- Local Area Network (sejumlah komputer yg saling dihubungkan bersama dalam area yg tidak begitu luas,sperti ruang/gedung. luas 10-1000 meter)
*- Metropolitan Area Network (Mengjangkau antar wilayah dalam satu kota/provinsi, jarak 10k-100k meter)
*- Wide Area Network (mencakup area yg luas dan mampu mengjangkau negara lain,jarak 100km-100.000 km)
- Global Area Network (skala besar WAN, di implementasikan secara global/mendunia, dapat mengjangkau benua lain)
*- Internet
*-Wireless

Topologi Jaringan Komputer

Adalah adalah suatu cara menghubungkan
host yang satu dengan host lainnya sehingga
membentuk sebuah jaringan.

Jenis Topologi :

Bus
Ring
Star

Topologi Bus
Topologi Bus digunakan sebuah kabel tunggal
atau kabel pusat dimana seluruh workstation dan
server dihubungkan

Topologi Ring
Di dalam topologi Ring semua workstation
dan server dihubungkan sehingga terbentuk
suatu pola lingkaran atau cincin.

Topologi Star
Pada topologi Star, masing-masing workstation
dihubungkan secara langsung ke server atau
HUB.

Tipe Jaringan Komputer :

Peer to Peer
Adalah tipe dimana setiap host dalam jaringan
dapat berperan menjadi penyedia dan
pengguna fasilitas (Non-Dedicated)

Client-Server
Adalah tipe dimana terdapat sebuah host
dalam jaringan yang berperan sebagai
penyedia fasilitas (Dedicated) dan host lainnya
berperan sebagai pengguna fasilitas.


Protokol Jaringan Komputer
Adalah aturan-aturan baku yang digunakan
untuk melakukan komunikasi antar host pada
sebuah jaringan.

Jenis-Jenis Protokol :
OSI
TCP/IP

IP Address

Adalah nomor unik yang diberikan kepada
host yang terhubung jaringan agar dapat saling
berkomunikasi.

Konsep IP Address :

Bit (Binari Digital) -> 11110010
Pengkelasan -> 216.108.29.254
DNS (Domain Name System) -> www.facebook.com

============MEDIA TRANSMISI=============
Jaringan membutuhkan penghubung
Fisik atau Wireless
Kecepatan
Biaya
Berdasarkan topologi yg digunakan
Media transmisi adalah jalur – jalur penghubung yang menghubungkan satu host dengan host lainnya sehingga terbentuk sebuah jaringan.

Jenis-Jenis Media Transmisi
Fisik
Wireless

Media Transmisi Fisik
UTP / STP Cable
Coaxial Cable
Fiber Optik

UTP / STP Cable
Unshielded  / ShieldedTwisted Pair
8 warna kabel
10baseT -> 10 – 100 Mbits
Isolator
Tipe Straight / Crossover
Commonly used
Cheap & High Quality
Physical Layer

Coaxial Cable
Kabel Antena
Tipe Thick / Thin
10base2-> 100 - 1000 Mbits
Terminator & ground
Not commonly used
Expensive at terminator
High Quality & Speed

Fiber Optik
Kabel Serat Fiber
10baseX-> Up to 3 Gbits
Commonly used by Company
Expensive
High Speed

Media Transmisi Wireless
Electromagnetic Wave
Radio Signal
GSM
CDMA
Frequency Base

UTP / STP Cable Type :
Tipe Straight
Menghubungkan device / komponen yang berbeda (ex : host dan switch)
Susunan =
PO – O	PO – O	
PH – B		PH – B	
PB – H		PB – H	
PC – C		PC – C

Tipe Crossover
Menghubungkan device / komponen yang sama (ex : host dan host)
Susunan =
PO – O	PH – H	
PH – B		PO – B	
PB – H		PB – O	
PC – C		PC – C

==============IP ADDRESS===============
Konsep IP Address

Alamat adalah alat agar “paket” mencapai
tujuan

Setiap host yang terhubung jaringan butuh IP
Address

IP Address disusun berdasarkan nomor unik

IP Address adalah nomor-nomor unik 
yang diberikan pada host yang terhubung 
jaringan agar dapat saling berkomunikasi.

Jenis-Jenis IP Address :
IP Address Versi 4
IP Address Versi 6

IP Address Versi 4 :
- Berbasis 32 bit yang di bagi dalam 4 ruas yg
dipisahkan dengan tanda titik (.) sehingga
setiap ruas mendapatkan masing-masing 8 bit
(ex : 202.10.29.254)
- Tersusun atas Net id dan Host id
- Menggunakan sistem pengkelasan
- Memiliki subnetmask sebagai pengenal
  jaringan

Bit (Binary Digital) :
- Merupakan bilangan yang hanya terdiri dari
dua angka,yaitu 0 dan 1
- Mesin hanya mengerti bit sebagai perintah
- Butuh penerjemahan ke dalam bahasa manusia
sehingga dapat dimengerti.

Net id dan Host id :
- Net id adalah bagian yang menunjukan alamat
jaringan dari sebuah host

- Host id adalah bagian yang menunjukan
identitas dari host

Kenapa menggunakan kelas? :
- Membaca bit biner terlalu sulit

- Alamat IP suatu host dibaca 8 bit demi 8 bit
dan setiap 8 bit tersebut dikonversi ke desimal

Pengkelasan :
Class A : 1 - 126
Class B : 128-191
Class C : 192-223

Subnetmask :
Class A -> 255.0.0.0
Class B -> 255.255.0.0
Class C -> 255.255.255.0
