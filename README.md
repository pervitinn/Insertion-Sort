# Insertion-Sort
[22,27,16,2,18,6] -> Insertion Sort  1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
verilen öbeğin en küçük elemanı 2'dir 2 ile 22 swap yapar.[2,27,16,22,18,6]
ikinci en küçük eleman olan 6 ile 27 swap yapar.[2,6,16,22,18,27]
üçüncü en küçük elaman olan 16 zaten olması gereken yerde olduğu için swap yapmaz.
dördüncü en küçük eleman olan 18 ile 22 swap yapar.[2,6,16,18,22,27]
22 ve 27 elemanları zaten olması gereken yerde olduğu için herhangi bir swap yapmazlar ve aşamalar tamamlanır.



2-Big-O gösterimini yazınız.
O(n^2)



3-Time Complexity:
Average Case:Aradığımız sayının ortada olması
Worst Case:Aradığımız sayının sonda olması
Best Case:Aradığımız sayının dizinin en başında olması


4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Dizinin sıralanmış halinde .[2,6,16,18,22,27] 18 ne en başta(best case) ne en sonda(worst case) olmadığı için 18 average case kapsamına girer.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1- en küçük sayı olan 2 ile 7 swap yapar.[2,3,5,8,7,9,4,15,6]
2-3 zaten olması gereken yerde olduğu için herhangi bir yer değişimi olmaz.[2,3,5,8,7,9,4,15,6]
3-4 ile 5 swap yapar.[2,3,4,8,7,9,5,15,6]
4-en küçük 4. sayı olan 5 ile 8 swap yapıp yer değiştirir.[2,3,4,5,7,9,8,15,6]
www.patika.dev
