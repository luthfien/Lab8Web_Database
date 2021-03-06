# Lab8Web_Database

`membuat aplikasi CRUD sederhana, yang perlu disiapkan adalah database server menggunakan MySQL. Pastikan MySQL Server sudah dapat dijalankan melalui XAMPP.`

# Menjalankan MySQL Server

`Untuk menjalankan MySQL Server dari menu XAMPP Contol.`

 aktifkan MySQL dan Apache.

![image](https://user-images.githubusercontent.com/56451391/120888528-eb12d600-c622-11eb-866e-e60dae94e985.png)

#  Mengakses MySQL Client menggunakan PHP MyAdmin

`Pastikan webserver Apache dan MySQL server sudah dijalankan. Kemudian buka melalui browser:` http://localhost/phpmyadmin/

![image](https://user-images.githubusercontent.com/56451391/120888619-8015cf00-c623-11eb-8c8c-4b131fb59db8.png)

**Kemudian membuat database sebagai berikut:**

![image](https://user-images.githubusercontent.com/56451391/120888738-38dc0e00-c624-11eb-8fed-fa3f78d775e2.png)

`Lalu klik kirim pada bagian pojok kanan bawah.`

**Membuat Tabel Sebagai berikut :**

![image](https://user-images.githubusercontent.com/56451391/120888904-f830c480-c624-11eb-823b-3473244bea6e.png)

![image](https://user-images.githubusercontent.com/56451391/120888944-22828200-c625-11eb-8244-deb74c425412.png)

**Menambahkan data seperti berikut :**

![image](https://user-images.githubusercontent.com/56451391/120889064-b18f9a00-c625-11eb-8722-6d2e6e2ab0a7.png)

![image](https://user-images.githubusercontent.com/56451391/120889144-f87d8f80-c625-11eb-9349-2ee345e8e6e9.png)

#  Membuat Program CRUD

`Buat folder lab8_php_database pada root directory web server (c:\xampp\htdocs)`

![image](https://user-images.githubusercontent.com/56451391/120889407-1697bf80-c627-11eb-9f90-218bba4d74ad.png)

![image](https://user-images.githubusercontent.com/56451391/120889436-4941b800-c627-11eb-816d-598326684955.png)

# Membuat file koneksi database

`Buat file baru dengan nama koneksi.php`

![image](https://user-images.githubusercontent.com/56451391/120891434-d63e3e80-c632-11eb-9f00-a7ac5bb896a6.png)

![image](https://user-images.githubusercontent.com/56451391/120891443-e8b87800-c632-11eb-9f17-79cf8e72cad7.png)

#  Membuat file index untuk menampilkan data (Read)

`Buat file baru dengan nama index.php`

![image](https://user-images.githubusercontent.com/56451391/120890891-c8d38500-c62f-11eb-94a1-3825859eb053.png)

![image](https://user-images.githubusercontent.com/56451391/120890903-d983fb00-c62f-11eb-9b72-de42d4fe0cdb.png)

![image](https://user-images.githubusercontent.com/56451391/120890879-b2c5c480-c62f-11eb-8097-7f83cde3ec2b.png)

#  Mengubah Data (Update)

`Buat file baru dengan nama ubah.php`

![image](https://user-images.githubusercontent.com/56451391/120891313-14872e00-c632-11eb-9ce4-e5aa63ab0a28.png)

![image](https://user-images.githubusercontent.com/56451391/120891326-308acf80-c632-11eb-9ab6-31bd6d8e9200.png)

`Lihat pada tampilan web browser ,Seperti berikut :`

![image](https://user-images.githubusercontent.com/56451391/120891364-7a73b580-c632-11eb-914c-79abfa95c2cd.png)

# Mengubah Data (Update)

`Buat file baru dengan nama ubah.php`

![image](https://user-images.githubusercontent.com/56451391/120892041-574b0500-c636-11eb-9bbc-4ee83e303ea5.png)

![image](https://user-images.githubusercontent.com/56451391/120892134-d80a0100-c636-11eb-907f-ddc96ba51785.png)

![image](https://user-images.githubusercontent.com/56451391/120891970-d3911880-c635-11eb-9199-af9bb142738f.png)

# Menghapus Data (Delete)

`Buat file baru dengan nama hapus.php`

![image](https://user-images.githubusercontent.com/56451391/120892345-0805d400-c638-11eb-9a91-295a5ebf838c.png)

![image](https://user-images.githubusercontent.com/56451391/120892523-f670fc00-c638-11eb-9b9a-6c50de369784.png)

![image](https://user-images.githubusercontent.com/56451391/120892612-6a130900-c639-11eb-937f-1a7139c5026e.png)
