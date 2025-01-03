# PT Sisber 1's Employees Information System

This application is made by:  
Class 03TPLE005's Sistem Berkas Group 1:  
- Alief Aditiyo Nasokha – 231011400929  
- Egidius Edi Putrawan – 231011403453  
- Agung Prayoga – 231011400246  
- Jaisy M. Algifari - 231011400253  
- Tri Wulan Setiyowati – 231011401099  

This application's purpose is to demonstrate students' understanding of file systems (sistem berkas).

---

## Prerequisites:
1. **Go installed**
2. **MySQL installed** with these configurations:
   - Port: `3306` (default)
   - Root user
   - Root password: `qwer1234`
   - Run this query in the MySQL CLI:
     ```sql
     create database Pegawai;

     use Pegawai;

     CREATE TABLE `Employee9998` (
       ID_Pegawai int auto_increment primary key,
       NIK varchar(16),
       Nama varchar(20),
       Username varchar(20) unique,
       Password varchar(120),
       Alamat varchar(100),
       Tempat_Lahir varchar(30),
       Tanggal_Lahir date,
       No_HP int,
       Pekerjaan varchar(20),
       Gender varchar(20),
       updated_at datetime default CURRENT_TIMESTAMP,
       created_at datetime default CURRENT_TIMESTAMP
     ) ENGINE=InnoDB DEFAULT CHARSET=latin1;
     ```

---

## How to Run:
1. Go to the root of the project.
2. Run:
   ```bash
   go run main.go
3. Open http://localhost:9998/ in your browser


## Instruktsi Bahasa Indonesia

Tujuan dari aplikasi ini adalah untuk menunjukkan pemahaman mahasiswa tentang sistem berkas.

---

## Prasyarat:
1. **Go terinstal**
2. **MySQL terinstal** dengan konfigurasi berikut:
   - Port: `3306` (default)
   - Pengguna Root
   - Password Root: `qwer1234`
   - Jalankan query berikut di MySQL CLI:
     ```sql
     create database Pegawai;

     use Pegawai;

     CREATE TABLE `Employee9998` (
       ID_Pegawai int auto_increment primary key,
       NIK varchar(16),
       Nama varchar(20),
       Username varchar(20) unique,
       Password varchar(120),
       Alamat varchar(100),
       Tempat_Lahir varchar(30),
       Tanggal_Lahir date,
       No_HP int,
       Pekerjaan varchar(20),
       Gender varchar(20),
       updated_at datetime default CURRENT_TIMESTAMP,
       created_at datetime default CURRENT_TIMESTAMP
     ) ENGINE=InnoDB DEFAULT CHARSET=latin1;
     ```

---

## Cara Menjalankan:
1. Masuk ke root folder proyek.
2. Jalankan perintah:
   ```bash
   go run main.go
3. Buka http://localhost:9998/ di browser Anda.