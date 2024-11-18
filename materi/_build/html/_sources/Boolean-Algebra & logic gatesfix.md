---
title: Boolean-Algebra & logic gatesfix

---

# Aljabar Boolean & Gerbang Logika

## Tujuan
* Memahami hubungan antara logika Boolean dan sirkuit komputer digital.
* Belajar cara merancang sirkuit logika sederhana.
* Memahami bagaimana sirkuit digital bekerja bersama-sama untuk membentuk sistem komputer yang kompleks.

## Operator Biner:
-Aljabar Boolean memiliki dua operator biner:
* Penjumlahan (+): Digunakan untuk operasi disjungsi (OR).
* Perkalian (⋅): Digunakan untuk operasi konjungsi (AND).

## Operator Uner:
-Komplemen (’): Digunakan untuk menghasilkan nilai yang berlawanan dari suatu elemen. Misalnya, jika a = 1, maka a’ = 0, dan sebaliknya.

### Contoh dalam pemrograman python
![image](https://hackmd.io/_uploads/SkCmspdJJg.png)

## Aksioma-Aksioma:
-Untuk setiap a, b, c ∈ B, berlaku aksioma-aksioma berikut:
* Closure: a + b ∈ B dan a ⋅ b ∈ B.
* Identitas: a + 0 = a dan a ⋅ 1 = a.
* Komutatif: a + b = b + a dan a ⋅ b = b ⋅ a.
* Distributif: a ⋅ (b + c) = (a ⋅ b) + (a ⋅ c) dan a + (b ⋅ c) = (a + b) ⋅ (a + c).
* Komplemen: Untuk setiap a ∈ B, terdapat elemen unik a’ ∈ B sehingga a + a’ = 1 dan a ⋅ a’ = 0

### Aljabar Boolean adalah sistem matematika untuk manipulasi variabel yang dapat memiliki salah satu dari dua nilai.  
* Dalam logika formal, nilai-nilai ini adalah "benar" dan "salah."  
* Dalam sistem digital, nilai-nilai ini adalah "nyala" dan "mati," 1 dan 0, atau "tinggi" dan "rendah."  
### Ekspresi Boolean dibuat dengan melakukan operasi pada variabel Boolean.  
### Operator Boolean yang umum termasuk AND (AND), (OR), dan (NOT).

## Aljabar Boolean
* Sebuah operator Boolean dapat dijelaskan sepenuhnya menggunakan tabel kebenaran. 

* Tabel kebenaran untuk operator Boolean D (AND) dan (OR) ditunjukkan di sebelah kanan. 
* Operator AND  juga dikenal sebagai produk Boolean. Operator OR adalah jumlah Boolean..
![image](https://hackmd.io/_uploads/BJNOhTdy1x.png)
###  Boolean Algebra
-Sebuah fungsi Boolean memiliki:  
* Setidaknya satu variabel Boolean,  
* Setidaknya satu operator Boolean, dan  
* Setidaknya satu input dari himpunan {0,1}.  

-Fungsi ini menghasilkan output yang juga merupakan anggota dari himpunan {0,1}.
* Tabel kebenaran untuk fungsi Boolean. : 
   ![image](https://hackmd.io/_uploads/Byefp6_kkx.png)
   di tunjukan si sebelah kanan
* Untuk mempermudah evaluasi fungsi Boolean, tabel kebenaran berisi kolom tambahan (diarsir) untuk menyimpan evaluasi dari bagian-bagian subfungsi.
![image](https://hackmd.io/_uploads/B1zNpad1kl.png)
![image](https://hackmd.io/_uploads/BktNpau11l.png)
* Kelompok kedua
![image](https://hackmd.io/_uploads/H1Pd6TOJJe.png)
* Kelompok 3 
![image](https://hackmd.io/_uploads/By-nppdy1l.png)
* Terkadang, lebih ekonomis membangun sirkuit dengan menggunakan komplemen fungsi dan mengkomplementasi hasilnya dibandingkan mengimplementasikan fungsi secara langsung. Hukum DeMorgan memudahkan penemuan komplemen dari fungsi Boolean, yang menyatakan: 
![image](https://hackmd.io/_uploads/HySbUWFJkl.png)

### Logic Gates
* Fungsi Boolean diimplementasikan dalam sirkuit komputer digital yang disebut gerbang (gates).  

* Gerbang adalah perangkat elektronik yang menghasilkan hasil berdasarkan dua atau lebih nilai input.  

* Dalam kenyataannya, gerbang terdiri dari satu hingga enam transistor, tetapi desainer digital menganggapnya sebagai satu kesatuan.  

* Sirkuit terintegrasi mengandung kumpulan gerbang yang sesuai untuk tujuan tertentu..
* Tiga gerbang AND, OR, dan  NOT.
![image](https://hackmd.io/_uploads/ryRMyAd1yg.png)

## Gerbang logika 
![image](https://hackmd.io/_uploads/BJtPJ0OyJe.png)
gerbang AND 1 AND 0 = 0
![image](https://hackmd.io/_uploads/rygOyROykl.png)
gerbang OR 1 OR 0 = 1
* NAND dan NOR dua gerbang yang sangat penting. Simbol dan tabel kebenarannya ditunjukkan di sebelah kanan. 
![image](https://hackmd.io/_uploads/SkgrL-Ky1x.png)
* NAND dan NOR dikenal dengan gerbang universal  karena mereka murah untuk diproduksi dan setiap fungsi Boolean dapat dibangun menggunakan gerbang ini. NAND atau hanya gerbang NOR .  
![image](https://hackmd.io/_uploads/H14UUZFkkl.png)
* Gerbang dapat memiliki beberapa  inputs dan dan lebih dari satu output.
* Output kedua dapat disediakan untuk komplemen dari operasi. 
![image](https://hackmd.io/_uploads/Bk3wL-Kkkx.png)
##  Komponen Digital
* Hal utama yang perlu diingat adalah bahwa kombinasi gerbang menerapkan fungsi Boolean.
* Rangkaian di bawah ini mengimplementasikan fungsi Boolean :
![image](https://hackmd.io/_uploads/BJq98Wtyke.png)

##  Combinational Circuits

-Kami telah merancang rangkaian yang mengimplementasikan fungsi Boolean :
* Rangkaian ini merupakan contoh rangkaian logika kombinasional.
* ![image](https://hackmd.io/_uploads/r1lZXrK11x.png)

* Rangkaian logika kombinasional menghasilkan output tertentu
* Combinational logic circuits give us many useful devices.
* One of the simplest is the half adder, which finds the sum of two bits.
* We can gain some insight as to the construction of a half adder by looking at its truth table, shown at the right.
![image](https://hackmd.io/_uploads/HyJ7mBK11e.png)
* Seperti kita lihat, jumlahnya dapat ditemukan menggunakan operasi XOR dan sisanya menggunakan operasi AND.
![image](https://hackmd.io/_uploads/H1BSXHtkkx.png)
![image](https://hackmd.io/_uploads/r1aHQHt1Je.png)
![image](https://hackmd.io/_uploads/HJ8PQBtk1x.png)
