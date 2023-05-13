# web-smpKu
Latihan Laravel -  Membuat Aplikasi WEB sekolah SMP 
Dibuat dengan Framework Laravel 8 & adminLTE


## Setup
- buka direktori project di terminal anda.
- ketikan command : cp .env.example .env (copy paste file .env.example)
- buat database 

Lalu ketik command dibawah ini
- composer install
- php artisan optimize:clear 
- php artisan key:generate (generate app key)
- php artisan migrate (migrasi database)
- php artisan db:seed 

## Login
Email : rahmsaepul@example.com
Password : 123456

## Fitur
# Front / Depan
- Home (Halaman home,menampilkan artikel,pengumuman terbaru) 
- Artikel & Show + pencarian artikel  
- Pengumuman & Show

# admin
- Autentikasi (menggunakan fortify)
- Halaman Dashboard
- Manage User (CRUD)
- Manage Artikel (CRUD)
- Manage Agenda (CRUD)
- Manage Pengumuman (CRUD)
- Manage Kategori Artikel (CRUD)

