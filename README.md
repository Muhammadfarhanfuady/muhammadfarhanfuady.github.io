# 🚀 Portfolio Website

Website CV & Portofolio pribadi yang **elegan, modern, dan teroptimasi SEO** — siap deploy ke GitHub Pages.

---

## ✨ Fitur

- **Dark mode** elegan dengan efek glassmorphism & animated orbs
- **Fully responsive** — mobile, tablet, desktop
- **SEO lengkap** — meta tags, Open Graph, Twitter Card, JSON-LD structured data
- **Sitemap.xml + robots.txt** untuk Google indexing
- **Zero dependencies** — pure HTML, CSS, JavaScript
- **Animasi halus** dengan IntersectionObserver (scroll-triggered)
- **Performa tinggi** — tidak ada framework berat

---

## 📁 Struktur File

```
portfolio/
├── index.html      ← Halaman utama (edit di sini!)
├── sitemap.xml     ← Untuk Google Search Console
├── robots.txt      ← Panduan crawler
├── favicon.svg     ← Ikon browser
├── cv.pdf          ← ⬅ TAMBAHKAN file CV Anda di sini
└── README.md
```

---

## 🔧 Cara Kustomisasi

Buka `index.html` dan cari komentar `<!-- Edit ... -->` atau ganti:

| Yang perlu diubah | Lokasi di kode |
|---|---|
| Nama Anda | `<title>`, `hero-name`, meta tags |
| Deskripsi profil | `meta name="description"` |
| Foto profil | `hero-avatar` — ganti placeholder dengan `<img>` |
| Statistik (tahun, projek) | Section `hero-stats` |
| Email & sosmed | `contact-links`, `footer-socials` |
| Pengalaman kerja | Section `#experience` timeline items |
| Projek | Section `#projects` cards |
| Pendidikan | Section `#education` cards |
| Skills & persentase bar | `skills-grid` — ubah `--w:0.92` (0–1) |
| URL canonical | `<link rel="canonical">` |
| Username GitHub | Semua URL `username.github.io` |

---

## 🚀 Deploy ke GitHub Pages

### Langkah 1 — Buat Repository
```bash
# Buat repo baru di github.com bernama: username.github.io
# (ganti "username" dengan GitHub username Anda)
```

### Langkah 2 — Upload File
```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/username/username.github.io.git
git push -u origin main
```

### Langkah 3 — Aktifkan GitHub Pages
1. Buka repository di GitHub
2. Settings → Pages
3. Source: `Deploy from a branch`
4. Branch: `main` / `(root)`
5. Save — website aktif dalam 1–3 menit di `https://username.github.io`

### Langkah 4 — Update sitemap & robots.txt
Ganti semua `username.github.io` dengan URL Anda yang sebenarnya.

---

## 🔍 SEO — Daftarkan ke Google

Setelah website aktif:

1. **Google Search Console**: https://search.google.com/search-console
2. Tambahkan properti dengan URL `https://username.github.io`
3. Verifikasi dengan HTML tag (tambahkan ke `<head>` di index.html)
4. Submit sitemap: `https://username.github.io/sitemap.xml`

> Website akan mulai terindeks Google dalam 1–4 minggu.

---

## 💡 Tips Tambahan

- **Custom domain** (opsional): Beli domain `.dev` atau `.id`, arahkan ke GitHub Pages via CNAME
- **Foto profil**: Tambahkan `foto.jpg` dan ganti placeholder di `hero-avatar`
- **CV PDF**: Tambahkan `cv.pdf` agar tombol Download CV berfungsi
- **OG Image**: Buat gambar `og-image.jpg` (1200×630px) untuk preview di WhatsApp/LinkedIn

---

## 📄 Lisensi

Bebas digunakan untuk keperluan pribadi.
