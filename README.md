# INSERTION SORT PROJECT
Patika Dev Profile: https://app.patika.dev/muratgulcan

## PROJE 1
[22,27,16,2,18,6] -> Insertion Sort

  1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
  2. Big-O gösterimini yazınız.
  3. Time Complexity:
      -Average case: Aradığımız sayının ortada olması,
      -Worst case: Aradığımız sayının sonda olması,
      -Best case: Aradığımız sayının dizinin en başında olması.
  4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


### 1. INSERTION SORT ###

İlk başlayacağımız sayı listenin başındaki sayı olduğundan dolayı 22'den başlarız ve sağına "|" işaretini çekeriz. Sonra da işaretin sağında kalan ifade ile karşılaştırız. Sağdaki sayı küçük ise "|" işaretinin soluna geçirtilerek solundaki küçük ve sağındaki büyük sayı olacak şekilde sıralanır. Eğer sayı büyük ise "|" işaretinin solundaki sayının sağına yazılır.


    [22|, 27, 16, 2, 18, 6]
    [22, 27|, 16, 2, 18, 6]
    [16, 22, 27|, 2, 18, 6]
    [2, 16, 22, 27|, 18, 6]
    [2, 16, 18, 22, 27|, 6]
    [2, 6, 16, 18, 22, 27]

### 2. BIG-O ###

    Best case    : O(n)
    Average case : O(n^2)
    Worst case   : O(n^2)

### 3. TIME COMPLEXITY ###

    Average case: The number we are looking for is in the middle.
    Worst case: The number we are looking for is at the end.
    Best case: The number we are looking for is at the beginning.

### 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız. ###

    Average case -> [2, 6, 16, 18, 22, 27]
