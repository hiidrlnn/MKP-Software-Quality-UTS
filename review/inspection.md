# Inspection

Inspection adalah proses peninjauan software yang dilakukan secara lebih teliti dan terstruktur untuk menemukan kesalahan pada sistem, terutama pada kode program.

Pada aplikasi rental PlayStation, inspection dilakukan dengan mengecek bagian-bagian penting seperti:

- Controller Laravel (AuthController, PaymentController, dll)
- Model (Rental, Unit, Payment)
- Validasi input pada form

Contohnya:
- Memastikan login hanya bisa dilakukan dengan data yang benar
- Memastikan input data pelanggan tidak kosong
- Memastikan perhitungan total pembayaran sesuai

Inspection dilakukan tanpa menjalankan program, fokusnya adalah membaca dan memahami kode untuk menemukan kemungkinan kesalahan.

Tujuannya adalah mengurangi bug sebelum sistem digunakan secara langsung.
