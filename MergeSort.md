Merge Sort algoritması kullanılarak verilen dizinin sıralanması aşamaları:

[16, 21, 11, 8, 12, 22]

[16, 21, 11] [8, 12, 22]
[16] [21, 11] [8] [12, 22]
[16] [11, 21] [8] [12, 22]
[11, 16, 21] [8] [12, 22]
[8, 11, 16, 21] [12, 22]
[8, 11, 12, 16, 21, 22]
Big-O gösterimi: Merge Sort'un ortalama, en kötü ve en iyi durum karmaşıklığı O(n log n)'dir.