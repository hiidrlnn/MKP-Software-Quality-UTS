# White Box Testing

## Definisi
White Box Testing adalah metode pengujian yang dilakukan dengan melihat dan memahami struktur kode program. Pengujian ini fokus pada logika, alur program, dan proses internal sistem.

## Penerapan pada Aplikasi Rental PS
Pengujian dilakukan pada bagian backend Laravel, khususnya controller dan model.

Controller yang diuji:
- AuthController → login
- PaymentController → pembayaran
- PetugasController → penyewaan
- OwnerController → laporan

Model yang digunakan:
- User
- Rental
- Unit
- Payment
- Customer

## Tujuan
- Memastikan logika program berjalan dengan benar
- Memastikan proses penyimpanan data sesuai

## Contoh
Jika pembayaran berhasil:
- data masuk ke tabel payment
- status rental berubah menjadi "lunas"
