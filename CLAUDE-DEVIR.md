# Claude / tasarımcı agentine güncel görev

Bu depodaki README, ROADMAP ve BEKLEYEN-GIRDILER belgelerini oku. Proje sahibi A yönünü seçti: koyu/sinematik tasarımı koru. Üç yeni demo üretme.

Amaç: eksik müşteri bilgileri gelmeden başlanabilir işleri ilerletmek. Logo/ürün/garanti/telefon/domain eksikliği çekirdek tasarımı ve backend hazırlığını durdurmasın. Bu belge bir plan deposudur; ayrı uygulama kodunun varlığını veya gerçek servis bağlantılarını varsayma.

## İşletme ve akış

Nimotech Performance; Türkiye/Türkçe/TL, Europe/Istanbul. Pazartesi–cumartesi 09.00–19.00, pazar kapalı. PPF seçenekleri yalnız mat/şeffaf. Sabit fiyat veya checkout yok. Fotoğraf, marka/model/model yılı, ad, telefon ve e-posta ile talep; not isteğe bağlı. Önce talep, sonra personelin değerlendirdiği AI önizleme ve kişisel PDF; randevu personelce kesinleşir.

5 yıl garanti bildirildi; kapsam/belge/istisnalar henüz yok. Kendi ürün markası bildirildi; teknik belge gelmeden özellik icat etme. AI önizlemesi temsili görünüm olarak etiketlenecek. Aynı gün dönüş için kesin koşullar netleşmeden süre garantisi verme.

## Senden beklenenler

1. A müşteri sitesi/panel/shared ve kullanılan vendor/font/lisanslar ile yalnız uygun örnek görsellerden izole devir paketi hazırla. Yerel mutlak dosya yollarını ve özel dosyaları public depoya koyma. Orijinal plakalı fotoğrafları, seçilmeyen adayları ve gizli yapılandırmaları dışarıda tut.
2. Mevcut durumda çalışan ve demo olan işlevleri listele. localStorage verisini gerçek kalıcı kayıt veya güvenli admin erişimi olarak sunma.
3. Form ve panelin mobil/masaüstü, boş/hata/yükleniyor/başarı durumlarını tamamla.
4. Ürün/garanti/işlem/iletişim alanlarını merkezi veriden güncellenebilir kur. Gerçek içerik gelince sayfa baştan yapılmasın.
5. Panel liste/detay/not/durum/önizleme/teklif/galeri ekranlarını ortak API sözleşmesine hazırla. Backend alanları manager ile birlikte kesinleşecek.
6. Kişisel PDF için altı bölümlü şablon hazırla: kapak; araç karşılaştırması; uygulama planı; ürün/kalite; garanti/belgeler; fiyat/sonraki adım. Hayali sertifika veya QR ekleme.
7. Ücretsiz geçici hosting için yalnız güvenli yayımlanabilir çıktıyı hazırla. Domain zaten var, erişimi sonradan gelecek. Mevcut domaini bekleme; P24 ayrı yayın adımıdır.
8. SMS'i gerçek bağlantı olarak çalıştırma: Türk numarası henüz alınmadı, P25 askıda. Diğer bot/istek korumaları devam eder.
9. Kişisel/VELIOFLOW hesaplarına, mevcut browser/CLI girişlerine veya sabit servis anahtarına bağımlılık ekleme. Üretim için müşteri/ayrı proje mülkiyeti ve taşınabilir yapı zorunlu.
10. Manager ile dosya/dal sınırlarını belirle; migration/erişim/sağlayıcı dosyalarında çakışan değişiklik yapma. Diğer agentin çalışmasını silme.

Backend paketi: kurulum/migration, gerçek erişim, kalıcı kayıt, özel medya, PDF motoru, sağlayıcı adapterleri, kuyruk, bot sınırları, yedek ve devir testleri. Gerekirse görevler açıkça yeniden atanır; sorumlu sütunları henüz GitHub kullanıcı ataması değildir.

## Teslim raporu

Dosya/dal/commit; yerel çalıştırma; çalışan gerçek çıktı; testler; test edilmeyenler; kalan demo/sahte sağlayıcılar; eksik müşteri girdileri; hesap bağımlılıkları ve devir tarifi. Ücretli servis açma, gerçek mesaj gönderme veya domain/DNS değişikliğini görevin yapılmış varsayımına ekleme.

Public issue/yorumlara gizli anahtar, özel medya veya kişisel iletişim verisi yazma. Uygulama kaynağını bu plan deposuna yüklemek ayrıca istenmedikçe kapsamda değildir.
