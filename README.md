# Tugas Rutin 10 — Blog CRUD (Laravel)

## Fitur
- CRUD post (tambah, lihat, edit, hapus) dengan Resource Controller
- Validasi form dan pesan error per field
- Flash message sukses/gagal
- Pagination (5 post per halaman)
- Layout master dan komponen Blade (`x-alert`, `x-card`)

## Langkah Install
1. `composer install`
2. `copy .env.example .env`
3. `php artisan key:generate`
4. Buat database `p10_blog`, sesuaikan DB_* di `.env`
5. `php artisan migrate`
6. (Data contoh) `php artisan db:seed --class=PostSeeder`
7. `php artisan serve` lalu buka http://127.0.0.1:8000

## Screenshot
Lihat folder `screenshot/`.