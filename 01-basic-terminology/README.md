# 01. Basic Terminology

## 📌 Core Terminology & Functions

* **Client**
  * **Definisi**: Perangkat atau aplikasi yang meminta layanan/data.
  * **Fungsi**: Memulai komunikasi untuk mengakses informasi atau layanan dari server (contoh: membuka browser).

* **Server**
  * **Definisi**: Sistem atau perangkat yang menyediakan layanan/data.
  * **Fungsi**: Menunggu, memproses, dan merespons permintaan data dari berbagai client.

* **Host**
  * **Definisi**: Perangkat aktif ber-IP yang terhubung ke jaringan.
  * **Fungsi**: Bertindak sebagai titik pengirim atau penerima data di dalam jaringan.

* **Package / Packet**
  * **Definisi**: Unit data dasar yang dipecah untuk dikirimkan melalui jaringan.
  * **Fungsi**: Membawa potongan data secara efisien agar mudah dikirim dan disusun ulang di tujuan.

* **Frame**
  * **Definisi**: Unit data pada Layer 2 (Data Link OSI).
  * **Fungsi**: Membungkus paket data agar siap dikirimkan melalui media fisik antar perangkat dalam satu segmen jaringan lokal.

* **Bandwidth**
  * **Definisi**: Kapasitas maksimal jalur transfer data.
  * **Fungsi**: Menentukan seberapa banyak data yang dapat dilewatkan dalam satu satuan waktu (misal: Mbps).

* **Latency**
  * **Definisi**: Waktu tunda perjalanan data dari sumber ke tujuan.
  * **Fungsi**: Mengukur responsibilitas jaringan (semakin kecil latency, semakin cepat koneksi terasa).

* **Throughput**
  * **Definisi**: Kecepatan transfer data aktual saat digunakan.
  * **Fungsi**: Mengetahui performa nyata pengiriman data di kondisi jaringan yang sedang berjalan.

* **Protocol**
  * **Definisi**: Aturan standar komunikasi antar perangkat.
  * **Fungsi**: Memastikan perangkat dari berbagai *vendor* bisa saling memahami dan bertukar data dengan benar.

* **Port**
  * **Definisi**: Nomor identifikasi layanan atau aplikasi di jaringan.
  * **Fungsi**: Mengarahkan lalu lintas data masuk ke aplikasi yang tepat di dalam komputer (contoh: Port 80 untuk web).

* **Socket**
  * **Definisi**: Gabungan Alamat IP dan Port (`IP:Port`).
  * **Fungsi**: Menjadi titik akhir (*endpoint*) yang unik agar komunikasi antar aplikasi di jaringan tidak tertukar.

* **IP Address**
  * **Definisi**: Alamat logika unik untuk identifikasi perangkat di Layer 3.
  * **Fungsi**: Menjadi alamat pengenal agar data bisa dirutekan (*routing*) antar jaringan yang berbeda.

* **MAC Address**
  * **Definisi**: Alamat fisik unik bawaan pabrik pada kartu jaringan (NIC).
  * **Fungsi**: Mengidentifikasi perangkat secara permanen untuk pengiriman data di jaringan lokal (Layer 2).

* **ARP (Address Resolution Protocol)**
  * **Definisi**: Protokol penerjemah alamat.
  * **Fungsi**: Mencocokkan IP Address (Layer 3) dengan MAC Address (Layer 2) agar komunikasi fisik dapat terjadi.

* **Transmission Media Types**
  * **Definisi**: Media fisik atau nirkabel yang digunakan transmisi data.
  * **Fungsi**: Sebagai jalur rambat sinyal data (baik menggunakan kabel UTP, fiber optik, maupun gelombang udara/Wi-Fi).
