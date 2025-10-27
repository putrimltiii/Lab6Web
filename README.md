# Lab6Web
## PRAKTIKUM 6 Web Framework
# Nama: Putri Melati Ramadhaniati
# NIM: 31241014
# Kelas: TI.24.A1

# Tujuan
1. Mahasiswa mampu memahami konsep dasar dari web framework.
2. Mahasiswa mampu memahami struktur dasar layout web menggunakan css framework.
3. Mahasiswa mampu memahami elemen-elemen css framewordk
   
# Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode.
2. Buat folder baru dengan nama lab6_css_framework
3. Buat file baru dokumen html
4. Buat struktur dasar dari dokumen HTML.
5. Buatlah layout web sederhana menggunakan css frameword (Twitter Bootsrtap).
6. Lakukan validasi dokumen html dengan mengakses http://validator.w3.org
Berdasarkan gambar layout web berikut, buatlah menggunakan Twitter Bootstrap.

# Membuat File Proyek
Pada tahap ini dibuat folder baru bernama lab6_css_framework yang berfungsi sebagai tempat penyimpanan seluruh file proyek.
Di dalamnya dibuat file utama index.html yang akan berisi struktur HTML dari halaman web.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f3821c40-f3da-4170-b4cd-628af1649fa5" />

# Membuat Struktur Dasar HTML
Langkah pertama adalah membuat file baru bernama index.html. Di dalamnya dituliskan struktur dasar HTML5 yang diawali dengan <!DOCTYPE html>, lalu diikuti elemen <html>, <head>, dan <body>.
Pada bagian <head>, ditambahkan judul halaman menggunakan tag <title>Melati Store</title> dan pengaturan tampilan agar responsif melalui meta tag viewport.

# Menghubungkan CSS Framework Bootstrap
Pada bagian <head>, ditambahkan link CDN Bootstrap versi 5 menggunakan tag <link>. Framework ini digunakan agar tampilan halaman menjadi lebih rapi dan modern tanpa perlu menulis banyak CSS secara manual. Selain itu juga ditambahkan Bootstrap Icons agar dapat menampilkan ikon-ikon seperti toko, truk, kunci, dan hadiah.

# Membuat Navigasi (Navbar)
Bagian paling atas halaman adalah navigasi atau navbar. Elemen ini dibuat menggunakan komponen navbar dari Bootstrap dengan kelas navbar-dark bg-dark agar berwarna hitam.
Navbar berisi logo toko TokoKu di sebelah kiri dan menu navigasi di sebelah kanan, yaitu: Beranda, Produk, Tentang, dan Kontak.

# Membuat Header / Bagian Sambutan
Setelah navbar, ditambahkan bagian sambutan menggunakan elemen <header> dengan teks tengah.
Di sini terdapat judul besar "Selamat Datang di Melati Store" dan teks deskripsi di bawahnya. Warna teks “Melati Store” diubah menjadi hitam agar lebih serasi dengan tema keseluruhan.

# Membuat Bagian Konten Utama
1. Di bagian utama (<main>), halaman dibagi menjadi dua kolom menggunakan sistem grid Bootstrap (.row dan .col-md-*).
2. Kolom kiri (8 bagian) berisi tiga fitur utama toko:
3. Pengiriman Cepat dengan ikon truk.
4. Pembayaran Aman dengan ikon perisai kunci.
5. Promo Menarik dengan ikon hadiah. 
7. Setiap bagian menggunakan kombinasi ikon, judul, dan deskripsi singkat.
8. Kolom kanan (4 bagian) berisi daftar kategori produk dalam bentuk kartu (card) Bootstrap dengan bayangan halus (shadow). Kategori yang ditampilkan adalah Elektronik, Fashion, dan Makanan.

# Membuat Footer
Di bagian bawah halaman ditambahkan elemen <footer> dengan latar belakang hitam (bg-dark) dan teks putih (text-white).
Footer berisi keterangan © 2025 Melati Store serta catatan bahwa halaman dibuat menggunakan Bootstrap 5.

# Menambahkan Script Bootstrap
Di bagian akhir sebelum </body>, disertakan link JavaScript Bootstrap (bootstrap.bundle.min.js) agar elemen-elemen interaktif seperti navbar toggle dapat berfungsi ketika halaman dibuka di perangkat mobile.
<img width="1920" height="1080" alt="1 melati store" src="https://github.com/user-attachments/assets/995e7b56-9a81-4451-b1f4-88d9e0c5f84e" />

# Melakukan Validasi HTML
Setelah kode selesai, dilakukan pengecekan menggunakan situs W3C Validator
Caranya dengan membuka halaman tersebut, memilih tab “Validate by File Upload”, lalu mengunggah file index.html.
Hasil validasi menunjukkan “Document checking completed. No errors or warnings to show”, artinya file HTML sudah valid dan tidak mengandung kesalahan penulisan kode.
<img width="1920" height="1080" alt="validator" src="https://github.com/user-attachments/assets/b457a151-f338-412d-9d05-23d2470a775b" />

