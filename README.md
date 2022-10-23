# mergesort
Veri Yapıları ve Algorritmalar Patika Dev Ödevi 2 Merge Sort
[16,21,11,8,12,22] 
Soru1: Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Sayıları üçerli iki gruba böleriz. 
Solda 16, 21, 11 olur. Sağ tarafta 8, 12, 22 olur. 
Solda İkinci aşamada 16 yı ayrı yazarız. 21 ve 11 yan yana yazarız. 
Solda üçüncü aşamada 21 ve 11 i ayrı yazarız. 
Solda 4. aşamada 16 tek başına olduğu için aynen yazarız. 11 21 in soluna yazılır. 
Solda 5. aşamada 11, 16, 21 olacak şekilde sıralarız. 
Her seferinde küçük olan sayı büyük olan sayının soluna yazılarak ilerlenir. 
Sağda ikinci aşamada 8, 12 ve 22 iki parçaya ayrılır. 12 ve 22 yan yana yazarız. 8 tek başına yazılır. (Burada istersek 8 ve 12 yi yan yana yazıp, 22 yi tek başına da yazabilirdik. Amaç sayıları gruplandırarak tekil hale gelene kadar devam etmek.) 
Sağda üçüncü aşamada 12 ve 22 ayrı ayrı yazılır. 
Sağda dördüncü aşamada 8, 12 ve 22 tekil olarak yazılır. Sıralama yapılır ve küçükten büyüğe doğru sıralama yapılarak bağlanır. 
Elimizde küçükten büyüğe doğru sıralanmış üçerli iki sayı grubu var.
Burada işimiz artık çok daha kolay. 
Çünkü en solda yer alan sayılar iki tarafta da sayı grubunun en küçükleri. 
Solda 11 sağda 8 en başta yer alan en küçük sayılardı. 
Onlar arasında küçük olan 8 sayısı en sola yazılır. 
11 sayısından daha küçük sayı olmadığı için ikinci sıraya 11 yazılır. 
Sonra aynı karşılaştırma 16 ve 12 için yapılır. 
12 üçüncü sıraya 16 4. sıraya yazılır. 
Bu şekilde devam ederek 8, 11, 12, 16, 21, 22 sayıları merge sort yöntemi ile sıralanmış olur. 
Soru2: Big-O gösterimini yazınız.
Soruda sıralama işlemi yaparken işlemlerin toplamı 2ˣ=n olur. 
Bu da x=logn demektir. Yani ben doğru dizilim için logn kere işlem yapmış olurum.
Big(O) notation gösterimi de O(nlogn) olur.
