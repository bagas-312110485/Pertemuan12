# Pertemuan12

pada pertemuan 12 saya diberi soal :

![Gambar 1](png/Tugas.png)

## Diagram Class

![Gambar 2](png/diagramClass.png)

## Flowchart

Untuk Flowchart bisa di akses [Flowchart](Flowchart.pdf)

## PROGRAM

pertama saya membuat sebuah class daftar nilai

````py
    class daftarNilai()
````

Lalu saya melanjutkan dengan membuat method method fungsinya

````py
    def tambah(self)
    def ubah(self)
    def lihat(self)
    def hapus(self)
````

lalu saya mengisi setiap method dengan elemen elemen nya

````py
    nama= input("masukan nama: ")
    nim= input("masukan nim :")                                         
    nilaiTugas= int(input("Masukkan Nilai Tugas: "))
    nilaiUts= int(input("Masukkan Nilai UTS\t: "))            
    nilaiUas= int(input("Masukkan Nilai UAS\t: "))             
    nilaiAkhir= (0.30 * nilaiTugas) + (0.35 * nilaiUts) + (0.35 * nilaiUas)
    dt[nama]=nim,nilaiTugas,nilaiUts,nilaiUas,nilaiAkhir
````

lalu saya membuat sebuah looping

````py
    while True:
        input('tambah   (1)
            ubah     (2)
            lihat    (3)
            hapus    (4)
            ')
            c = input("\nsilahkan masukan pilihan : ")
````

dan terakhir membuat fungsi if else untuk menjalankan method

````py
    if (c=="1"):
        data.tambah()
    elif (c=="2"):
        data.ubah()
    elif (c=="3"):
        data.lihat()
    elif (c=="4"):
        data.hapus()
    else:
        data.keluar()
        break
````

## Code Program
Untuk Code program bisa di akses [Program](Class.py)

## Output

ini adalah output apabila memilih tambah(1)

![Gambar 3](png/1.png)

ini adalah output apabila memilih ubah(2)

![Gambar 4](png/2.png)

ini adalah output apabila memilih untuk tambah lagi

![Gambar 5](png/t.png)

ini adalah output apabila memilih hapus(3)

![Gambar 6](png/3.png)

ini adalah output apabila memilih lihat (4)

![Gambar 7](png/4.png)

ini adalah output apabila memilih else/keluar(5)

![Gambar 8](png/5.png)

======TERIMAKASIH======