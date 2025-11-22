# Praktikum5

## Penjelasan 

Program ini dibuat menggunakan Python dan memanfaatkan struktur data dictionary untuk menyimpan data mahasiswa. Program dapat menambah, mengubah, menghapus, menampilkan, dan mencari data mahasiswa melalui menu interaktif


Program ini bertujuan mengelola daftar nilai mahasiswa menggunakan dictionary, menyediakan menu interaktif yang dapat memudahkan pengguna dan menghitung nilai akhir berdasarkan bobot untuk tugas = 30%, UTS = 35%, UAS = 35%.

## 1. Struktur Data (Dictionary)

Data mahasiswa disimpan dalam dictionary dengan format berikut:

data = {
    "NIM": {
        "nama": "...",
        "tugas": nilai,
        "uts": nilai,
        "uas": nilai,
        "akhir": nilai
    }
}

Key utama = NIM mahasiswa

Value = dictionary berisi data nilai mahasiswa


Struktur ini dipilih karena:

Mudah diakses menggunakan kunci

Cocok untuk menyimpan data banyak mahasiswa

Mudah diubah dan dihapus



---

## 2. Perhitungan Nilai Akhir

Nilai akhir dihitung menggunakan rumus:

Nilai Akhir = 30% * Tugas + 35% * UTS + 35% * UAS

Dalam program ditulis sebagai:

akhir = round((0.30 * tugas) + (0.35 * uts) + (0.35 * uas), 2)

Fungsi round() digunakan agar nilai akhir hanya tampil 2 angka di belakang koma.

### Tampilan Program

