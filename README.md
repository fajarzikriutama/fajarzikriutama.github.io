# Personal page Fajar Zikri Utama

Menggunakan desain dan kode `code.html` dari ZIP Stitch milik Anda: tema gelap, aksen emas, kartu tautan. Navigasi bawah dihapus. Pada desktop (lebar minimal 1024px), profil dan tautan tampil berdampingan agar semua tautan muat dalam satu layar pada ukuran desktop umum. Tampilan ponsel tetap satu kolom.

## File

- `index.html`: profil dan isi halaman.
- `style.css`: gaya tambahan dan penyesuaian responsif.
- `tailwind-config.js`: konfigurasi tema asli Stitch.
- `assets/profile.svg`: placeholder inisial FZU.
- `assets/foto-profil.jpg`: foto profil yang digunakan, dengan crop wajah melalui CSS.

Buka `index.html` di browser. Internet diperlukan untuk Tailwind CDN, Google Fonts, dan Material Symbols. Tidak ada langkah build.

## Mengganti foto dan tautan

1. Ganti `assets/foto-profil.jpg` untuk memperbarui foto. Atur `object-position` di `style.css` jika posisi wajah berbeda.
2. Tautan sosial aktif: Facebook (`FajarZikri`), YouTube (`@FajarZikri`), TikTok (`@fajarzikriutama`), dan LinkedIn (`fajarzikriutama`). Ikon merek memakai SVG lokal di dalam HTML.
3. Kartu utama menuju `blog.fajarzikri.my.id`, `english.fajarzikri.my.id`, dan `class.fajarzikri.my.id`. Tautan mengikuti website asli `https://fajarzikri.my.id/`.
4. Nama, gelar, bio, dan footer dapat diedit di `index.html`.

Repo tujuan: https://github.com/fajarzikriutama/fajarzikriutama.github.io. Konfigurasi domain berada di `CNAME`.
