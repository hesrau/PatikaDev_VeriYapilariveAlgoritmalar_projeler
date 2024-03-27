# PatikaDev_VeriYapilariveAlgoritmalar_projeler
# Selection Sort

`[22,27,16,2,18,6]`

a) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
``` a'nın cevapları:
1: [22,27,16,2,18,6]   // 22  27'den küçük olduğu için hiç bir sıralama yapılmadı
2: [22,16,27,2,18,6]   // 27 ile 16 yer değişti
3: [16,22,27,2,18,6]   // 22 ile 16 yer değişti
4: [16,22,2,27,18,6]   // 27 ile 2 yer değişti
5: [16,2,22,27,18,6]   // 22 ile 2 yer değişti
6: [2,16,22,27,18,6]   // 16 ile 2 yer değişti
7: [2,16,22,18,27,6]   // 27 ile 18 yer değişti
8: [2,16,18,22,27,6]   // 22 ile 18 yer değişti
9: [2,16,18,22,6,27]   // 27 ile 6 yer değişti
10: [2,16,18,6,22,27]  // 22 ile 6 yer değişti
11: [2,16,6,18,22,27]  // 18 ile 6 yer değişti
12: [2,6,16,18,22,27]  // 16 ile 6 yer değişti
```
b) Big-O gösterimi:

`O(n^n)`

c) Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
```
Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
```
`Cevap -> Average case`

d) [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
```
[2,3,5,8,7,9,4,15,6] 2 ile 7 yer değişti
[2,3,4,8,7,9,5,15,6] 4 ile 5 yer değişti
[2,3,4,5,7,9,8,15,6] 5 ile 8 yer değişti
[2,3,4,5,6,9,8,15,7] 6 ile 7 yer değişti
```
# Merge Sort
`[16,21,11,8,12,22]`
a) Yukarıdaki dizinin merge sort türüne göre aşamalarını yazınız:
```
                      [16,21,11]                             [8,12,22]
                    /           \                         /           \
                  [16,21]       [11]                    [8,12]        [22]
                /      \           \                  /      \           \
              [16]  -  [21]        [11]             [8]  -   [12]        [22]   
                \      /           /                 \       /             /
                [16,21]         [11]                  [8,12]            [22]
                     \           /                         \           /
                      [11,16,21]                             [8,12,22]

                                    [8,11,12,16,21,22]                               
```
b) Big-O gösterimini yazınız:

`O(nlogn)`

# Binary Search Tree
