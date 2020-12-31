# PCSX4
Free PlayStation 4 Emulatörü
# PCSX4 Hakkında 
PCSX4, Windows için  C ++ ile yazılmış açık kaynaklı deneysel bir PS4 Emulator projesidir. PS4 oyunları oynamanıza izin veren ilk ve tek emülatör. Arka uç API oluşturucuları olarak OpenGL, Vulkan ve DirectX 12 kullanıyor ve PS4 münhasırlarının çoğunu, hala beta sürümünde olduğu gibi bazı aksaklıklarla üst düzey makinelerde çalıştırıyor. İndirme bölümünden alabileceğiniz sık sürümler olacaktır .

# Hakkında 
Yerel PS4 Emülasyonu
PS4, x86_64 mimarisine dayalıdır, bu nedenle PCSX4, OGRE, Vulcan API ve Orbital donanım destekli sanallaştırmadan yararlanarak Windows sistemlerinde yerel olarak çalışır. PCSX4, görsel kaliteden ödün vermeden oyunları sorunsuz bir şekilde işler.

Kilitsiz FPS
Artık pek çok oyun 60 FPS ve ötesinde çalışabildiğinden, PS4 oyunlarını PCüzerinde değişken kare hızlarında ve pürüzsüz bir deneyimle oynayabilirsiniz. Vulkan desteğine sahip özel bir GPU'nuz varsa, iyi bir performans bekleyebilirsiniz.

Çoklu Giriş Aygıtları
PCSX4, çoklu giriş oyun cihazlarını destekler. Birinci şahıs nişancı oyunları için fare girişini bile kullanabilirsiniz. PS4 & XBOX-ONE denetleyicisinin PCSX4 üzerinde tak ve çalıştır desteği vardır.

# Başlangıç
PCSX4 Emulator is a PlayStation 4 

# İndir
Şu anda sadece Windows için destek vardır  https://github.com/SolveTube/PCSX4/releases/tag/1.09 buradan indirebilirsiniz.

# Kurulum 
Download PCSX4 extract from rar exe download rar password: st0956

#  Hangi İşletim Sistemleri Destekleniyor?
Yalnızca 64bit Windows 7, 8.1, 10 desteklenir.  Windows kullanıcılarının  .net framework 3.5, VC ++ 2015 ve DirectX 11.1 platform güncellemesi KB2670838-x64'ü  yüklemeleri gerekir.

# Hangi CPU'lar destekleniyor?
PCSX4, bir işlemcinin en çok 8 çekirdeğini kullanacak şekilde optimize edilmiştir, ancak SSE-4.2 ve AVX ile en az 4 çekirdekli işlemci gerektirir.

Intel:  Core-i5 3xxx  ve üstü desteklenmektedir.

AMD:  FX-41xx ve üstü desteklenmektedir.

PCSX4 ile CPU performansı ve kararlılığı büyük ölçüde farklılık gösterir ve hangi işlemcinin mükemmel çalıştığını söylemek zordur. Bazı mobil tabanlı i5 ve i7 işlemciler, daha düşük saat hızları nedeniyle performans sorunlarına neden olabilir.

# Hangi GPU'lar destekleniyor?
PCSX4, en az Direct 3D 11.1 ve Pixel shader model 5.0'ı desteklemek için bir GPU gerektirir.

Nvidia:  GeForce GTX 660 veya üstü gereklidir.

AMD:  AMD Radeon 7870 veya üstü gereklidir.

1080p çözünürlükte 60FPS'de her oyunu sorunsuz çalıştırmak için GeForce GTX 970 veya Radeon R9-290X önerilebilir. PCSX4, 4K çözünürlüğü destekliyor ancak çift üst düzey GPU'larla bile 60FPS'ye ulaşmak çok zor.

# Ne kadar bellek (RAM) Gerekir?
4 GB, PCSX4 için minimum gereksinimdir, ancak 6 GB  veya daha fazlası önerilir.  Daha yüksek saat hızlarına sahip RAM, oyun önbellek diski olarak SSD ile birlikte kullanıldığında oyun yükleme sürelerini artırabilir.

# Sorunlar 

1- Uygulama doğru bir şekilde başlatılamadı (0xc000007b)
Sisteminizde bazı DirectX dosyaları eksik olabilir, sisteminizde DirectX 11.1 platform güncellemesi KB2670838-x64'ün  kurulu olduğundan emin olun .

2-"MSVCP140.dll eksik olduğundan bu program başlatılamıyor
PCSX4 derleme için VisualC ++ 2015 kullanır, sisteminizde Visual C ++ 2010 yeniden dağıtılabilir  (64-bit) yüklü olduğundan emin olun  .

3-XINPUT1_3.dll bulunamadığı için bu uygulama başlatılamadı
PCSX4, en son DirectX çalışma zamanını gerektirir,  bu hatayı düzeltmek için kurun.

# PCSX4  içinde PlayStation 4 oyunlarını oynama
PCSX4 can run pirated games and original CD games. Piracy games will require .iso files. PCSX4 currently only supports games released exclusively for PlayStation 4.

# Teşşekkür 
PCSX4, bu PS4 Emulator projesine katkıda bulunan geliştiricilerimiz ve destekçilerimiz sayesinde birçok harika şey yapabilir. İyi öykünme performansını arşivlemek için hala uzun bir yoldayız ancak en iyi PlayStation 4 oyunlarını PC ve Mac'te oynanabilir hale getirmek için çok çalışıyoruz

# Sorumluluk Reddi
PCSX4 (PS4 Emulator) yasa dışı faaliyetler için yapılmamıştır ve korsanlıkla ilgili katı bir politikamız vardır. Tüm kaynaklar, yasal olarak sahip olunan cihazların, oyunların ve internette bulunan bilgilerin tersine mühendislik yoluyla elde edilir. Bu projenin temel amacı, oyun deneyimini geliştirmek, araştırmak ve cihaz öykünmesinin temel kavramları hakkında eğitim sağlamaktır.

# SSS
PCSX4 Nedir?
PCSX4, PC'nizde  S4 oyunları oynamanıza olanak tanıyan, donanım destekli sanallaştırmaya dayalı bir beta PlayStation 4 ve PlayStation 4 Pro emülatör projesidir. PS4 konsolunuzun "oyun istasyonu cihaz tanımlayıcısını" ( PDIX ) ve orijinal PS4 oyunlarını almasını gerektirir . PCSX4 geliştirme, ilk olarak 2014'ün sonlarında kapalı kaynakla başlatıldı, ancak daha sonra geliştirmeyi desteklemek için yarı açık kaynağa geçti. Daha fazla bilgi için bu hızlı başlangıç ​​kılavuzunu izleyin .

Pdix. Nedir?
S4 oyunları oynamanıza olanak tanıyan, donanım destekli sanallaştırmaya dayalı bir beta PlayStation 4 ve PlayStation 4 Pro emülatör projesidir. PS4 konsolunuzun "oyun istasyonu cihaz tanımlayıcısını" ( PDIX ) ve orijinal PS4 oyunlarını almasını gerektirir . PCSX4 geliştirme, ilk olarak 2014'ün sonlarında kapalı kaynakla başlatıldı, ancak daha sonra geliştirmeyi desteklemek için yarı açık kaynağa geçti. Daha fazla bilgi için bu hızlı başlangıç ​​kılavuzunu izleyin . 

Pdix. Nasıl Çıkarılır?
PDIX'i çıkarmak  için  PS4 web tarayıcınızda https://pcsx4.com/extract-pdix adresine gidin  . PCSX4'ü indirdikten sonra PCSX4'ün dosya konumuna .pdix adlı bir klasör açın  pdix'i PlayStation 4'te çıkarabilirsiniz fakat manuel olarakda döküm yapmak için https://github.com/pcsx4emudev/pdix-dumper buraya göz gezdirin.

# Uyumluluk
Bu sayfa hem PC hem de Mac'teki oyunların PCSX4 ile uyumluluk durumunu gösterir. Lütfen bu oyunların uyumluluk durumunun kullanıcılar tarafından gönderilen günlüklere / verilere dayandığını ve listenin bu emülatör tarafından desteklenen tüm oyunları içermediğini, çünkü her oyunu test edemeyeceğimizi unutmayın. Kullanıcılar , listeyi güncel tutmak için oyunların uyumluluk durumunu buraya gönderebilir . Oyun performansı, farklı grafik API'leri nedeniyle Windows ve macOS arasında da farklılık gösterebilir, ancak uyumluluk her iki işletim sisteminde de aynı kalır.

Abzu	Macera, sanat	Oynanabilir
Akiba Gezisi	Macera, döv onları	Oynanabilir
Yabancılaşma	Hepsini Vur	Oynanabilir
Genlik	Müzik, ritim	Giriş
Ark: Güçlü Olanın Hayatta Kalması	Eylem, hayatta kalma	Hatalar
Armello	Masa oyunu, RPG	Hatalar
Axiom Sınırı	Aksiyon macera	Oynanabilir
Bodrum Taraması	Eylem, 2.5D	Oynanabilir
Blacklight: İntikam	Birinci şahıs Nişancı	Oynanabilir
Kan yoluyla bulaşan	Aksiyon RPG	Oynanabilir
Kırık Çağ: Komple Macera	İşaretle ve tıkla	Hatalar
Gün ışığı	Hayatta kalma korku	Oynanabilir
Day of the Tentacle: Special Edition	Grafik macera	Oynanabilir
Gone Günler	Aksiyon macera, hayatta kalma korkusu	Oynanabilir
Şeytanın ruhları	kurgu rol yapma oyunu	Oynanabilir
Detroit: İnsan Olun	Macera	Oynanabilir
Digimon Story: Cyber ​​Sleuth	RPG	Oynanabilir
Disgaea 5	Taktik rol yapma	Oynanabilir
Doki-Doki Evreni	Macera	Oynanabilir
Downwell	Dikey kaydırmalı nişancı	Oynanabilir
Dragon Quest Üreticileri	RPG, sandbox	Oynanabilir
Dragon Quest Kahramanları	RPG	Oynanabilir
Driveclub	Yarış	Oynanabilir
Zindanlar 2	Strateji	Oynanabilir
Gungeon'a girin	Zindan sürün, onları vur	Oynanabilir
Herkes Rapture'a gitti	Macera	Oynanabilir
Şişman Prenses Maceraları	Action-adv, RPG	Oynanabilir
Final Fantasy XIV: A Realm Reborn	MMORPG	Oynanabilir
Firewatch	Action-adv	Oynanabilir
Futuridium EP Deluxe	Oyun makinesi	Hiçbir şey değil
Galak-Z: Boyut	Atıcı	Oynanabilir
Gauntlet: Slayer Sürümü	Kes ve eğik çizgi	Oynanabilir
Tsushima'nın Hayaleti	Aksiyon macera, gizlilik	Oynanabilir
God of War III Remastered	Kes ve eğik çizgi	Oynanabilir
Savaş Tanrısı (2018)	Action-adv	Oynanabilir
Godzilla	Action-adv	Hatalar
Büyük Krallık	Taktik RPG	Oynanabilir
Büyük Çağlar: Ortaçağ	Strateji	Oynanabilir
Gravity Rush Remastered	Action-adv, action RPG	Oynanabilir
Yuvayı Büyüt	Macera, platform oyunu	Oynanabilir
Suçlu Dişli Xrd	Savaş	Oynanabilir
Silahlar yukarı!	Eylem, strateji	Oynanabilir
Helldivers	Gerçek zamanlı strateji	Oynanabilir
Hitman Git	Bulmaca	Oynanabilir
Hohokum	Macera	Hatalar
Horizon Zero Dawn	Eylem rol yapma	Oynanabilir
Hotline Miami 2: Yanlış Numara	Aksiyon, yukarıdan aşağıya nişancı	Giriş
Rezil İlk Işık	Action-adv, open world	Oynanabilir
Rezil İkinci Oğul	Action-adv, open world	Oynanabilir
Görünmez, Inc.	Sıra tabanlı taktikler	Oynanabilir
Gerilme Öldür	Eylem, strateji	Oynanabilir
Killzone Gölge Düşüşü	Birinci şahıs Nişancı	Oynanabilir
Kingdom Hearts III	Eylem rol yapma	Oynanabilir
Knack	Platformer	Hatalar
Son muhafız	Macera	Oynanabilir
LittleBigPlanet 3	Platform, sandbox	Oynanabilir
Megadimension Neptunia VII	RPG	Oynanabilir
Paralı Krallar	Aksiyon, RPG, platform	Oynanabilir
MLB 14: Gösteri	Spor Dalları	Oynanabilir
MLB 15: Gösteri	Spor Dalları	Oynanabilir
MLB 16: Gösteri	Spor	Oynanabilir
Mystery Chronicle: One Way Heroics	RPG	Oynanabilir
N ++	Metanet Yazılımı	Hiçbir şey değil
Ni-Oh	Aksiyon RPG	Oynanabilir
No Man's Sky	Dünyayı aç	Oynanabilir
Nobunaga'nın Tutkusu: Etki Alanı	Taktik RPG	Oynanabilir
Nükleer Taht	Aksiyon, roguelike	Crash
Omega Beşlisi	RPG, idol Simülasyonu	Crash
Odin Küresi: Leifthrasir	Aksiyon RPG	Oynanabilir
Sipariş: 1886	Üçüncü şahıs nişancı	Oynanabilir
Pix the Cat	Oyun makinesi	Hiçbir şey değil
PlanetSide 2	MMOFPS	Oynanabilir
Pox Nora	Taktik kartlar	Oynanabilir
Cırcır ve Clank	Platform	Oynanabilir
Red Dead Redemption 2	Action-adv	Oynanabilir
Resogun	Hepsini Vur	Oynanabilir
Gizli Pançolar	Nişancı, kavga	Giriş
Senran Kagura: Estival Versus	Savaş	Oynanabilir
Canavarın Gölgesi	Aksiyon	Oynanabilir
SOMA	Hayatta kalma korku	Oynanabilir
Yıldız Okyanusu: Dürüstlük ve Sadakatsizlik	Aksiyon RPG	Oynanabilir
Hikayeler: Kaderlerin Yolu	Aksiyon RPG	Oynanabilir
Örümcek Adam (2018)	Aksiyon macera	Oynanabilir
Örümcek Adam: Miles Morales	Aksiyon macera	Oynanabilir
Street Fighter V	Savaş	Hatalar
Süper Anne Yükü	RPG, bulmaca	Oynanabilir
Savaşçıların Kralı XIV	Savaş	Oynanabilir
Oyun Odası	Arttırılmış gerçeklik	Crash
Zestiria Masalları	RPG	Oynanabilir
The Last of Us Remastered	Action-adv	Oynanabilir
The Last of Us Part II	Aksiyon macera	Oynanabilir
Talos İlkesi	Bulmaca	Crash
Tearaway Unfolded	Platformer	Oynanabilir
Transistör	Sıra tabanlı strateji	Oynanabilir
Zor Kuleler	Parti, bulmaca	Oynanabilir
Trine 3: Güç Eserleri	Platform, bulmaca	Oynanabilir
Ultra Sokak Dövüşçüsü IV	Savaş	Hatalar
Umbrella Corps	Hayatta kalma korku	Oynanabilir
Uncharted: Nathan Drake Koleksiyonu	Action-adv	Oynanabilir
Uncharted 4: Bir Hırsızın Sonu	Action-adv	Oynanabilir
Şafağa kadar	Hayatta kalma korku	Oynanabilir
Valkyria Chronicles Remaster	Strateji RPG	Oynanabilir
Ethan Carter'ın Kaybolması	Adv, puzzle	Oynanabilir
Ses	Gizlilik	Oynanabilir
War Thunder	MMO, savaş uçuş simülatörü	Crash
Şahit	Macera, bulmaca	Crash
Dünya Savaşı Toons	Birinci şahıs Nişancı	Oynanabilir
Yakuza 0	Aksiyon	Oynanabilir
Yakuza 6 Hayatın Şarkısı	Aksiyon macera	Oynanabilir

DEngine-pcsx4
Çalışkan Motor
Modern Bir Çapraz Platform Düşük Seviyeli 3D Grafik Kitaplığı Cıvıldamak

Diligent Engine , hafif bir çapraz platform grafik API'si soyutlama kitaplığı ve işleme çerçevesidir. Direct3D11, OpenGL ve OpenGLES aracılığıyla eski platformları desteklerken Direct3D12, Vulkan ve Metal'den tam olarak yararlanacak şekilde tasarlanmıştır. Diligent Engine, ortak ön uç API'yi ortaya çıkarır ve tüm platformlarda evrensel gölgeleme dili olarak HLSL'yi kullanır ve arka uçları oluşturur. Platforma özgü gölgelendirici gösterimleri (GLSL, DX bayt kodu veya SPIRV) karşılık gelen arka uçlarla kullanılabilir. Motor, bir oyun motorunda veya başka herhangi bir 3B uygulamada grafik alt sistemi olarak kullanılmak üzere tasarlanmıştır. Apache 2.0 lisansı altında dağıtılır ve kullanımı ücretsizdir.

Lisans Gitter üzerinde sohbet Discord'da sohbet edin Derleme Durumu Derleme Durumu Codacy Rozeti

Özellikleri
Çapraz platform
Desteklenen tüm platformlar ve işleme arka uçları için tam olarak aynı istemci kodu
Hayır #if defined(_WIN32)... #elif defined(LINUX)... #elif defined(ANDROID)...
Hayır #if defined(D3D11)... #elif defined(D3D12)... #elif defined(OPENGL)...
Tüm platformlarda ve tüm arka uçlarda tam olarak aynı HLSL gölgelendiricileri (VS, PS, GS, HS, DS, CS) çalışır
Yüksek performans
Modüler tasarım
Bileşenler mantıksal ve fiziksel olarak açıkça ayrılır ve gerektiğinde kullanılabilir
Sadece projeniz için ihtiyacınız olanı alın
Açık ve kısa API
C / C ++
Nesne tabanlı
Vatansız
Anahtar grafik özellikleri:
Yeni nesil grafik API'lerinden yararlanmak için tasarlanmış otomatik gölgelendirici kaynak bağlama
Çok iş parçacıklı komut arabelleği oluşturma
D3D12 / Vulkan arka uç ile 300 fps'de 50.000 çizim çağrısı
Çok iş parçacıklı kaynak oluşturma
Kaynak durumu geçişleri üzerinde otomatik veya açık kontrol
Tanımlayıcı ve bellek yönetimi
Shader kaynak yansıması
Kapsamlı doğrulama ve hata raporlama
Kodu hızlı ve güvenilir kılmak için modern c ++ özellikleri
Sürekli entegrasyon ile tutarlı yüksek kalite sağlanır
Otomatik derlemeler ve birim testi
Kaynak kodu biçimlendirme doğrulaması
Statik analiz
Üst düzey Rendering bileşenleri
Atmosferik ışık saçılım sonrası efekt
Ton eşleme araçları
Fiziksel tabanlı GLTF2.0 oluşturucu
Gölgeler
Sevgili Imgui ve Nuklear ile Entegrasyon
Desteklenen Plaformlar ve Düşük Seviye Grafik API'leri
Platform	D3D11	D3D12	OpenGL	Vulkan	OpenGLES	Derleme Durumu
 Win32 (Windows masaüstü)	✔️	✔️	✔️	✔️	-	Derleme Durumu
 Evrensel Windows	✔️	✔️	-	-	-	Derleme Durumu
 Linux	-	-	✔️	✔️	-	Derleme Durumu
 Mac os işletim sistemi	-	-	✔️	✔️( MoltenVK aracılığıyla )	-	Derleme Durumu
 Android	-	-	-	✔️	✔️	
 iOS	-	-	-	✔️( MoltenVK aracılığıyla )	✔️	Derleme Durumu
İçindekiler
Depoyu Klonlamak
Depo Yapısı
Derleme ve Çalıştırma Talimatları
Win32
Evrensel Windows Platformu
Linux
Android
Mac os işletim sistemi
iOS
Diligent Engine'i Mevcut Yapı Sistemiyle Entegre Etme
Derleme Seçenekleri
Yapıyı Özelleştirme
API ile Başlarken
Öğreticiler
Örnekler
Demolar
Üst Düzey Oluşturma Bileşenleri
Lisans
Katkı
Referanslar
Sürüm Geçmişi

Depoyu Klonlamak
Bu, dört alt modül içeren ana depodur . Depoyu ve tüm alt modülleri almak için aşağıdaki komutu kullanın:

git clone --recursive https://github.com/DiligentGraphics/DiligentEngine.git
Mevcut depoyu güncellerken, tüm alt modülleri güncellemeyi unutmayın:

git pull
git submodule update --recursive
En son sürümü edindikten sonra CMake'i yeniden çalıştırmak ve temiz yeniden oluşturma işlemi gerçekleştirmek de iyi bir fikirdir.


Depo Yapısı
Ana depo aşağıdaki alt modülleri içerir:

Çekirdek alt modülü , Direct3D11 , Direct3D12 , OpenGL / GLES ve Vulkan arka uçlarını uygular . Modül bağımsızdır ve kendi başına inşa edilebilir.
Araçlar alt modülü, doku yükleme kitaplığı , varlık yükleme kitaplığı , önemli imgui uygulaması ve yerel uygulama uygulamasını içerir .
DiligentFX , çeşitli işleme bileşenlerini uygulayan yüksek seviyeli bir işleme çerçevesidir. Modül, Çekirdek ve Araçlar modüllerine bağlıdır.
Örnekler alt modülü, Diligent Engine API'nin kullanımını göstermeyi amaçlayan öğreticiler ve örnek uygulamalar içerir. Modül, Core, Tools ve DiligentFX modüllerine bağlıdır.

Derleme ve Çalıştırma Talimatları
Diligent Engine, CMake'i çapraz platform oluşturma aracı olarak kullanır . Cmake'yi kullanmaya başlamak için en son sürümü indirin (3.16 veya üstü gereklidir). Başka bir derleme ön koşulu Python yorumlayıcısıdır (3.0 veya üstü gereklidir). Aşağıdaki talimatları izledikten sonra derleme / çalıştırma sorunları yaşıyorsanız, lütfen sorun giderme bölümüne bakın .


Win32
Ön koşullar oluşturun:

Windows SDK 10.0.17763.0 veya üstü (mesh gölgelendiriciler için 10.0.19041.0 gereklidir)
C ++ derleme araçları
Visual C ++ ATL Desteği
Derleme dosyaları oluşturmak için CMake GUI veya komut satırı aracını kullanın. Örneğin, build / Win64 klasöründe Visual Studio 2019 64 bit çözüm ve proje dosyaları oluşturmak için motorun kök klasörüne gidin ve aşağıdaki komutu çalıştırın:

cmake -S . -B ./build/Win64 -G "Visual Studio 16 2019" -A x64
Aşağıdaki komutu kullanarak Win8.1 SDK'yı hedefleyen Win32 çözümü oluşturabilirsiniz:

cmake -D CMAKE_SYSTEM_VERSION=8.1 -S . -B ./build/Win64_8.1 -G "Visual Studio 16 2019" -A x64
MinGW kullanıyorsanız, aşağıdaki komutu kullanarak make dosyalarını oluşturabilirsiniz (ancak işlevselliğin sınırlı olacağını ve MinGW'nin motoru oluşturmak için önerilen bir yol olmadığını unutmayın):

cmake -S . -B ./build/MinGW -D CMAKE_BUILD_TYPE=Release -G "MinGW Makefiles"
⚠️Mevcut uygulamada, cmake derleme klasörüne giden tam yol beyaz boşluklar içermemelidir .

Vulkan doğrulama katmanlarını etkinleştirmek için, Vulkan SDK'yı indirmeniz ve VulkanSDK kurulum klasöründeki Bin dizininin VK_LAYER_PATHyolunu içeren environemt değişkenini eklemeniz gerekir .

Build / Win64 klasöründe DiligentEngine.sln dosyasını açın , konfigürasyonu seçin ve motoru oluşturun. İstediğiniz projeyi başlangıç ​​projesi olarak ayarlayın (varsayılan olarak GLTF Görüntüleyici seçilecektir) ve çalıştırın.

Varsayılan olarak, örnek ve öğretici uygulamalar arka uç oluşturma seçimi iletişim kutusunu gösterecektir. : D3D11'i, D3D12, OpenGL veya Vulkan modunu zorlamak için aşağıdaki komut satırı seçeneklerini kullanın biçem D3D11'i , biçem D3D12 , biçem GL veya VK-biçem . Visual Studio ortamı dışında bir uygulama çalıştırmak istiyorsanız, uygulamanın varlıklar klasörü çalışma dizini olarak ayarlanmalıdır. (Visual Studio için bu, CMake tarafından otomatik olarak yapılandırılır). Alternatif olarak, yapı hedefine veya yükleme klasörüne gidebilir ve yürütülebilir dosyayı buradan çalıştırabilirsiniz.


Evrensel Windows Platformu
Evrensel Windows platformu için derleme dosyaları oluşturmak için aşağıdaki iki cmake değişkenini tanımlamanız gerekir:

CMAKE_SYSTEM_NAME=WindowsStore
CMAKE_SYSTEM_VERSION=< Windows SDK Version >
Örneğin, build / UWP64 klasöründe Visual Studio 2019 64 bit çözüm ve proje dosyaları oluşturmak için motorun kök klasöründen aşağıdaki komutu çalıştırın:

cmake -D CMAKE_SYSTEM_NAME=WindowsStore -D CMAKE_SYSTEM_VERSION=10.0 -S . -B ./build/UWP64 -G "Visual Studio 16 2019" -A x64
CMAKE_SYSTEM_VERSION'ı iyileştirerek belirli bir SDK sürümünü hedefleyebilirsiniz, örneğin:

cmake -D CMAKE_SYSTEM_NAME=WindowsStore -D CMAKE_SYSTEM_VERSION=10.0.16299.0 -S . -B ./build/UWP64 -G "Visual Studio 16 2019" -A x64
İstediğiniz projeyi başlangıç ​​projesi olarak ayarlayın (varsayılan olarak GLTF Görüntüleyici seçilecektir) ve çalıştırın.

Varsayılan olarak, uygulamalar D3D12 modunda çalışacaktır. Aşağıdaki komut satırı seçeneklerini kullanarak D3D11 veya D3D12'yi seçebilirsiniz: -mod D3D11 , -mod D3D12 .

Not: CMAKE_SYSTEM_VERSION = 8.1 cmake değişkenini tanımlayarak Windows 8.1'i hedefleyen bir çözüm üretmek mümkündür, ancak uygun c ++ 11 desteğinden yoksun Visual Studio 2013 (v120) araç setini kullanacağı için oluşturulamaz.


Linux
Linux ortamınızın c ++ geliştirme için ayarlanması gerekir. Zaten öyleyse, Diligent Engine modern c ++ özelliklerini kullandığı için c ++ araçlarınızın güncel olduğundan emin olun (gcc / g ++ 7 veya üstü önerilir). Aşağıdaki paketleri kurmanız gerekebilir:

gcc, make ve diğer gerekli c / c ++ araçları:
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install build-essential
cmake
sudo apt-get install cmake
Diğer gerekli paketler:
sudo apt-get install libx11-dev
sudo apt-get install mesa-common-dev
sudo apt-get install mesa-utils
sudo apt-get install libgl-dev
sudo apt-get install python3-distutils
Vulkan'ı yapılandırmak için şunları da yapmanız gerekecek:

GPU'nuz için en son Vulkan sürücülerini ve kitaplıklarını yükleyin
Vulkan SDK'yı yükleyin
Sisteminizin doğru şekilde yapılandırıldığından emin olmak için, SDK'dan örnekler oluşturmayı ve çalıştırmayı deneyebilirsiniz.
Hata ayıklama yapılandırması için dosya oluşturmak üzere motorun kök klasöründen aşağıdaki CMake komutunu çalıştırın:

cmake -S . -B ./build/Linux64 -G "Unix Makefiles" -DCMAKE_BUILD_TYPE="Debug"
Motoru oluşturmak için aşağıdaki komutu çalıştırın:

cmake --build ./build/Linux64
Motorun kök klasörü , motoru oluşturmak için IDE'yi yapılandıran Visual Studio Code ayarları dosyalarını içerir . Uygulamaları doğrudan IDE'den çalıştırabilirsiniz. Bir uygulamayı komut satırından çalıştırmak için uygulamanın varlıklar klasörü geçerli dizin olmalıdır.


Android
Lütfen makinenizin Android geliştirme için ayarlandığından emin olun. İndir Android Studio , yükleme ve NDK ve CMake yapılandırmak ve diğer gerekli araçları. Android Studio ile birlikte verilen CMake sürümünü kullanmıyorsanız, derleme dosyalarınızın doğru şekilde yapılandırıldığından emin olun . Ortamınızın doğru şekilde kurulduğunu doğrulamak için, Vulkan Android eğitimlerinin yanı sıra çaydanlıklar örneğini oluşturmayı deneyin .

Bilinen Sorunlar:

Yerel derleme python çalıştırılabilir bulamazsa , NativeApp'in build.gradle dosyasındaki CMake bağımsızPYTHON_EXECUTABLE değişkenlerine değişken ekleyin : -DPYTHON_EXECUTABLE=/Path/To/Your/Python36/python.exe
Yerel derleme shader_list.h dosyasını bozarsa git'e gidin ve değişiklikleri geri alın.
Android'de öğreticiler ve örnekler oluşturmak ve çalıştırmak için DiligentSamples / Android klasörünü Android Studio ile açın .

Varsayılan olarak, uygulamalar OpenGLES modunda çalışacaktır. Bunları Vulkan modunda çalıştırmak için aşağıdaki başlatma bayraklarını ekleyin: --es mode vk(Android Studio'da Çalıştır-> Yapılandırmaları Düzenle menüsüne gidin)


Mac os işletim sistemi
Depoyu klonladıktan sonra, Xcode projesi oluşturmak için motorun kök klasöründen aşağıdaki komutu çalıştırın ( sistemde CMake'nin kurulu olması gerekir ):

cmake -S . -B ./build/MacOS -G "Xcode"
Proje build/MacOSklasörde yer alacaktır .

Vulkan Derleme Ortamını Yapılandırma
Varsayılan olarak, MacOS'ta Vulkan uygulaması yoktur. Diligent Engine, Vulkan'ı dinamik olarak yükler ve MoltenVK veya gfx-taşınabilirlik gibi bir Vulkan Taşınabilirlik uygulamasını kullanabilir . VulkanSDK'yi kurun ve sisteminizin burada açıklandığı gibi doğru şekilde yapılandırıldığından emin olun . Özellikle, aşağıdaki ortam değişkenlerini tanımlamanız gerekebilir (Vulkan SDK'nın kurulu olduğu ~/LunarG/vulkansdk-macosve MoltenVK kullanmak istediğiniz varsayılarak):

export VULKAN_SDK=~/LunarG/vulkansdk-macos/macOS
export PATH=$VULKAN_SDK/bin:$PATH
export DYLD_LIBRARY_PATH=$VULKAN_SDK/lib:$DYLD_LIBRARY_PATH
export VK_ICD_FILENAMES=$VULKAN_SDK/share/vulkan/icd.d/MoltenVK_icd.json
export VK_LAYER_PATH=$VULKAN_SDK/share/vulkan/explicit_layer.d
Kabukta ayarlanan ortam değişkenlerinin, Launchpad veya diğer masaüstü GUI'den başlatılan uygulamalar tarafından görülmediğini unutmayın. Bu nedenle, bir uygulamanın Vulkan kitaplıklarını bulduğundan emin olmak için komut satırından başlatılması gerekir. Aynı nedenden dolayı, xcode proje dosyası da openkomut kullanılarak kabuktan açılmalıdır . Xcode sürüm 7 ve sonraki sürümlerde, bu davranışın önce aşağıdaki komut kullanılarak etkinleştirilmesi gerekebilir:

defaults write com.apple.dt.Xcode UseSanitizedBuildSystemEnvironment -bool NO
Daha fazla ayrıntı için lütfen bu sayfaya bakın.

⚠️ DYLD_LIBRARY_PATHve LD_LIBRARY_PATHortam değişkenleri, Sistem Bütünlüğü Koruması devre dışı bırakılmadığı sürece (genellikle önerilmez) MacOS'ta yok sayılır. Yürütülebilir dosyaların Vulkan kitaplığını bulması için rpath içinde olması gerekir. Eğer VULKAN_SDKortam değişkeni ayarlamak ve doğru konuma noktaları olan, Çalışkan Motor otomatik olarak tüm uygulamalar için rpath yapılandırır.

En son test edilen LunarG SDK sürümü: 1.2.154.0.


iOS
İOS derlemesi için yapılandırılmış Xcode projesi oluşturmak için motorun kök klasöründen aşağıdaki komutu çalıştırın :

cmake -S. -B ./build/iOS -DCMAKE_SYSTEM_NAME = iOS -G "Xcode"
Gerekirse, iOS dağıtım hedefinin yanı sıra diğer parametreleri de sağlayabilirsiniz, örneğin:

cmake -S. -B ./build/iOS -DCMAKE_SYSTEM_NAME = iOS -DCMAKE_OSX_DEPLOYMENT_TARGET = 11.0 -G "Xcode"
Xcode proje dosyasını build/IOSklasörde açın ve motoru oluşturun. Uygulamaları bir iOS cihazında çalıştırmak için proje ayarlarında uygun geliştirme ekibini ayarlamanız gerekir.

Vulkan Derleme Ortamını Yapılandırma
İOS'ta Vulkan'ı etkinleştirmek için, VulkanSDK'yı indirip yükleyin . İOS'ta Vulkan yükleyici yoktur ve Diligent Engine, Vulkan on Metal'i uygulayan MoltenVK XCFramework ( MoltenVk kurulum kılavuzuna bakın) ile doğrudan bağlantı kurar . İOS'ta Diligent Engine'de Vulkan'ı etkinleştirmek için, örneğin CMake'yi çalıştırırken Vulkan SDK'ya giden yolu belirtin (Vulkan SDK'nın şurada kurulu olduğunu varsayarak /LunarG/vulkansdk-macos):

cmake -DCMAKE_SYSTEM_NAME = iOS -DVULKAN_SDK = / LunarG / vulkansdk-macos -S. -B ./build/iOS -G "Xcode"
Varsayılan olarak, motor LunarG SDK'da bulunan MoltenVK XCFramework ile bağlantılıdır. Bu istenmiyorsa veya bir uygulama belirli bir konumdan bir çerçeve kullanmak istiyorsa, MoltenVK_FRAMEWORKCMake değişkeni aracılığıyla çerçeveye giden tam yolu sağlayabilir .

MoltenVK kurulumu ve kullanımı hakkında daha fazla bilgi için MoltenVK kullanım kılavuzuna bakın .

En son test edilen LunarG SDK sürümü: 1.2.154.0.


Diligent Engine'i Mevcut Yapı Sistemiyle Entegre Etme
Diligent modüler bir yapıya sahiptir, bu nedenle projeniz için yalnızca gerekli işlevselliği uygulayan bu alt modülleri kullanabilirsiniz. Aşağıdaki şema modüller arasındaki bağımlılıkları göstermektedir.

  Core
   |
   +------>Tools----------.
   |        |             |
   |        V             |
   +------->FX---------.  |
   |                   |  |
   |                   V  V
   '----------------->Samples
Projeniz Cmake Kullanıyor
Projeniz CMake kullanıyorsa, Diligent Engine eklemek yalnızca birkaç satır kod gerektirir. Dizin yapısının aşağıdaki gibi göründüğünü varsayalım:

|
+-DiligentCore
+-HelloDiligent.cpp
Ardından aşağıdaki adımların yapılması gerekir:

Aramak add_subdirectory(DiligentCore)
İçerme dizinleri listesine DiligentCore'u ekleyin
Gerekli oluşturma arka uçlarını uygulayan hedeflere bağımlılıklar ekleyin
Aşağıda bir CMake dosyası örneği verilmiştir:

cmake_minimum_required ( SÜRÜM 3.6)

proje (HelloDiligent CXX)

add_subdirectory (DiligentCore)

add_executable (HelloDiligent WIN32 HelloDiligent.cpp)
 target_compile_options (HelloDiligent PRIVATE -DUNICODE -DENGINE_DLL)
 target_include_directories (HelloDiligent PRIVATE  "DiligentCore" )

target_link_libraries (HelloDiligent
 PRIVATE
    Diligent-GraphicsEngineD3D11-paylaşımlı
    Diligent-GraphicsEngineOpenGL-paylaşımlı
    Çalışkan-GraphicsEngineD3D12-paylaşımlı
    Çalışkan-GraphicsEngineVk-paylaşımlı
)
copy_required_dlls (HelloDiligent)
copy_required_dlls(), sistemin onları bulup yükleyebilmesi için yürütülebilir dosyanın yanındaki paylaşılan kitaplıkları kopyalayan kullanışlı bir işlevdir. Alternatif olarak, target_link_libraries()komutu kullanarak kitaplıkların statik (aynı zamanda paylaşılan) sürümlerine bağlanabilirsiniz . Bu durumda , hedefler gerekli tüm içerme yollarını dışa aktardığından , dahil etme dizinleri listesine DiligentCore'u açıkça eklemeye gerek yoktur . Lütfen Windows ve Linux için başlangıç ​​eğitimlerine de göz atın .

Projeniz Cmake Kullanmıyor
Projeniz CMake kullanmıyorsa, CMake ile kitaplıklar oluşturmanız ve bunları derleme sisteminize eklemeniz önerilir. Windows platformları için, en son derleme yapılarını appveyor'dan indirebilirsiniz .

Global CMake kurulum dizini CMAKE_INTALL_PREFIX değişkeni tarafından kontrol edilir . /usr/localUNIX ve c:/Program Files/${PROJECT_NAME}Windows'da varsayılan olarak ayarlandığını unutmayın, bu istediğinizi olmayabilir. Kullanım -D CMAKE_INSTALL_PREFIX=installyerel kullanmak installyerine klasör:

cmake -S . -B ./build/Win64 -D CMAKE_INSTALL_PREFIX=install -G "Visual Studio 16 2019" -A x64
Kitaplıkları ve başlık dosyalarını yüklemek için, yapı klasöründen aşağıdaki CMake komutunu çalıştırın:

cmake --build. --target install
DiligentCore kurulum dizini, motoru entegre etmek için gereken her şeyi içerecektir:

include alt dizini gerekli tüm başlık dosyalarını içerecektir. Bu dizini içerme arama dizinlerinize ekleyin.
lib alt dizini statik kitaplıklar içerecektir.
bin alt dizini dinamik kitaplıklar içerecektir.
Daha kolay bir yol, dinamik kitaplıklarla bağlantı kurmaktır. Statik olarak bağlanırken, DiligentCore'un yanı sıra motor tarafından kullanılan tüm üçüncü taraf kitaplıklarını listelemeniz gerekecektir. Bunun yanı sıra, platforma özgü sistem kitaplıkları da belirtmeniz gerekecektir. Örneğin, Windows platformu için, projenizin bağlantı kurması gereken kitaplıkların listesi aşağıdaki gibi görünebilir:

DiligentCore.lib glslang.lib HLSL.lib OGLCompiler.lib OSDependent.lib spirv-cross-core.lib SPIRV.lib SPIRV-Tools-opt.lib SPIRV-Tools.lib glew-static.lib GenericCodeGen.lib MachineIndependent.lib vulkan-1.lib dxgi.lib d3d11.lib d3d12.lib d3dcompiler.lib opengl32.lib
Vulkan kitaplıkları DiligentCore / ThirdParty / vulkan / libs dizininde bulunabilir.

Çalışkan Motor başlıkları olarak tanımlanacak aşağıdaki platform makro biri gerektirir 1: PLATFORM_WIN32, PLATFORM_UNIVERSAL_WINDOWS, PLATFORM_ANDROID, PLATFORM_LINUX, PLATFORM_MACOS, PLATFORM_IOS.

Eğer aşağıdaki CKağıt seçenekleri kullanarak yüklemek istediğiniz motorun bileşenleri kontrol edebilir: DILIGENT_INSTALL_CORE, DILIGENT_INSTALL_FX, DILIGENT_INSTALL_SAMPLES, ve DILIGENT_INSTALL_TOOLS.

Motoru entegre etmenin başka bir yolu, derleme dosyaları (Visual Studio projeleri gibi) oluşturmak ve bunları derleme sisteminize eklemektir. Aşağıda açıklanan derleme özelleştirme, özel ihtiyaçlarınız için ayarları değiştirmenize yardımcı olabilir.


Derleme Seçenekleri
Varsayılan olarak, mevcut platformda bulunan tüm arka uçlar oluşturulmuştur. Devre dışı spesifik arka uçları için aşağıdaki seçenekleri kullanın: DILIGENT_NO_DIRECT3D11, DILIGENT_NO_DIRECT3D12, DILIGENT_NO_OPENGL, DILIGENT_NO_VULKAN, DILIGENT_NO_METAL. Seçenekler, aşağıdaki örnekte olduğu gibi cmake UI aracılığıyla veya komut satırından ayarlanabilir:

cmake -D DILIGENT_NO_DIRECT3D11=TRUE -S . -B ./build/Win64 -G "Visual Studio 16 2019" -A x64
Ayrıca, bireysel motor bileşenleri etkin veya aşağıdaki seçenekleri kullanarak devre dışı bırakılabilir: DILIGENT_BUILD_TOOLS, DILIGENT_BUILD_FX, DILIGENT_BUILD_SAMPLES, DILIGENT_BUILD_DEMOS, DILIGENT_BUILD_UNITY_PLUGIN. Yalnızca SampleBaseproje oluşturmak istiyorsanız, DILIGENT_BUILD_SAMPLE_BASE_ONLYseçeneğini kullanabilirsiniz .

Varsayılan olarak Vulkan arka ucu, çalışma zamanında HLSL ve GLSL gölgelendiricilerinin SPIRV'ye derlenmesini sağlayan glslang ile bağlantılıdır. Çalışma zamanı derlemesi gerekmiyorsa, glslang DILIGENT_NO_GLSLANGcmake seçeneğiyle devre dışı bırakılabilir . Ek olarak, Direct3D olmayan arka uçlarda HLSL desteği DILIGENT_NO_HLSLseçenekle devre dışı bırakılabilir . Seçeneklerin etkinleştirilmesi, özellikle mobil uygulamalar için önemli olabilecek Vulkan ve OpenGL arka uç ikililerinin boyutunu önemli ölçüde azaltır.

Diligent Engine , kod tabanında tutarlı biçimlendirme sağlamak için clang formatını kullanır . Doğrulama, DILIGENT_NO_FORMAT_VALIDATION CMake seçeneği kullanılarak devre dışı bırakılabilir . Biçimlendirme sorunları bulunursa herhangi bir havuz isteğinin başarısız olacağını unutmayın.


Yapıyı Özelleştirme
Diligent Engine, aşağıdaki isteğe bağlı cmake işlevlerini tanımlayan yapılandırma komut dosyası sağlayarak istemcilerin derleme ayarlarını özelleştirmesine olanak tanır :

custom_configure_build() - yapı yapılandırmaları, c / c ++ derleme bayrakları, bağlantı bayrakları vb. gibi genel yapı özelliklerini tanımlar.
custom_pre_configure_target() - derlemedeki her hedef için özel ayarları tanımlar ve motorun yapı sistemi hedefi yapılandırmaya başlamadan önce çağrılır.
custom_post_configure_target() - motorun yapı sistemi hedefi, istemcinin motor tarafından ayarlanan özellikleri geçersiz kılmasına izin verecek şekilde yapılandırdıktan sonra çağrılır.
Yapılandırma betiğinin yolu, BUILD_CONFIGURATION_FILEcmake çalıştırılırken değişken aracılığıyla sağlanmalı ve cmake kök klasörüne göre olmalıdır, örneğin:

cmake -D BUILD_CONFIGURATION_FILE=BuildConfig.cmake -S . -B ./build/Win64 -G "Visual Studio 16 2019" -A x64
Custom_configure_build () işlevi ile genel derleme ayarlarını özelleştirme
Tanımlanırsa, custom_configure_build()herhangi bir yapı hedefi eklenmeden önce işlev çağrılır. Varsayılan olarak, cmake aşağıdaki dört yapılandırmayı tanımlar: Debug, Release, RelWithDebInfo, MinSizeRel. İsterseniz CMAKE_CONFIGURATION_TYPESdeğişken ayarlayarak kendi yapı yapılandırmalarınızı tanımlayabilirsiniz . Örneğin, yalnızca iki yapılandırmaya sahip olmak istiyorsanız: Debug ve ReleaseMT, aşağıdaki satırı custom_configure_build() işleve ekleyin :

set (CMAKE_CONFIGURATION_TYPES Debug ReleaseMT CACHE STRING "Yapılandırma türleri: Hata Ayıklama, ReleaseMT"  FORCE )
Derleme sisteminin hata ayıklama ve yayın (optimize edilmiş) yapılandırmalarının listesini bilmesi gerekir, bu nedenle aşağıdaki iki değişken de CMAKE_CONFIGURATION_TYPESdeğişken tanımlandığında ayarlanmalıdır :

set (DEBUG_CONFIGURATIONS DEBUG CACHE INTERNAL ""  FORCE )
 set (RELEASE_CONFIGURATIONS RELEASEMT CACHE INTERNAL ""  FORCE )
Nedeniyle cmake ayrıntılarının, yapılandırma adları sıralanan o Not DEBUG_CONFIGURATIONSve RELEASE_CONFIGURATIONS harfi büyük olmalıdır .

Dört standart cmake konfigürasyonu dışında herhangi bir konfigürasyon tanımlarsanız, her yeni konfigürasyon için aşağıdaki değişkenleri de ayarlamanız gerekir:

CMAKE_C_FLAGS_<Config> - c derleme bayrakları
CMAKE_CXX_FLAGS_<Config> - c ++ derleme bayrakları
CMAKE_EXE_LINKER_FLAGS_<Config> - yürütülebilir bağlantı bayrakları
CMAKE_SHARED_LINKER_FLAGS_<Config> - paylaşılan kütüphane bağlantı bayrakları
Örneğin:

seti (CMAKE_C_FLAGS_RELEASEMT "/ MT"  CACHE İÇ ""  KUVVET )
 seti (CMAKE_CXX_FLAGS_RELEASEMT "/ MT"  CACHE İÇ ""  KUVVET )
 seti (CMAKE_EXE_LINKER_FLAGS_RELEASEMT "/ OPT: REF"  CACHE İÇ ""  KUVVET )
 seti (CMAKE_SHARED_LINKER_FLAGS_RELEASEMT "/ OPT: REF"  ÖNBELLEK DAHİLİ ""  KUVVET )
Aşağıda bir custom_configure_build () işlevi örneği verilmiştir:

fonksiyonu (custom_configure_build)
     halinde (CMAKE_CONFIGURATION_TYPES)
         # ayıklama yapılandırmaları 
        set (DEBUG_CONFIGURATIONS DEBUG cache İÇ ""  GÜÇ )
         # Yayın (optimize edilmiş) yapılandırmaları 
        set (RELEASE_CONFIGURATIONS RELEASEMT cache İÇ ""  GÜÇ )
         # değişken tanımlar cmake tarafından üretilen yapılandırmaları oluşturmak CMAKE_CONFIGURATION_TYPES 
        grubu (CMAKE_CONFIGURATION_TYPES ayıklama ReleaseMT CACHE STRING "Yapılandırma türleri: Debug, ReleaseMT"  FORCE )

        seti (CMAKE_CXX_FLAGS_RELEASEMT "/ MT"  CACHE İÇ ""  KUVVET )
         seti (CMAKE_C_FLAGS_RELEASEMT "/ MT"  CACHE İÇ ""  KUVVET )
         seti (CMAKE_EXE_LINKER_FLAGS_RELEASEMT "/ OPT: REF"  CACHE İÇ ""  KUVVET )
         seti (CMAKE_SHARED_LINKER_FLAGS_RELEASEMT "/ OPT: REF"  CACHE İÇ ""  KUVVET )
     endif ()
 endfunction ()
Custom_pre_configure_target () ve custom_post_configure_target () işlevleriyle bireysel hedef derleme ayarlarını özelleştirme
Tanımlanmışsa, custom_pre_configure_target() derleme sistemi tarafından oluşturulan her hedef için çağrılır ve hedefe özgü özelliklerin yapılandırılmasına izin verir.

Varsayılan olarak, yapı sistemi bazı hedef özellikleri ayarlar. Eğer custom_pre_configure_target()setleri tüm özellikleri gerekli, bu ayrı bir işlem ayarlayarak gerekli olduğunu inşa sistemini söyleyebilir TARGET_CONFIGURATION_COMPLETE ana kapsamı değişkeni TRUE:

ayarla (TARGET_CONFIGURATION_COMPLETE TRUE PARENT_SCOPE )
Aşağıda bir custom_pre_configure_target()fonksiyon örneği verilmiştir :

function (custom_pre_configure_target TARGET )
     set_target_properties ( $ {TARGET}  PROPERTIES
        STATIC_LIBRARY_FLAGS_RELEASEMT / LTCG
    )
    grubu (TARGET_CONFIGURATION_COMPLETE DOĞRU PARENT_SCOPE )   
 endfunction ()
İstemcinin yalnızca bazı ayarları geçersiz kılması gerekiyorsa custom_post_configure_target(), motor hedefi yapılandırmayı tamamladıktan sonra çağrılan işlevi tanımlayabilir , örneğin:

function (custom_post_configure_target TARGET )
     set_target_properties ( $ {TARGET}  PROPERTIES
        CXX_STANDARD 17
    )
endfunction ()

API ile Başlarken
Lütfen bu sayfaya bakın . Ayrıca, aşağıda listelenen eğitimler ve örnekler, başlamak için iyi bir yerdir.


Öğreticiler
Öğretici	Ekran görüntüsü	Açıklama
01 - Merhaba Üçgen		Bu eğitim, Diligent Engine API kullanılarak basit üçgenin nasıl oluşturulacağını gösterir.
02 - Küp		Bu eğitim, gerçek bir 3B nesnenin, bir küpün nasıl oluşturulacağını gösterir. Gölgelendiricilerin dosyalardan nasıl yükleneceğini, köşe, dizin ve tek tip tamponların nasıl oluşturulacağını ve kullanılacağını gösterir.
03 - Tekstüre etme		Bu eğitim, bir 3B nesneye nasıl doku uygulanacağını gösterir. Dosyadan bir dokunun nasıl yükleneceğini, gölgelendirici kaynak bağlama nesnesinin nasıl oluşturulacağını ve gölgelendiricide bir dokunun nasıl örnekleneceğini gösterir.
03 - Tekstüre-C		Bu eğitici, Tutorial03 ile aynıdır, ancak C API kullanılarak uygulanır.
04 - Örnekleme		Bu öğretici, her kopya için benzersiz dönüşüm matrisi kullanarak bir nesnenin birden çok kopyasını oluşturmak için örneklemenin nasıl kullanılacağını gösterir.
05 - Doku Dizisi		Bu eğitim, her örnek için benzersiz doku kullanmak üzere örneklemenin doku dizileriyle nasıl birleştirileceğini gösterir.
06 - Çoklu Okuma		Bu eğitim, birden çok iş parçacığından paralel olarak komut listelerinin nasıl oluşturulacağını gösterir.
07 - Geometri Gölgelendirici		Bu eğitimde, düzgün tel kafes oluşturmak için geometri gölgelendiricisinin nasıl kullanılacağı gösterilmektedir.
08 - Mozaikleme		Bu öğretici, basit uyarlanabilir arazi işleme algoritması uygulamak için donanım döşemesinin nasıl kullanılacağını gösterir.
09 - Dörtlü		Bu öğretici, dokuları ve karışım modlarını sık sık değiştirerek birden çok 2D dörtlünün nasıl oluşturulacağını gösterir.
10 - Veri Akışı		Bu eğitici, değişen miktarlarda verileri GPU'ya verimli bir şekilde aktarmak için dinamik arabellek eşleme stratejisini MAP_FLAG_DISCARDve MAP_FLAG_DO_NOT_SYNCHRONIZEişaretlerini gösterir.
11 - Kaynak Güncellemeleri		Bu eğitim, Diligent Engine'de arabellekleri ve dokuları güncellemenin farklı yollarını gösterir ve her yöntemle ilgili önemli dahili ayrıntıları ve performans sonuçlarını açıklar.
12 - Hedef Oluştur		Bu eğitim, bir 3B küpün ekran dışı oluşturma hedefine nasıl dönüştürüleceğini ve basit bir işlem sonrası efektinin nasıl yapılacağını gösterir.
13 - Gölge Haritası		Bu eğitim, bir gölge haritası kullanarak temel gölgelerin nasıl oluşturulacağını gösterir.
14 - Hesaplamalı Gölgelendirici		Bu eğitici, hesaplama gölgelendiricileri kullanarak basit bir parçacık simülasyon sisteminin nasıl uygulanacağını gösterir.
15 - Çoklu Windows		Bu eğitici, birden çok pencerede işlemek için Diligent Engine'in nasıl kullanılacağını gösterir.
16 - Bağlantısız Kaynaklar		Bu eğitici, oluşturma performansını önemli ölçüde iyileştirmek için yeni nesil API'ler tarafından etkinleştirilen dinamik gölgelendirici kaynak dizinleme özelliğinden yararlanan bir teknik olan bindless kaynakların nasıl uygulanacağını gösterir.
17 - MSAA		Bu eğitici, geometrik kenarların daha pürüzsüz ve geçici olarak daha kararlı görünmesi için çoklu örnek kenar yumuşatmanın (MSAA) nasıl kullanılacağını gösterir.
18 - Sorgular		Bu eğitici, GPU işlemi hakkında, oluşturulan temellerin sayısı, komut işleme süresi vb. Gibi çeşitli bilgileri almak için sorguların nasıl kullanılacağını gösterir.
19 - İşleme Geçişleri		Bu eğitici, basit ertelenmiş gölgelendirmeyi uygulamak için render passes API'sinin nasıl kullanılacağını gösterir.
20 - Mesh Gölgelendirici		Bu öğretici, GPU'da hayal kırıklığı ayıklama ve nesne LOD hesaplamasını uygulamak için yeni programlanabilir aşamalar olan büyütme ve ağ gölgelendiricilerin nasıl kullanılacağını gösterir.

Örnekler
Örneklem	Ekran görüntüsü	Açıklama
Atmosfer Örneği		Bu örnek, Epipolar Işık Saçılımı işlem sonrası efektinin fiziksel tabanlı bir atmosfer oluşturmak için bir uygulamaya nasıl entegre edileceğini gösterir .
GLTF Görüntüleyici		Bu örnek, GLTF modellerini yüklemek ve işlemek için Asset Loader ve GLTF PBR Renderer'ın nasıl kullanılacağını gösterir .
Gölgeler		Bu örnek, yüksek kaliteli gölgeler oluşturmak için Gölgeleme bileşeninin nasıl kullanılacağını gösterir .
Sevgili ImGui Demosu		Bu örnek, motorun sevilen imgui UI kitaplığıyla entegrasyonunu gösterir .
Nuklear Demosu		Bu örnek, motorun nuklear UI kitaplığıyla entegrasyonunu gösterir .
Merhaba AR		Bu örnek, Diligent Engine'in temel bir Android AR uygulamasında nasıl kullanılacağını gösterir.

Demolar
Proje	Ekran görüntüsü	Açıklama
Asteroitler Performans Ölçütü		Bu demo, bir performans karşılaştırması olarak tasarlanmıştır ve Intel tarafından geliştirilen bu demoya dayanmaktadır . 50.000 benzersiz dokulu asteroit oluşturur. Her asteroid, 1000 benzersiz ağdan birinin ve 10 benzersiz dokudan birinin birleşimidir. Örnek, orijinal D3D11 ve D3D12 yerel uygulamalarını kullanır ve farklı işleme modlarının performansının karşılaştırılmasına izin vermek için Diligent Engine API kullanarak uygulama ekler.
Unity Entegrasyon Demosu		Bu proje Diligent Engine'in Unity ile entegrasyonunu göstermektedir

Üst Düzey Oluşturma Bileşenleri
Üst düzey işleme işlevselliği, DiligentFX modülü tarafından gerçekleştirilir . Aşağıdaki bileşenler artık mevcuttur:

Epipolar ışık saçılımı sonrası etki


Ton eşleme gölgelendirici yardımcı programları

GLTF2.0 Yükleyici ve Görüntü tabanlı aydınlatmalı Fiziksel tabanlı oluşturucu .
	
	
Gölgeler



Diligent Engine kullanan ürünler
Ürününüzün Diligent Engine kullanması durumunda bize bir bağlantı gönderebilirseniz memnun oluruz.

Vrmac Graphics : .NET için çapraz platform grafik kitaplığı

Ürününüz burada (lütfen bir PR gönderin )!

Lisans
Apache 2.0 lisansına bakın .

Bu proje, her biri bağımsız lisanslamaya sahip olabilen bazı üçüncü taraf bağımlılıklarına sahiptir:

Çekirdek modülü:
SPIRV-Cross : SPIRV ayrıştırma ve çapraz derleme araçları.
SPIRV-Headers : SPIRV başlık dosyaları.
SPIRV-Tools : SPIRV optimizasyon ve doğrulama araçları.
glslang : Khronos referans derleyicisi ve GLSL, ESSL ve HLSL için doğrulayıcı.
glew : OpenGL Extension Wrangler Kitaplığı.
Araçlar modülü:
libjpeg : JPEG resim dosyalarını okumak ve yazmak için C kütüphanesi.
libtiff : TIFF Kitaplığı ve Yardımcı Programlar.
libpng : Resmi PNG referans kitaplığı.
zlib : Bir sıkıştırma kitaplığı.
tinygltf : Yalnızca bir başlık C ++ 11 glTF 2.0 kitaplığı.
sevgili imgui : Bir bloat içermeyen anlık mod grafik kullanıcı arabirimi kitaplığı.

Katkı
Kodunuza katkıda bulunmak için bu depoya bir Çekme İsteği gönderin. Diligent Engine , DiligentEngine deposundaki kodun Fikri Mülkiyet yükümlülüklerinden muaf olduğunu garanti eden Apache 2.0 lisansı altında lisanslanmıştır . Bu havuza kod gönderirken, kodun herhangi bir Fikri Mülkiyet iddiasından muaf olduğunu kabul ediyorsunuz.

Diligent Engine , kod tabanında tutarlı kaynak kodu stilini sağlamak için clang formatını kullanır . Biçim, her kaydetme ve çekme isteği için uygulayıcı ve geçiş tarafından doğrulanır ve herhangi bir kod biçimlendirme sorunu bulunursa derleme başarısız olur. Lütfen clang-format ve otomatik kod formatlamanın nasıl kurulacağına ilişkin talimatlar için bu sayfaya bakın .


Referanslar
API Referansı


Sürüm Geçmişi
Sürüm Geçmişine Bakın

# GCN-Vulkan-Hpp
Vulkan-Hpp: Vulkan için C ++ Bağlamaları
Vulkan-Hpp'nin amacı, geliştiricilerin Vulkan deneyimini CPU çalışma zamanı maliyeti getirmeden iyileştirmek için Vulkan C API'si için yalnızca başlık C ++ bağlamaları sağlamaktır. Numaralandırmalar ve bit alanları için tür güvenliği, STL kapsayıcı desteği, istisnalar ve basit numaralandırmalar gibi özellikler ekler.

Platform	Derleme Durumu
Linux	Derleme Durumu
Başlangıç
Vulkan-Hpp, 1.0.24 sürümünden beri LunarG Vulkan SDK'nın bir parçasıdır. Sadece #include <vulkan/vulkan.hpp>ve C ++ bağlamalarını kullanmaya hazırsınız. Henüz Vulkan SDK tarafından desteklenmeyen bir Vulkan sürümü kullanıyorsanız, başlığın en son sürümünü burada bulabilirsiniz .

Minimum Gereksinimler
Vulkan-Hpp, derlemek için C ++ 11 uyumlu bir derleyici gerektirir. Aşağıdaki derleyicilerin çalıştığı bilinmektedir:

Visual Studio> = 2015
GCC> = 4.8.2 (önceki sürüm çalışabilir, ancak test edilmemiştir)
Clang> = 3.3
Vulkan-Hpp, Numuneler ve Testler Oluşturma
Yerel örnekleri ve testleri oluşturmak için bu depoyu klonlamanız ve gerekli derleme dosyalarını oluşturmak için CMake'yi çalıştırmanız gerekir.

0.) CMake ve git'in kurulu olduğundan ve bir kabuktan erişilebilir olduğundan emin olun. Vulkan SDK'yı kurduğunuzdan emin olun. Güzel biçimlendirilmiş bir Vulkan-Hpp başlığı elde etmek için isteğe bağlı olarak clang-format> = 10.0 kurun. 1.) Git sağlayan bir kabuk açın ve depoyu aşağıdakilerle klonlayın: git clone --recurse-submodules https://github.com/KhronosGroup/Vulkan-Hpp.git 2.) Mevcut dizini yeni oluşturulan Vulkan-Hpp dizinine değiştirin. 3.) adlı yeni bir klasör oluşturun buildve mevcut dizini yeni oluşturulan klasörle değiştirin. 4.) CMake ile bir yapı ortamı oluşturun Oluşturucuların cmake -D DSAMPLES_BUILD_WITH_LOCAL_VULKAN_HPP=ON -DSAMPLES_BUILD=ON -DTESTS_BUILD_WITH_LOCAL_VULKAN_HPP=ON -DTESTS_BUILD=ON -G "<generator>" .. tam listesi için çalıştırın cmake -G. 5.) Oluşturulan projeyi bir IDE ile açın, örneğin Visual Studio veya ile derleme işlemini başlatın cmake --build ..

isteğe bağlı) Vulkan-Hpp'yi ve alt modüllerini güncellemek için çalıştırın git pull --recurse-submodules.

Opsiyonel özellikler
Biçimlendirme
Program clang-formatı CMake tarafından bulunursa, CLANG_FORMAT_EXECUTABLE tanımlaması buna göre ayarlanır. Bu durumda, oluşturulan vulkan.hpp, bu projenin kök dizininde bulunan .clang-format dosyası kullanılarak biçimlendirilir. Aksi takdirde, oluşturucuda sabit kodlanmış olarak biçimlendirilir.

Kullanım
ad alanı vk
Vulkan C API ile ad çakışmalarını önlemek için C ++ bağları vk ad alanında bulunur. Yeni adlandırma için aşağıdaki kurallar geçerlidir

Tüm işlevler, numaralandırmalar, tutamaçlar ve yapılarda Vk öneki kaldırılmıştır. Buna ek olarak, işlevlerin ilk harfi küçüktür.
vkCreateInstance olarak erişilebilir vk::createInstance
VkImageTiling olarak erişilebilir vk::ImageTiling
VkImageCreateInfo olarak erişilebilir vk::ImageCreateInfo
Numaralandırmalar, derleme zamanı türü güvenliği sağlamak için kapsamlı numaralandırmalarla eşlenir. İsimler, VK_ öneki ve tip infix kaldırılarak 'e' + CamelCase olarak değiştirildi. Enum türünün bir uzantı olması durumunda, uzantı soneki enum değerlerinden kaldırılmıştır.
Diğer tüm durumlarda, uzantı soneki kaldırılmamıştır.

VK_IMAGETYPE_2Dşimdi vk::ImageType::e2D.
VK_COLOR_SPACE_SRGB_NONLINEAR_KHRşimdi vk::ColorSpaceKHR::eSrgbNonlinear.
VK_STRUCTURE_TYPE_PRESENT_INFO_KHRşimdi vk::StructureType::ePresentInfoKHR.
Bayrak bitleri, _BITsonekin de kaldırılmasıyla, kapsamlı numaralandırmalar gibi işlenir .
Bazı durumlarda, Vulkan-Hpp'yi özel bir ad alanına taşımak gerekebilir. Bu, Vulkan-Hpp dahil edilmeden önce VULKAN_HPP_NAMESPACE tanımlanarak elde edilebilir.

Kulplar
Vulkan-Hpp, tam tip güvenliği sağlamak ve kollardaki üye işlevler için destek eklemek için tüm tutamaçlar için bir sınıf bildirir. Her işlev için bir tutamaç sınıfına, karşılık gelen tutamacı ilk parametre olarak kabul eden bir üye işlevi eklenmiştir. vkBindBufferMemory(device, ...)Birinin yerine yazabilir device.bindBufferMemory(...)veya vk::bindBufferMemory(device, ...).

Tutamaçlar için C / C ++ Birlikte Çalışma
64-bit platformlarda Vulkan-Hpp, C ++ Vulkan tutamaçları ve C Vulkan tutamaçları arasında örtük dönüştürmeleri destekler. 32 bit platformlarda gönderilemeyen tüm tutamaçlar şu şekilde tanımlanır uint64_t, bu nedenle, uyumsuz tutamaç türleri arasındaki atamaları yakalayacak derleme zamanında tür dönüştürme denetimleri engellenir. Vulkan-Hpp, 32 bit platformlar için örtük dönüştürmeyi öntanımlıdır ve bunun static_castgibi dönüşüm için a kullanılması önerilir : VkDevice = static_cast<VkDevice>(cppDevice)rasgele bazı int'lerin bir tutamaca dönüştürülmesini önlemek için veya tam tersi kazara. Kodunuzu 64 bitlik bir platformda geliştiriyorsanız, ancak kodunuzu derleme VULKAN_HPP_TYPESAFE_CONVERSIONsisteminizde 1'e tanımlayabileceğiniz açık yayınlar eklemeden veya dahil etmeden önce 32 bitlik bir platform için derlemek istiyorsanızvulkan.hpp. 64 bitlik platformlarda bu tanım varsayılan olarak 1'e ayarlanır ve örtük dönüştürmeleri devre dışı bırakmak için 0'a ayarlanabilir.

Bayraklar
Kapsamlı enum özelliği, bayraklara tür güvenliği ekler, ancak aynı zamanda işaret bitlerinin & ve | gibi bitsel işlemler için girdi olarak kullanılmasını da engeller.

Çözelti Vulkan-Hpp bir şablon sınıfı sağlar gibi vk::Flagsgibi standart işlemleri getiriyor &=, |=, &ve |bizim kapsamlı çeteleler için. 0 ile başlatma dışında, bu sınıf tam olarak normal bir bit maskesi gibi davranır ve kazara karşılık gelen numaralandırma tarafından belirtilmeyen bitleri ayarlamak imkansızdır. Bit maskesi işlemeye ilişkin birkaç örnek:

vk :: ImageUsageFlags iu1; // bit kümesi olmadan bir bit maskesini 
başlatın vk :: ImageUsageFlags iu2 = {}; // bit 
setsiz bir bit maskesi başlatın vk :: ImageUsageFlags iu3 = vk :: ImageUsageFlagBits :: eColorAttachment; // tek bir değerle 
başlat vk :: ImageUsageFlags iu4 = vk :: ImageUsageFlagBits :: eColorAttachment | vk :: ImageUsageFlagBits :: eStorage; // veya bir bit maskesi elde etmek için iki bit 
PipelineShaderStageCreateInfo ci ({} / * herhangi bir bit kümesi olmadan bir bayrak geçirin * / , ...);
CreateInfo yapıları
Vulkan'da bir tutamaç oluştururken genellikle CreateInfoyeni tanıtıcıyı tanımlayan bir yapı oluşturmak gerekir. Bu, aşağıdaki Vulkan C örneğinde görülebileceği gibi oldukça uzun bir kodla sonuçlanabilir:

VkImageCreateInfo ci;
ci. sType = VK_STRUCTURE_TYPE_IMAGE_CREATE_INFO;
ci.pNext = nullptr ;
ci.flags = ... bazı bayraklar ...;
ci.imageType = VK_IMAGE_TYPE_2D;
ci.format = VK_FORMAT_R8G8B8A8_UNORM;
ci.extent = VkExtent3D {genişlik, yükseklik, 1 };
ci.mipLevels = 1 ;
ci.arrayLayers = 1 ;
ci.samples = VK_SAMPLE_COUNT_1_BIT;
ci.tiling = VK_IMAGE_TILING_OPTIMAL;
ci.usage = VK_IMAGE_USAGE_COLOR_ATTACHMENT_BIT;
ci.sharingMode = VK_SHARING_MODE_EXCLUSIVE;
ci.queueFamilyIndexCount = 0 ;
ci.pQueueFamilyIndices = 0 ;
ci.initialLayout = VK_IMAGE_LAYOUT_UNDEFINED;
vkCreateImage (aygıt, & ci, ayırıcı ve görüntü));
Vulkan geliştiricilerinin bir CreateInfo yapısını alana göre doldururken karşılaştığı iki tipik sorun vardır

Bir veya daha fazla alan başlatılmadan bırakılır.
sType yanlış.
Özellikle ilkini tespit etmek zor.

Vulkan-Hpp, her üye değişkeni için bir parametre kabul eden tüm CreateInfo nesneleri için yapıcılar sağlar. Bu şekilde, bir değer unutulmuşsa derleyici bir derleyici hatası atar. Buna ek olarak sType, otomatik olarak doğru değerle doldurulur ve varsayılan olarak a'ya pNextayarlanır nullptr. Bir kurucuda aynı kod şu şekilde görünür:

vk :: ImageCreateInfo ci ({}, vk :: ImageType :: e2D, vk :: Format :: eR8G8B8A8Unorm,
                       {genişlik, yükseklik, 1 },
                        1 , 1 , vk :: SampleCountFlagBits :: e1 ,
                       vk :: ImageTiling :: eOptimal, vk :: ImageUsageFlagBits :: eColorAttachment,
                       vk :: SharingMode :: eExclusive, 0 , nullptr , vk :: ImageLayout :: eUndefined);
vk :: Image image = device.createImage (ci);
CreateInfo yapıları için oluşturucularla, geçici öğeler şu şekilde Vulkan işlevlerine de aktarılabilir:

vk :: Image image = device.createImage ({{}, vk :: ImageType :: e2D, vk :: Format :: eR8G8B8A8Unorm,
                                     {genişlik, yükseklik, 1 },
                                      1 , 1 , vk :: SampleCountFlagBits :: e1 ,
                                     vk :: ImageTiling :: eOptimal, vk :: ImageUsageFlagBits :: eColorAttachment,
                                     vk :: SharingMode :: eExclusive, 0 , nullptr , vk :: ImageLayout :: eUndefined});
Belirlenmiş Başlatıcılar
C ++ 20 ile başlayarak, C ++ belirlenmiş başlatıcıları destekler. Bu özellik, kullanıcı tarafından bildirilen veya miras alınan herhangi bir #define VULKAN_HPP_NO_STRUCT_CONSTRUCTORSkurucuya sahip olmamayı gerektirdiğinden, tüm yapı oluşturucularını vulkan.hpp'den kaldıran bunu yapmanız gerekir . Bunun yerine, toplu başlatmayı kullanabilirsiniz. Kaynağınızdaki ilk birkaç vk satırı şöyle görünebilir:

// vk :: ApplicationInfo yapısını 
başlat vk :: ApplicationInfo applicationInfo {. pApplicationName    = UygulamaAdı,
                                     . applicationVersion = 1 ,
                                     . pEngineName         = MotorAdı,
                                     . engineVersion       = 1 ,
                                     . apiVersion          = VK_API_VERSION_1_1};
        
// vk :: InstanceCreateInfo 
vk :: InstanceCreateInfo instanceCreateInfo {. pApplicationInfo = & applicationInfo};
onun yerine

// vk :: başlatmak ApplicationInfo yapısı 
vk :: ApplicationInfo applicationInfo (AppName, 1 , EngineName, 1 , VK_API_VERSION_1_1);
        
// vk :: InstanceCreateInfo 
vk :: InstanceCreateInfo instanceCreateInfo ({}, & applicationInfo);
Gösterge siparişinin beyan sırasına uyması gerektiğini unutmayın. Ayrıca, artık vk yapılarının sType üyesini açıkça ayarlayabileceğinizi de unutmayın. Bu ne gerekli (varsayılan olarak doğru şekilde başlatıldıkları için) ne de tavsiye edilir.

ArrayProxy Kullanarak Dizileri İşlevlere Aktarma
Vulkan API, iki işlev bağımsız değişkeni olarak (sayma, işaretçi) gerektiren birkaç yere sahiptir ve C ++, bu çifte mükemmel şekilde eşleşen birkaç kapsayıcıya sahiptir. Basitleştirmek gelişimi için Vulkan-Hpp bağları olanlar bağımsız değişken çiftlerinin yerini ArrayProxyboş diziler ve tek bir değer olarak STL konteyner kabul şablon sınıfı std::initializer_list, std::arrayve std::vectorinşaat için bağımsız değişken olarak. Bu şekilde, üretilen tek bir Vulkan sürümü, her bir konteyner türü için bir işlev oluştururken meydana gelebilecek kombinatorik patlamaya sahip olmadan çeşitli girdileri kabul edebilir.

ArrayProxy'nin nasıl kullanılacağına ilişkin bazı kod örnekleri:

vk :: CommandBuffer c;

// boş bir dizi 
geçir c.setScissor ( 0 , nullptr );

// tek bir değer iletin. Değer referans olarak aktarılır 
vk :: Rect2D scissorRect = {{ 0 , 0 }, { 640 , 480 }};
c.setScissor ( 0 , scissorRect);

// geçici bir değer iletir. 
c.setScissor ( 0 , {{ 0 , 0 }, { 640 , 480 }});

// yığından iki dikdörtgeni kullanarak bir std :: initializer_list oluşturun. Bu, dikdörtgenlerin bir kopyasını oluşturabilir. 
vk :: Rect2D scissorRect1 = {{ 0 , 0 }, { 320 , 240 }};
vk :: Rect2D scissorRect2 = {{ 320 , 240 }, { 320 , 240 }};
c.setScissor ( 0 , {scissorRect, scissorRect2});

// iki geçici dikdörtgen kullanarak bir std :: initializer_list oluşturun. 
c.setScissor ( 0 , {{    0 ,    0 }, { 320 , 240 }},
                {{ 320 , 240 }, { 320 , 240 }}
}
);

// bir std :: array 
std :: array <vk :: Rect2D, 2 > arr {scissorRect1, scissorRect2};
c.setScissor ( 0 , dizi);

// dinamik boyutta bir std :: vektör aktar
std :: vektör <vk :: Rect2D> vec;
vec.push_back (scissorRect1);
vec.push_back (scissorRect2);
c.setScissor ( 0 , vec);
Yapıları İşlevlere Aktarma
Vulkan-Hpp, yapılara işaretçiler için referanslar üretir. Bu dönüştürme, geçici yapıların işlevlere aktarılmasına izin verir ve bu da daha kısa kodla sonuçlanabilir. Girişin isteğe bağlı olması ve dolayısıyla bir boş göstericinin kabul edilmesi durumunda, parametre türü bir vk::Optional<T> const&tür olacaktır . Bu tür T, girdi olarak bir başvuruyu veya nullptr'yi kabul eder ve bu nedenle isteğe bağlı geçici yapılara izin verir.

// C
VkImageSubresource subResource;
subResource.aspectMask = 0 ;
subResource.mipLevel = 0 ;
subResource.arrayLayer = 0 ;
VkSubresourceLayout düzeni;
vkGetImageSubresourceLayout (cihaz, görüntü ve alt kaynak ve düzen);

// C ++ 
otomatik düzen = device.getImageSubresourceLayout (image, {{} / * flags * / , 0  / * miplevel * / , 0  / * arrayLayer * / });
Yapı İşaretçi Zincirleri
Vulkan, yapıların pNext işaretçisiyle zincirlenmesine izin verir. Vulkan-Hpp, minimum çabayla bu tür yapı zincirlerinin oluşturulmasına izin veren değişken bir şablon sınıfına sahiptir. Buna ek olarak, spesifikasyonun böyle bir pNextzincirin yapımına izin verip vermediğini derleme zamanında kontrol eder .

// Bu başarıyla derlenecektir.
vk :: StructureChain <vk :: MemoryAllocateInfo, vk :: ImportMemoryFdInfoKHR> c;
vk :: MemoryAllocateInfo & assignInfo = c.get <vk :: MemoryAllocateInfo> ();
vk :: ImportMemoryFdInfoKHR & fdInfo = c.get <vk :: ImportMemoryFdInfoKHR> ();

// Spesifikasyona göre geçerli olmadığı için derleme başarısız olur.
vk :: StructureChain <vk :: MemoryAllocateInfo, vk :: MemoryDedicatedRequirementsKHR> c;
vk :: MemoryAllocateInfo & assignInfo = c.get <vk :: MemoryAllocateInfo> ();
vk :: ImportMemoryFdInfoKHR & fdInfo = c.get <vk :: ImportMemoryFdInfoKHR> ();
Vulkan-Hpp, bu zincirler için, zincirin bir parçası olan tüm yapıların bir listesini kabul eden CreateInfo nesnelerine benzer bir kurucu sağlar. pNextAlan otomatik olarak doğru değere ayarlanır:

vk :: StructureChain <vk :: MemoryAllocateInfo, vk :: MemoryDedicatedAllocateInfo> c = {
   vk :: MemoryAllocateInfo (boyut, tür),
   vk :: MemoryDedicatedAllocateInfo (resim)
};
Bir StructureChain'in yapılarından biri kaldırılacaksa, belki bazı isteğe bağlı ayarlar nedeniyle, işlevi kullanabilirsiniz vk::StructureChain::unlink<ClassType>(). StructureChain'i, belirtilen yapı artık pNext zincirinin bir parçası olmayacak şekilde değiştirir. StructureChain'in gerçek bellek düzeninin bu işlev tarafından değiştirilmediğini unutmayın. Aynı yapının StructureChain'e tekrar eklenmesi gerektiğinde, kullanın vk::StructureChain::relink<ClassType>().

Bazen kullanıcının bilgi sorgulamak için önceden tahsis edilmiş bir yapı zincirini geçmesi gerekir. Bu durumlar için iki karşılık gelen alıcı işlevi vardır. Dönüş değerini oluşturmak için en az iki öğeden oluşan bir yapı zinciri oluşturan değişken bir şablona sahip olan:

// Sorgu vk :: MemoryRequirements2HR ve vk :: MemoryDedicatedRequirementsKHR, Device :: getBufferMemoryRequirements2KHR çağrılırken: 
auto result = device.getBufferMemoryRequirements2KHR <vk :: MemoryRequirements2KHR, vk :: MemoryDedicated ({} )KHR>;
vk :: MemoryRequirements2KHR & memReqs = result.get <vk :: MemoryRequirements2KHR> ();
vk :: MemoryDedicatedRequirementsKHR & dedMemReqs = result.get <vk :: MemoryDedicatedRequirementsKHR> ();
Zincirleme olmadan sadece temel yapıyı elde etmek için, sağlanan diğer alıcı işlevinin yapının alması için bir şablon bağımsız değişkenine ihtiyacı yoktur:

// Query just vk::MemoryRequirements2KHR
vk::MemoryRequirements2KHR memoryRequirements = device.getBufferMemoryRequirements2KHR({});
Dönüş değerleri, Hata Kodları ve İstisnalar
Varsayılan olarak Vulkan-Hpp'de istisnalar etkinleştirilmiştir. Bu, Vulkan-Hpp'nin bir Vk :: Result döndüren her işlev çağrısının dönüş kodunu kontrol ettiği anlamına gelir. Vk :: Result bir başarısızlıksa, std :: runtime_error atılır. Artık hata kodunu döndürmeye gerek olmadığından, C ++ bağları artık istenen gerçek dönüş değerini, yani bir vulkan tutamacını döndürebilir. Bu durumlarda, ResultValue :: type, döndürülen tür olarak tanımlanır.

Bir cihaz oluşturmak için şimdi yazabilirsiniz:

vk :: Device device = PhysicalDevice.createDevice (createInfo);
Bazı işlevler vk::Result::eSuccess, bir başarı kodu olarak değerlendirilmekten daha fazlasını sağlar . Bu işlevler için her zaman a döndürürüz ResultValue<SomeType>. Bunun bir örneği şu acquireNextImage2KHRşekilde kullanılabilir:

vk :: ResultValue < uint32_t > result = device- > acquireNextImage2KHR (acquireNextImageInfo);
anahtar (sonuç.sonucu)
{
	case vk :: Result :: eSuccess:
		currentBuffer = sonuç. değer ;
		kırmak ;
	vaka vk :: Sonuç :: eTimeout:
	 vaka vk :: Sonuç :: eNotReady:
	 vaka vk :: Sonuç :: eSuboptimalKHR:
		 // şey anlamlı do 
		kırmak ;
	default :
		 // olmamalı, çünkü diğer dönüş kodları bir hata olarak kabul edilir ve bir istisna 
		molası verir ;
}
Zaman geçtikçe bazı vulkan fonksiyonları, vk::Result::eSuccessbir başarı kodundan daha fazla sonuç kodunu desteklemeye başlayacak şekilde değişebilir . Bu mantıksal değişiklik C-API'de görünmez, ancak C ++ - API'de görünür, çünkü böyle bir işlev artık vk::ResultValue<SomeType>sadece yerine a döndürür SomeType. Bu tür (nadir) durumlarda, cpp-kaynaklarınızı bu API değişikliğini yansıtacak şekilde ayarlamanız gerekir.

İstisna işleme tanımlayarak devre dışı bırakılmışsa VULKAN_HPP_NO_EXCEPTIONStürünü ResultValue<SomeType>::typebir holding olan bir yapıdır vk::Resultve SomeType. Bu yapı, kullanarak dönüş değerlerini paketten çıkarmayı destekler std::tie.

vk::ArrayProxyVe dönüş değeri dönüşümünü kullanmak istemiyorsanız , yine de düz C-stili işlevi çağırabilirsiniz. Aşağıda, API'yi kullanmanın 3 yolunu gösteren üç örnek bulunmaktadır:

İlk snippet, API'nin istisnasız nasıl kullanılacağını ve dönüş değeri dönüşümünü gösterir:

// İstisna yok, dönüş değeri dönüşümü yok 
ShaderModuleCreateInfo createInfo (...);
ShaderModule shader1;
Sonuç sonucu = device.createShaderModule (& createInfo, ayırıcı, & shader1);
eğer (result.result! = VK_SUCCESS)
{
    hata kodunu işlemek;
    Temizlemek?
    dönüş ?
}

ShaderModule shader2;
Sonuç sonucu = device.createShaderModule (& createInfo, ayırıcı, & shader2);
eğer (sonuç! = VK_SUCCESS)
{
    hata kodunu işlemek;
    Temizlemek?
    dönüş ?
}
İkinci kod parçası, API'nin dönüş değeri dönüşümünü kullanarak, ancak istisnalar olmadan nasıl kullanılacağını gösterir. Zaten orijinal koddan biraz daha kısa:

ResultValue <ShaderModule> shaderResult1 = device.createShaderModule ({...} / * createInfo temporary * / );
eğer (shaderResult1.result! = VK_SUCCESS)
{
  hata kodunu işlemek;
  Temizlemek?
  dönüş ?
}

// std :: kravat desteği.
vk :: Sonuç sonucu;
vk :: ShaderModule shaderModule2;
std :: tie (sonuç, shaderModule2) = device.createShaderModule ({...} / * createInfo geçici * / );
eğer (shaderResult2.result! = VK_SUCCESS)
{
  hata kodunu işlemek;
  Temizlemek?
  dönüş ?
}
Sonucu paketinden çıkarmanın daha güzel bir yolu, C ++ 17'nin yapılandırılmış bağlamaları ile sağlanır. Tek satırlık bir kodla sonucu almamızı sağlayacaklar:

auto [sonuç, shaderModule2] = device.createShaderModule ({...} / * createInfo temporary * / );
Son olarak, son kod örneği istisnaları ve dönüş değeri dönüşümünü kullanıyor. Bu, API'nin varsayılan modudur.

 ShaderModule shader1;
 ShaderModule shader2;
 dene {
   shader1 = aygıt. createShaderModule ({...});
   shader2 = aygıt. createShaderModule ({...});
 } catch (std :: exception  const & e) {
    // hatayı ve boş kaynakları 
 işleyin}
Vulkan-Hpp'nin RAII tarzı tutamaçları desteklemediğini ve kaynaklarınızı hata işleyicide temizlemeniz gerektiğini unutmayın!

C ++ 17: [[nodiscard]]
C ++ 17 ve üstü ile, bazı işlevler [[nodiscard]] ile ilişkilendirilir ve bu, dönüş değerini herhangi bir şekilde kullanmazsanız bir uyarı ile sonuçlanır. VULKAN_HPP_NO_NODISCARD_WARNINGS'i tanımlayarak bu uyarıları kapatabilirsiniz.

Numaralandırmalar
Dönüş değeri dönüşümü için, özel işlem gerektiren özel bir dönüş değerleri sınıfı vardır: Numaralandırmalar. Numaralandırmalar için genellikle şu şekilde kod yazmanız gerekir:

std :: vector <LayerProperties, Ayırıcı> özellikleri;
uint32_t propertyCount;
Sonuç sonucu;
yapmak
{
  // sorgulanacak öğe sayısını belirle 
  result = static_cast <Result> ( vk :: enumerateDeviceLayerProperties (m_physicalDevice, & propertyCount, nullptr ));
  eğer ((sonuç == Sonuç :: eSuccess) && propertyCount)
  {
    // bellek ve sorgu 
    özelliklerini yeniden ayırın. yeniden boyutlandırma (propertyCount);
    result = static_cast <Result> ( vk :: enumerateDeviceLayerProperties (m_physicalDevice, & propertyCount, reinterpret_cast 
     <VkLayerProperties *> (properties. data ())));
  }
} while (sonuç == Sonuç :: eIncomplete);
// sayı değişmiş olabilir, özellikler yeterince büyük özellikte değilse yeniden başlayın. 
resize (propertyCount);
Bu döngüyü tekrar tekrar yazmak sıkıcı olduğundan ve hataya açık olduğundan, C ++ bağlama numaralandırmayı halleder, böylece sadece şunları yazabilirsiniz:

std :: vector <LayerProperties> properties = PhysicalDevice.enumerateDeviceLayerProperties ();
Otomatik kaynak yönetimi için UniqueHandle
Vulkan-Hpp bir vk::UniqueHandle<Type, Deleter>arayüz sağlar. Her bir Vulkan tutamaç türü için , altta yatan Vulkan kaynağını yok edildiğinde silen vk::Typebenzersiz bir tutamaç vk::UniqueTypevardır, örneğin vk::UniqueBuffer için benzersiz tutamaç vk::Buffer.

vk::TypeVulkan-Hpp tipi bir Vulkan tanıtıcısı oluşturan her işlev için , bir vk::UniqueType. Örneğin vk::Device::createBuffervardır vk::Device::createBufferUniqueve vk::allocateCommandBuffersvardır vk::allocateCommandBuffersUnique.

Otomatik imha için gerekli olduğundan vk::UniqueHandle, çoğu silicinin vk::AllocationCallbacksyapım için kullanılan ve üst tanıtıcıyı depolaması gerektiğinden , kullanmanın bir bedeli olduğunu unutmayın .

Özel ayırıcılar
Bazen std::vectorözel ayırıcılar ile kullanılması gerekir . Vulkan-Hpp, vk::ArrayProxybir vektör döndüren işlevler için ve işlevler için girdi olarak özel ayırıcılara sahip vektörleri destekler . İkinci durum için, favori özel ayırıcınızı aşağıdaki gibi fonksiyon çağrısına şablon argümanı olarak ekleyin:

std :: vector <LayerProperties, MyCustomAllocator> properties = PhysicalDevice.enumerateDeviceLayerProperties <MyCustomAllocator> ();
Ayrıca, bu işlevlere bir argüman olarak sağlayarak durum bilgisi olan bir özel ayırıcı da kullanabilirsiniz. Ne yazık ki, derleyicileri mutlu etmek için, aynı zamanda Dispatch argümanını da açıkça ayarlamanız gerekir. Varsayılanı elde etmek için basit bir "{}" yeterli olacaktır:

MyStatefulCustomAllocator ayırıcı;
std :: vector <LayerProperties, MyStatefulCustomAllocator> properties = PhysicalDevice.enumerateDeviceLayerProperties (allocator, {});
Özel iddialar
Vulkan.hpp'nin her yerinde, bir assert işlevi için birkaç çağrı vardır. Tanımlayarak VULKAN_HPP_ASSERT, bunun yerine çağrılmak üzere kendi özel assert işlevinizi belirtebilirsiniz.

Varsayılan olarak, tanımlandığında VULKAN_HPP_ASSERT_ON_RESULTsonuçları kontrol etmek için kullanılacaktır VULKAN_HPP_NO_EXCEPTIONS. Hataları kendi başınıza halletmek istiyorsanız, tıpkı olduğu gibi devre dışı bırakabilir / özelleştirebilirsiniz VULKAN_HPP_ASSERT.

Uzantılar / Cihaz Başına işlev işaretçileri
Vulkan yükleyici, yalnızca Vulkan temel işlevlerini ve sınırlı sayıda genişletmeyi açığa çıkarır. Vulkan-Hpp'yi uzantılarla kullanmak için, kullanılan tüm Vulkan işlevlerine saplamalar sağlayan bir kitaplığa sahip olmak veya Vulkan-Hpp'ye bu işlev işaretlerini göndermesini söylemek gerekir. Vulkan-Hpp, her işlev çağrısında son parametre olarak bir gönderme sınıfını kabul ederek işlev başına bir gönderme mekanizması sağlar. Gönderim sınıfı, kullanılan her Vulkan işlevi için çağrılabilir bir tür sağlamalıdır. Vulkan-Hpp DispatchLoaderDynamic, kitaplığın bildiği tüm işlev işaretlerini getiren tek bir uygulama sağlar .

// Bu gönderme sınıfı, geçirilen örnek aracılığıyla tüm işlev işaretçilerini getirecektir 
vk :: DispatchLoaderDynamic dldi (örnek);

// Bu gönderme sınıfı, mümkünse, iletilen aygıt için işlev işaretçilerini getirecek, yoksa iletilen örnek için 
vk :: DispatchLoaderDynamic dldid (örnek, aygıt);

// Son parametre 
device.getQueue (graphics_queue_family_index, 0 , & graphics_queue, dldid) olarak işlev çağrısına gönderme sınıfını ilet;
DispatchLoaderDynamicVarsayılan dağıtıcı olarak kullanmak için (şu anlama gelir: onu her işlev çağrısına açıkça eklemeniz gerekmez), bu varsayılan dağıtım programına depolama sağlamak #define VULKAN_HPP_DISPATCH_LOADER_DYNAMIC 1için makroyu VULKAN_HPP_DEFAULT_DISPATCH_LOADER_DYNAMIC_STORAGEkaynak kodunuzda tam olarak bir kez bulundurmanız gerekir. Ardından VULKAN_HPP_DEFAULT_DISPATCHER, aşağıdaki kod parçacıklarında gösterildiği gibi, makro tarafından kullanabilirsiniz . Böyle bir a oluşturmayı kolaylaştırmak DispatchLoaderDynamiciçin küçük bir yardımcı sınıf var DynamicLoader. Tam özellikli bir ürün oluşturmak DispatchLoaderDynamiciki ila üç aşamalı bir süreçtir:

örnek bağımsız işlev işaretçileri almak için PFN_vkGetInstanceProcAddr türünde bir işlev işaretçisi ile başlatın:
    vk :: DynamicLoader dl;
    PFN_vkGetInstanceProcAddr vkGetInstanceProcAddr = dl.getProcAddress <PFN_vkGetInstanceProcAddr> ( " vkGetInstanceProcAddr " );
    VULKAN_HPP_DEFAULT_DISPATCHER.init (vkGetInstanceProcAddr);
diğer tüm işlev işaretleyicilerini almak için bir vk :: Instance ile başlatın:
    vk :: Örnek örneği = vk :: createInstance ({}, nullptr );
    VULKAN_HPP_DEFAULT_DISPATCHER.init (örnek);
cihaza özel işlev işaretçileri almak için isteğe bağlı olarak bir vk :: Device ile başlat
    std :: vector <vk :: PhysicalDevice> PhysicalDevices = instance.enumeratePhysicalDevices ();
    assert (! PhysicalDevices.empty ());
    vk :: Device device = PhysicalDevices [ 0 ] .createDevice ({}, nullptr );
    VULKAN_HPP_DEFAULT_DISPATCHER.init (aygıt);
Yukarıdaki ikinci adımdan sonra, dağıtıcı tamamen işlevseldir. Üçüncü adımı eklemek, potansiyel olarak daha verimli bir kodla sonuçlanabilir.

Bazı durumlarda, DispatchLoaderDynamic için depolama alanı bir DLL'ye gömülmelidir. Bu durumlar VULKAN_HPP_STORAGE_SHAREDiçin, Vulkan-Hpp'ye deponun bir DLL'de bulunduğunu belirtmek için tanımlamanız gerekir . DLL'yi depolamayla derlerken VULKAN_HPP_STORAGE_SHARED_EXPORT, gerekli sembollerin dışa aktarılmasının da tanımlanması gerekir.

Tüm işlevler için, bu VULKAN_HPP_DEFAULT_DISPATCHER, o işlevin son bağımsız değişkeni için varsayılan değerdir. Her işlev çağrısı için (örneğin, farklı cihazlar için birden fazla göndericiniz olduğunda) açık bir şekilde dağıtıcı sağlamak istiyorsanız ve yanlışlıkla herhangi bir işlev çağrısını kaçırmadığınızdan emin olmak istiyorsanız, VULKAN_HPP_NO_DEFAULT_DISPATCHER tanımlayabilirsiniz. bu varsayılan bağımsız değişkeni kaldırmak için vulkan.hpp eklemeden önce.

Tip özellikleri
vulkan.hpp, şablon programlamayı kolaylaştıran birkaç tür özelliği sağlar:

template <typename EnumType, EnumType value> struct CppType Haritalar IndexTypedeğerleri ( IndexType::eUint16, IndexType::eUint32ilgili türü (için, ...) uint16_t, uint32_tüye tipine göre, ...) Type; Haritalar ObjectTypedeğerleri ( ObjectType::eInstance, ObjectType::eDeviceilgili türü (için, ...) vk::Instance, vk::Deviceüye tipine göre, ...) Type; Haritalar DebugReportObjectTypedeğerleri ( DebugReportObjectTypeEXT::eInstance, DebugReportObjectTypeEXT::eDeviceilgili türü (için, ...) vk::Instance, vk::Deviceüye tipine göre, ...) Type;
template <typename T> struct IndexTypeValue Skaler türleri ( uint16_t,, uint32_t...) karşılık gelen IndexTypedeğerle ( IndexType::eUint16, IndexType::eUint32, ...) eşler.
template <typename T> struct isVulkanHandleType Bir tür eşler truebir sap sınıfı (var ancak ve ancak vk::Instance, vk::Devicestatik üyesi tarafından, ...) value.
HandleClass::CType Haritalar sap sınıf ( vk::Instance, vk::Devicekarşılık gelen C-tipi (için, ...) VkInstance, VkDeviceüye tipine göre, ...) CType.
HandleClass::objectType Haritalar sap sınıf ( vk::Instance, vk::Devicekarşılık gelen, ...) ObjectTypedeğeri ( ObjectType::eInstance, ObjectType::eDevicestatik üyesi tarafından, ...) objectType.
HandleClass::debugReportObjectType Haritalar sap sınıf ( vk::Instance, vk::Devicekarşılık gelen, ...) DebugReportObjectTypeEXTdeğeri ( DebugReportObjectTypeEXT::eInstance, DebugReportObjectTypeEXT::eDevicestatik üyesi tarafından, ...) debugReportObjectType.
Örnekler ve Testler
Projenizi CMake kullanarak yapılandırdığınızda, çözümünüze bazı örnek projeler eklemek için SAMPLES_BUILD özelliğini etkinleştirebilirsiniz. Bunların çoğu LunarG örneklerinden gelen bağlantı noktalarıdır, ancak CreateDebugUtilsMessenger, InstanceVersion, PhysicalDeviceDisplayProperties, PhysicalDeviceExtensions, PhysicalDeviceFeatures, PhysicalDeviceGroups, PhysicalDeviceMemoryProperties, PhysicalDeviceProperties, PhysicalDeviceQueFeature gibi bazıları da vardır. Tüm bu örnekler sadece derlenmeli ve çalıştırılmalıdır. Projenizi CMake kullanarak yapılandırdığınızda, çözümünüze bazı test projeleri eklemek için TESTS_BUILD özelliğini etkinleştirebilirsiniz. Bu testler yalnızca derleme testleridir ve çalıştırılmaları gerekmez.

Yapılandırma Seçenekleri
Vulkan.hpp'nin özellik kümesini ve davranışını kontrol etmek için kullanabileceğiniz birkaç tanım vardır:

VULKAN_HPP_ASSERT
At various places in vulkan.hpp an assertion statement is used. By default, the standard assert funtions from <cassert> is called. By defining VULKAN_HPP_ASSERT before including vulkan.hpp, you can change that to any function with the very same interface.

VULKAN_HPP_ASSERT_ON_RESULT
If there are no exceptions enabled (see VULKAN_HPP_NO_EXCEPTIONS), an assertion statement checks for a valid success code returned from every vulkan call. By default, this is the very same assert function as defined by VULKAN_HPP_ASSERT, but by defining VULKAN_HPP_ASSERT_ON_RESULT you can replace just those assertions with your own function, using the very same interface.

VULKAN_HPP_DEFAULT_DISPATCHER
Every vk-function gets a Dispatcher as its very last argument, which defaults to VULKAN_HPP_DEFAULT_DISPATCHER. If VULKAN_HPP_DISPATCH_LOADER_DYNAMIC is defined to be 1, it is defaultDispatchLoaderDynamic. This in turn is the dispatcher instance, which is defined by VULKAN_HPP_DEFAULT_DISPATCH_LOADER_DYNAMIC_STORAGE, which has to be used exactly once in your sources. If, on the other hand, VULKAN_HPP_DISPATCH_LOADER_DYNAMIC is defined to something different from 1, VULKAN_HPP_DEFAULT_DISPATCHER is set to be DispatchLoaderStatic(). You can use your own default dispatcher by setting VULKAN_HPP_DEFAULT_DISPATCHER to an object that provides the same API. If you explicitly set VULKAN_HPP_DEFAULT_DISPATCHER, you need to set VULKAN_HPP_DEFAULT_DISPATCHER_TYPE accordingly as well.

VULKAN_HPP_DEFAULT_DISPATCHER_TYPE
Bu, tarafından belirtildiği gibi varsayılan dağıtıcı türünü adlandırır VULKAN_HPP_DEFAULT_DISPATCHER. Varsayılan olarak, VULKAN_HPP_DISPATCH_LOADER_DYNAMIC1 olmasına veya 1 olmamasına bağlı olarak DispatchLoaderDynamic veya DispatchLoaderStatic'tir . Açıkça ayarlarsanız VULKAN_HPP_DEFAULT_DISPATCHER, VULKAN_HPP_DEFAULT_DISPATCHER_TYPEbuna göre de ayarlamanız gerekir .

VULKAN_HPP_DEFAULT_DISPATCH_LOADER_DYNAMIC_STORAGE
Kendinizinkini tanımlamadıysanız VULKAN_HPP_DEFAULT_DISPATCHERve VULKAN_HPP_DISPATCH_LOADER_DYNAMIC1 (varsayılan) olarak tanımladıysanız, VULKAN_HPP_DEFAULT_DISPATCH_LOADER_DYNAMIC_STORAGEo varsayılan dağıtım programına depolama sağlamak için makroyu kaynak dosyalarınızdan herhangi birinde tam olarak bir kez bulundurmanız gerekir.

VULKAN_HPP_DISABLE_ENHANCED_MODE
Bu, vulkan.hpp'yi eklemeden önce tanımlandığında, esasen tüm gelişmiş işlevleri devre dışı bırakırsınız. Daha sonra elde edeceğiniz tek şey, kapsamlı numaralandırmalar aracılığıyla derleme zamanı hatası algılama, vk::Flagsbit maskeleri için yardımcı sınıfın kullanımı, varsayılan başlatma sağlayan tüm vulkan yapılar için sarmalayıcı yapıları ve vk::StructureChainyapı zincirlerinin derleme zamanı inşası için yardımcı sınıftır .

VULKAN_HPP_DISPATCH_LOADER_DYNAMIC
Bu, tarafından açıkça belirtilmediği sürece dinamik (1 olduğunda) veya statik (1 olmadığında) DispatchLoader'ı varsayılan olarak seçer VULKAN_HPP_DEFAULT_DISPATCHER. Varsayılan olarak bu, tanımlanmışsa 1 VK_NO_PROTOTYPES, aksi takdirde 0 olarak tanımlanır.

VULKAN_HPP_ENABLE_DYNAMIC_LOADER_TOOL
Varsayılan olarak, DynamicLoadervulkan kitaplığını dinamik olarak yüklemek için küçük bir yardımcı sınıf kullanılır. Vulkan.hpp'yi eklemeden önce 1'den farklı bir şeye ayarlarsanız, bu yardımcı kullanılamaz ve işlev için açıkça kendi yükleyici türünüzü sağlamanız gerekir DispatchLoaderDynamic::init().

VULKAN_HPP_INLINE
Bu, işlevleri satır içi olarak işaretlemek için kullanılan derleyiciye bağımlı öznitelik olacak şekilde ayarlanır. Derleyiciniz farklı bir özniteliğe ihtiyaç duyarsa, vulkan.hpp'yi eklemeden önce bunu uygun şekilde tanımlayabilirsiniz.

VULKAN_HPP_NAMESPACE
Varsayılan olarak vulkan.hpp ile kullanılan ad alanı vk. VULKAN_HPP_NAMESPACEVulkan.hpp eklemeden önce tanımlayarak bunu ayarlayabilirsiniz.

VULKAN_HPP_NO_EXCEPTIONS
Bir vulkan işlevi, bir başarı kodu olarak belirtilmemiş bir hata kodu döndürdüğünde, VULKAN_HPP_NO_EXCEPTIONSvulkan.hpp dahil edilmeden önce tanımlanmadıkça bir istisna atılır .

VULKAN_HPP_NO_NODISCARD_WARNINGS
C ++ 17 ile, bir vkşey döndüren tüm işlevler öznitelikle bildirilir [[nodiscard]]. Bu, VULKAN_HPP_NO_NODISCARD_WARNINGSvulkan.hpp dahil edilmeden önce tanımlanarak kaldırılabilir .

VULKAN_HPP_NO_SMART_HANDLE
VULKAN_HPP_NO_SMART_HANDLEVulkan.hpp eklemeden önce tanımlandığında , yardımcı sınıf UniqueHandleve tüm benzersiz tutamaç türleri kullanılamaz.

VULKAN_HPP_NO_SPACESHIP_OPERATOR
C ++ 20 ile uzay gemisi operatörü denen <=>şey tanıtıldı. Bu operatör destekleniyorsa, vulkan.hpp'deki tüm yapılar ve sınıflar bunun varsayılan uygulamasını kullanır. Şu anda bu operatörün bazı uygulamaları çok yavaş ve diğerleri eksik göründüğünden, VULKAN_HPP_NO_SPACESHIP_OPERATORvulkan.hpp'yi eklemeden önce tanımlayarak bu operatörü bu yapılardan ve sınıflardan kaldırabilirsiniz.

VULKAN_HPP_TYPESAFE_CONVERSION
32-bit vulkan, tutamaçlar için tür güvenli değildir, bu nedenle varsayılan olarak bu platformda kopya oluşturucularına izin vermeyiz. Bu özelliği 32 bit platformlarda etkinleştirmek için tanımlayın VULKAN_HPP_TYPESAFE_CONVERSION.

Kullanımdan kaldırılan öğeler
Vulkan.hpp'de kullanımdan kaldırıldı olarak işaretlenen birkaç öğe vardır (C ++ 14 ve üzeri ile):

Örtülü yayın operatörleri, vk::ResultValuebelirli koşullar altında potansiyel olarak yanlıştır. Bunun vk::ResultValueyerine , değerin üyesi olarak açıkça erişmelisiniz.

Tür özellikleri cpp_type<ObjectType::eObjectTypeID>, daha genel tür özellikleriyle değiştirilir CppType<Type, Type::eTypeID>.

Bazı işlevler (aşağıda listelenmiştir), vulkan.hpp'deki genel yaklaşıma uymayan bir arabirim sağlar; burada bir işlevden aldığınız değerlerin döndürülmesi beklenir. Bunun yerine, gerçekte bu değerleri döndüren, aynı ada sahip karşılık gelen işlevleri kullanın. Etkilenen işlevler şunlardır:

	Device::getAccelerationStructureHandleNV
	Device::getCalibratedTimestampsEXT
	Device::getQueryPoolResults
	Device::getRayTracingCaptureReplayShaderGroupHandlesKHR
	Device::getRayTracingShaderGroupHandlesKHR
	Device::getRayTracingShaderGroupHandlesNV
	Device::writeAccelerationStructuresPropertiesKHR
	PhysicalDevice::enumerateQueueFamilyPerformanceQueryCountersKHR
Tüm bu unsurlar Kasım 2021 civarında kaldırılacaktır.

Ayrıca bakınız
Bu listeye eklemek için bir PR göndermekten çekinmeyin.

Örnekler Bir Sascha Willems örneği Vulkan-Hpp
Vookoo Vulkan-Hpp için durum bilgili yardımcı sınıfları, Giriş Makalesi .
Lisans
Telif Hakkı 2015-2020 The Khronos Group Inc.

Apache Lisansı Sürüm 2.0 ("Lisans") kapsamında lisanslanmıştır; Lisans ile uyumlu olmadıkça bu dosyayı kullanamazsınız. Lisansın bir kopyasını şu adresten edinebilirsiniz:

http://www.apache.org/licenses/LICENSE-2.0
Geçerli yasalar gerektirmedikçe veya yazılı olarak kabul edilmedikçe, Lisans kapsamında dağıtılan yazılım, açık veya zımni HERHANGİ BİR GARANTİ VEYA KOŞUL OLMAKSIZIN "OLDUĞU GİBİ" esasına göre dağıtılır. Lisans kapsamındaki belirli dil yönetim izinleri ve sınırlamaları için Lisans'a bakın.

# pdix damperli kamyon
PDIX Damper
PCSX4'ün gerektirdiği dosyaları gerçek bir PlayStation 4 konsolundan boşaltmak / çıkarmak için damper. Damper şu anda PS4 FW ver 1.76, 4.55, 5.00, 5.05'i destekliyor.

Kullanım
Bilgisayarınızı ve PS4'ü aynı ağa bağlayın.

Ps4-payload-sdk kurulumu .

Oluşturmadan önce, içinde bulunan IP adresini ( #define BLOBS_ADDR IP(192,168,2,1)) çalışacağı source/blob.cbilgisayarın IP adresi ile değiştirin server.py.

Ürün yazılımı sürümünüz için yükü oluşturun make. Aşağıdaki desteklenen aygıt yazılımı sürümlerinden birini seçin: 1.76, 4.55, 5.00, 5.05. Örneğin:

5,00 yap
Sunucuyu şu şekilde başlatın:

python server.py
Bilgisayarınızın IP adresini PlayStation 4 web tarayıcısına girin ve ekrandaki talimatları izleyin. Tarafından sağlanan istismar server.pyyalnızca ürün yazılımı 5.00 için çalışır. Farklı bir bellenim kullanıyorsanız, manuel olarak bir açıktan yararlanma çalıştırmanız ve netcat / socat kullanarak damperli yükü göndermeniz gerekir:

socat -u DOSYA: dumper.bin TCP: " PS4 IP " : 9020
Geliştirme
Bu damper, yükleri bağlantı noktasında ikili biçimde dinleyen bir istismar gerektirir 9020. Bu yüklerin, kullanıcı adres alanında aşağıdaki şekilde eşlenmesi gerekir:

0x926200000: Kod (değiştirilebilir Makefile)
0x926300000: Veriler (değiştirilebilir Makefile)
0x926400000: Bağımsız değişkenler (değiştirilebilir source/main.c)
Ayrıca, sunucu 9021gelen blobları bağlantı noktasında ve isteğe bağlı olarak 9022hata ayıklama mesajlarını dinleyecektir .

Derleme Notları
Yeni bir FW için destek eklemek istiyorsanız source/ksdk_XXX.inc, şablon olarak bunlardan birini kullanın ve gerekli ofseti FW'nizinkiyle eşleşecek şekilde güncelleyin.

Kredi
AlexAltea

