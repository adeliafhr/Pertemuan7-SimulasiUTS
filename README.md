# Aplikasi CRUD Java Swing untuk Entitas Buku
---
## 🗂️ Table Of Contents 
- [Koneksi Database dengan JDBC](https://github.com/adeliafhr/Pertemuan7-SimulasiUTS/blob/main/Buku.java)
- [Penerapan CRUD](https://github.com/adeliafhr/Pertemuan7-SimulasiUTS/blob/main/Buku.java)

 ---
##  📋 Langkah - Langkah Penggunaan
### 1. Membuat database pada postgreSQL dengan nama **Buku**
   ![databaseBuku](https://github.com/user-attachments/assets/2676a3dc-a1e3-479f-9e17-b5ee9d9fb16e)
   
   ---
### 2. Membuat kelas java frame form dengan nama **Buku**
![Screenshot (232)](https://github.com/user-attachments/assets/ada1f374-5c97-44b4-8b50-db47702eacd9)

---
### 3. Koneksi project dengan database 
Koneksikan project dengan database yang terdapat pada PostgreeSQL dan tambahkan library JAR PostgreeSQL pada project
   ![jdbc buku](https://github.com/user-attachments/assets/e1847650-8817-4b1c-ad6f-65dc7cd040e2) ![libraryBuku](https://github.com/user-attachments/assets/5664e52f-43e7-49e5-a103-5fc36319931d)
   
---
### 4. Membuat design GUI
Komponen utama yang di gunakan adalah :

- JTable yang digunakan untuk menampilkan data buku
- JButton yang digunakan untuk tombol insert, update, dan delete
- JLabel yang digunakan untuk menampilkan teks yang tetap
- JTextField yang digunakan untuk mengisi data ISBN, Judul buku, Tahun terbit, Penerbit
   ![GUI Buku](https://github.com/user-attachments/assets/d00e12f0-eb45-4044-a24c-7ca23707d2ed)

  ---
### 5. Buat kode untuk mengoneksi java dengan database
   ![koneksi java pd database buku](https://github.com/user-attachments/assets/0f3236bd-ff13-4c7e-b7c5-534c6c506c17)

   ---
### 6. Buat method tampil
method tampil digunakan untuk menampilkan semua data buku pada tabel
   ![tampilBuku](https://github.com/user-attachments/assets/4a87c16a-1281-4abf-8e35-bece6673a156)

   ---
### 7. Buat kode untuk menambahkan data buku (button insert)
Pengguna dapat menambahkan data buku dan menulisnya pada JTextField lalu data buku akan tersimpan pada tabel
   ![insertBuku](https://github.com/user-attachments/assets/d94a2e19-37dd-4ad1-a808-3a15f72365bb)
   #### -Berikut adalah tampilan saat menambah data buku-
   ketika kita menekan tombol insert secara otomatis data berhasil di tambahkan dan muncul notifikasi data berhasil ditambah
   ![tampilinsertbuku](https://github.com/user-attachments/assets/500b693d-8f90-4e37-826d-5de253386f77)

---
### 8. Buat kode untuk mengubah data buku (button update)
Pengguna dapat mengupdate data buku dengan memilih data mana yang akan di update dan mengupdate sesuai dengan kemauan lalu data buku akan diupdate dan akan tersimpan pada tabel

   ![updateBuku](https://github.com/user-attachments/assets/68480442-f822-4cd0-9ae0-1c3bbb85f57e)
##### -Berikut adalah tampilan saat mengupdate data-
ketika kita menekan tombol update secara otomatis data yang kita pilih akan di update dan muncul notifikasi data berhasil di update
![tampilUpdateBuku](https://github.com/user-attachments/assets/c5b95074-7137-4886-b1b8-747d291b6397)

---
### 9. Buat kode untuk menghapus data buku (button delete)
Pengguna dapat menghapus data buku dengan cara memilih data mana yang akan di hapus maka data yang sudah terhapus tidak terdapat pada tabel

   ![deletBuku](https://github.com/user-attachments/assets/de8f3bc8-6e9a-4277-8acc-29b91a5bcac3)
#### -Berikut adalah tampilan saat menghapus data-
ketika kita menekan tombol delete secara otomatis data yang kita pilih akan terhapus dan muncul notifikasi data berhasil di hapus
![tampilDeleteBuku](https://github.com/user-attachments/assets/479c7c69-ddd9-42a2-8691-ccf6c931d014)

---
### 10. Buat method TabelMouseClicked
method ini digunakan agar data yang kita pilih akan muncul pada JTextField secara otomatis
![mouseClickBuku](https://github.com/user-attachments/assets/10a649fe-7774-4403-8140-ae58b364fab5)

---
### 11. Buat method bersih
method bersih digunakan untuk menghapus isi dari textField

![bersihBuku](https://github.com/user-attachments/assets/650e2bd3-209e-4bb6-8d24-c0891e627ca4)

---
## 💡Selamat Belajar dan Selamat Mencoba dalam menggunakan Java Swing untuk pengembangan aplikasi GUI!📖








   
