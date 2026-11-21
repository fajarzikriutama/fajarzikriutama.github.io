# Personal page Fajar Zikri Utama

Menggunakan desain dan kode `code.html` dari ZIP Stitch milik Anda: tema gelap, aksen emas, kartu tautan. Navigasi bawah dihapus. Pada desktop (lebar minimal 1024px), profil dan tautan tampil berdampingan agar semua tautan muat dalam satu layar pada ukuran desktop umum. Tampilan ponsel tetap satu kolom.

## File

- `index.html`: profil dan isi halaman.
- `style.css`: gaya tambahan dan penyesuaian responsif.
- `tailwind.css`: CSS statis yang digunakan homepage.
- `tailwind-config.js`: konfigurasi tema untuk menghasilkan CSS statis.
- `assets/profile.svg`: placeholder inisial FZU.
- `assets/foto-profil-*.webp`: varian foto untuk berbagai ukuran dan kepadatan layar.
- `assets/foto-profil.jpg`: foto sumber, cadangan, dan gambar pratinjau saat tautan dibagikan.

Buka `index.html` di browser atau jalankan `python3 -m http.server 8765 --bind 127.0.0.1` dan buka `http://127.0.0.1:8765/`. Google Fonts memerlukan internet. Saat font gagal dimuat, homepage memakai font sistem.

Setelah mengubah kelas Tailwind di HTML atau tema, buat ulang `tailwind.css` dan sertakan hasilnya saat publikasi.

```sh
npx --yes tailwindcss@3.4.17 --config tailwind-config.js --content index.html --output tailwind.css --minify
```

## Mengganti foto dan tautan

1. Saat mengganti foto, perbarui JPG dan varian WebP dengan lebar 192, 352, dan 528 piksel. Jika rasio foto berubah, perbarui dimensi di HTML dan metadata Open Graph. Atur `object-position` di `style.css` jika posisi wajah berbeda.
2. Tautan sosial aktif: Facebook (`FajarZikri`), YouTube (`@FajarZikri`), TikTok (`@fajarzikriutama`), dan LinkedIn (`fajarzikriutama`). Ikon merek memakai SVG lokal di dalam HTML.
3. Kartu utama menuju `blog.fajarzikri.my.id`, `english.fajarzikri.my.id`, dan `class.fajarzikri.my.id`. Tautan mengikuti website asli `https://fajarzikri.my.id/`.
4. Nama, gelar, dan bio dapat diedit di `index.html`.

Repo tujuan: https://github.com/fajarzikriutama/fajarzikriutama.github.io. Konfigurasi domain berada di `CNAME`.
