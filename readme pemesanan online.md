# README: Proyek Web Pemasaran Online

## Ringkasan
Proyek ini adalah platform berbasis web yang dirancang untuk memfasilitasi pemasaran online. Platform ini menjadi solusi bagi Usaha Mikro, Kecil, dan Menengah (UMKM) untuk memasarkan produk secara efisien melalui e-commerce. Proyek ini dibuat sebagai bagian dari tugas mata kuliah Pemrograman Web.

## Fitur
1. **Sistem Login**
   - Login aman untuk admin dan pelanggan.
   - Kontrol akses berbasis peran.

2. **Registrasi Pengguna**
   - Pengguna baru dapat mendaftar dengan memasukkan username, email, dan password.

3. **Dashboard**
   - Dashboard yang ramah pengguna untuk admin dan pelanggan.

4. **Pemesanan Produk**
   - Memungkinkan pelanggan untuk memesan produk.
   - Termasuk fitur seperti memilih nama produk, jumlah, tanggal pengiriman, dan menambahkan catatan.

5. **Manajemen Pesanan**
   - Admin dapat melihat, mengedit, dan menghapus pesanan pelanggan.

6. **Profil Pelanggan**
   - Menampilkan informasi pelanggan, termasuk nama, alamat, dan detail keanggotaan.

## Teknologi yang Digunakan
- **Frontend**: HTML, CSS
- **Backend**: PHP
- **Database**: MySQL
- **Server**: XAMPP (Apache)

## Langkah Instalasi

1. **Prasyarat**
   - Instal [XAMPP](https://www.apachefriends.org/index.html) pada sistem Anda.
   - Pastikan PHP dan MySQL sudah terkonfigurasi dengan benar.

2. **Pengaturan File Proyek**
   - Clone atau unduh repositori ini.
   - Tempatkan file proyek di direktori `htdocs` pada XAMPP.

3. **Konfigurasi Database**
   - Buka `phpMyAdmin` melalui XAMPP.
   - Buat database baru (misalnya, `pemasaran_online`).
   - Impor file `database.sql` yang disediakan dalam proyek.

4. **Konfigurasi Koneksi**
   - Perbarui detail koneksi database di file `koneksi.php`.
     ```php
     $servername = "localhost";
     $username = "root";
     $password = "";
     $dbname = "pemesanan_online";
     ```

5. **Jalankan Proyek**
   - Jalankan layanan Apache dan MySQL menggunakan XAMPP.
   - Akses proyek melalui browser di `http://localhost/<folder-proyek>`.

## Cara Penggunaan
- **Admin**: Login untuk mengelola pesanan, profil pelanggan, dan daftar produk.
- **Pelanggan**: Login atau daftar untuk memesan dan melacak pesanan.

## Struktur Folder
```
project-folder/
├── css/               # Berisi file CSS untuk styling
├── img/               # Menyimpan gambar
├── js/                # Berisi file JavaScript (jika ada)
├── php/               # Berisi skrip PHP untuk logika backend
├── index.php          # Titik masuk utama aplikasi
└── README.md          # Dokumentasi proyek
```

## Kontribusi
Kontribusi sangat diterima! Silakan ikuti langkah-langkah berikut:
1. Fork repositori ini.
2. Buat branch baru (`git checkout -b fitur/FiturAnda`).
3. Commit perubahan Anda (`git commit -m 'Menambahkan fitur tertentu'`).
4. Push ke branch Anda (`git push origin fitur/FiturAnda`).
5. Buka pull request.

## Penulis
- Mohamad Dharma Amerta Brahma Putra
- Jovanda Kelvin W. P.
- Wulan Tsania
- Pracitra Ade Saputra
- Kumara Veda Harya Putra

## Ucapan Terima Kasih
Terima kasih khusus kepada dosen kami, Abdi Pandu Kusuma, S.Kom., M.T., atas bimbingan dan dukungannya.

## Lisensi
Proyek ini dilisensikan di bawah Lisensi MIT.
