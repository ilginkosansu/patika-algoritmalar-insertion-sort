# Insertion Sort
-----------------------
Verilen sayı dizinimiz --> [22, 27, 16, 2, 18, 6]
Insertion sort algoritması, dizin içerisinde en küçük elemanı bulur ve en baştakiyle yer değiştirir. Ardından yerleştirdiği ilk eleman haricinde geri kalan elemanlar içerisinden en küçüğünü arar ve 2. elemana yerleştirir. Bu işlemi bu şekilde sıralayarak tamamlar.

1. adım --> [22, 27, 16, 2, 18, 6]
2. adım --> [2, 27, 16, 22, 18, 6]
3. adım --> [2, 6, 16, 22, 18, 27]
4. adım --> [2, 6, 16, 18, 22, 27]

## Big-O Gösterimi
-----------------------
Big-O = O(n^2)

## Time-Complexity
-----------------------
Aradığımız sayı,18 dizinin ortalarında olduğundan 'avarege case' kapsamına girer.

-----------------------
**************************************************************************
-----------------------

1. adım --> [7, 3, 5, 8, 2, 9, 4, 15, 6]
2. adım --> [2, 3, 5, 8, 7, 9, 4, 15, 6]
3. adım --> [2, 3, 4, 8, 7, 9, 5, 15, 6]
4. adım --> [2, 3, 4, 5, 7, 9, 8, 15, 6]

