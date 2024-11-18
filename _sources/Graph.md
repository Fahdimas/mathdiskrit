---
title: Graph

---

## Analisa Graph
Graph adalah frekuensi antara hubungan antar suatu objek cotoh nya orang yang berhubungan seperti komunikasi sesama orang yang dapat di nyatakan dalam graph berbobot.
contoh garph berbobot selain komunikasi yaitu jarak antara kota masing masing individu seperti individu yang dari bangkalan , pamekasan,sampang dan surabaya.
dan dalam graph yang menyatakan jaraknya kita bisa mencari lintasan terpendek lewat mana berddasarkan garph berbobot.
*Social Network Analysis merupakan bidang kajian yang mengekplorasitentang hubungan manusia dengan menggunakan teori graf. Implementasi Social Network Analysis dapat menjelaskan relasi atau hubungan antar aktor melalui visualisasi berbentuk graf. Relasi dalam analisis jaringan sosial dapat diproses dalam bentuk perhitungan yang disebut centrality dalam sebuah jaringan sosial sesuai dengan posisi masing-masing aktor di dalam struktur jaringan tersebut
![image](https://hackmd.io/_uploads/Hy6SVNOMJx.png)

![image](https://hackmd.io/_uploads/BJZ4S4dMke.png)

Social network 
terdapat node yang mewakili 
orang atau individu atau aktor. 
Relasi  antar objek  dapat dinyatakan dengan link 
atau edges yang terjadi antara aktor tersebut 
Social network terdiri dari banyak aktor 
yang mempunyai relasi satu sama lain hingga
membentuk peta jaringan sosial yang dinyatakan dengan 
graph
*Tidak semua node dalam jaringan adalah penting  (aktor)
*Mencari node yang paling penting dalam suatu jaringan
*Centrality adalah penentuan aktor menggunakan ukuran pada Social Network Centrality dalam teori graf dan social network .Dibagi menjadi empat jenis, 
-degree centrality, 
-betweeness centrality, 
-closeness centrality 
-eigenvector centrality
## Degree Centrality
*Degree centrality adalah jumlah edge yang terkoneksi pada suatu node yang mewakili interaksi.
*Pentingnya node ditentukan oleh jumlah node yang berdekatan dengan node tersebut
-Lebih besar derajatnya (degree), maka lebih penting node itu dalam suatu jaringan 
-Hanya sebagian kecil node yang memiliki derajat tinggi dalam jaringan 
Degree Centraliity 
![image](https://hackmd.io/_uploads/BkYyrSdGyx.png)

Normalisasi  Degree Centrality:
![image](https://hackmd.io/_uploads/B1aeBHuzkg.png)

![image](https://hackmd.io/_uploads/S1twBrOMkl.png)

Untuk  node 1, degree centrality adalah 3;
Normalisasi degree centrality adalah
3/(9-1)=3/8.

## Closeness Centrality

*Closenes centrality adalah nilai kedekatan antara satu node dengan node lain dalam jaringan dengan menghitung rata-rata dari jarak relasi node-node tersebut. Skor closeness centrality mewakili kecepatan dalam penyebaran informasi.

*Average Distance:
![image](https://hackmd.io/_uploads/SyA5KUdzJl.png)

*Closeness Centrality 
![image](https://hackmd.io/_uploads/BJQsFU_z1g.png)

## Contoh Closeness Centrality 
![image](https://hackmd.io/_uploads/HJGntIdMye.png)

![image](https://hackmd.io/_uploads/BkohKLOfkl.png)

![image](https://hackmd.io/_uploads/S1bTFIuzkl.png)

## Betweenness Centrality
*Skor betweeness Centrality mewakili seberapa besar informasi yang tersebar dari suatu aktor. Semakin besar skor, artinya aktor tersebut semakin berperan dalam penyebaran informasi 

*Semakin banyak lintasan yang harus melewati persimpangan itu (misal tidak ada jalan alternatif), maka semakin penting arti persimpangan tersebut. Hal ini menandakan seberapa besar suatu node diperlukan sebagai penghubung dalam penyebaran informasi di dalam jaringan

*Ukuran ini juga dapat digunakan untuk mengidentifikasi boundary spanners, yaitu orang atau node yang berperan sebagai penghubung (jembatan) antara dua komunitas

## Betweenness Centrality
*Menghitung jumlah lintasan terpendek yang melewati suatu node
*Node dengan  betweenness  tinggi  adalah  penting dalam komunikasi dan penyebaran informasi
*Betweenness Centrality
![image](https://hackmd.io/_uploads/ryhf9Luf1l.png)
![image](https://hackmd.io/_uploads/SkQ798dfkg.png)
![image](https://hackmd.io/_uploads/BJGIqIOG1x.png)

## Betweenness Centrality
![image](https://hackmd.io/_uploads/SJxd9Luzyg.png)
![image](https://hackmd.io/_uploads/ByHOc8dfkl.png)
![image](https://hackmd.io/_uploads/ry5OcU_GJl.png)

betweenness centrality  untuk node 5?
![image](https://hackmd.io/_uploads/S1Xq5Luz1x.png)
![image](https://hackmd.io/_uploads/r1059I_zyg.png)
![image](https://hackmd.io/_uploads/H1Xs5L_zyl.png)

## Normalisasi Betweenness Centrality
![image](https://hackmd.io/_uploads/Bywh5Lufye.png)
