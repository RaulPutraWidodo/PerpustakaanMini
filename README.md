# $${\color{lightgreen}PerpustakaanMini}$$

PerpustakaanMini adalah Perpustakaan Management System berbasis web yang dikembangkan menggunakan PHP, MySQL, JavaScript, CSS, dan framework Bootstrap, dirancang untuk membantu mengelola buku yang di miliki secara efisien dengan fitur: autentikasi (login), tambah buku (CRUD dengan database MySQL), daftar buku.

| Mata Kuliah     | Dosen Pengampu                     |
| --------- | ----------------------------- |
| **Pemrograman Web 2** | Agung Nugroho S.kom., M.Kom.      |

<br>

| Profile     | Anggota                     |
| --------- | ----------------------------- |
| **312310610** | Raul Putra Widodo         |
| **312310697** | Lintang Rafi Adhi         |
| **312310591** | Wishnu Aqbil Ramadani     |

## ⚙️ Teknologi & Tools

- **Bahasa**: PHP (Native)
- **Database**: MySQL
- **Frontend**: HTML, CSS, Bootstrap
- **Email**: PHPMailer
- **Server Lokal**: XAMPP (Apache & MySQL)

---

````markdown
## 🛠️ Cara Instalasi

1. **Clone atau Unduh Project**
   ```bash
   git clone https://github.com/FadilAdz/InvoiceWeb.git
````

2. **Letakkan Folder di XAMPP**
   Pindahkan folder hasil clone ke:

   ```
   C:\xampp\htdocs\perpustakaanmini
   ```

3. **Import Database**

   * Jalankan XAMPP dan buka `phpMyAdmin`
   * Buat database baru, misalnya: `perpustakaan_mini`
   * Import file SQL dari folder `DATABASE FILE/`

4. **Sesuaikan Koneksi Database**

   * Edit file koneksi di `includes/config.php` (atau sesuai struktur file kamu)
   * Contoh:

     ```php
     $host = "localhost";
     $user = "root";
     $pass = "";
     $dbname = "perpustakaan_mini";
     ```

5. **Jalankan Aplikasi di Browser**
   Akses melalui URL:

   ```
   http://localhost/8080
   ```

---

---

## 📸 Screenshot Tampilan

### 1. Halaman Login
![image](invoice/login.png)
Form untuk user melakukan login ke sistem.

### 2. Halaman Dashboard
![image](invoice/dashbord.png)
Tampilan utama setelah login berisi ringkasan data dan navigasi ke menu lainnya.

### 3. Invoice List
![image](invoice/invoice.png)
Menu untuk melihat daftar seluruh invoice yang telah dibuat.

### 4. Customer List
![image](invoice/customer.png)
Menu untuk melihat dan mengelola daftar customer.

### 5. Product List
![image](invoice/produk.png)
Menu untuk melihat dan mengelola daftar produk.

### 6. User List
![image](invoice/user.png)
Menu untuk melihat dan mengelola daftar user yang memiliki akses ke sistem.

---
