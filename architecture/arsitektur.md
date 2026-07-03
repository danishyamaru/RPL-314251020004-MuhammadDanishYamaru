# Arsitektur Sistem

## 1. Pendahuluan

Arsitektur perangkat lunak merupakan struktur dasar yang menjelaskan bagaimana setiap komponen dalam sistem saling berinteraksi. Pemilihan arsitektur yang tepat akan mempermudah proses pengembangan dan pemeliharaan sistem.

---

## 2. Arsitektur yang Digunakan

Sistem menggunakan **Layered Architecture**.

Layer yang digunakan terdiri dari:

- Presentation Layer
- Business Logic Layer
- Data Access Layer
- Database Layer

---

## 3. Penjelasan Setiap Layer

### Presentation Layer

Layer yang berhubungan langsung dengan pengguna.

Contohnya:

- Halaman Login
- Dashboard
- Halaman Produk
- Checkout

---

### Business Logic Layer

Layer yang menjalankan seluruh proses bisnis.

Contoh:

- Login
- Perhitungan total pembayaran
- Validasi transaksi

---

### Data Access Layer

Layer yang menghubungkan aplikasi dengan database.

Tugasnya:

- Insert Data
- Update Data
- Delete Data
- Select Data

---

### Database Layer

Menyimpan seluruh data sistem seperti:

- User
- Produk
- Transaksi
- Kategori
- Laporan

---

## 4. Alasan Menggunakan Layered Architecture

- Mudah dikembangkan.
- Mudah diuji.
- Mudah dipelihara.
- Kode lebih rapi.
- Memisahkan tanggung jawab setiap komponen.

---

## Kesimpulan

Layered Architecture sangat cocok digunakan pada Sistem E-Commerce karena mampu menjaga struktur aplikasi tetap terorganisir.