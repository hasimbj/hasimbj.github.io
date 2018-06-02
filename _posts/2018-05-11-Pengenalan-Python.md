---
layout: post
title:  "Pengenalan Python"
date:   2018-05-11 09:00 +0700
categories: programming
---

### Apa itu Python?

Python adalah salah satu bahasa tingkat tinggi yang dapat digunakan untuk membuat berbagai macam program seperti program CLI, program GUI, aplikasi desktop, web, IoT, dan lainnya. Python dikenal mudah dipelajari bagi pemula karena sintaksnya yang sederhana dan dokumentasinya yang bagus.

### Instalasi Python

Python tersedia untuk berbagai macam sistem operasi seperti Windows, GNU/Linux, Mac OS, dan lainnya. Python dapat diunduh di [https://python.org](https://python.org)

### Hello World

Sudah jadi tradisi setiap belajar bahasa pemrograman, pertama kali kita akan membuat program sederhana yakni menampilkan teks *Hello World!*, untuk menampilkan teks ke layar dengan bahasa python dapat menggunakan fungsi `print`.
~~~python
print('Hello World!)
~~~
> perintah tersebut akan menampilkan teks 'Hello World!' ke layar.

### Variabel

Untuk membuat variabel di python sangatlah mudah, kita tinggal menuliskan nama variable diikuti tanda sama dengan (=) kemudian nilai variable tersebut.
~~~python
nama = 'Hasim Budi Jatmiko'
usia = 21
PI = 3.14
buah = ['jeruk', 'melon', 'apel']
nilai = {1:'D', 2:'C', 3:'B', 4:'A'}
angka = (1, 2, 3)
benar = True
~~~

### Tipe Data

Python mendukung berbagai macam tipe data seperti string, integer, float, list, tuple, dictionary, boolean dan lainnya.
~~~python
# String diapit tanda petik, bisa itu single-quote , double quote, atau triple-quote
'Hasim Budi'
"Sofia"
""" Ini adalah string,
biasanya triple-quote digunakan untuk dokumentasi program """

# Integer
100

# Float
3.14

# List
['Hasim', 21, 'Laki-Laki', 'Purworejo']

# Tuple
(255, 0, 0)

# Dictionary
{nama: 'Hasim', usia: 21, alamat: 'Purworejo'}

# Boolean
True dan False
~~~

### Komentar

Komentar di python menggunakan tanda pagar (#)
~~~python
# Ini adalah komentar
# Fungsi untuk menjumlahkan 2 nilai
def jumlah(a, b):
    return a + b
~~~

### Fungsi

Untuk membuat fungsi di python kita bisa menggunakan keyword `def` diikuti nama fungsi, berikut contoh pembuatan fungsi di python.
~~~python
def luas_lingkaran(r):
    luas = 3.14 * r * r
    return luas

luas_lingkaran(12) # menghitung luas lingkaran dengan jari-jari (r) 12
~~~

> fungsi diatas menghitung berapa luas lingkaran sesuai input jari-jari yang dimasukkan ke parameter r

### Kondisional

Untuk menangani pernyataan kondisional dapat dilakukan dengan `if .. else ..`.
~~~python
nilai = 80

if nilai >= 75:
    print('Lulus')
else:
    print('Tidak Lulus')
~~~

### Perulangan

Untuk melakukan looping atau perulangan, dapat menggunakan `for` ataupun `while`.
~~~python
for i in range(1,11):
    print(i) # menampilkan angka 1 sampai 10

# menampilkan angka 0 sampai 14
start = 0
while start < 15:
    print(start)
    start += 1
~~~

### Kelas

Python merupakan bahasa pemrograman berorientasi objek (object-oriented programming), untuk berurusan dengan objek, atau membuat blueprint dari objek kita menggunakan keyword `class` diikuti nama kelas untuk pembuatan kelas.
~~~python
class Karyawan:
    def __init__(self, nama, bagian):
        self.nama = nama
        self.bagian = bagian

# Instansiasi objek
karyawan1 = Karyawan('Hasim', 'Produksi')
karyawan1.nama # mengakses atribut nama
karyawan1.bagian # mengakses atribut bagian
~~~

Masih banyak hal yang dapat dipelajari, python mempunyai banyak sekali library yang menarik untuk dipelajari.
Sekian postingan pengenalan bahasa pemrograman python, semoga bermanfaat.
    