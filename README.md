#Praktikum 3

Nama : Muhammad Shiddiq
Kelas : TI.22.B1
NIM : 312210125

# Menghitung luas dan keliling lingkaran menggunakan `Python`

1. Buat File bernama LuasKelilingLingkaran.py

![Screenshot (48)](https://user-images.githubusercontent.com/115475520/198848712-1a37b89b-4fc2-46f0-a795-f72604db44fd.png)

2. Berikut Flowchart untuk menghitung luas dan keliling lingkaran

![Flowchart-menghitung-luas-keliling-lingkaran-1](https://user-images.githubusercontent.com/115475520/198848670-25f92bbe-cb9c-49dd-9e0a-e7b29d8af2a5.png)
  
3. Lalu Masukan CODE berikut :

![Screenshot (46)](https://user-images.githubusercontent.com/115475520/198848716-bbf1388c-0b51-47fb-b39f-81e5cf733b31.png)

    ```python
      # import module math
    import math
    # Variable jariJari menampung nilai input yang dimasukan yaitu berupa string
    jariJari = input('Masukan jari-jari lingkaran :')
    """
    rumus luas & keliling lingkaran
    _____________________________________
    luas     = phi * r^2
    keliling = 2 * phi * r
    _____________________________________
    """
    # convert string to integer
    jariJari = int(jariJari)
    # hitung luas lingkaran
    luas = math.pi * (jariJari * jariJari)
    # hitung luas keliling
    keliling = 2 * math.pi * jariJari
    # output luas & keliling lingkaran
    # .2f => mengambil 2 angka setelah (,)
    print("Berikut Luas lingkaran =  ", format(luas, '.2f'))
    print("Berikut Keliling lingkaran = ", format(keliling, '.2f'))
    ```

4. Ketika dijalankan Inputkan Jari jari dan Berikut Hasil nya

![Screenshot (47)](https://user-images.githubusercontent.com/115475520/198848729-44699d42-443b-4aa7-8fea-fb52080f231d.png)
  
5. Begitulah cara menghitung luas dan keliling Lingkaran
