# Tüm yapılacaklar

## Güncel sorumluluk kararı — bütün uygulama Claude’da

31 Ekim 2026: Proje sahibi tüm uygulamayı Claude'a devretti. Site/panelin yanında sunucu/backend, veri tabanı, personel girişi/yetkileri, özel dosya deposu, AI, WhatsApp/e-posta, PDF, ücretsiz geçici hosting, test ve teslim işleri de Claude'un sorumluluğundadır. Codex manager koordinasyon, rapor inceleme ve sonuç doğrulamada kalır; paralel uygulama kodu geliştirmez. Claude rutin teknik kararlar veya backend işleri için Codex'in uygulamasını beklemez.

Eksik bilgi/hesap veya araç erişimi yalnız ilgili adımı bekletir. Claude engeli, gereken tek girdiyi ve buna rağmen ilerlettiği işi açıklar. Bu devir, tüm bağlantıların hazır olduğu veya tüm işlerin aynı akşam biteceği iddiası değildir. SMS askısı, hesap bağımsızlığı ve geçici Higgsfield API istisnası sürer. Eski issue gövdelerindeki rol ayrımı güncel iş dağılımı değildir; bu karar ve güncel görev belgeleri önceliklidir. Bu bir GitHub kullanıcı daveti/assignee ataması değildir.

Durumlar başlangıç planıdır; tamamlanma iddiası yoktur. Eksik girdi tüm işi durdurmaz.

| ID | İş | Durum | Uygulama sorumlusu |
|---|---|---|---|
| [P01](#p01) | Kaynak devri | HAZIR | Claude |
| [P02](#p02) | Seçilen tasarımı sabitleme | HAZIR | Claude |
| [P03](#p03) | Modüler içerik | KISMEN_BEKLIYOR | Claude |
| [P04](#p04) | Servis sözleşmesi | HAZIR | Claude |
| [P05](#p05) | Ayrı kurulum/veri | HAZIR | Claude |
| [P06](#p06) | Gerçek admin yetkisi | HAZIR | Claude |
| [P07](#p07) | Kalıcı talepler | HAZIR | Claude |
| [P08](#p08) | Özel fotoğraf deposu | HAZIR | Claude |
| [P09](#p09) | Bot/kötüye kullanım | KISMEN_BEKLIYOR | Claude |
| [P10](#p10) | Personel paneli bağlantısı | HAZIR | Claude |
| [P11](#p11) | Galeri | KISMEN_BEKLIYOR | Claude |
| [P12](#p12) | AI iş akışı | KISMEN_BEKLIYOR | Claude |
| [P13](#p13) | Teklif verisi | HAZIR | Claude |
| [P14](#p14) | Gerçek PDF çıktısı | KISMEN_BEKLIYOR | Claude |
| [P15](#p15) | Bildirim kuyruğu | HAZIR | Claude |
| [P16](#p16) | E-posta bağlantısı | KISMEN_BEKLIYOR | Claude |
| [P17](#p17) | WhatsApp bağlantısı | KISMEN_BEKLIYOR | Claude |
| [P18](#p18) | Ürün/garanti/işlem içeriği | BEKLIYOR | Claude |
| [P19](#p19) | QR | BEKLIYOR | Claude |
| [P20](#p20) | Domain/HTTPS/yayın | KISMEN_BEKLIYOR | Claude |
| [P21](#p21) | Kalite/kabul | HAZIR | Claude |
| [P22](#p22) | Devir provası | KISMEN_BEKLIYOR | Claude |
| [P23](#p23) | Doküman/teslim | HAZIR | Claude |
| [P24](#p24) | Ücretsiz geçici hosting ve sağlayıcı alt alan adı | KISMEN_BEKLIYOR | Claude |
| [P25](#p25) | SMS doğrulama — Türk numarası alınıncaya kadar askıda | BEKLIYOR | Claude |

## P01
### Kaynak devri

**Durum:** HAZIR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Claude A kaynak paketi ve bağımlılıkları, çalıştırma komutu, kullanılan paketler/varlık lisansları, mevcut çalışan/dummy özellik listesi; hesap erişimi olmadan açılır

**Şimdi yapılacak:** A tasarımının gerekli bağımlılıklarıyla izole kaynak paketini ve lisans envanterini hazırla. İlk değişiklikten önce arşiv ve Git başlangıç kaydı al.

**Eksik / sınır:** Seçilen A yönü ve statik HTML/CSS/JS bilgisi aktarıldı; kaynak paketi ve işlevler uygulayıcı tarafından incelenecek.

**Tam kapanış / bağımlılık:** Kaynak teslimi ve bağımlılık kontrolü.

## P02
### Seçilen tasarımı sabitleme

**Durum:** HAZIR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Tek site/panel yönü, mobil/masaüstü, eksik/hata/boş/yükleniyor durumları

**Şimdi yapılacak:** Seçilen A görsel yönünü koruyarak mobil/masaüstü, boş, hata, yükleniyor ve başarı durumlarını tamamla.

**Eksik / sınır:** Sonradan gelecek logo ve gerçek görseller için değiştirilebilir alanlar kullan.

**Tam kapanış / bağımlılık:** Onaylı son içerikler.

## P03
### Modüler içerik

**Durum:** KISMEN_BEKLIYOR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Logo, ürün, 5 yıl garanti, işlem listesi, foto/video, adres/saat alanları sonradan yönetilebilir

**Şimdi yapılacak:** Logo, ürün, garanti, adımlar ve iletişim için merkezi içerik alanlarını oluştur; boş alanları zarifçe gizle veya taslak olarak işaretle.

**Eksik / sınır:** Onaylı logo/ticari unvan, ürün adı/teknik föy, garanti belgesi, işlem listesi ve iletişim bilgileri eksik.

**Tam kapanış / bağımlılık:** İlgili gerçek içeriklerin müşteri onayı.

## P04
### Servis sözleşmesi

**Durum:** HAZIR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Form/panel/PDF/AI/bildirim alanları ve durumları ortak; hangi agent hangi dosyayı değiştirir net

**Şimdi yapılacak:** Form, panel, talep, dosya, teklif, AI ve bildirim durumları için alanlar/yanıtlar/hatalar içeren servis sözleşmesi yaz.

**Eksik / sınır:** Kaynak incelemesine bağlı teknik kararlar açıkça öneri olarak tutulacak.

**Tam kapanış / bağımlılık:** Agentler arası sözleşme onayı.

## P05
### Ayrı kurulum/veri

**Durum:** HAZIR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Nimotech'e ayrılmış veri deposu; migration, ayar örneği, kurulum komutu, proje sahibinin hesabı olmadan tekrar kurulum

**Şimdi yapılacak:** Müşteriye ayrı veri deposu, migration, boş ayar örneği ve tekrar kurulabilir çalışma ortamı hazırla.

**Eksik / sınır:** Yerel şema hazırlığı uygulamanın bağlandığı anlamına gelmez.

**Tam kapanış / bağımlılık:** Gerçek sunucu hesabı ve ortam kararı, üretim aşamasında.

## P06
### Gerçek admin yetkisi

**Durum:** HAZIR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Davetli personel erişimi, güvenli oturum, gerekli MFA, yetki kontrolü; anonim özel veri okuyamaz

**Şimdi yapılacak:** Davetli personel, rol kontrolleri, oturum ve MFA akışını yerelde sentetik kullanıcılarla doğrula.

**Eksik / sınır:** Gerçek personel sayısı ve erişim listesi bekleniyor.

**Tam kapanış / bağımlılık:** Müşterinin yetkili personel listesi.

## P07
### Kalıcı talepler

**Durum:** HAZIR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Zorunlu alanlar sunucuda denetlenir; kayıt yenilemeden sonra kalır; panelde doğru görünür; kesin randevu oluşmaz

**Şimdi yapılacak:** Zorunlu alanlar, talep numarası, kalıcı kayıt ve panel liste/detay akışını örnek veriyle bağla.

**Eksik / sınır:** Fotoğraf, marka/model/yıl, ad, telefon, e-posta ve mat/şeffaf seçimi gerekir.

**Tam kapanış / bağımlılık:** P04/P05/P06/P08 teknik bağımlılıkları.

## P08
### Özel fotoğraf deposu

**Durum:** HAZIR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Format/boyut/piksel kontrolü, metadata temizliği, anonim erişim engeli; yalnız yetkili erişim/paylaşım

**Şimdi yapılacak:** Özel dosya deposu, dosya türü/boyutu/piksel kontrolü, metadata temizliği ve yetkili erişimi uygula.

**Eksik / sınır:** Gerçek müşteri fotoğrafları public depoya veya genel demo galerisine konmayacak.

**Tam kapanış / bağımlılık:** Üretimde saklama/silme süresi ve depolama hesabı.

## P09
### Bot/kötüye kullanım

**Durum:** KISMEN_BEKLIYOR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Sunucu doğrulama, oran sınırı, mükerrer kayıt ve dosya kontrolü; sağlayıcılı bot kontrolü değiştirilebilir

**Şimdi yapılacak:** Sunucu doğrulama, istek sınırı, dosya kontrolü ve mükerrer talep korumasını SMS olmadan uygula.

**Eksik / sınır:** SMS ayrı P25 görevidir ve askıdadır. Dış bot servisi kullanılırsa müşteri hesabıyla ayrıca bağlanır.

**Tam kapanış / bağımlılık:** Dış bot servisi kararı; SMS çekirdeği engellemez.

## P10
### Personel paneli bağlantısı

**Durum:** HAZIR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Liste/detay/arama/durum/not/teklif ekranları gerçek API sonuçlarını gösterir; hata gizlenmez

**Şimdi yapılacak:** Panel listesi/detayı, arama, durum, not ve teklif ekranlarını gerçek API adapterine bağla.

**Eksik / sınır:** Demo localStorage kalıcı gerçek backend sayılmaz.

**Tam kapanış / bağımlılık:** P04/P07 sözleşmesi ve kalıcı veri.

## P11
### Galeri

**Durum:** KISMEN_BEKLIYOR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Yetkili yükler/sıralar/kaldırır; yayınlanan içerik siteye yansır; talep fotoğrafları otomatik yayımlanmaz

**Şimdi yapılacak:** Yetkili ekleme/sıralama/kaldırma/yayınlama akışını örnek ve yayın hakkı olan görsellerle kur.

**Eksik / sınır:** Gerçek uygulama görselleri henüz teslim edilmedi. Özel talep fotoğrafları otomatik yayımlanmaz.

**Tam kapanış / bağımlılık:** Gerçek görseller ve yayımlama onayı.

## P12
### AI iş akışı

**Durum:** KISMEN_BEKLIYOR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Personel başlatır; maliyet sınırı, tek iş/tekrar kontrolü, başarısız/belirsiz iş takibi; sonuç personelce onaylanır

**Şimdi yapılacak:** Higgsfield API adapteri, sunucu secret yapılandırması, iş durumları, maliyet sınırı ve tekrar/belirsiz sonuç kontrollerini hazırla. Proje sahibinin Higgsfield API anahtarı geliştirmede geçici kullanılabilir; mevcut izin anahtarın alındığı veya bağlantının kurulduğu anlamına gelmez.

**Eksik / sınır:** Gerçek resmî API erişimi, ücretlendirme ve üretim/tekrar sınırı henüz doğrulanmadı. Anahtar public kod/issue/sohbet/loga yazılmaz; kişisel browser/CLI oturumu kullanılmaz. Diğer hesaplar için eski mülkiyet kuralı sürer.

**Tam kapanış / bağımlılık:** Geliştirme: güvenli sunucu secret girişi, API erişimi ve limitlerin doğrulanması. Teslim: müşteri anahtarıyla değiştirme ve eski anahtar olmadan çalışma testi; nihai müşteri hesabı gelene kadar adapter/test işleri beklemez.

## P13
### Teklif verisi

**Durum:** HAZIR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Personelin tutarı/kapsamı, sürüm/onay, geçerlilik/koşul alanları; AI fiyat uyduramaz

**Şimdi yapılacak:** Personelin tutar/kapsam girdiği, sürümlenen ve onay durumları ayrılmış teklif kaydını oluştur.

**Eksik / sınır:** Sabit fiyat yok; tutarı AI belirlemez.

**Tam kapanış / bağımlılık:** Geçerlilik, vergi ve ödeme koşulları gerçek sürümde müşteriden gelecek.

## P14
### Gerçek PDF çıktısı

**Durum:** KISMEN_BEKLIYOR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Sunucu şablonu/görsellerden indirilebilir, Türkçe karakterli, taşmayan kişisel PDF; örnek belge yer tutucuları açık; özel erişim

**Şimdi yapılacak:** Örnek bilgilerle gerçek indirilebilir PDF motorunu ve görsel şablonu kur; Türkçe karakter ve sayfa taşmasını kontrol et.

**Eksik / sınır:** Logo, ürün, hazırlık işlemleri ve garanti belgeleri eksik; bu kısımlar sonradan doldurulur.

**Tam kapanış / bağımlılık:** Gerçek içerik gelince son PDF içerik kabulü.

## P15
### Bildirim kuyruğu

**Durum:** HAZIR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Kayıttan sonra işler; tek talep için istenmeyen çift bildirim yok; hata/tekrar deneme kaydı

**Şimdi yapılacak:** Talep kaydı sonrası bildirim kuyruğu, hatalar, tekrar deneme ve mükerrer gönderim kontrolünü sahte sağlayıcıyla doğrula.

**Eksik / sınır:** Gerçek e-posta/WhatsApp hesabı olmadan iş kuyruğu test edilebilir.

**Tam kapanış / bağımlılık:** Gerçek gönderim P16/P17 ile ayrıca açılır.

## P16
### E-posta bağlantısı

**Durum:** KISMEN_BEKLIYOR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Müşteri alan adı ve göndereni; teslim durumları doğru; başka adrese yanlış içerik gönderilmez

**Şimdi yapılacak:** E-posta adapterini, şablonları ve hata/durum takibini test sağlayıcısıyla hazırla.

**Eksik / sınır:** Bildirim adresi, gönderen ve müşteri hesabı henüz yok.

**Tam kapanış / bağımlılık:** Müşteri e-posta hesabı, gönderen/domain doğrulaması ve gerçek test.

## P17
### WhatsApp bağlantısı

**Durum:** KISMEN_BEKLIYOR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Müşterinin hattı, aynı telefondaki Business kullanımını koruyacak resmî yöntem doğrulanır; bildirim alıcısı net

**Şimdi yapılacak:** WhatsApp bildirim ve paylaşım ekranlarını/adapter sözleşmesini test sağlayıcısıyla hazırla.

**Eksik / sınır:** Hat bilgisi ve aynı telefondaki WhatsApp Business kullanımını koruyacak resmî yöntem doğrulanacak.

**Tam kapanış / bağımlılık:** Müşterinin WhatsApp hattı/hesabı ve sağlayıcı uygunluğu.

## P18
### Ürün/garanti/işlem içeriği

**Durum:** BEKLIYOR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Onaylı ürün ve garanti belgeleri, dahil/ek hizmetler, gerçek görseller; hayali iddia yok

**Şimdi yapılacak:** İçerik modelini ve belge/görsel alanlarını hazır tut; gelen her içerik için onay ve sürüm kaydı düşün.

**Eksik / sınır:** Logo, ürün teknik/lisans belgeleri, garanti kapsamı, hazırlık/ek hizmetler ve gerçek görseller bekleniyor.

**Tam kapanış / bağımlılık:** Müşteri dosyalarının teslimi; adımlar için bildirilen gün 2 Kasım 2026, teslim tarihi değil.

## P19
### QR

**Durum:** BEKLIYOR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Ürün belgesi mi araç garantisi mi seçilir; gerçek hedefe açılır; özel veri herkese açılmaz

**Şimdi yapılacak:** QR hedefi türünü belirleyecek alanları ve doğrulama akışı taslağını hazırla.

**Eksik / sınır:** Ürün belgesi mi araca özel garanti mi açacağı kararlaştırılmadı. Sahte QR üretilmez.

**Tam kapanış / bağımlılık:** Gerçek belge/hedef URL ve erişim kararı.

## P20
### Domain/HTTPS/yayın

**Durum:** KISMEN_BEKLIYOR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Müşteri mülkiyetindeki hosting ve domain; ortam ayarları, yedek/geri alma; domain değişimi uygulama kodu istemez

**Şimdi yapılacak:** URL/callback/webhook yapılandırmasını taşınabilir hazırla; geçici adresten mevcut müşteri domainine geçişi dokümante et.

**Eksik / sınır:** Domain mevcut; yeni domain satın alma görevi yok. Domain/DNS erişimi sonra sağlanacak. İlk staging P24 ile yapılabilir.

**Tam kapanış / bağımlılık:** Mevcut müşteri domaininin erişimi ve son yayın kabulü.

## P21
### Kalite/kabul

**Durum:** HAZIR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Form→kayıt→panel→onaylı PDF; farklı cihaz; yetkisiz erişim; bozuk dosya; tekrar tıklama; sağlayıcı hatası; mobil kontrol

**Şimdi yapılacak:** Formdan panel/PDF akışına, yetkisiz erişime, hatalı dosyaya ve tekrar tıklamaya anlamlı testler yaz; mobil/masaüstü kontrol et.

**Eksik / sınır:** Her küçük iş doğrulanır; sahte sağlayıcı sonucu gerçek teslim/AI kanıtı değildir.

**Tam kapanış / bağımlılık:** Tam kabul gerçek entegrasyonlar sonrası.

## P22
### Devir provası

**Durum:** KISMEN_BEKLIYOR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Temiz ortamda kurulum + veri/dosya geri yükleme + yeni müşteri anahtarları; proje sahibinin oturumu kapalıyken çalışma

**Şimdi yapılacak:** İkinci temiz yerel ortamda migration, veri/dosya yedeği ve geri yükleme provası yap.

**Eksik / sınır:** Yerel prova şimdi yapılabilir. Müşteri hesabı ve sunucusundaki nihai devir ayrıca gerekir.

**Tam kapanış / bağımlılık:** Müşteri ortamı ve gerçek hesaplarla son kabul.

## P23
### Doküman/teslim

**Durum:** HAZIR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Kaynak Git geçmişi, bağımlılıklar/lisanslar, kurulum/işletim/yedek dokümanı, personel kullanım kılavuzu, eksiklerin listesi

**Şimdi yapılacak:** Kaynak envanteri, Git geçmişi, paket/lisans listesi, kurulum/işletim/yedek ve personel kılavuzunu tut.

**Eksik / sınır:** Gizli anahtarlar, özel dosyalar ve kişisel bilgisayar yolları public belgelerde bulunmayacak.

**Tam kapanış / bağımlılık:** Her işin gerçek test ve eksik durum raporu.

## P24
### Ücretsiz geçici hosting ve sağlayıcı alt alan adı

**Durum:** KISMEN_BEKLIYOR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Sentetik verili A tasarımı ücretsiz planın geçici HTTPS adresinde açılır; eksik backend servisleri açıkça belirtilir; deployment/geri alma/taşıma adımları belgelenir.

**Şimdi yapılacak:** Deploy edilecek güvenli statik çıktı paketini, yol/yönlendirme kontrollerini ve deployment tarifini hazırla. Mevcut müşteri domainini bekleme.

**Eksik / sınır:** Sağlayıcı hesabının mülkiyeti ve yetkili erişimi netleşmeli. Ücretsiz planın sınırları kontrol edilecek. Site kaynakları ve yayımlanacak güvenli paket henüz manager tarafından incelenmedi.

**Tam kapanış / bağımlılık:** Müşteri mülkiyetinde ya da açıkça ayrı proje mülkiyetinde hosting hesabı erişimi ve doğrulanmış yayın paketi. Kişisel/VELIOFLOW hesabı kendiliğinden seçilmez.

## P25
### SMS doğrulama — Türk numarası alınıncaya kadar askıda

**Durum:** BEKLIYOR · **Uygulama sorumlusu:** Claude

**Kabul ölçütü:** Numara satın alındıktan ve sağlayıcı erişimi doğrulandıktan sonra OTP gönderim/doğrulama, süre, deneme sınırı, yeniden gönderim aralığı ve maliyet limiti test edilir.

**Şimdi yapılacak:** OTP arayüzü ve sağlayıcı sözleşmesini sahte göndericiyle tasarlamak mümkün; ana form ve bot koruması SMS beklemeden geliştirilecek.

**Eksik / sınır:** Türk numarası henüz satın alınmadı. Gerçek SMS sağlayıcısı/hesabı ve maliyet onayı yok.

**Tam kapanış / bağımlılık:** Proje sahibinin numaranın alındığını bildirmesi, müşteri mülkiyetindeki sağlayıcı kurulumu ve gerekli gönderici uygunluklarının doğrulanması. Numara alımı tek başına çalışan OTP demek değildir.
