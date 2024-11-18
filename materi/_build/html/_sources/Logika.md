---
title: logika

---

# logika dan pembuktian 

## negasi
negasi adalah salah satu operasi logika dasar yang mengubah nilai kebenaran suatu pernyataan. Jika suatu pernyataan bernilai benar (True), negasinya akan bernilai salah (False), dan jika pernyataannya salah (False), maka negasinya akan menjadi benar (True).
Negasi biasanya dilambangkan dengan simbol $\neg$, ~, atau $!$.

Jika sebuah pernyataan P dinyatakan, maka negasi dari P ditulis sebagai $\neg P$ dan dibaca sebagai "bukan P ".


| P  | $\neg P$ | 
| -- | -- |
|  T |  F | 
|  F |  T |


## konjungsi
konjungsi adalah salah satu operasi logika yang menghubungkan dua pernyataan dan menghasilkan nilai benar hanya jika kedua pernyataan tersebut benar. Konjungsi biasanya dilambangkan dengan simbol ∧ atau dalam bahasa pemrograman sering digunakan simbol &&.

Jika ada dua pernyataan logika, $P$ dan $Q$ , maka konjungsi mereka, yang ditulis sebagai $P ∧ Q$, berarti "$P$ dan $Q$."Konjungsi akan bernilai benar jika kedua pernyataan, $P$ dan $Q$, bernilai benar, dan akan bernilai salah jika salah satu atau kedua pernyataan bernilai salah.



|   P   |   Q    |  $( p \land q )$|
| ------| ------ | ------ |
|   T   |   T    |    T   |
|   T   |   F    |    F   |
|   F   |   T    |    F   |
|   F   |   F    |    F   |
## disjungsi
disjungsi adalah operasi logika yang menghubungkan dua pernyataan dan menghasilkan nilai benar jika salah satu atau kedua pernyataan bernilai benar. Disjungsi sering dilambangkan dengan simbol ∨, yang dibaca sebagai "atau."

Jika ada dua pernyataan logika, P dan Q, maka disjungsi mereka, yang ditulis sebagai P ∨ Q, berarti "P atau Q." Disjungsi akan bernilai salah hanya jika kedua pernyataan salah

$\begin{array}{|c|c|c|}
\hline
P & Q & P \lor Q \\
\hline
\text{Benar (T)} & \text{Benar (T)} & \text{Benar (T)} \\
\text{Benar (T)} & \text{Salah (F)} & \text{Benar (T)} \\
\text{Salah (F)} & \text{Benar (T)} & \text{Benar (T)} \\
\text{Salah (F)} & \text{Salah (F)} & \text{Salah (F)} \\
\hline
\end{array}$


## implikasi
implikasi adalah operasi logika yang menyatakan hubungan antara dua pernyataan, di mana pernyataan pertama (hipotesis) menyiratkan pernyataan kedua (konklusi). Implikasi sering dilambangkan dengan simbol → dan dibaca sebagai "jika... maka...".

Jika ada dua pernyataan logika, P dan Q, maka implikasi mereka, yang ditulis sebagai P → Q, berarti "Jika P, maka Q." Implikasi ini hanya akan bernilai salah jika P benar dan Q salah. Dalam semua kasus lainnya, implikasi dianggap benar.

## biimplikasi
biimplikasi adalah operasi logika yang menyatakan hubungan dua arah antara dua pernyataan. Biimplikasi sering dilambangkan dengan simbol ↔ atau ⇔ dan dibaca sebagai "jika dan hanya jika" (iff: if and only if).

Jika ada dua pernyataan logika, P dan Q, maka biimplikasi mereka, yang ditulis sebagai P ↔ Q, berarti "P benar jika dan hanya jika Q benar." Dengan kata lain, P dan Q harus memiliki nilai kebenaran yang sama agar biimplikasi bernilai benar—baik keduanya benar atau keduanya salah.


Buatlah tabel kebenaran untuk~pernyataan berikut $$P\lor(R\to\ Q)$$

$$\begin{array}{c|c|c|c|cc}P&Q&R&\ Q&R\to\ Q&P\lor(R\to\ Q)\\\hline\text{Т}&\text{Т}&\text{Т}&\text{T}&\text{T}&\text{T}\\\text{Т}&\text{Т}&\text{F}&\text{F}&\text{T}&\text{T}\\\text{T}&\text{F}&\text{T}&\text{T}&\text{F}&\text{T}\\\text{T}&\text{F}&\text{F}&\text{F}&\text{F}&\text{T}\\\text{F}&\text{T}&\text{T}&\text{F}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{F}&\text{F}&\text{T}&\text{T}\\\text{F}&\text{F}&\text{T}&\text{T}&\text{F}&\text{F}\\\text{F}&\text{F}&\text{F}&\text{T}&\text{T}&\text{T}&\text{}\end{array}$$
