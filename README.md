# PatkikaDev
## 1. InsertionSortProjesi

[22,27,16,2,18,6] -> Insertion Sort

> 1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
````
- 1. adım: [2,27,16,22,18,6]
- 2. adım: [2,6,16,22,18,27]
- 3. adım: [2,6,16,22,18,27] "16 en küçük olduğu için aynı kalır"
- 4. adım: [2,6,16,18,22,27]
- 5. adım: [2,6,16,18,22,27] "liste sıralı hale geldi"
````

> 2. Big O gösterimini yazınız.
``` 
n+(n-1)+(n-2)....+1 >> o(n^2) 
```
> 3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
``` 
Best Case: o(n)
Worst Case: o(n^2)
Average Case: o(n^2)
```

> 4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
```
Average case kapsamına girer. Dizinin ortasında yer aldığı için. 
```
> 5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
- 1.adım: [2,3,5,8,7,9,4,15,6]
- 2.adım: [2,3,5,8,7,9,4,15,6] "3 dizideki en küçük ikinci eleman olduğu için, aranan o olduğu için sıralama değişmez."
- 3.adım: [2,3,4,8,7,9,5,15,6]
- 4.adım: [2,3,4,5,7,9,8,15,6]
```
## Merge Sort projesi 

> [16,21,11,8,12,22] -> Merge Sort
> Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
``` 
- 1. adım: [16,21,11] --- [8,12,22] olarak ortadan ikiye parçalanır.
- 2. adım: [16,21] [11] --- [8,12] [22]  parçalama yaptığımız grupları tekrar parçalarız.
- 3. adım: [16] [21] [11] --- [8] [12] [22] tekler haline geldikten sonraki hali 
- 4. adım: [16,21] [11] -- [8,12] [22] olarak birleştirilmiş olur 
- 5. adım: [11,16,21] -- [8,12,22]
- 6 adım: [8,11,12,16,21,22]
```
> Big-O gösterimini yazınız.
``` 
o(nlogn)
```


