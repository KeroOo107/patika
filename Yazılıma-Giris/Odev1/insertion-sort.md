# Insertion Sort
Proje 1 [22,27,16,2,18,6]
1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız
> - 1-"2" yi ilk sıraya ve "22" yi "2" nin yerine koy. [2,2716,22,18,6]
> - 2- "2" den sonraki en küçük sayı "6" olduğu için "27" ile yerlerini değiştiriyoruz.[2,6,16,22,18,27]
> - 3- Kalan dört elemandan en küçüğü 16 olduğu için sıralama değişmiyor. [2,6,16,22,18,27]
> - 4- Kalan üç elemandan en küçüğü "18" "22" ile yer değiştiriyoruz. [2,6,16,18,22,27]
> 5- Son iki elamanın sıralaması da doğru olduğundan dolayı sonuca ulaşmış oluyoruz. [2,6,16,18,22,27]
2. Big-O gösterimini yazınız,
>"n" elemanımız olduğunu varsayarsak en küçük sayıyı bulmak için bütün elemanları (n) kontrol ediyoruz ve o elemanı en başa alıyoruz. Sıradaki en küçük sayıyı bulmak için ilk eleman hariç diğeri bütün elemanlara (n-1) bakıyoruz. İşlemlerin sonunda (n*(n+1)/2)'den sonucumuz O(n^2) olarak çıkar.

3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
> 18 sayısı dizinin ortasında yer aldığı için Average Case.

4. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
> - [2,3,5,8,7,9,4,15,6]
> - [2,3,5,8,7,9,4,15,6]
> - [2,3,4,8,7,9,5,15,6]
> - [2,3,4,5,7,9,8,15,6]