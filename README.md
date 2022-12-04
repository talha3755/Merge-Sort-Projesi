# Merge-Sort-Projesi
Merge Sort

##[16,21,11,8,12,22] -> Merge Sort
### Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
* [6,21,11,8,12,22]
* [16,21,11] | [8,12,22]
* [16,21] [11] | [8,12] [22]
* [16] [21] [11] | [8] [12] [22]
* [11] [16,21] | [8] [12,22]
* [11,16,21] | [8,12,22]
* [8,12,11,16,21,22]
### Big-O gösterimini yazınız.
* 2^x=n -> logn=x 
* Big-O = O(nlogn)