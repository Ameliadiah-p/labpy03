# labpy03

Nama    : Amelia Diah Parwati
Nim     : 312110134
Kelas   : TI.21.CA1
Mapel   : Bahasa Pemrograman

Latihan1.py

Program Sederhana Untuk Menampilkan N Bilangan Acak Yang Lebih Kecil Dari 0.5
A. Algoritma Program Untuk Menampilkan N Bilangan Acak Yang Lebih Kecil Dari 0.5
    1.  Masukan Jumlah N pengulangan
    2.  Proses pengulangan sesuai jumlah pengulangan yang dinputkan
    3.  Tampilkan pengulangan dengan nilai di bawah 0.5
    4.  Selesai
Setelah anda menegetahui Algoritma Dalam sebuah Program Maka Langkah Berikutnya Kita Membuat Flowchartnya. 
Berikut ini Flowchart Program

B.  Flowchart Program
    ![gambar1](flowchart1)

C.  Program Untuk Menampilkan N Bilangan Acak Yang Lebih Kecil Dari 0.5
    ![gambar1](program1)

==> Urutan Pembuatan Program
    1.  Ketikan Program print ('Tampilkan n Bilangan Acak yang Lebih Kecil Dari 0.5')
    2.  Ketikan Program jumlah=int(input("Masukan Jumlah N : "))
    3.  Ketikan Program import random
    4.  Ketikan Program for i in range ( jumlah ) :
    5.  Ketikan Program print("Data ke", 1+i,"=>", (random.uniform(0.1,0.5)))

==> Penjelasan Alur Program
    1.  print ('Tampilkan n Bilangan Acak yang Lebih Kecil Dari 0.5') 
        Untuk Menampilkan atau Mencetak kalimat. Tampilkan N Bilangan Acak yang Lebih Kecil Dari 0.5
    2.  jumlah=int(input("Masukan Jumlah N : ")) 
        Untuk menentukan jumlah input yang di inginkan sesuai tipe data    yaitu interger tipe data bilangan bulat
    3.  import random*
    4.  for i in range ( jumlah ) : Untuk Pengulangan dengan range jumlah
    5.  print("Data ke", 1+i,"=>", (random.uniform(0.1,0.5)))
        Untuk menampilkan atau mencetak urutan data sesuai jumlah inputan dengan hasil di bawah 0.5

Latihan2.py

A. Algoritma Program Untuk Menampilkan Bilangan Terbesar Dari N Buah Data Yang Dinputkan

    1.  mulai
    2.  input bilangan N
    3.  Jika max < a maka akan lanjut pengulangan 4.Jika a==0 maka akan berhenti proses pengulangan
    4.  Dan mencetak hasil nilai maxium dari N yang di isikan
    5.  Selesai
    
    Setelah anda menegetahui Algoritma Dalam sebuah Program Maka Langkah Berikutnya Kita Membuat Flowchartnya. Berikut ini Flowchart Program

B. Flowchart Program
    ![gambat1](flowchart2)

C. Program Untuk Menampilkan Bilangan Terbesar Dari N Buah Data Yang Dinputkan
    ![gambar1](program2)

==> Urutan Pembuatan Program
    1.  Ketikan Program print ('Menampilkan Bilangan Terbesar Dari N Buah Data Yang Diinputkan')
    2.  Ketikan Program max= 0
    3.  Ketikan Program while true:
    4.  Ketikan Program a=int(input("Masukan Bilangan :"))
    5.  Ketikan Program if max < a
    6.  Ketikan Program max=a
    7.  Ketikan Program if a==0:
    8.  Ketikan Program break
    9.  Ketikan Program print("Bilangan Tebesar Adalah :", max)

==> Penjelasan Alur Program
    1.  print ('Menampilkan Bilangan Terbesar Dari N Buah Data Yang Diinputkan') Untuk menampilkan kalimat
        Menampilkan Bilangan Terbesar Dari N Buah Data Yang Diinputkan
    2.  max= 0 kode max disini untuk menentukan nilai max nya adalah 0
    3.  while true: Untuk perulangan hingga waktu yang tidak di tentukan atau selamanya
    4.  a=int(input("Masukan Bilangan :")) a untuk menginput tipe data interger ( bilangan bulat )
    5.  if max < a max=a jika max kurang dari a maka max = a
    6.  if a==0: break jika a= 0 maka akan berhenti dengan syarat break yang terpenuhi
    7.  print("Bilangan Tebesar Adalah :", max) Menampilkan *Bilangan Tebesar Adalah : Nilai maximumnya

Program1.py

A. Algoritma Program Untuk Menghitung Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan
    1.  Mulai
    2.  Input modal misalkan x = 100.000.000 ( deklarasikan )
    3.  Input presentase untung a=0x, b=0x, c=0.01x, d=0.01x, e=0.05x, f=0.05x, g=0.05x, h=0.02x
    4.  For i in range (len (y)) pengulangan
    5.  Print (“laba bulan ke-“,i+1,”sebesar:” ,y[i])
    6.  Menghitung jumlah laba keseluruhan Z= (a+b+c+d+e+f+g+h)
    7.  Print (“jumlah laba selama 8 bulan adalah:”)
    8.  selesai

B.Flowchart Program
    ![txt](flowchart3)