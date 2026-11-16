# REZALDI — 3D Portfolio

Website portfolio statis, responsif, dengan animasi CSS dan JavaScript.

## Menjalankan di laptop
1. Ekstrak ZIP.
2. Buka folder di VS Code.
3. Buka `index.html` di browser (atau gunakan ekstensi Live Server).

## Deploy ke GitHub Pages
1. Buat repository GitHub baru.
2. Upload `index.html`, `style.css`, dan `script.js` ke root repository.
3. Buka Settings → Pages.
4. Pada Build and deployment pilih Deploy from a branch.
5. Pilih branch `main` dan folder `/ (root)`, lalu Save.

## Deploy ke Cloudflare Pages
1. Masuk Cloudflare Dashboard → Workers & Pages → Create.
2. Pilih Pages → Connect to Git.
3. Pilih repository GitHub ini.
4. Framework preset: None; Build command kosong; Build output directory `/`.
5. Deploy.

## Personalisasi
- Ganti email `hello@example.com` di `index.html`.
- Edit deskripsi, proyek, dan daftar skill di `index.html`.
- Ubah warna utama di bagian `:root` pada `style.css`.
