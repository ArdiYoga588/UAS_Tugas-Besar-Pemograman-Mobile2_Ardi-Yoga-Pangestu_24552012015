# UAS_Tugas-Besar-Pemrograman-Mobile-2  
## E-Commerce Jersey Bola  
**Nama :** Ardi Yoga Pangestu  
**NIM  :** 24552012015  
**KELAS:** TIF RP-23 CNS A

---

## 📱 Deskripsi Proyek
**E-Commerce Jersey Bola** adalah aplikasi berbasis **Flutter** yang memungkinkan pengguna untuk melihat, mencari, menyukai, dan memesan jersey sepak bola secara online.

Aplikasi ini dikembangkan sebagai **Tugas Besar Individu Pemrograman Mobile 2** dengan menerapkan:
- REST API (Mock API)
- Firebase Authentication
- Deployment sebagai **Progressive Web App (PWA)** menggunakan **Netlify**

---

## 🌐 Platform
- 📱 **Android**
- 💻 **Web (PWA – Progressive Web App)**

---

## 🛠 Teknologi yang Digunakan
- **Flutter**
- **Dart**
- **REST API (MockAPI.io)**
- **Firebase**
  - Firebase Authentication
- **Flutter Web (PWA)**
- **Netlify (Deployment)**

---

## 🔗 API yang Digunakan
### REST API (MockAPI)
Digunakan untuk:
- Mengambil daftar produk jersey
- Menampilkan detail produk,seperti ukuran dan deskripsi produk
- Menampilkan harga dan gambar produk

---

## 🔐 Firebase
Authentication (auth_service.dart)
- Registrasi pengguna baru.
- Login pengguna ke dalam aplikasi.
- Manajemen identitas dan keamanan akun.

Cloud Firestore (cart_service.dart & order_service.dart)
- Penyimpanan data keranjang belanja secara real-time.
- Manajemen transaksi dan riwayat pesanan (order).
- Penyimpanan katalog produk (harga, stok, dan deskripsi jersey).

Firebase Storage
- Penyimpanan dan distribusi file gambar produk jersey agar aplikasi tetap ringan.

Konfigurasi Firebase dilakukan melalui:
- Firebase Console (Web App) untuk pengaturan proyek.
- firebase_options.dart sebagai jembatan koneksi kunci API antara Flutter dan Firebase.
- Firebase.initializeApp() pada file utama (main.dart) untuk menginisialisasi layanan saat aplikasi dijalankan.`

---

## ✨ Fitur Aplikasi

### 🔑 Autentikasi
- Login pengguna
- Registrasi pengguna
- Validasi input email dan password

---

### 🏠 Home
- Tampilan beranda aplikasi
- Pencarian produk berdasarkan nama
- Navigasi utama ke halaman produk

---

### 🛍 Produk Jersey
- Menampilkan daftar jersey sepak bola
- Data diambil dari REST API
- Tampilan gambar produk
- Informasi nama dan harga produk

---

### ❤️ Favorite
- Menambahkan produk ke favorit
- Menghapus produk dari favorit

---

### 🛒 Pesanan
- Keranjang pesanan
- Pesanan aktif
- Pesanan selesai
- Di batalkan

---

## 🖼 Tampilan Aplikasi
- **Splash Screen****Login****Registrasi**
<p align="center">
  <img src="https://github.com/user-attachments/assets/ed505f69-a0bf-4f56-825e-072a6c2816a3" width="200">
  <img src="https://github.com/user-attachments/assets/b2eac24e-1790-41a1-babe-efcd184f7f4d" width="200">
  <img src="https://github.com/user-attachments/assets/d6e0b91d-a49c-4cd3-8d12-ec7424314fcc" width="200">
</p>

  Menampilkan splash sceen,login,dan register sebelum masuk ke E-Commerce

- **Home**  
<p align="center">
  <img src="https://github.com/user-attachments/assets/f958f13e-b018-426f-a808-cccbd113ef81" width="200">
</p>
  Menampilkan halaman utama aplikasi dengan navigasi bawah.

- **Produk**  
<p align="center">
  <img src="https://github.com/user-attachments/assets/5a4b829a-e3a5-4c4c-a813-2af07d8bc703" width="200">
  <img src="https://github.com/user-attachments/assets/90d708b9-527d-429a-9da9-0d57bd48a326" width="200">
</p>
  Menampilkan daftar jersey bola dan juga harga penambahan favorit.

- **Favorite**
<p align="center">
   <img src="https://github.com/user-attachments/assets/02b2f3c2-52db-4316-8ef5-d38a43a78b19" width="200">
</p>
  Menampilkan produk yang disukai pengguna.

- **Pesanan**  
  Menampilkan keranjang,pesanan pengguna dan pembatalan pesanan.

---

## 🎯 Tujuan Proyek
Aplikasi telah di-build sebagai **Flutter Web (PWA)** dan dideploy menggunakan **Netlify**.
- Memenuhi Tugas Besar Flutter
- Menerapkan REST API
- Menggunakan Firebase Authentication
- Deploy aplikasi ke Web sebagai PWA
- Menerapkan navigasi multi-halaman dan UI dinamis
