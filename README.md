<h1 align="center">Selamat datang di Sistem Informasi Akademik Sekolah! 👋</h1>

## Apa itu Sistem Informasi Akademik Sekolah?
**Sistem Informasi Akademik Sekolah adalah Website untuk para siswa dapat melihat jadwal pelajaran, dan nilai rapot dan para guru dapat menambahkan nilai siswa dengan muda melalui website.**

## Fitur apa saja yang tersedia di Sistem Informasi Akademik Sekolah?

- Autentikasi Admin
- User & CRUD
- Jadwal & CRUD
- Kelas & CRUD
- Mata Pelajaran & CRUD
- Guru & CRUD
- Siswa & CRUD
- Rapot
- Dan lain-lain

## Release Date

**Release date : 28 Apr 2020**


## Default Account for testing

**Admin Default Account**

- email: admin@gmail.com
- Password: 12345678

---

## Install

1. **Install Composer**

```bash
composer install
cp .env.example .env
```

2. **Buka `.env` lalu ubah baris berikut sesuai dengan databasemu yang ingin dipakai**

```bash
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
```

3. **Instalasi website**

```bash
php artisan key:generate
php artisan migrate --seed
```

4. **Jalankan website**

```bash
php artisan serve
```

## Contributing

Contributions, issues and feature requests di persilahkan.
Jangan ragu untuk memeriksa halaman masalah jika Anda ingin berkontribusi. **Berhubung Project ini saya sudah selesaikan sendiri, namun banyak fitur yang kalian dapat tambahkan silahkan berkontribusi yaa!**

## License

- **Sistem Informasi Akademik Sekolah is open-sourced software licensed under the MIT license.**
