# II.-Hafta-Odevleri.md
#### 1- Yeni bir Gitthub repository oluştururken, repomuza ekleyebileceğimiz lisanslar nelerdir, bu lisanslar arasındaki farklar nelerdir?

 -  Açık kaynak lisansları özel izin istemeksizin bir projeye katkıda bulunmayı kolaylaştıran yetkilerdir. Yazılan yazılımın kolayca paylaşılmasını ve ortadaki                bürokratik engellerin kalkmasını sağlar. Ayrıca paylaşılan yazılımın yazarını koruyarak yazarın yaptığı katkıların unutulmamasını sağlar.
       - ##### GNU General Public License
            - Kopyalanabilir.
            - Dağıtılabilir.
            - İstediğiniz değişiklikler yapılabilir.
            - Yazılımın her yeni versiyonu bu lisansı kullanmak zorundadır.
            - BSD Licence Genel itibariyle GNU lisansına benziyor ama yeni bir lisans ile ürünü tekrar dağıtabilirsiniz.
      - ##### MIT License
           - Yazılımı dağıtabilirsiniz.
           - Yazılımı satabilirsiniz ve kaynak kodunu sağlamak zorunda değilsiniz.
           - Kaynak kodunu alan herkes değiştirebilir, yeni versiyonlarını yayınlayabilir.
           - Ticari olarak kullanabilirsiniz.
      - ##### Apache License
           - Tüm kopyaları, değiştirilmiş veya değiştirilmemiş, lisansın bir kopyası eşliğinde dağıtılabilir yada kullanılabilir.
           - Bütün değişiklikler, değiştirilmiş olarak işaretlenmelidir.
           - Ticari olarak kullanabilirsiniz.
      - ####  Creative Commons
           - Yazılımın yazarı her zaman eklenmelidir. Bunun haricinde kopyalamak, yayınlamak serbesttir.
           - Yazılım ticari amaçlarla kullanılamaz.
           - Yazılımı değiştiremezsiniz, sadece orjinalini kullanabilirsini
    
 | Lisanslar  | Yapabilecekleriniz        | Yapamayacaklarınız      | Zorunda Olduklarınız             |
 :----------  |------------------         |--------------------     |----------------------            |
 |GNU         |-  Ticari olarak           |-  Lisanslayamazsınız    |- Orjinalini bulundurmak          |
 |            | kullanabilirsiniz.        |                         | zorundasınız.                    |
 |            |-  Değiştirebilirsiniz.    |                         |                                  |
 |            |-  Dağıtabilirsiniz.       |                         |                                  |
 |            |-  Yazarı Sorumlu          |                         |                                  |
 |            | tutamazsınız.             |                         |                                  |
 |MIT         |-  Ticari olarak           |-  Yazarı sorumlu        |-  Telif bulundurmalısınız.       |
 |            | kullanabilirsiniz.        | tutamazsınız.           |- Lisansı bulundurmalısınız.      |
 |            |- Değiştirebilirsiniz.     |                         |                                  |
 |            |- Dağıtabilirsiniz.        |                         |                                  |
 |            |- Lisansyabilirsiniz.      |                         |                                  |
 |            |- Husis kullanabilirsiniz. |                         |                                  |
 |APACHE      |- Ticari olarak            |-  Yazarı sorumlu        |                                  |
 |            | kullanabilirsiniz         | tutamazsınız.           |-  Telif bulundurmalısınız.       |
 |            |- Değiştirebilirsiniz.     |-  Yazarların isimlerini |-  Lisansı bulundurmalısınız.     |
 |            |- Dağıtabilirsiniz.        | kullanamazsınız         |-  Değişiklikleri belirmelisiniz.
 |            |- Lisansyabilirsiniz.      |                         |-  Değişiklikleri bildirmelisiniz.|
 |            |- Hususi kullanabilirsiniz.|                         |                                  |
 |CREATIVE    |- Ticari olarak            |-  Yazarı sorumlu        |                                  |
 |COMMONS     | kullanabilirsiniz.        | tutamazsınız.           |                                  |
 |            |- Değiştirebilirsiniz.     |- Yazarların isimlerini  |                                  |  
 |            |- Dağıtabilirsiniz.        | kullanamazsınız.        |                                  |
 
- Daha detaylı bilgi için;
  - [Open Source Initiative](https://opensource.org/licenses/alphabetical)
  - [Understanding Open Source Licencing](https://openacs.org/about/licensing/open-source-licensing)
  
#### 2- Merge-Squash-Rebase arasındaki farklar nelerdir?

- Merge   : Herhangi bir branch'de yaptığımız değişiklikleri master branch'imiz ile birleştirme ve ya master branch'e engetre etme işlemidir.

- Squash  : Geçmişte atılan commitleri yeniden düzenlemek,isimlendirmek ve ya birleştirmek için kullanılır.Squash da istenilen
commit aralığını geri gidip yeniden düzenleme yaptığımız için "force push" kullanımı zorunludur.

- Rebase  : Git'de merge ve rease komutları benzer işlevleri yerine getirmek için kullanılıyor.Her iki komut da bir daldaki değişiklikleri başka bir dala
birleştirmek için kullanılır. Rebase komutu kullandığımızda ise A dalındaki her bir commit B dalına sanki commit işlemi B dalından yapılmış gibi yeniden yazılır.

#### 3- Agile-Scrum-Kanban kavramları nelerdir ?

- Agile     :  Hızlı geri bildirim sağlanarak değişime dayalı sürekli tasarım geliştirilmesi,test etme ilkeleri
kullanılarak küçük ekipler tarafından yüksek kaliteli uyarlanabilir yazılım geliştirilmesi.

- Scrum     :  Scrumın temelinde deneysel süreç kontrol teorisi (veya deneycilik) yer alır. Deneycilik, bilginin deneyimden ve bilinen şeylere dayanarak alınan kararlardan meydana geldiğini ileri sürer. Scrum, öngörülebilirliği en iyi seviyeye çıkarmak ve riski kontrol etmek için iterasyonlu ve artımlı (incremental) bir yaklaşım kullanır.Scrum, ilk bakışta çok basit kuralları olan bir yönetimsel modeldir. Gereksinimleri açıkça belirli olmayan, değişime açık, karmaşık yazılım projelerinin yönetimi için uygulanmaktadır. Scrum, detaylı bir şekilde projede izlenmesi gereken adımları belirtmemekte, onun yerine basit ama önemli birkaç olmazsa olmaz kuralıyla esnek bir yönetim sunmaktadır.

- Kanban    : Temelde 4 prensip kullanılır.
  - Şimdi ne biliyorsan onunla başla.
  - Artırımsal ve evrimsel değişimi takip etmeyi kabul et.
  - Mevcut sürece,rollere,sorumluluklara ve ünvana saygı göster.
  - Tüm seviyelerde liderliği teşvik et.

- Bu prensiplerin ışığında Kanban'ın 5 ana özelliği sayılırsa:
  - İş akışını görselleştir.
  - Aynı anda yapılan işleri sınırlanır.
  - Akışı yönet ve ölç.
  - Süreç ilkelerini belirgin kıl.
  - İş birliği yaparak iyileştir.

#### 4- Github Flow'un alternatifleri nelerdir? Artılarını ve eksilerini karşılaştırınız.
  - GitKraken
  - SourceTree
  - Gmaster
  - Git Temporal
  
#### 5- Gang of Four(GOF) araştırınız.

  Gang of Four Sistematiği
  
  - Creational Patterns(Kurucu Desenler):Nesnelerin oluşturulması ile ilgilidir.
    - Abstract Factory: İlişkili sınıfların oluşturulmasında kullanılır.
    - Factory Method:  Birden fazla türetilmiş sınıfın tek bir örneğinin oluşturulmasında kullanılır.
    - Builder: Nesne üretilirken belirli özellikler vermemizi sağlayan desendir.
    - Prototype: Nesnenin bir prototipten kopyalanarak üretilmesinde kullanılır.
    - Singleton: En çok bilinen tasarım desenlerinden biridir.
    Programın yaşam döngüsü içerisinde bir nesnenin sadece bir kez oluşturulmasında kullanılır.
    
  - Structural Patterns(Yapısal Desenler): Nesnelerin birbiri ile olan ilişkisini konu alır.
    - Adapter: Farklı sınıfların interfacelerini eşleştirir. Farklı yapıdaki nesnelerin kullanımı içindir.
    - Bridge:  Nesnelerin uygulama ve arayüzlerini birbirinden ayırır.
    - Composite:  Nesnelerin ağaç yapısında basit bir şekilde hiyerarşik olarak iç içe kullanımı içindir.
    - Decorator: Nesnelere dinamik olarak görevler eklemek için kullanılır.
    - Facade: Alt sistemleri tek bir sınıftan yönetmek için kullanılır.
    - Flyweight: Benzer,sık kullanılan nesnelerle veri paylaşımında bellek kullanımını en aza indirmek içindir.
    - Proxy: Başka bir nesneyi temsil eden bir nesnenin yönetimi ile ilgilidir.
  
  - Behavioral Patterns(Davranışsal Desenler): Sınıfların bir görevi yerine getirirken nasıl davranacağı ile ilgili desenlerdir.
    - Chain of Responsibility: Bir isteğin belirli sınıflar üzerinden iletilerek ilgili sınıfa ulaştırılması için kullanılır.
    - Command: İşlemlerin nesne halinde kapsüllenmesi için kullanılır.
    - Interpreter: Bir program içerisine dil öğelerinin dahil edilmesi için kullanılır.
    - Iterator:  Bir koleksiyonun öğelerine sıralı erişim için kullanılır.
    - Mediator: Nesneler arasında ki iletişimi basitleştirmek için kullanılır.
    - Memento: Nesnenin bazı yada tüm özelliklerini saklayarak daha sonra tekrar bu özellikleri geri yüklemek için kullanılır.
    - Observer: Bir nesnede yapılan değişiklikleri ona bağımlı diğer nesnelere iletmek için kullanılır.
    - State: Bir nesnenin durumuna göre davranışını değiştirmek için kullanılır.
    - Strategy: Bir sınıf içerisinde algoritmaları tutarak, değiştirilebilir hale getirmek için kullanılır.
    - Template Method: Bir algoritmanın iskeletinin tanımlanıp ,adımlarını alt sınıflarda tanımlayarak geçersiz kılınabilir halde kullanmak içindir.
    - Visitor: Sınıfları değiştirmeden yeni işlemler eklemek için kullanılır.

[Kaynak](http://enesaysan.com/software/c-tasarim-desenleri-design-patterns/)
Daha Detaylı bilgi için [tıklayabilirsiniz.](https://www.dofactory.com/net/design-patterns)

#### 5-Interface ve Abstract sınıflar arasındaki farklar nelerdir?

   
 | Abstract Sınıflar                                                | Interface'ler                                                          |
 |----------                                                        |------------------                                                      |
 |- Kod içerisinde “new” anahtar sözcüğü ile oluşturulamazlar.      | - Kod içerisinde “new” anahtar sözcüğü ile oluşturulamazlar.           |
 |- Bir sınıf sadece bir abstract sınıfı inherit alabilir.          | - Bir sınıf birden fazla interface implemente edebilir.                |
 |- Inherit alıcak sınıflar arasında genelde “is-a” ilişkisi vardır.| - Implemente edicek sınıflar arasında genelde “can-do” ilişkisi vardır.|
 |- Abstract sınıfda method ve değişkenler tanımlanabilir.          | - Interface içerisine sadece boş method’lar tanımlanabilir.            | 
 
  Detaylı bilgi için [tıklayınız.](https://eminecakmakci.wordpress.com/2019/02/17/interface-ve-abstract-class-arasindaki-farklar-nelerdir/)
 
