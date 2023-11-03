
# Panduan Menjalankan Unit Test Python

Ini adalah panduan sederhana untuk menjalankan unit test pada contoh kode Python menggunakan modul `unittest`. Kode di bawah ini adalah contoh unit test yang menguji fungsi `sum` pada list dan tuple.

## Instalasi

1. Pastikan Anda telah menginstal Python di komputer Anda. Anda dapat mengunduhnya dari [situs resmi Python](https://www.python.org/downloads/).

2. Klon repositori ini atau unduh file `test_perhitungan.py`.

```
bash
git clone https://github.com/username/nama-repositori.git
# atau
wget https://raw.githubusercontent.com/username/nama-repositori/main/test_perhitungan.py
```

3. Anda juga perlu memastikan Anda memiliki modul `unittest` yang sudah tersedia di instalasi Python Anda.

## Menjalankan Unit Test

1. Buka terminal atau command prompt.

2. Pindah ke direktori tempat file `test_perhitungan.py` disimpan.

3. Jalankan unit test dengan perintah berikut:

```bash
python test_perhitungan.py
```

Anda akan melihat hasil pengujian muncul di layar. Jika semua test cases berhasil, Anda akan melihat pesan "OK". Jika ada yang gagal, Anda akan mendapatkan pesan kesalahan yang akan membantu Anda mengidentifikasi masalah dalam kode.

## Penjelasan Kode

- `test_sum`: Test case ini menguji fungsi `sum` untuk list `[1, 2, 3]`. Hasil seharusnya adalah 6.

- `test_sum_tuple`: Test case ini menguji fungsi `sum` untuk tuple `(2, 2, 2, 2)`. Hasil seharusnya adalah 8.

## Kontribusi

Jika Anda menemukan masalah atau ingin berkontribusi pada proyek ini, jangan ragu untuk membuat pull request atau melaporkan masalah di [GitHub repository](https://github.com/username/nama-repositori).

Terima kasih telah menggunakan panduan ini. Semoga bermanfaat!