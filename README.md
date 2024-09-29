# PBO Mini-Project/Posttest 1
## Nama: Hana Anastasya Wardah
## NIM: 230916012

## Studi Kasus: Sistem Manajemen Penyewaan DVD - CineReel DVD
### Latar Belakang
Perusahaan rental film CineReel DVD yang dikelola oleh Hanabi telah beroperasi selama beberapa tahun dengan cara manual. Pelanggan datang ke toko untuk memilih film dan mengisi formulir penyewaan secara tertulis. Namun, Hanabi ingin memodernisasi sistem penyewaan DVD-nya agar lebih efisien dan dapat mengurangi kesalahan manusia.

Hanabi meminta tim pengembang untuk membuat Sistem Manajemen Penyewaan DVD yang dapat digunakan oleh dua jenis pengguna:

* Admin (pengelola toko): Memiliki kendali penuh untuk menambah, memperbarui, atau menghapus film dari sistem.
* Customer (pelanggan): Dapat melihat daftar film yang tersedia, menyewa film, dan mengembalikan film.

### Tujuan Sistem
* Admin: Memudahkan Hanabi dalam mengelola katalog film yang tersedia di toko. Admin dapat menambah film baru, memperbarui informasi film, atau menghapus film yang tidak tersedia.
* Customer: Mempermudah pelanggan, seperti Abe, dalam memilih, menyewa, dan mengembalikan film.
Skenario Penggunaan
* Login sebagai Admin:

Hanabi, sebagai admin, login ke dalam sistem dengan username admin dan password admin123. Setelah berhasil login, ia dapat:

1. Menambah film baru,
2. Memperbarui informasi film yang ada,
3. Menghapus film yang tidak tersedia,
4. Menampilkan daftar semua film.
Hanabi menambahkan film baru seperti "Inception" (genre: Sci-Fi) dan "The Dark Knight" (genre: Action) ke dalam katalog.

Kemudian, Hanabi mengubah genre film "Film A" dari "Action" menjadi "Thriller" karena ada kesalahan pada data awal.

Ia juga menghapus film yang sudah rusak dari katalog.

* Login sebagai Customer:

Abe, seorang pelanggan reguler, login ke sistem menggunakan username customer dan password cust123.

Setelah login, Abe dapat melihat daftar film yang tersedia di CineReel DVD, seperti "Inception", "The Dark Knight", "Film B", dan "Film C".

Abe memutuskan untuk menyewa film "Inception". Ia memasukkan indeks film "Inception", dan sistem mencatat bahwa film tersebut disewa oleh Abe. Film tersebut kemudian tidak tersedia untuk pelanggan lain hingga dikembalikan.

Setelah beberapa hari, Abe kembali dan mengembalikan film "Inception" melalui sistem. Film tersebut kini tersedia kembali untuk pelanggan lain.

## Validasi dan Keamanan:
Sistem memverifikasi username dan password sebelum pengguna bisa mengakses fitur.
Hanabi sebagai admin tidak bisa menyewa film, karena fitur ini hanya tersedia bagi pelanggan seperti Abe.
Film yang disewa tidak bisa disewa oleh pelanggan lain hingga film tersebut dikembalikan.
Fitur Utama Sistem
* Admin:

1. Menambah film baru ke katalog.
2. Menghapus film yang tidak tersedia.
3. Mengupdate informasi film.
4. Melihat daftar film yang tersedia.
* Customer:

1. Melihat daftar film yang bisa disewa.
2. Menyewa film dengan memilih indeks film.
3. Mengembalikan film yang telah disewa.

## Masalah yang Diatasi Sistem:
Efisiensi Pengelolaan: Sebelumnya, Hanabi harus mencatat film secara manual dan sering kali mengalami kesulitan dalam melacak ketersediaan film. Dengan sistem ini, film yang disewa atau dikembalikan langsung tercatat secara otomatis.
Kemudahan Pelanggan: Abe dan pelanggan lain dapat memilih dan menyewa film dengan lebih cepat dan tanpa harus mengantri lama.
Minim Kesalahan: Sistem meminimalisasi kesalahan manusia, seperti film disewa dua kali atau data film tidak diperbarui.

## Kesimpulan
Sistem Manajemen Penyewaan DVD yang diterapkan di CineReel DVD mempermudah Hanabi dalam mengelola bisnis penyewaannya. Pelanggan seperti Abe dapat menyewa dan mengembalikan film dengan lebih mudah, sementara Hanabi memiliki kontrol penuh atas film yang tersedia di katalog.

### Cara Penggunaan 
Pada awal program akan ditampilkan menu untuk user pilih, yaitu Login Admin/Customer

<img width="112" alt="Screenshot 2024-09-29 203022" src="https://github.com/user-attachments/assets/62719d60-245a-4b2d-b58f-7fdadf0d1500">

* jika user memilih Admin maka akan diminta memasukkan username dan password admin

<img width="117" alt="Screenshot 2024-09-29 203036" src="https://github.com/user-attachments/assets/84df37d6-f3a0-4927-90b1-6ddbd04050b7">

setelah itu masuk ke menu Admin

<img width="214" alt="Screenshot 2024-09-29 203044" src="https://github.com/user-attachments/assets/018991b4-58e5-454c-af6b-50f2f7ec2fa3">

Opsi 1 Admin:
Diminta menginput nama dan genre film baru.

<img width="150" alt="Screenshot 2024-09-29 203105" src="https://github.com/user-attachments/assets/14881431-b042-4190-b56a-56fb1e5ae3ab">

Opsi 2 Admin:
Menampilkan semua daftar film yang ada.

<img width="103" alt="Screenshot 2024-09-29 203116" src="https://github.com/user-attachments/assets/9ed8849b-855d-4b90-a4d8-7e99a48639e4">

Opsi 3 Admin:
Diminta menginput indeks/nomor film, judul baru, dan genre baru.

<img width="211" alt="Screenshot 2024-09-29 203428" src="https://github.com/user-attachments/assets/0f4c5572-9c36-4a15-81e8-ece50fed4156">

Opsi 4 Admin:
Diminta untuk menginput indeks/nomor film yang ingin di hapus

<img width="205" alt="Screenshot 2024-09-29 203440" src="https://github.com/user-attachments/assets/daf829c4-faab-4e8b-9e4e-8e6c36545bd9">

Opsi 5 Admin:
Keluar dari program.

<img width="187" alt="Screenshot 2024-09-29 203457" src="https://github.com/user-attachments/assets/825450b1-daea-450f-a4d9-4882ba4b405f">

* Login Customer maka akan diminta untuk memasukkan/input username dan password customer
  jika berhasil maka, akan masuk ke menu utama customer
  
<img width="243" alt="Screenshot 2024-09-29 203742" src="https://github.com/user-attachments/assets/b97fa5cb-b11e-4649-8348-c311f837df86">

Opsi 1 Customer:
Menampilkan daftar semua film yang tersedia.

<img width="159" alt="Screenshot 2024-09-29 204108" src="https://github.com/user-attachments/assets/3425fa2d-9a63-45c4-a03d-2b4e07b060f5">

Opsi 2 Customer:
Diminta untuk menginput indeks/nomor film yang ingin disewa.

<img width="193" alt="Screenshot 2024-09-29 204128" src="https://github.com/user-attachments/assets/21f54d2c-f69a-43a5-a338-4a9968c6aac3">

Opsi 3 Customer:
Diminta untuk menginput indeks/nomor film yang ingin dikembalikan.

<img width="224" alt="Screenshot 2024-09-29 204140" src="https://github.com/user-attachments/assets/c0a40d42-76e8-40f5-928a-339d21ff0364">

Opsi 4 Customer:
Keluar dari program.

<img width="176" alt="Screenshot 2024-09-29 204152" src="https://github.com/user-attachments/assets/2163de64-7076-40ec-b385-2dd8701b2cde">

Program Selesei.
