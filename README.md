# Neon Racer

Game balap canvas (static HTML) — deploy sebagai Static Site di Render.

## Struktur
- `index.html` — game
- `assets/` — opsional: `car.png`, `enemy.png`, `tree.png` (kalau tidak ada, game pakai gambar buatan Canvas)
- `render.yaml` — konfigurasi Render (Blueprint)

## Deploy
1. Push folder ini ke GitHub.
2. Render Dashboard → New → Static Site (atau Blueprint) → pilih repo.
3. Build Command: kosongkan / `echo "no build"`, Publish Directory: `.`
4. Deploy.
