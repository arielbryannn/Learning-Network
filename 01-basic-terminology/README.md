# 01. Basic Terminology

## 📌 Definisi, Fungsi, serta contoh Terminology

* **Client**
  * **Definisi**: Perangkat atau aplikasi yang meminta layanan/data.
  * **Fungsi**: Memulai komunikasi untuk mengakses informasi atau layanan dari server.
  * **Contoh**: Browser di laptop/HP pengguna saat membuka halaman web (seperti Chrome atau Firefox).

* **Server**
  * **Definisi**: Sistem atau perangkat yang menyediakan layanan/data.
  * **Fungsi**: Menunggu, memproses, dan merespons permintaan data dari berbagai client.
  * **Contoh**: Komputer server pusat milik Google atau YouTube yang menyimpan dan mengirimkan video.

* **Host**
  * **Definisi**: Perangkat aktif ber-IP yang terhubung ke jaringan.
  * **Fungsi**: Bertindak sebagai titik pengirim atau penerima data di dalam jaringan.
  * **Contoh**: PC, laptop, smartphone, atau printer yang tersambung ke jaringan lokal/Wi-Fi.

* **Package / Packet**
  * **Definisi**: Unit data dasar yang dipecah untuk dikirimkan melalui jaringan.
  * **Fungsi**: Membawa potongan data secara efisien agar mudah dikirim dan disusun ulang di tujuan.
  * **Contoh**: File dokumen atau foto yang dipecah-pecah kecil saat dikirim lewat internet.

* **Frame**
  * **Definisi**: Unit data pada Layer ke-2 (Data Link OSI).
  * **Fungsi**: Membungkus paket data agar siap dikirimkan melalui media fisik antar perangkat dalam satu segmen jaringan lokal.
  * **Contoh**: Paket data yang sudah ditambahkan informasi MAC Address asal dan tujuan sebelum masuk ke kabel LAN.

* **Bandwidth**
  * **Definisi**: Kapasitas maksimal jalur transfer data.
  * **Fungsi**: Menentukan seberapa banyak data yang dapat dilewatkan dalam satu satuan waktu.
  * **Contoh**: Kapasitas langganan internet rumah sebesar 50 Mbps.

* **Latency**
  * **Definisi**: Waktu tunda perjalanan data dari sumber ke tujuan.
  * **Fungsi**: Mengukur responsibilitas jaringan (semakin kecil latency, semakin cepat koneksi terasa).
  * **Contoh**: Angka ping sebesar `10ms` saat mengecek koneksi ke server game atau Google.

* **Throughput**
  * **Definisi**: Kecepatan transfer data aktual saat digunakan.
  * **Fungsi**: Mengetahui performa nyata pengiriman data di kondisi jaringan yang sedang berjalan.
  * **Contoh**: Kecepatan unduh (*download*) file yang beneran didapat sebesar 4 MB/s.

* **Protocol**
  * **Definisi**: Aturan standar komunikasi antar perangkat.
  * **Fungsi**: Memastikan perangkat dari berbagai *vendor* bisa saling memahami dan bertukar data dengan benar.
  * **Contoh**: HTTP/HTTPS untuk akses web, atau TCP/IP untuk aturan pengiriman data.

* **Port**
  * **Definisi**: Nomor identifikasi layanan atau aplikasi di jaringan.
  * **Fungsi**: Mengarahkan lalu lintas data masuk ke aplikasi yang tepat di dalam komputer.
  * **Contoh**: Port `80`/`443` untuk web, atau port `8291` khusus buat aplikasi WinBox MikroTik.

* **Socket**
  * **Definisi**: Gabungan Alamat IP dan Port (`IP:Port`).
  * **Fungsi**: Menjadi titik akhir (*endpoint*) yang unik agar komunikasi antar aplikasi di jaringan tidak tertukar.
  * **Contoh**: `192.168.1.10:443` (gabungan IP komputer dan port layanannya).

* **IP Address**
  * **Definisi**: deretan angka unik yang diberikan kepada setiap perangkat yang terhubung ke jaringan komputer atau internet agar bisa  saling berkomunikasi.
  * **Fungsi**: Menjadi alamat pengenal agar data bisa dirutekan (*routing*) antar jaringan yang berbeda.
  * **Contoh**: `192.168.1.1` atau `8.8.8.8`.

* **MAC Address**
  * **Definisi**: Alamat fisik unik bawaan pabrik pada kartu jaringan (NIC).
  * **Fungsi**: Mengidentifikasi perangkat secara permanen untuk pengiriman data di jaringan lokal (Layer 2).
  * **Contoh**: `AC:DE:48:23:56:78` yang tertanam di hardware kartu jaringan.

* **ARP (Address Resolution Protocol)**
  * **Definisi**: Protokol penerjemah alamat.
  * **Fungsi**: Mencocokkan IP Address (Layer 3) dengan MAC Address (Layer 2) agar komunikasi fisik dapat terjadi.
  * **Contoh**: Perangkat menyebar pesan di jaringan lokal untuk bertanya, "Siapa pemilik IP 192.168.1.5? Tolong kasih tau MAC Address-nya."

* **Transmission Media Types**
  * **Definisi**: Media fisik atau nirkabel yang digunakan transmisi data.
  * **Fungsi**: Sebagai jalur sinyal data dari satu titik ke titik lain.
  * **Contoh**: Kabel UTP, kabel Fiber Optik, atau gelombang elektromagnetik Wi-Fi.
