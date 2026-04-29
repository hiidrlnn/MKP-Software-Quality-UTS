# Aplikasi Website Rental PlayStation

## Deskripsi
Aplikasi ini adalah sistem informasi rental PlayStation berbasis web yang digunakan untuk mengelola penyewaan, pengembalian, dan pembayaran.

---

## Teknologi
- Framework: Laravel
- Frontend: Tailwind CSS
- Database: MySQL

---

## Fitur Utama

### 1. Login
User dapat login ke sistem menggunakan username dan password.

File terkait:
- app/Http/Controllers/AuthController.php
- resources/views/login.blade.php

---

### 2. Booking / Penyewaan
User dapat melakukan penyewaan PlayStation.

File terkait:
- app/Http/Controllers/BookingController.php
- resources/views/booking.blade.php

---

### 3. Pengembalian
Petugas dapat mencatat pengembalian unit.

File terkait:
- app/Http/Controllers/PengembalianController.php

---

### 4. Pembayaran
Sistem mencatat pembayaran (tunai/digital).

File terkait:
- app/Http/Controllers/PembayaranController.php

---

## Routing
Routing utama terdapat pada:
- routes/web.php

---

## Catatan
Folder seperti vendor dan node_modules tidak disertakan karena ukuran besar dan tidak diperlukan untuk penilaian.
