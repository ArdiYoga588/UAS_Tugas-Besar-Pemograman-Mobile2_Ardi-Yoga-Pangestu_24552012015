# UAS_Tugas-Besar-Pemrograman-Mobile-2  
## E-Commerce Jersey Bola  
**Nama:** Ardi Yoga Pangestu  
**NIM:** 24552012015  

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
- Menampilkan detail produk
- Menampilkan harga dan gambar produk

---

## 🔐 Firebase
Firebase digunakan untuk:
- **Authentication**
  - Login pengguna
  - Registrasi pengguna

Konfigurasi Firebase dilakukan melalui:
- Firebase Web App
- `firebase_options.dart`
- `Firebase.initializeApp()`

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
- Di batalkan

---

## 🖼 Tampilan Aplikasi
- **Home**  
  ![WhatsApp Image 2026-01-22 at 00 59 23](https://github.com/user-attachments/assets/f958f13e-b018-426f-a808-cccbd113ef81)

  Menampilkan halaman utama aplikasi dengan navigasi bawah.

- **Produk**  
  Menampilkan daftar jersey bola dan juga harga penambahan favorit.

- **Favorite**  
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
