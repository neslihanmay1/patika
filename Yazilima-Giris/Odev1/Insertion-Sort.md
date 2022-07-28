# Insertion Sort Projesi

**[22,27,16,2,18,6] -> Insertion Sort**

 **1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.**


ilk hali -> [22 **|** 27, 16, 2, 18, 6]

[22, 27 **|**  16, 2, 18, 6]

[16, 22, 27 **|** 2, 18, 6]

[2, 16, 22, 27 **|** 18, 6]

[2, 16, 18, 22, 27 **|** 6]

son hali -> [2, 6, 16, 18, 22, 27]



**2. Big-O gösterimini yazınız.**

Best Case -> O($n$)
Average Case -> O($n^2$)
Worst Case -> O($n^2$)


 **NOT:** Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

**3.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.**

Average case.

**4.[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**

ilk hali -> [7 **|** 3, 5, 8, 2, 9, 4, 15, 6]

1.adım -> [3, 7 **|**  5, 8, 2, 9, 4, 15, 6]

2.adım -> [3, 5, 7 **|** 8, 2, 9, 4, 15, 6]

3.adım -> [3, 5, 7, 8 **|** 2, 9, 4, 15, 6]

4.adım -> [2, 3, 5, 7, 8 **|** 9, 4, 15, 6]
