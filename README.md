# setting-mikrotik-
Mikrotik adalah sebuah sistem operasi berbasis perangkat lunak yang berfungsi untuk mengubah komputer menjadi ruter. Sistem mikrotik digunakan di berbagai tempat baik institusi, perusahan, maupun perorangan.

Cara Setting Mikrotik dari Awal sampai Akhir
Mikrotik menggunakan sistem komputer berbasis Linux untuk dijadikan dasar network router. Mikrotik berbeda dengan ruter, software ini memiliki fitur tambahan seperti SNMP, Monitoring, Caching DNS Client, Firewall dan NAT, Web Proxy, dan Tools.

1. Hubungkan Router
Ada dua jenis router yang bisa yang digunakan untuk mengatur Mikrotik, yakni dengan konfigurasi perangkat dan tidak. Jenis ruter yang pertama bisa mengikuti buku petunjuk sesuai ruter yang digunakan.

Untuk ruter yang tidak memiliki konfigurasi, langkah yang harus dilakukan adalah menghubungkan port Enther 1 router ke kabel WAN dan menghubungkan PC ke Ether2.

Setelah itu, buka WinBox dan cari ruter yang sedang digunakan kemudian klik tombol ‘Connect’ untuk menghubungkan ke ruter tersebut.

2. Setting Konfigurasi IP Address
Konfigurasi IP Adreess bisa dilakukan melalui berbagai perangkat. Pada contoh kali ini, pengaturan konfigurasi IP Adreess akan dilakukan Winbox. Berikut langkah-langkahnya.

Buka jendela 'Bridge' kemudian klik tab 'Bridge'. Tekan tombol (+) dd untuk membuka dialog baru. Masukkan nama lokal bridge lalu klik OK.

Klik tab 'Ports' kemudian klik tombol (+). Nantinya ada jendela baru yang terbuka dan pilih Interface Ether2. Setelah itu pilih Local di bagian Bridge dan tekan OK .

Buka IP dan klik Addresses kemudian masukkan tombol (+). Masukkan 192. 168.88.1/24 dan pilih 'Local' di bagikan 'Interface'. Tekan 'OK'.

3. Setting Konfigurasi DHCP Server
Setelah konfigurasi IP Address selesai, proses selanjutnya adalah mengatur konfigurasi DHCP Server DHCP. Caranya buka IP kemudian klik 'DHCP Server'.

Setelah itu tekan tombol DHCP Set up untuk membuka jendela baru. Klik 'Local' pada 'DHCP Server Interface' dan Kik 'Next'.

4. Setting Konfigurasi Jaringan Internet
Pada dasarnya sistem mikrotik bertujuan agar perangkat bisa mengakses jaringan Internet. Cara konfigurasinya bisa dengan membuka kategori segmen PPP dan klik tab Interfaces.

Selanjutnya klik tombol (+) dan pilih 'PPPoE Client'. Klik 'Ether 1' dibagian 'Interfce' dan klik 'OK'.

Setelah semua konfigurasi berhasil, pengguna bisa mengakses Internet dari ruter. Lakukan verifikasi konektivitas IP dengan melakukan Ping ke Alamat IP yang diketahui server Google.

5. Buat Kata Sandi
Apabila berhasil terhubung, buat kata sandi untuk meningkatkan keamanan minimal 12 karakter dengan angka, simbol, kapital, dan huruf kecil.

Pastikan untuk mengingat kata sandi yang sudah dibuat. Sebab, jika lupa tak ada cara untuk memulihkannya. Pengguna perlu menginstal ulang ruter yang sudah dikonfigurasi.
