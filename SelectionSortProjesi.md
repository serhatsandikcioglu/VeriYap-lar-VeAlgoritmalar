# Selection Sort
## [22,27,16,2,18,6] -> Insertion Sort
Verilen dizi insertion sort algoritmas� ile s�ralanacak. �lk ad�mda, 2 ile ba�layarak, her bir eleman� uygun pozisyona ta��mak i�in di�er elemanlarla kar��la�t�r�l�r. Sonu�ta, s�ralanm�� bir diziye ula��l�r:

[22, 27, 16, 2, 18, 6] --> [2, 22, 27, 16, 18, 6] --> [2, 16, 22, 27, 18, 6] --> [2, 16, 18, 22, 27, 6] --> [2, 6, 16, 18, 22, 27]
Big-O g�sterimi O(n^2).
18 say�s� ortada oldu�undan dolay� Average Case'dir.
## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a g�re ilk 4 ad�m�
[7, 3, 5, 8, 2, 9, 4, 15, 6] --> [2, 3, 5, 8, 7, 9, 4, 15, 6]
[2, 3, 5, 8, 7, 9, 4, 15, 6] --> [2, 3, 4, 8, 7, 9, 5, 15, 6]
[2, 3, 4, 8, 7, 9, 5, 15, 6] --> [2, 3, 4, 5, 7, 9, 8, 15, 6]
[2, 3, 4, 5, 7, 9, 8, 15, 6] --> [2, 3, 4, 5, 6, 9, 8, 15, 7]