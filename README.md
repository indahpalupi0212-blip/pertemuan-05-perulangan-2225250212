# Pertemuan 05 Perulangan Python

- Nama: Indah Palupi Kusumaningrum
- NIM: 2225250212
- Kelas: 3F


## Tujuan

Menggunakan perulangan `for` dan `while` untuk menyelesaikan masalah iteratif, melakukan validasi input, menghitung nilai menggunakan proses berulang, serta memahami kondisi berhenti pada perulangan dalam Python.

## Cara Menjalankan

### Latihan 1 - Tabel Perkalian

```bash
python3 latihan/01_tabel_perkalian.py
```

### Latihan 2 - Jumlah Bilangan

```bash
python3 latihan/02_jumlah_bilangan.py
```

### Latihan 3 - Validasi Input

```bash
python3 latihan/03_validasi_input.py
```

### Latihan 4 - Menghitung Bilangan Genap

```bash
python3 latihan/04_hitung_genap.py
```

### Kuis 2 - Deret Aritmetika

```bash
python3 kuis/kuis2_deret_aritmetika.py
```

## Algoritma Kuis 2

1. Membaca nilai suku pertama (`a`) dan beda (`d`).

2. Membaca banyak suku (`n`).

3. Jika nilai `n` kurang dari atau sama dengan 0, program meminta pengguna memasukkan nilai `n` kembali sampai valid.

4. Menginisialisasi variabel `total` dengan nilai 0.

5. Menggunakan perulangan `for` sebanyak `n` kali.

6. Pada setiap iterasi, menghitung nilai suku ke-i menggunakan rumus:

   ```
   suku = a + i * d
   ```

7. Menampilkan nomor suku dan nilainya.

8. Menambahkan nilai suku ke dalam variabel `total`.

9. Setelah perulangan selesai, menampilkan jumlah seluruh suku deret.

## Hasil Pengujian

### Latihan 1 - Tabel Perkalian

| Input  | Keluaran yang Diharapkan          | Keluaran Aktual | Status   |
| ------ | --------------------------------- | --------------- | -------- |
| n = 4  | Tabel perkalian 4 sampai 4 × 10   | Sesuai          | Berhasil |
| n = -3 | Tabel perkalian -3 sampai -3 × 10 | Sesuai          | Berhasil |

### Latihan 2 - Jumlah Bilangan

| Input  | Keluaran yang Diharapkan | Keluaran Aktual | Status   |
| ------ | ------------------------ | --------------- | -------- |
| n = 1  | Jumlah = 1               | Sesuai          | Berhasil |
| n = 5  | Jumlah = 15              | Sesuai          | Berhasil |
| n = 10 | Jumlah = 55              | Sesuai          | Berhasil |

### Latihan 3 - Validasi Input

| Input         | Keluaran yang Diharapkan        | Keluaran Aktual | Status   |
| ------------- | ------------------------------- | --------------- | -------- |
| 120 → -5 → 75 | Menolak 120 dan -5, menerima 75 | Sesuai          | Berhasil |

### Latihan 4 - Menghitung Bilangan Genap

| Input  | Keluaran yang Diharapkan | Keluaran Aktual | Status   |
| ------ | ------------------------ | --------------- | -------- |
| n = 1  | 0                        | Sesuai          | Berhasil |
| n = 5  | 2                        | Sesuai          | Berhasil |
| n = 10 | 5                        | Sesuai          | Berhasil |

### Kuis 2 - Deret Aritmetika

| Input (a, d, n) | Jumlah yang Diharapkan | Keluaran Aktual | Status   |
| --------------- | ---------------------- | --------------- | -------- |
| 2, 3, 5         | 40                     | Sesuai          | Berhasil |
| 10, -2, 4       | 28                     | Sesuai          | Berhasil |
| 1.5, 0.5, 3     | 6.0                    | Sesuai          | Berhasil |

## Refleksi

Pada saat mengerjakan tugas ini, saya memahami perbedaan penggunaan perulangan `for` dan `while`. Perulangan `for` lebih sesuai digunakan ketika jumlah iterasi sudah diketahui, sedangkan `while` digunakan ketika proses bergantung pada suatu kondisi tertentu.

Kesalahan yang sempat saya temui adalah penggunaan batas perulangan yang kurang tepat pada fungsi `range()`, sehingga jumlah iterasi tidak sesuai dengan yang diharapkan. Kesalahan tersebut dapat diperbaiki dengan memeriksa kembali nilai awal, nilai akhir, dan langkah (step) pada perulangan.

Melalui latihan dan kuis ini, saya menjadi lebih memahami konsep iterasi, kondisi berhenti, validasi input berulang, akumulasi nilai, serta cara menguji program menggunakan beberapa test case sebelum melakukan commit dan push ke GitHub.
