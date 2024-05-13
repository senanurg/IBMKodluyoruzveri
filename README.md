# IBMKodluyoruzveri

1) [22,27,16,2,18,6]

Adım: [22, 27, 16, 2, 18, 6] -> [22, 27, 16, 2, 18, 6] (22 sabit, ilk eleman sıralı olarak kabul edilir)
Adım: [22, 27, 16, 2, 18, 6] -> [16, 22, 27, 2, 18, 6] (16, 22'den küçük olduğu için yer değiştirir)
Adım: [16, 22, 27, 2, 18, 6] -> [2, 16, 22, 27, 18, 6] (2, 16'dan küçük olduğu için yer değiştirir)
Adım: [2, 16, 22, 27, 18, 6] -> [2, 16, 18, 22, 27, 6] (18, 22'den küçük olduğu için yer değiştirir)
Adım: [2, 16, 18, 22, 27, 6] -> [2, 6, 16, 18, 22, 27] (6, 16'dan küçük olduğu için yer değiştirir)
Sıralı dizi: [2, 6, 16, 18, 22, 27]

Insertion Sort'un Big-O gösterimi O(n^2)'dir.

18 sayısının  sıralı dizideki durumu :

Average case: Aradığımız sayının ortada olması durumu
Worst case: Aradığımız sayının sonda olması durumu
Best case: Aradığımız sayının dizinin en başında olması durumu


Verilen dizi: [7, 3, 5, 8, 2, 9, 4, 15, 6]

Adım: [7, 3, 5, 8, 2, 9, 4, 15, 6] -> [2, 3, 5, 8, 7, 9, 4, 15, 6] (Minimum: 2)
Adım: [2, 3, 5, 8, 7, 9, 4, 15, 6] -> [2, 3, 4, 8, 7, 9, 5, 15, 6] (Minimum: 4)
Adım: [2, 3, 4, 8, 7, 9, 5, 15, 6] -> [2, 3, 4, 5, 7, 9, 8, 15, 6] (Minimum: 5)
Adım: [2, 3, 4, 5, 7, 9, 8, 15, 6] -> [2, 3, 4, 5, 6, 9, 8, 15, 7] (Minimum: 6)

Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

1.Adım (Bölme): [16, 21, 11] ve [8, 12, 22] olmak üzere iki alt diziye ayrılır.
2.Adım (Bölme): [16] ve [21, 11] ile [8] ve [12, 22] olmak üzere dört alt diziye ayrılır.
3.Adım (Birleştirme): [16] ve [21, 11] birleştirilir, [8] ve [12, 22] birleştirilir.
4.Adım (Birleştirme): [11, 16, 21] ve [8, 12, 22] birleştirilir.
5.Adım (Sonuç): [8, 11, 12, 16, 21, 22] olarak sıralı dizi elde edilir.


Big-O gösterimi O(n log n)'dir.



Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

           7
          / \
         5   8
        / \   \
       1   6   9
      / \     /
     0   3   9
        / \
       2   4



       
