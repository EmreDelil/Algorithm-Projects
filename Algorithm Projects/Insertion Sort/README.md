# Insertion Sort Projesi

## 1. soru

### [22,27,16,2,18,6] dizisini insertion sort yöntemi aşamalarını yazınız.
```
1. [2,27,16,22,18,6] = dizideki en küçük eleman bulunup 1. sıra ile yer değiştirir.
2. [2,6,16,22,18,27] = 2. sıradaki eleman ile dizinin kalan en küçük elemanı yer değiştirir.
- Bu şekilde son elemana kadar gidilir
3. [2,6,16,18,22,27] = tüm elemanlar doğru sıralandıktan sonra işlemi bitirir.
```
---
## 2. soru

### Big-O gösterimini yazınız.
```
n+(n-1)+(n-2)+...+1 = (n*(n+1)/2)= (n²+n)/2 = O(n²) olur.
Dizimiz 6 elemanlı olduğu için sonucumuz 6² = 36 olur.
```
---
## 3. soru

### Time complexity.
```
worst case = O(n²) = 36, best case = 1, average case = 16 or 18
```
---
## 4. soru

### Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
```
18 sayısı ortanca sayı olduğu için average case kapsamındadır.
```
---
## 5. soru

### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
1. [2,3,5,8,7,9,4,15,6]
2. [2,3,5,8,7,9,4,15,6]
3. [2,3,4,8,7,9,5,15,6]
4. [2,3,4,5,7,9,8,15,6]
```
