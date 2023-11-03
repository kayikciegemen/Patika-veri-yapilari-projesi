# Patika Veri Yapıları ve Algoritmalar dersi projeleri 

## Proje 3 (Binary Search)

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

### Çözüm 
- [0,1,2,3,4,5,6,7,8,9]     - Binary search sıralı olması gerektiği için öncelikle sıralıyoruz
              [5]           - Root 5'dir sağında büyükler solunda küçükler bulunur
- [0,1,2,3,4]        [6,7,8,9] - Rootun sağında ve solunda küçükler ve büyükler olarak ayırdık 
-    [2]                [8]     - İçlerinden yeni rootlar seçtik 
- [0,1]    [3,4]      [6,7] [9]  - Yine rootun küçükleri ve büyükleri olarak ayırdık 
- [0] [1]  [3] [4]   [6] [7] [9] - Her eleman tek kaldığında search tree işlemi bitmiştir
