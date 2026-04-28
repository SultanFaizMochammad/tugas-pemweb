# LAPORAN TUGAS — Website Personal

## Identitas
- **Nama**: Sultan Faiz Mochammad  
- **NIM**: L200240278  
- **Prodi**: Teknik Informatika  
- **Mata Kuliah**: Pemrograman Web  

---

## Link Website
🌐 **Live Website**: [https://sultanfaiz.github.io/portfolio](https://sultanfaiz.github.io/portfolio)  
_(Ganti dengan link GitHub Pages / Netlify / Vercel kamu setelah deploy)_

---

## Deskripsi Website

Website personal ini terdiri dari 3 halaman utama dengan desain bertema **editorial brutalist** — terinspirasi dari desain dashboard analitik modern dengan palet warna kuning, hitam, dan merah.

---

## Halaman yang Dibuat

### 01 — Beranda (`index.html`)
Halaman utama yang memperkenalkan diri, menampilkan skill teknis dalam format grid 4 kolom, dan kutipan personal sebagai penutup.

### 02 — Portofolio (`portofolio.html`)
Menampilkan 4 proyek unggulan dalam grid 2 kolom, statistik angka (jumlah proyek, teknologi, jam coding), dan tabel pengalaman/organisasi.

### 03 — Kontak (`kontak.html`)
Halaman kontak dengan 3 channel komunikasi (Email, GitHub, LinkedIn), form kontak interaktif dengan validasi JavaScript, dan status ketersediaan kolaborasi.

---

## Teknologi yang Digunakan

- **HTML5** — Struktur semantik halaman
- **CSS3** — Styling lengkap: Flexbox, CSS Grid, animasi, CSS Variables, responsive design
- **JavaScript** — Validasi form dan interaksi tombol kirim pesan
- **Google Fonts** — Font `Bebas Neue` (display) dan `Space Mono` (body)

---

## Fitur Responsif

Website menggunakan media query `@media (max-width: 768px)` untuk menyesuaikan layout di perangkat mobile:
- Grid multi-kolom berubah menjadi 1 kolom
- Tagline navigasi disembunyikan di layar kecil
- Padding dan ukuran font menyesuaikan viewport

---

## Cara Deploy ke GitHub Pages

```bash
# 1. Inisialisasi repo (jika belum)
git init
git add .
git commit -m "Initial commit: website personal"

# 2. Push ke GitHub
git remote add origin git@github.com:USERNAME/REPO-NAME.git
git push -u origin main

# 3. Aktifkan GitHub Pages
# Settings → Pages → Source: Deploy from branch → main → / (root) → Save
```

Setelah beberapa menit, website akan live di:  
`https://USERNAME.github.io/REPO-NAME`

---

## Referensi

- MDN Web Docs — CSS Grid & Flexbox
- Google Fonts — Bebas Neue, Space Mono
- Desain terinspirasi dari template VELO Analytics (dosen)

---

## Pengalaman / Organisasi

- Anggota FOSTI (Forum Studi Teknologi Informasi) — UMS
- Panitia Lomba FostiFest — Festival Teknologi FOSTI UMS
- Peserta Lomba Catur — Ikatan Mahasiswa Muhammadiyah (IMM)