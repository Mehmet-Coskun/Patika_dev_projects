## Merge Sort

[16,21,11,8,12,22] -> Merge Sort

[16,21,11,8,12,22] -> Merge Sort

- Yukar�daki dizinin sort t�r�ne g�re a�amalar�n� yaz�n�z.
- Big-O g�sterimini yaz�n�z.

| A�amalar | Dizi | ��lem |
|---------|----------------|------------|
|1.| [16,21,11,8,12,22] | dizi tek elemanli diziler oluncaya kadar iki diziye ayr�l�r|
|2. | [16,21],[11] , [8,12],[22]|
|3.| [16],[21],[11],[8],[12],[22]|
|4.| [16,21],[8,11],[12,22]| Diziler kar��la�t�r�larak birle�tirilir
|5.| [8,11,16,21],[12,22]| dizilerdeki yerle�tirilmemi� en k���k elemanlar kar��la�t�r�larak yeni listeye �nce en k���k olacak �ekilde eklenir. Geriye kalanlar da s�ralanm�� oldular� i�in direkt sona eklenir.
|6.|[8,11,12,16,21,22]|Tek bir s�ral� liste elde edene kadar i�lem tekrarlan�r.

i�lem s�resi = Log N + nlog ns oldu�undan 

O(nLog(n))

