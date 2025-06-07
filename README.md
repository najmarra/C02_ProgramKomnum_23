# Kelompok C-02
1. Ahmad Faiz Tajuddin (5025231291)
2. Najma Lail Arazy (5025241243)
3. Hidayah Nur Septiani (5025241247)
4. Nadia Putri Shafina (5025241254)
# No 23
Soal

`` 
Diketahui f(x) = x**3 + 4*x**2 - 59*x - 126
Carilah nilai ao, a1, bo, dan semua akar x dengan menggunakan metoda 
faktorisasi. 
[Lakukan iterasi hingga iterasi ke-3] 
``

# Metoda Faktorisasi 
`` def persamaan(equation_str) ``

Fungsi untuk memisahkan koefisiaen dari persamaan yang diberikan oleh pengguna.

`` def faktorisasi(A2, A1, A0) ``

Fungsi metoda faktorisasi untuk mencari nilai b0, a1, dan a0. Perulangan dilakukan sebanyak 3 kali iterasi. Hasil akhir dibulatkan dengan ketelitian 2 angka di belakang koma.

`` def akar(b0, a1, a0) ``

Fungsi untuk mencari nilai akar dari persamaan yang diberikan pengguna. Hasil akhir dibulatkan dengan menghilangkan angka desimalnya.

Hasil 

``
Hasil Iterasi 1: b0 = 0, a1 = 4, a0 = -59
Hasil Iterasi 2: b0 = 2.14, a1 = 1.86, a0 = -63.0
Hasil Iterasi 3: b0 = 2.00, a1 = 2.00, a0 = -63.0

Akar-akar persamaan dari faktorisasi:
Akar 1: -2
Akar 2: -9
Akar 3: 7 
``
