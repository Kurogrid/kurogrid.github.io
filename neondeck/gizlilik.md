[English](privacy.md)

# NEONDECK Gizlilik Politikası

_Son güncelleme: 12.11.2026 (Firefox)_

NEONDECK, Firefox ve Chrome için yeni sekme sayfasını bir kontrol paneliyle değiştiren bir tarayıcı eklentisidir. Bu politika verilerine ne olduğunu açıklar. Kısaca: **NEONDECK'in sunucusu, hesap sistemi, analitiği ve reklamı yoktur. Verilerin tarayıcında kalır.**

## NEONDECK neyi saklar

Kurduğun her şey yalnızca kendi cihazında, tarayıcının yerel eklenti depolamasında (`storage.local`) tutulur:

- ayarlar (ad, dil, tema, görünüm seçenekleri, arama motorları)
- netlink'lerin (kayıtlı bağlantılar ve kategoriler)
- widget içerikleri: notlar, görevler, alışkanlıklar, dünya saati dilimleri, AI hızlı bağlantıları, Pomodoro sayaç durumu, hava durumu için seçtiğin şehir
- kısa süreli hava durumu önbelleği (15 dakikada bir yenilenir)

Bu veriler başka cihazlara eşitlenmez ve geliştiriciye asla gönderilmez. Eklentiyi kaldırmak ya da **Ayarlar → Veri → Varsayılanlara dön** düğmesi verileri siler.

## Ağ istekleri

NEONDECK yalnızca tek bir servise, yalnızca **Hava durumu** widget'ını açıp bir şehir seçersen bağlanır:

- **Open-Meteo** (`api.open-meteo.com`, `geocoding-api.open-meteo.com`): konum ararken yazdığın şehir adını ve seçtiğin konumun iki ondalığa yuvarlanmış koordinatlarını (yaklaşık 1 km) alır. İstekler çerez ve yönlendiren (referrer) bilgisi olmadan gönderilir. Open-Meteo'nun koşulları ve gizlilik bilgileri: https://open-meteo.com/

Firefox'ta bu, opsiyonel *konum* verisi olarak beyan edilir: Firefox ilk hava isteğinden önce onayını ister; onayı istediğin zaman eklentinin izinlerinden geri alabilirsin. Onay olmadan widget hiçbir şey göndermez.

Eklentinin yaptığı başka bir istek yoktur. Arama yaptığında ya da bir bağlantı açtığında tarayıcın o siteye (örneğin seçtiğin arama motoruna) gider; o sitenin ne yaptığı kendi gizlilik politikasına tabidir.

## Opsiyonel izinler

NEONDECK yalnızca `storage` izniyle kurulur. Diğer izinler opsiyoneldir ve yalnızca ilgili düğmeye tıkladığında istenir:

- **Site favicon'ları (`favicon`, yalnızca Chrome)**: site ikonlarını tarayıcının kendi ikon önbelleğinden gösterir. Sitelere istek gönderilmez.
- **Tarayıcı yer imleri (`bookmarks`)**: yalnızca **Yer imlerini içe aktar**'a tıkladığında bir kez okunur ve cihazındaki netlink'lerine kopyalanır. Yer imleri hiçbir yere gönderilmez.

Bunları istediğin zaman **Ayarlar → İzinler**'den ya da tarayıcının eklentiler sayfasından geri alabilirsin.

## Yedekler

**JSON dışa aktar** bilgisayarında bir dosya oluşturur; **JSON içe aktar** seçtiğin dosyayı okur. Bu dosyalar sen paylaşmadıkça cihazından çıkmaz. Yüklenen arka planlar yedeğe dahil edilmez.

## NEONDECK'in yapmadıkları

- kullanıcı hesabı ya da oturum açma yok
- analitik, telemetri, izleme ya da reklam yok
- veriler kimseye satılmaz ya da paylaşılmaz
- uzak kod yok: eklentinin çalıştırdığı her şey paketin içindedir

## Çocuklar

NEONDECK çocuklar dahil kimseden bilerek veri toplamaz.

## Değişiklikler

Bu politika değişirse yeni sürüm aynı adreste yeni tarihle yayımlanır.

## İletişim

Sorular için: kurogrid.dev@gmail.com
