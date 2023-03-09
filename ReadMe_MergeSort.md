# Patika Data Structures and Algorithms
This study has done for Patika.dev - Data Structures and Algorithms - https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje

Bu çalışma Veri Yapıları ve Algoritmaları dersi için oluşturulmuştur. Soru ve çözümü yer almaktadır.
https://app.patika.dev/ScienceHunter

## Proje 2

[16, 21, 11, 8, 12, 22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

#### **Çözüm:** 
Merge Sort(Birleştirme Sıralaması) bir dizi öğeyi sıralamak için kullanılan bir sıralama algoritmasıdır. İşlemin temel prensibi, dizi öğelerinin birbirleriyle karşılaştırılması ve ardından sıralanmış bir şekilde birleştirilmesidir.

İşlemin adımları şu şekildedir:

- Dizi ortadan ikiye bölünür.
- Her yarısı, aynı işlemle tekrar ortadan ikiye bölünür, bu işlem dizinin elemanları tek bir eleman kalana kadar tekrarlanır.
- Her parça teker teker karşılaştırılarak, sıralı bir şekilde birleştirilir.
- Bu işlem sırasında öğeler birbirleriyle karşılaştırılırken, önce sol yarım, sonra da sağ yarım elemanlar karşılaştırılır ve daha küçük olan öğe önce sıralanır. Bu adımdan sonra, bir sonraki adımda sıralanmış öğeler, birleştirilir.

**Sıralanması istenilen dizi :** [16, 21, 11, 8, 12, 22]

![image](https://user-images.githubusercontent.com/17726687/223878658-2d295975-5017-4718-8934-fee41d8476e5.png)


İlgili dizininin Big-O gösterimi: Başlangıçta n eleman varken bir sonrakinde yarısı olacak şekilde en son 1 eleman kalana kadar devam edecektir. Bu durumda $$2^x = n$$ ise 1 elemana ulaşılana kadar $$x = log(n)$$ kadar bir iterasyon gerçekleşecektir. n tane eleman olduğu düşünüldüğünde $$Big-O(n*log(n))$$ dir.
