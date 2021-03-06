﻿
# Açık Kaynak Yazılım Lisansları ve Karşılaştırması:
Açık kaynak lisansları özel izin istemeksizin bir projeye katkıda bulunmayı kolaylaştıran yetkilerdir. Yazılan yazılımın kolayca paylaşılmasını ve ortadaki bürokratik engellerin kalkmasını sağlar. Ayrıca paylaşılan yazılımın yazarını koruyarak yazarın yaptığı katkıların unutulmamasını sağlar.

 ## 1.)MIT Licence
 En yaygın kullanılan lisans türlerinden biridir. MIT tarafından yayınlandığı için adı da aynı şekilde MIT olarak geçer. Çok kullanışlıdır.
 -  Yazılımı dağıtabilirsiniz.
 -   Yazılımı satabilirsiniz ve kaynak kodunu sağlamak zorunda değilsiniz.
 -   Kaynak kodunu alan herkes değiştirebilir, yeni versiyonlarını yayınlayabilir.
 -   Ticari olarak kullanabilirsiniz.

 ## 2.) Apache Licence
 Apache lisansının MIT’den bir farkı yoktur. Sadece yazılımınızı dağıtırken kullandığınız Apache lisanslı ürünlerin lisanslarını da dağıtımınıza eklemeniz gerekiyor. Yani kısaca emeğe saygı konusu daha önemli tutulmuş bu lisansta.
 -  Tüm kopyaları, değiştirilmiş veya değiştirilmemiş, lisansın bir kopyası eşliğinde dağıtılabilir yada kullanılabilir.
 -   Bütün değişiklikler, değiştirilmiş olarak işaretlenmelidir.
 -   Ticari olarak kullanabilirsiniz.
  ## 3.)GNU General Public Licence
  GNU lisansı da MIT gibi aynı şekilde size yazılımın kodlarına erişim konusunda herhangi bir kısıtlama getirmez. Fakat MIT lisansına göre kullanım açısından bazı kısıtlamalar getirir. Bu kısıtlamaların en önemlisi eğer yazılımında GNU lisansına sahip bir ürün kullandıysanız ve ürünü dağıtmaya başlarsanız sizin yazılımınız da GNU lisansına sahip olmalıdır. Yani yazılımın kendi geliştirdiğiniz kısımlarının da kaynak kodlarını paylaşmak zorundasınız. Dolayısı ile kaynak kodlarını paylaştığınız bir yazılımı ticari olarak satmak zor olacaktır.
 -  Kopyalayabilirsiniz.
-   Dağıtabilirsiniz.
-   İstediğiniz değişiklikleri yapabilirsiniz.
-   Yazılımın her yeni versiyonu bu lisansı kullanmak zorundadır.

## 4.) Creative Commons
Bu lisans türleri çok gözde değildir. Aşağıdakileri sağlar.
-   Yazılımın yazarı her zaman eklenmelidir. Bunun haricinde kopyalamak, yayınlamak serbesttir.
-   Yazılım ticari amaçlarla kullanılamaz.
-   Yazılımı değiştiremezsiniz, sadece orjinalini kullanabilirsiniz.
[KAYNAK1](https://www.yusufaytas.com/acik-kaynak-lisanslari/)
[KAYNAK2](https://www.yusufaytas.com/acik-kaynak-lisanslari/)
# merge,squash,rebase arasındaki farklar nelerdir?
## Merge Pull Request:
Github'da bir "pull request"de **Merge pull request** i seçtiğinizde tüm commitler bir **branch** tan temel **branch** a birleştirme kaydı yolu üzerinden eklenir.

![RESİM](https://camo.githubusercontent.com/ebd45dc824af281f97fc4310e52545c903d615aa593a750e3572c615625365dc/68747470733a2f2f646f63732e6769746875622e636f6d2f6173736574732f696d616765732f68656c702f70756c6c5f72657175657374732f7374616e646172642d6d657267652d636f6d6d69742d6469616772616d2e706e67)

## Squash and merge:
Github'da bir "pull request"de **Squash and merge** i seçtiğinizde bir **Pull request** in commitleri tek bir commit olarak sıkıştırılır.Katkıda bulunanın tüm kişisel commitlerini görmek yerine, commitler tek bir bir committe kombinlenerek **default branch** ta merge edilir.
![resim](https://camo.githubusercontent.com/aaf50a0f3a94a0ea112ca3fef918c02f334347e5f09d4e5663eab2dd2f5073f8/68747470733a2f2f646f63732e6769746875622e636f6d2f6173736574732f696d616765732f68656c702f70756c6c5f72657175657374732f636f6d6d69742d737175617368696e672d6469616772616d2e706e67)
## Rebase and merge:
Rebase komutu ile merge ettiğimizde branchdaki commitler ana branchda gerçekleşmiş gibi sayar ve tarihçe olarak arkada iz bırakmadan sanki değişiklikler ana branchda gerçekleşmiş gibi varsayılır.
# Agile Nedir?
Agile modeli proje yönetimi, yazılım geliştirme sürecinde karşılaşılan problemleri çözmek üzere, tekrarlanan yazılım geliştirme modeli taban alınarak geliştirilmiş ,sık aralıklarla parça parça yazılım teslimatını ve değişikliği teşvik eden bir yazılım geliştirme modeli.
2001 Şubat Ayında, 17 bağımsız yazılım lideri, farklı bilgi ve yaklaşımlardan yararlanarak daha iyi nasıl yazılım geliştirileceğini bulmak için bir araya geldiler. 2 günlük beyin fırtınası sonrası Agile Manifestosunu yayınladılar. Agile manifesto, 4 temel değer üzerine odaklanmaktadır:
## Agile Manifesto — 4 Temel Değer:

 1. İş süreçleri ve araçlardan ziyade **bireyler ve bireyler arasındaki etkileşim** değerlidir.
 2. Kapsamlı bir dokümantasyon sürecinden ziyade, **çalışan bir yazılım** ortaya koymak daha önemlidir.
 3. **Müşteri ile işbirliği yapmak**, sözleşme görüşmelerinden daha önemlidir.
 4. **Değişime cevap vermek**, mevcut planı izlemekten daha önemlidir.

###  Scrum nedir?
Kendi rehberindeki tanımlaması “İnsanların mümkün olan en yüksek değere sahip ürünleri üretken ve yaratıcı bir şekilde geliştirirken, karmaşık ve adaptasyona açık sorunları ele alabildikleri bir çerçeve” olan scrum, agile proje yönetme metodolojilerinden biridir.
Yazılım süreçlerinin detaylı ve ihtiyaca göre ortaya çıkan gereksinimlere göre esnek olabilen bir çözüm yönetimidir.
Bu şekilde, aylar boyunca lineer bir geliştirme süreci sonunda ürün çıkarmak yerine, hızla değişen ihtiyaçlara cevap verebilmek adına, haftalık çalışma planlamaları “**sprint**” adı verilen çalışma süreleri içinde gerçekleştirilir.Her sprint’te yapılması gereken işler, kişiler tarafından sahiplenilir ve sprint sonunda ürün olarak çıkar. Sprint şu parçalardan oluşuyor:

 - **Preparation:** İş sahipleri tarafından üretime hazırlanan doküman, araştırma ek tasarım gerektiren işler. Sprint boyunca aday olmaya hazırlanan işler.
 -   **Candidates:** Hazırlığı tamamlandığı düşünülen işler. Sprint meeting’de herkes bu listeden öncelik sıralamasına göre current’a kart alır. Sprint meeting’den önce hepimiz mutlaka göz gezdiririz. Alttaki sorular önceliğinde fikirler geliştirmek sprint toplantımızı hem daha verimli hem daha kısa ve öz hale getirir
 -   **Current Sprint:** Bütün ekibin, içinde bulunulan sprint için üreteceğini taahhüt ettiği işleri içeren liste.
 -   **Review not accepted:** Müşteriden veya PB ekibinden geri dönmüş olan kartlar.
 -   **In progress:** Hepimizin o sırada hangi işlerle uğraştığımızı görebilmek için yapmaya başladığımız iş bu listeye alınır.
 -   **Waiting review:**  Teste gönderilmiş. PB ekibindeki müşteri temsilcilerinin veya iş sahiplerinin testini bekleyenler.
 -   **Client test:**  Gerçekten müşterilerin veya test’te deneme yapılamayan konular için iş sahiplerinin testini bekliyor.
 -   **Review accepted:**  Test edilmiş, kabul edilmiş. Production’a alınabilir durumda olanlar.
 -   **Done:** Biten, kullanımda — yayında olan tüm işlerimiz.
### Kanban Nedir?
Kanban üretim ve malzeme akışını kontrol etmek için kullanılan; üretim proseslerine neyi, ne zaman, ne kadar üreteceklerini ve nereye göndereceklerini söyleyen bir üretim yönetimi aracıdır. Kanban görsel yönetimiyle daha iyi bir iletişimi hedefler. Her türlü israftan kaçınarak daha verimli çalışmanın yollarını arar. 5 prensibi bulunmaktadır.
 -  İşi görselleştirme  
 -  Geliştirilmekte olan işi limitleme
 -  Akışa odaklanma
 -  Süreci belirgin hale getirme
 -  Sürekli iyileştirme
### scrum ve kanban arasındaki benzerlikler:
 
 - ikisinin özünde çeviklik ve yalınlık bulunur.
 - işler emir komuta ile değil iş çekme prensibine dayalı tamamlanır.
 - İkiside aynı anda geliştirilen işleri sınırlamayı önerir.
 - İkiside sürecin iyileştirilmesi için şeffaflığı kullanır.
 -   İkiside deneyciliğe dayanır.
 -   İkiside olabildiğince erken ve sık yazılım teslimatı yapmaya çalışır.
 -   İkisinde de geliştirme takımları kendi kendini yönetir.
 -   İkisinde de büyük işlerin küçük parçalara ayrılması tavsiye edilir.
 - İkisinde de özellikle bir pratiğin- TDD, Sürekli Teslim, Refactoring, Acceptance Testing, Small Releases, Simple Design, Coding Standards, Shared Metaphor, Collective Code Ownership- kullanılması belirtilmemiştir. İçinde bulunulan ortama göre bu pratiklerin benimsenmesi geliştirme takımına bırakılmıştır.
[KAYNAK3](http://www.yilmazcihan.com/scrum-ve-kanban-arasindaki-benzerlikler-ve-farkliliklar/)
[KAYNAK4](https://www.entranet.com/tr/blog/yazilim-10055/kanban-vs-scrum)
#  Github Flow'un alternatifleri nelerdir? Artılarını ve eksileri:
**Github Flow**  hafif bir workflow'dur. Github tarafından 2011 yılında oluşturulmuştur.
Avantajları:
-   Sürekli entegrasyon avantajı
-   Git Flow'a alternatif
-   Tek bir versiyonu yönetmek için ideal
Dezavantajları:
-   Proje çabucak kompleks hale gelebilir
-   Çok sayıda versiyon yönetimi için önerilmez
**Git Flow**  en popüler ve en bilinen workflow'dur. Vincent Driessen tarafından 2010 yılında oluşturulmuştur. 2 ana branch üzerine kurulmuştur.(master ve develop)
Avantajları:
-   Projenin yaşam döngüsünde branchlerin daha temiz bir durumda olmasını sağlar.
-   Branch isimlendirmeleri proje yönetimini kolaylaştırır.
-   Git eklentileri desteği vardır.
-   Çok sayıda versiyon yönetimi yapılabilir.
Dezavantajları
-   Git geçmişi çok düzgün okunamaz.
-   2 branche bölünmeden dolayı sürekli üretimi ve entegrasyonu daha zorlu hale gelir
-   Tek versiyon için önerilmez.
**GitLab Flow**  GitLab tarafından 2014 yılında geliştirilmiştir. Github Flow'dan farklı olarak farklı branchleri vardır.
Avantajları:
-   Git geçmişi daha okunaklı ve temizdir.
-   Tek versiyon için avantajlıdır.
Dezavantajları:
-   Github Flow'dan daha kompleksdir.
-   Çok fazla versiyonlamada Git Flow kadar karmaşık bir yapıya bürünebilir.
**One Flow**  2015 yılında Git Flow'a alternatif olarak Adam Ruka tarafından üretilmiştir. Git Flow ile arasındaki fark One Flow'da develop branch'inin olmamasıdır.
Avantajları:
-   Takımın kararlarına göre değişkenlik gösterebilir.
-   Tek versiyon için uygundur.
-   Git geçmişi daha temizdir.
Dezavantajları:
-   Sürekli teslim projeler için uygun değildir.
-   Feature branch'i sürekli entegrasyonu daha zor hale getirir.
-   Çok fazla versiyonlama kısmında iyi değildir.

[KAYNAK5](https://medium.com/@patrickporto/4-branching-workflows-for-git-30d0aaee7bf)

# Abstract class ile Interface Arasındaki Fark Nedir?
 - interface ve abstract class’lar new anahtar sözcüğü ile oluşturulamazlar.
-   Bir sınıf birden fazla interface’i kalıtım olarak alabilir ama bir sınıfa bir tane abstract class kalıtım alınabilir.
-   Interface içerisinde boş metodlar tanımlanabilir ama abstract class’larda hem boş metodlar tanımlanabilir hemde içi dolu metodlar tanımlabilir.
-   Abstract sınıflar içerisinde metod gövdeleri tanımlanıp özellik değerleri ayarlandığı için genellikle sonradan üzerine ek geliştirilmek yapmak için kullanılıır ama interface de ise body ve değer set edilemediği için tamamen interface üzerinden tüm üyeleri implemente edilerek sıfırdan geliştirmeler yapılması gereken durumlarda kullanılır.
-   Abstract class’lar içerisinde sadece abstract olarak işaretlenmiş metod ve özellikler implement edilmek zorundadır fakat interface içerisindeki tüm özellik ve metodlar implement edilmek zorundadır.
-   Bir class bir tane abstract class’ı kalıtım olarak alabilir ama bir class istenilen sayıda interface’i kalıtım olarak alabilir.
-   Interface içerisinde özellik ve metodlarda erişim belirleyiciler kullanılmaz herşey public olarak kabul edilir fakat abstract sınıflarda kullanılabilir.
-   Abstract sınıflara diğer sınıf ve interface’ler kalıtım olarak geçilebilir fakat interface’e yine farklı interface’ler haricinde herhangi bir yapı kalıtım olarak geçilemez.

#  Tasarım Kalıpları Nedir?
Gang of Four topluluğu tarafından yayınlanan tasarım desenleri ,Nesne Yönelimli Programlama da karşılaşılmış tasarım sorunlarına üretilmiş optimum çözümler olarak tanımlanabilir. Tasarım desenleri bizlere daha yönetilebilir ve okunabilir kod yazmak konusunda avantajlar sağlar. Bunun yanında performans ve geliştirilebilirlik konusunda da katkıları vardır.Tasarım kalıpları, yazılım tasarımında sürekli karşılaşılan genel sorunlara esnek, yeniden kullanılabilir, başarılı çözümler getiren hazır kalıplardır. Tasarım desenleri genel olarak 3 başlık altında toplanır. Bunlar;
## Creational Patterns-Kurucu Desenler:
Nesnelerin oluşturulması ile ilgili patternlerdir.

 -  _Abstract Factory: İlişkili sınıfların oluşturulmasında kullanılır._
 -   _Factory Method: Birden fazla türetilmiş sınıfın tek bir örneğinin oluşturulmasında kullanılır._
 -   _Builder: Nesne üretilirken belirli özellikler vermemizi sağlayan desendir._
 -   _Prototype: Nesnenin bir prototipten kopyalanarak üretilmesinde kullanılır._
 -   _Singleton: En çok bilinen tasarım desenlerinden biridir. Programın yaşam döngüsü içerisinde bir nesnenin sadece bir kez oluşturulmasında kullanılır._
 ## Structural Patterns– Yapısal Desenler:
 Nesnelerin birbiri ile olan ilişkisini konu alır.
 -   _Adapter: Farklı sınıfların interfacelerini eşleştirir. Farklı yapıdaki nesnelerin kullanımı içindir._
 -   _Bridge: Nesnelerin uygulama ve arayüzlerini birbirinden ayırır._
 -   _Composite: Nesnelerin ağaç yapısında basit bir şekilde hiyerarşik olarak iç içe kullanımı içindir._
 -   _Decorator: Nesnelere dinamik olarak görevler eklemek için kullanılır._
 -   _Facade: Alt sistemleri tek bir sınıftan yönetmek için kullanılır._
 -   _Flyweight: Benzer,sık kullanılan nesnelerle veri paylaşımında bellek kullanımını en aza indirmek içindir._
 -   Proxy: Başka bir nesneyi temsil eden bir nesnenin yönetimi ile ilgilidir.

 ## Behavioral Patterns– Davranışsal Desenler:
 Sınıfların bir görevi yerine getirirken nasıl davranacağı ile ilgili desenlerdir.-   _Chain of Responsibility: Bir isteğin belirli sınıflar üzerinden iletilerek ilgili sınıfa ulaştırılması için kullanılır._
-   _Command: İşlemlerin nesne halinde kapsüllenmesi için kullanılır._
-   _Interpreter: Bir program içerisine dil öğelerinin dahil edilmesi için kullanılır._
-   _Iterator: Bir koleksiyonun öğelerine sıralı erişim için kullanılır._
-   _Mediator: Nesneler arasında ki iletişimi basitleştirmek için kullanılır._
-   _Memento: Nesnenin bazı yada tüm özelliklerini saklayarak daha sonra tekrar bu özellikleri geri yüklemek için kullanılır._
-   _Observer: Bir nesnede yapılan değişiklikleri ona bağımlı diğer nesnelere iletmek için kullanılır._
-   _State: Bir nesnenin durumuna göre davranışını değiştirmek için kullanılır._
-   _Strategy: Bir sınıf içerisinde algoritmaları tutarak, değiştirilebilir hale getirmek için kullanılır._
-   _Template Method: Bir algoritmanın iskeletinin tanımlanıp ,adımlarını alt sınıflarda tanımlayarak geçersiz kılınabilir halde kullanmak içindir._
-   _Visitor: Sınıfları değiştirmeden yeni işlemler eklemek için kullanılır._

[KAYNAK6](https://deryacakmak.medium.com/tasar%C4%B1m-kal%C4%B1plar%C4%B1-nelerdir-cd216ba47921)
 [KAYNAK7](http://enesaysan.com/software/c-tasarim-desenleri-design-patterns/)


