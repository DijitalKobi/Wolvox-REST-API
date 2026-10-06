# WolvoxApi

AKINSOFT Wolvox ERP için REST API. Cari, stok, sipariş, fatura, irsaliye, kasa, banka ve rapor verilerine e-ticaret
sitelerinin, pazaryeri entegrasyonlarının ve kurum içi uygulamaların güvenli, hızlı ve standart bir arayüzle erişmesini sağlar.

Bu depo ürün tanıtımı içindir; yazılımın kaynak kodu paylaşılmaz.

## Ürün hakkında

WolvoxApi, Wolvox ERP'nin geliştirici arayüzünü modern bir REST API olarak sunar. Uygulamalar ERP verisini JSON biçiminde
okur ve yazar; oturum yönetimi, önbellek, hata durumları ve güvenlik API tarafından üstlenilir. Ürün, ERP'nin bulunduğu
bilgisayara Windows servisi olarak kurulur ve Windows arayüzlü yönetim aracıyla yapılandırılır.

## Kimler için

**E-ticaret siteleri** — Sipariş, müşteri, stok ve fiyat bilgisini ERP ile otomatik olarak eşitlemek isteyen mağazalar.

**Entegrasyon ve yazılım firmaları** — Wolvox ERP kullanan müşterilerine pazaryeri, B2B portalı ya da mobil uygulama
bağlantısı geliştiren ekipler.

**Kurum içi uygulamalar** — Raporlama, panel ve iş akışı uygulamalarında ERP verisine standart bir arayüzle ulaşmak isteyen
işletmeler.

## Özellikler

### Kapsamlı ERP erişimi
Cari kartlar ve hareketler, stok kartları ve envanter, depolar, faturalar, irsaliyeler, siparişler, teklifler, kasa, banka,
çek ve senet, tanımlar ve raporlar tek bir arayüzden okunur.

### Kayıt oluşturma ve güncelleme
Cari ve adres kaydı, tahsilat ve ödeme hareketi, fatura, irsaliye, sipariş ve teklif oluşturma; iptal, kargo bilgisi
güncelleme, depolar arası transfer ve sayım girişi yapılabilir.

### Güvenli yazma
Yazma istekleri hiçbir koşulda kendiliğinden yeniden gönderilmez; mükerrer kayıt oluşmaz. Sonucu kesinleşmeyen bir işlem
açıkça bildirilir ve kontrol edilmesi gerektiği belirtilir.

### Yüksek performans
Okumalar önbellekten karşılanır, ERP oturumları yeniden kullanılır, büyük listeler sayfalı okunur. Yoğun kullanımda da
tutarlı yanıt süreleri sağlanır.

### Çoklu şirket, çalışma yılı ve şube
Her istek şirket, çalışma yılı ve şube belirtebilir; şubeli şirketlerde kayıtlar doğru şubeye yazılır.

### Güvenlik
API anahtarıyla kimlik doğrulama, izin verilen ağlar listesi, sertifikası kendiliğinden yenilenen HTTPS ve istek sınırı.
Parola ve benzeri gizli bilgiler hiçbir yanıtta yer almaz; yönetim işlemleri yalnızca kurulu bilgisayardan yapılabilir.

### Etkileşimli belgeler
Her uç, açıklamaları ve örnek istekleriyle Swagger ve Scalar arayüzlerinde belgelidir; istekler tarayıcıdan denenebilir.

### İzleme ve tanılama
Sağlık uçları, ölçüm sayaçları, ayrıntılı günlükler ve tek adımda hazırlanan tanı paketiyle sorunlar hızla tespit edilir.

### Windows yönetim aracı
Kurulum sihirbazı, ERP bağlantısı, servis yönetimi, günlük görüntüleme, gelişmiş ayarlar ve lisans işlemleri tek bir
uygulamada toplanır.

### Veritabanı uyumluluğu
Wolvox ERP'nin Firebird ve MS SQL Server ile çalışan kurulumlarıyla uyumludur.

## Erişilebilen veriler

**Cari** — Kartlar, bakiyeler, hareketler, adresler, kredi limitleri ve taksitler; cari ve adres oluşturma, tahsilat ve ödeme
hareketi.

**Stok ve depo** — Stok kartları, envanter, barkod, seri ve lot bakiyeleri, grup, renk, beden, birim, marka ve model
tanımları; depo bazında envanter, depolar arası transfer ve sayım.

**Satış ve satın alma belgeleri** — Fatura, irsaliye, sipariş ve teklif başlıkları ve satırları; oluşturma ve iptal.

**Finans** — Kasa ve banka hesapları, POS tanımları, bankalar arası transfer, çek ve senet girişi.

**Tanımlar** — Döviz ve kurlar, para birimleri, özel alan tanımları, genel ve e-Fatura ayarları, ülke, il ve ilçe listeleri.

**Raporlar** — Gün sonu raporu; cari hareket, fatura ve çek-senet analizleri; yönetici ve şube izleme panelleri.

**Şirket** — Kurulumdaki şirketler, çalışma yılları, şubeler ve şirket kartı bilgileri.

## Lisanslama

WolvoxApi, Dijitalkobi tarafından verilen lisansla çalışır. Lisans, kurulu bilgisayara, işletmenin vergi numarasına ve
AKINSOFT lisans numarasına bağlıdır. Süreli (yıllık) ve süresiz lisans seçenekleri vardır; yeni kurulum yedi gün deneme
olarak kullanılabilir.

## Çalışma ortamı

Windows 10, Windows 11 ya da Windows Server; ASP.NET Core 10 Runtime ve .NET 10 Desktop Runtime; AKINSOFT Wolvox ERP ve
geliştirici arayüzü erişimi.

## İletişim

Dijitalkobi E-Ticaret Yazılım Bilişim Reklam ve Danışmanlık Hizmetleri Sanayi ve Ticaret Limited Şirketi

Web: https://www.dijitalkobi.com.tr/

E-posta: kenan@dijitalkobi.com.tr

Ürün tanıtımı, fiyat ve lisans bilgisi için bizimle iletişime geçebilirsiniz.

## Yasal bilgi

WolvoxApi, Dijitalkobi tarafından bağımsız olarak geliştirilmiştir ve AKINSOFT ile bir ortaklık ya da onay ilişkisi içermez.
AKINSOFT ve Wolvox, sahiplerinin ticari markalarıdır. Yazılımın tüm hakları Dijitalkobi'ye aittir.
