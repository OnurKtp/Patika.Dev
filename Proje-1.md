# Proje-1 

[22,27,16,2,18,6] -> Insertion Sort 

## 1-) Verilen diziyi Insertion Sort'a göre sıralayalım.

Adım-1 >> [2,27,16,22,18,6] <br>
Adım-2 >> [2,6,16,22,18,27]<br>
Adım-3 >> [2,6,16,18,22,27]<br>
Sonuç >>  [2,6,16,18,22,27]<br>
<br>


## 2-) Big-O gösterimini yapalım.

Her işlem yaptığımda ilgilendiğim veri 1 eksiliyor. Bir n kadar veri ile başladığımı düşünelim ve ilk sıralama işlemini yapalım.<br>
Sonraki sıralamada n-1 kadar veri ile ilgilenmem gerekecek. n+(n-1)+(n-2)+...+1'e kadar gidecektir. Bunun da matematiksel formülü n*(n+1)/2'dir.<br>
<br>
Formül n^2+n/2 şeklinde de gösterilebilir. Big-O gösteriminde en baskın değeri alacağımıza göre: O(n^2)'dir.<br>
<br>


## 3-) Time Complexity

Best Case: O(n)<br>
Average Case: O(n^2)<br>
Worst Case: O(n^2)<br>
<br>


## 4-) 18 sayısı hangi Case kapsamına girer ona bakalım.

18 sayısı Average Case kapsamına girer.<br>
<br>


## 5-) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

a) [2,3,5,8,7,9,4,15,6]<br>
b) [2,3,4,8,7,9,5,15,6]<br>
c) [2,3,4,5,7,9,8,15,6]<br>
d) [2,3,4,5,6,9,8,15,7]<br>
kalan adımlar,<br>
e) [2,3,4,5,6,7,8,15,9]<br>
f) [2,3,4,5,6,7,8,9,15]<br>
