# praktikum12
Nama  : Muhamad David Ali

NIM   :312210291

Kelas : TI 22 A1

# String 
- String adalah jenis yang paling populer di Python. 
-Untuk membuatnya hanya dengan melampirkan 
karakter dalam tanda kutip. 
- Python memperlakukan tanda kutip tunggal sama 
dengan tanda kutip ganda. 
- Membuat string semudah memberi nilai pada sebuah 
variabel.


# Latihan 1
~~~
txt = 'Hello World'
~~~
- Hitung jumlah karakternya
- Ambil karakter terakhir
- Ambil karakter index ke-2 sampai index ke-4 (llo)
- Hilangkan spasi pada text tersebut (HelloWorld)
- Ubah text menjadi huruf besar
- Ubah text menjadi huruf kecil
- Ganti karakter H dengan karakter J

#
- Hitung jumlah karakternya.
untuk meghitung jumlah kerakter kita gunakanlah ' len() '
~~~
txt = 'Hello World'
jumlah_karakter = len(txt)
print ("jumlah karakternya adalah  : ",jumlah_karakter)
~~~
Input dan dan hasil runnya :
![Screenshot](https://user-images.githubusercontent.com/116184002/209442101-3cf183a2-3de2-48c4-86bd-9d9ed725c474.png)
-----
- Ambil karakter terakhir 
karakter terakhir dari 'Hello World' adalah 'd' cara mengambilnya 
~~~
txt = 'Hello World'
print ("txt[10]: ",txt[10])
~~~
'txt' adalah string yang kita buat '[10]' adalah urutan terakhir karena karakter dihitung dari 0
![Screenshot](https://user-images.githubusercontent.com/116184002/209442404-eb123c48-269d-493c-8f15-32ff2759c195.png)
-----
- Ambil karakter index ke-2 sampai index ke-4 (llo)
~~~
txt = 'Hello World'
print ("txt[2:5]: ",txt[2:5])
~~~
![Screenshot](https://user-images.githubusercontent.com/116184002/209442563-b125fb91-1089-4872-852d-ceff3e1e755f.png)
-----
- Hilangkan spasi pada text tersebut (HelloWorld)
~~~
txt = 'Hello World'
hilangkan_spasi = txt.replace(" ","")
print (hilangkan_spasi)
~~~
![Screenshot](https://user-images.githubusercontent.com/116184002/209442698-f0bcf48b-15b9-4385-ab13-57c3d8286b9b.png)
-----
- Ubah text menjadi huruf besar
untuk merubah semua karakter 'Hello World' menjadi kapital semua menggunakan 'upper()' 
~~~
txt = 'Hello World'
print (txt.upper())
~~~
![Screenshot](https://user-images.githubusercontent.com/116184002/209442787-79ff0257-f074-48b4-a767-81a3623f39e2.png)
-----
- Ubahlah text menjadi huruf kecil
untuk mengubah text yang tadiya kapital semua menjadi huruf kecil menggunakan 'lower()'
~~~
txt = 'Hello World'
print (txt.upper())
print (txt.lower())
~~~
![Screenshot](https://user-images.githubusercontent.com/116184002/209442916-c9d7b8c0-fc4f-4487-9d64-8eccda1fa762.png)
-----
- Mengganti karakter H menjadi J 
~~~
txt = 'Hello World'
print (txt.replace('H','J'))
~~~
![Screenshot](https://user-images.githubusercontent.com/116184002/209443019-d5ed5a6e-156e-4961-bb5d-2fc801bef5fe.png)
-----


# Latihan 2
~~~
umur = 24
txt = "Hello, nama saya john, dan umur saya adalah {0} tahun"
print (txt.format(umur))
~~~
![Screenshot (49)](https://user-images.githubusercontent.com/116184002/209869174-f4178e07-3282-4c41-b61a-c92890a7f093.png)


