### [16,21,11,8,12,22] -> Merge Sort

### Q1 : Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

``
Answer : [16,21,11,8,12,22] -> [16,21,11] [8,12,22] -> [16] [21,11] [8] [12,22]
-> [16] [21] [11] [8] [12] [22] -> [16] [11,21] [8] [12,22] -> [11,16,21] [8,12,22] 
-> [8,11,12,16,21,22]
``

### Q2 : Big-O gösterimini yazınız.

``
Answer : O(nlogn)
``

Note: Merge Sort bir listeyi her adımda parçaya ayırıp tek eleman kalıncaya kadar bölüyor. Böldükten sonra sıralı bir şekilde bize sunuyor (Performans +).