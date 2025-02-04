Proje 2  
[16,21,11,8,12,22] -> Merge Sort  

1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

- Dizi ikiye bölünür: **[16,21,11]** ve **[8,12,22]**  
- Alt diziler tekrar bölünür:  
  - **[16,21]** ve **[11]**  
  - **[8,12]** ve **[22]**  
- Bölünen parçalar sıralanır:  
  - **[16,21]** zaten sıralı  
  - **[8,12]** zaten sıralı  
- Birleştirme aşaması:  
  - **[16,21]** ve **[11]** birleşir → **[11,16,21]**  
  - **[8,12]** ve **[22]** birleşir → **[8,12,22]**  
  - **[11,16,21]** ve **[8,12,22]** birleşir → **[8,11,12,16,21,22]**  

Sonuç: **[8,11,12,16,21,22]**

2) Big-O gösterimini yazınız.

Merge Sort, diziyi sürekli ikiye böldüğü için **O(log n)** bölme adımları içerir.  
Her adımda birleştirme işlemi **O(n)** zaman alır.  
Bu nedenle toplam karmaşıklık:  

**O(n log n)**  
