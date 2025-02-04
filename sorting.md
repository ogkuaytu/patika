[22,27,16,2,18,6] -> Insertion Sort

1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

- [22, | 27, 16, 2, 18, 6] (İlk eleman sıralı kabul edilir)
- [22, 27, | 16, 2, 18, 6] (27 doğru yerde)
- [16, 22, 27, | 2, 18, 6] (16, 22 ve 27'nin önüne geçti)
- [2, 16, 22, 27, | 18, 6] (2, tüm elemanların önüne geçti)
- [2, 6, 16, 18, 22, | 27] (6, 16’nın önüne geçti)
- [2, 6, 16, 18, 22, 27] (Dizi sıralandı)

2) Big-O gösterimini yazınız.

Step 1 -> n  
Step 2 -> n-1  
Step 3 -> n-2  
...  
Step n-1 -> 1

sum = (n*(n-1))/2 -> **O(n²)**

3) Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case’lerden hangisinin kapsamına girer? Yazınız.

- **Average case**: Aradığımız sayının ortada olması
- Worst case: Aradığımız sayının sonda olması
- Best case: Aradığımız sayının dizinin en başında olması

Cevap: **Average case**

---

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort’a göre ilk 4 adımını yazınız.

1. **min=2** -> swap 7 and 2 -> **[2, | 3, 5, 8, 7, 9, 4, 15, 6]**
2. **min=3** -> no need to swap -> **[2, 3, | 5, 8, 7, 9, 4, 15, 6]**
3. **min=4** -> swap 5 and 4 -> **[2, 3, 4, | 8, 7, 9, 5, 15, 6]**
4. **min=5** -> swap 8 and 5 -> **[2, 3, 4, 5, | 7, 9, 8, 15, 6]**  
