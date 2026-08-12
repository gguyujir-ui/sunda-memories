# Gugus Sunda — Class Memorial

Website kenangan kelas Gugus Sunda. Terdiri dari `index.html` + folder `images/` berisi foto-foto kelas.

## 📁 Struktur folder (harus persis sama di GitHub)

```
index.html
images/
  foto1.jpg
  foto2.jpg
  foto3.jpg
  foto4.jpg
  foto5.jpg
  foto6.jpg
  foto7.jpg
```

## 🌐 Cara publish ke GitHub Pages

1. Buat repository baru di GitHub (bisa public atau private)
2. Upload `index.html` ke root repo
3. Buat folder `images/` lalu upload ketujuh foto ke dalamnya (lewat **Add file → Upload files**, atau ketik `images/nama-file.jpg` saat upload biar otomatis masuk folder)
4. Buka **Settings → Pages**
5. Di bagian **Source**, pilih branch `main` dan folder `/ (root)`, lalu **Save**
6. Tunggu 1–2 menit, link web-nya akan muncul di bagian atas halaman Pages, formatnya:
   ```
   https://<username-github-kamu>.github.io/<nama-repo>/
   ```

## ✏️ Cara edit isi web

Buka `index.html` dengan text editor apa saja, cari komentar `EDIT DATA DI SINI` di dalam tag `<script>`. Di situ ada beberapa data yang bisa diubah:

- `strukturKelas` — wali kelas & petinggi kelas (nama, jabatan, foto)
- `students` — daftar nama untuk halaman Name (nama + quote)
- `memoryPhotos` — foto-foto di halaman Home & Memories
- `sosmed` — link media sosial kelas

Untuk foto baru, paling gampang pakai link dari internet (upload dulu ke Imgur/Google Drive/dsb), tempel di bagian `src`.

## 📁 Struktur

Cuma ada 1 file: `index.html`. Semua CSS, JavaScript, dan foto (base64) sudah menyatu di dalamnya.
