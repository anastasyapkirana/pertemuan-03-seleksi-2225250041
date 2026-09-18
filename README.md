# Pertemuan 03 Seleksi Python
```
Nama: Anastasya Putri Kirana
NIM: 2225250041
Kelas: 3A
```
## Tujuan

Menulis program seleksi menggunakan if, if-else, kondisi majemuk, dan nested if.

## Cara Menjalankan

Jalankan program latihan dengan perintah:

```
python latihan/01_genap_ganjil.py
python latihan/02_bandingkan_dua_bilangan.py
python latihan/03_kelulusan_bersyarat.py
python latihan/04_jenis_segitiga.py
```
Jalankan Tugas 2 dengan perintah:

```
python tugas/analisis_persamaan_kuadrat.py
```

## Algoritma Tugas

1. Membaca koefisien a, b, dan c sebagai bilangan float.
2. Memeriksa apakah a sama dengan 0.
3. Jika a sama dengan 0, program menampilkan bahwa input bukan persamaan kuadrat.
4. Jika a tidak sama dengan 0, menghitung diskriminan dengan rumus D = b² - 4ac.
5. Jika diskriminan lebih besar dari 0, menghitung dan menampilkan dua akar real yang berbeda.
6. Jika diskriminan sama dengan 0, menghitung dan menampilkan satu akar real kembar.
7. Jika diskriminan kurang dari 0, program menampilkan bahwa tidak ada akar real.

## Hasil Pengujian

| No. | Input (a, b, c) | Hasil yang Diharapkan | Hasil Aktual | Status |
|---|---|---|---|---|
| 1 | (1, -5, 6) | Dua akar real: 3.00 dan 2.00 | Diskriminan = 1.00; x1 = 3.00, x2 = 2.00 | Berhasil |
| 2 | (1, 2, 1) | Akar real kembar: -1.00 | Diskriminan = 0.00; x = -1.00 | Berhasil |
| 3 | (1, 0, 1) | Tidak ada akar real | Diskriminan = -4.00; Persamaan kuadrat tidak memiliki akar real. | Berhasil |
| 4 | (0, 2, 3) | Bukan persamaan kuadrat | Bukan persamaan kuadrat. | Berhasil |

## Refleksi

Selama mengerjakan program, saya belajar menggunakan nested if untuk menentukan keputusan berdasarkan nilai diskriminan. Saya juga belajar bahwa setiap cabang program perlu diuji dengan test case yang berbeda agar logika program dapat dipastikan berjalan sesuai aturan.