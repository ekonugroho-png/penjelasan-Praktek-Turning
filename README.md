# PERBAIKAN LOGO & FOTO INSTRUKTUR - WEBSITE TURNING ATMI

Versi ini mengikuti file yang terlihat pada screenshot repository `ekonugroho-png/penjelasan-Praktek-Turning`.

## 1. Struktur GitHub yang sesuai dengan HTML baru

```text
penjelasan-Praktek-Turning/
├── index.html
└── assets/
    └── img/
        ├── logo-atmi.jpg
        ├── agustinus-dewandana.jpg
        ├── andhy-rinanto.jpg
        ├── section_lw/  (untuk gambar materi Section Turning)
        ├── alat_ukur/   (untuk gambar materi alat ukur)
        └── ulir/       (untuk gambar materi ulir)
```

Ketiga file logo/foto **tidak** perlu dipindahkan karena HTML terbaru sudah memakai path yang tampak pada screenshot GitHub.

## 2. Cara memperbaiki yang tidak tampil

1. Unduh `index.html` dari paket ini.
2. Masuk ke repository GitHub → buka `index.html` lama di root.
3. Ganti isi file lama dengan isi dari `index.html` terbaru, lalu **Commit changes**. Alternatif: hapus `index.html` lama, lalu upload `index.html` terbaru dengan nama yang sama.
4. Buka alamat GitHub Pages website Anda setelah deployment selesai. Gunakan `Ctrl+F5` atau buka tab privat bila gambar lama masih muncul.
5. Jika tetap tidak tampil, buka tiga URL uji di bawah. Bila salah satunya 404, periksa nama file atau pastikan GitHub Pages memakai branch/folder yang benar.

## 3. Alamat gambar untuk pengujian langsung

- https://ekonugroho-png.github.io/penjelasan-Praktek-Turning/assets/img/logo-atmi.jpg
- https://ekonugroho-png.github.io/penjelasan-Praktek-Turning/assets/img/agustinus-dewandana.jpg
- https://ekonugroho-png.github.io/penjelasan-Praktek-Turning/assets/img/andhy-rinanto.jpg

URL tersebut merupakan **pola alamat yang diharapkan** jika GitHub Pages Anda dipublikasikan sebagai situs proyek dari repository dengan nama itu. URL belum diverifikasi secara online.

## 4. Mengganti foto berikutnya

Di GitHub, buka `assets/img`, lalu ganti `logo-atmi.jpg`, `agustinus-dewandana.jpg`, atau `andhy-rinanto.jpg` dengan berkas baru **bernama sama**. Commit perubahan.

Jika Anda mengganti tipe gambar (misalnya JPEG menjadi PNG), sesuaikan ekstensi dalam atribut `src` pada `index.html` juga, atau pertahankan format JPG.

## 5. Gambar materi lain

HTML tidak mengubah path gambar materi lain. File materi tetap harus ada di subfolder `assets/img/section_lw`, `assets/img/alat_ukur`, dan `assets/img/ulir` sesuai `DAFTAR_GAMBAR_TURNING_GITHUB_SESUAI_REPO.csv`. Folder `.gitkeep` saja tidak menampilkan gambar.

Animasi bubut 3D, navigasi, CSS, dan fungsi website lain tidak diubah.
