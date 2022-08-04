# Veri-Yap-lar-ve-Algoritmalar

www.patika.dev
 
### Insertion Sort

# Soru 1
[22,27,16,2,18,6] -> Insertion Sort
s1.1:Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
s1.2:Big-O gösterimini yazınız.
s1.3:Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
s1.4:Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

# Çözüm 1 
ç1.1:
[22,27,16,2,18,6]
dizimizin en küçük sayısını en başa getirmek için 2 ile 22 elemanlarını yer değiştiririz.
[2,27,16,22,18,6]
2'den sonra gelen en küçük sayı 6 olduğundan, 6 ile 27 sayıları yer değiştirmemiz gerekir.
[2,6,16,22,18,27]
16 sayısı dizideki 6'dan sonra gelen en küçük sayı olduğundan bir işlem gerekmez. 16'dan sonra gelmesi gereken 18 sayısı için 18 ve 22 yer değiştirir.
[2,6,16,18,22,27]
dizimizin geri kalan elemanları doğru yerde olduğundan dizimizin son hali bu şekildedir.
[2,6,16,18,22,27]

ç1.2: O(n^2)

ç1.3:
average case: O(n^2)
worst case: O(n^2)
best case: O(n)

ç1.4: average case

# Soru 2
s2.1: [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

# Çözüm 2
adım 1:
[2,3,5,8,7,9,4,15,6]
adım 2:
[2,3,4,8,7,9,5,15,6]
adım 3:
[2,3,4,5,7,9,8,15,6]
adım 4:
[2,3,4,5,6,9,8,15,7]



## Merge Sort Proje ödevi

# Soru 1
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

1. [16,21,11,8,12,22] dizisini ortadan ikiye bölelim.

2. [16,21,11] ve [8,12,22] olmak üzere iki küme oluştu.

3. [16] --- [21,11] ve [8] --- [12,22] olarak elimizde 4 küme oldu.

4. Verileri tek elemanlı küme olacak şekilde ayıralım: [16]-[21]-[11]-[8]-[12]-[22]

5. Verileri küçükten büyüğe kendi grupları içinde birleştirelim: [16]-[11,21]-[8]-[12,22] => [11,16,21] - [8,12,22]

6. Son olarak birleştirelim. [8,11,12,16,21,22]

# Soru 2
Big-O gösterimini yazınız.
O(nLogn)
