# 🧩 CRUD Java Swing dengan Upload CSV

Proyek ini dibuat sebagai **tugas pertemuan ke-10** mata kuliah **Pemrograman Berorientasi Objek (PBO)**.  
Aplikasi ini mengimplementasikan sistem **CRUD (Create, Read, Update, Delete)** berbasis **Java Swing** yang terhubung ke **database PostgreSQL**, dengan tambahan fitur unggah data dari **file CSV**.

---

## 📜 Deskripsi Proyek
Aplikasi ini merupakan sistem CRUD yang dikembangkan menggunakan **Java Swing** dengan koneksi ke **PostgreSQL**.  
Fitur utama yang ditambahkan adalah **Upload CSV**, yang memungkinkan pengguna memasukkan data dalam jumlah banyak ke dalam database tanpa input manual.

### 🔧 Komponen Utama
- **Jendela Utama (Main Form):** Menampilkan data dalam bentuk tabel (`JTable`).
- **Dialog Pop-up (JDialog):** Untuk proses tambah, ubah, dan hapus data.
- **Tombol Upload CSV:** Menggunakan `JFileChooser` untuk memilih file `.csv`.
- **Database PostgreSQL:** Sebagai media penyimpanan data CRUD.
- **BufferedReader:** Untuk membaca isi file CSV sebelum dimasukkan ke database.

---

## 🎯 Tujuan Pembelajaran
- Memahami cara membaca dan memproses file **CSV di Java**.
- Mengimplementasikan **JFileChooser** dalam aplikasi GUI.
- Menambah efisiensi input data lewat fitur **import otomatis**.
- Menerapkan **Custom Exception** dan penanganan error berbahasa Indonesia.
- Menggabungkan konsep **OOP + GUI + Database** dalam satu proyek terintegrasi.
- Memperluas sistem CRUD dengan mekanisme upload CSV.

---

## ⚙️ Implementasi Fitur Upload CSV
Langkah-langkah utama dalam menambahkan fitur ini:

1. Tambahkan **button "Upload"** di tampilan utama aplikasi (`Form`).
2. Tambahkan **import** library Java yang diperlukan pada file `DataPramuka.java`.
3. Buat method untuk membaca file `.csv` dan memasukkan datanya ke database.
4. Jalankan program dan pilih file CSV menggunakan `JFileChooser`.
5. Sistem akan otomatis **skip** data yang memiliki **primary key duplikat** (misal: nomor atau nama klub sama).

---
