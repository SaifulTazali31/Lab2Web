# Lab2Web
# praktikum 2
Nama    : Saiful Tazali 

Nim     : 311910625

Kelas   : TI.19.C1
# 1.MEMBUAT DOKUMEN HTML
Buatlah dokumen HTML seperti berikut
![gambar1](https://user-images.githubusercontent.com/81814954/114268712-bfada980-9a2c-11eb-90a3-d37e316233a6.png)

#  2. Mendeklarasikan CSS Internal

Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen.


![gambar2](https://user-images.githubusercontent.com/81814954/114268802-42ceff80-9a2d-11eb-98d1-67635b9a43f3.png)


Inilah tampilanya 

![gambar3](https://user-images.githubusercontent.com/81814954/114268844-790c7f00-9a2d-11eb-8212-2ddaa07af1d8.png)


# 3. Menambahkan Inline CSS
Kemudian tambahkan deklarasi inline CSS pada tag <p> seperti berikut.
  ![gambar4](https://user-images.githubusercontent.com/81814954/114268925-0a7bf100-9a2e-11eb-9951-0f3c07f0a8c5.png)


![gambar5](https://user-images.githubusercontent.com/81814954/114268950-36977200-9a2e-11eb-8f67-86f62ae977dd.png)


# 4. Membuat CSS Eksternal
Buatlah file baru dengan nama style_eksternal.css kemudian buatlah deklarasi CSS seperti berikut.


![gambar6](https://user-images.githubusercontent.com/81814954/114269027-b0c7f680-9a2e-11eb-999e-ac264eb2abde.png)


![gambar7](https://user-images.githubusercontent.com/81814954/114269056-da811d80-9a2e-11eb-921b-5d28e5f6646a.png)



![gambar8](https://user-images.githubusercontent.com/81814954/114269089-fc7aa000-9a2e-11eb-8463-3d1986cd495f.png)


# 5. Menambahkan CSS Selector
Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file
style_eksternal.css, tambahkan kode berikut.
![gambar9](https://user-images.githubusercontent.com/81814954/114269122-3481e300-9a2f-11eb-86db-57216aeb199d.png)


![gambar10](https://user-images.githubusercontent.com/81814954/114269132-44012c00-9a2f-11eb-9975-aaf7fd050d4b.png)


# Pertanyaan dan tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

membuat margin
![gambar11](https://user-images.githubusercontent.com/81814954/114270255-89c0f300-9a35-11eb-96f6-112683a3e5c9.png)


2.Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!


Pada pendeklarasian CSS elemen h1 mengubah tampilan seluruh elemen yang memiliki tag h1, sedangkan #intro h1 hanya mengubah tampilan elemen h1 yang memiliki id #intro.


3.Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!



Pendeklarasikan CSS pada elemen yang sama namun dengan isi deklarasi yang berbeda, maka semua deklarasi CSS tersebut akan ditampilkan. Namun jika isi dari ketiga deklarasi CSSnya sama semua, maka browser hanya akan menampilkan salah satunya, dengan urutan Inline CSS, Eksternal CSS, dan yang terakhir Internal CSS.



4.Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! (
).



Kedua deklarasi tersebut akan tampil, namun selector ID yang akan tampil jika deklarasinya ada yang sama antara ID dan Class.





