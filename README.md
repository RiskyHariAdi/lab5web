| Nama      | Risky HariAdi |
| ----------- | ----------- |
| NIM     | 312010124       |
| Kelas   | TI.20.A.1        |

## Langkah langkah praktikum 5
Persiapan membuat dokumen HTML dengan nama file lab5_javascript.html seperti berikut.

![foto!](foto/1.png)

![foto!](foto/11.png)

## 1. Javascript Dasar
Pemakaian Alert sebagai property window

![foto!](foto/2.png)

Hasilnya
![foto!](foto/hasil2.png)
Pemakaian method dalam objek

![foto!](foto/3.png)

Hasilnya
![foto!](foto/hasil3.png)

Pemakaian Prompt

![foto!](foto/4.png)
![foto!](foto/41.png)
Hasilnya
![foto!](foto/hasil4.png)

Pembuatan fungsi dan cara pemanggilannya

![foto!](foto/5.png)

Hasilnya

![foto!](foto/hasil5.png)
## 2. Dasar Pemrograman Di Javascript
Operasi dasar aritmatika

![img2!](foto/6.png)

Hasilnya
![foto!](foto/hasil6.png)

Seleksi kondisi (if..else)

disini saya memasukkan data 90

![img2!](assets/img/2/1-22.png)

Penggunaan operator switch untuk seleksi kondisi

![img2!](assets/img/2/1-3.png)

![img2!](assets/img/2/1-33.png)

## 3. pembuatan Form
Form input

saya coba input nilai 8

![img3!](assets/img/3/1.png)

Form button

![img3!](assets/img/3/2.png)

![img3!](assets/img/3/2-1.png)

## 4. HTML DOM
Pilihan menggunakan checkBox dengan perhitungan otomatis

![img4!](assets/img/4/1.png)

## Pertanyaan dan Tugas
1. Buat script untuk melakukan validasi pada isian form

## Jawab

Membuat validasi nama, no.telp, Email

## 1. Nama
Saya akan memberikan Validasi berupa inputan hanya boleh mengguankan Huruf/Alphabet saja. Contoh: Fajar (benar), Fajar02 (salah).

![imgpraktikum!](assets/img/praktikum/1-1.png)

Penjelasan
- Pertama membuat nama function Alphabet, dengan parameter dinamis yaitu (nilai, pesan).
- Data yang boleh dimasukkan adalah berupa "a-zA-Z".
- Jika selain data "a-zA-Z" ini dimasukkan, maka akan muncul pesan Alert "alert(pesan);"

![imgpraktikum!](assets/img/praktikum/1.png)

## 2. No.Telp
Pada bagian ini akan saya berikan validasi berupa hanya angka saja yang boleh di inputkan, contoh: 12345 (benar), 123AB (salah).

![imgpraktikum!](assets/img/praktikum/2.png)

Penjelasan:
- var numberExp = /^[0-9]+$/; merupakan variabel numberExp yang diberi batasan validasi angka 0-9
- Arti Match pada "if(nilai.value.match(numberExp))" adalah string.match(), mencari string menggunakan Regular Expression (Regex)
- Jika salah atau inputan tidak benar maka akan ada pesan alert "alert(pesan);"

![imgpraktikum!](assets/img/praktikum/2-1.png)

## 3. Email
Pada email akan diberikan validasi masih berupa Regular Expression. Contoh: fajar.agngn@gmail.com (benar), fajar.agngn@gmail. (salah).

![imgpraktikum!](assets/img/praktikum/3.png)

Penjelasan:
- membuat variabel email " var email = /^([a-zA-Z0-9_.+-])+@(([a-zA-Z0-9-])+.)+([a-zA-Z0-9]{2,4})+$/; " berupa huruf, angka dan simbol yang diperbolehkan dalam input sebuah email. Jika email salah maka akan ada pesan alert "alert(pesan);"

![imgpraktikum!](assets/img/praktikum/3-1.png)

## Berikut penulisan form yang benar

![imgpraktikum!](assets/img/praktikum/4.png)
