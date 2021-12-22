# Patika.Dev-DataStructuresAndAlgorithms
## PROJE 1
### **[22, 27, 16, 2, 18, 6] -> Insertion Sort**

#### 1 - Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
    [22, 27, 16, 2, 18, 6]
    
    [2, 27, 16, 22, 18, 6]
    
    [2, 6, 16, 22, 18, 27]
    
    [2, 6, 16, 18, 22, 27]
    
#### 2 - Big-O gösterimini yazınız.
    O(n^2)
    
#### 3 - Time Complexity: Average case: Aradığımız sayının ortada olması, Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
    Best case: 2
    Average case: 16, 18
    Worst case: 27
    
#### 4 - Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
    Average case
    
#### 5 - [7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
    [7, 3, 5, 8, 2, 9, 4, 15, 6]
    
    1.Adım: [2, 3, 5, 8, 7, 9, 4, 15, 6]
    
    2.Adım: [2, 3, 4, 8, 7, 9, 5, 15, 6]
    
    3.Adım: [2, 3, 4, 5, 7, 9, 8, 15, 6]
    
    4.Adım: [2, 3, 4, 5, 6, 9, 8, 15, 7]
    
## PROJE 2
### **[16, 21, 11, 8, 12, 22] -> Merge Sort**

#### 1 -  Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
             [16, 21, 11, 8, 12, 22]
                  /            \ 
        [16, 21, 11]          [8, 12, 22]
          /      \             /        \ 
      [16, 21]    [11]       [8, 12]     [22]
        /   \       |         /   \        |  
    [16]    [21]   [11]     [8]    [12]   [22]
      \      /      |         \     /      | 
      [16, 21]    [11]        [8, 12]    [22]
        \   |      /           \   |     /                 
        [11, 16, 21]           [8, 12, 22]
           \   \    \          /   /   /
              [8, 11, 12, 16, 21, 22]
    
#### 2 - Big-O gösterimini yazınız.
    O(nlogn)
   
## PROJE 3
#### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
    [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
    Root: 5
    Root'un sağında: 7
    Root'un solounda: 3
     
                      5 
                  /       \
                3          7
              /   \      /   \
             1     4    6     8
            / \               | 
           0   2              9
