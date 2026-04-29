# Test Case Website Rental PlayStation

## Keterangan
Aplikasi berbasis Laravel dengan fitur:
- Login
- Penyewaan (multi step)
- Pembayaran
- Pengembalian
- Laporan (owner)

---

## 1. Login Petugas

| ID | TC-01 |
|----|------|
| Deskripsi | Login petugas berhasil |
| Input | Username & password valid |
| Expected | Masuk ke dashboard petugas |

---

## 2. Login Gagal

| ID | TC-02 |
|----|------|
| Deskripsi | Login dengan password salah |
| Input | Username benar, password salah |
| Expected | Muncul pesan error |

---

## 3. Input Data Pelanggan

| ID | TC-03 |
|----|------|
| Deskripsi | Input data pelanggan |
| Input | Nama, alamat, no hp, email |
| Expected | Data tersimpan & lanjut ke pilih unit |

---

## 4. Pilih Unit PlayStation

| ID | TC-04 |
|----|------|
| Deskripsi | Memilih unit PS |
| Input | PS5, qty 1, durasi 2 hari |
| Expected | Total harga tampil |

---

## 5. Pilih Unit Kosong

| ID | TC-05 |
|----|------|
| Deskripsi | Tidak memilih unit |
| Input | Tidak centang unit |
| Expected | Muncul validasi error |

---

## 6. Konfirmasi Penyewaan

| ID | TC-06 |
|----|------|
| Deskripsi | Konfirmasi data penyewaan |
| Input | Klik tombol konfirmasi |
| Expected | Masuk ke halaman pembayaran |

---

## 7. Pembayaran Manual Berhasil

| ID | TC-07 |
|----|------|
| Deskripsi | Pembayaran sesuai nominal |
| Input | Nominal = total |
| Expected | Status lunas & halaman sukses |

---

## 8. Pembayaran Kurang

| ID | TC-08 |
|----|------|
| Deskripsi | Nominal kurang dari total |
| Input | Nominal < total |
| Expected | Muncul error / tidak bisa lanjut |

---

## 9. Pengembalian Unit

| ID | TC-09 |
|----|------|
| Deskripsi | Proses pengembalian |
| Input | Klik "Proses Pengembalian" |
| Expected | Status berubah menjadi Returned |

---

## 10. Laporan Penyewaan (Owner)

| ID | TC-10 |
|----|------|
| Deskripsi | Menampilkan laporan |
| Input | Filter tanggal |
| Expected | Data transaksi tampil sesuai filter |

---

## 11. Update Stok Unit

| ID | TC-11 |
|----|------|
| Deskripsi | Stok berkurang setelah sewa |
| Input | Melakukan penyewaan |
| Expected | Stok unit berkurang |

---

## 12. Akses Dashboard Owner

| ID | TC-12 |
|----|------|
| Deskripsi | Melihat statistik |
| Input | Login sebagai owner |
| Expected | Dashboard statistik tampil |
