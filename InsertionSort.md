## A)
[22,27,16,2,18,6] -> Insertion Sort

1) Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
2) Big-O gösterimini yazınız.
3) Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
<br> <br>

## A.1)
Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
1. [22, 27, 6, 2, 18, 6]
2. [2, 27, 6, 22, 18, 6]
3. [2, 6, 16, 22, 18, 27]
4. [2, 6, 16, 18, 22, 27]

## A.2)
Big-O gösterimini yazınız.
#### Worst Case: O(n^2)
#### Best Case: O(n)
#### Average Case: O(n^2)

## A.3)
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
#### Worst Case
[27, 22, 18, 16, 6, 2]
#### Average Case
[6, 16, 22, 2, 18, 27]
#### Best Case
[2, 6, 16, 18, 22, 27]

## A.4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Dizi tamamlandığı zaman 18 sayısı ortada olduğu için average case kapsamına girer.
