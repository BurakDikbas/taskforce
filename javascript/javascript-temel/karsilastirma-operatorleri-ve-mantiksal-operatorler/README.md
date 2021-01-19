# Karşılaştırma Operatörleri ve Mantıksal Operatörler

## Karşılaştırma Operatörleri 

Karşılaştırma operatörleri, değişkenler veya değerler arasındaki eşitlik ve farkı bulmak için kullanılır. Bu iki değerin karşılaştırmasını yaparak true (doğru) veya false (yanlış) sonucu verir.

##### == Eşitse
```
var a = 10;
var b = "10";
console.log(a==b)  "Ekranda çıkan sonuç = true"
```
a ve b değeri birbirine eşit olduğu için sonuç **true** olacaktır.

##### === Hem değeri hem de türü eşitse

```
var a = 10;
var b = "10";
console.log(a===b)  "Ekranda çıkan sonuç = false"
```
a ve b değeri arasında üç tane eşittir olmasından ötürü burada hem değerin hem de türün eşit olup olmadığı kontrol edilecektir. a ve b değişkenin değeri aynı olmasına karşın türleri farklı olduğu için sonuç **false** olacaktır.

##### != Eşit değilse
```
var a = 10;
var b = "10";
console.log(a!=b)   "Ekranda çıkan sonuç = false"
console.log(a!==b)  "Ekranda çıkan sonuç = true"

var c= "kodluyoruz"
var d= "javascript"
console.log(c!=d)  "Ekranda çıkan sonuç = true"
```
a ve b değişkenimiz birbirine eşit değil ise sonucumuz true dönecektir. İlk logumuzda a'nın değeri ile b'nin değeri aynı olduğu için çıkan sonucumuz **false** olacaktır. İkinci logumuzda ise değerleri aynı olmasına karşın tür kontrolünün yapılıyor olmasından olmasından dolayı değerler eşit olmayacaktır ve **true** sonucumuz çıkacaktır. Üçüncü eşit değilse karşılaştırma operatöründe ise iki string ifade karşılaştırılmıştır ve içerdeki iki değer birbirinden farklı olduğu için **true** sonucu dönecektir.

#####  < Küçükse

```
var a = 10;
var b = 10;
console.log(a<b)  "Ekranda çıkan sonuç = false"
```

a'nın b'den küçük olması durumunda sonucumuz true olacaktır. Fakat yukarıdaki örnekte a değişkeni b'den küçük değildir ve sonucumuz **false** dönecektir.

#####  <= Küçük veya eşitse

```
var a = 10;
var b = 10;
console.log(a<=b)  "Ekranda çıkan sonuç = true"
```

a'nın b'den küçük olması veya eşit olması durumunda durumunda sonucumuz true olacaktır. a değişkeninin değeri ile b değişkeninin değeri eşit olmasından dolayu sonucumuz **true** dönecektir.

#####  > Büyükse ve >= Büyük veya eşitse

```
var a = 20;
var b = 10;
console.log(a>b)  "Ekranda çıkan sonuç = true"

var c = 20;
var d = 20;
console.log(c>=d)  "Ekranda çıkan sonuç = true"

```
a değerimiz b değerimizden büyük olması durumunda true dönecektir. a ve b değişkenleri kıyaslandığında a'nın daha büyük olmasından dolayı **true** sonucunu aldık.

c değerimizin d'den büyük veya eşit olması durumunda true olmaması durumunda false sonucu çıkacaktır. a değerimiz b ye eşit olduğu için sonucumuz **true** olmuştur. 

## Kaynakça

https://www.yusufsezer.com.tr/javascript-operatorler/

https://www.btdersleri.com/ders/JavaScript-Kar%C5%9F%C4%B1la%C5%9Ft%C4%B1rma-ve-Mant%C4%B1ksal-Operat%C3%B6rler