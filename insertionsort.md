#Insertion Sort Ödevi

[22,27,16,2,18,6]

##Yukarı verilen dizinin insertion sort türüne göre aşamalarını yazınız.

1. Adım: 2, en küçük elemandır, 22 ile yer değiştirecek. [2,27,16,22,18,6]
2. Adım: 6, sıradaki en küçük elemandır, 27 ile yer değiştirecek. [2,6,16,22,18,27]
3. Adım: 16, sıradaki en küçük elemandır, yerinde kalacak.
4. Adım: 18, sıradaki en küçük elemandır, 22 ile yer değiştirecek. [2,6,16,18,22,27]
5. Adım: 22, sıradaki en küçük elemandır, yerinde kalacak.
6. Adım: 27, sıradaki en küçük elemandır, yerinde kalacak.

##Big-O gösterimini yazınız.

Her yeni sırayı bulurken n sayılı bir sistemde sırasıyla n-1, n-2, ... 2, 1 kıyaslama yapılarak ilerleniyor. Karışıklık seviyesi 1'den n-1'e kadar olan sayıların toplamıyla bulunur. Bu da (n-1)*n toplamından bulunur. Big-O gösterimi buradan O(n^2) şeklinde bulunur.

##Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?
Sıralanmış dizinin son hali [2,6,16,18,22,27] olacağından 18 sayısı ortada bulunacağı için sorunun yapısına göre "Average Case" durumunun kapsamına girmektedir.

##Selection sort'a göre sıralamanın ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6] dizisnin sıralaması yapılırken şu şekilde ilerlenir:

1. Adım: 2, en küçük elemandır, 7 ile yer değiştirecek. [2,3,5,8,7,9,4,15,6]
2. Adım: 3, sıradaki en küçük elemandır, yerinde kalacak.
3. Adım: 4, sıradaki en küçük elemandır, 5 ile yer değiştirecek. [2,3,4,8,7,9,5,15,6]
4. Adım: 5, sıradaki en küçük elemandır, 8 ile yer değiştirecek. [2,3,4,5,7,9,8,15,6]
