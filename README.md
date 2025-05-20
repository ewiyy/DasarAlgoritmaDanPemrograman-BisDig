# DasarAlgoritmaDanPemrograman-BisDig
1. ## Program: Mencari Nilai Tertinggi dari 5 Siswa
### Deskripsi
Program ini digunakan untuk menerima input nilai dari 5 siswa, lalu mencari dan menampilkan:
- Nilai tertinggi
- Siswa ke berapa yang mendapatkannya
### Konsep yang Digunakan
- **Perulangan (`for`)** digunakan untuk menginput nilai tanpa mengulang kode secara manual.
- **List (array)** digunakan untuk menyimpan nilai-nilai siswa dalam satu struktur data.
- Fungsi **`max()`** digunakan untuk mencari nilai tertinggi.
- Fungsi **`index()`** untuk menentukan siswa yang mendapat nilai tersebut.
### Contoh Output
Masukkan nilai siswa ke-1: 78
Masukkan nilai siswa ke-2: 85
Masukkan nilai siswa ke-3: 90
Masukkan nilai siswa ke-4: 88
Masukkan nilai siswa ke-5: 90
===== HASIL =====
Nilai tertinggi adalah 90.0, didapat oleh siswa ke-3.
### Cara Menjalankan Program
1. Pastikan Python terinstal.
2. Jalankan perintah:
   ```bash
   python nilai_tertinggi.py

2. ## Program: Menentukan Kelulusan Berdasarkan Rata-Rata Nilai
### Deskripsi
Program ini dibuat untuk membantu siswa mengetahui apakah mereka **LULUS** atau **TIDAK LULUS** berdasarkan rata-rata nilai dari 3 mata pelajaran.
### Syarat Kelulusan
- LULUS jika rata-rata **≥ 75**
- TIDAK LULUS jika rata-rata **< 75**
### Konsep yang Digunakan
- **Tipe Data:**
  - `float` untuk nilai ujian
  - `str` untuk status kelulusan
- **Operator:**
  - Aritmatika: `+`, `/`
  - Perbandingan: `>=`
  - Penugasan: `=`
### Contoh Output
Masukkan nilai mata pelajaran 1: 80
Masukkan nilai mata pelajaran 2: 70
Masukkan nilai mata pelajaran 3: 75

===== HASIL KELULUSAN =====
Rata-rata nilai: 75.00
Status: LULUS
### Cara Menjalankan
1. Pastikan Python sudah terinstal.
2. Jalankan dengan perintah:
   ```bash
   python kelulusan.py
   
3. ## Program: Menghitung Faktorial dengan Rekursi
### Deskripsi
Program ini ditulis dalam bahasa Python untuk menghitung faktorial dari suatu bilangan menggunakan metode **rekursif**.
### Konsep
Faktorial dari suatu bilangan `n` adalah hasil perkalian dari `n` dengan semua bilangan bulat positif di bawahnya hingga 1.  
Contoh: `5! = 5 × 4 × 3 × 2 × 1 = 120`
Program ini menggunakan **fungsi rekursif**, yaitu fungsi yang memanggil dirinya sendiri.
### Contoh Output
Masukkan angka untuk menghitung faktorial: 5
Faktorial dari 5 adalah 120
### Struktur File
- `faktorial.py` : Berisi kode Python untuk menghitung faktorial.
- `README.md` : Penjelasan tentang program dan cara kerjanya.
### Cara Menjalankan
1. Pastikan Python sudah terinstal.
2. Jalankan program dengan perintah:
   ```bash
   python faktorial.py

4.  ## Program: Diskon 10% Jika Belanja > Rp500.000
### Deskripsi
Program ini digunakan dalam sistem e-commerce untuk menghitung total bayar pelanggan setelah diskon.  
Pelanggan mendapatkan **diskon 10%** jika total belanja **lebih dari Rp500.000**.
### Konsep yang Digunakan
- **Struktur Kontrol Percabangan (`if-else`)** digunakan untuk memeriksa apakah pelanggan berhak mendapat diskon atau tidak.
- **Operator Perbandingan (`>`)** digunakan untuk menentukan syarat pemberian diskon.
- **Operator Aritmatika (`*`, `-`)** digunakan untuk menghitung diskon dan total bayar.
### Contoh Output
Masukkan total belanja (Rp): 600000

===== STRUK PEMBAYARAN =====
Total belanja : Rp600,000.00
Diskon : Rp60,000.00
Total bayar : Rp540,000.00
### Cara Menjalankan
1. Pastikan Python telah terinstal di komputer Anda.
2. Jalankan perintah:
   ```bash
   python diskon_ecommerce.py

5. ## Program: Menghitung Total Harga 3 Barang
### Deskripsi
Program ini merupakan sistem sederhana untuk membantu kasir menghitung total harga dari 3 barang yang dibeli oleh pelanggan.
### Langkah Algoritma
1. Mulai program.
2. Minta pengguna memasukkan harga dari 3 barang satu per satu.
3. Jumlahkan semua harga.
4. Tampilkan total pembayaran.
5. Selesai.
### Contoh Output
Masukkan harga barang ke-1: 15000
Masukkan harga barang ke-2: 27500
Masukkan harga barang ke-3: 5000

===== TOTAL PEMBAYARAN =====
Total harga dari 3 barang adalah: Rp47,500.00

### Fitur Program
- Validasi input angka
- Format output dengan dua desimal dan tanda ribuan
### Cara Menjalankan
1. Pastikan Python telah diinstal di komputer Anda.
2. Jalankan perintah:
   ```bash
   python total_harga.py
