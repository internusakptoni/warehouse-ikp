# warehouse.ikp — Internusa IKP

Starter antarmuka responsif untuk rancangan sistem gudang Internusa IKP.

**Penting:** ini hanya pratinjau antarmuka. Angka dan transaksi adalah data contoh. Belum ada autentikasi sungguhan, database, atau penyimpanan transaksi. Jangan gunakan untuk operasional dan jangan masukkan stok asli dulu.

## File
- `index.html`: struktur halaman
- `styles.css`: desain navy-putih responsif
- `app.js`: navigasi prototipe

## Deploy gratis di Cloudflare Pages
1. Upload ketiga file website (`index.html`, `styles.css`, `app.js`) ke root repository GitHub.
2. Di Cloudflare dashboard, buka **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
3. Pilih repository `warehouse-ikp`.
4. Pilih preset **None**, kosongkan build command, dan gunakan root `/` sebagai build output directory jika diminta.
5. Deploy. Cloudflare akan memberi alamat `*.pages.dev` jika nama proyek tersedia.

Jika Cloudflare meminta verifikasi email, selesaikan verifikasi sebelum deployment. Jangan masukkan secret key atau password ke repository.

## Tahap berikutnya
Hubungkan Supabase untuk autentikasi, akses per lokasi, master item, stok, transaksi masuk/keluar/transfer, persetujuan admin, dan audit log.
