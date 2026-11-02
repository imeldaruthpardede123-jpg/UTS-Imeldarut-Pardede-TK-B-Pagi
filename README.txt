Imelda Store
Tema Alat Tulis Kantor segar hijau, putih, dan biru.

# Paket 3 Aplikasi Kasir Web

Paket ini berisi tiga aplikasi kasir web dengan tema berbeda:
2. Imelda Store — hijau segar untuk Alat Tulis Kantor


## Cara menjalankan di XAMPP (Windows)	
2. Salin folder , `Imelda-Store` ke `C:\xampp\htdocs\`.
3. Buka XAMPP Control Panel, klik **Start** pada Apache dan MySQL.
4. Buka salah satu alamat berikut:
   - http://localhost/kasir-mart/
  5. Database `kasir_web_suite` dan tabel-tabelnya dibuat otomatis saat pertama kali dibuka. Akun demo juga dibuat otomatis.

## Login
- Username: `admin`
- Password: `admin123`

## Fitur
- Login admin
- Dashboard statistik
- CRUD produk dan kategori
- Pencarian produk
- Transaksi dengan beberapa produk
- Validasi pembayaran dan kembalian
- Pengurangan stok otomatis dalam transaksi database
- Riwayat transaksi dan cetak struk
- Laporan omzet bulanan
- Peringatan stok menipis
- Layout responsif untuk desktop dan layar HP

## Catatan
- Ketiga aplikasi memakai database MySQL yang sama (`kasir_web_suite`), sehingga data produk dan transaksi akan terlihat sama di ketiganya. Tema dan nama aplikasinya berbeda.
- Jika ingin data tiap aplikasi benar-benar terpisah, ubah `DB_NAME` pada `config.php` menjadi nama database yang berbeda untuk setiap folder.
- Untuk penggunaan nyata, ganti password demo, gunakan HTTPS, dan tambahkan pengelolaan pengguna/otorisasi sebelum dipublikasikan ke internet.
- Google Fonts membutuhkan koneksi internet untuk font tambahan; aplikasi tetap berjalan tanpa koneksi, menggunakan font fallback.
