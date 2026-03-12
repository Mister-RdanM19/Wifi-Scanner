# Mr.Rm19 Wifi Sc4nner

Mesin Pemantau Jaringan Nirkabel tingkat lanjut untuk lingkungan Windows. Utilitas ini menyediakan fitur audit nirkabel waktu nyata (real-time), analisis keamanan, dan diagnostik jaringan dalam antarmuka yang efisien dan berorientasi pada performa.
<img src="https://raw.githubusercontent.com/Mister-RdanM19/Wifi-Scanner/refs/heads/main/scanner.png">
## Fitur Utama

* **Pemantauan Nirkabel**: Pemindaian jaringan SSID dan BSSID yang tersedia secara waktu nyata.
* **Audit Keamanan**: Deteksi otomatis protokol autentikasi, termasuk pengenalan WPA3 dan peringatan "Keamanan Lemah" untuk konfigurasi WEP/WPA yang rentan.
* **Analisis Sinyal**: Pemantauan kekuatan sinyal yang intuitif dengan tingkatan warna berdasarkan tingkat keparahan (Kuat, Sedang, Lemah).
* **Wawasan Infrastruktur**: Deteksi IP Gateway otomatis dan identifikasi Vendor MAC berdasarkan awalan BSSID.
* **Penyaringan Tingkat Lanjut**: Kemampuan untuk mengisolasi jenis jaringan tertentu, seperti jaringan Terbuka (Open) atau instansi WPA3 yang Aman.
* **Antarmuka Teroptimasi**: UI mode gelap dengan kontras tinggi yang dibangun dengan Tkinter Python, dioptimalkan untuk keterbacaan cepat.

## Gambaran Teknis

Aplikasi ini menggunakan Native Wifi API Windows (`netsh`) untuk berinteraksi langsung dengan perangkat keras nirkabel. Dengan memanfaatkan manajemen subprocess, aplikasi ini menjembatani data sistem tingkat rendah ke dalam presentasi grafis yang terstruktur.

### Prasyarat

* **Sistem Operasi**: Windows 10/11 (Dioptimalkan untuk lingkungan Windows).
* **Perangkat Keras**: Kartu Antarmuka Jaringan Nirkabel (NIC) yang aktif.

## Instalasi

1. download file `wifi-sc4nner.exe`
2. run as administrator 
3. happy scanner
