# -Merge-Sort-Projesi
Merge Sort Project given by patika.dev in Data Structures and Algorithms section

**[16,21,11,8,12,22] -> Merge Sort**

**[16,21,11,8,12,22] dizisinin Merge sort türüne göre aşamaları:**


```
          [16,21,11,8,12,22]
           /              \
    [16,21,11]           [8,12,22]  
       /    \              /    \
   [16,21] [11]          [8,12] [22] 
     /  \    \            /  \    \
   [16] [21] [11]       [8] [12] [22]
     \   /    /          \   /    /
    [16,21] [11]         [8,12] [22]
        \    /              \    /
     [11,16,21]           [8,12,22]
             \             / 
            [8,11,12,16,21,22]

```
**Big-O gösterimi:** O(n*log n)


