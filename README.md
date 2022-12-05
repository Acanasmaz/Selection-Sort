# Selection-Sort

## Soru

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.



## Cevap

[22,27,16,2,18,6] n
[2,27,16,22,18,6] n-1
[2,6,16,22,18,27] n-2
[2,6,16,18,22,27] 1

n+(n-1)+(n-2)+1

n.(n+1)/2

n^2+n/2

Big o notation: O(n^2)

18 Average Casedir.

## Soru

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

## Cevap
0- [7,3,5,8,2,9,4,15,6]
1- [2,3,5,8,7,9,4,15,6]
2- [2,3,5,8,7,9,4,15,6]
3- [2,3,4,5,7,9,8,15,6]
4- [2,3,4,5,6,9,8,15,7]
