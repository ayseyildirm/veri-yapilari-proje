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


## Proje 3:
**Binary Search Tree Oluşturma Aşamaları:**

1. **Başlangıç Durumu:**
   - İlk eleman, root (kök) olarak belirlenir: root 7'dir.

2. **5 Ekleniyor:**
   - 5, 7'nin soluna eklenir: root'un solunda 5 bulunur.

        ```
        7
       /
      5
        ```

3. **1 Ekleniyor:**
   - 1, 5'in soluna eklenir.

        ```
        7
       /
      5
     /
    1
        ```

4. **8 Ekleniyor:**
   - 8, 7'nin sağına eklenir.

        ```
        7
       / \
      5   8
     /
    1
        ```

5. **3 Ekleniyor:**
   - 3, 5'in sağına eklenir.

        ```
        7
       / \
      5   8
     / \
    1   3
        ```

6. **6 Ekleniyor:**
   - 6, 5'in sağına eklenir.

        ```
        7
       / \
      5   8
     / \
    1   3
       /
      6
        ```

7. **0 Ekleniyor:**
   - 0, 1'in soluna eklenir.

        ```
        7
       / \
      5   8
     / \
    1   3
   / \
  0   6
        ```

8. **9 Ekleniyor:**
   - 9, 8'in sağına eklenir.

        ```
        7
       / \
      5   8
     / \   \
    1   3   9
   / \
  0   6
        ```

9. **4 Ekleniyor:**
   - 4, 3'ün sağına eklenir.

        ```
        7
       / \
      5   8
     / \   \
    1   3   9
   / \   \
  0   6   4
        ```

10. **2 Ekleniyor:**
   - 2, 1'in sağına eklenir.

        ```
        7
       / \
      5   8
     / \   \
    1   3   9
   / \   \
  0   6   4
       /
      2
        ```




