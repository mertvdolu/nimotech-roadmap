# Bu akşam için uygulama sırası

## Güncel sorumluluk kararı — bütün uygulama Claude’da

31 Ekim 2026: Proje sahibi tüm uygulamayı Claude'a devretti. Site/panelin yanında sunucu/backend, veri tabanı, personel girişi/yetkileri, özel dosya deposu, AI, WhatsApp/e-posta, PDF, ücretsiz geçici hosting, test ve teslim işleri de Claude'un sorumluluğundadır. Codex manager koordinasyon, rapor inceleme ve sonuç doğrulamada kalır; paralel uygulama kodu geliştirmez. Claude rutin teknik kararlar veya backend işleri için Codex'in uygulamasını beklemez.

Eksik bilgi/hesap veya araç erişimi yalnız ilgili adımı bekletir. Claude engeli, gereken tek girdiyi ve buna rağmen ilerlettiği işi açıklar. Bu devir, tüm bağlantıların hazır olduğu veya tüm işlerin aynı akşam biteceği iddiası değildir. SMS askısı, hesap bağımsızlığı ve geçici Higgsfield API istisnası sürer. Eski issue gövdelerindeki rol ayrımı güncel iş dağılımı değildir; bu karar ve güncel görev belgeleri önceliklidir. Bu bir GitHub kullanıcı daveti/assignee ataması değildir.

## Güncel istisna — geçici Higgsfield API erişimi

31 Ekim 2026: Proje sahibi, geliştirme aşamasında kendi Higgsfield API anahtarının geçici kullanımına izin verdi. Bu yalnız Higgsfield API için istisnadır; diğer kişisel/VELIOFLOW hesaplarına bağlantı izni değildir. Anahtar sunucu tarafı secret yapılandırmasında tutulur; browser kodu, public depo/issue, sohbet, log veya PDF içine yazılmaz. Kişisel browser/CLI oturumu kullanılmaz.

Hesap/anahtar sağlayıcı adapterinden ve uygulama kodundan ayrılacak. Teslimde müşterinin anahtarıyla değiştirilecek ve uygulamanın eski anahtar olmadan çalıştığı doğrulanacak. Resmî API erişimi, ücretlendirme ve üretim/tekrar limitleri ayrıca kontrol edilecek; bu izin sınırsız harcama veya otomatik yeniden üretim anlamına gelmez. Bu kayıtta anahtar alınmadı, bağlantı kurulmadı ve ücretli üretim başlatılmadı.

Kaynak/erişim durumuna göre hedeflerdir; aynı akşam tamamlanma garantisi değildir. İçerik bekleyen işler çekirdek geliştirmeyi durdurmaz.

1. **A kaynak paketini güvenli devral:** bağımlılıklar, göreli yollar, lisanslar, gerçekten çalışan/demo özellik envanteri; değişiklikten önce arşiv ve Git başlangıcı.
2. **API/veri sözleşmesini sabitle:** form/panel/dosya/teklif durumları; agentler aynı dosyayı eşzamanlı değiştirmesin.
3. **Kalıcı uçtan uca talep:** örnek fotoğraf + zorunlu araç/iletişim → sunucuda kayıt → yetkili panel; yeniden başlatınca kayıt kalır.
4. **Kişisel teklif PDF'i:** personelin fiyat/kapsamı → gerçek PDF → panelden özel erişim; eksik ürün/garanti alanları açıkça taslak.
5. **Ücretsiz geçici yayın hazırlığı:** sentetik verili güvenli statik çıktı, geçici HTTPS adresine uygun yapı. Hesap mülkiyeti/erişimi netleşince P24 yayınlanır. Mevcut domainin gelmesi beklenmez.
6. **Devir provası:** ikinci temiz yerel kurulum, migration, fotoğraf/PDF yedeği ve geri yükleme. Kişisel browser/CLI oturumu gerekmemeli.

İlk hedefler tamamlanırsa galeri, sağlayıcı testleri, bildirim kuyruğu ve kalan mobil/erişim testleri yapılabilir. Ücretsiz statik hosting gerçek backend/depolama/PDF/AI sisteminin ücretsiz ve hazır olduğu anlamına gelmez.

## Bu akşam gerçek aktivasyonu bekleyenler

- SMS: Türk numarası satın alınana ve sağlayıcı kurulana kadar askıda.
- WhatsApp/e-posta: müşteri hattı/hesap/gönderen uygunluğu sağlanana kadar test sağlayıcısı.
- AI: müşteri hesabı, API erişimi ve limitler sağlanana kadar test sağlayıcısı.
- Belgeler ve nihai içerik: onaylı dosyalar gelene kadar modüler taslak.
- Mevcut domain: erişim geldiğinde geçici adresten geçiş.

Bir arayüzdeki “başarılı” etiketi backend kaydı, AI sonucu, PDF üretimi veya mesaj tesliminin kanıtı değildir. Her iş gerçek çıktısıyla ayrı doğrulanır.
