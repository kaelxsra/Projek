# 📦 Program Peminjaman Barang Sekolah

Repository ini berisi perancangan database untuk Program Peminjaman Barang di Sekolah.  
Sistem ini digunakan untuk mencatat proses peminjaman, pengembalian, dan persetujuan barang.

## 🎯 Tujuan
- Mempermudah pendataan peminjaman barang sekolah
- Mengurangi risiko kehilangan barang
- Menyediakan dokumentasi database yang terstruktur

## 🧩 Fitur Sistem
- Manajemen data pengguna (siswa/guru)
- Manajemen data barang
- Transaksi peminjaman dan pengembalian
- Persetujuan peminjaman oleh petugas
- Pencatatan kondisi barang

## 🗄️ Database Diagram (ERD)

![ERD Peminjaman Barang](images/erd-peminjaman-barang.svg)

> Diagram dibuat menggunakan **dbdiagram.io**

## 🏗️ Struktur Database
Sistem database terdiri dari beberapa tabel utama:
- User
- Barang
- Peminjaman
- Detail Peminjaman
- Petugas
- Persetujuan

Relasi database memungkinkan satu peminjaman memiliki lebih dari satu barang.

## 📁 Struktur Repository

Projek/
├── README.md
├── images/
│ └── erd-peminjaman-barang.svg
├── db/
│ └── diagram.dbml
└── sql/
└── create_table.sql


## 🛠️ Tools yang Digunakan
- dbdiagram.io
- GitHub

## 📌 Catatan
Repository ini dibuat untuk keperluan tugas sekolah dan dapat dikembangkan lebih lanjut.

---

**Dibuat oleh**  
Nama  : Mikael Putra Permana  
Kelas : XI-RPL

![ERD Peminjaman Barang](images/Untitleds.png)
