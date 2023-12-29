# React Authentication

## User Authentication Basics

User Authentication hanyalah teknik untuk memverifikasi bahwa pengguna aplikasi benar-benar orang yang mereka katakan.

## Cara kerja

Ada tiga strategi atau tes utama yang dapat digunakan untuk memverifikasi pengguna:

1. The knowledge test (Knowledge-Based Authentication)
   authentication yang paling umum digunakan. Memverifikasi identitas pengguna berdasarkan pada sesuatu hal yang mereka ketahui (pin atau password).
   masalah utama dengan strategi ini:
   - terlalu bergantung pada kekuatan kata sandi.
   - bisa mudah ditebak atau dicari oleh peretas.
2. The ownership test (Ownership-Based Authentication)
   memverifikasi identitas pengguna berdasarkan apakah mereka memiliki sesuatu atau tidak (akses ke alamat email atau nomor telephone atau kode OTP).
   authentication ini cukup aman tetapi tetap memiliki masalahnya sendiri:
   - Beberapa mengandalkan strategi berbasis pengetahuan secara tidak langsung (yaitu, seseorang bisa menebak kata sandi email).
   - Perangkat fisik dapat dicuri.
   - Perangkat fisik bisa hilang.

karena knowledge-based dan ownership-based masih memiliki kerentanan maka hadirlah "Two-Factor Authentication". Ini adalah strategi yang direkomendasikan atau diwajibkan oleh banyak situs. Dimana ini mengkombinasikan knowledge-based dan ownership-based.

3. The biological test (Biological-Based Authentication)
   memverifikasi pengguna berdasarkan pada karakteristik biologis yang sulit dipalsukan oleh peretas (wajah, sidik jari dan pemindaian mata)
