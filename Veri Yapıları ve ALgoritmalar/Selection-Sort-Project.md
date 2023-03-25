# Selection-Sort-Project
<p>
[22,27,16,2,18,6] -> Insertion Sort Project
Dizinin sort türüne göre aşamalarını yazınız.

*1-verilen örüntüye göre en küçük eleman bulunup, en baştaki eleman ile yer değiştirilir.
*[22,27,16,2,18,6] ->[2,27,16,22,18,6]--> 22 ile 2 yer değiştirir
*[2,27,16,22,18,6] ->[2,6,16,22,18,27]--> 27 ile 6 yer değiştirir
*[2,6,16,22,18,27] ->[2,6,16,22,18,27]--> 3. sırada  her şey aynı kalıyor.
*[2,6,16,22,18,27] ->[2,6,16,18,22,27]--> 22 ile 18 yer değiştirir
*[2,6,16,18,22,27] ->[2,6,16,18,22,27]--> **liste tamamlandı.

*2- Big-O Gösterimi*
Big-O gösterimi, tasarladığımız bir algoritmanın performansını ve zaman karmaşıklığını(time complexity) ölçmek için kullandığımız en önemli araçlardan biridir. O(n^2)

  Son dizide '[2,6,16,18,22,27]' 18 ortada olduğu için "Average Case" kapsamına girer.

  *3- Selection Sort*
  [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6] ->[2,3,5,8,7,9,4,15,6]--> 2 ile 7 yer değiştiriyor
[2,3,5,8,7,9,4,15,6] ->[2,3,4,8,7,9,5,15,6]--> 4 ile 5 yer değiştiriyor
[2,3,4,8,7,9,5,15,6] ->[2,3,4,5,6,9,8,15,7]--> 8 ile 5 yer değiştiriyor
[2,3,4,5,6,9,8,15,7] ->[2,3,4,5,6,7,8,15,9]--> 7 ile 9 yer değiştiriyor
[2,3,4,5,6,7,8,15,9] ->[2,3,4,5,6,7,8,9,15]--> 9 ile 15 yer değiştiriyor
</p>
[Patika](https://www.patika.dev/tr)