# Patika Data Structures and Algorithms
This study has done for Patika.dev - Data Structures and Algorithms - https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/insertion-sort-proje

Bu çalışma Veri Yapıları ve Algoritmaları dersi için oluşturulmuştur. Soru ve çözümler yer almaktadır.
https://app.patika.dev/ScienceHunter

## Proje 1
1. [22, 27, 16, 2, 18, 6] -> Insertion Sort

Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

- **Average case:** Aradığımız sayının ortada olması
- **Worst case:** Aradığımız sayının sonda olması
- **Best case:** Aradığımız sayının dizinin en başında olması.

#### **Çözüm 1:** 
Insertion Sort(Araya Koyma Sıralaması) ilgili dizinin ilk olarak birinci elemanını ele alır. Sonrasında sıradaki elemanla aralarında bir sıralama yapar.

**Sıralanması istenilen dizi :** [22, 27, 16, 2, 18, 6]

**Başlangıç Hali :** [22] [27, 16, 2, 18, 6]

![image](https://user-images.githubusercontent.com/17726687/223804395-0c1679e8-3a6d-4768-9b97-cc5b154f362a.png)
İlgili dizininin Big-O gösterimi: Başlangıçta n eleman varken 1 eleman kalana kadar devam edecektir. Bu durumda $$n + (n-1) + (n-2) + ... + 1 = \frac{n(n+1)}{2} = \frac{n^2}{2}+\frac{n}{2}$$ olacaktır. Bu durumda en kötü senaryoya göre $${n^2}$$ baskın durumda olacaktır. Öyleyse $$Big-O({n^2})$$ dir.

İlgili dizi sıralandıktan sonra 18 sayısı ortalarda olduğundan **Average Case** durumuna uymaktadır.

2. [7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Tüm adımları içermekle birlikte ilk dört adım sarı ton ile belirtilmiştir. 

![image](https://user-images.githubusercontent.com/17726687/223832731-4d15af71-4bb4-45f0-9cc6-9ea85810bbdb.png)

