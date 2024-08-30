# Proyek Flutter User List

Proyek ini adalah aplikasi Flutter sederhana yang menampilkan daftar pengguna dan detail pengguna.

## Struktur Proyek

```
lib/
│
├── dummy/
│   └── people.dart
│
├── model/
│   └── people.dart
│
├── ui/
│   ├── user_page.dart
│   └── user_detail.dart
│
└── main.dart
```

## Deskripsi File

1. `lib/dummy/people.dart`: Berisi data dummy untuk daftar pengguna.
2. `lib/model/people.dart`: Mendefinisikan model data untuk objek Person.
3. `lib/ui/user_page.dart`: Menampilkan halaman daftar pengguna.
4. `lib/ui/user_detail.dart`: Menampilkan halaman detail pengguna.
5. `lib/main.dart`: File utama yang menjalankan aplikasi Flutter.

## Fitur

- Menampilkan daftar pengguna dengan foto profil, nama, dan email.
- Melihat detail pengguna termasuk nama, email, dan alamat.
- Navigasi antar halaman daftar pengguna dan detail pengguna.

## Cara Menjalankan Proyek

1. Pastikan Anda telah menginstal Flutter SDK.
2. Clone repositori ini ke komputer Anda.
3. Buka terminal dan arahkan ke direktori proyek.
4. Jalankan perintah `flutter pub get` untuk menginstal dependensi.
5. Jalankan perintah `flutter run` untuk menjalankan aplikasi di emulator atau perangkat fisik.

## Dependensi

Proyek ini menggunakan dependensi standar Flutter. Tidak ada dependensi tambahan yang diperlukan.

## Kontribusi

Jika Anda ingin berkontribusi pada proyek ini, silakan buat pull request atau laporkan masalah di bagian Issues.
