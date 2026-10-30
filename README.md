# Tugas Praktikum 5 UI/UX

| | |
|---|---|
| Nama | _isi nama_ |
| NIM | _isi NIM_ |
| Kelas | _isi kelas_ |
| Mata Kuliah | UI/UX |

Repo ini berisi dua halaman web statis untuk Praktikum 5. Keduanya ditulis dengan HTML dan CSS internal (di dalam tag `<style>`), tanpa framework dan tanpa JavaScript.

## Isi Repo

```
.
├── alpukat.html     Halaman 1: Alpukat Buah Nikmat Kaya Manfaat
├── perkutut.html    Halaman 2: Perkutut Jawa Suara Emas Penghibur Hati
└── image/           Semua gambar yang dipakai kedua halaman
```

## Halaman 1: Alpukat (`alpukat.html`)

Halaman informasi sekaligus penawaran jual alpukat. Isinya sejarah singkat alpukat, kandungan gizi, khasiat vitamin, daftar harga, galeri jenis alpukat, promo, dan info COD.

Materi CSS yang diterapkan:

- Selector elemen untuk `body`, `h1`, `p`
- Class `.center` untuk membuat gambar rata tengah dengan `margin: auto`
- Class `.foto` untuk galeri berlatar hitam berisi empat jenis alpukat
- Class `.cod` untuk kotak info pembayaran dengan border titik-titik
- Tabel harga dengan `border-collapse` dan warna baris selang-seling memakai `tr:nth-child(even)` dan `tr:nth-child(odd)`
- Selector id `#tombol` untuk tombol PESAN SEKARANG

## Halaman 2: Perkutut Jawa (`perkutut.html`)

Halaman tentang burung perkutut jawa: kutipan Soekarno, profil, cara beternak, galeri, dan penawaran harga.

Materi CSS yang diterapkan:

- Menu navigasi dengan link anchor ke bagian Profil, Budidaya, dan Harga
- `blockquote` dengan latar kuning untuk kutipan
- Pseudo-element `p:first-of-type::first-letter` untuk huruf awal besar (drop cap)
- `object-fit: cover` supaya ukuran gambar seragam
- Media query `@media screen and (max-width: 600px)` agar tampilan tetap rapi di HP

## Cara Membuka

Download atau clone repo ini, lalu buka `alpukat.html` atau `perkutut.html` langsung di browser. Folder `image/` harus tetap sejajar dengan file HTML supaya gambarnya tampil.
