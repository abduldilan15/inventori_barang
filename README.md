# inventori_barang
Aplikasi Inventori Barang dengan Java Berbasis Desktop.

# Versi
Versi yang saya gunakan untuk membuat aplikasi ini adalah:

- IDE Apache NetBeans 12.1
- Java 11
- MySQL 8.0.21

# Konfigurasi
Untuk menggunakan aplikasi ini, silahkan setting databasenya terlebih dahulu. Buka project di Apache NetBeans - **inventori_barang** > **Source Packages** > **inventori_barang**
kemudian ubah file **koneksi.java** dan sesuaikan dengan yang Anda gunakan, seperti berikut ini:

- connURL = URL koneksi yang terhubung ke database, contoh jika nama databasenya inventori maka URLnya menjadi "jdbc:mysql://localhost:3306/inventori?autoReconnect=true&useSSL=false"
                    + "&useUnicode=true&useJDBCCompliantTimezoneShift=true&useLegacyDatetimeCode=false&serverTimezone=UTC"
- user = nama user di database
- password = password untuk user di database

Default username dan password yang digunakan untuk login : 
- Username : **rinaldi**
- Password : **rinaldipratama.com**

# Fitur Aplikasi
Adapun beberapa fitur yang tersedia pada aplikasi ini adalah sebagai berikut:

- Kelola data master berupa:
  - Supplier
  - Pelanggan
  - Pegawai
  - Barang
  - Kategori Barang
- Transaksi Barang Masuk
- Transaksi Barang Keluar
- Cetak Laporan:
  - Persediaan Barang
  - Barang Masuk
  - Barang Keluar
- Ubah nama, username, status dan password
  



