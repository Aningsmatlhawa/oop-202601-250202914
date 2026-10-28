# Catatan Minggu 02: (Struktur OPP: Class, Object, Encapsulation)


## Yang saya kerjakan
Pada minggu kedua saya mengerjakan class Aset dengan menambahkan kode, nama, status, dan kondisi untuk mengelola dat aset yang akan dipinjam dengan akses private class agar tidak dapat diakses dari luar.

## Keputusan desain
saya menggunakan IlleggalArgumentException untuk mengelola kode atau nama, status, kondisi yang kosong.

## Kendala
Kendala saya munculnya peringatan error di constructor pada bagian "throw new...", penggunaan kode yang sudah benar tetapi VS code masih menunjukkan kesalahan sintaks

## Penggunaan AI
- Alat yang dipakai: (GPT)
- Bagian yang dibantu AI: (Constructor)
- Prompt utama: (1. "Kenapa bagian 'throw new...' masih error padahal kode sudah benar?", 2. "Padahal tidak ada penambahan simbol pada baris tersebut tetapi masih merah")
- Yang saya ubah atau tolak dari saran AI, dan alasannya:
Menyesuaikan kode dengan struktur class yang disarankan karena menjadikan tidak rapi dan VS code akan memunculkan kode error terus menerus.
- Satu hal yang saya pahami lebih baik sekarang:
Yang saya pahami penggunaan simbol tidak boleh terlewat dan diabaikan, karena akan membuat error walaupun hanya spasi atau titik