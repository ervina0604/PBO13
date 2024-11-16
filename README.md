# 📚 Laporan Tugas Kuliah - Pemrograman Berorientasi Objek (Pertemuan Tigabelas)

**Topik Utama:** Implementasi Sistem Login dengan Database PostgreSQL dan GUI  

---

## 📑 Daftar Isi  
1. [Membuat Tabel di Database PostgreSQL](#1-membuat-tabel-di-database-postgresql)  
2. [Membuat Entity Class dari Database](https://github.com/ervina0604/PBO13/blob/main/META-INF/persistence.xml)  
3. [Membuat Form Login](https://github.com/ervina0604/PBO13/blob/main/pbo13/login.java)  
4. [Tampilan Berhasil Login](https://github.com/ervina0604/PBO13/blob/main/pbo13/GuiMataKuliah.java)  
5. [Menambahkan Tombol Logout](https://github.com/ervina0604/PBO13/blob/main/pbo13/GuiMataKuliah.java)  

---

## 1. Membuat Tabel di Database PostgreSQL  
 membuat tabel yang akan menyimpan data login. Tabel ini digunakan untuk menyimpan informasi seperti **username** dan **password** pengguna.   
- Gunakan perintah SQL untuk membuat tabel di PostgreSQL.
  ![image](https://github.com/user-attachments/assets/27465b61-f3ad-4054-b869-d47cc7fc2a60)

- Tambahkan data pengguna yang diperlukan ke tabel.
- ![image](https://github.com/user-attachments/assets/c7259118-b8c7-4c6a-9047-5cee1da9249d)

---

## 2. Membuat Entity Class dari Database  
Entity class digunakan untuk memetakan tabel yang ada di database ke dalam bentuk objek Java. Dengan memanfaatkan library seperti **JPA (Java Persistence API)**, proses ini bisa dilakukan secara otomatis.  
![image](https://github.com/user-attachments/assets/1f12e542-8dde-4566-a425-30b967f4e2e2)

![image](https://github.com/user-attachments/assets/bd39f89f-b8b6-4af1-94ea-f8e2dd28ce83)

![image](https://github.com/user-attachments/assets/60c16234-8794-4308-b79e-186185d6367a)

- Otomatis muncul di project setelah proses pemetaan selesai.  
![image](https://github.com/user-attachments/assets/98392491-3197-47fc-a1e8-19f07a51319a)

---

## 3. Membuat Form Login  
![image](https://github.com/user-attachments/assets/e7cb5ee4-b0eb-41e4-b0bc-1fbb7391851c)

source code: 
![image](https://github.com/user-attachments/assets/d380e348-6f6b-40d6-895e-3d0e1cfb5622)

---

## 4. Tampilan Berhasil Login  
Setelah login berhasil, pengguna akan melihat pesan konfirmasi bahwa login berhasil. Kemudian, tampilan akan berpindah ke antarmuka berikutnya, yaitu **GUI MataKuliah**.  
![image](https://github.com/user-attachments/assets/1fd9050f-72b3-4c18-9350-51c7e019317f)

---

## 5. Menambahkan Tombol Logout  
Di GUI MataKuliah, tambahkan tombol **Logout** yang memungkinkan pengguna keluar dari sesi mereka dan kembali ke form login.  
![image](https://github.com/user-attachments/assets/99bcb3d9-4c06-4ce1-a170-11c2a9e7ee7f)

source code: 
![image](https://github.com/user-attachments/assets/43823a15-c7e6-467c-94b9-aa4e2324a9a3)

---

## 🚀 Selamat Menerapkan Konsep Pemrograman Berorientasi Objek!  

--- 
