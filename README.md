[22, 27, 16, 2, 18, 6] -> Insertion Sort:

1.Adım: Listenin ilk elemanı olan 22 sıralanmış bölümün başına yerleştirilir. Dizi şu şekilde olur: [22, 27, 16, 2, 18, 6].

2.Adım: Listenin ikinci elemanı olan 27, 22'den büyük olduğu için sıralanmış bölümün sonuna yerleştirilir. Dizi şu şekilde olur: [22, 27, 16, 2, 18, 6].

3.Adım: Listenin üçüncü elemanı olan 16, 27'den küçük olduğu için sıralanmamış bölümdeki elemanların arasına yerleştirilir. Dizi şu şekilde olur: [16, 22, 27, 2, 18, 6].

4.Adım: Listenin dördüncü elemanı olan 2, sıralanmamış bölümün başına yerleştirilir. Dizi şu şekilde olur: [2, 16, 22, 27, 18, 6].

5.Adım: Listenin beşinci elemanı olan 18, 27'den küçük ve 16'dan büyük olduğu için sıralanmamış bölümdeki elemanların arasına yerleştirilir. Dizi şu şekilde olur: [2, 16, 18, 22, 27, 6].

6.Adım: Listenin altıncı elemanı olan 6, 27'den küçük ve 22'den büyük olduğu için sıralanmamış bölümdeki elemanların arasına yerleştirilir. Dizi şu şekilde olur: [2, 6, 16, 18, 22, 27].


Big-O gösterimi: O(n^2)

Time Complexity: Dizi sıralandıktan sonra 18 sayısı için Average case kapsamına girer. Bu durumda aradığımız sayı ortada olacaktır.

[7,3,5,8,2,9,4,15,6] -> Selection Sort:

1.Adım: Dizinin en küçük elemanı olan 2 bulunur ve ilk eleman ile yer değiştirilir. Dizi şu şekilde olur: [2, 3, 5, 8, 7, 9, 4, 15, 6].

2.Adım: Dizinin en küçük elemanı olan 3 bulunur ve ikinci eleman ile yer değiştirilir. Dizi şu şekilde olur: [2, 3, 5, 8, 7, 9, 4, 15, 6].

3.Adım: Dizinin en küçük elemanı olan 4 bulunur ve üçüncü eleman ile yer değiştirilir. Dizi şu şekilde olur: [2, 3, 4, 8, 7, 9, 5, 15, 6].

4.Adım: Dizinin en küçük elemanı olan 5 bulunur ve altıncı eleman ile yer değiştirilir. Dizi şu şekilde olur: [2, 3, 4, 8, 7, 5, 9, 15, 6].
