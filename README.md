# IBMKodluyoruzveri

Soru 1) [22,27,16,2,18,6]

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
