# Pertemuan 11 - Dictionary/Map

**Nama:** Nindia Najihatuz Zahro  
**NIM:** 2225250150  
**Kelas:** 3E

## Tujuan
Memodelkan data mahasiswa menggunakan dictionary dan pasangan key-value dalam Python.

## Struktur Data
Program menggunakan dictionary dengan NIM sebagai key utama. Setiap value berupa dictionary yang berisi nama, kelas, dan nilai mahasiswa.

## Cara Menjalankan
Jalankan perintah berikut pada terminal VS Code:

```bash
python praktik/data_mahasiswa.py
```

## Test Case

| Pengujian | Hasil Aktual | Status |
|---|---|---|
| Pencarian A003 | Data Citra ditemukan | Berhasil |
| Pencarian A999 | Data tidak ditemukan | Berhasil |
| Penambahan A006 | Data Fajar berhasil ditambahkan | Berhasil |
| Pembaruan nilai A002 | Nilai berubah menjadi 82 | Berhasil |
| Menampilkan seluruh data | Semua data mahasiswa tampil | Berhasil |
| Menghitung rata-rata | 83.50 | Berhasil |

## Refleksi
Kesalahan yang dapat terjadi pada dictionary adalah KeyError ketika mengakses key yang tidak tersedia. Untuk mengatasinya, program menggunakan method get() dan memeriksa hasil pencarian sebelum menampilkan data.
