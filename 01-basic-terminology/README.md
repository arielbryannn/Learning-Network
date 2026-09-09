# 01. Basic Terminology

Catatan ringkas versi saya dalam dasar *Network Engineering* bersumber roadmap.sh.

## 📌 Core Terminology

* **Client**: Perangkat/aplikasi yang meminta layanan/data ke server.
* **Server**: Sistem atau perangkat yang menyediakan layanan/data untuk client tersebut.
* **Host**: Perangkat aktif ber-IP yang terhubung ke dalam jaringan.
* **Package / Packet**: Unit data dasar yang dikirimkan melalui jaringan.
* **Frame**: Unit data pada Layer 2 (Data Link) yang membungkus paket untuk transmisi fisik.
* **Bandwidth**: Kapasitas maksimal jalur transfer data dalam waktu tertentu.
* **Latency**: Waktu tunda perjalanan data dari sumber ke tujuan (diukur dalam milidetik/ms).
* **Throughput**: Kecepatan transfer data aktual yang berhasil dicapai saat pengujian.
* **Protocol**: Aturan standar komunikasi antar perangkat di jaringan.
* **Port**: Nomor identifikasi layanan/aplikasi di jaringan (contoh: Port 80 untuk web).
* **Socket**: Gabungan Alamat IP dan Port (`IP:Port`) sebagai jalur komunikasi aplikasi.
* **IP Address**: Alamat logika unik untuk identifikasi perangkat di Layer 3.
* **MAC Address**: Alamat fisik unik bawaan pabrik pada kartu jaringan (NIC).
* **ARP (Address Resolution Protocol)**: Protokol untuk menerjemahkan IP Address ke MAC Address.
* **Transmission Media Types**: Media fisik (kabel UTP, fiber optik) atau nirkabel untuk mengirim data.
