## Merge Sort

[16,21,11,8,12,22] -> Merge Sort

[16,21,11,8,12,22] -> Merge Sort

- Yukarýdaki dizinin sort türüne göre aþamalarýný yazýnýz.
- Big-O gösterimini yazýnýz.

| Aþamalar | Dizi | Ýþlem |
|---------|----------------|------------|
|1.| [16,21,11,8,12,22] | dizi tek elemanli diziler oluncaya kadar iki diziye ayrýlýr|
|2. | [16,21],[11] , [8,12],[22]|
|3.| [16],[21],[11],[8],[12],[22]|
|4.| [16,21],[8,11],[12,22]| Diziler karþýlaþtýrýlarak birleþtirilir
|5.| [8,11,16,21],[12,22]| dizilerdeki yerleþtirilmemiþ en küçük elemanlar karþýlaþtýrýlarak yeni listeye önce en küçük olacak þekilde eklenir. Geriye kalanlar da sýralanmýþ oldularý için direkt sona eklenir.
|6.|[8,11,12,16,21,22]|Tek bir sýralý liste elde edene kadar iþlem tekrarlanýr.

iþlem süresi = Log N + nlog ns olduðundan 

O(nLog(n))

