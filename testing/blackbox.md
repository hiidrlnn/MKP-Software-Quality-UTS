# Black Box Testing

## Definisi
Black Box Testing adalah metode pengujian yang dilakukan tanpa melihat kode program. Pengujian hanya fokus pada input yang diberikan dan output yang dihasilkan oleh sistem.

## Penerapan pada Aplikasi Rental PS
Pengujian dilakukan berdasarkan tampilan (UI) dan fitur yang digunakan oleh user.

Fitur yang diuji:
- Login petugas
- Penyewaan (input data pelanggan, pilih unit)
- Pembayaran
- Pengembalian
- Laporan

## Contoh Pengujian

1. Login
Input: username & password benar  
Output: masuk ke dashboard

2. Pilih Unit
Input: pilih PS5, durasi 2 hari  
Output: total harga tampil

3. Pembayaran
Input: nominal sesuai  
Output: status menjadi berhasil

4. Pengembalian
Input: klik proses pengembalian  
Output: status berubah menjadi returned
