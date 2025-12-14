# Kalkulator Aman

Program **Kalkulator Aman** adalah program Python sederhana untuk latihan **penanganan eksepsi (exception handling)** agar input pengguna tetap aman.

---

## Tujuan

* Membuat kalkulator sederhana
* Melatih penggunaan `try` dan `except`
* Mencegah error akibat input tidak valid

---

## Konsep yang Digunakan

* Function (`def percobaan()`)
* Input & output
* Tipe data `float`
* Exception handling (`try`, `except`, `ValueError`)

---

## Cara Kerja Program

1. Program menampilkan judul
2. Pengguna memasukkan angka
3. Program mengecek input
4. Jika input bukan angka, muncul pesan error

---

## Cara Menjalankan

1. Simpan file dengan nama `kalkulator_aman.py`
2. Jalankan perintah:

   ```bash
   python kalkulator_aman.py
   ```

---

## Contoh Error

```
Masukkan angka pertama: abc
Error: Input harus berupa angka!
```

---

## Struktur Program

```
percobaan()
 ├─ tampilkan judul
 ├─ input angka (try)
 └─ pesan error (except)
```

---

