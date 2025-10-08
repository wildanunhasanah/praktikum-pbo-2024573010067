# Laporan Modul 2: Dasar Pemrograman Java

**Mata Kuliah:** Praktikum Pemrograman Berorientasi Objek   
**Nama:** Wildanun Hasanah  
**NIM:** 2024573010067  
**Kelas:** 2E

---

## 1. Abstrak
Laporan ini berisi rangkuman hasil praktikum mengenai dasar-dasar pemrograman Java. Tujuan laporan adalah untuk memahami konsep dasar seperti variabel, tipe data, operator, input-output, percabangan (if-else, switch), serta perulangan (for, while, do-while). Dengan praktikum ini diharapkan mahasiswa mampu menguasai sintaks dasar Java sebagai fondasi untuk pemrograman berorientasi objek.

---

## 2. Praktikum

### Praktikum 1 - Variabel dan Operator
#### Dasar Teori
Pada praktikum ini dipelajari cara mendeklarasikan variabel, menggunakan tipe data dasar, dan mengoperasikan operator aritmatika, casting, serta automatic promotion.
#### Langkah Praktikum
1. Buat class `VariableDemo`.
2. Deklarasikan variabel bertipe `int`, `double`, `char`, `boolean`, dan `String`.
3. Lakukan operasi aritmatika dan casting tipe data.
4. Cetak hasil ke layar.
#### Screenshoot Hasil
![](laporan/laporan1/gambar/VariabelDemo.png)
#### Analisa dan Pembahasan
Program berhasil menampilkan hasil deklarasi variabel serta operasi aritmatika. Percobaan ini memperlihatkan bagaimana Java menangani perbedaan tipe data melalui casting.

---

### Praktikum 2 - Input dan Output
#### Dasar Teori
Java menyediakan class `Scanner` untuk menerima input dari pengguna. Output dapat ditampilkan dengan `System.out.print` dan `System.out.println`.
#### Langkah Praktikum
1. Buat class `InputOutputDemo`.
2. Gunakan `Scanner` untuk membaca input `String`, `int`, dan `double`.
3. Tampilkan hasil input ke layar.
#### Screenshoot Hasil
![](laporan/laporan1/gambar/InputOutput.png)

#### Analisa dan Pembahasan
Program menerima input dari pengguna lalu menampilkannya kembali. Hal ini menunjukkan konsep dasar interaksi antara program dan user.

---

### Praktikum 3 - Percabangan If-Else
#### Dasar Teori
Percabangan digunakan untuk mengambil keputusan berdasarkan kondisi. Pada Java tersedia `if-else` dan `switch`.
#### Langkah Praktikum
1. Buat class `GradeDemo`.
2. Baca input nilai.
3. Tentukan grade (`A-E`) berdasarkan range nilai menggunakan `if-else`.
4. Tampilkan hasil.
#### Screenshoot Hasil
![](laporan/laporan1/gambar/GradeDemo.png)
#### Analisa dan Pembahasan
Program berhasil menentukan grade sesuai rentang nilai. Konsep ini penting untuk membuat logika dalam aplikasi nyata.

---

### Praktikum 4 - Percabangan Switch
#### Dasar Teori
`Switch` digunakan untuk memilih salah satu aksi dari banyak pilihan berdasarkan nilai ekspresi.
#### Langkah Praktikum
1. Buat class `MenuDemo`.
2. Buat menu pilihan (misalnya: tambah, kurang, kali, bagi).
3. Gunakan `switch-case` untuk menentukan operasi.
4. Cetak hasil operasi ke layar.
#### Screenshoot Hasil
![](laporan/laporan1/gambar/MenuDemo.png)
#### Analisa dan Pembahasan
Program dapat memilih operasi sesuai input user. `Switch` lebih efisien dibandingkan `if-else` jika pilihan cukup banyak.

---

### Praktikum 5 - Nested If
#### Dasar Teori
`Nested if` adalah percabangan bersarang, yaitu `if` di dalam `if`.
#### Langkah Praktikum
1. Buat class `NestedIfDemo`.
2. Implementasikan logika untuk menentukan kategori (misalnya nilai dan keterangan lulus/tidak lulus).
3. Jalankan program dan amati hasil.
#### Screenshoot Hasil
![](laporan/laporan1/gambar/NestedIfDemo.png)
#### Analisa dan Pembahasan
Program berhasil mengelompokkan hasil dengan logika bersarang. Konsep ini berguna saat kondisi lebih dari satu.

---

### Praktikum 6 - Perulangan For
#### Dasar Teori
`For` digunakan untuk perulangan dengan jumlah iterasi yang sudah jelas.
#### Langkah Praktikum
1. Buat class `ForLoopDemo`.
2. Cetak angka 1–10.
3. Buat tabel perkalian sederhana.
#### Screenshoot Hasil
![](laporan/laporan1/gambar/ForLoopDemo.png)
#### Analisa dan Pembahasan
Perulangan `for` cocok digunakan saat jumlah perulangan sudah diketahui, misalnya mencetak angka berurutan.

---

### Praktikum 7 - Perulangan While
#### Dasar Teori
`While` digunakan untuk perulangan berdasarkan kondisi yang harus bernilai `true`.
#### Langkah Praktikum
1. Buat class `WhileLoopDemo`.
2. Implementasikan perulangan countdown (misalnya dari 10 ke 1).
3. Tambahkan kondisi berhenti.
#### Screenshoot Hasil
![](laporan/laporan1/gambar/WhileLoopDemo.png)
#### Analisa dan Pembahasan
Program mencetak angka mundur sesuai kondisi. `While` cocok digunakan ketika jumlah iterasi tidak diketahui pasti di awal.

---

### Praktikum 8 - Nested Loop
#### Dasar Teori
`Nested loop` adalah perulangan bersarang, yaitu `loop` di dalam `loop`.
#### Langkah Praktikum
1. Buat class `NestedLoopDemo`.
2. Implementasikan perulangan untuk mencetak pola (misalnya segitiga bintang atau tabel).
3. Jalankan program.
#### Screenshoot Hasil
![](laporan/laporan1/gambar/NestedLoopDemo.png)
#### Analisa dan Pembahasan
Program berhasil mencetak pola dengan perulangan bersarang. `Nested loop` banyak digunakan untuk masalah multidimensi, seperti matriks atau tabel.

---

## 3. Kesimpulan
Dari praktikum ini dapat disimpulkan bahwa dasar pemrograman Java meliputi variabel, operator, input-output, percabangan (if-else, switch, nested if), serta perulangan (for, while, nested loop). Pemahaman konsep dasar ini penting sebagai landasan untuk mempelajari konsep lanjutan seperti class, objek, dan pemrograman berorientasi objek.

---

## 5. Referensi
1. Oracle Java Documentation — https://docs.oracle.com/javase/tutorial/
2. Deitel, H. & Deitel, P. (2017). *Java: How to Program, 11th Edition.* Pearson.
3. W3Schools Java Tutorial — https://www.w3schools.com/java/

---
