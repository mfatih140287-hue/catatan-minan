# Catatan Minan B 9334 FXU (Offline)

Aplikasi web offline untuk catatan transaksi driver.

## Fitur
- Tambah, edit, hapus transaksi.
- Hitung sisa otomatis (Borongan - UJ).
- Rekap total UJ, borongan, dan sisa.
- Data rekening driver.
- Cetak / simpan PDF dan bagikan ringkasan.
- Cadangkan dan pulihkan data JSON.
- PWA: dapat dipasang di Android dan dipakai offline setelah pertama kali dibuka.

## Penting
- Data disimpan lokal di browser/perangkat masing-masing (localStorage).
- Tidak ada sinkronisasi antar-HP dan tidak ada akun/admin online.
- Jangan hapus data browser sebelum membuat cadangan JSON.
- GitHub Pages hanya meng-host file aplikasi; catatan transaksi tidak dikirim ke GitHub.

## Cara unggah lewat HP Android
1. Buka https://github.com dan masuk akun.
2. Tekan tombol **+** lalu **New repository**.
3. Nama repository: `catatan-minan`, pilih **Public**, lalu **Create repository**.
4. Di halaman repository, pilih **Add file** > **Upload files**.
5. Ekstrak ZIP ini terlebih dahulu, lalu unggah semua isi folder (index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, README.md).
6. Tekan **Commit changes**.
7. Buka **Settings** > **Pages**.
8. Pada **Build and deployment**, pilih **Deploy from a branch**.
9. Pilih branch **main**, folder **/(root)**, lalu **Save**.
10. Tunggu beberapa menit. URL aplikasi akan muncul di bagian Pages, biasanya `https://NAMA-USERNAME.github.io/catatan-minan/`.
11. Buka URL itu di Chrome Android, pilih menu ⋮ > **Tambahkan ke layar utama** atau **Install app**.
12. Buka aplikasi sekali saat online agar file tersimpan untuk penggunaan offline.

## Penggunaan
Masukkan transaksi melalui tab Catatan Transaksi. Gunakan tab Rekening Driver untuk data rekening. Buat cadangan secara berkala melalui tab Cadangkan Data.
