# Lab8Web
## PHP dan Database MySQL

### Menjalankan Web server
Pertama, kita harus menjalankan web server yang ada di XAMPP control begini tampilannya:
![gambar1](screenshot/ss1.png)

### Membuat Database
Kedua, pastikan webserver Apache dan MySQL telah berjalan begini kemudian buka melalui browser : http://localhost/phpmyadmin/, begini  tampilannya:
![gambar2](screenshot/ss2.png)

Lalu, membuat tabel dan menambahkan data pada tabel tersebut, begini tampilannya:
![gambar3](screenshot/ss3.png)
![gambar4](screenshot/ss4.png)
![gambar5](screenshot/ss5.png)



### Membuat Program CRUD
Setelah membuat database dan tabel saya mengecek database yang saya buat pada cmd, begini tampilannya:
![gambar6](screenshot/ss6.png)

Lalu, saya membuat folder baru dengan nama lab8_php_database pada root directory web server (d:\xampp\htdocs) dan kemudian untuk mengakses nya menggunakan URL http://localhost/lab8_php_database/, begini tampilannya:
![gambar7](screenshot/ss7.png)


### Membuat File Koneksi Database
Lalu, saya membuat file baru dengan nama koneksi.php dan buka melalui browser untuk menguji koneksi database (untuk menampilkan koneksi berhasil, uncomment pada perintah echo "koneksi berhasil") beginilah tampilannya:
![gambar8](screenshot/ss8.png)


### Membuat File Index
Membuat file index untuk menampilkan data dengan buat file baru bernama index.php, begini tampilannya:
![gambar9](screenshot/ss9.png)


### Menambah Data
Menambah data dengan membuat file baru bernama tambah.php, begini tampilannya:
![gambar10](screenshot/ss10.png)

Dan ini adalah hasil dari menambahkan barang tersebut:
![gambar11](screenshot/ss11.png)


### Mengubah Data
Mengubah data (update) dengan membuat file bernama ubah.php begini tampilannya:
![gambar12](screenshot/ss12.png)


### Menghapus Data
Membuat file baru dengan nama hapus.php untuk menghapus data, begini tampilannya:
![gambar13](screenshot/ss13.png)