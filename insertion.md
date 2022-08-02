# Insertion Sort Projesi

## [22,27,16,2,18,6] -> Insertion Sort
## Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

**Insertion Sort Algoritması**, 2.elemandan başlayarak elemanlarını kendinden önceki eleman ile karşılaştırarak küçükten büyüğe olacak şekilde diziyi sıralar.

**1.Adım**
İlk eleman olan 22 kendi başına sıralı olmaktadır. Bir işlem gerektirmez.
 **[22|,27,16,2,18,6]**

**2.Adım**
22 ile 27 yi karşılaştırır. 27 elemanı 22'den büyük olduğu için bir işlem gerçekleşmez.
 **[22,27|,16,2,18,6]**

**3.Adım**
16 elemanı ile gerisindeki sayılar kıyaslanır. 16, 27'den küçük olduğu için yer değiştirir. Daha sonra 16 ile 22 kıyaslanır ve 16, 22'den küçük olduğun için yer değiştirirler.

 **[16,22,27|,2,18,6]**

**4.Adım**
Uyguladığımız işlemleri 2 elemanı için tekrarlayarak diziyi sıralarız.
 **[2,16,22,27|,18,6]**

**5.Adım**
Uyguladığımız işlemleri 18 elemanı için tekrarlayarak diziyi sıralarız.
 **[2,16,18,22,27|,6]**

**6.Adım**
Uyguladığımız işlemleri 6 elemanı için tekrarlayarak diziyi sıralarız.

 **[2,6,16,18,22,27]**

***Dizimizin insertion sort algoritması ile sıralanmış şekli;***
 
 ***[2,6,16,18,22,27]***

## Big-O Gösterimi 

O(n^2)

## Time Complexity

Average Case : Aradığımız sayının ortada olması

**O(n^2)**

Worst Case : Aradığımız sayının sonda olması

**O(n^2)** 

Best Case: Aradığımız sayının dizinin en başında olması.

**O(n)**

## 4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Dizimizin sıralanmış hali **[2,6,16,18,22,27]** şeklindedir. 18 sayısı ortada olduğu için **average case**'dir.

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

**1.Adım**

[7|,3,5,8,2,9,4,15,6]

**2.Adım**

[3,7|,5,8,2,9,4,15,6]

**3.Adım**

[3,5,7|,8,2,9,4,15,6]

**4.Adım**

[3,5,7,8|,2,9,4,15,6]