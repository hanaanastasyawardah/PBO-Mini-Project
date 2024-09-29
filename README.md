# PBO Mini Project 1
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

* Admin
