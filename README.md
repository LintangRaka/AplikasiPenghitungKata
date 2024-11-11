# Penghitung Kata dengan Java Swing


Nama : Lintang Raka Buana  
NPM : 2210010381   
Kelas: 5A REG Banjarbaru

![image](https://github.com/user-attachments/assets/803a4fd3-694c-4cd6-8876-ef96bac70a1d)
![image](https://github.com/user-attachments/assets/1cec7b32-95c9-4a6c-a1c8-99a8b6dd2233)
![image](https://github.com/user-attachments/assets/66a002fc-8a21-4488-93b4-b3c340eec38f)
![image](https://github.com/user-attachments/assets/82eeb656-c550-4955-9b9d-f5f83c3efb5b)
![image](https://github.com/user-attachments/assets/0285c2f7-12f2-465d-8825-01e416abace8)


## Deskripsi Program
Program ini menyediakan antarmuka grafis (GUI) yang memungkinkan pengguna untuk memasukkan teks dan secara otomatis menghitung jumlah kata, karakter, kalimat, dan paragraf. Program ini juga memiliki fitur pencarian kata dan penyimpanan hasil perhitungan ke dalam file teks.

## Fitur
1. **Input Teks**:
   - Pengguna memasukkan teks ke dalam `JTextArea`, yang kemudian dihitung jumlah kata, karakter, kalimat, dan paragrafnya.
   
2. **Pencarian Kata**:
   - Pengguna dapat mencari kata tertentu dalam teks yang diinput, dan kata yang ditemukan akan disorot dalam `JTextArea`.

3. **Penyimpanan ke File**:
   - Pengguna dapat menyimpan teks beserta hasil perhitungan ke dalam file `.txt`.

## Komponen GUI yang Digunakan
- `JFrame` untuk frame utama aplikasi.
- `JPanel` untuk tata letak komponen.
- `JLabel` untuk label teks yang menampilkan hasil perhitungan.
- `JTextArea` untuk input teks.
- `JButton` untuk tombol "Hitung", "Cari", dan "Simpan".
- `JFileChooser` untuk memilih lokasi penyimpanan file.

## Event Handling
- **DocumentListener** pada `JTextArea` untuk mendeteksi perubahan teks secara otomatis.
- **ActionListener** pada tombol "Hitung", "Cari", dan "Simpan" untuk menjalankan perhitungan, pencarian, dan penyimpanan saat tombol ditekan.

## Logika Program
- **Perhitungan Jumlah Kata, Karakter, Kalimat, dan Paragraf**:
  - Menggunakan metode split untuk memisahkan teks berdasarkan spasi, tanda baca, dan paragraf.
  
- **Sorotan Kata yang Ditemukan**:
  - Menggunakan `Highlighter` dan `HighlightPainter` untuk menandai kata yang ditemukan dalam teks.

- **Penyimpanan ke File**:
  - Menggunakan `BufferedWriter` untuk menulis teks beserta hasil perhitungan ke dalam file `.txt`.

## Cara Menggunakan
1. Masukkan teks di `JTextArea`.
2. Tekan tombol "Hitung" untuk memperbarui jumlah kata, karakter, kalimat, dan paragraf.
3. Gunakan tombol "Cari" untuk menemukan kata tertentu di dalam teks.
4. Gunakan tombol "Simpan" untuk menyimpan teks beserta hasil perhitungan ke dalam file.
