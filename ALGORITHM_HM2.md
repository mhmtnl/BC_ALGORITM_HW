1.[16,21,11,8,12,22] -> Dizinin merge sort türüne göre aşamalarını yazınız.
     
    Sayı grubunu tek tutup sıra sıra incelemek yerine bunu daha küçük sayı grupları içinde aynı anda yapmak daha hızlı sonuç almaya yarayacaktır. 
    Elemanlar tek kalana kadar iki parçaya ayırmak :   
                                                     1- [16,21,11] - [8,12,22]
                                                     2- [16], [21,11] - [8,12], [22]
                                                     3- [16], [11,21] - [8,12], [22]
                                                     4- [11,16,21] -[8,12,22]
                                                     5- [8,11,12,16,21,22]


2.Big-O gösterimini yazınız.
    O(n log n)
