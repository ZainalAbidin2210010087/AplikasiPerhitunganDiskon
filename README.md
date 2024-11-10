# NAMA : ZAINAL ABIDIN

# NPM  : 2210010087

# KELAS : 5B NONREG BANJARMASIN 

# ( TUGAS 3 )


---

# AplikasiPerhitunganDiskon

## Deskripsi
**AplikasiPerhitunganDiskon** adalah aplikasi berbasis Java Swing yang membantu pengguna menghitung diskon pada harga barang. Program ini memungkinkan pengguna memasukkan harga asli produk, memilih persentase diskon, dan menambahkan potongan tambahan dari kode kupon untuk mendapatkan harga akhir. Aplikasi ini juga menampilkan riwayat perhitungan sebelumnya.

## Fitur
1. **Input Harga Asli**: Pengguna dapat memasukkan harga asli produk.
2. **Persentase Diskon**: Pilihan diskon dari 20%, 40%, 60%, atau 80%.
3. **Kode Kupon Tambahan**: Input tambahan untuk diskon yang dihasilkan dari kode kupon.
4. **Riwayat Perhitungan**: Hasil perhitungan disimpan dalam area riwayat sehingga pengguna dapat melihat perhitungan sebelumnya.
5. **Penghitungan Otomatis**: Setelah memasukkan data, tombol “Hitung Diskon” akan menghitung harga akhir dan penghematan secara otomatis.
6. **Validasi Input**: Program memvalidasi semua input numerik untuk memastikan tidak ada kesalahan.

## Teknologi yang Digunakan
- **Java**: Bahasa pemrograman utama.
- **Java Swing**: Library GUI (Graphical User Interface) untuk membangun antarmuka.
- **Event Handling**: Menggunakan `ActionListener` dan `ItemListener` untuk menangani interaksi pengguna.

## Keunggulan
- **Antarmuka yang Mudah Dipahami**: GUI intuitif dengan tombol dan input yang jelas.
- **Riwayat Perhitungan**: Memungkinkan pengguna menyimpan dan melihat perhitungan sebelumnya.
- **Kalkulasi Otomatis**: Menghemat waktu dengan otomatisasi penghitungan harga akhir.
- **Fleksibilitas Diskon**: Pengguna dapat menggabungkan beberapa jenis diskon dalam satu perhitungan.

## Cara Menggunakan Aplikasi
1. **Masukkan Harga Asli**: Ketik harga produk asli pada kolom “Masukkan Harga”.
2. **Pilih Diskon**: Pilih persentase diskon yang diinginkan dari `discountComboBox`.
3. **Masukkan Kode Kupon**: Jika memiliki kode kupon tambahan, masukkan nilai potongannya di kolom "Kode Diskon".
4. **Klik "Hitung Diskon"**: Tombol ini akan menghitung harga akhir dan jumlah penghematan.
5. **Lihat Hasil**: Hasil akhir akan muncul pada kolom "Harga Akhir", dan total penghematan akan muncul pada kolom "Penghematan".
6. **Riwayat Perhitungan**: Setiap perhitungan akan tersimpan dalam area "Riwayat" untuk referensi lebih lanjut.

## Cara Menjalankan Program
1. Pastikan **Java Development Kit (JDK)** telah terinstal.
2. Unduh atau salin kode `DiscountCalculatorForm.java`.
3. Buka terminal atau command prompt, navigasikan ke direktori file, dan jalankan perintah berikut:
   ```bash
   javac DiscountCalculatorForm.java
   ```
   untuk mengompilasi program.
4. Jalankan program dengan perintah:
   ```bash
   java DiscountCalculatorForm
   ```
5. Aplikasi akan terbuka dalam bentuk GUI. Ikuti langkah-langkah penggunaan untuk menghitung diskon pada produk.

---

Dengan aplikasi ini, pengguna dapat dengan mudah menghitung diskon dan melihat penghematan pada berbagai produk, dengan fleksibilitas untuk menambahkan potongan tambahan dari kode kupon.
