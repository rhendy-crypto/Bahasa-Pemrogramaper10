# Praktikum 5
## Latihan 1
```Buat Dictionary daftar kontak Nama sebagai key, dan nomor sebagai value
Nama Nomor Telpon
#Ari 081267885
#Dina
087677776
Tampilkan kontaknya Ari
Tambah kontak baru dengan nama Riko, nomor 087654544
Ubah kontak Dina dengan nomor baru 088999776
Tampilkan semua Nama
Tampilkan semua Nomor
Tampilkan daftar Nama dan nomornya
Hapus kontak Dina.
```

## Input
![image](https://github.com/user-attachments/assets/18a716e5-ec08-4878-ae2d-f168078ac936)

## Output
![image](https://github.com/user-attachments/assets/17669fb8-1759-4354-873c-0912c4428821)

## Penjelasan
```1. Membuat Dictionary: Kita membuat sebuah dictionary kosong bernama kontak untuk menyimpan data kontak.
2. Menambahkan Kontak: Kita menambahkan kontak Ari dan Dina dengan nama sebagai key dan nomor sebagai value.
3. Mengakses Kontak: Untuk menampilkan kontak Ari, kita langsung akses dengan menggunakan key "Ari".
4. Menambahkan Kontak Baru: Kita menambahkan kontak baru Riko dengan cara yang sama seperti sebelumnya.
5. Mengubah Nomor: Untuk mengubah nomor Dina, kita cukup mengganti value pada key "Dina".
6. Menampilkan Semua Nama: Kita menggunakan perulangan for untuk mengakses semua key (nama) dalam dictionary.
7. Menampilkan Semua Nomor: Kita menggunakan kontak.values() untuk mendapatkan semua nilai (nomor) dan kemudian melakukan perulangan.
8. Menampilkan Daftar Lengkap: Kita menggunakan kontak.items() untuk mendapatkan pasangan key-value dan kemudian mencetaknya dalam format yang lebih mudah dibaca.
9. Menghapus Kontak: Kita menggunakan del untuk menghapus kontak Dina berdasarkan key-nya.
```
