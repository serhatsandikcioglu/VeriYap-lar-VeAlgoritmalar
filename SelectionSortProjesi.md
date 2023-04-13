# Selection Sort
## [22,27,16,2,18,6] -> Insertion Sort
Verilen dizi insertion sort algoritmasý ile sýralanacak. Ýlk adýmda, 2 ile baþlayarak, her bir elemaný uygun pozisyona taþýmak için diðer elemanlarla karþýlaþtýrýlýr. Sonuçta, sýralanmýþ bir diziye ulaþýlýr:

[22, 27, 16, 2, 18, 6] --> [2, 22, 27, 16, 18, 6] --> [2, 16, 22, 27, 18, 6] --> [2, 16, 18, 22, 27, 6] --> [2, 6, 16, 18, 22, 27]
Big-O gösterimi O(n^2).
18 sayýsý ortada olduðundan dolayý Average Case'dir.
## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adýmý
[7, 3, 5, 8, 2, 9, 4, 15, 6] --> [2, 3, 5, 8, 7, 9, 4, 15, 6]
[2, 3, 5, 8, 7, 9, 4, 15, 6] --> [2, 3, 4, 8, 7, 9, 5, 15, 6]
[2, 3, 4, 8, 7, 9, 5, 15, 6] --> [2, 3, 4, 5, 7, 9, 8, 15, 6]
[2, 3, 4, 5, 7, 9, 8, 15, 6] --> [2, 3, 4, 5, 6, 9, 8, 15, 7]