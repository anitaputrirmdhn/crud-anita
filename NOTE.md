Langka – Langka Membuat CRUD 
1.	Buat project baru
2.	Buat database di mysql 
3.	Pilih virtual code. buka projek Laravel baru. Kemudian  pilih New Terminal ketik dan jalankan composer create-project --prefer-dist laravel/laravel mahasiswa. 
4.	Buka Xampp pilih mysql dan klik admin.  Buat Database di Xampp/ local host my admin dengan nama yang sudah ditentukan.
5.	Setelah itu buat table migration-terminal-make:migration mahasiswa 
6.	Buat model php artisan make:model mahasiswa 
7.	Sesuaikan struktur table migrations kemudian sesuaikan file model dengan struktur table migrations.
8.	Jalankan ke terminal migrasi php artisan migrate 
9.	Buat controller dengan menjalankan php artisan make:controller MahasisawaController
10.	Setelah itu Semua halaman tampilan melalui Controller. Anda harus menampilkan data dengan menggunakan  public function index(), lalu passing data post itu ke view index.blade.php melalui method view() sebagai parameter kedua.
11.	 Buat Model, model digunakan untuk mendapatkan data dari database. Buat view di resources/views, Setelah itu kita buat file baru resources/views/posts/index.blade.php
12.	Di Laravel Anda telah membuat halaman menggunakan pagename.blade.php
13.	Buat halaman pages
14.	layout.blade.php, index.blade.php, create.blade.php, edit.blade.php,show.blade.php
15.	Buat form action mengarah ke route mahasiswa.edit dengan menggunakan public function update() untuk mengedit data,

Catatan!!
Saya mengerjakan laravel 9 mengikuti tutorial dari youtub rollo Academy ini link youtub nya : https://youtube.com/playlist?list=PLOpjxspexSIkCQNhoW8mKpQqXBgqPalxj dan maaf jika masi banyak salah. 
