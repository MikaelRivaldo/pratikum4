# Praktikum 2 - Modul Praktikum 2

Program sederhana dengan input tiga buah bilangan, dari ketiga bilangan tersebut tampilkan bilangan terbesarnya.

1. Cetak nilai bilangan 1 sampai 3 yang akan di input

> a = int(input("Masukan Bilangan 1 : "))  
> b = int(input("Masukan Bilangan 2 : "))  
> c = int(input("Masukan Bilangan 3 : "))  

2. Lalu buat kondisi if dan cetak hasil maksimal maks seperti dibawah ini.
Masukan a sebagai nilai maksimal, lalu masukan jika b adalah nilai maksimal maka b akan di cetak sebagai nilai terbesar begitu juga dengan c

> % digunakan sebagai pengganti untuk nilai numerik atau desimal.

> maks = a  
> if b > maks:  
>       maks = b  
> if c > maks:  
    maks = c  
    
> print()
> print('Nilai yang terbesar adalah : %d' % maks)  

3. Run program dengan 3 kondisi inputan yang berbeda

![gambar 1](https://user-images.githubusercontent.com/115770247/200644136-88f6d445-e083-4bd0-8ebe-b26d46907361.png)

![gambar 2](https://user-images.githubusercontent.com/115770247/200644361-1384cc54-2d1a-4908-8fa5-71af8107f22a.png)

![gambar 3](https://user-images.githubusercontent.com/115770247/200644381-b7c455dd-2d7e-4720-aeea-78dfa4e9dba3.png)

# Flowchart Praktikum 2 - Modul 2

Latihan 1 - Modul Praktikum 3

Membuat program bilangan acak yang lebih kecil dari 0.5

1. Cetak nilai bilangan yang akan di input
2. Gunakan fungsi import random terlebih dahulu

> jumlah = int(input("Masukkan nilai n : "))  
> import random  
> for i in range (jumlah) :  
    > print("Data ke", i+1,"=",(random.uniform(0.1,0.5)))  

3. Angka yang di input akan mencetak jumlah seberapa banyaknya nilai data ke print("Data ke", i+1,"=",(random.uniform(0.1,0.5)))  

4. Cetak dengan rumus i+1 untuk mencetak +1 setiap seberapa banyak nilai input yang dimasukkan

> (0.1,0.5) gunanya untuk membatasi angka acak dari 0,1 sampai 0,5

5. Jalankan program

![gambar 5](https://user-images.githubusercontent.com/115770247/200646393-08f0242b-6c45-499f-8324-6a4e1b2a226a.png)

# Latihan 2 - Modul Praktikum 3

Program menampilkan bilangan terbesar dari n buah data yang diinputkan dan masukkan angka 0 untuk berhenti

> max = 0  
> while True:  
    > a=int(input("Masukan bilangan : "))  
    > if max < a:  
        > max = a  
    > if a ==0 :  
        > break  

> print()  
> print("Bilangan terbesar adalah :", max)  

- Deklarasikan max = 0
- Masukan while True adalah perulungan tak terbatas
- Cetak input bilangan a=int(input("Masukan bilangan : "))
- Buat kondisi if max = a
- Gunakan angka 0 sebagai fungsi break, dengan menginput angka 0, maka program akan terhenti
- Cetak hasil bilangan terbesar dari kondisi max

# Program 1 - Modul Praktikum 3

Buat program sederhana dengan perulangan

> modal = 100000000  
> laba = 0  
> untung = 0  
> for i in range(1,9,1):  
    > if(i<3):  
        > laba = 0  
        > untung = untung + laba  
    > elif(i<5):  
     > laba = modal*1/100  
     > untung = untung + laba  
    > elif(i<8):  
     > laba = modal*5/100  
     > untung = untung + laba  
    > else:  
        > laba = modal*2/100  
        > untung = untung + laba  
    > print("Laba Bulan ke-",i," Sebesar = Rp.",laba)  
> print("Total Laba Adalah : ",untung)  

- Masukan integer

> modal = 100000000  
> laba = 0  
> untung = 0  

- Gunakan fungsi for for i in range(1,9,1):. Fungsi (1,9,1) adalah untuk membatasi angka dari 1 sampai 9, sedangkan ,1) untuk menambah 1 nilai setiap output dari Laba bulan ke -
- Buat kondisi if/elif/else (i<...) untuk mengubah status pada beberapa bulan ke -
- Buat rumus modal*.../100 dan untung = untung + laba
- Cetak hasil

> print("Laba Bulan ke-",i," Sebesar = Rp.",laba)  
> print("Total Laba Adalah : ",untung)  

-Terakhir, run program

# Latihan 1 - Struktur Kondisi

Program sederhada dengan input 2 buah bilangan, kemudian tentukan bilangan terbesar dari kedua bilangan tersebut menggunakan statement if.

# Menentukan bilangan yang lebih besar
> a = input("Masukan nilai a : ")  
> b = input("Masukan nilai b : ")  

> if a > b:  
    > print("Nilai", a ,"lebih besar dari", b)  
> else:  
    > print("Nilai", b ,"Lebih besar dari", a)  
    
 Hasil run program :
 
# Latihan 2 - Struktur Kondisi

Buat program untuk mengurutkan data berdasarkan input sejumlah data (minimal 3 variable input atau lebih), kemudian tampilkan hasilnya secara berurutan mulai dari data terkeciL.

# Mengurutkan 3 nilai dari terkecil ke terbesar

> print ("Masukkan 3 bilangan yang diinginkan!")  
> a = input("Bilangan 1 = ")  
> b = input("Bilangan 2 = ")  
> c = input("Bilangan 3 = ")  

> if a<b and a<c:  
    > if b < c:  
        > print(a, b, c)  
    > else:  
        > print(a, c, b)  
> elif b<a and b<c:  
    > if a<c:  
        > print(b, a, c)  
    > else:  
        > print(b, c, a)  
> else:  
    > if a<b:  
        > print(c, a, b)  
    > else:  
        > print(c, b, a)  
        
Run program

