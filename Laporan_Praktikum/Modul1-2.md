# Laporan Praktikum Jaringan Komputer

## Tujuan Praktikum
Download dan Installasi Wireshark dan Mempelajari Tools Wireshark

## Modul 1 - Langkah Download dan Install Wireshark
1. Download Wireshark terlebih dahulu dengan menggunakan link berikut ini : [Download Wireshark](http://www.wireshark.org/)<br>
   ![Tampilann pada web download Wireshark](../assets/image/Modul1.1.png)<br>
   Pilih Wireshark yang sesuai dengan laptop. Lalu klik, otomatis akan terdownload seperti gambar diatas

2. Setelah downnload selesai lakukan installasi Wireshark di laptop, dengan cara klik dua kali file yang telah kalian download<br>
   ![Tampilan setelah di klik dua kali](../assets/image/Modul1.2.png)<br>
   Pilih open
   ![Tampian setelah pilih open](../assets/image/Modul1.3.png)<br>
   Geser Wireshark ke application dan juga lakukan intsall ChmodBPF.pkg

3. Tampilan setelah klik install ChmodBPF.pkg<br>
   ![Tampilannya akan seperti ini](../assets/image/Modul1.4.png)<br>
   Pilih continue
   ![Tampilann setelah contine](../assets/image/Modul1.5.png)<nr>
   Pilih continue lagi
   ![Tampilann setelah continue kedua](../assets/image/Modul1.6.png)<br>
   Pilih install
   ![Tampilann akhir install ChmodBPF.pkg](../assets/image/Modul1.7.png)<br>
   Tampilan akhir akan seperti ini setelah install ChmodBPF.pkg, lalu klik close

4. Masuk ke aplikasi Wireshark, tampilannya akan seperti ini
   ![Tampilann pada web download Wireshark](../assets/image/Modul1.8.png)

## Modul 2 - langkah Menjalankan Wireshark
1. Tampilan awal masuk akan seperti gambar berikut ini:
   ![Tampilann awal masuk Wireshark](../assets/image/Modul2.1.png)

2. Karena laptop saya terhubung ke internet menggunakan Wifi, maka interface yang saya pilih di Wireshark adalah Wifi. Interface ini saya pilih agar semua paket data yang masuk dan keluar melalui jaringan Wifi dapat ditangkap dan dianalisis oleh Wireshark.

3. Setelah memilih interface Wifi dan memulai proses capture, Wireshark mulai menampilkan paket data yang masuk dan keluar dari laptop saya secara real-time.
   ![Tampilann setelah memilih interface Wifi](../assets/image/Modul2.2.png)

4. Untuk langkah percobaan masuk ke dalam browser lalu paste URL berikut ini :
   [Contoh URL percobaan](http://gaia.cs.umass.edu/wireshark-labs/INTRO-wireshark-file1.html)
   ![Setelah membuka URL tersebut halaman akan menampilkan seperti ini “Congratulations! You've downloaded the first Wireshark lab file!”](../assets/image/Modul2.3.png)

5. Masuk kembali ke Wireshark, lakukan pencarian dengan filter http. Kemudian akan terlihat beberapa protokol http yang dapat kita lihat, pilih yang ada kata "200 OK (text/html)
   ![Berikut gambar setelah filter http](../assets/image/Modul2.4.png)
   Pada bagian Line-based text data: text/html, Wireshark menampilkan isi data dari http. Data tersebut merupakan isi halaman web,yang berisi pesan “Congratulations! You've downloaded the first Wireshark lab file!” yang menunjukkan bahwa halaman web berhasil dimuat.

## Terima Kasih