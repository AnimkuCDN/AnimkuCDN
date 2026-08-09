# ⚡ AnimkuCDN - Anime Thumbnail Scraper & Free GitHub CDN

Sistem scraping thumbnail anime otomatis dari **Animku API (`https://animku-apis.vercel.app/`)**, mengompresi gambar ke format **WebP** super cepat & hemat bandwidth, serta menyediakan CDN gratis menggunakan **Custom Domain (`cdn.animku.my.id`)**, **GitHub Pages**, dan **jsDelivr CDN**.

---

## ⚡ Deploy 1-Klik Pakai Token (Tanpa Login Browser)

Cukup jalankan satu perintah berikut di terminal:

```bash
python deploy.py
```

Script ini akan secara otomatis:
1. Mereset remote repository GitHub dari 0 secara bersih.
2. Mem-push Web Pages UI (`index.html`, `styles.css`, `app.js`) dan GitHub Actions workflow.
3. Menghasilkan metadata JSON catalog.
4. Memicu GitHub Actions Cloud Runner untuk mengunduh semua WebP ke cloud storage repo GitHub Anda!

---

## 🌐 Endpoints & Link CDN:

- **Custom Domain CDN**: `https://cdn.animku.my.id/cdn/thumbnails/{slug}.webp`
- **jsDelivr Edge CDN**: `https://cdn.jsdelivr.net/gh/AnimkuCDN/AnimkuCDN@main/cdn/thumbnails/{slug}.webp`
- **JSON Catalog API**: `https://cdn.animku.my.id/cdn/data/anime_catalog.json`
- **JSON Genres List API**: `https://cdn.animku.my.id/cdn/data/genres_list.json`
