# Praktikum 6
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

Hasil:
Program akan menampilkan output sesuai dengan instruksi yang saya berikan.
```

## Tugas Praktikum
```Buat program sederhana yang akan menampilkan daftar nilai mahasiswa, dengan ketentuan
Program dibuat dengan menggunakan Dictionary

• Tampilkan menu pilihan: (Tambah Data, Ubah Data, Hapus Data, Tampilkan Data, Cari Data)
• Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%, uts: 35%, uas: 35%)

Buat flowchart dan penjelasan programnya pada README.md.
Commit dan push repository ke github.
```

## Profgramnya
![WhatsApp Image 2024-11-26 at 00 57 52_5baff2e5](https://github.com/user-attachments/assets/0c805be0-d7a3-4862-a6a6-05a01eae9752)

![WhatsApp Image 2024-11-26 at 01 06 56_73e61270](https://github.com/user-attachments/assets/1773fa3a-3167-4e24-ae8d-9f3827e0f22c)

```Penjelasan:
1. Dictionary mahasiswa: Digunakan untuk menyimpan data seluruh mahasiswa. Setiap mahasiswa direpresentasikan sebagai sebuah key (NIM) dengan nilai berupa dictionary yang berisi nilai tugas, UTS, UAS, dan nilai akhir.
2. Fungsi:
tambah_data(): Menambahkan data mahasiswa baru ke dalam dictionary.
ubah_data(): Mengubah data mahasiswa yang sudah ada.
hapus_data(): Menghapus data mahasiswa dari dictionary.
tampilkan_data(): Menampilkan semua data mahasiswa yang sudah tersimpan.
cari_data(): Mencari data mahasiswa berdasarkan NIM.
3. Perulangan while True: Membuat program terus berjalan hingga pengguna memilih untuk keluar.
```

## Berikut Flowchartnya
![WhatsApp Image 2024-11-26 at 01 45 27_ff6e9976](https://github.com/user-attachments/assets/7da4b89f-713e-4f34-ae85-d01beb1bf411)

## © Rhendy Zhaky Alvian
email: rhendyzhakyalvian@gmail.com
