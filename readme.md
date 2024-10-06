## soru 1- [16,21,11,8,12,22] -> Merge Sort
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.


##  cevap 1 
```  
6 veri var 3 -3 parçalıyoruz
[16,21,11] [8,12,22]
[16] [21,11] [8] [12,22]
[16] [21] [11] [8] [12] [22]
[16] [11,21] [8] [12,22]
[11,16,21] [8,12,22]
[8,11,12,16,21,22]

``` 

---

##  soru 2- Big-O gösterimini yazınız. 
##  cevap 2 
O(nlogn)