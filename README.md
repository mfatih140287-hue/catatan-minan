# Catatan Minan (Offline)

Aplikasi web offline untuk catatan transaksi driver. Plat nomor mobil bisa diganti oleh masing-masing driver, dan laporan dibagikan ke WhatsApp sebagai gambar.

## Fitur
- Tambah, edit, hapus transaksi (Tanggal, Driver, Plat, Dari, Ke, UJ, Borongan).
- Sisa dihitung otomatis (Borongan - UJ) dan ada rekap total.
- **Plat nomor per driver**: isi di menu Pengaturan, tampil di judul aplikasi dan di gambar laporan. Bisa juga diubah per transaksi.
- **Bagikan sebagai gambar (PNG)**: pratinjau dulu, lalu kirim ke WhatsApp lewat menu berbagi HP. Jika transaksi banyak, otomatis dibagi beberapa gambar (25 baris per gambar).
- Data rekening driver, ikut tampil di gambar yang dibagikan (bisa dimatikan lewat kotak centang di pratinjau).
- Tombol periode cepat: Minggu Ini, Minggu Lalu, Semua.
- Gambar laporan bisa menyertakan tabel sisa: minggu kemarin, minggu ini, dan total semua sisa (hanya angka Sisa; kotak centang di pratinjau, muncul saat periode dipilih).
- Menu Pengurangan Sisa: catat pengurangan (tanggal, keterangan, jumlah) yang mengurangi total semua sisa; hasilnya tampil sebagai SISA AKHIR di gambar laporan.
- Cetak / simpan PDF.
- Cadangkan dan pulihkan data JSON.
- PWA: bisa dipasang di Android dan dipakai offline.

## Penting
- Data disimpan lokal di HP masing-masing (localStorage), tidak ada sinkronisasi antar-HP.
- Jangan hapus data browser sebelum membuat cadangan JSON.
- Jika sebelumnya memakai versi lama di alamat yang sama, data lama tetap terbaca; plat transaksi lama diisi otomatis.

## Cara unggah lewat HP Android
1. Buka https://github.com dan masuk akun.
2. Tekan **+** > **New repository**, nama `catatan-minan`, **Public**, **Create repository**.
3. **Add file** > **Upload files**, unggah semua isi folder ZIP ini (ekstrak dulu), lalu **Commit changes**.
4. **Settings** > **Pages** > **Deploy from a branch** > branch **main**, folder **/(root)** > **Save**.
5. Buka URL `https://NAMA-USERNAME.github.io/catatan-minan/` di Chrome Android, lalu ⋮ > **Tambahkan ke layar utama**.
6. Buka sekali saat online agar tersimpan untuk penggunaan offline.
7. Masuk ke menu **Pengaturan** dan isi plat nomor mobil Anda.
