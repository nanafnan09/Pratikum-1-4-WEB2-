# 🚀 Laporan Praktikum Pemrograman Web 2 
CodeIgniter 4 Proyek ini merupakan dokumentasi hasil pengerjaan Praktikum Pemrograman Web 2 di Universitas Pelita Bangsa. 
Fokus utama proyek ini adalah membangun sistem manajemen artikel menggunakan framework CodeIgniter 4 dengan arsitektur MVC (Model-View-Controller).

# 🛠️ Tahapan Pengembangan Web
1. Persiapan dan Konfigurasi Awal (Modul 1) Aktivasi Ekstensi PHP:
- Mengaktifkan ekstensi php-json, php-mysqlnd, php-intl, dan mbstring melalui file php.ini untuk kebutuhan framework .
- Instalasi Framework: Mengunduh CodeIgniter 4 dan mengekstraknya ke direktori htdocs/lab11_ci
- Mode Debugging: Mengubah file env menjadi .env dan mengatur CI_ENVIRONMENT ke mode development untuk mempermudah pelacakan error .
- Routing: Mendefinisikan rute awal pada file app/Config/Routes.php.

2. Implementasi Database dan CRUD (Modul 2)
- Database: Membuat database bernama lab_ci4 dan tabel artikel yang memiliki kolom id, judul, isi, gambar, status, dan slug.
- Model: Membuat ArtikelModel.php yang merepresentasikan tabel artikel di database .
- Controller: Membangun Artikel.php untuk menangani logika pemanggilan data dan tampilan.
- CRUD Dasar: Mengimplementasikan fungsi untuk menampilkan daftar artikel (index), detail artikel (view), tambah data (add), ubah data (edit), dan hapus data (delete).

3. Layouting dan Komponen Modular (Modul 3)
- View Layout: Menggunakan konsep template utama pada file main.php agar bagian navigasi dan footer konsisten di setiap halaman menggunakan renderSection.
- View Cell: Membuat komponen modular Artikel Terkini untuk menampilkan daftar artikel terbaru di sidebar secara otomatis.
- 
