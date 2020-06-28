# iv-hafta-odevi

## Cevaplar

- AddMVC vs AddMVCCore : http://ajaynallanagula.blogspot.com/2018/03/aspnet-core-addmvc-vs-addmvccore.html
- AddDateAnnotations nedir : https://www.mshowto.org/mvc-data-annotations-nedir-nasil-kullanilir-bolum-35.html
- Shanpshot nedir :

- First : Eğer size herhangi bir sonucun döneceği kesin ise kullanın, dönen sonuçlar içerisinde ilk elemanı alır. Eğer sonuç dönmez ise hata alırsınız.

- FirstOrDefault : Size dönen sonuçlar içerisinde ilk elemanı alır ve sonuç dönmez ise hata almazsınız.Bu seçimde de mantık SingleOrDefault ile aynıdır. Ancak bu seçimde istenen şartta ilk eleman seçilir.

- Single : Eğer size tek bir sonucun döneceği kesin ise kullanın. Birden fazla sonuç ya da hiç sonuç dönmezse hata alırsınız.Eğer seçimimiz sonucunda sadece bir tane eleman geleceği garanti ise, bu durumda Single seçimini kullanabiliriz. Eğer şartımızı sağlayan hiçbir eleman dönmezse veya şartımızı sağlayan birden fazla eleman dönerse, bu iki durumda da istisnalar fırlatılacak ve hata ile karşılaşmış olacağız.

- SingleOrDefault : ğer size tek bir sonucun döneceği kesin ise ve de sonuç dönmeyebilir ise kullanın. Birden fazla sonuç dönerse hata alırsınız.Eğer dizi içinden sadece bir tane sayı seçmek istiyorsak ve seçim şartımız sağlanmıyorsa, bu durumda int tipinin varsayılan değeri olan 0(sıfır) döndürülsün istiyorsak SingleOrDefault seçimini kullanmalıyız.

- En kısa null check nasıl yapılır? : https://www.geeksforgeeks.org/c-sharp-isnullorempty-method/#:~:text=C%23%20%7C%20IsNullOrEmpty()%20Method,not%20been%20assigned%20a%20value

- partial view nedir : https://www.teknologweb.com/asp-net-mvc-partial-view

- - -

*  Geri dönen bilgiye göre yeşil renkte onay mesajı gösterilmesi. (örneğin:view bag)

*  AddMVC - AddMVCCore - AddDateAnnotations nedir? Nerelerde eklenmelidir?

 * Shanpshot nedir? nasıl değişir? neden alınır?

*  Jquery Calender--> [Datapicker](https://jqueryui.com/datepicker/) --> DueAt'i takvim tipinde eklemek nasıl yapılır? Araştırınız. (DateTimeUffset tipinden atamalar oluşucak)

*  First- FirstOrDefault ve Single- SingleOrDefault nedir? Aralarındaki farkı araştırınız.

*  En kısa null check nasıl yapılır?

* partial view nedir?

* Farklı authentication bulup,aynı işleri farklı yollar ile yapanları araştırınız.

* Ödev- Razor Pages/MVC Projects karşılaştırmasını yapınız.
