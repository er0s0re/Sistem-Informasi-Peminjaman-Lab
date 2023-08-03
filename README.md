# Sistem Informasi Peminjaman Lab

## Latar Belakang
Laboratorium merupakan fasilitas penting yang digunakan oleh mahasiswa dan dosen untuk melakukan praktikum, penelitian, atau kegiatan akademik lainnya. Untuk memanfaatkan laboratorium dengan baik, diperlukan sistem informasi yang dapat mengatur peminjaman laboratorium secara efisien dan transparan. Sistem informasi ini juga dapat membantu admin dalam mengelola data peminjaman dan membuat laporan.

## Tujuan
Tujuan dari proyek ini adalah untuk membuat sistem informasi peminjaman laboratorium “The Zeus Nganu Laboratory” yang dapat memudahkan mahasiswa dalam mengajukan dan melihat jadwal peminjaman lab, admin dalam mengelola data peminjaman, dan dosen dalam memantau kegiatan lab.

## Fitur
Fitur utama dari sistem informasi ini adalah:

1) Mahasiswa dapat register dengan data diri, kelas, dan prodi, atau login dengan akun yang sudah dibuat sebelumnya.
2) Mahasiswa dapat mengisi form peminjaman lab dengan data diri, kelas, prodi, hari, waktu, dan alasan peminjaman.
3) Mahasiswa dapat melihat jadwal lab yang sedang kosong dan status pengajuan peminjaman lab yang sudah dikirim.
4) Mahasiswa dapat mengedit profilnya sendiri.
5) Admin dapat login dengan akun khusus dan melihat daftar pengajuan peminjaman lab, menyetujui atau menolak pengajuan, dan membuat laporan peminjaman.
6) Admin dapat menghapus atau mengedit akun mahasiswa.

## Teknologi
Teknologi yang digunakan untuk membuat sistem informasi ini adalah:

- Bahasa pemrograman: PHP
- Database: MySQL
- Front-end: HTML, CSS, Bootstrap, JavaScript
- Back-end: Apache
- Tools: Visual Studio Code, XAMPP

## Cara install:
- Unduh file zip dari link ini (https://drive.google.com/file/d/1xvgUjqesLGIxuhYlPOkQAgsDXppaQbrL/view?usp=drive_link)
- Ekstrak file zip ke dalam folder htdocs yang ada di direktori C:\xampp
- Pastikan nama folder hasil ekstrak adalah "lab", sehingga lokasinya menjadi C:\xampp\htdocs\lab
- Buka software XAMPP dan aktifkan modul Apache, MySQL, dan FileZilla
- Buka browser dan masukkan URL http://localhost/phpmyadmin/
- Klik "New" untuk membuat database baru
- Beri nama database "the_lab" lalu klik "Create"
- Klik database "the_lab" yang sudah dibuat, lalu klik "Import"
- Klik "Choose File" dan pilih file "the_lab.sql" yang ada di folder db di dalam folder lab yang sudah diekstrak
- Gulir ke bawah dan klik "Import"

## Cara menggunakan:
1) Buka browser dan akses : 'localhost/lab/Login'
  - Jalankan program tersebut dengan login sebagai mahasiswa atau admin
2) Via Online tanpa Menginstall : https://penjinakberuang.000webhostapp.com

## Laporan 
  'https://drive.google.com/file/d/1bAfwBE4UvUIx9f7AKrF96Abk9eEj3fDA/view?usp=sharing'

## Anggota Tim
Proyek ini dikerjakan oleh tim The Zeus Nganu Laboratory yang terdiri dari:

1) Eros Alfedo Hermanto (2108096006) - Ketua
2) Nabila Tri Septiana (2108096011) - Anggota 1
3) Salsabila Safirana Wibisono (2108096024) - Anggota 2
4) Insanu Sholeh Jum Gunawan (2108096032) - Anggota 3

## Dosen Pengampu
Proyek ini dibimbing oleh Hery Mustofa, M.Kom sebagai dosen pengampu mata kuliah pemrograman web di Program Studi Teknologi Informasi Fakultas Sains dan Teknologi Universitas Islam Negeri Walisongo Semarang.

## Lisensi
Proyek ini dilisensikan di bawah lisensi MIT. Lihat file LICENSE untuk detailnya.
