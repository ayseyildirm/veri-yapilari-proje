# veri-yapilari-proje
Veri Yapıları ve Algoritmalar dersi için proje ödevleri
## **Proje 1:**
\[22, 27, 16, 2, 18, 6\] -> Insertion Sort

**Aşamalar:**
1. [22, **27**, 16, 2, 18, 6]
2. [**22, 27**, 16, 2, 18, 6]
3. [**16, 22, 27**, 2, 18, 6]
4. [2, **16, 22, 27**, 18, 6]
5. [2, 16, **18, 22, 27**, 6]
6. [2, 16, 18, **6, 22, 27**]

Sıralı dizi: [2, 6, 16, 18, 22, 27]

**Big-O Gösterimi:** O(n^2)

**Time Complexity (Zaman Karmaşıklığı):**
- Average case: O(n^2)
- Worst case: O(n^2)
- Best case: O(n)

**18 Sayısının Durumu:**
- Average case: Aradığımız sayının ortada olması
- Worst case: Aradığımız sayının sonda olması
- Best case: Aradığımız sayının dizinin en başında olması

## **Proje 2:**
**Soru:**
\[16, 21, 11, 8, 12, 22\] -> Merge Sort

**Aşamalar:**

1. **Başlangıç Durumu:**
   - Dizi: [16, 21, 11, 8, 12, 22]

2. **Bölme (Split):**
   - Dizi iki eşit parçaya ayrılır:
     - [16, 21, 11] | [8, 12, 22]

3. **Alt Dizileri Sıralama (Recursion):**
   - Sol alt dizi: [16, 21, 11]
     - Dizi iki parçaya ayrılır:
       - [16] | [21, 11]
       - [16] ve [21, 11] sıralanır:
         - [16] | [11, 21] (Sıralanmış sol alt dizi)
   - Sağ alt dizi: [8, 12, 22]
     - Dizi iki parçaya ayrılır:
       - [8] | [12, 22]
       - [8] ve [12, 22] sıralanır:
         - [8] | [12, 22] (Sıralanmış sağ alt dizi)

4. **Birleştirme (Merge):**
   - Sıralanmış sol ve sağ alt diziler birleştirilir:
     - [8, 11, 12, 16, 21, 22]

5. **Sonuç:**
   - Dizi sıralanmış haldedir: [8, 11, 12, 16, 21, 22]

**Big-O Gösterimi:** O(n log n)


