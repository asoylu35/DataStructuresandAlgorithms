#Proje 1
##[22,27,16,2,18,6] -> Insertion Sort
###Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
-Dizinin ikinci elemanı başlangıç elemanı olarak seçilir.Bu dizide 27 ikinci eleman.
-Daha sonra 27 ile 22 kıyas edilir. 22 < 27 olduğu için sıralama değişmiyor. [22,27,16,2,18,6]
-Şimdi de üçüncü eleman olan 16 ile 27 kontrol edilir. 16 < 27 ancak aynı zamanda 16 < 22 olduğundan 16 sayısı en başa alınır ve sayılar sırasına göre kaydırılır. Dizinin yeni hali 16,22,27,2,18,6 olur
-Bu adımda da sıra dördüncü eleman yani 2 sayısına bakmaya gelmiştir. 2 hepsinden küçük olduğu için direkt sola kaya kaya en başa yerleşir ve diğer sayılarda birer sağa kayarak kendi sırasını alırlar. Dizinin son hali: 2,16,22,27,18,6 olacaktır.
-Bu adımda da sıra beşinci eleman yani 18 sayısına bakmaya gelmiştir. 16<18 ve 18<22 olduğu için yeni sıralama 2,16,18,22,27,6
-Son olarak altıncı eleman 6<16 olduğu için direkt 16nın yerine gelir.Son sıralama 2,6,16,18,22,27dir.
[2,6,16,18,22,27]
Big-O gösterimini yazınız.
-Big-O=O(n^2)
### Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
18 sayısı tam ortadaki sayı olduğu için average case kapsamına girer.
##Selection Sort
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
İlk olarak en küçük elemanı belirliyoruz.Bu eleman 2
-En küçük elemanla (2) en baştaki elamanı yer değiştiriyoruz.
[2,3,5,8,7,9,4,15,6]
-İkinci en küçük elemanı buluyoruz(3).Onun yeri doğru olduğu için sıralamada bir değişiklik olmuyor.Üçüncü küçük eleman 4 onunla da 5in yerini değiştiriyoruz.2,3,4,8,7,9,5,15,6
-Diğer en küçük eleman 5 o da 8 ile yer değiştiriyor.2,3,4,5,7,9,8,15,6
- Diğer en küçük eleman 6, onu da 7 ile yer değiştiriyoruz. 2,3,4,5,6,9,8,15,7



