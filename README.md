# Kartu Pos Kenangan

Halaman web statis. Tidak perlu server, cukup GitHub Pages.

## Isi folder

- `index.html`: seluruh halaman (teks kenangan, surat, permainan, efek).
- `fotos/data.js`: daftar foto tiap kenangan.
- `fotos/`: tempat file foto (JPG, PNG, atau WebP).

## Unggah ke GitHub

1. Buka github.com, buat repository baru. Pilih **Public**, beri nama yang tidak mudah ditebak (mis. `kenangan-x7q`).
2. Di halaman repository, pilih **Add file → Upload files**, lalu unggah `index.html`. Tekan **Commit changes**.
3. Buat folder foto: **Add file → Create new file**, ketik nama `fotos/data.js`, tempel isi file `data.js`, lalu **Commit changes**.
4. Buka **Settings → Pages**. Di bagian Source pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
5. Tunggu satu sampai dua menit. Alamatnya: `https://NAMAKAMU.github.io/NAMA-REPO/`

## Menambah foto

1. Buka folder `fotos` di repository, pilih **Add file → Upload files**, lalu unggah foto-fotonya.
2. Buka `fotos/data.js`, tekan ikon pensil, tulis nama file di kenangan yang sesuai, lalu **Commit changes**.

Contoh:

```js
k1: ["fotos/k1-pertama.jpg", "fotos/k1-kedua.jpg"],
```

Kecilkan foto dulu sampai sekitar 1600 piksel di sisi terpanjang supaya halaman cepat dibuka.

## Mengganti teks

Semua teks ada di bagian `CONFIG` di dalam `index.html` (dekat bagian atas skrip): nama, tanggal jadian, judul dan cerita tiap kenangan, isi surat, pertanyaan kuis, dan kupon hadiah. Edit lewat ikon pensil di GitHub, lalu **Commit changes**.

## Catatan privasi

Situs GitHub Pages bisa dibuka siapa saja yang punya alamatnya. Jangan taruh data yang sangat pribadi, dan bagikan alamatnya hanya ke orang yang dituju.
