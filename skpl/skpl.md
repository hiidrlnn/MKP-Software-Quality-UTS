# SKPL - Sistem Informasi Rental PlayStation

## 1. Pendahuluan
Dokumen ini menjelaskan kebutuhan perangkat lunak untuk sistem informasi rental PlayStation. Sistem ini digunakan untuk membantu pengelolaan penyewaan, pengembalian, dan pembayaran secara terstruktur.

---

## 2. Tujuan Sistem
- Membantu proses penyewaan PlayStation
- Mengelola data pelanggan dan unit
- Menyediakan laporan transaksi

---

## 3. Lingkup Sistem
Sistem digunakan oleh:
- Petugas rental → mengelola transaksi
- Pemilik → melihat laporan
- Sistem pembayaran digital → validasi pembayaran

---

## 4. Fitur Utama (Use Case)

- Penyewaan unit PlayStation
- Pengembalian unit
- Pembayaran (tunai & digital)
- Update ketersediaan unit
- Laporan penyewaan

(Sesuai diagram use case di dokumen SKPL kamu)

---

## 5. Kebutuhan Fungsional

- Sistem dapat login user
- Sistem dapat mencatat penyewaan
- Sistem dapat mencatat pengembalian
- Sistem dapat menghitung biaya
- Sistem dapat menampilkan laporan

---

## 6. Kebutuhan Non-Fungsional

- Sistem mudah digunakan
- Respon cepat
- Data aman

---

## 7. Struktur Data (Ringkasan)

Tabel utama:
- user
- petugas
- pemilik
- pelanggan
- unit
- penyewaan
- pengembalian
- pembayaran

(Sesuai database di dokumen SKPL)

---

## 8. Teknologi

- Backend: Laravel (PHP)
- Frontend: HTML, Tailwind CSS
- Database: MySQL
