# Aplikasi Perpustakaan SMP Al Falah Kota Bekasi

Aplikasi Perpustakaan SMP Al Falah Kota Bekasi merupakan aplikasi berbasis desktop yang dirancang untuk membantu proses pengelolaan data perpustakaan, mulai dari pendataan siswa, petugas, presensi petugas, pengunjung, koleksi buku, transaksi peminjaman dan pengembalian buku, hingga pembuatan laporan.

Aplikasi ini dibuat sebagai **Proyek Kerja Praktek Program Studi Teknik Informatika, Fakultas Teknik dan Ilmu Komputer, Universitas Indraprasta PGRI**.

## Teknologi

- **Java**
- **NetBeans**
- **MySQL**

## Fitur Aplikasi

Aplikasi memiliki beberapa pengguna dengan hak akses sesuai perannya, yaitu **Admin**, **Petugas**, dan **Siswa**.

### Admin

- Login Admin
- Mengelola data siswa
- Mengelola data petugas
- Mengelola data presensi petugas
- Mengelola data pengunjung
- Mengelola koleksi buku
- Mengelola transaksi peminjaman buku
- Mengelola transaksi pengembalian buku
- Mengakses laporan perpustakaan
- Mencetak laporan

### Petugas

- Login ke aplikasi
- Mengelola data siswa
- Mengelola data petugas
- Mencatat presensi petugas
- Mencatat data pengunjung
- Mengelola koleksi buku
- Melakukan transaksi peminjaman buku
- Melakukan transaksi pengembalian buku
- Melihat dan mencetak laporan

### Siswa

- Terdaftar sebagai anggota perpustakaan
- Melakukan peminjaman buku sesuai ketentuan
- Melakukan pengembalian buku
- Menggunakan layanan perpustakaan sesuai hak akses yang diberikan

## Data yang Dikelola

Aplikasi mengelola beberapa jenis data utama:

- **Data Siswa** — NIS, nama, kelas, jenis kelamin, dan nomor HP.
- **Data Petugas** — ID petugas, nama, jenis kelamin, dan nomor HP.
- **Data Presensi Petugas** — ID petugas, nama, tanggal presensi, dan status kehadiran.
- **Data Pengunjung** — NIS, nama, kelas, dan tanggal kunjungan.
- **Data Buku** — kode buku, judul, kategori, penulis, penerbit, tahun terbit, dan stok.
- **Data Peminjaman** — kode pinjam, data siswa, data buku, tanggal pinjam, dan tenggat pinjam.
- **Data Pengembalian** — kode kembali, data peminjaman, tanggal kembali, dan denda.

## Tampilan Aplikasi

### Halaman Login

![Login](dokumentasi/01-login.png)

Halaman login digunakan untuk melakukan autentikasi pengguna sebelum masuk ke dalam aplikasi.

### Beranda

![Beranda](dokumentasi/02-beranda.png)

Beranda menampilkan ringkasan informasi perpustakaan dan menu navigasi untuk mengakses fitur utama aplikasi.

### Data Siswa

![Data Siswa](dokumentasi/03-data-siswa.png)

Halaman untuk mengelola data siswa yang menjadi anggota perpustakaan.

### Data Pengunjung

![Data Pengunjung](dokumentasi/04-data-pengunjung.png)

Halaman untuk mencatat dan mengelola kunjungan siswa ke perpustakaan.

### Data Petugas

![Data Petugas](dokumentasi/05-data-petugas.png)

Halaman untuk mengelola data petugas perpustakaan.

### Presensi Petugas

![Presensi Petugas](dokumentasi/06-presensi-petugas.png)

Halaman untuk mencatat kehadiran petugas perpustakaan berdasarkan tanggal dan status kehadiran.

### Data Buku

![Data Buku](dokumentasi/07-data-buku.png)

Halaman untuk mengelola koleksi buku, meliputi kode buku, judul, kategori, penulis, penerbit, tahun terbit, dan stok.

### Peminjaman Buku

![Peminjaman Buku](dokumentasi/08-peminjaman-buku.png)

Halaman untuk melakukan transaksi peminjaman buku. Sistem menampilkan data siswa dan buku berdasarkan data yang tersimpan serta memperbarui stok setelah transaksi disimpan.

### Pengembalian Buku

![Pengembalian Buku](dokumentasi/09-pengembalian-buku.png)

Halaman untuk melakukan transaksi pengembalian buku. Tersedia fitur **Cek Denda** untuk menghitung biaya keterlambatan.

### Laporan

![Laporan](dokumentasi/10-laporan.png)

Halaman laporan digunakan sebagai pusat pencetakan berbagai laporan perpustakaan.

### Laporan Data Siswa

![Laporan Data Siswa](dokumentasi/11-laporan-siswa.png)
![Cetak Laporan Data Siswa](dokumentasi/17-cetak-laporan-siswa.png)

Laporan yang menampilkan data siswa dan dapat digunakan sebagai dokumentasi administrasi perpustakaan.

### Laporan Data Pengunjung

![Laporan Data Pengunjung](dokumentasi/12-laporan-pengunjung.png)
![Cetak Laporan Data Pengunjung](dokumentasi/18-cetak-laporan-pengunjung.png)

Laporan yang menampilkan data kunjungan siswa ke perpustakaan.

### Laporan Data Petugas dan Presensi Petugas

![Laporan Data Petugas dan Presensi Petugas](dokumentasi/13-laporan-petugas-dan-presensi-petugas.png)
![Cetak Laporan Data Petugas](dokumentasi/19-cetak-laporan-petugas.png)
![Cetak Laporan Data Presensi Petugas](dokumentasi/20-cetak-laporan-presensi-petugas.png)

Laporan yang menampilkan data petugas dan presensi petugas perpustakaan.

### Laporan Data Buku

![Cetak Laporan Data Buku](dokumentasi/14-cetak-laporan-buku.png)

Cetak laporan yang menampilkan data koleksi buku perpustakaan.

### Laporan Data Peminjaman Buku

![Laporan Peminjaman](dokumentasi/15-laporan-peminjaman.png)
![Cetak Laporan Peminjaman](dokumentasi/21-cetak-laporan-peminjaman.png)

Laporan yang menampilkan riwayat transaksi peminjaman buku.

### Laporan Data Pengembalian Buku

![Laporan Pengembalian](dokumentasi/16-laporan-pengembalian.png)
![Cetak Laporan Pengembalian](dokumentasi/22-cetak-laporan-pengembalian.png)

Laporan yang menampilkan riwayat transaksi pengembalian buku beserta informasi denda.

## Proses Utama

### Login dan Autentikasi

Pengguna memasukkan nama pengguna dan kata sandi. Sistem memverifikasi data login dan mengarahkan pengguna ke halaman Beranda apabila proses autentikasi berhasil.

### Pengelolaan Data

Data siswa, petugas, presensi, pengunjung, dan buku dapat ditambahkan, disimpan, diubah, dihapus, serta dicari sesuai kebutuhan pengelolaan perpustakaan.

### Peminjaman Buku

Alur peminjaman buku:

```text
Data Siswa
    ↓
Pilih / Input Data Buku
    ↓
Input Tanggal Pinjam
    ↓
Input Tenggat Pinjam
    ↓
Simpan Transaksi
    ↓
Stok Buku Berkurang
```

### Pengembalian Buku

Alur pengembalian buku:

```text
Data Peminjaman
    ↓
Input Tanggal Kembali
    ↓
Cek Denda
    ↓
Simpan Pengembalian
    ↓
Stok Buku Diperbarui
```

### Pembuatan Laporan

Data yang tersimpan dalam aplikasi dapat digunakan untuk menghasilkan laporan:

- Laporan Data Siswa
- Laporan Data Pengunjung
- Laporan Data Petugas
- Laporan Data Presensi Petugas
- Laporan Data Buku
- Laporan Data Peminjaman Buku
- Laporan Data Pengembalian Buku

## Aturan Perpustakaan

Beberapa aturan yang diterapkan dalam aplikasi berdasarkan laporan KKP:

- Setiap pengguna wajib melakukan login menggunakan akun yang terdaftar.
- NIS siswa dan ID petugas digunakan sebagai identitas unik sehingga tidak boleh terjadi duplikasi.
- Presensi petugas dicatat satu kali setiap hari.
- Setiap kunjungan siswa dicatat berdasarkan NIS dan tanggal kunjungan.
- Setiap buku memiliki kode khusus dan stok diperbarui ketika terjadi transaksi.
- Peminjaman hanya dapat dilakukan oleh siswa yang terdaftar sebagai anggota perpustakaan.
- Siswa tidak boleh meminjam lebih dari tiga buku sekaligus.
- Siswa tidak dapat melakukan peminjaman lain sebelum buku yang dipinjam dikembalikan.
- Jika pengembalian melewati batas waktu yang ditentukan, sistem menghitung denda keterlambatan.
- Buku yang rusak atau hilang wajib diganti sesuai kebijakan sekolah.

## Pengembang

**Kelompok KKP Program Studi Teknik Informatika**

Universitas Indraprasta PGRI

Anggota:

- Vernando Islamay Hartono — 202243500478
- Anatasya Aulya Wilatiktah — 202243500491
- Cristian Prayogi — 202243500511
- Ibnu Sabil — 202243500528
- Masrur Romzi — 202243500542
- Nur Faishal Ramdani — 202243500550
- Syifa Zaina Hilman — 202243500566
- Fakhry Firdaus Salam — 202243500579

**Program Studi Teknik Informatika**  
**Fakultas Teknik dan Ilmu Komputer**  
**Universitas Indraprasta PGRI**

---

**Kerja Praktek — 2025**
