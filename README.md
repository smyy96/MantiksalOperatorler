# Mantıksal Operatörler

```
Mantıksal operatörlerde,
And operatörünü bir çarpma işlemi gibi düşünebilirsiniz aynı şekilde
Or operatörünüde toplama işlemi gibi.
True = 1 ve False = 0 anlamına gelmektedir ve buna dayanarak işlemler yapılır.
```
![Ekran Alıntısı](https://user-images.githubusercontent.com/62007900/149238308-c0594ab6-6a8c-4ddc-ae03-51d393131aeb.JPG)

```
And'in çarpma işlemine benzediğini söylemiştim eğer and operatörünün olduğu koşullardan 
herhangi birinde false(0) değeri varsa sonuç false çıkar çünkü çarpma işleminde hangi 
sayı olursa olsun sıfır ile çarpıldığı zaman sonuç hep sıfır çıkar. Bu işlemde de aynı
mantık var bir tane false olması yeterli sonucu direk false'a cevirir.

1*0=0     True And False = False
0*0=0     False And False = False
0*1=0     False And True = False
1*1=1     True And True = True

```
```
Or ile yapılan koşullarda ise toplama işlemi gibi düşünüldüğü için bir tane true(1) değer olması yeterli
bu şekilde sonuç direk true çıkar.

1+1=1   True Or True = True 
1+0=1   True Or False = True 
0+1=1   False Or True = True 
0+0=0   False Or False = False 
```

