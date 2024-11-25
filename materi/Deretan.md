---
title: Deretan

---

# Deretan
## Deretan (sequence) 
* Deretan adalah suatu urutan atau susunan elemen atau objek yang disusun secara teratur berdasarkan suatu aturan tertentu. Elemen dalam deretan biasanya berupa angka, huruf, simbol, atau objek lainnya, dan urutannya dapat didasarkan pada pola, nilai, atau hubungan tertentu
* Definisi: Sebuah deretan adalah fungsi dari subset suatu himpunan bilangan bulat (biasanya N atau P) ke sebuah himpunan S.
N = {1, 2, 3, 4, … }
S misalnya {2, 4, 6, 8, …},   {1/3, 1/5, 1/7, …},  dsb
* Notasi deretan: {an}
* Deretan umumnya dinyatakan dalam suatu formula, misalnya:
	an = 2n
	an = 1/n
	an = 7 – 3n
Dalam konteks matematika, deretan sering merujuk pada barisan bilangan, yaitu kumpulan bilangan yang disusun dalam suatu pola tertentu.
 Misalnya:
Deretan bilangan ganjil: 1,3,5,7,…
Deretan bilangan genap: 2,4,6,8,…
Deretan bilangan yang membentuk deret aritmetika: 3,6,9,12....
* Contoh-contoh deretan dan formulanya:
* Deret Aritmetika
Deret dengan pola kenaikan atau penurunan tetap.
- Contoh: 2,5,8,11,14,…
- Rumus suku ke-n:
𝑈_𝑛=𝑎+(𝑛−1)⋅𝑏
Di mana:
- 𝑎: suku pertama 
- 𝑏: beda (selisih antar suku)
- 𝑛: nomor suku yang dicari
* Deret Geometri
Deret dengan pola kelipatan tetap.
- Contoh: 3,6,12,24,48,…
-  Rumus suku ke-n:
𝑈_𝑛=𝑎⋅𝑟^((𝑛−1) )
Di mana:
- 𝑎: suku pertama 
- 𝑟: rasio (perbandingan antar suku,
- 𝑛: nomor suku yang dicari
* Deret Bilangan Kuadrat
Deret dengan pola nilai berupa kuadrat bilangan bulat.
- Contoh: 1,4,9,16,25,…
-  Rumus suku ke-n:
𝑈_𝑛=𝑛^2
* Deret Bilangan Kubik
Deret dengan pola nilai berupa kubik bilangan bulat.
- Contoh: 1,8,27,64,125,…
- Rumus suku ke-n:
               𝑈_𝑛=𝑛^3
* Deret Fibonacci
Deret dengan pola di mana setiap suku merupakan jumlah dua suku sebelumnya.
- Contoh: 0,1,1,2,3,5,8,…
- Rumus suku ke-n (rekursif):
         𝐹_𝑛=𝐹_(𝑛−1)+𝐹_(𝑛−2),𝐹_0=0,𝐹_1=1
* String adalah deretan berhingga karakter berbentuk
		a1a2a3a4…an
Panjang string S adalah jumlah karakter di dalam string tersebut
Contoh:informatika adalah string dengan panjang 11 karakter
	10100101 adalah string biner dengan panjang 8 bit

* String kosong dilambangkan dengan , panjangnya = 0
# Penjumlahan deretan 
  Jumlah deretan 
	am, am+1, am+2, …, an
  adalah
	 am + am+1 + am+2 + … + an
  atau dalam notasi sumasi:
$$
\sum_{k=m}^n a_k
$$
    k adalah indeks summasi, 
    m adalah batas bawah indeks,
    n adalah batas atas indeks
Contoh 2: Berapa nilai 
$$
\sum_{k=1}^5 k^2
$$ 
Jawaban: 
$$
\sum_{k=1}^5 k^2 = 1^2 + 2^2 + 3^2 + 4^2 + 5^2 = 1 + 4 + 9 + 16 + 25 = 55
$$



Contoh 3: Batas bawah sumasi kadangkala perlu digeser agar dapat dijumlahkan dengan sumasi lain yang memiliki batas bawah berbeda. Pada contoh 2 di atas batas bawah digeser dari 1 menjadi 0, akibatnya:
$$
\sum_{k=1}^5 k^2 = \sum_{k=0}^4 (k+1)^2
$$  

Contoh 4: Sumasi dapat dipecah dengan membagi dua indeksnya, misalnya
$$
\sum_{k=1}^{100} k^2 = \sum_{k=1}^{49} k^2 + \sum_{k=50}^{100} k^2
$$ 
* TUGAS PEMBUKTIAN Dari 3 rumus dibawah
* Beberapa sumasi sudah ditemukan rumus penjumlahannya sebagai berikut:
![Screenshot 2024-11-24 195014](https://hackmd.io/_uploads/B1hzbsg7Jg.png)
Contoh 5: Hitung nilai
$$
\sum_{k=50}^{100} k^2
$$
Jawaban:
$$
\sum_{k=1}^{100} k^2 = \sum_{k=1}^{49} k^2 + \sum_{k=50}^{100} k^2
$$

$$
\sum_{k=50}^{100} k^2 = \sum_{k=1}^{100} k^2 - \sum_{k=1}^{49} k^2
$$


 Gunakan rumus
 ![Screenshot 2024-11-24 195152](https://hackmd.io/_uploads/SJKYboemJx.png)
$$
\sum_{k=50}^{100} k^2 = \frac{100 \cdot 101 \cdot 201}{6} - \frac{49 \cdot 50 \cdot 99}{6} = 338,350 - 40,425 = 297,925
$$

Di dalam algoritma, kita perlu menghitung berapa kali suatu operasi tertentu dilakukan di dalam sebuah kalang bersarang (nested loop). Penjumlahan semua operasi di dalam kalang bersarang dinyatakan dalam bentuk sumasi ganda.
Contoh:
$$
\sum_{i=1}^{4} \sum_{j=1}^{3} ij
$$
Untuk menghitung sumasi ganda, mula-mula ekspansi sumasi terdalam, lalu  dilanjukan dengan sumasi terluar:
$$
\sum_{i=1}^{4} \sum_{j=1}^{3} ij = \sum_{i=1}^{4} (i + 2i + 3i) = \sum_{i=1}^{4} 6i = 6 + 12 + 18 + 24 = 60
$$
Contoh penggunaan: Berapa kali operasi + dilakukan di dalam algoritma di bawah ini? 
x = 0
for j = 1 to 10 do
    for k = 1 to j do
           x = x + 2
   end for
end for 
Penyelesaian:
Operasi + terdapat di dalam pernyataan x = x + 2
Operasi ini dilakukan satu kali pada setiap pengulangan
Jumlah seluruh operasi + adalah:
$$
t = \sum_{j=1}^{10} \sum_{k=1}^{j} 1
$$
$$
= \sum_{j=1}^{10} (1 + 1 + \dots + 1 \text{ sebanyak } j \text{ kali})
$$
$$
= \sum_{j=1}^{10} 
$$
$$
= \frac{10(10+1)}{2} = 55
$$
Latihan:
Tentukan nilai 
$$
\sum_{k=1}^{8} 2^k + \sum_{k=2}^{8} (-3)^k
$$ 

Tentukan nilai 
$$
\sum_{i=0}^{2} \sum_{j=0}^{3} (2i + 3j)
$$ 

Tentukan nilai 
$$
\sum_{i=0}^{3} \sum_{j=0}^{2} i
$$ 
## Rekursi
* Sebuah objek dikatakan rekursif  (recursive) jika ia didefinisikan dalam terminologi dirinya sendiri. 

* Proses mendefinisikan objek dalam terminologi dirinya sendiri disebut rekursi (recursion).

* Perhatikan tiga buah gambar pada tiga slide berikut ini.
Objek fraktal  adalah contoh bentuk rekursif.
![Picture1](https://hackmd.io/_uploads/ryLBujgXJg.gif)
![Picture2](https://hackmd.io/_uploads/H1lP_ie7Je.jpg)
## Fungsi Rekursif
* Fungsi rekursif didefinisikan oleh dua bagian:
 (i)  Basis 
1. Bagian yang berisi nilai fungsi yang terdefinisi secara eksplisit.
2. Bagian ini juga sekaligus menghentikan rekursif (dan memberikan sebuah nilai yang terdefinisi pada fungsi rekursif).
 
 (ii)  Rekurens
1. Bagian ini mendefinisikan fungsi dalam terminologi dirinya sendiri. 
2. Berisi kaidah untuk menemukan nilai fungsi pada suatu input dari nilai-nilai lainnya pada input yang lebih kecil. 
Contoh 6:  Misalkan f didefinsikan secara rekusif sbb

![Picture3](https://hackmd.io/_uploads/B14auseQkx.png)				
		           
Tentukan nilai f(4)!	
	Solusi:      f(4) = 2f(3) + 4 
			=  2(2f(2) + 4) + 4
			=  2(2(2f(1) + 4) + 4) + 4
			=  2(2(2(2f(0) + 4) + 4) + 4) + 4
			=  2(2(2(2.3 + 4) + 4) + 4) + 4	
			=  2(2(2(10) + 4) + 4) + 4
			=  2(2(24) + 4) + 4
			=  2(52) + 4
			= 108	
Cara lain menghitungnya:
		f(0) = 3
		f(1) = 2f(0) + 4 = 2  3 + 4 = 10
		f(2) = 2f(1) + 4 = 2  10 + 4 = 24
		f(3) = 2f(2) + 4 = 2  24 + 4 = 52
		f(4) = 2f(3) + 4 = 2  52 + 4 = 108
		
Jadi, f(4) = 108.

Contoh 7: Nyatakan n! dalam definisi rekursif

Solusi:
![Picture4](https://hackmd.io/_uploads/HJwwYsxmye.png)


Misalkan f(n) = n!, maka  
![Picture5](https://hackmd.io/_uploads/rkDutie7kg.png)



		
Menghitung 5! secara rekursif adalah:
 5! = 5 .4! = 5 . 4 . 3! = 5. 4 .3. 2! 
= 5 . 4 . 3 . 2. 1! = 5 .4 . 3 . 2 . 1 . 0!= 5 . 4 . 3 .2 . 1 . 1 = 120
Algoritma menghitung faktorial:

function Faktorial (input  n :integer)integer
{ mengembalikan nilai n!;
  basis   : jika n = 0, maka 0! = 1
  rekurens: jika n > 0, maka n! = n x (n-1)!
}
DEKLARASI
      -
ALGORITMA:
    if n = 0 then
       return 1		              { basis }
    else
       return  n * Faktorial(n – 1)	{ rekurens }
    end
Contoh 8: Barisan Fibonacci  0, 1, 1, 2, 3, 5, 8, 11, 19, …. Dapat dinyatakan secara rekursif sebagai berikut:
![Picture6](https://hackmd.io/_uploads/SkKgiog7kg.png)
Contoh 9: Fungsi (polinom) Chebyshev dinyatakan sebagai
![Picture7](https://hackmd.io/_uploads/SJiZsjx7ke.png)
Contoh 10: Sumasi  ![Picture8](https://hackmd.io/_uploads/SkhXjolXJg.png)
didefinisikan secara rekursif sebagai  berikut:
![Picture9](https://hackmd.io/_uploads/rkfrsogQ1l.png)
sehingga 
![Picture10](https://hackmd.io/_uploads/Skr8joxmJl.png)
Latihan
1. Definisikan an secara rekursif , yang dalam hal ini a adalah bilangan riil tidak-nol dan n adalah bilangan bulat tidak-negatif.
2. Nyatakan a x b secara rekursif, yang dalam hal ini a dan b adalah bilangan bulat positif.
Solusi:
1. ![Picture11](https://hackmd.io/_uploads/rJdYjilmJl.png)
sehingga:
![Picture12](https://hackmd.io/_uploads/HJv9iilQye.png)
2.![Picture13](https://hackmd.io/_uploads/HJDiojgQ1l.png)
menjadi : ![Picture15](https://hackmd.io/_uploads/HJSajsxXkg.png)
## Struktur Rekursif
Struktur data yang penting dalam komputer adalah pohon biner (binary tree). 
![Picture16](https://hackmd.io/_uploads/ry7x2ix7Je.png)
* Simpul (node) pada pohon biner mempunyai paling banyak dua buah anak.

* Jumlah anak pada setiap simpul bisa 1, 2, atau 0.

* Simpul yang mempunyai anak disebut simpul cabang (branch node) atau simpul dalam (internal node)

* Simpul yang tidak mempunyai anak disebut simpul daun (leave).
* Pohon biner adalah struktur yang rekursif, sebab setiap simpul mempunyai cabang yang juga berupa pohon. Setiap cabang disebut  upapohon (subtree).
![Picture17](https://hackmd.io/_uploads/rywQhsx7yx.jpg)

Oleh karena itu, pohon dapat didefinisikan secara rekursif sebagari berikut:
(i) Basis: kosong adalah pohon biner
(ii) Rekurens: Jika T1 dan T2 adalah pohon biner, maka  * adalah pohon biner
								                    T1       T2 
				         	              
Proses pembentukan pohon biner secara rekursif:
(i)                 
(ii) 
![Picture18](https://hackmd.io/_uploads/HkVTnog71l.gif)









