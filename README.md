# Insertion-Sort-Projesi

## Proje 1

 [22,27,16,2,18,6] -> Insertion Sort Asamalari

```
*1*.asama [2,27,16,22,18,6] 
*2*.asama [2,6,16,22,18,27]
*3*.asama [2,6,16,18,22,27]
```

### Big-O gosterimi:

```
[22,27,16,2,18,6] 
n kadar islem olsa
(n)+(n-1)+(n-2) ...+1
(n).(n+1)/2
n^2 yi aliyoruz kat sayı onemli degildi.
O(n^2)
```

### Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

### Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Dizinin sıralanmıs hali:[2,6,16,18,22,27]
18 aradıgımız sayı ortada olmasından oturu 'average case'

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

```
*1*.asama [2,3,5,8,7,9,4,15,6] 
*2*.asama [2,3,4,8,7,9,5,15,6]
*3*.asama [2,3,4,5,7,9,8,15,6]
*4*.asama [2,3,4,5,6,9,8,15,7]
```