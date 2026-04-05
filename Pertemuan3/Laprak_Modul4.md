Nama    : Brian Alfredo Adhita Putra<br>
NIM     : 103072400165

# Modul 4 - DNS

## Tujuan Praktikum
Mahasiswa dapat menginvestigasi cara kerja DNS menggunakan Wireshark

## Nslookup
Nslookup merupakan salah satu tools yang digunakan untuk mengetahui informasi terkait DNS. Dengan menggunakan perintah ini, kita bisa melihat alamat IP dari suatu domain, mengetahui server DNS yang digunakan, serta informasi lainnya seperti mail server.

Contoh Penggunaan Nslookup:
1. Buka terminal.
2. Jalankan perintah "nslookup www.mit.edu"
![HTTP Get](../assets/image/Modul4.1.png)
Perintah ini digunakan untuk mengetahui alamat IP dari domain www.mit.edu dan DNS server yang digunakan.
3. Jalankan perintah "nslookup -type=NS mit.edu"
![HTTP Get](../assets/image/Modul4.2.png)
Perintah ini digunakan untuk melihat daftar DNS server yang bertanggung jawab terhadap domain mit.edu.
4. Jalankan perintah "nslookup www.aiit.or.kr bitsy.mit.edu"

Perintah ini digunakan untuk melakukan query ke server DNS tertentu, bukan menggunakan DNS default.

Pengujian Mandiri:
1. Jalankan nslookup untuk mendapatkan alamat IP dari server web di Asia. Berapa alamat IP server tersebut?
Jalankan perintah "nslookup www.nus.edu.sg"
![HTTP Get](../assets/image/Modul4.4.png)
2. Jalankan nslookup agar dapat mengetahui server DNS otoritatif untuk universitas di Eropa.
Jalankan perintah "nslookup -type=NS ox.ac.uk"
![HTTP Get](../assets/image/Modul4.5.png)
3. Jalankan nslookup untuk mencari tahu informasi mengenai server email dari Yahoo! Mail melalui salah satu server yang didapatkan di pertanyaan nomor 2. Apa alamat IP-nya?
Jalankan perintah "nslookup -type=MX yahoo.com dns0.ox.ac.uk"
![HTTP Get](../assets/image/Modul4.6.png)
server DNS yang digunakan hanya melayani domain tertentu, sehingga permintaan terhadap domain lain bisa ditolak.

## Ifconfig
ifconfig adalah salah satu fasilitas kecil yang paling berguna di dalam host, terutama untuk men-debug masalah jaringan.

Contoh penggunaan Ifconfig:
1. Untuk melihat alamat IP, jalankan perintah berikut "Ifconfig"
![HTTP Get](../assets/image/Modul4.7.png)
2. Untuk melihat record yang telah disimpan DNS Servern jalankan perintah berikut "scutil --dns"
![HTTP Get](../assets/image/Modul4.8.png)
3. Untuk menghapus cache DNS, jalankan perintah berikut "
![HTTP Get](../assets/image/Modul4.9.png)
Setelah menjalankan perintah untuk menghapus cache DNS, tidak muncul output pada terminal, yang menandakan bahwa perintah berhasil dijalankan tanpa error.

## Tracing DNS dengan Wireshark