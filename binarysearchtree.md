# Binary Search Tree Ödevi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

## Yukarı verilen dizinin Binary-Search-Tree aşamalarını yazınız.

### 1. Adım: Kök olarak 7 değerini seçiyorum.
### 2. Adım: Ağaca 5 değerini eklemek istiyorum. 5 değeri 7'den küçüktür.
	  7
	 /
	5
### 3. Adım: Ağaca 1 değerini eklemek istiyorum. 1 değeri 7'den ve 5'ten küçüktür.
	    7
	   /
	  5
	 /
	1
### 4. Adım: Ağaca 8 değerini eklemek istiyorum. 8 değeri 7'den büyüktür.
	    7
	   / \
	  5   8
	 /
	1
### 5. Adım: Ağaca 3 değerini eklemek istiyorum. 3 değeri 7'den, 5'ten küçük, 1'den büyüktür.
	     7
	    / \
	   5   8
	  /
	 1
	/ \
	   3
### 6. Adım: Ağaca 6 değerini eklemek istiyorum. 6 değeri 7'den küçük, 5'ten büyüktür.
	     7
	    / \
	   5   8
	  / \
	 1   6
	  \
	   3
### 7. Adım: Ağaca 0 değerini eklemek istiyorum. 0 değeri diğer tüm değerlerden küçüktür.
	      7
	     / \
	    5   8
	   / \
	  1   6
	 / \
	0   3
### 8. Adım: Ağaca 9 değerini eklemek istiyorum. 9 değeri diğer tüm değerlerden büyüktür.
	      7
	     / \
	    5   8
	   / \   \
	  1   6   9
	 / \
	0   3
### 9. Adım: Ağaca 4 değerini eklemek istiyorum. 4 değeri 7 ve 5'ten küçük, 1 ve 3'ten büyüktür.
	       7
	      / \
	     5   8
	    / \   \
	   1   6   9
	  / \
	 0   3
	      \
	       4
### 10. Adım: Ağaca 2 değerini eklemek istiyorum. 2 değeri 7 ve 5'ten küçük, 1'den büyük ve 3'ten küçüktür.
	       7
	      / \
	     5   8
	    / \   \
	   1   6   9
	  / \
	 0   3
	    / \
	   2   4
