# Lab8Web_PHP_database

# Laporan Praktikum 8 — PHP dan Database MySQL

## 1. Persiapan XAMPP

Pada tahap pertama, XAMPP digunakan sebagai lingkungan server lokal untuk menjalankan aplikasi PHP dan database. Apache digunakan untuk menjalankan halaman website, sedangkan MySQL digunakan untuk mengelola database.

## 2. Membuat Database

Database dibuat melalui phpMyAdmin dengan nama `latihan1`. Database ini digunakan untuk menyimpan seluruh informasi barang yang akan dikelola oleh aplikasi.

## 3. Membuat Tabel Data Barang

Di dalam database `latihan1`, dibuat tabel `data_barang` yang memiliki beberapa kolom, yaitu ID barang, kategori, nama, gambar, harga beli, harga jual, dan stok. Tabel ini menjadi tempat penyimpanan data barang.

## 4. Menambahkan Data Awal

Beberapa data barang dimasukkan ke dalam tabel menggunakan perintah SQL INSERT. Data awal yang digunakan adalah HP Samsung Android, HP Xiaomi Android, dan HP OPPO Android.

## 5. Membuat Koneksi Database

File `koneksi.php` dibuat untuk menghubungkan program PHP dengan database MySQL. Koneksi ini menggunakan fungsi `mysqli_connect()` agar PHP dapat mengakses data di dalam database.

## 6. Menampilkan Data Barang (Read)

File `index.php` digunakan untuk menampilkan seluruh data barang dari tabel `data_barang`. Data diambil menggunakan perintah SQL SELECT dan ditampilkan dalam bentuk tabel HTML.

## 7. Menambahkan Data Barang (Create)

File `tambah.php` digunakan untuk menambahkan barang baru ke dalam database. Pengguna mengisi formulir berisi nama barang, kategori, harga jual, harga beli, stok, dan gambar. Data kemudian disimpan menggunakan perintah SQL INSERT.

## 8. Mengubah Data Barang (Update)

File `ubah.php` digunakan untuk mengubah informasi barang yang sudah tersimpan di database. Data barang diambil berdasarkan ID menggunakan parameter URL, kemudian ditampilkan dalam formulir. Setelah formulir disimpan, perubahan diterapkan menggunakan perintah SQL UPDATE.

## 9. Membuat Tampilan CSS

File `style.css` digunakan untuk mengatur tampilan halaman website, seperti warna latar belakang, judul, tabel, formulir, dan tombol. CSS dibuat secara sederhana agar tampilan lebih rapi dan mudah digunakan.
