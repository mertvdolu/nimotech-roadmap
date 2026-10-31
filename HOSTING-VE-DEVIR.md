# Ücretsiz geçici hosting ve sonradan devir

## Güncel sorumluluk kararı — bütün uygulama Claude’da

31 Ekim 2026: Proje sahibi tüm uygulamayı Claude'a devretti. Site/panelin yanında sunucu/backend, veri tabanı, personel girişi/yetkileri, özel dosya deposu, AI, WhatsApp/e-posta, PDF, ücretsiz geçici hosting, test ve teslim işleri de Claude'un sorumluluğundadır. Codex manager koordinasyon, rapor inceleme ve sonuç doğrulamada kalır; paralel uygulama kodu geliştirmez. Claude rutin teknik kararlar veya backend işleri için Codex'in uygulamasını beklemez.

Eksik bilgi/hesap veya araç erişimi yalnız ilgili adımı bekletir. Claude engeli, gereken tek girdiyi ve buna rağmen ilerlettiği işi açıklar. Bu devir, tüm bağlantıların hazır olduğu veya tüm işlerin aynı akşam biteceği iddiası değildir. SMS askısı, hesap bağımsızlığı ve geçici Higgsfield API istisnası sürer. Eski issue gövdelerindeki rol ayrımı güncel iş dağılımı değildir; bu karar ve güncel görev belgeleri önceliklidir. Bu bir GitHub kullanıcı daveti/assignee ataması değildir.

## Güncel istisna — geçici Higgsfield API erişimi

31 Ekim 2026: Proje sahibi, geliştirme aşamasında kendi Higgsfield API anahtarının geçici kullanımına izin verdi. Bu yalnız Higgsfield API için istisnadır; diğer kişisel/VELIOFLOW hesaplarına bağlantı izni değildir. Anahtar sunucu tarafı secret yapılandırmasında tutulur; browser kodu, public depo/issue, sohbet, log veya PDF içine yazılmaz. Kişisel browser/CLI oturumu kullanılmaz.

Hesap/anahtar sağlayıcı adapterinden ve uygulama kodundan ayrılacak. Teslimde müşterinin anahtarıyla değiştirilecek ve uygulamanın eski anahtar olmadan çalıştığı doğrulanacak. Resmî API erişimi, ücretlendirme ve üretim/tekrar limitleri ayrıca kontrol edilecek; bu izin sınırsız harcama veya otomatik yeniden üretim anlamına gelmez. Bu kayıtta anahtar alınmadı, bağlantı kurulmadı ve ücretli üretim başlatılmadı.

## Karar

Önce ücretsiz planın verdiği geçici adresle geliştirme/inceleme, sonra müşterinin zaten mevcut domainine geçiş. Domain beklemek kod ve önizleme hazırlığını durdurmaz. Ücretsiz geçici hosting, kalıcı üretim altyapısının ve tüm backend servislerinin ücretsiz olacağı taahhüdü değildir.

## Statik A tasarımı için aday

Cloudflare Pages, statik HTML için ücretsiz plan sınırları kapsamında adaydır; yayımdan sonra projeye `*.pages.dev` adresi verilir. Bu henüz oluşturulmuş veya rezerve edilmiş bir proje adı değildir. Resmî kaynaklar: [Statik HTML dağıtımı](https://developers.cloudflare.com/pages/framework-guides/deploy-anything/) ve [plan sınırları](https://developers.cloudflare.com/pages/platform/limits/). Kaynak incelemesi, hesap mülkiyeti ve deployment paketi doğrulaması yapılmadan hazır hosting var denmez.

Seçilen tasarımın site/panel/shared/vendor göreli yolları korunmalı; /site ve /panel veya seçilecek public yolları gerçekten çalışmalı. Yalnız gerekli ve izinli dosyalar çıktı paketinde olmalı. Özel kaynaklar, ham plakalı fotoğraflar, veritabanı ve sırlar yayımlanmaz. Staging arama motoru indekslemesi kapatılır; bu bir erişim kontrolü yerine geçmez. Genel tasarım demosu sentetik verili, gerçek veri alan staging ise doğrulanmış erişim kontrollü olmalı.

## Backend ayrı karardır

Kalıcı kayıt, personel kimliği, özel dosya deposu, PDF motoru, iş kuyruğu ve AI sağlayıcısı statik dosya hostinginden ayrı çalışma ihtiyaçlarıdır. Ücretsiz backend planlarının uyku/depolama/süre gibi sınırları ayrı incelenir. Örneğin [Render ücretsiz servisleri](https://render.com/docs/free) 15 dakika boşta kalınca uyuyabilir; bu yüzden anlık bildirim/kalıcı dosya beklentisi otomatik karşılanmış sayılmaz. Bu örnek Render seçildiği anlamına gelmez.

Önce yerelde taşınabilir backend ve örnek verilerle test; müşteri/ayrı proje mülkiyetindeki uygun ortam kesinleşince staging bağlantısı. Ücretli plana otomatik geçiş veya kart ekleme yok.

## Devir kabulü

- Kaynak, Git geçmişi, bağımlılık ve varlık lisansları.
- Migration, boş ayar örneği, kurulum ve deployment/geri alma komutları.
- Veri + özel fotoğraf/PDF yedekleri ve geri yükleme kanıtı.
- API/depoma/e-posta/WhatsApp/AI ve host URL'lerinin yapılandırmadan değişmesi.
- Kişisel bilgisayarın açık kalmasına veya tarayıcı/CLI oturumuna bağımlılık olmaması.
- Müşteri mülkiyetindeki hesaplar, faturalandırma ve kurtarma/erişim sahipliğinin belgelenmesi. Bir hesabın adında proje adı olması müşteri mülkiyeti kanıtı değildir.
- Gerçek müşteriye geçişte yeni anahtarlar, erişim gözden geçirmesi ve gerekiyorsa personel davetleri. Oturum/parolaların sağlayıcılar arasında sorunsuz taşınacağı vaat edilmez.
- Domain erişimi gelince DNS/HTTPS, URL/callback/webhook ve paylaşım bağlantıları güncellenip test edilir. Yeni domain satın alma gerekmez.
- Bu public plan deposu tek başına uygulama kodunun veya özel verilerin public yayımlanmasına izin değildir.
