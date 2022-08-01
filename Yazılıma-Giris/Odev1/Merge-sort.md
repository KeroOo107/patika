# Merge Sort
https://app.patika.dev/keremcanmlmn
### Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
> - İlk olarak dizimizi [16,21,11] ve [8,12,22] olarak ikiye ayırıyoruz.
> - Bu dizileri tek eleman kalana kadar ikiye ayırıyoruz. [16,21] [11] [8,12] [22]
> - [16] [21] [11] [8] [12] [22]
> - Küçük olanı sola olacak şekilde ikili dizlerimizi oluşturuyoruz. [16,21] [8,11] [12,22]
> - Bu dizileri de sırayla birleştiriyoruz. [8,11,16,21] [12,22]
> -  [8,11,12,16,21,22]

Big-O gösterimini yazınız.
> O(nlogn)