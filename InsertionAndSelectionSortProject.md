Insertion Sort algoritması kullanılarak verilen dizinin sıralanması aşamaları:

[22, 27, 16, 2, 18, 6]

[22] 27 16 2 18 6
[22, 27] 16 2 18 6
[16, 22, 27] 2 18 6
[2, 16, 22, 27] 18 6
[2, 16, 18, 22, 27] 6
[2, 6, 16, 18, 22, 27]
Big-O gösterimi: Insertion Sort'un ortalama, en kötü ve en iyi durum karmaşıklığı O(n^2)'dir.
Dolayısıyla, 18 sayısı, Average case (Ortalama durum) kapsamına girer.


[7, 3, 5, 8, 2, 9, 4, 15, 6]

Adım 1:
[2, 3, 5, 8, 7, 9, 4, 15, 6] - En küçük eleman olan 2, dizinin başına yerleştirilir.

Adım 2:
[2, 3, 5, 8, 7, 9, 4, 15, 6] - İkinci en küçük eleman olan 3, zaten doğru konumda olduğu için yer değiştirme yapmadan geçilir.

Adım 3:
[2, 3, 4, 8, 7, 9, 5, 15, 6] - Üçüncü en küçük eleman olan 4, dizinin başına yerleştirilir.

Adım 4:
[2, 3, 4, 5, 7, 9, 8, 15, 6] - Dördüncü en küçük eleman olan 5, dizinin başına yerleştirilir.

Bu adımlar sonucunda, verilen dizinin Selection Sort ile ilk 4 adımı gerçekleştirilmiştir.
