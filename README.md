   ## 1. TUJUAN PEMBELAJARAN
- Merancang dan membuat layout halaman Login dan Registrasi.
- Menggunakan widget dasar Flutter seperti Scaffold, Column, TextField, dan ElevatedButton.
- Mengimplementasikan navigasi antar halaman menggunakan Navigator.
- Mengelola state sederhana dan menyimpan data input pengguna.
- Memahami event handling seperti aksi tombol login/registrasi.

   ## 2. ALAT YANG DIBUTUHKAN
- Flutter SDK
- Android Studio / VS Code (dengan ekstensi Flutter)
- Emulator Android/iOS atau perangkat fisik

   ## 3. ANALISIS PROGRAM
- main.dart
    - Tempat awal aplikasi dijalankan, sekaligus untuk menentukan halaman pertama yang muncul misalnya halaman login atau homepage
    ![main.dart](image/main.jpg)

- login_page.dart
   - Halaman ini berisi form login dengan input email dan password. Kalau datanya benar, pengguna masuk ke homepage. Kalau salah, akan muncul pesan gagal login
    ![login_page.dart](image/login.jpg)

- register_page.dart
   - Halaman ini berisi form registrasi untuk memasukkan nama lengkap, email, dan password. Data akan disimpan sebagai user baru. Jika berhasil, akan muncul notifikasi sukses lalu diarahkan kembali ke halaman login
    ![register_page.dart](image/register%20.jpg)

- home_page.dart
   - Halaman utama ini muncul setelah login dengan akun terdaftar. Di dalamnya ada pesan selamat datang menggunakan nama pengguna, serta     tombol logout untuk kembali ke halaman login
    ![home_page.dart](image/home%20.jpg)

- user_data.dart
   - Bagian ini digunakan untuk menyimpan data akun yang sudah diregistrasikan dengan memanfaatkan struktur data Map
    ![user_data.dart](image/data.jpg)

   ## 4. OUTPUT PROGRAM
- halaman login
    ![login](image/halaman_login.jpg)
- halaman registrasi
    ![registrasi](image/halaman_register.jpg)
- halaman home
    ![home](image/halaman_home.jpg)

   ## 5. LATIHAN 
- validasi input
![latihan1](image/latihan1.PNG)
- Menampilkan/Menyebunyikan Password
![latihan2](image/latihan2.PNG)
- animasi sederhana
![latihan3](image/latihan3.PNG)
- simpan sesi login
![latihan4](image/latihan4.PNG)
