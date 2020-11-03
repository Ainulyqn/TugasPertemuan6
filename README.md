# **Tugas ini untuk melengkapi pertemuan ke 6** <br>
# **Dan menjelaskan project**

![logo](poto/upb.png)

**Nama          : Ainul Yaqin** <br>
**NIM           : 312010423**<br>
**Kelas         : TI.20.A.1**<br>
**Mata Kuliah   : Bahasa Pemograman**

# **Lab 1**

Pada halaman ini (Tugas Pertemuan 6 - Lab 1) saya diberikan tugas oleh Dosen yaitu mempelajari operator aritmatika menggunakan bahasa Pemrograman pyhton. Berikut source code yang di berikan oleh dosen :

`#penggunaan end` <br>
`print('A', end='')` <br>
`print('B', end='')` <br>
`print('C', end='')` <br>
`print()` <br>
`print('X')` <br>
`print('Y')` <br>
`print('z')` <br>

`#Penggunaan separator`<br>
`w, x, y, z = 10, 15, 20, 25` <br>
`print(w, x, y, z)` <br>
`print(w, x, y, z, sep=',')` <br>
`print(w, x, y, z, sep='')` <br>
`print(w, x, y, z, sep=':')` <br>
`print(w, x, y, z, sep='.....')` <br>

Baik, berikutnya saya akan menjelaskan tentang materi yang diberikan oleh dosen.

* Penggunaan END Penggunaan end digunakan untuk menambahkan karakter yang dicetak di akhir baris. secara default penggunaan end adalah untuk ganti baris.

`print('A', end='')` <br>
`print('B', end='')` <br>
`print('C', end='')` <br>

`> Penggunaan print () digunakan untuk mencetak output, seperti syntax dibawah ini :`

`print()`

`>Syntax dibawah ini digunakan untuk menampilkan output berupa string`

`print('X')` <br>
`print('Y')` <br>
`print('z')` <br>

Hasil dari source code tersebut seperti gambar dibawah ini :

![lab1](poto/lab1.png)

* Penggunaan Separator

`>Pendeklarasian beberapa variable beserta nilainya`

`w,x,y,z=10,15,20,25` <br>
`>Menampilkan hasil dari variable tiap-tiap variable`

`print(w,x,y,z)` <br>
`>Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemisah : (koma)`

`print(w,x,y,z,sep=",")` <br>
`>Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemisah`

`print(w,x,y,z,sep="")` <br>
`>Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemisah : (titik dua)`

`print(w,x,y,z,sep=":")` <br>
`>Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemisah`

`print(w,x,y,z,sep="-----")`

* Hasil dari syntax / source code diatas adalah seperti berikut ini :

![separator](poto/separator.png)

* String Format

String formatting atau pemformatan string memungkinan kita menyuntikkan item kedalam string dari pada kita mencoba menggabungkan string menggunakan koma atau string concatenation.

* Penggunaan source code yang di berikan oleh dosen seperti berikut : <br>
![string](poto/format1.png)

`#string format 1`
`print(0, 10**0)` <br>
`print(1, 10**1)` <br>
`print(2, 10**2)` <br>
`print(3, 10**3)` <br>
`print(4, 10**4)` <br>
`print(5, 10**5)` <br>
`print(6, 10**5)` <br>
`print(8, 10**8)` <br>
`print(9, 10**9)` <br>
`print(10, 10**10)` <br>

`#string format 1`
`print('{0:>3} {1:>16}'.format(0, 10**0))` <br>
`print('{0:>3} {1:>16}'.format(1, 10**1))` <br>
`print('{0:>3} {1:>16}'.format(2, 10**2))` <br>
`print('{0:>3} {1:>16}'.format(3, 10**3))` <br>
`print('{0:>3} {1:>16}'.format(4, 10**4))` <br>
`print('{0:>3} {1:>16}'.format(5, 10**5))` <br>
`print('{0:>3} {1:>16}'.format(6, 10**6))` <br>
`print('{0:>3} {1:>16}'.format(7, 10**7))` <br>
`print('{0:>3} {1:>16}'.format(8, 10**8))` <br>
`print('{0:>3} {1:>16}'.format(9, 10**9))` <br>
`print('{0:>3} {1:>16}'.format(10, 10**10))` <br>

Saat ini saya akan membahas satu persatu dari syntax yang telah diberikan oleh Dosen.

**String Format 1**

Pada syntax / source code strring format satu akan menampilkan output berupa 2 outputan. <br>
Yang pertama (sebelah kiri) akan menampilkan angka urut dari angka 0 hingga 10, sedangkan untuk sebelah kanan akan menampilkan Operasi Aritmatika Pangkat.
Dengan ketentuan sebagai berikut, Operasi pangkat dengan angka kiri sebagai pokok (Rumus : ** [bintang dua] ) <br>
Hasil dari syntax tersebut adalah 10 pangkat 0, hingga 10 pangkat 10, dengan output sebagai berikut : <br>

![format](poto/format.png)

**String Format 2**

Pada syntax atau source code string format dua akan menampilkan output berupa 2 output'an juga (seperti String Format 1, yaitu kanan dan kiri ) <br>
Dengan ketentuan sebagai berikut :

Secara Default, **.format()** menggunakan rata kiri, angka ke kanan. kita dapat menggunakan opsi opsional <,^, atau > untuk mengatur perataan kiri, tengah, atau kanan. Contoh lain dalam penggunaan **.format()** sebagai berikut :

`print('{0:8} | {1:9}'.format('Nama orang','Jumlah'))` <br>
`print('{0:8} | {1:9}'.format('Ahmad',3.))` <br>
`print('{0:8} | {1:9}'.format('Wildan',10))` <br>

Hasil dari source code contoh diatas akan seperti berikut : <br>
![foto](poto/string.png)



