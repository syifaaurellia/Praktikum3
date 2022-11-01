#### Hallo nama saya Syifa Aurellia Rahma. Saya membuat ini untuk memenuhi tugas saya. ####
# Latihan Python di Pycharm #
### DAFTAR ISI <br>
| No | Description | Link |
| ----- | ----- | ---- |
| 1 | Cara Installasi Pycharm| [Click Here](#Cara-Installasi-Pycharm)|
| 2 | Latihan 1 | [Click Here](#Latihan-1) |
| 3 | Latihan 2 | [Click Here](#Latihan-2) |
| 4 | Latihan 3 | [Click Here](#Latihan-3) |
| 5 | Menghitung Luas Dan Keliling Lingkaran | [Click Here](#Menghitung-Luas-Dan-Keliling-Lingkaran) |
| 6 | Flowchart Menghitung luas dan keliling lingkaran | [Click Here](#Flowchart-Menghitung-luas-dan-keliling-lingkaran) |

# Cara Installasi Pycharm #
1. Anda harus install Pycharm di https://www.jetbrains.com/pycharm/download/#section=windows , Dan anda pilih yang Community

![Screenshot (68)](https://user-images.githubusercontent.com/115867244/199033576-438bf4d1-4bc1-4205-ab68-94e0aef2f565.png)

2. Anda next saja semua perintahnya
3. Jika sudah selesai maka program siap di gunakan

# Cara Menjalankan Pycharm #
# Latihan 1 #
1. Pertama-tama anda harus Klik New project lalu kasih nama project anda(sesuai yang anda mau), Dan anda harus pilih yang Previously Configurred interperter lalu klik yang add interperter dan pilih yang System interperter dan anda klik yang versi Python anda seperti gambar di bawah ini.

![Screenshot (95)](https://user-images.githubusercontent.com/115867244/199042836-b5bc7304-fcc1-4a8c-b693-71dda27c1569.png)

![Screenshot (97)](https://user-images.githubusercontent.com/115867244/199043201-9ad5a1d7-e8a4-4102-af21-dece02cb1954.png)


2. Selanjutnya anda membuat file Python baru di project anda tadi dan anda kasih nama file sesuai yang anda inginkan

![Screenshot (93)](https://user-images.githubusercontent.com/115867244/199043466-95d20186-53aa-43db-8cc6-7e539a764181.png)

![Screenshot (94)](https://user-images.githubusercontent.com/115867244/199043560-d068b8b2-2752-4f3c-8b60-5b30c752f012.png)

3. Anda masukan code dari Latihan1 anda lalu Run

        # penggunaan end
        print('A', end='')
        print('B', end='')
        print('C', end='')
        print()
        print('X')
        print('Y')
        print('Z')

        # penggunaan separator
        w, x, y, z = 10, 15, 20, 25
        print(w, x, y, z)
        print(w, x, y, z, sep=',')
        print(w, x, y, z, sep='')
        print(w, x, y, z, sep=':')
        print(w, x, y, z, sep='-----')

        # string format
        print(0, 10**0)
        print(1, 10**1)
        print(2, 10**2)
        print(3, 10**3)
        print(4, 10**4)
        print(5, 10**5)
        print(6, 10**6)
        print(7, 10**7)
        print(8, 10**8)
        print(9, 10**9)
        print(10, 10**10)

        # string format
        print('{0:>3} {1:>16}'.format(0, 10**0))
        print('{0:>3} {1:>16}'.format(1, 10**1))
        print('{0:>3} {1:>16}'.format(2, 10**2))
        print('{0:>3} {1:>16}'.format(3, 10**3))
        print('{0:>3} {1:>16}'.format(4, 10**4))
        print('{0:>3} {1:>16}'.format(5, 10**5))
        print('{0:>3} {1:>16}'.format(6, 10**6))
        print('{0:>3} {1:>16}'.format(7, 10**7))
        print('{0:>3} {1:>16}'.format(8, 10**8))
        print('{0:>3} {1:>16}'.format(9, 10**9))
        print('{0:>3} {1:>16}'.format(10, 10**10))
        
 ![Screenshot (102)](https://user-images.githubusercontent.com/115867244/199135663-9f50faf0-669a-4581-be87-c4f1ed0f4181.png)
     
  ![Screenshot (103)](https://user-images.githubusercontent.com/115867244/199135682-bcf29fd9-2a69-4d9b-8752-b19aa245ac87.png)
    
- Hasil Run :

![Screenshot (77)](https://user-images.githubusercontent.com/115867244/199135825-1f6a443b-5cb7-4459-b5ac-3f04f939f2fa.png)

![Screenshot (78)](https://user-images.githubusercontent.com/115867244/199135875-c3f5f6bb-57b3-444f-ac3a-e73fcb6d920d.png)

# Latihan 2 #
1. Anda masukan code latihan 2 anda lalu Run

        a=input("masukkan nilai a:")
        b=input("masukkan nilai b:")
        print("variable a=",a)
        print("variable b=",b)
        print("hasil penggabungan {1}&{0}=%s".format(a,b) %(a+b))

        #koversi nilai variable
        a=int(a)
        b=int(b)
        print("hasil penjumlahan {1}+{0}=%s".format(a,b) %(a+b))
        print("hasil pembagian {1}/{0}=%s".format(a,b) %(a/b))
        
   ![Screenshot (106)](https://user-images.githubusercontent.com/115867244/199136520-e6e1ceff-1019-4a68-b05c-dfa9d95ec02f.png)

- Hasil Run

![Screenshot (81)](https://user-images.githubusercontent.com/115867244/199136671-befbc196-0a07-42c9-a343-53677d341f5c.png)

# Latihan 3 #
1. Anda masukan code seperti dibawah ini dan lalu Run

        string = ""

        x = int(input("Masukkan angka :"))
        bar = x
        # Looping Baris
        while bar >= 0:
                # Looping Kolom Spasi Kosong
                kol = bar
                while kol > 0:
                        string = string + "   "
                        kol = kol - 1
                # Looping Kolom Bintang Sisi Kiri		
                kiri = 1
                while kiri < (x - (bar-1)):
                        string = string + " * "
                        kiri = kiri + 1		
                # Looping Kolom Bintang Sisi Kanan
                kanan = 1
                while kanan < kiri -1:
                        string = string + " * "
                        kanan = kanan + 1	

                string = string + "\n\n"
                bar = bar - 1

        bar = 1	
        # Looping Baris
        while bar <= x:
                kol = bar+1
                # Looping Kolom Spasi Kosong
                while kol > 1:
                        string = string + "   "
                        kol = kol - 1
                # Looping Kolom Bintang Sisi Kiri	
                kiri = 0
                while kiri < (x - bar):
                        string = string + " * "
                        kiri = kiri + 1	
                # Looping Kolom Bintang Sisi Kanan
                kanan = kiri	
                while kanan > 1:
                        string = string + " * "
                        kanan = kanan - 1

                string = string + "\n\n"
                bar = bar + 1
        print (string)
        
 ![Screenshot (107)](https://user-images.githubusercontent.com/115867244/199136986-eb45fe71-eece-4818-97c0-bc92fa31f625.png)

![Screenshot (110)](https://user-images.githubusercontent.com/115867244/199137010-22e5b065-be4d-49f9-98e0-419772c27e6b.png)

- Hasil Run :

![Screenshot (84)](https://user-images.githubusercontent.com/115867244/199137124-3daf74ef-c291-430a-90dd-2a62d4673e3f.png)

 ![Screenshot (85)](https://user-images.githubusercontent.com/115867244/199137162-c10b70bf-e99e-4961-a969-0f4a792163da.png)

# Menghitung Luas dan Keliling Lingkaran #
1. Masukan code di bawah ini lalu run

        import math

        r = float(input("Masukan Jari-jari : "))

        luas = math.pi * (r * r)
        keliling = 2 * math.pi * r

        print("Luas Lingkaran \t\t= ", luas)
        print("Keliling Lingkaran\t= ", keliling)   
        
![Screenshot (112)](https://user-images.githubusercontent.com/115867244/199137531-fb02dbdb-285a-408f-af70-82bb3d0132a2.png)

- Hasil Run :

![Screenshot (88)](https://user-images.githubusercontent.com/115867244/199137616-d38a7e8c-597d-4b93-bde4-514e5dc958f1.png)

# Flowchart Menghitung Luas dan Keliling Lingkaran #

![198817259-154fec0b-f2b1-44e5-86c0-4c7ab1ad6142](https://user-images.githubusercontent.com/115867244/199137703-882b39f4-d922-46b3-b0ca-2e736c12208a.png)

### Terima Kasih ###
