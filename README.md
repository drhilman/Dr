# Website Dr. Hilman Mauludin

Struktur ini sudah disiapkan khusus untuk Cloudflare Workers Static Assets.

## Struktur
- `public/index.html` — halaman utama
- `public/styles.css` — tampilan website
- `wrangler.jsonc` — konfigurasi Cloudflare, assets diarahkan ke `./public`
- `package.json` — Wrangler sebagai devDependency
- `.gitignore` — mencegah `node_modules` dan file lokal ikut ter-deploy

## Cloudflare
Di Cloudflare Workers & Pages:
- Repository: `HilmanMauludin/hilman-mauludin`
- Root directory: `/`
- Build command: kosong
- Deploy command: `npx wrangler deploy`

Penting: jangan mengubah `assets.directory` menjadi `.`. Gunakan `./public`.
Jangan mengunggah `node_modules` ke GitHub.

## GitHub
Upload seluruh isi folder ini ke repository `HilmanMauludin/hilman-mauludin` dan replace file lama jika diminta.
