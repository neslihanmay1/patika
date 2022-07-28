# Merge Sort Projesi


**[16,21,11,8,12,22] -> Merge Sort**


## **Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.**


- öncelikle diziyi her bir eleman tek kalacak şekilde ayırırız.


[16, 21, 11] ---- [8, 12, 22]

[16, 21] -- [11] ---- [8, 12] -- [22]

[16] - [21] - [11] - [8] - [12] - [22]


- şimdi ise elemanları sıralayarak birleştireceğiz.


[16, 21] -- [11] --- [8, 12] -- [22]

[11, 16, 21] --- [8, 12, 22]

[8, 11, 12, 16, 21, 22]


## **Big-O gösterimini yazınız.**

Best Case -> O($n$log($n$))

Average Case -> O($n$log($n$))

Worst Case -> O($n$log($n$))