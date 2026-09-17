# Pertemuan-03-seleksi-2225250113

| **Keterangan** | **Data** |
|---|---|
| **Nama** | Masya Bantani |
| **NIM** | 2225250113 |
| **Kelas** | 3-E |
| **Jurusan** | Pendidikan Matematika |

## **Tujuan Repositori**

Repositori ini dibuat untuk mengumpulkan hasil latihan dan tugas praktik Python pada materi seleksi. Melalui latihan dan tugas ini, saya mempelajari penggunaan ```if, if-else,``` kondisi majemuk menggunakan operator logika, serta nested ```if``` untuk membuat keputusan berdasarkan kondisi tertentu.

## **Daftar Berkas dan Fungsinya**

| **Berkas**                      | **Fungsi**                                                                                 |
| ------------------------------- | ------------------------------------------------------------------------------------------ |
| `01_genap_ganjil.py`            | Menentukan apakah suatu bilangan merupakan bilangan genap atau ganjil.                     |
| `02_bandingkan_dua_bilangan.py` | Membandingkan dua bilangan dan menentukan hubungan kedua bilangan tersebut.                |
| `03_kelulusan_bersyarat.py`     | Menentukan status kelulusan berdasarkan nilai akhir dan persentase kehadiran.              |
| `04_jenis_segitiga.py`          | Menentukan jenis segitiga berdasarkan panjang ketiga sisinya.                              |
| `analisis_persamaan_kuadrat.py` | Menganalisis persamaan kuadrat berdasarkan nilai diskriminan dan menentukan jenis akarnya. |
| `README.md`                     | Berisi dokumentasi repositori dan hasil pengujian program.                                 |

## **Cara Menjalankan Program**

Program dijalankan melalui Terminal pada folder utama repositori.

**Contoh Menjalankan Latihan**

```text
python3 latihan/01_genap_ganjil.py
python3 latihan/02_bandingkan_dua_bilangan.py
python3 latihan/03_kelulusan_bersyarat.py
python3 latihan/04_jenis_segitiga.py
```

**Menjalankan Tugas Utama**

```python3 tugas/analisis_persamaan_kuadrat.py```

Setelah program dijalankan, masukkan nilai sesuai pertanyaan yang muncul pada Terminal.

## **Hasil Pengujian Tugas Utama**

Program `analisis_persamaan_kuadrat.py` diuji menggunakan empat test case wajib.

| **Kasus** | **Input (a, b, c)** | **Keluaran yang Diharapkan** | **Keluaran Aktual**          | **Status** |
| --------- | ------------------- | ---------------------------- | ---------------------------- | ---------- |
| 1         | 1, -5, 6            | Dua akar real: 3.00 dan 2.00 | Dua akar real: 3.00 dan 2.00 | Berhasil   |
| 2         | 1, 2, 1             | Akar kembar: -1.00           | Akar kembar: -1.00           | Berhasil   |
| 3         | 1, 0, 1             | Tidak ada akar real          | Tidak ada akar real          | Berhasil   |
| 4         | 0, 2, 3             | Bukan persamaan kuadrat      | Bukan persamaan kuadrat      | Berhasil   |

Keempat test case menghasilkan keluaran yang sesuai dengan kondisi persamaan kuadrat berdasarkan nilai diskriminan.

## **Exit Ticket**

1. Perbedaan penting antara if dan if-else adalah if hanya menjalankan perintah ketika kondisi bernilai benar, sedangkan if-else menyediakan pilihan lain ketika kondisi bernilai salah.
2. Kesalahan logika yang paling mudah saya lakukan adalah salah menggunakan operator perbandingan, terutama membedakan > dengan >=.
3. Test case 59, 60, dan 61 membantu saya memahami batas kelulusan karena masing-masing mewakili nilai di bawah batas, tepat pada batas, dan di atas batas.

## **Refleksi**

Dari latihan dan tugas ini, saya memahami cara menggunakan percabangan dalam Python dengan if, if-else, kondisi majemuk, dan nested if. Saya juga memahami penggunaan operator perbandingan seperti ==, >, >=, serta operator logika and dan or untuk membuat keputusan dalam program.
Kesalahan yang saya temukan adalah penggunaan operator perbandingan yang kurang tepat pada kondisi tertentu. Saya memperbaikinya dengan memperhatikan kembali aturan yang diberikan dan melakukan pengujian menggunakan beberapa nilai batas.
Pada pertemuan berikutnya saya ingin lebih memahami penggunaan percabangan dan menggabungkannya dengan konsep Python lainnya agar dapat membuat program dengan kondisi yang lebih kompleks.
