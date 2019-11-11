# labspy03
TUGAS PRAKTIKUM 3

  LATIHAN 1

Menampilkan Bilangan Acak Yang Lebih Kecil Dari 0.5
Untuk menampilkan bilangan acak yang lebih kecil dari 0.5 dibutuhkan code seperti berikut:

![pych tgs 3](https://user-images.githubusercontent.com/44828458/68597293-4e806480-04cf-11ea-8684-eb3507a73a51.png)

(1). Pertama kita akan membuat perintah "num = int(input("masukkan bilangan: "))" untuk memasukkan nilai n yang diinginkan.

(2). Kedua adalah memasukkan variable dibawah, untuk menentukan jumlah data yang akan kita cari.

    jumlah = num+1
    start = 1
    stop = jumlah
    step = 1

(3). Ketiga adalah memasukkan perintah "for i in range(start, stop, step)", untuk memulai dan mengakhiri looping sesuai input start, stop dan step yang sudah kita masukkan tadi di langkah kedua.

(4). Keempat adalah memasukkan perintah "from random import random", agar bilangan yang ditampilkan adalah acak

(5). Masukkan perintah "a = random()" sebagai variable untuk menampilkan bilangan acaknya

(6). Terakhir adalah masukkan perintah "print("data ke:", i, "=>", (a)), untuk menampilkan hasil dari semua syntax yang sudah kita masukkan sebelumnya.

Berikut hasil eksekusi program diatas :

![pych tgs3 2](https://user-images.githubusercontent.com/44828458/68595634-6b676880-04cc-11ea-89ad-57ccb2607a05.png)

  LATIHAN 2

Menampilkan Bilangan Terbesar Dari N, Masukkan Bilangan 0 Untuk Berhenti

Untuk melakukan hal seperti judul diatas kita harus memasukkan code sebagai berikut :

![pypy 1](https://user-images.githubusercontent.com/44828458/68595819-cc8f3c00-04cc-11ea-8319-7e4055e10ef5.png)

Masukkan perintah " a = int() dan b = int()" untuk menyatakan bilangan bulat, nilai variable belum dimasukkan.

Lalu kita akan menggunakan statement while dan if :

    while a >= 0:
        a = int(input("Masukkan bilangan: "))
    if a == 0:
        break
    if a > b:
        b = a
    print("Bilangan terbesar adalah", b)

Keterangan : Ketika nilai a lebih dari 0, maka tampilkan input "masukkan bilangan: ". Ketika nilai a sama dengan 0 maka berenti menampilkan input "masukkan bilangan". Lalu a > b, b = a, akan mengambil nilai a terbesar untuk variable b.

Berikut hasil eksekusi program diatas :

![pych tgs3 3](https://user-images.githubusercontent.com/44828458/68596489-e3825e00-04cd-11ea-8cf7-a9f112f2498b.png)


  LATIHAN 3
  
  Menghitung Total Keuntungan

Jadi di latihan3 ini kita akan menghitung total keuntungan dari soal berikut : Seorang pengusaha menginvestasikan uangnya untuk memulai usaha dengan modal 100 juta, pada bulan 1 dan 2 belum menghasilkan laba. bulan ketiga mendapatkan laba sebesar 1%, dan pada bulan ke 5 pendapatan laba meningkat ke 5%, lalu pada bulan ke 8 mengalami penurunan sebesar 2%, sehingga laba menjadi 3%. Hitunglah keuntungan selama 8 bulan berjalannya usaha.

Nah untuk menghitung keuntungan usaha tersebut kira-kira beginilah codingnya :

![pypy 2](https://user-images.githubusercontent.com/44828458/68596753-4ecc3000-04ce-11ea-8901-a0abb337fafb.png)

Pertama kita akan memasukkan nilai ke variable "modal, laba dan untung", besar nilai dapat dilihat dalam code diatas.

Lalu kita akan menggunakan statement for dan if :

    for i in range (1, 9):
    if (i < 3):
        laba = 0
        untung = untung + laba
    elif (i < 5):
        laba = modal*1/100
        untung = untung + laba
    elif (i < 8):
        laba = modal*5/100
        untung = untung + laba
    else:
        laba = modal*2/100
        untung = untung + laba print("Laba bulan ke", i, "Sebesar:", laba) print("Total laba adalah :", untung)
 
 Berikut hasil eksekusi program diatas :
 
 ![pych tgs3 4](https://user-images.githubusercontent.com/44828458/68596504-e9783f00-04cd-11ea-912f-d1ea772ca8bc.png)




