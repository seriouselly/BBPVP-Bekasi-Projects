# Project PBL Batch 3A BBPVP Bekasi 2025

## Backend

Backend menggunakan Node.js, Express, dan MySQL untuk API data siswa.

### Fitur

- CRUD data siswa
- Autentikasi JWT
- Enkripsi password dengan bcrypt

### Instalasi & Menjalankan

1. Masuk ke folder `backend`
2. Install dependencies:
   ```bash
   npm install
   ```
3. Buat file `.env` dan atur variabel database serta JWT (lihat contoh di `.env`)
4. Jalankan server:
   ```bash
   npm run dev
   ```
   Server berjalan di http://localhost:3000

## Frontend

Frontend menggunakan React + Vite untuk antarmuka CRUD siswa.

### Fitur

- Tabel data siswa
- Form tambah/edit siswa
- Integrasi API backend
- Styling dengan Bootstrap

### Instalasi & Menjalankan

1. Masuk ke folder `frontend`
2. Install dependencies:
   ```bash
   npm install
   ```
3. Jalankan aplikasi:
   ```bash
   npm run dev
   ```
   Frontend berjalan di http://localhost:5173

### Catatan

Pastikan backend sudah berjalan agar frontend bisa mengambil data siswa.

---

Untuk pengembangan lebih lanjut, lihat masing-masing folder `backend` dan `frontend`.