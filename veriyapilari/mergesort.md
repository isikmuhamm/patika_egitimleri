# Merge Sort Ödevi

[16, 21, 11, 8, 12, 22]

## Yukarı verilen dizinin merge sort türüne göre aşamalarını yazınız.

1. Adım: Dizi ikiye bölünür. [16,21,11], [8,12,22]
2. Adım: Diziler kendi aralarında tekrar ikiye bölünür. [16,21], [11] ve [8,12], [22]
3. Adım: Diziler birer elemana ulaşılana kadar tekrarlı şekilde ikiye bölünür. Bu dizi için son adıma üçüncü seferde ulaşıyor. [16], [21], [11] ve [8], [12], [22]
4. Adım: Diziler öbekler halinde sıralanıyor. [16,21],[11] ve [8,12],[22]
5. Adım: Diziler tekrar öbekler halinde sıralanıyor. [11,16,21] ve [8,12,22]
6. Adım: Diziler tekrar öbekler halinde sıralanıyor. [8, 11, 12, 16, 21, 22]

## Big-O gösterimini yazınız.

Merge sort isimli algoritma yapısı gereği log_2 tabanında n defa kıyaslama yaptığı ve diziyi ikiye bölüp tekrar birleştirme sırasında bu işlemi n defa tekrarladığı için karışıklık katsayısını O( n*log_2(n) ) olarak gösterebiliriz.
