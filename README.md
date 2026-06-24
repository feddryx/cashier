# Cashier

Aplikasi kasir (Point of Sale / POS) berbasis HTML, CSS, dan JavaScript yang berjalan sepenuhnya di browser tanpa server. Data tersimpan secara lokal menggunakan Local Storage sehingga dapat digunakan secara offline. Dibuat dengan LLM.

### >> [Jalankan Secara Online](https://feddryx.github.io/cashier/cashier.html)

## Fitur Utama

### Setup Toko

* Onboarding saat pertama kali digunakan
* Pengaturan nama toko
* Upload logo toko
* Pengaturan modal awal kas
* Penyimpanan otomatis konfigurasi toko

---

## Sistem Kasir (POS)

### Manajemen Pesanan

* Pencarian menu secara real-time
* Filter menu berdasarkan kategori
* Keranjang belanja (cart)
* Tambah dan kurangi jumlah item
* Input kuantitas manual
* Perhitungan subtotal otomatis

### Diskon Produk

* Diskon nominal (Rp)
* Diskon persentase (%)
* Harga asli dicoret (strikethrough)
* Harga setelah diskon dihitung otomatis

### Checkout & Pembayaran

* Proses pembayaran langsung
* Perhitungan total otomatis
* Dukungan biaya tambahan
* Perhitungan kembalian
* Pencatatan transaksi otomatis

### Responsif Mobile

* Floating cart
* Bottom navigation
* Cart sheet khusus mobile
* Optimasi layar sentuh

---

## Manajemen Menu

### Pengelolaan Produk

* Tambah menu baru
* Edit menu
* Hapus menu
* Aktif / nonaktif menu
* Harga jual produk

### Kategori

* Tambah kategori
* Kelola kategori
* Filter berdasarkan kategori
* Statistik jumlah item per kategori

### Visual Menu

* Icon menu yang dapat dipilih
* Badge kategori
* Badge diskon
* Tampilan grid responsif

---

## Riwayat Transaksi

### Penyimpanan Transaksi

* Semua transaksi tersimpan otomatis
* ID transaksi unik
* Waktu transaksi lengkap

### Pencarian & Filter

* Cari transaksi berdasarkan nama atau ID
* Filter berdasarkan tanggal
* Statistik transaksi

### Statistik Riwayat

* Total transaksi
* Total penjualan
* Nilai rata-rata transaksi
* Total item terjual

---

## Manajemen Kas

### Monitoring Saldo

* Saldo kas real-time
* Modal awal
* Total kas masuk
* Total kas keluar

### Arus Kas

* Kas masuk manual
* Kas keluar manual
* Catatan arus kas
* Riwayat mutasi kas

### Fitur Tambahan

* Ubah modal awal
* Filter arus kas berdasarkan tanggal
* Perhitungan saldo otomatis

---

## Laporan Penjualan

### Dashboard Statistik

* Penjualan hari ini
* Penjualan 7 hari terakhir
* Total penjualan keseluruhan
* Rata-rata nilai transaksi

### Analitik

* Grafik tren penjualan 14 hari
* Menu terlaris
* Penjualan per kategori
* Jumlah transaksi

### Visualisasi Data

* Chart interaktif menggunakan Chart.js
* Ringkasan performa bisnis
* Analisis kategori produk

---

## Antarmuka Pengguna

### Tema

* Light Mode
* Dark Mode
* Pergantian tema instan
* Penyimpanan preferensi tema

### UX Features

* Toast notification
* Modal dialog
* Loading screen
* Animasi halus
* Responsive design

### Accessibility

* Optimasi perangkat mobile
* Touch friendly
* Reduced motion support
* Tampilan adaptif berbagai ukuran layar

---

## Penyimpanan Data

### Local Storage

Semua data disimpan secara lokal di browser:

* Informasi toko
* Menu
* Kategori
* Riwayat transaksi
* Arus kas
* Pengaturan aplikasi
* Preferensi tema

Tidak memerlukan database maupun server eksternal.

---

## Teknologi

### Frontend

* HTML5
* CSS3
* JavaScript (Vanilla JS)

### Library

* Tailwind CSS
* Lucide Icons
* Chart.js

### Storage

* Browser Local Storage

---

