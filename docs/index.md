# Data Mining (C)

###### Nama  : Yogi Dwy Al Qurniawan

###### NIM     : 180441100059

Source data : [COVID19](https://www.cnbcindonesia.com/news/20200319081026-4-145990/data-menteri-jokowi-yang-positif-negatif-covid-19/3)

``import numpy as np`
`from kmodes.kmodes import KModes``

random categorical data

data = np.random.choice(20, (100, 10))

km = KModes(n_clusters=4, init='Huang', n_init=5, verbose=1)

clusters = km.fit_predict(data)

Print the cluster centroids

print(km.cluster_centroids_)

![](assets\images\t obat.png)

[Sumber]: https://jatim.bps.go.id/statictable/2018/02/08/887/produksi-tanaman-obat-di-jawa-timur-kg-2009-2016.html	" BPS Propinsi Jawa Timur"

#### 1. Jahe

![](assets\images\21.png)

![](assets\images\1Jahe.png)

​        Rata-rata =   46 964 657 

​        Standar Deviasi = 34670120,95

#### 2. Laos/Lengkuas

![](assets\images\22.png)

![](assets\images\2.png)

​        Rata-rata =     9 064 009  

​        Standar Deviasi = 2428083,844

#### 3. Kencur

![](assets\images\23.png)

![](assets\images\3.png)

​        Rata-rata =   3 835 909 

​        Standar Deviasi = 945013,3247

#### 4. Kunyit

![](assets\images\24.png)

![](assets\images\4.png)

​        Rata-rata =     30 129 284 

​        Standar Deviasi = 38899667,309

#### 5. Lempuyang

![](assets\images\25.png)

![](assets\images\5.png)

​        Rata-rata =   4  2937 708 

​        Standar Deviasi = 913550,7542

#### 6. Temulawak

![](assets\images\26.png)

![](assets\images\6.png)

​        Rata-rata =    12 066 265  

​        Standar Deviasi = 4058900,476

#### 7. Temuireng![](assets\images\27.png)

![](assets\images\7.png)

​        Rata-rata =   2 696 629 

​        Standar Deviasi = 1087452,719

#### 8. Temukunci

![](assets\images\28.png)

![](assets\images\8.png)

​        Rata-rata =     2 179 858 

​        Standar Deviasi = 828941,0099

#### 9. Dringo/Dlingo

![](assets\images\29.png)

![](assets\images\9.png)

​        Rata-rata =    92 172 

​        Standar Deviasi = 133858,6347

#### 10. Kapulaga

![](assets\images\30.png)

![](assets\images\10.png)

​        Rata-rata =     949 184 

​        Standar Deviasi = 1070263,769

#### 11. Mengkudu/Pace*)

![](assets\images\31.png)

![](assets\images\11.png)

​        Rata-rata =     3 425 769 

​        Standar Deviasi = 1632442,715

#### 12. Mahkota Dewa*)

![](assets\images\32.png)

![](assets\images\12.png)

​        Rata-rata =     729 393  

​        Standar Deviasi = 348718,0583

#### 13. Kejibeling

![](assets\images\33.png)

![](assets\images\13.png)

​        Rata-rata =     120 007  

​        Standar Deviasi = 123378,235

#### 14. Sambiloto

![](assets\images\34.png)

![](assets\images\14.png)

​        Rata-rata =         1 511 355    

​        Standar Deviasi = 1208957,677

#### 15. Lidah Buaya

![](assets\images\35.png)

![](assets\images\15.png)

​        Rata-rata =         216 081   

​        Standar Deviasi = 130332,9857



Sumber : https://jatim.bps.go.id/statictable/2018/02/08/887/produksi-tanaman-obat-di-jawa-timur-kg-2009-2016.html