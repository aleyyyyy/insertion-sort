# insertion-sort
### Proje 1
### [22,27,16,2,18,6] -> Insertion Sort

### Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
### Big-O gösterimini yazınız.
### Time Complexity yazınız.
### Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


sort türüne göre aşamaları
[22,27,16,2,18,6]-(n)
[2,27,16,22,18,6]-(n-1)
[2,6,16,22,18,27]-(n-2)
[2,6,16,18,22,27]-(1)

big-o gösterimi
o(n^2)

time complexity
worst case: [27,22,18,16,6,2]
best case: [2,6,16,18,22,27]

Dizi sıralandıktan sonra 18 sayısı average case kapsamına girer.

[7,3,5,8,2,9,4,15,6]-(n)
[2,3,5,8,7,9,4,15,6]-(n-1)
[2,3,4,8,7,9,5,15,6]-(n-2)
[2,3,4,5,7,9,8,15,6]-(n-3)
[2,3,4,5,6,9,8,15,7]-(n-4)
[2,3,4,5,6,7,8,15,9]-(n-5)
[2,3,4,5,6,7,8,9,15]-(1)

www.patika.dev
