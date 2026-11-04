# Yumu Drop — Gizlilik Politikası

[English](privacy-policy.md) · [Verilerini silme](#silme)

Son güncelleme: 4 Kasım 2026

Yumu Drop, **YEETS! Games** markasıyla geliştirilir. Gizlilik ve veri silme
başvuruları için [yeetsgames45@gmail.com](mailto:yeetsgames45@gmail.com)
adresine ulaşabilirsin.

> Kapalı test sürümü. Veri sorumlusunun tam hukuki kimliği, KVKK kapsamındaki
> işleme şartları ve yurt dışı aktarım mekanizması ile hedef yaş grubu üretim
> yayını öncesinde doğrulanıp iki dilde bu metne işlenecektir.

## Kısaca

Yumu Drop'u internet bağlantısı ve hesap olmadan oynayabilirsin. TESTERLAR
sıralamasına katılmak isteğe bağlıdır. **KATIL** seçeneğini kullandığında
oyun senin için anonim bir hesap oluşturur ve skorun yurt dışındaki bir
sunucuda saklanır. Oyunda reklam veya analitik bulunmaz ve verilerini
satmayız.

## Cihazında kalan bilgiler

Ayarların, görev ve kariyer ilerlemen, seçtiğin görünüm ve tema ile cihazdaki
**en iyi 10 turun** ayrıntıları (puan, cihaz tarihi, görünüm, aşama ve en iyi
seri) yerel olarak saklanır. Çevrimiçi sıralama bu geçmiş listeyi göndermez.
Katılırsan yenileme anahtarın, takma ad seçimin ve gönderilmeyi bekleyen en
iyi skor da cihazında saklanır. Uygulamayı kaldırmak veya verilerini
temizlemek yerel kayıtları kaldırır. Sunucudaki hesap için [silme adımlarını
izle](#silme).

## TESTERLAR sıralamasına katıldığında

**Rekorlar → TESTERLAR → KATIL** ile oyun HTTPS üzerinden Supabase'e
bağlanır. Hesap rastgele oluşturulan benzersiz bir kimlikle tanınır. Hesabı
oluşturmak veya sıralamada yer almak için gerçek ad, e-posta, telefon veya
konum istenmez. Takma ad oyun içindeki hazır kelime listelerinden seçilir.

- Hesap ve oturum bilgileri giriş, oturum yenileme ve hizmet güvenliği için
  kullanılır. Supabase bağlantı sırasında IP adresini ve istemcinin teknik
  bilgisini işleyebilir. Oyun IP adresinden konum çıkarmaz.
- Oyun, katılımdan sonra tamamlanan uygun Arcade turlarının skorunu, rastgele
  tur kimliğini, sezonu, isabet sayısını ve süresini gönderir. İsabet sayısı ve
  süre yalnızca aralık kontrolünde kullanılır; bunlar sıralama veritabanına
  yazılmaz.
- Sunucu hesap başına en iyi Arcade skorunu, skorun ulaşıldığı ve son
  gönderildiği zamanları, tur kimliğini, sezonu, Yumu numarasını ve takma
  adın liste seçimlerini saklar. Skor
  gönderimi ve sıralama erişimi oturumla ilişkilendirilir.
- Sıralamaya katılan diğer oyunculara takma ad, Yumu numarası, puan, sıra ve
  skorun UTC günü sunulabilir. Hesap kimliği, oturum anahtarları ve IP adresi
  sıralama listesine verilmez.

**PAYLAŞIMI DURDUR** yeni skor gönderimini kapatır. Mevcut hesabı ve
sıralama satırını silmek için **VERİLERİMİ SİL** seçeneğini kullan.

## İşleme amaçları ve yurt dışı aktarım

Veriler sıralama hizmetini sunmak, oturumu yönetmek, hizmeti kötüye kullanıma
karşı korumak ve veri taleplerini yanıtlamak için işlenir. Katıldıktan sonra
bu veriler, oyunun gönderdiği ağ istekleriyle toplanır. Destek başvurusunda
ilettiğin bilgiler e-postayla alınır ve başvurunu değerlendirmek ve
sonucunu bildirmek için kullanılır.

Sıralama için hizmet sağlayıcımız Supabase Inc.'dir. Projenin veritabanı
İsveç'in Stockholm bölgesindedir. Türkiye'den bu hizmete gönderilen
sıralama ve oturum bilgileri yurt dışında işlenir. Bu aktarım yalnızca
TESTERLAR sıralamasına katılmayı seçtiğinde ve bu bilgilendirmeye
ulaşabileceğin bir noktadan sonra gerçekleşir. KVKK madde 5 ve madde 9
kapsamındaki hukuki nitelendirme, üretim yayını öncesinde uzman görüşüyle
kesinleştirilip bu metne işlenecektir.

## Saklama süreleri

| Kayıt | Saklama ve silme |
| --- | --- |
| Aktif hesap, skor ve takma ad | Başarılı hesap silme işlemine veya sezon sonu temizliğine kadar. Test sezonu kapatıldıktan sonra bu kayıtlar en geç 30 gün içinde silinir. |
| Oturum, yenileme anahtarları ve oturuma bağlı IP / istemci bilgileri | Hesaba bağlıdır ve hesap silinene kadar kalabilir. Hesabın silinmesi ilişkili oturum kayıtlarını da kapsar. |
| API istek günlükleri (IP adresi dahil) | 1 gün. |
| Auth denetim kayıtları (IP adresi dahil) | Projenin veritabanına yazılmaz. Yalnızca sağlayıcının günlük sisteminde tutulur; 1 saat. |
| Veritabanı yedekleri | Sağlayıcının otomatik veritabanı yedeği bulunmaz ve ayrıca yedek alınmaz. |
| Silme ve destek başvuruları (e-posta) | Başvuru sonuçlandıktan sonra e-posta silinir. Başvurunun tarihi, Yumu numarası ve sonucu kayıt amacıyla saklanır. |

Plan veya sağlayıcı değişirse yukarıdaki süreler değişebilir; bu durumda
politika, değişiklik uygulanmadan önce güncellenir.

<a id="silme"></a>

## Verilerini silme

**Oyunda:** Rekorlar → TESTERLAR → **VERİLERİMİ SİL** yolunu izle ve
ikinci dokunuşla onayla. İşlem başarılı olursa anonim hesabın ve ilişkili
aktif skor, takma ad ve oturum kayıtların silinir. Yerel rekorlarını ve
ayarlarını kaldırmak için uygulama verilerini temizleyebilir veya oyunu
kaldırabilirsin.

**Oyun dışında:** [Yumu Drop veri silme başvurusu gönder](mailto:yeetsgames45@gmail.com?subject=Yumu%20Drop%20veri%20silme).
Başvuruda Yumu numaranı yaz. Yumu numarası, takma ad ve skor diğer
oyuncuların da görebildiği bilgilerdir ve tek başına hesap sahipliğini
kanıtlamaz. Bu nedenle başvuru şu kurala göre değerlendirilir:

- Hesap, başvuru tarihinden önceki **7 gün** içinde sunucuya hiç
  bağlanmamışsa artık hiçbir cihazda kullanılmadığı kabul edilir. Hesap ve
  ilişkili skor, takma ad ve oturum kayıtları başvurudan itibaren en geç
  30 gün içinde silinir.
- Hesap son 7 gün içinde bağlanmışsa hâlâ bir cihazda kullanılıyordur. Bu
  durumda silme, o cihazdaki oyunda **VERİLERİMİ SİL** ile yapılmalıdır;
  hesap başvuru üzerine silinmez. Cihazına artık erişemiyorsan bize yaz;
  durumunu birlikte değerlendirip başka bir doğrulama yolu arayalım.

Başvurunun sonucu sana e-postayla bildirilir. Skor göndermemiş hesapların
Yumu numarası yoktur; bu hesaplar sezon sonu temizliğinde silinir.
E-postayla oturum anahtarı veya parola gönderme.

## Çocuklar ve ebeveynler

Oyunda reklam, analitik, sohbet veya serbest metin alanı bulunmaz.
Çevrimiçi sıralama isteğe bağlıdır, anonim hesap kullanır ve gerçek ad,
e-posta, telefon veya konum istemez. Ebeveynler veya yasal temsilciler
gizlilik sorularını ve silme başvurularını yukarıdaki iletişim adresine
iletebilir.

## Hakların ve başvuru yolların

Geçerli olduğu ölçüde verilerin işlenip işlenmediğini öğrenmek, işleme ve
aktarım hakkında bilgi istemek, düzeltme veya silme talep etmek ve işlemeye
itiraz etmek için iletişim adresine başvurabilirsin. KVKK kapsamındaki
haklar ve başvuru yolları [Kişisel Verileri Koruma Kurumu](https://www.kvkk.gov.tr/)
sitesinde açıklanır. Geçerli olduğunda yetkili veri koruma otoritesine
şikâyette bulunabilirsin.

## Değişiklikler

Bu politika değiştiğinde sayfanın başındaki "Son güncelleme" tarihi
yenilenir. Sunucuya gönderilen veriler değişirse değişiklik, oyunun yeni
sürümü yayınlanmadan önce bu metne işlenir.
