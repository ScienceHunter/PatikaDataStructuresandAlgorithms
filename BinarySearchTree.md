# Patika Data Structures and Algorithms
This study has done for Patika.dev - Data Structures and Algorithms - (https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/binary-search-tree-proje)

Bu çalışma Veri Yapıları ve Algoritmaları dersi için oluşturulmuştur. Soru ve çözümü yer almaktadır.
https://app.patika.dev/ScienceHunter

## Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

#### **Çözüm:** 
![image](https://user-images.githubusercontent.com/17726687/223901956-a0224c8d-f50f-4c2b-ac31-42d82dbdf27e.png)

1. Yukarıdaki görseldeki gibi öncelikle 7 değeri eklenir. Daha önceden eklenmiş bir değer olmadığından 7 değeri ağacımızın root değeri olarak belirlenmiş olur.
2. Devamında 5 değeri gelmektedir. 5, 7'den küçük olduğu için root’un solunda yer alır.
3. Devamında 1 değeri gelmektedir. 1, 5'ten küçük olduğu için 5'in solunda yer alır.
4. Sonrasında 8 değeri gelmektedir. 8, root 7'den büyük olduğu için root’un sağında yer alır.
5. 3 değeri 5'ten küçüktür ancak daha evvel 5'in soluna 1'i eklediğimizden 3 1'den büyük olduğu için 1'in sağında yer alacaktır. 
6. 6 değeri 7'den küçüktür, 5'ten de büyüktür. 5'in sağına gelecek şekilde işlem görecektir.
7. 0 değeri 1'den küçüktür. Bu nedenle 1'in solunda yer alacaktır.
8. 9 değeri 8'den büyüktür. Bu nedenle 8'in sağında yer alacaktır. 
9. 4 değeri 5'ten küçük - 3'ten büyüktür. Bu nedenle 3'ün sağında yer alacaktır. 
10. 2 değeri 3'ten küçüktür. Bu nedenle 3'ün solunda yer alacaktır.

Görsel için faydalanılan kaynak: https://www.cs.usfca.edu/~galles/visualization/BST.html
