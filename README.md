# Ordenação-de-Dados
Data Sorting exercises from College
|Complexity|Insertion|Selection|Bubble|Shell|Heap|Quick|Merge|Radix|
|:-|-:|-:|-:|-:|-:|-:|-:|-:|
|Worst Case|O(n²)|O(n²)|O(n²)|O(nlog²n)|O(nlogn)|O(n²)|O(nlogn)|O(nk)|
|Average Case|O(n²)|O(n²)|O(n²)|Depends|O(nlogn)|O(nlogn)|O(nlogn)|O(n+s)|
|Best Case|O(n)|O(n²)|O(n)|O(n)|O(nlogn)|O(nlogn)|O(nlogn)|O(n)|

*__Insertion Sort:__ Traverses the vector from left to right, leaving smaller values sorted to the left.
*__Selection Sort:__ Find the smallest value and place it in the first position, then the second value in the second position, and so on until all is sorted.
*__Bubble Sort:__ Traverses the vector several times comparing 2 to 2 elements. If it is not ordered, it performs the exchange and restarts the loop.
*__Shell Sort:__ Break the vector into multiple segments and apply sorting. At the end it applies the insertion sort.
*__Merge Sort:__ Divide into small groups and order them. Then join the two closest groups together and order them. The process continues until everything is sorted.
