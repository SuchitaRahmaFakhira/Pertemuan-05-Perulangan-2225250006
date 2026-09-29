# Pertemuan 05 Perulangan Python

## Identitas

```text
Nama: Suchita Rahma Fakhira
NIM: 2225250006
Kelas: 3B
Mata Kuliah: Algoritma dan Pemrograman
```

## Tujuan

```text
Pada pertemuan ini saya mempelajari perulangan menggunakan for dan while
dalam Python. Selain itu, saya mempelajari penggunaan range(), kondisi
berhenti, seleksi if di dalam perulangan, akumulasi, dan counting.

Tujuan pembelajaran:
1. Memahami konsep perulangan for dan while.
2. Memahami penggunaan range() pada perulangan for.
3. Menentukan kondisi berhenti pada perulangan while.
4. Menggunakan seleksi if di dalam perulangan.
5. Menggunakan akumulator dan counter.
6. Melakukan pengujian dan tracing sederhana.
7. Menjalankan program melalui VS Code dan mengunggahnya ke GitHub.
```

## Cara Menjalankan

```bash
python latihan/01_tabel_perkalian.py
python latihan/02_jumlah_bilangan.py
python latihan/03_validasi_input.py
python latihan/04_hitung_genap.py
python kuis/kuis2_deret_aritmetika.py
```

## Algoritma Kuis 2

```text
1. Masukkan nilai suku pertama a.
2. Masukkan nilai beda d.
3. Masukkan banyak suku n.
4. Periksa nilai n.
5. Jika n <= 0, minta pengguna memasukkan nilai n kembali.
6. Ulangi proses sampai mendapatkan nilai n yang valid.
7. Tentukan nilai awal total = 0.
8. Gunakan perulangan for sebanyak n kali.
9. Hitung setiap suku dengan rumus:
   suku = a + i * d
10. Tampilkan nomor dan nilai setiap suku.
11. Tambahkan setiap suku ke dalam total.
12. Setelah perulangan selesai, tampilkan jumlah seluruh suku.
```

## Hasil Pengujian

### Pengujian 1

```text
Input:
a = 2
d = 3
n = 5

Output:
Suku ke-1: 2.00
Suku ke-2: 5.00
Suku ke-3: 8.00
Suku ke-4: 11.00
Suku ke-5: 14.00
Jumlah = 40.00
```

### Pengujian 2

```text
Input:
a = 10
d = -2
n = 4

Output:
Suku ke-1: 10.00
Suku ke-2: 8.00
Suku ke-3: 6.00
Suku ke-4: 4.00
Jumlah = 28.00
```

### Pengujian 3

```text
Input:
a = 1.5
d = 0.5
n = 3

Output:
Suku ke-1: 1.50
Suku ke-2: 2.00
Suku ke-3: 2.50
Jumlah = 6.00
```

## Refleksi

```text
1. Bagian mana yang menentukan jumlah iterasi?

Jumlah iterasi ditentukan oleh nilai n pada range(n). Jika n = 5,
maka perulangan berjalan sebanyak 5 kali.


2. Mengapa total = 0 biasanya ditulis sebelum loop?

Karena total digunakan untuk menyimpan hasil penjumlahan selama
perulangan. Dengan nilai awal 0, setiap suku dapat ditambahkan
secara bertahap ke dalam total.


3. Apa yang terjadi jika total = 0 diletakkan di dalam loop?

Nilai total akan kembali menjadi 0 pada setiap iterasi sehingga
hasil penjumlahan sebelumnya akan hilang dan jumlah akhir menjadi
tidak benar.


4. Mengapa while digunakan untuk validasi n?

Karena jumlah percobaan untuk mendapatkan nilai n yang valid belum
diketahui. Perulangan while akan terus berjalan selama n <= 0 sampai
pengguna memasukkan nilai yang valid.


5. Bagaimana membuktikan bahwa loop berhenti tepat sebanyak n kali?

Perulangan menggunakan range(n). Fungsi tersebut menghasilkan nilai
dari 0 sampai n - 1, sehingga perulangan berjalan tepat sebanyak n kali.
```