# MPI Matematika SMP

Media Pembelajaran Interaktif (MPI) Matematika jenjang SMP kelas 7, 8, dan 9.
Kurikulum Merdeka, pendekatan Pembelajaran Mendalam, Fase D.

Acuan TP/ATP: MGMP Matematika SMP Kabupaten Lampung Tengah, Tahun Pelajaran 2026/2027.

## Struktur

Satu materi pokok = satu halaman MPI (multi-page, bukan single page):

- `index.html` — beranda, pilih kelas
- `kelas-7/`, `kelas-8/`, `kelas-9/` — daftar materi per kelas
- `kelas-X/semester-Y/nama-materi.html` — halaman MPI per materi
- `atp/index.html` — daftar TP dan ATP
- `assets/css/style.css` — gaya bersama, responsif HP, tablet, laptop, dan TV/panel 52 inci
- `assets/js/main.js` — fungsi bersama (tahap berikutnya)

Tiap MPI berisi: pemantik, eksplorasi, LKPD digital, permainan, kuis,
refleksi, dan bagian khusus guru (panduan, kunci, miskonsepsi).

## Pilot yang sudah tersedia

- Kelas 7 Semester 1: Bilangan Bulat (B.1, B.2)
- Kelas 8 Semester 1: Teorema Pythagoras (G.4)
- Kelas 9 Semester 1: SPLDV (A.7)
- Kelas 9 Semester 1: Bangun Ruang Sisi Datar (G.5, P.1) — satu file mandiri (`kelas-9/semester-1/bangun-ruang-sisi-datar.html`), bisa dibuka offline tanpa internet; identitas siswa 9A–9D dan ekspor hasil ke .xlsx/.csv sudah tertanam di dalam file.

Materi lain ditandai "Segera" di daftar kelas dan akan ditambahkan
dengan pola halaman yang sama.

## GitHub Pages

Situs statis HTML/CSS/JavaScript, tanpa proses build.
Publikasikan dari branch `main`, folder root.
Alamat yang dituju: https://mariana742.github.io/mpi/
