# odev1_2tribonacci
1-)Algoritmanın Amacı ne için kullanıldığı/kullanılabileceği:
Bu programın amacı, kullanıcının girdiği n değerine göre Tribonacci dizisinin n'inci elemanını hesaplamaktır. 
Tribonacci dizisi, Fibonacci dizisine benzer bir matematiksel dizidir ve ilk üç elemanı 0, 1, 1'dir. 
Daha sonra her eleman, önceki üç elemanın toplamıdır. Yani dizinin dördüncü elemanı, ilk üç elemanın toplamı olan 2'dir. 
Beşinci eleman, 1+1+2=4'dür. Altıncı eleman, 1+2+4=7'dir ve böyle devam eder.

Tribonacci dizisi, birçok matematiksel problemin çözümünde kullanılabilir. Örneğin, bir işlem sırasında her bir adımın 
önceki üç adımın sonucuna bağlı olduğu durumlarda Tribonacci dizisi kullanılabilir.
Ayrıca, Tribonacci sayıları, bilgisayar algoritmalarının analizi ve doğrusal olmayan dinamik sistemlerin modellenmesi gibi alanlarda da kullanılabilir.

2-)Programın çalışma şekli :
programın çalışma şekli şu adımlardan oluşur:
Program çalıştırıldığında, Main() metodu çağrılır.
Kullanıcıdan bir n değeri girilmesi istenir.
Kullanıcının girdiği değer alınır ve integer tipine dönüştürülür.
Tribonacci(n) metodu çağrılır ve n değeri metoda parametre olarak geçilir.
Tribonacci() metodunda, n'in değeri kontrol edilir. Eğer n 0, 1 veya 2 ise, ilgili değer geri döndürülür.
Eğer n 3 veya daha büyükse, bir for döngüsü kullanılarak Tribonacci dizisinin n'inci elemanı hesaplanır.
Hesaplanan değer, Main() metodunda Console.WriteLine() metodunu kullanarak ekrana yazdırılır.
Program sonlanır.
Yani program, kullanıcının girdiği n değerine göre Tribonacci dizisinin n'inci elemanını hesaplar ve sonucu ekrana yazdırır.
