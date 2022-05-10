# Insertion Sort Projesi

## Proje 1

 
> [ 22, 27, 16, 2, 18, 6 ] -> Insertion Sort 

> Yukarı verilen dizinin sort türüne göre aşamalarını yazınız. 

```` 
[ 22, 27, 16, 2, 18, 6 ]

[ 16, 22, 27, 2, 18, 6 ]

[ 2, 16, 22, 27, 18, 6 ]

[ 2, 16, 18, 22, 27, 6 ]

[ 2, 6, 16, 18, 22, 27 ]
````

> Big-O gösterimini yazınız.

````
n + n-1 + n-2 ... + 1 yani
1 + 2 + 3 + .. + n

n*(n+1) / 2 = ( n^2 + n ) / 2 => O( n^2 )
````




>Time Complexity: 
````
Average case: Aradığımız sayının ortada olması,

O(n^2)

Worst case: Aradığımız sayının sonda olması, 

O(n^2)

Best case: Aradığımız sayının dizinin en başında olması.

O(n)


````


> Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
````
Average case: O(n^2)
````


> [ 7, 3, 5, 8, 2, 9, 4, 15, 6 ] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

````
[ 7, 3 , 5, 8, 2, 9, 4, 15, 6 ]

1. [ 3, 7, 5, 8, 2, 9, 4, 15, 6 ]
2. [ 3, 5, 7, 8, 2, 9, 4, 15, 6 ]
3. [ 2, 3, 5, 7, 8, 9, 4, 15, 6 ]
4. [ 2, 3, 4, 5, 7, 8, 9, 15, 6 ]

````
