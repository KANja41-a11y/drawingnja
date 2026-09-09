# Drawing App

Aplikasi menggambar berbasis web yang siap di-host di **GitHub Pages**.

## Fitur

- **Kuas (Brush)** & **Penghapus (Eraser)**
- **Shape tools**: Garis lurus, Kotak, Lingkaran
- **Color picker** untuk warna kuas
- **Ganti background** canvas
- **Ukuran kuas** (1–60)
- **Opacity / Transparansi** (5%–100%)
- **Tema Dark / Light**
- **Undo** (tombol + Ctrl+Z)
- **Hapus semua**
- **Unduh** sebagai PNG
- Support **mouse + touch** (HP/tablet)

## Cara Deploy ke GitHub Pages

1. Buat repository baru di GitHub (contoh: `drawing-app`)
2. Upload file `index.html` ke repository
3. Masuk ke **Settings → Pages**
4. Source: **Deploy from a branch** → pilih `main` → folder `/ (root)`
5. Tunggu beberapa detik, lalu buka URL yang muncul  
   (contoh: `https://username.github.io/drawing-app`)

## Struktur

```
drawing-app/
├── index.html   ← semua kode ada di sini (single file)
└── README.md
```
