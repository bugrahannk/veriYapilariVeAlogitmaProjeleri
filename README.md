# Insertion Sort
* https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/insertion-sort-proje
* Profil: https://app.patika.dev/bugrahannk

_____________________________________________


```
[22,27,16,2,18,6] -> Insertion Sort
```

*    Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

```
[22,27,16,2,18,6]
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]
```



*    Big-O gösterimini yazınız.

```
6 eleman olduğundan O(n²) = O(6²) = O(36) 
```


*    Time Complexity:

Average case: Aradığımız sayının ortada olması,
Worst case: Aradığımız sayının sonda olması,
Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

```
Average Case
```



*   [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

```
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]

```


# Merge Sort
* https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje
* Profil: https://app.patika.dev/bugrahannk

_____________________________________________


```
[16,21,11,8,12,22] -> Merge Sort
```

* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız
* Big-O gösterimini yazınız.

```
a)[16,21,11] [8,12,22]
b)16 [21,11] 8 [12,22]
c)16 21 11 8 12 22
d)16 [11,21] 8 [12,22]
e)[11,16,21] [8,12,22]
f)[8,11,12,16,21,22]
```
```
(2^x = n)'den x=log(n) defa yapılır. Her bir adımın time complexity değeri O(n) olduğu için genel ifade "O(nlog(n))" olmalı.
```


