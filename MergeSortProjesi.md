# Merge Sort
## [16,21,11,8,12,22] -> Merge Sort
[16, 21, 11, 8, 12, 22] --> [16, 21, 11] ve [8, 12, 22]
Her bir alt dizi tekrar ikiye bölünür:

[16, 21, 11] --> [16] ve [21, 11]
[8, 12, 22] --> [8] ve [12, 22]
Daha sonra, tek elemanlý alt diziler sýralanýr ve birleþtirilir:

[16] ve [21, 11] --> [11, 16, 21]
[8] ve [12, 22] --> [8, 12, 22]

Son olarak, iki sýralý alt dizi birleþtirilir:

[11, 16, 21] ve [8, 12, 22] --> [8, 11, 12, 16, 21, 22]
Big-O gösterimi O(n log n).