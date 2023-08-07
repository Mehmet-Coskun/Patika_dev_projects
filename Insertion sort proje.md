# Insertion Sort Project

1. [22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
| Aşamalar| Dizi| İşlem|
|---------|----------------|------------|
| 1. adım | **22**,27,16,2,18,6|22 ilk eleman olduğu için sıralanmıs sayarız|
| 2. adım | **22,27**,16,2,18,6|22 den büyük  olduğu için 27 sonra gelir|
| 3. adım | **16,22,27**,2,18,6|16 22 den küçük olduğu için 22 den önce gelir|
| 4. adım | **2,16,22,27**,18,6|2 16 dan küçük olduğu için 16 dan önce gelir|
| 5. adım | **2,16,18,22,27**,6|sırası ile kontrol edilir ve 18, 16 dan büyük 22 den küçük yerine oturur| 
| 6. adım | **2,6,16,18,22,27**|sırası ile kontrol edilir ve 6, 2 den büyük 16 dan küçük yerine oturur, sıralama biter.|

O(n^2) karmaşıklığa sahiptir.

1. avarage case = n^2
2. worst case = n^2
3. best case = n

