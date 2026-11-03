# Website JP Teknologi Integrasi

Website company profile **JP Teknologi Integrasi** — Smart Building Solutions (www.jpteknologi.com).

Halaman statis satu file (`index.html`) tanpa build step: HTML + CSS + JavaScript.

## Struktur
- `index.html` — seluruh halaman (Beranda, Tentang, Layanan, Solusi, Keunggulan, Sektor, Proses, Kontak)
- `assets/` — gambar website (`hero.webp`, `tentang.webp`, `solusi.webp`, `og.jpg`), dibuat oleh workflow **Ambil & kompres gambar** (tab Actions)
- `favicon.svg`, `robots.txt`, `sitemap.xml`, `404.html`, `CNAME`

## Menjalankan
Buka `index.html` langsung di browser, atau sajikan dengan server statis apa pun (cPanel, Netlify, GitHub Pages).

## Kontak & WhatsApp
Nomor WhatsApp diatur di konstanta `WA` di bagian `<script>` pada `index.html`. Form "Kirim Pesan" membuka WhatsApp dengan isi pesan terisi otomatis.
