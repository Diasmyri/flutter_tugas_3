# Flutter Profile Page

Project ini merupakan aplikasi sederhana berbasis Flutter yang dibuat untuk menampilkan halaman profil pengguna.

- **Nama:** Dias Mayri
- **Kelas:** TI24PSE3
- **NIM:** 1124160056

## Ringkasan Progress Pengerjaan

### Day 1 (Rabu, 28 Oktober 2026)

**Commit 1 — `ini commit pertama yaitu pembuatan folder flutter`**

Membuat folder project Flutter sebagai tempat untuk menyimpan dan mengembangkan aplikasi yang akan dibuat.

**Commit 2 — `menambahkan import 'package:flutter/material.dart';`**

Menyalin kode awal dari materi PDF yang diberikan dosen sebagai panduan pengerjaan. Saat itu saya mengira seluruh struktur kode yang ada di dalam materi tersebut perlu diikuti dan diterapkan ke dalam project.

**Commit 3 — `mengubah username dan role`**

Menyesuaikan informasi profil dengan mengganti nama pengguna menjadi Dias Mayri dan role menjadi Mahasiswa Global Institute.

### Day 2 (Kamis, 29 Oktober 2026)

**Commit 1 — `refactor: menyederhanakan dan membersihkan kode di main.dart`**

Merapikan dan menyederhanakan isi file `main.dart` agar struktur kode lebih mudah dipahami serta tidak terlalu banyak bagian yang tidak diperlukan.

**Commit 2 — `feat: prepare profile_page.dart file structure`**

Membuat file `profile_page.dart` sebagai tempat untuk menyusun halaman profil agar kode tampilan tidak seluruhnya berada di dalam file utama aplikasi.

### Day 3 (Sabtu, 31 Oktober 2026)

**Commit 1 — `feat: create basic profile page structure with scaffold and appbar`**

Mulai membangun tampilan halaman profil menggunakan `Scaffold` dan `AppBar`, kemudian menambahkan bagian avatar serta informasi dasar pengguna.

**Commit 2 — `refactor: extract avatar and info into custom widgets`**

Memisahkan bagian avatar dan informasi pengguna menjadi widget `ProfileAvatar` dan `ProfileInfo` agar kode lebih rapi serta setiap bagian tampilan memiliki fungsi masing-masing.

**Commit 3 — `feat: add profile statistics row`**

Menambahkan bagian statistik profil yang menampilkan Projects, Followers, dan Following dengan mengatur susunan tampilannya menggunakan `Row` dan `Column`.

### Day 4 (Minggu, 1 November 2026)

**Commit 1 — `feat: add scrollable experience list using ListView.builder`**

Menambahkan daftar project atau pengalaman pengguna menggunakan `ListView.builder` sehingga seluruh item dapat ditampilkan dan digulir ketika jumlah datanya semakin banyak.

**Commit 2 — `refactor: extract list tile into ExperienceCard widget and apply styling`**

Memisahkan tampilan setiap item daftar menjadi widget `ExperienceCard`, kemudian menambahkan ikon dan mengatur tampilannya agar lebih menarik serta konsisten.

### Day 5 (Senin, 2 November 2026)

**Commit 1 — `refactor: convert ProfilePage to StatefulWidget for dynamic data`**

Mengubah `ProfilePage` dari `StatelessWidget` menjadi `StatefulWidget` agar informasi yang ditampilkan dapat diperbarui secara langsung ketika terjadi perubahan data.

**Commit 2 — `feat: complete profile page with edit feature and README`**

Mengisi README.md sesuai dengan ketentuan dan Menambahkan fitur Edit Profil menggunakan `AlertDialog` yang menyediakan kolom untuk mengubah nama pengguna. Perubahan informasi tersebut kemudian diterapkan menggunakan `setState()` sehingga hasilnya langsung terlihat pada halaman profil setelah disimpan.
