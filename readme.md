[Merge Sort Projesi](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje)

# Proje 2

[16,21,11,8,12,22] -> Merge Sort

## Soru 1

#### Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

##### Cevap:

1. [16,21,11] - [8,12,22]
2. [16,21] [11] - [8,12] [22]
3. [16] [21] [11] - [8] [12] [22]
4. [16] [11,21] - [8] [12,22]
5. [11,16,21] - [8,12,22]
6. [8,11,12,16,21,22]

## Soru 2

#### Big-O göstermini yazınız.

##### Cevap:

[16,21,11,8,12,22] -> **2^x=n**

2^x=n -> logn=x (n adette işlem bulunuyor)

**Big-O = o(nlogn)**