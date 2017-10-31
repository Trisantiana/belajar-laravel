# Langkah-langkah membuat project di laravel 5.5


pertama kita membuat project baru dengan perintah :

` $ composer create-project --prefer-dist laravel/laravel perpus`

setelah semua terinstal ketikkan perintah `$ ls`


setelah itu `$ cd perpus` (masuk nama folder yang ingin kita gunakan).
kemudian ` $ ls -al` dan biasanya di linux belum ada file `.env` sehingga harus mengcopy sendiri dengan perintah ` $ cp .env.example .env` kemudian kita ulangi perintah ` $ ls -al` dan akan muncul file .env.
setelah itu kita buat generate nya dengan perintah ` $ php artisan key:generate` bila sudah ketikkan perintah `$ php artisan serve` dan biarkan dia berjalan