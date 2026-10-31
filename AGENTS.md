# Agent çalışma kuralları

## Güncel istisna — geçici Higgsfield API erişimi

31 Ekim 2026: Proje sahibi, geliştirme aşamasında kendi Higgsfield API anahtarının geçici kullanımına izin verdi. Bu yalnız Higgsfield API için istisnadır; diğer kişisel/VELIOFLOW hesaplarına bağlantı izni değildir. Anahtar sunucu tarafı secret yapılandırmasında tutulur; browser kodu, public depo/issue, sohbet, log veya PDF içine yazılmaz. Kişisel browser/CLI oturumu kullanılmaz.

Hesap/anahtar sağlayıcı adapterinden ve uygulama kodundan ayrılacak. Teslimde müşterinin anahtarıyla değiştirilecek ve uygulamanın eski anahtar olmadan çalıştığı doğrulanacak. Resmî API erişimi, ücretlendirme ve üretim/tekrar limitleri ayrıca kontrol edilecek; bu izin sınırsız harcama veya otomatik yeniden üretim anlamına gelmez. Bu kayıtta anahtar alınmadı, bağlantı kurulmadı ve ücretli üretim başlatılmadı.

Bu depo public plan ve görev kaydıdır; uygulama kodu değildir. Önce README, ROADMAP, BEKLEYEN-GIRDILER ve CLAUDE-DEVIR belgelerini oku.

- Seçilen A tasarımını koru. Eksik girdi çekirdek geliştirmeyi durdurmaz; her görevde şimdi yapılacak ve bekleyen kısmı ayır.
- SMS doğrulama Türk numarası alınana kadar askıda. SMS olmadan dosya/istek/bot denetimleri yapılır.
- Mevcut müşteri domaini beklenmeden ücretsiz geçici hosting hazırlığı yapılır. Hesap mülkiyeti ve erişimi yokken yayın yapıldı denmez.
- Kişisel/VELIOFLOW hesaplarını üretim bağımlılığı yapma. Gizli anahtar, özel fotoğraf, müşteri kaydı veya yerel kişisel dosya yolunu public commit/issue içine koyma.
- Gerçek mesaj, ücretli AI/servis, domain/DNS veya erişim değişikliği için ilgili açık kullanıcı talimatını kontrol et. Plan görevi otomatik harcama yetkisi değildir.
- Test sağlayıcısı, UI tıklaması ve gerçek başarılı işlem ayrı raporlanır. Doğrulanmayanı tamamlandı diye işaretleme.
- İzole dal ve belirli dosya sorumluluğu kullan. Diğer agentin değişikliklerini silme; force push veya geçmiş yeniden yazma yapma.
- Her görevde kabul ölçütü, gerçek test sonucu, eksik girdi ve devir etkisini güncelle.
- Aynı agentin öz kontrolünü bağımsız QA diye sunma.
