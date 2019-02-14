# PRAKTIKUM 3
Alur algoritma latihan1.py, latihan2.py dan program latihan1.py

# ALUR ALGORITMA latihan1.py
Pengertian :
# *import*
Pada python import berfungsi untuk multi file maksudnya yaitu kita dapat memanggil file lain di dalam satu module yang berbeda.
# *random*
Fungsi ini akan mengembalikan bilangan float random x, dimana 0 < x < 1. Fungsi random() tidak memiliki parameter masukan.

Sebagai Contoh Kita akan membuat Latihan1.py, sebelum memulai membuat latihan1.py maka hal yang pertama harus membuka aplikasi sublime text untuk membuat script kodingan nya. Pastikan sudan menginstall sublimetext nya agar lebih mudah dalam pembuatan kodingan nya.

# PERTAMA
Seperti biasa kita akan membuat file dengan format python (py) menggunakan sublime text , dengan cara, buka sublime text , kemudian klik new files, kemudian simpan file dengan nama latihan1.py contoh gambar sebagai berikut :
# ![1](https://user-images.githubusercontent.com/46699723/52762406-09b3c400-304a-11e9-9d6b-24c32ad4ae6d.png)
# ![2](https://user-images.githubusercontent.com/46699723/52762407-0ae4f100-304a-11e9-9ac6-4ca45bfaf100.png)
# ![3](https://user-images.githubusercontent.com/46699723/52762409-0b7d8780-304a-11e9-9f60-0ad90db88c90.png)
# ![4](https://user-images.githubusercontent.com/46699723/52762411-0caeb480-304a-11e9-957f-2a79b8c749e6.png)

# KEDUA
Kemudian setelah kita menyimpan file nya kita akan membuat script nya di python sebagai berikut :

Untuk line 1 Sampai line 9 silahkan ketik seperti line dibawah ini

    print ("masukan nilai N: 5")

    import random

    jumlah = 5

     = 0

    for x in range(jumlah):

    i = random.uniform(.0,.5)

    a+=1

    print("data ke:",a,"==>", i)
Contoh Gambar script di sublime :
# ![a](https://user-images.githubusercontent.com/46699723/52762677-32888900-304b-11e9-8e20-092a5d3e6511.png)

# KETIGA
Baiklah kemudian kita kan mencoba membuka file script kita melalu cmd.
Jalankan Python seperti biasa melalui cmd maka hasilnya akan seperti gambar berikut.
# ![5](https://user-images.githubusercontent.com/46699723/52762943-4d0f3200-304c-11e9-9dbc-1dbd9fe82dbb.png)
Baiklah Kita telah selesai di latihan1.py kita kan lanjut ke latihan2.py.

# ALUR ALGORITMA latihan2.py
Baiklah kita akan membuat latihan2.py yang mana latihan ini membahas tentang cara menentukan nilai bilangan terbesar menggunankan syntax "max". kita akan mulai membuat scriptnya menggunakan sublime terlebih dahulu.

# PERTAMA
Seperti biasa kita akan membuat file dengan format python (py) menggunakan sublime text , dengan cara, buka sublime text , kemudian klik new files, kemudian simpan file dengan nama latihan2.py contoh gambar sebagai berikut :

# ![1](https://user-images.githubusercontent.com/46699723/52763233-9613b600-304d-11e9-89fe-e0bb0d0d51f7.png)
# ![2](https://user-images.githubusercontent.com/46699723/52763234-96ac4c80-304d-11e9-8b07-0827b9a54626.png)
# ![3](https://user-images.githubusercontent.com/46699723/52763236-96ac4c80-304d-11e9-817d-8f651bdec61f.png)
# ![part2](https://user-images.githubusercontent.com/46699723/52763238-9744e300-304d-11e9-8020-0473cc65f6ba.png)

# KEDUA
Kita akan membuat scriptnya di sublime dengan mengetikan syntax sebangai berikut :
Untuk line 1 Sampai line 8 silahkan ketik seperti line dibawah ini

    print("\nMenentukan BIlangan Terbesar")
    print("\n")

    max=0
    while True:
	    a=int(input("Masukan Bilangan :"))
	    if max < a:
		max = a
	if a==0:
		break
    print("Bilangan Terbesar = ", max)

Berikut contoh gambar nya :
# ![a](https://user-images.githubusercontent.com/46699723/52763662-4c2bcf80-304f-11e9-83c4-a3b6a647f570.png)

# KETIGA
Baiklah kita selesai membuat scriptnya, kita akan menjalankan nya di cmd, seperti biasa kita akan memanggil file nya.
berikut contoh gambarnya saat kita jalankan scriptnya di cmd :
# ![b](https://user-images.githubusercontent.com/46699723/52763910-569a9900-3050-11e9-8cb4-6607b77b1e77.png)
Baiklah kita telah selesai dengan latihan 2, kemudian kita akan melanjutkan nya di Program1.

# ALUR ALGORITMA Program1.py

# PERTAMA
Seperti biasa kita akan membuat file dengan format python (py) menggunakan sublime text , dengan cara, buka sublime text , kemudian klik new files, kemudian simpan file dengan nama program1.py contoh gambar sebagai berikut :

# ![1](https://user-images.githubusercontent.com/46699723/52764194-98780f00-3051-11e9-8e16-fcc74aa48787.png)
# ![2](https://user-images.githubusercontent.com/46699723/52764195-98780f00-3051-11e9-9f9e-366215c6869b.png)
# ![3](https://user-images.githubusercontent.com/46699723/52764196-9910a580-3051-11e9-9272-70386a79b13a.png)
# ![c](https://user-images.githubusercontent.com/46699723/52764197-99a93c00-3051-11e9-9f5e-385eb8103628.png)

# KEDUA
Kita akan melanjutkan nya dengan mengetik scriptnya di sublime text, berikut scriptnya :

	a = 100000000
	for x in range(1,9):
	    if(x>=1 and x<=2):
	        b=a*0
		print("Laba Bulan Ke-",x," :",b)
	    if(x>=3 and x<=4):
		c=a*0.1
		print("Laba Bulan Ke-",x," :",c)
	    if(x>=5 and x<=7):
		d=a*0.5
		print("Laba Bulan Ke-",x," :",d)
	    if(x==8):
		e=a*0.2
		print("Laba Bulan Ke-",x," :",e)
	total = b+b+c+c+d+d+d+e
	print("\nTotal : ", total)

Berikut contoh gambar scriptnya :
# ![dallas](https://user-images.githubusercontent.com/46699723/52764357-4edbf400-3052-11e9-9325-b4db8dbf2b17.png)

# KETIGA
Kita telah selesai membuat scriptnya, dan kita akan menjalankan scriptnya di cmd, berikut gambar hasilnya :
# ![selesai](https://user-images.githubusercontent.com/46699723/52764418-a712f600-3052-11e9-9fa7-3eee6d92b714.png)

Baiklah demikian step by step cara menyelasaikan tugas latihan1.py, latihan2.py, dan program1.py.

DAUD YUSUF EFENDI - 311810375
TI.18.A.1



