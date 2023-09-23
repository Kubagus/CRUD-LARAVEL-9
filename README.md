# Program CRUD sederhana dengan fitur pencarian menggunakan Laravel 9

## Requirement
Sebelum menjalankan program, pastikan telah menginstall:
- Xampp atau aplikasi sejenis dengan versi php 8.2
- Composer
- Code editor

## Instalasi
- Clone repository/download
- Buka git di dalam foldernya, lalu jalankan command 
```
composer install
composer update
```
- Copy file `.env.example` dan ubah namanya menjadi `.env`
- buat database dengan nama laravel
- generate key
  ```
  php artisan key:generate
  ```
- Lakukan migrasi
 ```
 php artisan migrate --seed
```
- jalankan php artisan serve

