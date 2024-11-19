# Program Pengelolaan Data Nilai Mahasiswa
Program ini dibuat untuk mengelola data nilai mahasiswa dengan kemampuan untuk menambahkan data secara dinamis dan menghitung nilai akhir berdasarkan komponen-komponen nilai yang telah ditentukan.



# Deskripsi
Program ini dirancang untuk mengumpulkan dan mengelola data nilai mahasiswa. Pengguna dapat memasukkan nama, NIM, dan nilai untuk tugas, UTS, dan UAS. Program ini juga menghitung nilai akhir berdasarkan bobot yang telah ditentukan dan menampilkan daftar mahasiswa beserta nilai mereka dalam format tabel.



# Fitur
- Memasukkan data mahasiswa (nama, NIM, nilai tugas, UTS, dan UAS).
- Menghitung nilai akhir berdasarkan komponen nilai:
  - Tugas: 30%
  - UTS: 35%
  - UAS: 35%
- Menampilkan daftar mahasiswa dalam format tabel.
- Validasi input untuk memastikan nilai berada dalam rentang 0 hingga 100.



# Cara Menjalankan
1. Pastikan Anda memiliki Python terinstal di sistem Anda.
2. Salin kode program ke dalam file Python (misalnya, data_nilai_mahasiswa.py).
3. Buka terminal atau command prompt.
4. Navigasikan ke direktori tempat file disimpan.
5. Jalankan program dengan perintah:
   ```bash
   python data_nilai_mahasiswa.py



# Cara Penggunaan
Menjalankan Program bash python program_nilai.py

Input Data

Masukkan nama mahasiswa
Masukkan NIM
Masukkan nilai tugas (0-100)
Masukkan nilai UTS (0-100)
Masukkan nilai UAS (0-100)
Menambah Data

Ketik 'y' untuk menambah data baru
Ketik 't' untuk menampilkan hasil
Melihat Hasil

Program akan menampilkan tabel berisi semua data yang telah diinput
Format tabel menampilkan:
Nomor urut
Nama mahasiswa
NIM
Nilai Tugas
Nilai UTS
Nilai UAS
Nilai Akhir (hasil perhitungan)



# Struktur Kode
hitung_nilai_akhir(tugas, uts, uas): Fungsi untuk menghitung nilai akhir berdasarkan nilai tugas, UTS, dan UAS.
tampilkan_daftar(daftar_mahasiswa): Fungsi untuk menampilkan daftar mahasiswa dalam format tabel.
main(): Fungsi utama yang mengelola alur program, termasuk pengambilan input dan penyimpanan data.



# Struktur Kode
hitung_nilai_akhir(tugas, uts, uas): Fungsi untuk menghitung nilai akhir berdasarkan nilai tugas, UTS, dan UAS.
tampilkan_daftar(daftar_mahasiswa): Fungsi untuk menampilkan daftar mahasiswa dalam format tabel.
main(): Fungsi utama yang mengelola alur program, termasuk pengambilan input dan penyimpanan data.
