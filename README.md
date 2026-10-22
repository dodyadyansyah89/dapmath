# DapMath

Kumpulan aplikasi web interaktif matematika untuk siswa SMP kelas 7, 8, dan 9.
Live di: https://dodyadyansyah89.github.io/dapmath/

**Dibangun oleh Dody Adyansyah**

## Struktur repo

| Folder | Aplikasi |
|---|---|
| `/` | Portal DapMath (halaman depan, `index.html`) |
| `/pythagoras/` | Teorema Pythagoras (kelas 8) |
| `/pola-bilangan/` | Pola Bilangan (kelas 8) |
| `/koordinat-kartesius/` | Koordinat Kartesius (kelas 8) |
| `/relasi-fungsi/` | Relasi dan Fungsi (kelas 8) |
| `/persamaan-garis-lurus/` | Persamaan Garis Lurus (kelas 8) |
| `/spldv/` | SPLDV (kelas 8) |
| `/lingkaran/` | Lingkaran (kelas 8) |
| `/bangun-ruang-sisi-datar/` | Bangun Ruang Sisi Datar (kelas 8) |
| `/statistika-8/` | Statistika dan Peluang (kelas 8) |

Tiap folder berisi satu file `index.html` (aplikasi mandiri).

## Cara menambah aplikasi baru

1. Buat folder baru, mis. `/materi-baru/`.
2. Letakkan file aplikasi sebagai `index.html` di dalam folder tersebut.
3. Tambahkan kartu + tautan absolut (`https://dodyadyansyah89.github.io/dapmath/<folder>/`)
   di portal (`index.html` di root).
4. Commit & push — GitHub Pages menerbitkan otomatis ±1 menit.

## Database

Seluruh aplikasi mencatat login siswa dan nilai kuis ke satu Google Sheet
terpusat melalui Google Apps Script (URL Web App tertanam di tiap aplikasi,
menu Data Guru tiap aplikasi terkunci PIN guru).
