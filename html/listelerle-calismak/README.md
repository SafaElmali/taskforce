# Listeleme Etiketleri


Listeleri iki ana başlık altında listeleyebiliriz;

1. Sıralı Listeler
2. Sırasız Listeler



###  Sıralı Listeler

Sıralı listeler ardışık liste numaraları vermek için kullanılır. Sıralı listelerden yararlanmak için **<ol> **etiketi kullanılır.

````html
    <p> Gerçek <b>tereyağı</b> nasıl anlaşılır ?</p>
    <ol>
        <li>Oda sıcaklığında tamamen erimez</li>
        <li>Suyun içinde tek parça halinde çözünür</li>
        <li>Tereyağı rengi sarı yada beyaz olabilir</li>
    </ol>
````



**Ekran çıktısı:**

![sıra](figures/sıra.PNG)

şeklinde olur.



Liste başındaki sıralandırmayı rakamdan başka **roma rakamı veya alfabetik** şeklinde de yapabiliriz. Bunun için **type** özelliğini kullanmamız gerekir.



````html
<ol type="I">
  <li>Javascript</li>
  <li>C#</li>
  <li>Php</li>
</ol>
````



**Ekran çıktısı:**

![siralama](figures/siralama.png)



````html
<ol type="A">
  <li>Javascript</li>
  <li>C#</li>
  <li>Php</li>
</ol>
````



**Ekran çıktısı:**

![alfabetik](figures/alfabetik.PNG)



### Sırasız Listeler 

**Sırasız listeler** numaralandırma olmadan oluşturduğumuz  listeleredir. Her bir liste elemanı bir satırı kaplayacak şekilde yani blok etiket şeklinde oluşturulur.



````html
<ul>
  <li>Çay</li>
  <li>Türk Kahvesi</li>
  <li>Süt</li>
</ul> 
````



**Ekran çıktısı:**

- Çay
- Türk Kahvesi
- Süt

şeklinde olur.



Liste elemanlarının başındaki içi dolu daireyi değiştirebilir veya silebiliriz.



**Silmek İçin: **

````html
<ul style="list-style-type:none">
  <li>Çay</li>
  <li>Türk Kahvesi</li>
  <li>Süt</li>
</ul>
````



**Ekran çıktısı**:

​       Çay

​       Türk Kahvesi

​       Süt

şeklinde olur.



Liste başındaki içi dolu daireyi değiştirmek için ise **disc, square, circle** değerlerini kullanabiliriz.



````html
<ul style="list-style-type:square">
  <li>Telefon</li>
  <li>Bilgisayar</li>
  <li>Yazıcı</li>
</ul>
````



**Ekran çıktısı:**

![kare](figures/kare.PNG)




### Sorular
1. Sırasız liste oluşturmak için kullanılan etiket hangisidir ?

A) < list>
B) < nl>
C) < ul>
D) < ol>

2. Sıralı liste oluşturmak için kullanılan etiket hangisidir ?

A) < dl>
B) < list>
C) < ul>
D) < ol>



1)C  2)D


### Kaynak

https://www.geeksforgeeks.org/html-li-tag/
