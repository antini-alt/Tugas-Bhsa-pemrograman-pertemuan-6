# Tugas-Bhsa-pemrograman-pertemuan-6
Repository ini dibuat untuk memenuhi tugas bahasa pemrograman pertemuan ke 6
 
 Nama  : Antini permatasari
 
 NIM   : 312010095
 
 Kelas : TI.20.B.1<br><br>
 
 DAFTAR ISI <br>
 | No | Description | Link |
 | ----- | ----- | ---- |
 | 1  | Tugas pertemuan 5 | [Tugas_pertemuan_5](#pertemuan6_smt1#pertemuan-5---tugas)
 | 2  | Tugas pertemuan 6 Lab 1 | [Tugas_part6_Lab1](#pertemuan-6---Lab-1)
 | 3  | Tugas pertemuan 6 Lab 2 | [Tugas_part6_Lab2](#pertemuan-6---Lab-2)
 <br>
 
 ## pertemuan 5 - Tugas
 
 pada pertemuan 5 Bahasa pemograman saya diberi tugas oleh Dosen membuat Aplikasi Biodata python (seperti)
 ![tugas_5](picture/tugas_5.PNG) <br>
 saat ini saya akan menjelaskan hasil dari tugas tersebut.<br>
 Berikut *source code* nya atau link berikut ( [tugas pertemuan 5](p5.tugas.py) ): <br>
 ```python
print("please enter full name : ")
fullname=input()

print("please insert your Nickname : ")
nickname=input()

print("please enter your NPM : ")
NPM=input()

print("please enter your Born place : ")
bornplace=input()

print("please insert your age : ")
age=input()

print("please enter yuor home address : ")
address=input()

print("pleace enter your phone number : ")
phonenumber=input()


print("\nAssalammualaikum wr, wb.")
print(f"\nLet me introduce my self. My name is{fullname}, but you can call me(nickname). My NPM is{NPM}. I was Born in {bronplace} and i am {age} years old. I am very glad if you want to invite my house in {address}. So, don't forget to call me before with the number {phonenumber}.")
print("\nThank you.")
print("\n")
``` python
berikut penjelasan : <br>
``` python







``` 
source code diatas berfungsi untuk mencetak hasil / output berupa "*please enter full name :*" <br>
untuk menampilkan input string, saya menggunakan *tanda petik dua* didalam fungsi input(), sedangkan jika saya ingin menampilkan output/hasil berupa angka/interger saya tidak perlu menggunakan *tanda petik dua*. contohnya :
```python
fullname=input()
```
ket : <br>
-Variable adalah sebuah wadah penyimpanan data pada program yang akan digunakan selama program itu berjalan yang berfungsi sebagai variable dalam source code diatas adalah *fullname*.
-Fungsi *input()* adalah untuk memasukan nilai dari layar console di command prompt, lalu kemudian mengembalikan nilai saat  



<br>
sekarang saya akan membahas satu persatu syntax yang telah diberikan oleh Dosen.<br>

1. string format 1<br>
pada syntax / source code string format 1 akan menampilkan output 2 outputan.<br>
yang pertama (sebelum kiri) akan menampilkan angka urut dari angka 0 hingga angka 10, sedangkan untuk sebelah kanan akan menampilkan operasi Aritmatika pangkat.<br>
Dengan ketentuan, Operasi pangkat dengan angka kiri sebagai pokok (Rumus : **[bintang dua] )<nr>
Hasil dari syntax tersebut adalah 10 pangkat 0, hingga 10 pangkat 10, dengan output sebagai berikut : <br>
![Operasi Aritmatika pangkat]()

2. string format 2<br>
pada syntax / source code string fomat 2 akan menampilkan output 2 output'an juga, (seperti string format 1, yaitu kanan dan kiri )<br>
Dengan ketentuan : <br>
> Alignment, padding, dan procesion dengan **format()** dalam kurung kurawal kita dapat menetapkan panjang bidang, rata kanan atau kiri, paramenter pembulatan dan banyak lagi. contoh lain seperti berikut :
```python
 