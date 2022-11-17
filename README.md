
# Merge Sort Projesi
Sıralı olmayan diziyi ortadan eşit olarak iki alt diziye ayırır.
Bu ayırma işlemi, alt diziler en çok iki elemanlı olana kadar devam eder.Alt dizileri kendi içinde sıralar.
Sıralı iki alt diziyi tek bir sıralı dizi olacak şekilde birleştirir. Bu kurala göre aşağıdaki soruyu çözelim.

---
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

- [16,21,11] **/** [8,12,22]
- [16,21] , [11]  **/**  [8,12], [22]
- [16],[21]   ,  [11]  **/**     [8],[12]   ,   [22]
- [16,21] , [11] **/**[8,12],[22]
- [11,16,21]**/**[8,12,22] -> bu adımdan sonra iki gurubunda  sırasıyla ilk elemanlarından son elemanlarına karşılaştırma yapılarak sıralama gerçekleştirilir.
- [8,11,12,16,21,22] 

---
Big-O gösterimini yazınız.

**O(nlogn)**

[www.patika.dev](https://www.patika.dev/tr)