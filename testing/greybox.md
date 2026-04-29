# Grey Box Testing

## Definisi
Grey Box Testing adalah metode pengujian yang merupakan kombinasi antara Black Box dan White Box Testing. Tester mengetahui sebagian struktur sistem, seperti database atau alur sistem, tetapi tidak seluruh kode program.

## Penerapan pada Aplikasi Rental PS
Tester mengetahui:
- struktur database (Rental, Unit, Payment)
- alur penyewaan dari input hingga pembayaran

## Contoh Pengujian

1. Penyewaan
- input data pelanggan
- pilih unit PS5
- sistem menyimpan data ke tabel rental

2. Update Stok
- setelah penyewaan, stok unit berkurang

3. Pembayaran
- data masuk ke tabel payment
- status berubah menjadi lunas
