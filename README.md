## [16,21,11,8,12,22] dizisini Merge Sort ile sıralama


### i. [16,21,11] | [8,12,22]
### ii. [16,21] [11] | [8,12] [22]
### iii. [11,16,21] | [8,12,22]
### iiii. [8,11,12,16,21,22]

## BİG-O gösterimi:
n -> n/2- n/2 -> n/4 - n/4 - n/4 - n/4   olarak devam eder ve burada 2'ye bölünlerek devam ettiği için O(log2^n) işlem her satırda n defa tekrar ettiği için O(n.log2^n) olarak ifade edebilirz