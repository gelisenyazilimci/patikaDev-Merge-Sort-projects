## Verilen dizi: `[16,21,11,8,12,22]`

### Merge Sort Aşamaları

1. Dizi ikiye bölünür:  
   `[16,21,11]` ve `[8,12,22]`

2. İlk yarı tekrar ikiye bölünür:  
   `[16]`, `[21,11]`  
   `[21,11]` tekrar bölünür: `[21]`, `[11]`  
   Daha sonra sıralanır ve birleştirilir: `[11,21]`  
   Sonuç: `[16,11,21]`

3. İkinci yarı tekrar ikiye bölünür:  
   `[8]`, `[12,22]`  
   `[12,22]` sıralı olduğu için birleştirilir: `[8,12,22]`

4. İki sıralı alt dizi birleştirilir:  
   `[16,11,21]` ve `[8,12,22]`  
   Sıralanarak birleştirilir: `[8,11,12,16,21,22]`

### Big-O Gösterimi

- Best Case: `O(n log n)`
- Average Case: `O(n log n)`
- Worst Case: `O(n log n)`
