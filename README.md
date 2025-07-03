## ft\_transcendence Projesi - Tam Çeviri (TÜRKÇE)

# I Giriş

**Sürpriz.**

## İçindekiler

- I Giriş

- II Amaçlar

- III Zorunlu Kısım
  - III.1 Genel Bakış
  - III.2 Asgari Teknik Gereklilik
  - III.3 Oyun
  - III.4 Güvenlik Endişeleri

- IV Modüller
  - IV.1 Genel Bakış
  - IV.2 Web
  - IV.3 Kullanıcı Yönetimi
  - IV.4 Oynanış ve Deneyim
  - IV.5 AI-Algoritma
  - IV.6 Siber Güvenlik
  - IV.7 DevOps
  - IV.8 Grafik
  - IV.9 Erişilebilirlik
  - IV.10 Sunucu Taraflı Pong

- V Bonus Kısım

- VI Teslimat ve Eş Değerlendirme

## II Amaçlar

Bu proje bir sürprizdir.

Ortak Çekirdeğinizin sonuna yaklaşırken güçlü uyum sağlama ve problem çözme becerileri geliştirdiniz. Bu proje sizi -belki de- bilinmeyen teknolojilerle yüzleştirecek. Bir kez daha uyum sağlamak, keşfetmek, denemek ve beklenen yazılımı oluşturmak zorunda kalacaksınız.

Proje, aşağıda ayrıntılı olarak açıklanan bir zorunlu kısımdan ve çeşitli konularda bir dizi modülden oluşur. Büyük bir liste arasından istediğiniz modülleri seçebilirsiniz, ancak her modül ve zorunlu unsur teknik kısıtlamalar içerir ve bunları atlayamazsınız. Yani istediğiniz konuları seçebilirsiniz ama istediğiniz teknolojileri değil. Bu bilinçli bir pedagojik tercihtir.

Bu proje, yaklaşan bir staj veya başka bir profesyonel deneyim için bir portföy olmayı amaçlamaz. Amacı, tanımadığınız bir teknolojiyi kullanarak karmaşık bir görevi yerine getirme yeteneğinizi ortaya çıkarmaktır. Kariyeriniz boyunca kaçınılmaz olarak böyle durumlarla karşılaşacaksınız ve bu durumlar karşısında kendinize güveninizi geliştirmeyi hedefliyoruz.

Özellikle bu büyük ve uzun projede, tüm metni dikkatlice okumanızı, birkaç olası stratejiyi değerlendirmenizi, tasarımınızı düşünmenizi öneriyoruz. Bazı modüller diğerlerine bağlı olabilir, bazı modüller birbiriyle çelişebilir. Ft\_transcendence birçok şüphe barındıracak ve birçok zor karar gerektirecektir! Akıllıca hareket edin :-)

Ayrıca, bu proje kesinlikle uzun bir koşudur ve yanlış bir yol büyük bir zaman kaybına yol açacaktır. Proje yönetimi ve ekip yönetimi seçimleriniz zaman çizelgenizi ve sonuçlarınızı güçlü bir şekilde etkileyecektir. Bu konularda sizi destekleyecek birçok yaklaşım ve araç vardır.

İyi şanslar ve Pong oynamanın tadını çıkarın!

# III Zorunlu Kısım

Bu proje, güçlü Pong yarışması için bir web sitesi oluşturmaktır!

## III.1 Genel Bakış

Yazılımınız hoş bir kullanıcı arayüzü ve tüm arkadaşlarınızla Pong oynamanıza olanak tanıyan gerçek zamanlı çok oyunculu yetenekler sunacaktır.

* İlk olarak, projenizin asgari bir gereklilik olarak zorunlu yönergelere uyması gerekir (bir sonraki bölümde bkz.), bu nihai notun yalnızca küçük bir kısmını temsil eder.
* Bu belgenin ikinci bölümü, zorunlu kısmı değiştirebilecek veya tamamlayabilecek ek modüller sunacaktır.

Bu belgede yeşil renkle vurgulanan kelimeler teknoloji seçimlerini temsil eder ve zamanla değişecektir. Konunun sürümüne dikkat edin.

* Bir özelliği veya modülü tamamen sağlayan bir kütüphane veya araç kullanımı yasaktır.
* Üçüncü taraf bir kütüphane veya araç kullanımıyla ilgili doğrudan talimatlara (kullanılabilir, kullanılmalı, kullanılamaz) uyulmalıdır.
* Daha büyük bir özelliğin veya modülün alt bileşeni olan basit, benzersiz bir görevi çözen küçük bir kütüphane veya aracın kullanımı serbesttir.
* Değerlendirme sırasında, ekip proje yönergelerinde açıkça onaylanmamış ve projenin kısıtlamalarıyla çelişmeyen herhangi bir kütüphane veya araç kullanımını gerekçelendirecektir.
* Değerlendirme sırasında değerlendirici, belirli bir kütüphane veya aracın kullanımının meşru (ve izin verilen) olup olmadığını veya esasen tüm bir özelliği veya modülü çözüp çözmediğini (ve bu nedenle yasak olduğunu) belirleyecektir.

## III.2 Asgari Teknik Gereklilik

Projeniz aşağıdaki kurallara uymalıdır:

Bazı kısıtlamalar belirli modül seçimleriyle değiştirilebilir.

* Siteyi backend olmadan veya backend ile geliştirebilirsiniz.

  * Backend kullanırsanız saf PHP kullanmalı, framework kullanamazsınız. Ancak Framework modülü bu gerekliliği geçersiz kılabilir.
  * Backend veya framework bir veritabanı kullanıyorsa Database modülü kısıtlamalarına uymalısınız.
* Frontend TypeScript tabanlı olmalıdır. Ancak FrontEnd modülü bu gerekliliği değiştirebilir.
* Web siteniz tek sayfalık uygulama olmalıdır. Kullanıcı tarayıcıdaki Geri ve İleri düğmelerini kullanabilmelidir.
* Web siteniz en güncel kararlı Mozilla Firefox sürümü ile uyumlu olmalıdır. Elbette diğer tarayıcılarla da uyumlu olabilir!
* Kullanıcı siteyi gezerken işlenmemiş hata veya uyarı görmemelidir.
* Sitenizi çalıştırmak için Docker kullanmalısınız. Her şey tek bir komut satırı ile çalışacak şekilde bağımsız bir container içinde başlatılmalıdır.

Root yetkisiz modda container kullanıyorsanız bazı ek kısıtlamalar olabilir:

* Çalışma zamanı /goinfre veya /sgoinfre dizininde yer almalıdır.
* Non-root UID kullanılan container içinde host ile bind-mount volume kullanamazsınız.

Mevcut gerekliliklere (yukarıda yeşil renkte vurgulanan) ve cluster yapılandırmalarına bağlı olarak farklı stratejiler benimsemeniz gerekebilir: sanal makine içinde container çözümü, değişikliklerden sonra container’ı yeniden inşa etme, root UID kullanan özel bir imaj hazırlama gibi.

## III.3 Oyun

Bu web sitesinin ana amacı, diğer oyunculara karşı Pong oynamaktır.

* Kullanıcılar site üzerinden başka bir oyuncuya karşı canlı Pong oyununa katılabilmelidir. Her iki oyuncu da aynı klavyeyi kullanacaktır. Remote players modülü bu işlevi uzak oyuncularla geliştirebilir.

* Bir oyuncu başka bir oyuncuya karşı oynayabilmeli ve ayrıca bir turnuva sistemi bulunmalıdır. Bu turnuva, sırayla birbirleriyle oynayacak birden fazla oyuncudan oluşacaktır. Nasıl uygulayacağınız size bağlıdır, ancak kimin kime karşı oynadığı ve oyun sırası açıkça gösterilmelidir.

* Bir kayıt sistemi gereklidir: Bir turnuva başında her oyuncu takma adını girmelidir. Takma adlar yeni bir turnuva başladığında sıfırlanacaktır. Ancak bu gereklilik Standard User Management modülü ile değiştirilebilir. Not: Bu, kullanıcı hesabı oluşturmayı içermez. Varsayılan (zorunlu) sürümde kullanıcılar yalnızca manuel olarak takma ad girer.

* Bir eşleştirme sistemi olmalıdır: turnuva sistemi katılımcıların eşleşmesini düzenlemeli ve bir sonraki maçı duyurmalıdır.

* Tüm oyuncular aynı kurallara uymalıdır, paddle hızları da dahil. Bu gereklilik AI kullanıldığında da geçerlidir; AI normal bir oyuncu ile aynı hıza sahip olmalıdır.

* Oyun, varsayılan frontend kısıtlamalarına (yukarıda belirtilen) uymalıdır veya FrontEnd modülü veya Graphics modülü ile geçersiz kılınabilir. Görsel estetik değişebilir ancak oyun yine de orijinal Pong’un (1972) ruhunu korumalıdır.

* Bir özelliği veya modülü tamamen sağlayan bir kütüphane veya araç kullanımı yasaktır.

* Üçüncü taraf bir kütüphane veya araç kullanımıyla ilgili doğrudan talimatlara (can, must, can’t) uyulmalıdır.

* Daha büyük bir özelliğin veya modülün alt bileşeni olan basit, benzersiz bir görevi çözen küçük bir kütüphane veya aracın kullanımı serbesttir.

* Değerlendirme sırasında, ekip proje yönergelerinde açıkça onaylanmamış ve projenin kısıtlamalarıyla çelişmeyen herhangi bir kütüphane veya araç kullanımını gerekçelendirecektir.

* Değerlendirme sırasında değerlendirici, belirli bir kütüphane veya aracın kullanımının meşru (ve izin verilen) olup olmadığını veya esasen tüm bir özelliği veya modülü çözüp çözmediğini (ve bu nedenle yasak olduğunu) belirleyecektir.

* Turnuva sistemi kullanıcı kaydı ile veya kayıtsız çalışabilmelidir.

  * Standart Kullanıcı Yönetimi modülü olmadan: kullanıcılar manuel olarak takma ad girer.
  * Modül ile: takma adlar kayıtlı hesaplara bağlıdır, kalıcı istatistikler ve arkadaş listeleri sağlar.

    Modül turnuva mantığını genişletir; yerine geçmez.

## III.4 Güvenlik Endişeleri

Çalışan bir web sitesi oluşturmak için aşağıdaki güvenlik konularını ele almalısınız:

* Veritabanınızda saklanan herhangi bir şifre hashlenmiş olmalıdır.
* Web siteniz SQL enjeksiyonlarına/XSS saldırılarına karşı korunmalıdır.
* Bir backend veya başka özellikleriniz varsa, tüm yönler için HTTPS bağlantısı etkinleştirilmelidir (örneğin ws yerine wss kullanılmalıdır).
* Formlar ve kullanıcı girişi için doğrulama mekanizmaları uygulamalısınız; backend yoksa ana sayfada, backend varsa sunucu tarafında uygulanmalıdır.
* JWT Security modülünü iki faktörlü kimlik doğrulama ile uygulamayı seçseniz de seçmeseniz de sitenizin güvenliğini önceliklendirmek önemlidir. Örneğin bir API oluşturuyorsanız rotalarınızı koruyun. JWT tokenleri kullanmasanız bile site güvenli olmalıdır.
* Şifre hashleme algoritması güçlü olmalıdır.
* Güvenlik nedeniyle tüm kimlik bilgileri, API anahtarları, ortam değişkenleri vb. yerel olarak bir .env dosyasında saklanmalı ve git tarafından yok sayılmalıdır. Açıkta tutulan kimlik bilgileri projenizin başarısız olmasına sebep olur.

## IV Modüller

Artık projenin %25'ini tamamladınız, tebrikler!

Çalışan temel bir web sitesi ile sonraki adım geliştirme için modülleri seçmektir.

Projeyi %100 tamamlamak için en az 7 büyük modül gereklidir. Her modülü dikkatlice inceleyin çünkü bazıları temel sitenizde değişiklik gerektirebilir. Bu nedenle tüm konuyu dikkatlice okumanız şiddetle tavsiye edilir.

* Bir özelliği veya modülü tamamen sağlayan bir kütüphane veya araç kullanımı yasaktır.
* Üçüncü taraf bir kütüphane veya araç kullanımıyla ilgili doğrudan talimatlara (can, must, can’t) uyulmalıdır.
* Daha büyük bir özelliğin veya modülün alt bileşeni olan basit, benzersiz bir görevi çözen küçük bir kütüphane veya aracın kullanımı serbesttir.
* Değerlendirme sırasında, ekip proje yönergelerinde açıkça onaylanmamış ve projenin kısıtlamalarıyla çelişmeyen herhangi bir kütüphane veya araç kullanımını gerekçelendirecektir.
* Değerlendirme sırasında değerlendirici, belirli bir kütüphane veya aracın kullanımının meşru (ve izin verilen) olup olmadığını veya esasen tüm bir özelliği veya modülü çözüp çözmediğini (ve bu nedenle yasak olduğunu) belirleyecektir.

İki Küçük Modül bir Büyük Modül sayılır.

## IV.1 Genel Bakış

* Web

  * Büyük modül: Backend geliştirmek için bir framework kullanın.
  * Küçük modül: Frontend geliştirmek için bir framework veya araç seti kullanın.
  * Küçük modül: Backend için bir veritabanı kullanın.
  * Büyük modül: Turnuva skorunu Blockchain’de saklayın.

* Kullanıcı Yönetimi

  * Büyük modül: Standart kullanıcı yönetimi, kimlik doğrulama, turnuvalar arasında kullanıcılar.
  * Büyük modül: Uzaktan kimlik doğrulama.

* Oynanış ve kullanıcı deneyimi

  * Büyük modül: Uzak oyuncular.
  * Büyük modül: Çoklu oyuncu (2’den fazla oyuncu aynı oyunda).
  * Büyük modül: Kullanıcı geçmişi ve eşleştirme ile başka bir oyun ekleyin.
  * Küçük modül: Oyun özelleştirme seçenekleri.
  * Büyük modül: Canlı sohbet.

* AI-Algoritma

  * Büyük modül: AI rakibi ekleyin.
  * Küçük modül: Kullanıcı ve oyun istatistik panelleri.

* Siber Güvenlik

  * Büyük modül: WAF/ModSecurity ve HashiCorp Vault.
  * Küçük modül: GDPR uyumluluğu, kullanıcı anonimleştirme, yerel veri yönetimi, hesap silme.
  * Büyük modül: İki faktörlü kimlik doğrulama (2FA) ve JWT.

* DevOps

  * Büyük modül: Log yönetimi için altyapı kurulumu.
  * Küçük modül: İzleme sistemi.
  * Büyük modül: Backend’i mikro servisler olarak tasarlayın.

* Grafik

  * Büyük modül: Gelişmiş 3D teknikleri kullanın.

* Erişilebilirlik

  * Küçük modül: Tüm cihazlarda destek.
  * Küçük modül: Daha fazla tarayıcı desteği.
  * Küçük modül: Çoklu dil desteği.
  * Küçük modül: Görme engelliler için erişilebilirlik.
  * Küçük modül: Sunucu Taraflı Rendering (SSR) entegrasyonu.

* Sunucu Taraflı Pong

  * Büyük modül: Temel Pong’u sunucu taraflı Pong ile değiştirin ve bir API oluşturun.
  * Büyük modül: API entegrasyonu ile CLI üzerinden Pong oynayın.

## IV.2 Web

Bu modüller Pong oyununuzda gelişmiş web özelliklerinin entegrasyonunu sağlar.

* Büyük modül: Backend geliştirmek için bir framework kullanın.
  Bu büyük modülde backend geliştirmek için belirlenen web framework'ü Fastify ve Node.js'tir.

  Bu modülün gerekliliklerini takip etmediğiniz sürece backend'i bu modülün kısıtlamaları olmadan oluşturabilirsiniz.

* Küçük modül: Frontend geliştirmek için bir framework veya araç seti kullanın.
  Frontend geliştirme, TypeScript’e ek olarak yalnızca Tailwind CSS kullanılarak yapılmalıdır.

  Bu modülün gerekliliklerini takip etmediğiniz sürece frontend’i varsayılan yönergelere göre oluşturabilirsiniz.

* Küçük modül: Backend için bir veritabanı kullanın.
  Projedeki tüm veritabanı örnekleri için belirlenen veritabanı SQLite'tır. Bu seçim, proje bileşenleri arasında veri tutarlılığını ve uyumluluğu sağlar ve backend Framework modülü gibi diğer modüller için bir önkoşul olabilir.

* Büyük modül: Turnuva skorunu Blockchain’de saklayın.

  Bu büyük modül, Pong web sitesine turnuva skorlarını Blockchain üzerinde güvenli şekilde saklama özelliğini kazandırmayı amaçlar. Geliştirme ve test için bir test blockchain ortamı kullanılacaktır. Seçilen blockchain Avalanche, akıllı sözleşme dili Solidity'dir.

  Blockchain entegrasyonu: Ana hedef Avalanche Blockchain'i siteye entegre ederek skorların güvenli ve değiştirilemez şekilde saklanmasını sağlamaktır.

  Solidity Akıllı Sözleşmeleri: Blockchain ile etkileşim için Solidity akıllı sözleşmeleri geliştirilir. Bu sözleşmeler skorların kaydı, yönetimi ve alınması işlevini görür.

  Test Blockchain: Tüm blockchain fonksiyonları test blockchain ortamında geliştirilir ve doğrulanır.

  Uyumluluk: Blockchain işlevini entegre ederken Backend Framework modülü gibi diğer modüllerle bağlantılı olabilir. Backend'de Blockchain ile etkileşimi sağlamak için uyarlamalar gerekebilir.

  Bu modülü uygulayarak Pong web sitesine Blockchain tabanlı bir skor saklama sistemi kazandırmayı hedefliyoruz. Kullanıcılar, skorlarının bütünlüğünü garanti altına alan bu ek güvenlik ve şeffaflık katmanından faydalanacaktır. Modül, blockchain geliştirme ile ilgili riskleri en aza indirmek için bir test blockchain ortamının kullanımını vurgular.


## IV.3 Kullanıcı Yönetimi

Bu modül, Pong platformunda kullanıcı etkileşimleri ve erişim kontrolüyle ilgili ana unsurları kapsar. İki büyük bileşeni vardır: kullanıcı katılımı ve uzaktan kimlik doğrulama.

* Büyük modül: Standart kullanıcı yönetimi, kimlik doğrulama ve turnuvalar arası kullanıcılar.

  * Kullanıcılar siteye güvenli şekilde abone olabilir.
  * Kayıtlı kullanıcılar güvenli şekilde giriş yapabilir.
  * Kullanıcılar turnuvalara katılmak için benzersiz bir görüntüleme adı seçebilir.
  * Kullanıcılar bilgilerini güncelleyebilir.
  * Kullanıcılar bir avatar yükleyebilir, yüklenmezse varsayılan avatar kullanılır.
  * Kullanıcılar diğer kullanıcıları arkadaş olarak ekleyebilir ve çevrimiçi durumlarını görebilir.
  * Kullanıcı profilleri kazanılan ve kaybedilen oyunlar gibi istatistikleri gösterir.
  * Her kullanıcının 1v1 oyunları, tarihleri ve ilgili detayları içeren bir Maç Geçmişi vardır ve yalnızca oturum açan kullanıcılar erişebilir.

    Aynı kullanıcı adları/e-posta adreslerinin yönetimi size bağlıdır; mantıklı bir çözüm sunmanız gerekir.

* Büyük modül: Uzaktan kimlik doğrulama uygulama.
  Bu modülde, Google Sign-in sistemi entegre edilecektir.

  * Kimlik doğrulama sistemi entegre edilerek kullanıcıların güvenli şekilde giriş yapması sağlanır.
  * Yetkiliden gerekli kimlik bilgileri ve izinler alınır.
  * En iyi uygulamalara ve güvenlik standartlarına uygun kullanıcı dostu giriş ve yetkilendirme akışları uygulanır.
  * Web uygulaması ile kimlik sağlayıcı arasında kimlik doğrulama jetonlarının ve kullanıcı bilgilerinin güvenli şekilde aktarımı sağlanır.

    Bu büyük modül, web uygulamasına uzaktan bir kullanıcı kimlik doğrulaması sağlayarak kullanıcılara güvenli ve pratik bir erişim sunmayı amaçlar.

## IV.4 Oynanış ve Kullanıcı Deneyimi

Bu modüller projenin genel oynanış deneyimini geliştirmek için tasarlanmıştır.

* Büyük modül: Uzak oyuncular

  İki oyuncunun uzaktan oynayabilmesi mümkün olmalıdır. Her oyuncu ayrı bir bilgisayarda, aynı web sitesine erişerek aynı Pong oyununu oynar.

  Ağ sorunları, beklenmedik bağlantı kopmaları veya gecikmeler gibi durumları dikkate alın. En iyi kullanıcı deneyimini sunmalısınız.

* Büyük modül: Çoklu oyuncu

  İki oyuncudan fazla oyuncu olması mümkün olmalıdır. Her oyuncu canlı kontrol sağlar (bu yüzden "uzak oyuncular" modülü şiddetle önerilir). Oyun 3, 4, 5, 6 veya daha fazla oyuncu ile oynanabilir. Örneğin: 4 oyuncu kare bir tahtada her kenarı kontrol ederek oynayabilir.

* Büyük modül: Kullanıcı geçmişi ve eşleştirme ile başka bir oyun ekleyin

  Bu büyük modülün amacı, Pong’dan farklı yeni bir oyun eklemek ve kullanıcı geçmişi izleme ile eşleştirme özelliklerini entegre etmektir.

  ◦ Platformun tekliflerini çeşitlendirmek ve kullanıcıları eğlendirmek için yeni, ilgi çekici bir oyun geliştirin.

  ◦ Bireysel kullanıcıların oyun istatistiklerini kaydedip görüntülemek için kullanıcı geçmişi izleme uygulayın.&#x20;

  ◦ Kullanıcıların rakip bulmasını ve adil, dengeli maçlara katılmasını sağlamak için bir eşleştirme sistemi oluşturun.&#x20;

  ◦ Kullanıcı oyun geçmişi ve eşleştirme verilerinin güvenli şekilde saklanmasını ve güncel tutulmasını sağlayın.

  &#x20;◦ Yeni oyunun performansını ve yanıt verme hızını optimize ederek keyifli bir kullanıcı deneyimi sağlayın. Hataları düzeltmek, yeni özellikler eklemek ve oynanışı geliştirmek için düzenli olarak güncelleyin.&#x20;

  Bu büyük modül, platformunuzu yeni bir oyunla genişletmeyi, kullanıcı katılımını oyun geçmişiyle artırmayı ve keyifli bir oyun deneyimi için eşleştirme sağlamayı amaçlar.

* Küçük modül: Oyun özelleştirme seçenekleri&#x20;

  Bu küçük modülde, platformdaki tüm mevcut oyunlar için özelleştirme seçenekleri sunmak amaçlanır.

  &#x20;◦ Oyun deneyimini geliştirmek için güçlendirmeler, saldırılar veya farklı haritalar gibi özelleştirme özellikleri sunun.

  ◦ Daha basit bir deneyim tercih eden kullanıcılar için temel özelliklere sahip varsayılan bir sürüm seçmelerine izin verin.&#x20;

  ◦ Özelleştirme seçeneklerinin tüm oyunlarda mevcut ve uygulanabilir olmasını sağlayın.&#x20;

  ◦ Oyun parametrelerini ayarlamak için kullanıcı dostu ayar menüleri veya arayüzler uygulayın.&#x20;

  ◦ Tüm oyunlarda özelleştirme özelliklerinde tutarlılığı koruyarak birleşik bir kullanıcı deneyimi sunun.&#x20;

  Bu modül, kullanıcıların tüm mevcut oyunlarda çeşitli özelleştirme seçenekleriyle oyun deneyimlerini kendi tercihlerine göre uyarlamalarına imkan tanırken, daha basit bir oynanış isteyenler için varsayılan sürümü de sunar.

* Büyük modül: Canlı Sohbet

  Bu modülde, kullanıcılar için bir sohbet özelliği oluşturmanız gerekir:

  ◦ Kullanıcı diğer kullanıcılara doğrudan mesaj gönderebilmelidir.
  ◦ Kullanıcı diğer kullanıcıları engelleyebilmeli, böylece engellenen hesaplardan gelen mesajlar artık görünmemelidir.

  ◦ Kullanıcı sohbet arayüzü üzerinden diğer kullanıcıları Pong oyununa davet edebilmelidir.

  ◦ Turnuva sistemi bir sonraki oyunu kullanıcılara bildirebilmelidir.

  ◦ Kullanıcı sohbet arayüzünden diğer oyuncuların profillerine erişebilmelidir.


## IV.5 AI-Algo

Bu modüller projeye veri odaklı unsurlar kazandırır. Büyük modül, oynanışı geliştirmek için bir AI rakibi sunarken, küçük modül kullanıcı ve oyun istatistik panellerine odaklanır ve kullanıcılara oyun deneyimleri hakkında sade ama anlamlı bir bakış sunar.

* Büyük modül: Bir AI rakibi ekleyin

  Bu büyük modülde amaç oyuna bir AI oyuncu entegre etmektir. Bu görev için A\* algoritmasının kullanılması yasaktır.

  ◦ Kullanıcılar için zorlayıcı ve ilgi çekici bir oynanış deneyimi sağlayacak bir AI rakibi geliştirin.

  ◦ AI insan davranışını taklit etmelidir, yani AI uygulamanızda klavye girişini simüle etmelisiniz. Kısıtlama şudur: AI oyunu yalnızca saniyede bir yenileyerek görebilir, bu nedenle çarpmaları ve diğer hareketleri önceden tahmin etmelidir.

  Eğer Oyun Özelleştirme Seçenekleri modülünü uyguladıysanız, AI güçlendirmeleri kullanmalıdır.

  ◦ AI mantığı ve karar alma süreçleri, AI oyuncusunun akıllıca ve stratejik hamleler yapmasına olanak tanımalıdır.

  ◦ A\* dışında alternatif algoritma ve teknikler araştırarak etkili bir AI oyuncu oluşturun.

  ◦ AI farklı oyun senaryolarına ve kullanıcı etkileşimlerine uyum sağlamalıdır.

  AI'nın nasıl çalıştığını değerlendirme sırasında detaylı şekilde açıklamanız gerekecektir. "Hiçbir şey yapmayan" bir AI kesinlikle yasaktır; ara sıra kazanma yeteneğine sahip olmalıdır.

  Bu büyük modül, A\* algoritmasına dayanmadan oyuna heyecan ve rekabet katan bir AI rakibi ekleyerek oyunu geliştirmeyi amaçlar.

* Küçük modül: Kullanıcı ve Oyun İstatistik Panelleri

  Bu küçük modülde amaç, bireysel kullanıcılar ve oyun oturumları için istatistik panelleri sunmaktır.

  ◦ Kullanıcılara oyun istatistiklerine dair içgörü sağlayan kullanıcı dostu paneller oluşturun.

  ◦ Her oyun oturumu için ayrı bir panel geliştirin, detaylı istatistikler, sonuçlar ve her maç için geçmiş verileri gösterin.

  ◦ Panellerin veri izleme ve analiz için sezgisel ve bilgilendirici bir kullanıcı arayüzü sunmasını sağlayın.

  ◦ İstatistikleri açık ve görsel olarak etkileyici biçimde sunmak için grafikler ve tablolar gibi veri görselleştirme tekniklerini kullanın.

  ◦ Kullanıcıların kendi oyun geçmişi ve performans metriklerine rahatça erişebilmesini ve inceleyebilmesini sağlayın.

  ◦ Yararlı gördüğünüz diğer metrikleri de eklemekten çekinmeyin.

  Bu küçük modül, kullanıcıların kullanıcı dostu paneller aracılığıyla oyun istatistiklerini ve maç detaylarını izleme yeteneği kazanmasını sağlar ve oyun deneyimlerinin kapsamlı bir görünümünü sunar.


## IV.6 Siber Güvenlik

Bu siber güvenlik modülleri, projenin güvenlik yapısını güçlendirmek için tasarlanmıştır. Büyük modül, Web Uygulama Güvenlik Duvarı (WAF) ve ModSecurity yapılandırmaları ile HashiCorp Vault entegrasyonu sayesinde sağlam bir koruma sunar. Küçük modüller ise GDPR uyumluluğu, kullanıcı verisi anonimleştirme, hesap silme, İki Faktörlü Kimlik Doğrulama (2FA) ve JSON Web Token (JWT) özellikleri ekleyerek veri koruması, gizlilik ve kimlik doğrulama güvenliğine katkıda bulunur.

* Büyük modül: WAF/ModSecurity ile Güçlendirilmiş Yapılandırma ve HashiCorp Vault ile Gizli Bilgi Yönetimi

  Bu büyük modülün amacı, projenin güvenlik altyapısını birkaç önemli bileşen uygulayarak geliştirmektir.

  ◦ Web tabanlı saldırılara karşı koruma sağlamak için sıkı ve güvenli bir yapılandırmaya sahip bir Web Uygulama Güvenlik Duvarı (WAF) ve ModSecurity yapılandırın ve dağıtın.

  ◦ API anahtarları, kimlik bilgileri ve ortam değişkenleri gibi hassas bilgileri güvenli şekilde yönetmek ve saklamak için HashiCorp Vault'u entegre edin, bu sırların uygun şekilde şifrelenmiş ve izole edilmiş olmasını sağlayın.&#x20;

  Bu büyük modül, web uygulaması koruması için WAF/ModSecurity ve gizli bilgi yönetimi için HashiCorp Vault kullanarak güçlü bir güvenlik altyapısı sağlamayı amaçlar.

* Küçük modül: GDPR uyumluluğu seçenekleri, kullanıcı anonimleştirme, yerel veri yönetimi ve hesap silme

  Bu küçük modülün amacı, kullanıcıların veri gizliliği haklarını kullanabilmesini sağlayacak GDPR uyumluluğu seçenekleri sunmaktır.

  ◦ Kullanıcıların kişisel verilerinin anonimleştirilmesini talep etmesini sağlayan GDPR uyumlu özellikler uygulayın, böylece kimlik ve hassas bilgiler korunur.
  ◦ Kullanıcıların sistemde saklanan kişisel bilgilerini görüntüleme, düzenleme veya silme imkanı sunan araçlar sağlayın.

  ◦ Tüm ilgili verilerle birlikte hesapların kalıcı olarak silinmesini isteyen kullanıcılar için basit bir süreç sunarak veri koruma düzenlemelerine uygunluğu sağlayın.

  ◦ Kullanıcılarla veri gizliliği hakları hakkında açık ve şeffaf iletişim kurun, bu hakları kullanmak için erişilebilir seçenekler sunun.

  Bu küçük modül, kullanıcı gizliliğini ve veri korumasını artırarak kullanıcıların kişisel bilgilerini yönetmesine ve gizlilik haklarını kullanmasına olanak tanır.
  GDPR (Genel Veri Koruma Yönetmeliği) hakkında bilginiz yoksa, temel ilkelerini ve kullanıcı verisi yönetimi ile gizliliği üzerindeki etkilerini anlamak önemlidir. GDPR, Avrupa Birliği (AB) ve Avrupa Ekonomik Alanı (AEA) içindeki kişisel veri ve gizlilik haklarını korumayı amaçlayan bir düzenlemedir. Kişisel verilerin nasıl işleneceği ve yönetileceği konusunda katı kurallar içerir. GDPR ve gereklilikleri hakkında daha fazla bilgi için Avrupa Komisyonu'nun veri koruma resmi web sitesini ziyaret etmeniz şiddetle önerilir.
  [https://commission.europa.eu/law/law-topic/data-protection/data-protection-eu\_en](https://commission.europa.eu/law/law-topic/data-protection/data-protection-eu_en)

* Büyük modül: İki Faktörlü Kimlik Doğrulama (2FA) ve JWT Bu büyük modülün amacı, İki Faktörlü Kimlik Doğrulama (2FA) ve JSON Web Token (JWT) kullanarak güvenlik ve kullanıcı kimlik doğrulamasını geliştirmektir.

  ◦ Kullanıcı hesapları için ek bir güvenlik katmanı olarak 2FA uygulayın, kullanıcılardan şifrelerine ek olarak tek kullanımlık bir kod gibi ikincil bir doğrulama yöntemi talep edin.

  &#x20;◦ Kimlik doğrulama ve yetkilendirme için JSON Web Token (JWT) kullanarak kullanıcı oturumlarını ve kaynaklara erişimi güvenli şekilde yönetin.

  &#x20;◦ SMS kodları, doğrulayıcı uygulamalar veya e-posta tabanlı doğrulama seçenekleri ile kullanıcı dostu bir 2FA kurulumu sağlayın.

  &#x20;◦ Kullanıcı hesaplarına ve hassas verilere yetkisiz erişimi önlemek için JWT tokenlarının güvenli şekilde üretilmesini ve doğrulanmasını sağlayın.

  Bu büyük modül, 2FA sunarak kullanıcı hesap güvenliğini güçlendirmeyi ve JSON Web Token (JWT) kullanarak kimlik doğrulama ve yetkilendirmeyi geliştirmeyi amaçlar.

## IV.7 DevOps

Bu modüller, projenin altyapısını ve mimarisini geliştirmeye odaklanır. Büyük modüller, ELK (Elasticsearch, Logstash, Kibana) kullanarak verimli log yönetimi için altyapı kurulumu, backend'i esnek ve ölçeklenebilir mikro servisler olarak tasarlama ve Prometheus/Grafana kullanarak kapsamlı bir sistem izleme altyapısı sağlamayı kapsar.

* Büyük modül: ELK (Elasticsearch, Logstash, Kibana) ile Log Yönetimi için Altyapı Kurulumu

  Bu büyük modülün amacı, ELK yığını (Elasticsearch, Logstash, Kibana) kullanarak sağlam bir log yönetimi ve analiz altyapısı oluşturmaktır.

  ◦ Elasticsearch'u dağıtarak log verilerini verimli şekilde depolayın ve indeksleyin, aramayı ve erişimi kolaylaştırın.

  ◦ Logstash'i yapılandırarak çeşitli kaynaklardan log verilerini toplayın, işleyin, dönüştürün ve Elasticsearch'e gönderin.&#x20;

  ◦ Kibana'yı yapılandırarak log verilerini görselleştirin, panolar oluşturun ve log olaylarından içgörüler elde edin.

  &#x20;◦ Log verisi depolamasını etkili yönetmek için veri saklama ve arşivleme politikaları tanımlayın.&#x20;

  ◦ Log verisini ve ELK bileşenlerine erişimi korumak için güvenlik önlemleri uygulayın.&#x20;

  Bu büyük modül, ELK yığını kullanarak güçlü bir log yönetimi ve analiz sistemi kurarak etkin sorun giderme, izleme ve sistem performansına dair içgörü sunmayı amaçlar.

* Küçük modül: İzleme Sistemi

  Bu küçük modülün amacı, Prometheus ve Grafana kullanarak kapsamlı bir izleme altyapısı kurmaktır.

  ◦ Prometheus'u izleme ve uyarı aracı olarak dağıtarak çeşitli sistem bileşenlerinden metrik toplayın ve sağlık/durum takibini yapın.

  ◦ Farklı hizmetler, veritabanları ve altyapı bileşenlerinden metrik toplamak için veri ihracatçıları ve entegrasyonları yapılandırın.

  ◦ Grafana kullanarak özel panolar ve görselleştirmeler oluşturun, sistem metriklerini ve performansı gerçek zamanlı olarak görüntüleyin.

  ◦ Prometheus'ta uyarı kuralları tanımlayarak kritik sorunları ve anormallikleri proaktif olarak tespit edin ve yanıt verin.

  ◦ Geçmiş metrik verileri için uygun veri saklama ve depolama stratejileri belirleyin.

  ◦ Hassas izleme verilerini korumak için Grafana'da güvenli kimlik doğrulama ve erişim kontrol mekanizmaları uygulayın.

  Bu küçük modül, Prometheus ve Grafana kullanarak gerçek zamanlı görünürlük ve proaktif sorun tespiti sağlayarak sistem performansını ve güvenilirliğini artırmayı amaçlar.

* Büyük modül: Backend’i Mikro Servisler Olarak Tasarlamak

  Bu büyük modülün amacı, sistemin backend'ini mikro servis yaklaşımıyla tasarlamaktır.

  ◦ Backend'i, her biri belirli işlevlerden veya özelliklerden sorumlu olacak şekilde daha küçük, gevşek bağlı mikro servislere bölün.

  ◦ Mikro servisler arasında net sınırlar ve arayüzler tanımlayarak bağımsız geliştirme, dağıtım ve ölçeklendirme sağlayın.

  ◦ Mikro servisler arasında veri alışverişi ve koordinasyon sağlamak için RESTful API'ler veya mesaj kuyrukları gibi iletişim mekanizmaları uygulayın.

  ◦ Her mikro servisin tek bir, net tanımlı görevden veya iş kabiliyetinden sorumlu olmasını sağlayarak bakım kolaylığı ve ölçeklenebilirlik sağlayın.

  Bu büyük modül, sistemin mimarisini mikro servis tasarımı ile geliştirerek backend bileşenlerinde daha fazla esneklik, ölçeklenebilirlik ve sürdürülebilirlik sağlamayı amaçlar.

## IV.8 Grafik

* Büyük modül: Gelişmiş 3D Tekniklerinin Uygulanması

  Bu büyük modül, "Grafik" başlığı altında Pong oyununun görsel yönlerini geliştirmeye odaklanır. Daha sürükleyici bir oyun deneyimi yaratmak için gelişmiş 3D tekniklerinin kullanımını tanıtır. Özellikle, istenen görsel efektleri elde etmek için Pong oyunu Babylon.js kullanılarak geliştirilecektir.

  ◦ Gelişmiş 3D Grafik: Bu modülün ana hedefi, Pong oyununun görsel kalitesini artırmak için gelişmiş 3D grafik tekniklerini uygulamaktır. Babylon.js kullanılarak oyuncuları oyun ortamına tamamen dahil eden etkileyici görsel efektler oluşturulur.

  ◦ Sürükleyici Oynanış: Gelişmiş 3D tekniklerinin eklenmesi, kullanıcıya görsel olarak etkileyici ve çekici bir Pong oyunu sunarak genel oynanış deneyimini geliştirir.

  ◦ Teknoloji Entegrasyonu: Bu modül için seçilen teknoloji Babylon.js'dir. 3D grafiklerin oluşturulmasında bu araçlar kullanılacak ve uyumluluk ile optimum performans sağlanacaktır.

  Bu büyük modül, gelişmiş 3D tekniklerini tanıtarak Pong oyununun görsel unsurlarını dönüştürmeyi amaçlar. Babylon.js kullanılarak oyunculara sürükleyici ve görsel olarak etkileyici bir oyun deneyimi sunmayı hedefler.

## IV.9 Erişilebilirlik

Bu modüller, web uygulamamızın erişilebilirliğini artırmak için tasarlanmıştır. Tüm cihazlarla uyumluluk, tarayıcı desteğinin genişletilmesi, çoklu dil desteği, görme engelli kullanıcılar için erişilebilirlik özellikleri ve performans ile kullanıcı deneyimini iyileştirmek için Sunucu Taraflı Rendering (SSR) entegrasyonu sağlanır.

* Küçük modül: Tüm cihazlarda destek

  Bu modülün ana amacı, web sitenizin tüm cihazlarda sorunsuz çalışmasını sağlamaktır.

  ◦ Web sitesi duyarlı olmalı, farklı ekran boyutları ve yönelimlere uyum sağlamalı, masaüstü, dizüstü, tablet ve akıllı telefonlarda tutarlı bir kullanıcı deneyimi sunmalıdır.

  ◦ Kullanıcılar, kullandıkları cihaza bağlı olarak dokunmatik ekranlar, klavyeler veya fareler gibi farklı giriş yöntemleriyle web sitesinde kolayca gezinebilmeli ve etkileşimde bulunabilmelidir.

  Bu modül, tüm cihazlarda tutarlı ve kullanıcı dostu bir deneyim sunarak erişilebilirliği ve kullanıcı memnuniyetini en üst düzeye çıkarmayı amaçlar.

* Küçük modül: Tarayıcı Uyumluluğunu Genişletme
  Bu küçük modülde amaç, web uygulamasının başka bir tarayıcıya destek ekleyerek uyumluluğunu artırmaktır.

  ◦ Kullanıcıların uygulamaya sorunsuz erişmesini ve kullanmasını sağlamak için tarayıcı desteğini ek bir web tarayıcısını da kapsayacak şekilde genişletin.

  ◦ Yeni desteklenen tarayıcıda web uygulamasının doğru çalıştığını ve doğru görüntülendiğini sağlamak için kapsamlı test ve optimizasyon yapın.

  ◦ Yeni eklenen tarayıcıda oluşabilecek uyumluluk sorunlarını veya görüntüleme tutarsızlıklarını giderin.

  ◦ Tüm desteklenen tarayıcılarda tutarlı bir kullanıcı deneyimi sağlayarak kullanılabilirliği ve işlevselliği koruyun.

  Bu küçük modül, kullanıcıların tarayıcı seçiminde daha fazla seçenek sunarak web uygulamasının erişilebilirliğini genişletmeyi amaçlar.

* Küçük modül: Çoklu Dil Desteği

  Bu küçük modülde amaç, web sitenizin çeşitli kullanıcı kitlelerine hitap edebilmesi için çoklu dil desteği sunmaktır.

  ◦ Daha geniş bir kitleye hitap etmek için web sitesinde en az üç dil desteği uygulayın.

  ◦ Kullanıcıların tercihine göre web sitesinin dilini kolayca değiştirebilmesi için bir dil değiştirme aracı veya seçici sağlayın.

  ◦ Navigasyon menüleri, başlıklar ve temel bilgiler gibi önemli site içeriğini desteklenen dillere çevirin.

  ◦ Seçilen dilden bağımsız olarak kullanıcıların web sitesinde sorunsuzca gezinmesini ve etkileşimde bulunmasını sağlayın.

  ◦ Çeviri sürecini basitleştirmek ve farklı diller arasında tutarlılığı korumak için dil paketleri veya yerelleştirme kütüphaneleri kullanmayı değerlendirin.

  ◦ Kullanıcıların bir sonraki ziyaretlerinde varsayılan olarak tercih ettikleri dili ayarlamalarına izin verin.

  Bu küçük modül, içeriği birden fazla dilde sunarak web sitenizin erişilebilirliğini ve kapsayıcılığını artırmayı, uluslararası kullanıcılar için daha kullanıcı dostu hale getirmeyi amaçlar.

* Küçük modül: Görme Engelliler için Erişilebilirlik Ekleme

  Bu küçük modülde amaç, web sitenizi görme engelli kullanıcılar için daha erişilebilir hale getirmektir.

  ◦ Ekran okuyucular ve yardımcı teknolojiler için destek sağlayın.
  ◦ Görseller için açık ve açıklayıcı alt metin ekleyin.

  ◦ Okunabilirlik için yüksek kontrastlı renk şeması kullanın.
  ◦ Klavye ile gezinme ve odak yönetimini destekleyin.

  ◦ Metin boyutunu ayarlamak için seçenekler sunun.
  ◦ Erişilebilirlik standartlarına uyum sağlamak için düzenli güncellemeler yapın.

  Bu modül, görme engelli bireyler için web sitesinin kullanılabilirliğini artırmayı ve erişilebilirlik standartlarına uyum sağlamayı amaçlar.

* Küçük modül: Sunucu Taraflı Rendering (SSR) Entegrasyonu

  Bu küçük modülde odak, Sunucu Taraflı Rendering (SSR) entegrasyonu yaparak web sitesinin performansını ve kullanıcı deneyimini iyileştirmektir.

  ◦ Web sitesinin yüklenme hızını ve genel performansını artırmak için SSR uygulayın.

  ◦ İçeriğin sunucuda önceden işlenmesini ve kullanıcıların tarayıcılarına daha hızlı yüklenmesini sağlayın.

  ◦ Arama motorları için önceden işlenmiş HTML içerik sunarak SEO'yu optimize edin.

  ◦ SSR avantajlarından faydalanırken tutarlı bir kullanıcı deneyimi sağlayın.

  Bu modül, daha hızlı yükleme süreleri ve gelişmiş kullanıcı deneyimi için Sunucu Taraflı Rendering'i entegre ederek web sitesi performansını ve SEO'yu artırmayı amaçlar.

## IV.10 Sunucu Taraflı Pong

* Büyük modül: Temel Pong'u Sunucu Taraflı Pong ile Değiştirme ve API Uygulama

  Bu büyük modülde amaç, temel Pong oyununu sunucu taraflı bir Pong oyunu ile değiştirmek ve buna bir API eklemektir.

  ◦ Pong oyunu için oynanış, top hareketi, puanlama ve oyuncu etkileşimlerini yönetmek için sunucu taraflı mantığı geliştirin.

  ◦ Pong oyunu ile etkileşimi sağlamak için gerekli kaynakları ve uç noktaları sunan bir API oluşturun, böylece oyun hem Komut Satırı Arayüzü (CLI) hem de web arayüzü üzerinden kısmen kullanılabilir.

  ◦ Oyun başlatma, oyuncu kontrolleri ve oyun durumu güncellemelerini destekleyecek API uç noktalarını tasarlayın ve uygulayın.

  &#x20;◦ Sunucu taraflı Pong oyununun duyarlı olmasını sağlayarak ilgi çekici ve keyifli bir oynanış deneyimi sunun.

  &#x20;◦ Sunucu taraflı Pong oyununu web uygulamasıyla entegre ederek kullanıcıların oyunu doğrudan web sitesinde oynamasını sağlayın. Bu büyük modül, Pong oyununu sunucu tarafına taşıyarak hem web arayüzü hem de CLI üzerinden etkileşime imkan tanır ve oyun kaynaklarına kolay erişim için bir API sunar.

* Büyük modül: CLI Üzerinden Web Kullanıcılarına Karşı Pong Oynama ve API Entegrasyonu

  Bu büyük modülde amaç, kullanıcıların oyunu web sürümünü kullanan oyunculara karşı Komut Satırı Arayüzü (CLI) üzerinden oynamasını sağlayan bir CLI geliştirmektir. CLI, web uygulamasına sorunsuz şekilde bağlanarak CLI kullanıcılarının web oyuncularına katılmasını ve etkileşimde bulunmasını mümkün kılar.

  ◦ Web sitesindeki Pong oynanış deneyimini yansıtan sağlam bir CLI uygulaması oluşturun, CLI kullanıcılarının Pong maçlarını başlatmasını ve katılmasını sağlayın.

  ◦ CLI ile web uygulaması arasında iletişim kurmak için API'yi kullanarak CLI kullanıcılarının siteye bağlanmasını ve web oyuncularıyla etkileşimde bulunmasını sağlayın.

  ◦ CLI içinde bir kullanıcı kimlik doğrulama mekanizması geliştirerek CLI kullanıcılarının web uygulamasına güvenli şekilde giriş yapmasını sağlayın.

  ◦ CLI ile web kullanıcıları arasında gerçek zamanlı senkronizasyon sağlayarak oynanış etkileşimlerinin sorunsuz ve tutarlı olmasını sağlayın.

  ◦ CLI kullanıcılarının web oyuncularıyla Pong maçlarına katılmasını ve oluşturmasını sağlayarak çapraz platform oynanışı mümkün kılın.

  ◦ CLI'nin web kullanıcılarına karşı Pong maçları için nasıl kullanılacağını açıklayan kapsamlı dokümantasyon ve rehber sunun.

  Bu büyük modül, CLI kullanıcılarını web oyuncularına API entegrasyonu ile sorunsuz şekilde bağlayarak birleşik ve etkileşimli bir oyun ortamı sunarak Pong oynanış deneyimini geliştirmeyi amaçlar.

  Bu modülü tamamlamak istiyorsanız, önceki modülü yapmanız şiddetle tavsiye edilir.

## V Bonus Kısım

Bu proje için bonus bölümü basit olacak şekilde tasarlanmıştır. Ek modüller eklemeniz gerekmektedir.

* Her bir küçük modül için beş puan verilecektir.
* Her bir büyük modül için on puan verilecektir.

Bonus bölümü yalnızca zorunlu kısım MÜKEMMEL olduğunda değerlendirilecektir. "Mükemmel" demek, zorunlu kısmın tamamen tamamlanmış ve sorunsuz çalışıyor olması demektir. Tüm zorunlu gereklilikleri karşılamıyorsanız bonus bölümünüz kesinlikle değerlendirilmez.

## VI Teslimat ve Eş Değerlendirme

Görevlerinizi her zamanki gibi Git deposunda teslim edin. Savunma sırasında yalnızca deponuzdaki işler değerlendirilecektir. Dosya adlarının doğru olduğundan emin olmak için iki kez kontrol etmeniz önerilir.

* Bir özelliği veya modülü tamamen sağlayan bir kütüphane veya araç kullanımı yasaktır.
* Üçüncü taraf bir kütüphane veya araç kullanımıyla ilgili doğrudan talimatlara (kullanılabilir, kullanılmalı, kullanılamaz) uyulmalıdır.
* Daha büyük bir özelliğin veya modülün alt bileşeni olan basit, benzersiz bir görevi çözen küçük bir kütüphane veya aracın kullanımı serbesttir.
* Değerlendirme sırasında ekip, konuda açıkça onaylanmamış ve konunun kısıtlamalarıyla çelişmeyen herhangi bir kütüphane veya araç kullanımını gerekçelendirecektir.
* Değerlendirme sırasında değerlendirici, belirli bir kütüphane veya aracın kullanımının meşru (ve izin verilen) olup olmadığını veya esasen tüm bir özelliği veya modülü çözüp çözmediğini (ve bu nedenle yasak olduğunu) belirleyecektir.
