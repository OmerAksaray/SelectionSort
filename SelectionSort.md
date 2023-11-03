[22,27,16,2,18,6]
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?

Burada öncelikle dizideki en küçük sayıyı bütün sayıları kontrol edecek şekilde tarıyoruz. Taradığımızda en küçük sayının 2 olduğunu görüyoruz. 2 yi
dizinin en başındaki elemanla yer değiştirecek şekilde tekrardan yazıyoruz. ([2,27,16,22,18,6]). Şimdi ise 2 sayısının sağında kalanlarla bu işlemi yineliyoruz.
[2,6,16,22,18,27]. Şimdi 6 nın sağında kalanlar ile tekrardan bu işlemi yapıyoruz. [2,6,16,18,22,27] sonuç olarak bu diziye ulaşıyoruz. Burada diziyi sıraladık daha sonra bizden istenen
18 sayısı. Soldan başlayarak tek tek kontrol ediyoruz ve 5. sırada olduğunu görüyoruz. Burada best, worst ve average de n^2 dir çünkü her ihtimalde de biz sıralama yaparken 
bütün diziyi tek tek kontrol ediyoruz. Bu da bize n*(n+1)/2 den n^2 olarak buluruz.


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1- Dizinin en küçük elemanı 2 bu yüzden 2 ile 7 yer değiştirecek. [2,3,5,8,7,9,4,15,6]      
2- 2'nin sağında kalan sayılardan en küçük olanı 3 ve zaten doğru yerinde. [2,3,5,8,7,9,4,15,6] 
3- 3'ün sağında kalan sayılardan en küçük olanı 4 ve 5 ile yer değiştirmesi gerekiyor. [2,3,4,8,7,9,5,15,6] 
4- 4'ün sağında kalan sayılardan en küçük olanı 5 ve 8 ile yer değiştirecek. [2,3,4,5,7,9,8,15,6] 
