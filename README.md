# Merge-Sort  
Patika Dev Merge Sort Projesi  
  
1-) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.  
  Başla [16,21,11,8,12,22]  
 1 - [16, 21, 11] -- [8, 12, 22]  
2 - [16, 21]  [11] -- [8, 12] [22]  
3 - [16] [21] [11] -- [8] [12] [22]  
4 - [16, 21]  [11] -- [8, 12] [22]  
5 - [11, 16, 21] -- [8, 12, 22]  
6 - [8, 11,12, 16, 21, 22]  
  
2-) Big-O gösterimini yazınız.    
1 - n  
2 - n/2  
3 - n/4  
....  
(n-1) -> (n-1)/2^(n-2)  
  
n + n/2 + ... = n(1 + 1/2 + ...) = nlogn  
O(nlogn)  
