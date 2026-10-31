# Nimotech — uygulama planı ve agent görevleri

## Güncel sorumluluk kararı — bütün uygulama Claude’da

31 Ekim 2026: Proje sahibi tüm uygulamayı Claude'a devretti. Site/panelin yanında sunucu/backend, veri tabanı, personel girişi/yetkileri, özel dosya deposu, AI, WhatsApp/e-posta, PDF, ücretsiz geçici hosting, test ve teslim işleri de Claude'un sorumluluğundadır. Codex manager koordinasyon, rapor inceleme ve sonuç doğrulamada kalır; paralel uygulama kodu geliştirmez. Claude rutin teknik kararlar veya backend işleri için Codex'in uygulamasını beklemez.

Eksik bilgi/hesap veya araç erişimi yalnız ilgili adımı bekletir. Claude engeli, gereken tek girdiyi ve buna rağmen ilerlettiği işi açıklar. Bu devir, tüm bağlantıların hazır olduğu veya tüm işlerin aynı akşam biteceği iddiası değildir. SMS askısı, hesap bağımsızlığı ve geçici Higgsfield API istisnası sürer. Eski issue gövdelerindeki rol ayrımı güncel iş dağılımı değildir; bu karar ve güncel görev belgeleri önceliklidir. Bu bir GitHub kullanıcı daveti/assignee ataması değildir.

## Güncel istisna — geçici Higgsfield API erişimi

31 Ekim 2026: Proje sahibi, geliştirme aşamasında kendi Higgsfield API anahtarının geçici kullanımına izin verdi. Bu yalnız Higgsfield API için istisnadır; diğer kişisel/VELIOFLOW hesaplarına bağlantı izni değildir. Anahtar sunucu tarafı secret yapılandırmasında tutulur; browser kodu, public depo/issue, sohbet, log veya PDF içine yazılmaz. Kişisel browser/CLI oturumu kullanılmaz.

Hesap/anahtar sağlayıcı adapterinden ve uygulama kodundan ayrılacak. Teslimde müşterinin anahtarıyla değiştirilecek ve uygulamanın eski anahtar olmadan çalıştığı doğrulanacak. Resmî API erişimi, ücretlendirme ve üretim/tekrar limitleri ayrıca kontrol edilecek; bu izin sınırsız harcama veya otomatik yeniden üretim anlamına gelmez. Bu kayıtta anahtar alınmadı, bağlantı kurulmadı ve ücretli üretim başlatılmadı.

Güncelleme: 31 Ekim 2026. Bu public depo, yapılacak işlerin ve bekleyen girdilerin paylaşılabilir kaydıdır. Uygulama kaynak kodu, müşteri kayıtları, araç fotoğrafları ve gizli yapılandırma içermez.

## Güncel yön

- Seçilen tasarım **A: koyu / sinematik**. Bu yön korunur; yeni üç tasarım turu başlatılmaz.
- Aktarılan kaynak durumu: statik HTML/CSS/JS, tarayıcı içi demo verisi. Backend, gerçek personel girişi, AI ve WhatsApp bağlantısı olmadığı raporlandı; kaynak incelemesi henüz yapılmadı.
- Hedef: fotoğraflı araç talebi → personel paneli → onaylı temsili AI önizleme → personelin fiyatıyla kişisel PDF → personelin kesinleştirdiği randevu.
- Eksik müşteri içeriği geliştirmeyi durdurmaz. İskelet, kalıcı kayıt, erişim, PDF ve sağlayıcı testleri şimdi hazırlanır; gerçek içerik/hesap gelince ilgili adım tamamlanır.
- Önce **ücretsiz geçici hosting ve sağlayıcı alt alan adı**, sonra **zaten mevcut müşteri domaini**. Yeni domain satın alma görevi yoktur.
- **SMS doğrulama ASKIDA:** Türk numarası henüz alınmadı. Numara ve sağlayıcı hazır olunca devam edilir; bu sırada diğer bot/istek korumaları yapılır.
- Sistem kişisel veya VELIOFLOW hesaplarına, açık browser/CLI oturumuna bağımlı kurulmaz. Müşteriye ait/ayrı proje mülkiyetindeki servisler ve taşınabilir kaynak/veri/deployment hedeflenir. Bu hesabın public plan deposu olması, üretim servislerinin bu hesaba bağlanması anlamına gelmez.

## Belgeler

- [GitHub görev bağlantıları](ISSUES.md)
- [Tüm görevler ve kabul ölçütleri](ROADMAP.md)
- [Eksik girdiler ve beklemeden yapılacaklar](BEKLEYEN-GIRDILER.md)
- [Bu akşamın öncelikleri](BU-AKSAM.md)
- [Claude/tasarımcı çalışma talimatı](CLAUDE-DEVIR.md)
- [Geçici hosting ve domain geçişi](HOSTING-VE-DEVIR.md)
- [Agent çalışma kuralları](AGENTS.md)
- [Makine tarafından okunabilir görev listesi](tasks.json)

## Durumların anlamı

**HAZIR:** işe başlanabilir; tamamlandı demek değildir. **KISMEN_BEKLIYOR:** hazırlık/test şimdi yapılabilir, bir bölüm içerik/hesap bekler. **BEKLIYOR:** gerçek aktivasyon eksik girdi yüzünden ertelenir; varsa hazırlık işi ayrıca belirtilir.

Görevler ayrıca GitHub Issues üzerinden izlenecek. Raporlanan eski testler seçilen tasarımın üretim kabulü sayılmaz. Kamuya açık görevlere parola, anahtar, telefon, müşteri fotoğrafı veya kişisel veri eklemeyin.
