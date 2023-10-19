# PSEUDOCODE HALAMAN LOGIN DENGAN BOOTSTRAP

1. Mulai dengan dokumen HTML dasar:
    1.1. Deklarasikan doctype
    1.2. Mulai tag html dan tentukan bahasa
    1.3. Tambahkan tag head
    1.4. Atur karakter set dan viewport meta tag

2. Sisipkan Bootstrap stylesheet:
    2.1. Tambahkan link ke Bootstrap CDN di dalam tag head

3. Buat tag body:
    3.1. Tetapkan class untuk background (misalnya `bg-light`) dan class lain untuk styling global jika perlu

4. Gunakan Flexbox untuk memusatkan elemen (opsional, tapi sering digunakan untuk halaman login):
    4.1. Tetapkan class `d-flex`, `justify-content-center`, dan `align-items-center` pada body atau elemen pembungkus utama
    4.2. Tentukan tinggi minimal (misalnya `min-height: 100vh`)

5. Buat struktur grid Bootstrap untuk layout (meskipun dalam kasus ini kita mungkin tidak memerlukan grid yang rumit):
    5.1. Tambahkan elemen container (`<div class="container">`) untuk pembungkus utama
    5.2. Tambahkan elemen row (`<div class="row">`) di dalam container
    5.3. Untuk halaman login yang sederhana, kita mungkin hanya ingin memusatkan form login. Oleh karena itu, gunakan kolom dengan class offset untuk memusatkan:
        5.3.1. Contoh: `<div class="col-md-4 offset-md-4">` (Ini akan membuat kolom dengan lebar 4 unit grid di perangkat medium, dan menggeser kolom 4 unit dari kiri)

6. Dalam kolom yang telah dibuat, tambahkan kartu Bootstrap untuk form login:
    6.1. Buat elemen dengan class `card` untuk kartu luar
    6.2. Di dalam kartu, tambahkan `card-body` untuk konten kartu

7. Buat form login di dalam `card-body`:
    7.1. Tambahkan input untuk email dengan class `form-control`
    7.2. Tambahkan input untuk password dengan class `form-control`
    7.3. Tambahkan checkbox "Remember me" dengan class `form-check` dan komponen terkait
    7.4. Tambahkan tombol "Sign In" dengan class `btn` dan `btn-primary`

8. Sebagai sentuhan akhir, tambahkan teks hak cipta atau informasi lain di bawah form jika diperlukan.

9. Selesai.
