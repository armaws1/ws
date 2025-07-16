# MoneyBalance

Aplikasi web sederhana untuk mengelola keuangan pribadi.  
Dibuat dengan PHP dan SQLite, memiliki tampilan modern, fitur CRUD transaksi, login/register, serta role user dan admin.

---

## Fitur

- **Register & Login**: Pengguna bisa daftar dan login dengan username & password.
- **Role User & Admin**: 
  - User: hanya bisa melihat dan kelola transaksi milik sendiri.
  - Admin: bisa melihat semua transaksi user.
- **CRUD Transaksi**: Tambah, lihat, edit, dan hapus transaksi (pemasukan/pengeluaran).
- **Dashboard User & Admin**: Tampilan dashboard berbeda sesuai role.
- **Desain Modern**: Menggunakan CSS3, tampilan responsive dan profesional.
- **Keamanan**: Password di-hash, session aman, dan database terpisah.

---

## Struktur Folder

```
MoneyBalance/
├── db/
│   └── database.sqlite
├── inc/
│   └── db.php
├── public/
│   ├── admin.php
│   ├── edit_transaksi.php
│   ├── index.php
│   ├── login.php
│   ├── logout.php
│   ├── register.php
│   ├── style.css
│   ├── transaksi.php
│   └── delete_transaksi.php
```

---

## Cara Install & Jalankan

1. **Clone / Download project ini** ke komputer kamu.
2. **Pastikan PHP dan web server aktif** (direkomendasikan Laragon/XAMPP).
3. **Buka folder project** di web server (misal: `localhost/MoneyBalance/public/`).
4. **Database** sudah ada di folder `db/database.sqlite`.
5. **Akses aplikasi via browser**:
    - `http://localhost/MoneyBalance/public/login.php` untuk login/register
    - `http://localhost/MoneyBalance/public/index.php` untuk dashboard user
    - `http://localhost/MoneyBalance/public/admin.php` untuk dashboard admin

---

## Akun Demo

- **User**:  
  - Username: `arma`  
  - Password: `123`
- **Admin**:  
  - Username: `admin`  
  - Password: `admin`  
  *(atau edit DB langsung via DB Browser for SQLite)*

---

## Tools & Teknologi

- **PHP 7+**
- **SQLite**
- **HTML5 & CSS3**
- **Laragon/XAMPP (untuk localhost)**
- **DB Browser for SQLite** (edit DB manual)

---

## Author

- Nama: Armaya Wira Sandi
- NIM: 231240001437
- Project untuk tugas pemrograman web 2025

---

## Lisensi

Project ini dibuat untuk pembelajaran dan tugas kuliah.  
Bebas digunakan, diubah, dan dikembangkan lebih lanjut.
