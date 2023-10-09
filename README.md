# Markdown Kullanımı
 **Markdown nedir** ?
 1. Markdown, biçimlendirme öğeleri eklemenize olanak tanıyan bir işaretleme dilidir.
 2. Markdown sadece teknik yazılar için değil, genel olarak her türlü yazı için son derece kullanışlıdır.

## İçindekiler
- [Başlık](#başlık)
- [Listeler](#listeler)
- [Vurgulama](#vurgulama)
- [Kod](#kod)
- [Bağlantılar](#bağlantılar)
- [Blok Alıntılar](#blok-alıntılar)
- [Görsel Ekleme](#görsel-ekleme)
- [E-postalar](#e-postalar)
- [Tablo](#tablo)
- [HTML](#html)

## Markdown Örnekleri

1. **Başlık**
    * Başlıklar, içerikleri bölümler halinde düzenlemek için kullanılır. En büyüğü h1 ve en küçüğü h6 olmak üzere h1'den h6'ya kadar 6 seviye vardır. Normalde, tüm dosyanızda yalnızca bir h1 başlığı olmalıdır, bu da belgenin başlığıdır. 

    * Bir başlık # ile başlar. sayısı başlık seviyesini gösterir, örneğin;
  
```
#h1
##h2
###h
####h4
#####5
######h6
```

2. **Listeler**
   
     *İki tür liste vardır - sıralı ve sırasız.
     *Sırasız bir liste oluşturmak için, Örnek

```
- h1
- h2
- h3

```
böyle bir listeleme yapacaktır


- h1
- h2
- h3

    *Sıralı bir liste yapmak için, listedeki öğenin önüne 1. ve ardından bir boşluk koyun. Numarayı manuel olarak artırmanıza gerek yoktur, bu otomatik olarak yapılacaktır. Bu çok kullanışlıdır.


```

1. h1
1. h2
1. h3

```

böyle bir listeleme yapacaktır

1. h1
1. h2
1. h3


Listeler birden fazla seviyede iç içe de yerleştirilebilir. 

İki seviyeli sırasız liste örneği:

```

-  liste 1
    - liste 1.1
    - liste 1.2
- liste 2
    - liste 2.1
    - liste 2.2

1. liste 1
    1. liste 1.1
    1. liste 1.2
1. liste 2
    1. liste 2.1
    1. liste 2.2

```


**böyle bir listeleme yapacaktır**

-  liste 1
    - liste 1.1
    - liste 1.2
- liste 2
    - liste 2.1
    - liste 2.2

1. liste 1
    1. liste 1.1
    1. liste 1.2
1. liste 2
    1. liste 2.1
    1. liste 2.2
  

  

3. **Vurgulama**

```
**Kalın yap** kalın yapacaktır
*İtalik yap* italik yapacaktır
***Kalın ve italik yap*** kalın ve italik yapacaktır
```

**Kalın yap** kalın yapacaktır

*İtalik yap* italik yapacaktır

***Kalın ve italik yap*** kalın ve italik yapacaktır

4. **Kod**

  - yazı içinde kod bloğu örneği ters tırnak (``) 

    ``` h1 h2 `h3` ```

    h1 h2 `h3`

  - Kod Bloğu örneği ters tırnak (```) 


```
function sayHello() {
console.log("Merhaba, Dünya!");
}
sayHello();

Yukarıdaki kod, Markdown'da üç arka üst üste ters tırnak (```) kullanılarak bir kod bloğu oluşturur. Bu kod bloğu içindeki kodlar renkli ve düzgün bir biçimde gösterilir.
```


5. **Bağlantılar**
   
    -Bir bağlantıyı eklemek için yapılması gereken

   `[Bağlantı metni](Bağlantı URL'si)`

6. **Blok Alıntılar**

    `> Bu bir blok alıntı örneğidir. Bu metin alıntı yapılmış bir bölümü temsil eder. `

     ```
        > İlk satırı alıntıya dahil ediyorum.
        > İkinci satırı da alıntıya ekliyorum.
        > Blok alıntılar birden fazla satırdan oluşabilir.
     ```
     - Çıktısı

        > Bu bir blok alıntı örneğidir. Bu metin alıntı yapılmış bir bölümü temsil eder.
        
        > İlk satırı alıntıya dahil ediyorum.
        
        > İkinci satırı da alıntıya ekliyorum.
        
        > Blok alıntılar birden fazla satırdan oluşabilir.
        

7. **Görsel ekleme**
   
       -![Metin](görsel URL)

9. **Tablo**
 ```
| Başlık 1 | Başlık 2 | Başlık 3 |
| -------- | ------- | ------- |
| Hücre 1  | Hücre 2  | Hücre 3  |
| Hücre 4  | Hücre 5  | Hücre 6  |
```

Bu sözdizimi, bir tablo oluşturmak için kullanılır.
Her satır bir tablo satırını temsil eder ve dikey çubuklar (|) ile sütunlara ayrılır.
İlk satır genellikle tablo başlıklarını içerir ve ikinci satır, sütunları ayırmak için kullanılan çizgi ile (---) doldurulur. 
Diğer satırlar ise tablo hücrelerini içerir.

| Ürün     | Miktar | Fiyat   |
| -------- | ------ | ------- |
| Elma     | 3      | 20  |
| Muz      | 2      | 25  |
| Portakal | 5      | 20  |


9. **E-postalar**

   
E-postanızı <> içine koyun ve birisi bağlantıya tıkladığında varsayılan e-posta uygulaması başlatılacaktır.

Örnek

`<js@example.com>`

<js@example.com>

10. **HTML**
   
Markdown dosyalarında ayrıca HTML etiketlerini kullanabilirsiniz ve bunlar HTML kurallarına göre işlenir.

Aşağıdaki örneği deneyin:

```
<div>
    <p>Bu bir paragraf</p>
    <p>Sonraki bir sırasız liste olacak</p>
    <ul>
        <li>madde 1</li>
        <li><b>kalın yazı</b></li>
        <li><span style="color: red;">kırmızı renk yazı</span></li>
    </ul>
</div>
```





















