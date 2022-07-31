# Insertion-Sort-Projesi
Patika Insertion Sort Projesi- Aysun Akbal

www.patika.dev

Proje 1

[22,27,16,2,18,6] -> Insertion Sort

S1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
C1- Insertion sort'a göre verilen sayı dizisindeki elemanları küçükten büyüğe olacak şekilde sıralamak amaçtır. Bu sıralamayı yaparken en küçük eleman olan 2'yi en baştaki eleman olan 22 ile yerlerini değiştirerek işe başlarız.

[22,27,16,2,18,6]----n

[2,27,16,22,18,6]---- n-1

İkinci aşamada diğer küçük sayı 6 ile 27'nin yeri değişir.

[2,6,16,22,18,27]---- n-2

6'dan sonra küçük olan sayı 16 doğru yerinde olduğu için

[2,6,16,22,18,27]---- n-3

18 ile 22'nin yeri değiştirilir.

[2,6,16,18,22,27]---- n-4

dizinin son hali [2,6,16,18,22,27] olur.

S2- Big-O gösterimini yazınız.
C2- O(n^2)'dir. 

S3- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
C3- Average Case: [2,6,16,18,22,27] -  O(n^2) 
Worst Case: [27,22,18,16,6,2] -  O(n^2)
Best Case: [2,6,16,18,22,27] -  O(n)

S4- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
C4- 18 sayısı, dizinin ortanca değeridir. Avarage case kapsamına girer.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

En küçük sayı 2 olduğu için 7 ile 2'nin yerini değiştirerek başlarız.
[2,3,5,8,7,9,4,15,6] ---- n-1

İkinci adımda 2'den sonraki en küçük sayı 3 olduğu için dizide değişiklik yapılmaz.

[2,3,5,8,7,9,4,15,6] -----n-2

Üçüncü adım sonraki küçük sayı 4 olduğu için 5 ile 4'ün yeri değişir.

[2,3,4,8,7,9,5,15,6] ---- n-3

Dördüncü adım 5 ile 8'in yeri değişir.

[2,3,4,5,7,9,8,15,6]

www.patika.dev
