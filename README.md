# Your Moment ID — QR Memory Page

Halaman kenangan personal yang muncul saat pelanggan scan QR di papan akrilik.

---

## Cara Deploy ke GitHub Pages (Gratis)

### Langkah 1 — Buat repository baru di GitHub
1. Buka [github.com](https://github.com) → login
2. Klik tombol **"New"** (pojok kiri atas)
3. Isi nama repo: `yourmomentid` (atau nama apapun)
4. Pilih **Public**
5. Klik **"Create repository"**

---

### Langkah 2 — Upload file
1. Di halaman repo yang baru dibuat, klik **"uploading an existing file"**
2. Drag & drop ketiga file ini:
   - `index.html`
   - `form.html`
   - `README.md`
3. Klik **"Commit changes"**

---

### Langkah 3 — Aktifkan GitHub Pages
1. Klik tab **Settings** di repo kamu
2. Scroll ke bagian **"Pages"** (di menu kiri)
3. Di bagian **Source**, pilih **"Deploy from a branch"**
4. Branch: pilih **main** → folder: **/ (root)**
5. Klik **Save**
6. Tunggu 1-2 menit, lalu link kamu aktif:
   ```
   https://[username-kamu].github.io/yourmomentid/
   ```

---

## Cara Pakai untuk Setiap Order

### Untuk kamu (owner):
1. Kirim link form ke pelanggan:
   ```
   https://[username-kamu].github.io/yourmomentid/form.html
   ```
2. Pelanggan isi sendiri → otomatis dapat QR
3. Pelanggan screenshot QR → kirim ke kamu
4. Kamu cetak QR di papan akrilik

### Yang dilihat penerima saat scan:
- Nama wisudawan
- Pesan personal
- Foto kenangan
- Tanggal wisuda

---

## Struktur File

```
yourmomentid/
├── index.html   → halaman kenangan (tampil saat QR di-scan)
├── form.html    → form input untuk pelanggan
└── README.md    → panduan ini
```

---

## Catatan Teknis

- Semua data tersimpan langsung di URL (tidak butuh database)
- Gratis selamanya di GitHub Pages
- Bisa diakses dari HP manapun
- QR otomatis dibuat setelah pelanggan isi form

---

*Your Moment ID © 2025*
