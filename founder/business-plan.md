# Ağız İçi Tarayıcı Satış ve Kiralama (çalışma adı) · İş planı

**Karar: EKSİK** (`compile.py` ile hesaplandı)

- ✗ 100 simüle alıcıdan 7'si alıyor (%7; eşik %25).
- Henüz rakam yok (`founder/numbers.json`). `/founder-cfo` çalıştırılıp plan yeniden derlenmeli.

## Fikir

- Ne: Diş kliniklerine ve diş hekimlerine ağız içi tarayıcı (intraoral scanner) satan ve hasta başı ücretle kiralayan bir iş.
- Kimin için: Diş klinikleri ve diş hekimleri.
- Ne satıyor, kaça:
  - Ürün: Launca DL-300 Wireless ağız içi tarayıcı.
  - Satış: 4.950 € + KDV.
  - Kiralama: hasta başı 50 € + KDV.
- Nerede ve nasıl: Kiralama Ankara'da (girişimci cihazla randevulu olarak kliniğe gidiyor), satış Türkiye geneli. Müşteriye ulaşma kanalı henüz belirtilmedi.
- Destek (girişimci teyit etti, 27 Kasım 2026): Türkiye genelinde teknik servis; arızada yedek cihaz (süreler aşağıda); kendi kliniğinde ilk birkaç hastada ücretsiz deneme; kiralamada aynı hastanın tekrar taramaları ücretsiz.
- Kiralama modeli (girişimci teyit etti, 27 Kasım 2026): cihaz klinikte kalmıyor. Girişimci cihazla kliniğe gidiyor, hekim hastayı tarıyor, cihaz girişimciye geri veriliyor. Sayım hekimin gözü önünde, taranan hasta sayısı kadar. Randevular önceden, hekimin ve girişimcinin uygun olduğu saate ayarlanıyor; girişimci tarama sırasında odaya girmiyor. Aynı gün tarama gerekirse, girişimci müsaitse aynı gün de geliyor. Ücretsiz denemedeki taramaların STL dosyaları hekimin kendi laboratuvarına gönderilip onay alınabilir.
- Tedarik ve servis (girişimci teyit etti, 27 Kasım 2026): Cihazın toplam maliyeti 2.700 € (nakliye ve gümrük dahil). Girişimci Launca distribütörü, ama münhasır anlaşma yok. Servisi girişimci veriyor; büyük arızada Launca doğrudan yeni cihaz gönderiyor. Taksit şu an mümkün değil. Girişimci stokta yedek cihaz tutuyor; arızada Ankara ve İstanbul'a 1–2 gün, Türkiye'nin geri kalanına 5 gün içinde gönderiyor.
- Giderler (girişimci teyit etti, 27 Kasım 2026): Ankara'da bir klinik ziyaretinin maliyeti 1.000 TL. Aylık sabit gider 100.000 TL.
- Bütçe ve kısıtlar: Kuruluş bütçesi 750.000 TL. Diğer kısıtlar (zaman, ekip) belirtilmedi.

## Özet

### Karar: EKSİK (sayılardan hesaplandı, `compile.py`)
Kararı belirleyen üç sayı:

| # | Sayı | Durum |
| --- | --- | --- |
| 1 | **Simüle alıcı oranı: %7** (100 hekimden 7'si aldı; eşik %25) | ✗ Geçmiyor |
| 2 | **Cihaz başına brüt kalan: 2.250 €** (4.950 € − 2.700 € maliyet; servis, yol ve diğer giderler hariç) | CFO doğrulamadı |
| 3 | **Başa baş noktası ve 1. yıl kârı: hesaplanamadı** (aylık sabit gider 100.000 TL; euro/TL kuru, beklenen satış ve tarama sayısı ve başlangıç harcamasının dağılımı eksik) | Eksik |

**Karar neden "Eksik":** `founder/numbers.json` yok, çünkü `/founder-cfo` çalışmadı. Birim kârı, 1. yıl kârı ve başa baş kontrolleri yapılamadı. Panelden geçmeyen tek kontrol de alıcı oranı: %7, eşik %25.

**Eşik hakkında:** %25 varsayılan bir eşik ve aslında tüketici ürünleri için konmuş. 5.000 €'luk bir tıbbi cihazı, ilk kez duyan hekimlerin almasını ölçen bir panel için yüksek olabilir. Ama eşiği düşürmek kararı değiştirmez: rakamlar olmadan karar zaten "Eksik" kalır. Eşiği değiştirmedim.

### İş ne, kimin için
Launca DL-300 kablosuz ağız içi tarayıcının Türkiye distribütörü olarak iki teklif:
- **Satış:** 4.950 € + KDV, öncelikle çok hekimli polikliniklere.
- **Ankara'da randevulu kiralama:** hasta başı 50 € + KDV, peşin yok, öncelikle küçük ve yeni muayenehanelere.

İkisi de ücretsiz deneme ve hekimin kendi laboratuvarından STL onayıyla başlıyor.

### Panel ve kurul neyde anlaştı, neyde ayrıldı
**Anlaştıkları:**
- En büyük engel güven ve kanıt. Panelde 84 hekim "laboratuvarım onaylarsa" dedi. Kurulun üç üyesi de laboratuvar teyidi ve referans hekim istedi.
- Fiyat engel değil. 4.950 € kabul edilebilir aralıkta (2.506–5.497 €); engel peşin ödeme ve taksit yokluğu.

**Ayrıldıkları:**
- Kurul "satış mı kiralama mı ana iş" diye bölündü.
- Panel bunu kısmen cevapladı: kiralayanların hepsi küçük muayenehane, satın alanların hepsi poliklinik. Yani iki kol iki ayrı müşteriye hitap ediyor.
- Kurulun Tekel merceği ise münhasırlık olmadığı için hâlâ "geç" diyor.

### En büyük risk ve yapılacak
**Risk:** Kanıt olmadan hekimin "hayır" demesi. Laboratuvar onayı yok, referans hekim yok, distribütörün kalıcılığına dair güvence zayıf.

**Yapılacak:**
- Ankara Pilot: 15 klinik ve bir laboratuvar tarama günü, 30 Kasım – 20 Aralık.
- 2 laboratuvardan yazılı STL onayı.
- İlk referans klinikler.

Daha fazla bonus eklemek işe yaramadı; kısa panel testinde alım arttırmadı (bkz. `founder/offer.md`).

### Başlamak için gerekenler
- **Nakit:** CFO hesaplamadan belli değil. Elde 750.000 TL bütçe var, aylık sabit gider 100.000 TL.
- **İlk test:** Ankara Pilot. Yeni stok almadan, elindeki demo ve yedek cihazla yapılacak.
- **Başarı çizgisi:** 15 demodan en az 2 ödeyen klinik (bkz. `founder/launch.md`).

### Bu hafta yapılacak tek şey
**`/founder-cfo`'yu çalıştır.** Bunun için şu dört bilgiyi ver:
1. Euro/TL kuru
2. Bir kiralama ziyaretinde kaç hasta taranıyor
3. Beklenen aylık satış ve tarama sayısı
4. 750.000 TL'nin dağılımı (kaç cihaz stok, tanıtım, kuruluş)

Karar ancak bu rakamlarla "Kârlı" ya da "Henüz değil" olabilir. Aynı hafta Ankara'daki ilk laboratuvar randevularını al.

---
*Panel simüle alıcılardan oluşuyor, rakamlar projeksiyon. Gerçek müşteriler ve gerçek teklifler bunları doğrulamalı. Bu belge finansal, hukuki ya da vergi tavsiyesi değildir.*

## Kurulun görüşü

Tarih: 27 Kasım 2026. Önceki kararlar: `founder/board-v1/board.md`, `founder/board-v2/board.md`.

### 1. Oy
**2 şartlı fonla, 1 geç.** Ortalama puan: **4,0 / 10** (önceki iki kurulda 3,7).

| Mercek | v1 | v2 | v3 | Oy (v3) |
| --- | ---: | ---: | ---: | --- |
| Teklif | 4 | 4 | **5** | ŞARTLI FONLA |
| Tekel | 3 | 3 | 3 | GEÇ |
| Ürün | 4 | 4 | 4 | ŞARTLI FONLA |

Ayrıntılar: `founder/board/offers.md`, `monopoly.md`, `product.md`.

**Ne değişti:**
- **Teklif merceği puanı 4'ten 5'e çıkardı.** Gerekçeleri: pozitif birim marjı (cihaz başına 2.250 €), stokta yedek cihaz ve somut servis süreleri, laboratuvar onaylı deneme.
- **Ürün merceği satış sonrası desteği artık güçlü yan sayıyor.** "Cihaz bozuldu, iş durdu" anı baştan ele alınmış.
- **Tekel merceği yerinde kaldı.** Münhasırlık yok, kiralama kopyalanabilir.

### 2. Birden fazla üyenin dile getirdiği riskler
1. **Kanıt yok (3/3).** Laboratuvarlardan yazılı STL kabulü yok, referans hekim yok, işin adı yok. Son teklif (randevulu kiralama) panelde hiç test edilmedi. Teklif merceğine göre tekliflerin en çok battığı yer burası.
2. **Kiralama tek kişiye bağlı ve ölçeklenmiyor (3/3).** Hekimin hastası koltuktayken cihaz yolda olabilir. Sen hastalanırsan ya da izne çıkarsan hizmet duruyor. Bir ziyaretin yol ve zaman maliyeti bilinmediği için 50 €'nun kâr bırakıp bırakmadığı da bilinmiyor.
3. **Satış tarafı fiyat yarışına kayıyor (Teklif + Tekel).** Münhasırlık yok: Launca ikinci bir distribütör atayabilir, cihaz gri pazardan da gelebilir. Rakipler taksit veriyor, sen veremiyorsun (34 itiraz). "Daha ucuz ama peşin" teklifi hekimin "hayır" demesini kolaylaştırıyor.
4. **Laboratuvar ile klinik arasındaki devir kanıtlanmadı (Ürün + Teklif).** Hekimin asıl satın aldığı şey tarayıcı değil, laboratuvarın sorunsuz kabul ettiği bir ölçü. Burada bir kusur çıkarsa suç cihaza yazılır.

### 3. Koşullar: kontrol listesi
- [ ] **Kanıt önce:** Ankara'da 2–3 laboratuvardan DL-300 STL dosyalarını kabul ettiklerine dair yazılı teyit ve deneme yapmış en az bir referans hekim. Bunlar olmadan stok alımına bütçe harcanmasın. *(3 üye)*
- [ ] **Kiralamanın birim ekonomisi:** Bir ziyaretin yol ve zaman maliyeti, günlük randevu kapasitesi ve 50 €'dan geriye kalan tutar hesaplansın. 50 € maliyeti karşılamıyorsa model değişsin. → `/founder-cfo` *(3 üye)*
- [ ] **Sen yokken plan:** Yedek kişi, iptal kuralı ve günlük kapasite yazılı hâle gelsin. *(3 üye)*
- [ ] **Odak kararı:** İlk harcamadan önce satış mı kiralama mı ana iş, yazılı olarak karar verilsin. *(Ürün; diğer ikisi farklı yöne bakıyor, bkz. bölüm 4)*
- [ ] **Garanti ve adı konmuş teklif:** Örneğin "laboratuvar taramayı reddederse o hastanın ücreti alınmaz" ya da satışta "X gün içinde laboratuvar uyumu yoksa iade". Ayrıca eğitim, laboratuvar kurulumu ve kiradan satışa geçişte ödenenin mahsubu. → `/founder-offer` *(Teklif)*
- [ ] **Taksite cevap:** Bir finansman ortağı ya da kira mahsubu gibi bir yol bulunsun. Bulunamazsa satış, peşin ödeyebilen çok hekimli polikliniklerle sınırlansın. *(Teklif + Ürün)*
- [ ] **Savunulabilir bir kilit:** Launca'dan yazılı münhasırlık (en az Ankara) ya da laboratuvarlarla yazılı STL kabul ve yönlendirme anlaşmaları. *(Tekel, oy değiştirme şartı)*
- [ ] **Satın alan hekimin uçtan uca akışı:** Teslimat, kurulum, eğitim, ilk vaka ve servis çağrısı adım adım yazılsın; her adımın sorumlusu ve süresi belli olsun. *(Ürün)*
- [ ] **Son teklifi test et:** Düzeltilmiş kiralama anlatımıyla panel yeniden çalışsın. Ardından gerçek bir ön satış yapılsın. → `/founder-consumer` *(3 üye)*
- [ ] **Pazar ve kanal:** Ankara'da tarayıcısı olmayan kaç klinik var, ilk 10 kiralama müşterisi nereden ve kaça gelecek? → `/founder-consumer`, `/founder-cfo` *(3 üye)*

### 4. Üyeler arasındaki ayrılık
Kurul en temel soruda bölündü: **hangi kol ana iş?**
- **Ürün merceği satışı seçiyor.** Panelde alan 6 kişiden 5'i satın almayı seçti; kiralama girişimcinin takvimini tüketiyor. Ona göre kiralama ya kesilmeli ya da süre ve kapasite sınırı olan bir "satın almadan önce deneme yolu" olarak yeniden tanımlanmalı.
- **Tekel merceği kiralamayı seçiyor.** Satışta hiçbir koruma yok, ürün emtia. "Küçük pazarda büyük pay" başlangıcı yalnızca Ankara'daki hasta başı kirada görünüyor. Ama sadece bir kilit (münhasırlık ya da laboratuvar anlaşmaları) ve girişimciden bağımsız bir ölçek planı varsa fonlar.
- **Teklif merceği ikisini birden tutuyor.** Farkı fiyatta değil yığında görüyor: garanti, eğitim, laboratuvar kurulumu, kiradan satışa mahsup. Bu yığın varsa her iki kol da işler.

Bu ayrılığı kurul çözemiyor. Kiralamanın ekonomisi (`/founder-cfo`) ve son teklifin panel sonucu (`/founder-consumer`) çözecek.

### 5. Kurulun görebildiği en güçlü versiyon
Bu, anlattığın modelden farklı. En güçlü versiyon iki ayrı iş değil, tek bir huni:
- **Ana gelir satış.** Çok hekimli polikliniklere, adı konmuş bir teklifle satılıyor: ücretsiz deneme, laboratuvar onaylı STL, eğitim, 1–2 gün yedek cihaz ve "laboratuvar kabul etmezse iade" garantisi.
- **Ankara'daki hasta başı kiralama huninin girişi.** Peşin ödeyemeyen ya da emin olamayan hekim önce kiralıyor. Ödediği kiralar satın almaya geçince fiyattan düşülüyor. Böylece taksidin işlevi senin ek finansman riskin olmadan görülüyor.
- **Hendek laboratuvarlar.** Hekimin çalıştığı 2–3 Ankara laboratuvarıyla yapılmış yazılı STL kabul ve yönlendirme anlaşmaları ve ilk referans hekimler. Münhasırlık alınabilirse ikinci kilit olur.

Bu versiyon Ürün merceğinin "satış ana iş" görüşüyle, Tekel merceğinin "laboratuvar anlaşmaları kilit olur" görüşünü birleştiriyor. Kiralamanın kapasite sorunu da huni girişi olduğu için daha az önem taşıyor.

---
*Kurul üyeleri yayımlanmış iş çerçevelerini uygulayan mercekler, gerçek kişiler değil. Bu değerlendirme finansal, hukuki ya da vergi tavsiyesi değildir.*

## Rekabet

Tarih: 27 Kasım 2026. Bilgiler herkese açık kaynaklardan alındı ve her birinin bağlantısı verildi. Bayi sayfaları doğrudan okundu. "(arama sonucu)" ile işaretlenen bilgiler arama motoru özetinden geliyor; o sayfalar tek tek açılmadı.

> **Sınırlar:** Türk depoları tarayıcı fiyatlarını üye girişinin arkasında tutuyor, bu yüzden hiçbir depoda açık fiyat görülemedi. Şikâyetvar otomatik erişimi CAPTCHA ile engelliyor. Google Haritalar yorumları okunamadı. Şikâyet bölümü bu nedenle zayıf. Hiçbir rakam tahmin edilmedi.

### 1. Rakip tablosu (en doğrudan rakipten başlayarak)

#### Kiralama: Ankara
| Rakip | Tür | Ne sunuyor | Fiyat | Kaynak |
| --- | --- | --- | --- | --- |
| **Herkese açık tarayıcı kiralama teklifi bulunamadı** | — | Okunan 10 bayi sayfasının hiçbirinde "kiralama" ya da "kiralık" geçmiyor; aramalarda da Ankara'da kiralama teklifi çıkmadı | — | aşağıdaki bayi sayfaları |
| Medoral Care (Çankaya) | Doğrudan, satış | iTero Lumina; eğitim içerikleri. Sayfa başlığı: "iTero Türkiye Yetkili Satıcısı" | sitede yok | [medoralcare.com](https://www.medoralcare.com/) |
| Çatak Diş Deposu (Kızılay) | Doğrudan, satış | Dexis IS 3700 ve 3800; eğitimler, Exocad eğitimi, teknik servis. "Türkiye genelinde 30 yıla yakın tecrübe" | sitede yok | [catakdisdeposu.com](https://catakdisdeposu.com/agiz-ici-tarayicilar/) |
| Ankara'da ikinci el ilanlar | Dolaylı | Satılık iTero Element, Çankaya'da Heron tarayıcılar (arama sonucu) | — | [dentalilan Ankara](https://dentalilan.com/ankara-r781962) |
| Laboratuvar tarama hizmeti | İkame | Klinik cihaz almadan dijitale geçiyor: "bir tarayıcı veya yazılım satın alma ihtiyacı bile yoktur" (arama sonucu) | — | [United Dental](https://www.uniteddental.com.tr/klinik-dijitalizasyon-tarama/) |
| Geleneksel ölçü | İkame | Bugünkü varsayılan yöntem | — | — |

#### Satış: Türkiye geneli
| Rakip | Ne sunuyor | Fiyat görünürlüğü | Kaynak |
| --- | --- | --- | --- |
| Dentrealmarket | iTero Lumina/Pro, Dexis IS 3700/3800W, Eighteeth Helios 500/700 Kablosuz, 3Shape Trios 3/5 Kablosuz/Core, Aoralscan 3, Woodpecker Smile Scan, Primescan Connect. Kampanya: "Eski Tarayıcını Getir Lumina Pro Al" | Gizli (ürün verisinde fiyat 0). Bazı ürünlerde **"Vade Farksız 8 Taksit"** | [kategori](https://www.dentrealmarket.com/kategori/agiz-ici-tarayicilar) |
| Merkez Diş Deposu | Eighteeth Helios 500/600/680/700 Kablosuz, Cerec Primescan Connect | Yok. Sitede şöyle yazıyor: "Fiyatlandırma; cihazın donanımsal özellikleri, yazılım lisansları, teknik destek kapsamı ve entegrasyon seçeneklerine göre farklılık gösterebilir." | [merkezdis](https://www.merkezdis.com.tr/kategori/agiz-ici-tarayici) |
| Osstemshop | Medit i700 kablolu; teknik servis, yedek parça, webinar ve eğitim takvimi | **"Fiyatı Görmek İçin Giriş Yap"** | [osstemshop](https://osstemshop.com.tr/medit-i700-kablolu-ag-z-ici-taray-c/) |
| Dismalzemeleri.com | Medit i700 (Medit Türkiye); "üretici/distribütör garantilidir" | Fiyat için üye girişi gerekli | [dismalzemeleri](https://www.dismalzemeleri.com/medit-i700-agiz-ici-tarayici-pmu1403) |
| Edental | 3Shape, Medit, iTero karşılaştırması. Medit: "Fiyat-performans açısından yüksek tercih edilirlik"; iTero: "Yüksek fiyat" | Fiyat verilmemiş | [edental](https://www.edental.com.tr/hangi-agiz-ici-tarayici) |
| FUSSEN S6500 (DMO kamu kataloğu) | Çin menşeli tarayıcı | **Birim fiyat 178.767,16 ₺, KDV oranı %10.** Görülen tek açık TL fiyatı | [dmo.gov.tr](https://www.dmo.gov.tr/Katalog/Urun/Detay/5856906_1254029) |
| Launca Türkçe sitesi | DL-300 Kablosuz, DL-300, DL-300P, DL-206; tarayıcı eğitimi ve sorun giderme sayfaları; WhatsApp ve "Demo İste". Türkiye adresi ya da distribütör yok | Fiyat yok | [launca.com.tr](https://www.launca.com.tr/) |
| İkinci el (dentalilan) | Az kullanılmış Medit i700 | **5.000 EUR, 5 taksit** (arama sonucu) | [dentalilan](https://dentalilan.com/dental-urun-ilanlari/klinik-demirbas-urunler-cihazlar/dijital-dis-hekimligi-cadcam-sistemleri) |
| Gri pazar ithalat | Launca DL-300 Kablosuz; kripto, havale ve Western Union kabul ediyorlar | **4.750 USD** ([Bonker](https://bonkersales.com/index.php?path=146&route=product%2Fcategory)), **4.250 USD** ([Drpridemart](https://drpridemart.com/index.php?route=product%2Fcategory&path=146)) (arama sonucu) | |

#### Aynı cihazın yurt dışı fiyatları (DL-300 Kablosuz, arama sonucu)
- İngiltere, Dentinova: 3.999 £, KDV dahil. [Kaynak](https://store.dentinova.co.uk/product/launca-dl-300-wireless-intraoral-scanner-best-seller-ios/)
- ABD, Nour Dental: 14.225 USD. [Kaynak](https://nourdentalsupply.com/products/launca-dl-300-wireless-intraoral-scanner-free-shipping)
- ABD, Alpine Dental: 12.353 USD. [Kaynak](https://alpinedentalshop.com/products/launca-intraoral-wireless-intraoral-scanner-dl-300)
- Referans: Aoralscan 3 kablolu modelin önerilen perakende fiyatı 10.999 USD; abonelik yok. [Kaynak](https://www.shining3ddental.com/news-post/aoralscan-3-intraoral-scanner-review-the-latest-ios-by-shining-3d-the-best-low-cost-ios)

### 2. Fiyat aralığı (yeni bir tarayıcı için)
Türk depolarının hiçbiri fiyatı açık göstermiyor. Bu yüzden medyan hesaplanamadı; kur dönüşümü de yapılmadı.
- **En düşük:** Gri pazarda DL-300 Kablosuz, 4.250 USD (garanti ve yetki belirsiz).
- **Türkiye'de görülen tek açık fiyat:** FUSSEN S6500, 178.767,16 ₺ + %10 KDV (DMO kamu kataloğu).
- **Senin fiyatın:** DL-300 Kablosuz, 4.950 € + KDV.
- **İkinci el kıyas:** Az kullanılmış Medit i700, 5.000 EUR. Senin yeni cihaz fiyatına neredeyse eşit.
- **Açık iş:** Gerçek bayi fiyatları ancak üye olarak ya da telefonla teklif isteyerek öğrenilebilir: Çatak 0312 229 27 18, Medoral, Osstem, Merkez Diş. `/founder-pricing` öncesi en değerli adım bu.

### 3. Konumlandırma haritası (metin)
Eksenler: **Fiyat** (düşük → yüksek) × **Destek** (kutu teslim → eğitim, servis, garanti).

```
Destek ↑
yüksek |                        [Çatak: eğitim + Exocad + teknik servis]  [iTero bayileri: Medoral]
       |                        [Osstem: servis + yedek parça + webinar]  [3Shape: TRIOS Care]
       |   ( BOŞLUK: düşük fiyat + yerel destek + kiralama )
       |                        [Dentrealmarket / Merkez: çok markalı depo, taksit]
düşük  |  [Gri pazar DL-300]   [İkinci el ilanlar]   [FUSSEN S6500 / DMO]
       +---------------------------------------------------------------→ Fiyat
          düşük                                                    yüksek
```
Yerleşik depolar destek, eğitim ve servisi öne çıkarıyor (Çatak, Osstem). 3Shape'in TRIOS Care paketi ilk yıl içinde kurulum, eğitim, garanti ve hızlı cihaz değişimi sunuyor. [Kaynak](https://www.3shape.com/tr/scanners/trios-3). Senin cihazın fiyatta alt segmentte. Desteği belirsiz olursa gri pazarla ve ikinci elle aynı kutuya düşer.

### 4. Şikâyetler (sıralı; hepsi **zayıf**, her biri 3 yorumdan az)
1. **Bilgisayar uyumu ve bağlantı (zayıf, 1 şikâyet).** Başlık: "Thunderbolt 4 Olmayan Anakart Nedeniyle Tarayıcı Çalışmıyor Ve Değişim Talebim Reddedildi" (arama sonucu). [Şikâyetvar / İncehesap](https://www.sikayetvar.com/incehesap/musteri-hizmetleri?page=9). Destekleyen bilgi: Osstem de "Tarayıcının performansı kullanılan bilgisayarın işlemcisine, ekran kartına, belleğine… bağlıdır" diye uyarıyor. [osstemshop](https://osstemshop.com.tr/medit-i700-kablolu-ag-z-ici-taray-c/)
2. **Fiyat şeffaflığı yok (gözlem, şikâyet değil).** Depoların hepsi fiyatı üye girişine ya da satış ekibine bağlıyor. Hekim karşılaştırma yapmak için birden fazla depoyu aramak zorunda.
3. **Bayi şikâyetleri (zayıf).** Merkez Diş Deposu'nun Şikâyetvar'da 1 şikâyeti var (arama sonucu); sayfa CAPTCHA yüzünden okunamadı. [Şikâyetvar](https://www.sikayetvar.com/merkez-dis-deposu)

Diğer risk sinyalleri:
- **Patent riski.** 3Shape, Medit'in bazı tarayıcılarının patentlerini ihlal ettiğini iddia etti. Bu, 3Shape'in kendi açıklaması. [Business Wire](https://www.businesswire.com/news/home/20200113005525/en/3Shape-Wins-Patent-Infringement-Lawsuit-Against-Medit)
- **Launca'nın Türkiye distribütörü yok gibi görünüyor.** Türkçe sitede adres ya da bayi bilgisi yok; sadece WhatsApp ve demo formu var. [launca.com.tr](https://www.launca.com.tr/)

**Açık iş:** Google Haritalar yorumları elle okunmalı. Ayrıca 5–10 hekimle kısa görüşme yapılmalı (`/founder-consumer`).

### 5. Boşluk (güncellendi: 27 Kasım 2026, yeni teklif modeline göre)
Piyasa bilgisi değişmedi. Bu bölüm, girişimcinin teyit ettiği teklif maddelerine göre yeniden yazıldı: randevulu yerinde kiralama, ücretsiz deneme, STL dosyasıyla laboratuvar onayı, servis ve yedek cihaz.

1. **"Cihaz almadan dijital ölçü" boşluğu.** Okunan 10 bayi sayfasının hiçbiri kiralama ya da hasta başı ücret sunmuyor; piyasada tek finansman yolu taksit. Senin modelinde hekim cihaz almıyor, bakım yapmıyor, cihazı klinikte saklamıyor; sadece taradığı hasta için ödüyor. Bu modelin piyasadaki tek alternatifi laboratuvarın tarama hizmeti ([United Dental örneği](https://www.uniteddental.com.tr/klinik-dijitalizasyon-tarama/)). Fark şu: laboratuvar hizmetinde hekim laboratuvara bağlanıyor, senin modelinde dosya hekimin kendi seçtiği laboratuvara gidiyor.
2. **"Satın almadan önce kendi laboratuvarınla dene" boşluğu.** Depolar fiyatı bile üye girişinin arkasında tutuyor; herkese açık bir "kendi laboratuvarına STL gönder, onay al" teklifi görülmedi. Panelde en büyük itiraz laboratuvar uyumuydu (72 kişi). Bu teklif tam olarak ona cevap veriyor.
3. **Düşük fiyat + destek kutusu.** Desteği güçlü olanlar (Çatak, Osstem, iTero ve 3Shape bayileri) premium marka satıyor; ucuz seçeneklerin (gri pazar, ikinci el) desteği yok. Servis ve yedek cihaz taahhüdüyle 4.950 € bu kutuya oturuyor.

**Hâlâ açık olan:** Satışta taksit yok. Depolar "vade farksız 8 taksit" veriyor; ikinci el ilanlarda bile 5 taksit var. Taksit eklenmezse satışta depolara karşı dezavantaj sürüyor.

### 6. Tehdit: seni en hızlı kim kopyalar? (güncellendi)
- **Ankara'daki depolar (Çatak Diş Deposu, Medoral Care).** Teknik servis ekipleri ve hekim ilişkileri hazır. Yerinde kiralama modelini kopyalamaları kolay, ama premium marka sattıkları için hasta başı 50 €'ya inmeleri zor olabilir. Bu bir tahmin; doğrulanmadı.
- **Diş laboratuvarları.** Hekimi kendine bağlamak için tarayıcıyla kliniğe gidebilir ya da cihazsız tarama hizmeti verebilirler. Senin modeline en yakın rakip türü bu; Ankara'daki yaygınlığı doğrulanmadı.
- **Başka Launca satıcıları ya da üreticinin kendisi.** Türkiye'de görünür bir distribütör yok. Münhasırlık alamazsan aynı cihazı başkası daha ucuza satabilir.
- **Modelin doğal sınırı:** Tek kişi ve tek cihazla kiralama kapasitesi günlük randevu sayısıyla sınırlı. Büyüdükçe ikinci cihaz ve ikinci kişi gerekir; bu maliyeti `/founder-cfo` hesaplayacak.

### Sonraki adım
- `/founder-consumer`: son teklifi (randevulu kiralama, STL onayı) panelde test et.
- `/founder-pricing`: bu fiyat aralığını kullanır.
- `/founder-cfo`: kiralama kapasitesini ve kârlılığı hesaplar; cihazın alış fiyatı gerekecek.

## Alıcı paneli

**7 alır · 93 almaz** (%7) — 100 simüle alıcı. Seed 393267; aynı kartlar yeniden dağıtılabilir.

Bunlar simüle alıcılar, gerçek müşteri değil. İtirazları ve zayıf noktaları bulmak için kullan; büyük kararları para harcamadan önce gerçek kişilerle doğrula.

### Gruba göre

| grup | alıcı | alım oranı |
| --- | ---: | ---: |
| Yeni muayenehane açmış diş hekimi (yıllık geliri USD karşılığı) | 30 | 10% |
| Çok hekimli poliklinik / klinik sahibi diş hekimi (yıllık geliri USD karşılığı) | 30 | 10% |
| Yerleşik muayenehane sahibi diş hekimi (yıllık geliri USD karşılığı) | 40 | 2% |

### Satın alma davranışına göre

| grup | alıcı | alım oranı |
| --- | ---: | ---: |
| Önce dener sonra alır | 12 | 42% |
| Taksitle alan | 18 | 11% |
| Laboratuvarına bağlı | 15 | 0% |
| Meslektaş tavsiyesiyle alan | 13 | 0% |
| Fiyat avcısı | 15 | 0% |
| Klasik ölçüden memnun | 15 | 0% |
| Premium marka sadığı | 12 | 0% |

### Gelire göre

| grup | alıcı | alım oranı |
| --- | ---: | ---: |
| 43.000 $ altı (USD karşılığı) | 33 | 9% |
| 95.000 $ ve üstü | 35 | 9% |
| 43.000–95.000 $ | 32 | 3% |

### Neden almıyorlar

| neden | alıcı | kendi cümleleriyle |
| --- | ---: | --- |
| habit | 32 | "Klasik ölçü hâlâ işimi görüyor, laboratuvar dijital dosya istemeye başladı ama zorunlu tutmuyor. Laboratuvarım hangi tarayıcıyı önerirse ona bakarım; kendi başıma tanımadığım bir Çin markasına 5 bin euro vermem." (P001) · "Silikon ölçüyle yıllardır sorunsuz çalışıyorum, hastam da laboratuvarım da memnun. Muayenehaneyi yeni açtım, kira ve asistan maaşı zaten zorluyor; neredeyse yıllık gelirimin yarısı kadar bir cihaza ya da hasta başı 50 € ek maliyete şu an gerek görmüyorum." (P005) |
| trust | 32 | "Bulantı refleksli hastalarda dijital ölçü işime yarar, ama Launca'yı kullanan tanıdığım tek bir meslektaşım yok. Bu parayı peşin vereceksem ya ikinci el bir Medit alırım ya da depodan taksitle herkesin bildiği bir markayı." (P003) · "Klasik ölçü zaten işimi görüyor, hastam da şikâyet etmiyor; dijitale geçeceksem 3Shape ya da iTero gibi herkesin bildiği bir markaya geçerim, adını meslektaş grubunda hiç duymadığım bir Çin markasına değil." (P006) |
| price | 28 | "Laboratuvar dijital dosya istediği için bir tarayıcıya ihtiyacım olacağı belli, ücretsiz denemeyi de kabul ederim. Ama birkaç teklif toplamadan, ikinci el ilanlara ve diğer markaların kampanyalarına bakmadan bu ay 4.950 € + KDV vermem; hasta başı 50 € de bizim fiyatlarımıza göre pahalı." (P004) · "4.950 € peşin ödeyip bir Çin markasına bağlanmadan önce depodan taksitli Medit ya da Shining teklifine ve ikinci el ilanlara bakarım; birkaç teklif toplamadan bu ay karar vermem. Ücretsiz denemeyi isterim ama satın alma bu ay olmaz." (P007) |
| need | 1 | "Muayenehaneyi yeni açtım, yılda kazandığım paranın neredeyse dörtte biri olan 4.950 € + KDV'yi klasik ölçünün zaten yaptığı bir iş için bağlayamam. Ücretsiz denemeyi belki kabul ederim ama hasta başı 50 € da benim az sayıdaki protez vakamda hastaya yansıtamayacağım bir ek maliyet." (P048) |

### Neden alıyorlar

| neden | alıcı | kendi cümleleriyle |
| --- | ---: | --- |
| need | 3 | "Laboratuvarım artık dijital dosya istiyor ve yeni açtığım muayenehanede 5.000 € bağlayacak param yok; önce ücretsiz denerim, lab STL'leri onaylarsa ayda birkaç hastada hasta başı kiralamayla başlarım. Satın almayı şimdilik düşünmüyorum." (P016) · "Laboratuvarım artık dijital dosya istiyor ve birkaç hekimin çalıştığı klinikte hasta başı 50 € kiralama kısa sürede satın almayı geçer. Önce ücretsiz denemeyi yaparım; laboratuvar STL'leri sorunsuz onaylarsa 4.950 € benim için makul, bir tane alırım." (P046) |
| price | 3 | "Kiralama bana göre değil, birden fazla hekim çalışan klinikte cihazın randevuyla gelip gitmesini beklemem. Ama 4.950 € bir tarayıcı için düşük; ücretsiz denemede taramalar laboratuvardan onay alırsa kendi cihazımız olsun diye satın alırım." (P051) · "Çok hekimli klinikte bir tarayıcı tüm koltuklara yetmiyor; 4.950 € bu cihazlar için çok uygun, kendi kliniğimde ücretsiz deneyip laboratuvarım STL'leri onaylarsa ikinci ünite olarak alırım. Kiralama bana göre değil, hacmim yüksek." (P068) |
| convenience | 1 | "Ayda birkaç şeffaf plak vakası için 4.950 € bağlamam, ama önce ücretsiz deneyip STL'leri laboratuvarıma onaylatabiliyorsam, sonra peşinsiz hasta başı 50 € ile kiralamak tam benim tarzım. İlk ay ücretsiz denemeden sonra bir iki hastayı kiralık tararım, satın almayı sonra düşünürüm." (P002) |

### "Hayır"ı ne "evet"e çevirir

- Ücretsiz denemede çektiğim STL dosyalarını laboratuvarım sorunsuz kabul edip bu cihazı bana açıkça önerirse, önce hasta başı kiralamayla başlardım.
- Ankara'da güvendiğim bir meslektaşın bu cihazı aylardır sorunsuz kullandığını söylemesi; yanında taksit imkânı olursa ücretsiz denemeyi kesin yaparım.
- Denemede laboratuvarım STL'leri sorunsuz onaylarsa ve fiyat 4.000 € civarına inerse ya da yazılı garanti ve yedek cihaz taahhüdü sözleşmeye konursa alırım.
- Hastalarımın dijital ölçü istediğini görürsem ya da laboratuvarım dijital ölçüyle işi daha ucuz ve hızlı yapacağını söylerse, önce kiralamayı ücretsiz denemede birkaç hastada denerim.
- WhatsApp grubundaki güvendiğim birkaç meslektaşın bu cihazı aylardır sorunsuz kullandığını söylemesi ve laboratuvarımın Launca STL'lerinin 3Shape kadar oturduğunu onaylaması.
- 12 ay vade farksız taksit ve WhatsApp grubundan en az birkaç meslektaşın bu cihazı kullanıp laboratuvarlarının STL'leri sorunsuz kabul ettiğini söylemesi.
- Ankara'da tanıdığım birkaç meslektaşın bu cihazı bir yıldır sorunsuz kullandığını görmek ve laboratuvarımın deneme taramalarını yazılı olarak onaylaması.
- Kliniğimdeki bilgisayarlara kurulumu ve tüm hekimlerin eğitimini yerinde ücretsiz yapacaklarını yazılı taahhüt etmeleri ve 12 ay vade farksız taksit sunmaları.
- 12 ay faizsiz taksit seçeneği ya da fiyatın 3.500 € civarına inmesi; ücretsiz denemede STL'leri laboratuvarım sorunsuz onaylarsa ciddi düşünürüm.
- Laboratuvarım ücretsiz denemedeki STL dosyalarını sorunsuz kabul edip bu cihazı önerirse ve 12 ay taksit imkanı verilirse ciddi düşünürüm.
- Laboratuvarımın dijital ölçüyü şart koşması ya da fiyatın 3.000 € civarına inip taksitle ödenebilmesi; o zaman ücretsiz denemeyi yapar, kendi hastalarımda STL'leri görüp karar verirdim.
- Denemede laboratuvarım STL'leri sorunsuz onaylarsa ve fiyat rakip tekliflerin altına, 4.000 € civarına inerse, yazılı servis garantisiyle birlikte alırım.

Alanlar ilk ayda ortalama **1,6** alım (satışta cihaz, kirada tarama) yapacağını söylüyor.

100 alıcının hepsi dört fiyat sorusunu cevapladı; analiz Fiyatlama bölümünde.

## Fiyatlama

Tarih: 27 Kasım 2026. Girdiler:
- Panel fiyat eğrisi: `founder/pricing-curve.md` (100 simüle hekim, panel v3)
- Rakip fiyatları: `founder/competitors.md`
- Girişimcinin verdiği maliyet: 2.700 € (nakliye ve gümrük dahil)

> Simüle alıcıların fiyat cevapları neyin test edileceğini seçmeye yarar, kanıt değildir. `founder/numbers.json` henüz yok, çünkü `/founder-cfo` çalışmadı. Aşağıdaki marjlar yalnızca **fiyat − 2.700 €** hesabıdır; satış, yol, servis, yedek cihaz ve sabit giderler dahil değil. Gerçek marjı ve başa baş noktasını CFO hesaplayacak.

### 1. Alıcıların söylediği (Van Westendorp, satın alma, € KDV hariç)
| Nokta | Fiyat | Anlamı |
| --- | ---: | --- |
| PMC | 2.506 € | Bunun altında çok kişi "fazla ucuz, kalitesizdir" der |
| OPP | 2.525 € | En az direnç noktası |
| IPP | 3.795 € | "Ucuz" diyenle "pahalı" diyen eşit |
| PME | 5.497 € | Bunun üstünde çok kişi "almam" der |

**Kabul edilebilir aralık: 2.506 € – 5.497 €.** Medyan cevaplar: çok ucuz 1.500 €, ucuz 3.000 €, pahalılaşıyor 4.500 €, çok pahalı 6.500 €.

**4.950 € aralığın içinde, ama üst kısmında.** IPP ile PME arasında duruyor ve medyan "pahalılaşıyor" eşiğinin (4.500 €) biraz üstünde. Aralığın tavanına (5.497 €) 547 € mesafe var.

### 2. Rakiplerle karşılaştırma
| Seçenek | Fiyat | Ne dahil | Kaynak |
| --- | --- | --- | --- |
| **Senin teklifin** | **4.950 € + KDV** | Yeni cihaz, ücretsiz deneme, STL ile laboratuvar onayı, servis, 1–2 gün yedek cihaz (Ankara/İstanbul) | — |
| İkinci el Medit i700 | ~5.000 € | Az kullanılmış cihaz, 5 taksit; garanti ve servis belirsiz | dentalilan (arama sonucu) |
| Gri pazar DL-300 Kablosuz | 4.250–4.750 USD | Yurt dışından ithal; Türkiye'de garanti ve servis yok | Bonker, Drpridemart (arama sonucu) |
| FUSSEN S6500 (DMO kamu kataloğu) | 178.767 ₺ + %10 KDV | Kamu alımı kataloğu | dmo.gov.tr |
| Türk depoları (Dentrealmarket, Merkez Diş, Osstem, Çatak, Medoral) | Fiyat gizli (üye girişi ya da satış ekibi) | Çoğunda **vade farksız taksit**, eğitim, teknik servis | founder/competitors.md |
| Referans: Aoralscan 3 kablolu | Önerilen perakende 10.999 USD | Üretici fiyatı | shining3ddental.com |

**Sonuç:** Türkiye'de görülen yeni ve servisli seçenekler arasında 4.950 € düşük tarafta. Ama ikinci el Medit ve gri pazar DL-300 ile neredeyse aynı fiyatta. Senin farkın fiyat değil; deneme, laboratuvar onayı, servis ve yedek cihaz. Rakiplerin asıl üstünlüğü taksit.

### 3. Marj (yalnızca fiyat − 2.700 € maliyet)
| Fiyat | Brüt kalan | Brüt marj |
| ---: | ---: | ---: |
| 3.795 € (IPP) | 1.095 € | %29 |
| 4.450 € | 1.750 € | %39 |
| **4.950 € (mevcut)** | **2.250 €** | **%45** |
| 5.497 € (PME) | 2.797 € | %51 |

**Kiralama:** Hasta başı 50 € ile bir cihaz 54 taramada maliyetini çıkarıyor. 25 €'ya inersen bu sayı 108'e çıkar. Yol ve zaman maliyeti dahil değil; CFO hesaplayacak.

### 4. Karar: fiyat
**Liste fiyatı 4.950 € + KDV olarak kalsın.** Gerekçeler:
- Kabul edilebilir aralığın içinde.
- Türkiye'deki yeni ve servisli rakiplerin altında görünüyor.
- En yüksek brüt marjı veriyor (%45), ki bu marj servis, yedek cihaz ve ücretsiz deneme maliyetlerini taşımak zorunda.
- Panelde fiyat itirazlarının neredeyse hepsi fiyatın kendisine değil, **peşin ödemeye** ve **taksit yokluğuna** yönelikti (bkz. bölüm 7). Fiyatı düşürmek bu itirazı çözmez, marjı düşürür.

Fiyatı indirmek yerine ödeme şeklini kolaylaştır: **kira mahsubu** (bkz. merdiven).

### 5. Fiyat merdiveni
| Basamak | Kime | Fiyat | Bir üste çıkma nedeni |
| --- | --- | --- | --- |
| **Kiralama** (Ankara) | Küçük ve yeni muayenehaneler; ayda birkaç vaka | Hasta başı 50 € + KDV, peşin yok | Vaka sayısı arttıkça kira birikir. **6 ay içinde satın alırsan ödenen kiranın tamamı cihaz fiyatından düşülür.** |
| **Satın alma** | Çok hekimli poliklinikler, yüksek hacim | 4.950 € + KDV | Cihaz her an elinde; randevuya bağlı değilsin |
| **Satın alma + paket** (öneri) | İkinci cihaz isteyen ya da ekibini eğitmek isteyen poliklinikler | Fiyat CFO'dan sonra belirlenecek | Örneğin yerinde ekip eğitimi, uzatılmış garanti, ek tarama ucu. Maliyetleri bilinmediği için fiyat konmadı. |

Kira mahsubu, panelde 25 kişinin kendiliğinden istediği şeydi. Taksit veremediğin için taksidin işini görür. Senin riskin de yok, çünkü para peşin geliyor; sadece daha önce ödenmiş oluyor.

### 6. Açılış teklifi
**"Kurucu klinik" programı.** İlk 5 klinik **4.450 € + KDV**'ye satın alır. Karşılığında:
- Referans olmayı kabul eder: meslektaşlarına gösterim ve adının kullanılması.
- Laboratuvarının STL onayını yazılı olarak paylaşır.

**Son tarih: 31 Ocak 2027** ya da 5 klinik dolunca, hangisi önce gelirse. Bu indirim değil, referans karşılığı verilen bir fiyat. Tarihi ve kontenjanı belli olduğu için hekimleri "indirimi bekleyeyim" alışkanlığına itmez. Bu fiyattan cihaz başına brüt kalan tutar 1.750 € (%39).

Kurul ve panel en çok meslektaş referansının eksik olduğunu söyledi. Bu program o eksiği kapatmanın en ucuz yolu.

### 7. Gerçek hekimlerle test
**Test 1: ödeme şekli (fiyat aynı).**
- A: 4.950 € peşin
- B: 4.950 €, 6 ay kira mahsubuyla

İkisini Ankara'da 10'ar kliniğe sun. Ölç: denemeye kaç klinik başladı, kaçı laboratuvar onayı aldı, kaçı satın aldı ya da kiraladı.

**Test 2: fiyat (aralığın içinde iki nokta).**
- 4.950 € ile 4.450 €'yu iki ayrı klinik grubuna sun. Ölç: denemeden satın almaya geçiş oranı.

4.450 € gerçekten daha çok satıyorsa, kaybedilen 500 €'nun hacimle telafi edilip edilmediğini CFO hesaplasın.

**Kiralama fiyatı:** Panelde 8 kişi hasta başı 15–25 € istedi. Ama kiralayan 4 hekimin hepsi 50 €'yu kabul etti. Kiralama fiyatını şimdilik değiştirme. Gerçek denemelerde "pahalı" itirazı çok çıkarsa ayda bir tavan ücreti (örneğin "ayda en fazla X €") test edilebilir. X'i CFO belirlesin.

### 8. Panelin fiyat itirazları (kendi cümleleriyle, en sık üç tema)
1. **Peşin ödeme ve taksit yok:** "4.950 € + KDV'yi tek seferde ödeyecek nakdim yok, depodan bildiğim markaları vade farksız taksitle alabiliyorum." (P063)
2. **Aynı paraya alternatif var:** "4.950 € + KDV peşin, taksitsiz; aynı paraya ikinci el bir Medit bulurum ya da depodan taksitle bilinen bir marka alırım." (P010)
3. **Kiralama birikiyor:** "Ayda 20 civarı ölçü alıyorum, kiralama hasta başı 50 € ile ayda bin euroyu geçer, o yüzden olacaksa satın alırım." (P011)

Bu cümleler gerçek müşteri yorumu değil; pazarlamada itirazlara cevap hazırlamak için kullanılmalı.

### Not: KDV
Teklif KDV hariç fiyatlanmış. Ağız içi tarayıcının KDV oranını muhasebecinle teyit et (DMO kataloğunda bir tarayıcı %10 KDV ile listelenmiş). Hekim KDV dahil ~5.400–5.900 € görecek. Bir panel üyesi (P052) bunu açıkça yazdı: "KDV ile neredeyse 6.000 €."

### Sonraki adım
- `/founder-cfo`: `founder/numbers.json` oluşturur, gerçek marjı, başa baş noktasını ve kiralama kapasitesini hesaplar.
- `/founder-offer`: kira mahsubunu, kurucu klinik programını ve laboratuvar onayını teklife yerleştirir.

## Teklif

Tarih: 27 Kasım 2026. Yöntem: kurulun Teklif merceği (yayımlanmış bir teklif çerçevesinin özeti; bir kişinin sözleri değil).
Girdiler: `founder/panel/rapor.md` (panel v3), `founder/board.md`, `founder/pricing.md`, girişimcinin verdiği maliyetler.

> `founder/numbers.json` henüz yok, çünkü `/founder-cfo` çalışmadı. Maliyetler girişimcinin verdiği rakamlardan kaba olarak hesaplandı: cihaz 2.700 €, klinik ziyareti 1.000 TL. Euro/TL kuru verilmediği için TL ve € karışık gösterildi.

### 1. Problem listesi (hekimin gözünden)
**Satın almadan önce**
1. "Laboratuvarım bu dosyayı kabul eder mi?" (panel v3: 68 itiraz, 84 "evet"e çevirme isteği)
2. "Çevremde kullanan meslektaş yok." (33)
3. "Çin malı; distribütör birkaç yıl sonra kapanırsa servis ve güncelleme ne olacak?" (53)
4. "4.950 € + KDV'yi peşin ödeyemem." (34)
5. "Depolar vade farksız taksit veriyor, burada yok." (43 istek)
6. "Aynı paraya ikinci el Medit alırım."
7. "KDV ile neredeyse 6.000 € ediyor."
8. "Bilgisayarım uyumlu mu, kurulumu ve eğitimi kim yapacak?" (11)
9. "Klasik ölçü işimi görüyor." (alışkanlık: 32 kişi)
10. "Yatırımı kaç yılda çıkarırım?"

**Kullanırken**
11. "Kiralamada randevuya bağlı kalırım, hasta koltuktayken cihaz yolda olur." (21)
12. "Hasta başı 50 € ölçü malzemesine göre çok; hastaya yansıtamam."
13. "Ayda 20 hasta tararsam kira 1.000 €'yu bulur." (birikim)
14. "Tekrar tarama da ücretli mi?" (v2'de vardı, teklife eklendi)
15. "Yeni bir cihazı öğrenmek zaman alır."

**Sonra**
16. "Arıza olursa iş durur." (yedek cihaz var, ama "gerçekten gelir mi?")
17. "Yazılım güncellemesi ve yedek parça kaç yıl sürer?"
18. "İkinci elde değeri olur mu?"
19. "Kira mı alayım, satın mı? Kirada ödediğim boşa mı gidecek?" (25 kişi mahsup istedi)
20. "Hatalı tarama yüzünden ölçüyü tekrar almam gerekirse?"

### 2. Çözümler: değer ve maliyet
Değer 1–5 (hekim için), maliyet 1–5 (senin için; 1 = ucuz).

| # | Çözüm | Karşıladığı problem | Değer | Maliyet | Karar |
| --- | --- | --- | ---: | ---: | --- |
| A | Ücretsiz deneme + STL ile kendi laboratuvarından onay | 1, 15, 20 | 5 | 2 | **Var, kalsın** |
| B | **Laboratuvar onay garantisi:** satın aldıktan sonra 30 gün içinde laboratuvar taramaları kabul etmezse tam iade | 1, 20 | 4 | 2–3 (iade gelen cihaz demo olarak kullanılır) | Denendi (v4) |
| C | Kirada laboratuvarın reddettiği taramanın ücreti alınmaz | 1, 12, 20 | 3 | 1 (50 €/red) | Denendi (v4) |
| D | Kirada gecikme garantisi: geç kalırsak tarama ücretsiz | 11 | 3 | 1 (50 €/gecikme) | Denendi (v4) |
| E | **Kira mahsubu:** 6 ay içinde satın alırsan ödenen kira cihaz fiyatından düşülür | 4, 5, 13, 19 | 4 | 2 (nakit kaybı yok, satıştan düşülüyor) | Denendi (v4) |
| F | Kurucu klinik fiyatı: ilk 5 kliniğe 4.450 €, referans karşılığı, 31 Ocak 2027'ye kadar | 2, 4, 6 | 3 | 3 (5 × 500 € = 2.500 €) | Denendi (v4) |
| G | Sadakat: kirada her 10. hasta ücretsiz | 12, 13 | 2 | 2 (kira gelirinin %10'u) | Denendi (v4), etkisiz |
| H | Yerinde kurulum ve eğitim ücretsiz | 8, 15 | 3 | 1 (1 ziyaret, 1.000 TL) | Denendi (v4) |
| I | Servis ve yedek cihaz süresinin **yazılı sözleşmede** olması (Ankara/İstanbul 1–2 gün, diğer 5 gün) | 3, 16 | 4 | 1 | **Eklenmeli** |
| J | Launca distribütörlük belgesinin gösterilmesi + Launca'nın büyük arızada doğrudan cihaz göndermesinin yazılı olması | 3, 17 | 4 | 1 | **Eklenmeli** |
| K | Yazılım lisansı ya da yıllık ücret olmadığının açıkça yazılması (doğruysa) | 10, 17 | 3 | 1 | **Teyit et, ekle** |
| L | Gerçek referans klinikler (isimleriyle) | 2 | 5 | 3 (F ile birlikte) | **Önce kazanılmalı, uydurulamaz** |
| M | Ankara laboratuvarlarından yazılı "Launca STL kabul ediyoruz" listesi | 1 | 5 | 2 | **Önce alınmalı** |
| N | Taksit (finansman ortağı ya da banka) | 4, 5 | 5 | ? | **Girişimci şu an mümkün değil dedi** |

### 3. Test edilen yığın (pitch v4)
`founder/pitch-v4.md`. Ana ürün, sonuç olarak anlatıldı ("Laboratuvar Onaylı Dijital Ölçü"). Eklenenler: B, C, D, E, F, G, H.

**Girişimci onayı gerekenler:** B, C, D, E, G, H henüz senin onayladığın maddeler değil. Panelde etkilerini görmek için test edildi. Gerçek teklife girmeden önce her birini teyit etmelisin.

### 4. Değer denklemi (1–10, Teklif merceği)
| Unsur | v3 teklifi | v4 yığını | Neyi değiştirdi |
| --- | ---: | ---: | --- |
| Hayal edilen sonuç | 6 | 6 | Değişmedi |
| Algılanan olasılık | 4 | 4 | Garanti (B) ekledi, ama referans ve yazılı laboratuvar listesi (L, M) olmadan güven artmadı |
| Sonuca ulaşma süresi | 6 | 6 | Değişmedi |
| Efor / fedakârlık | 5 | 6 | Kira mahsubu (E) ve ücretsiz kurulum (H) biraz düşürdü; taksit olmadığı için peşin ödeme engeli sürüyor |

### 5. Yeniden test sonucu (kısa panel)
Aynı 20 hekim (P001–P020, aynı kartlar, seed 393267). Önce v3 teklifi, sonra v4 yığını gösterildi.

| | v3 teklifi | v4 yığını |
| --- | ---: | ---: |
| **Alan** | **2 / 20** | **0 / 20** |
| Neden "güven" | 5 | 8 |
| Neden "fiyat" | 7 | 6 |
| Neden "alışkanlık" | 6 | 5 |
| Laboratuvar itirazı | 18 | 14 |
| Meslektaş / referans eksikliği | 6 | 11 |
| Distribütörün kalıcılığı | 10 | 14 |
| Taksit | 9 | 9 |

**Sonuç: Yığın satın alma oranını artırmadı. Bu küçük örnekte düştü (2'den 0'a).** 20 kişilik bir örnekte 2 kişilik fark gürültü olabilir; ama yön olumlu değil. v3'te kiralayan iki hekim (P002, P016) v4'te almadı:
- **P002:** "Servis ve yedek cihaz süreleri sözleşmede yazılı olsun, Ankara'da kullanan bir meslektaşla konuşayım."
- **P016:** "Peşinsiz 12–24 ay taksit ya da hasta başı 20–25 € kira."

**Neden işe yaramadı:**
1. **Laboratuvar itirazı azaldı (18 → 14).** Yani laboratuvar garantisi işe yaradı. Ama yerini güven itirazları aldı.
2. **Uzayan teklif yeni şüpheler doğurdu.** Kurucu klinik ("referans olmayı kabul edersiniz") ve 30 günlük garanti, hekimlere "henüz kullanan yok" ve "30 günden sonra ne olacak" sorularını hatırlattı. Referans eksikliği itirazı 6'dan 11'e, distribütör kalıcılığı 10'dan 14'e çıktı.
3. **Asıl iki engel teklifle çözülemiyor.** Taksit (girişimci şu an veremiyor) ve meslektaş referansı (henüz yok, uydurulamaz). Sadakat kartı gibi bonuslar bu engellere dokunmuyor.

Bu, "sorun teklifin süslerinde değil, kanıtta ve ödeme şeklinde" demek.

### 6. Öneri
**Satış metnini v3'te bırak** (`founder/pitch.md` v3'e geri alındı). v4 yığını `founder/pitch-v4.md` olarak saklandı.

Teklife bonus eklemek yerine şu üç gerçek kanıtı topla. Panel ve kurul en çok bunları istiyor:
1. **Laboratuvar listesi (M):** Ankara'da 2–3 laboratuvardan "Launca DL-300 STL dosyalarını kabul ediyoruz" yazısı.
2. **İlk referanslar (L):** 3–5 klinik. Gerekirse kurucu klinik fiyatıyla (F), ama teklif metnine değil, birebir görüşmede.
3. **Yazılı güvence (I, J, K):** Servis ve yedek cihaz sürelerinin sözleşmede olması, Launca distribütörlük belgesi ve (doğruysa) "yıllık yazılım ücreti yok."

**Kira mahsubu (E)** panelde 25 kişinin kendiliğinden istediği şeydi. Kısa testte tek başına bir şeyi değiştirmedi, ama düşük maliyetli olduğu için gerçek denemelerde test etmeye değer.

**Taksit (N)** konusu açık kalıyor. Üç panelde de en sık ikinci istek bu oldu. Bir banka ya da finansman şirketiyle konuşmak, teklife eklenebilecek en etkili madde olabilir.

### Sonraki adım
- `/founder-cfo`: kira mahsubu, kurucu klinik fiyatı ve garantilerin maliyetini, ayrıca kiralamanın ziyaret başına ekonomisini hesaplar. Eksik girdiler: euro/TL kuru, ziyaret başına tarama sayısı, beklenen aylık satış ve tarama sayısı, başlangıç harcamasının dağılımı.
- `/founder-marketing`: v3 teklifi ve itiraz listesiyle mesajları hazırlar.

## Pazarlama

Tarih: 27 Kasım 2026. Girdiler: `founder/panel/rapor.md` (panel v3, 100 simüle hekim), `founder/competitors.md`, `founder/pricing.md`, `founder/offer.md`, `founder/board.md`, girişimcinin verdiği maliyetler.

> **Eksik:** `founder/numbers.json` yok (`/founder-cfo` çalışmadı). Müşteri başına ödenebilecek tutar aşağıda yalnızca bilinen rakamlarla hesaplandı. Euro/TL kuru verilmediği için TL ve € ayrı gösterildi. Panel cevapları simülasyondur; reklamlarda müşteri yorumu olarak kullanılamaz.

### 1. Konumlandırma

**İlk kitle (panel v3'e göre):**
- **"Önce dener sonra alır" hekimler:** %42 alım, en yüksek grup.
- **Küçük ve yeni muayenehaneler:** %10, hepsi kiralamayı seçti.
- **Çok hekimli poliklinikler:** %10, hepsi satın almayı seçti.

**Ortak tetikleyici:** "Laboratuvarım dijital dosya istemeye başladı."

#### Üç versiyon
**A. Kiralama odaklı (küçük muayenehane)**
> Ankara'da laboratuvarı dijital dosya istemeye başlamış ama 5.000 €'yu peşin bağlamak istemeyen muayenehaneler için, [işin adı] cihaz almadan dijital ölçüye geçmenin yolu: randevuyla cihazla geliyoruz, sadece taradığınız hasta için ödüyorsunuz. Depoların taksitli satışından farklı olarak peşin ödeme, bakım ya da kullanılmayan cihaz yok.

**B. Satış odaklı (poliklinik)**
> Birden fazla hekimin çalıştığı poliklinikler için Launca DL-300, satın almadan önce kendi kliniğinizde ve kendi laboratuvarınızla denediğiniz kablosuz ağız içi tarayıcı. Distribütörden doğrudan servis ve Ankara/İstanbul'a 1–2 günde yedek cihaz.

**C. Laboratuvar onayı odaklı (şemsiye)** ← **önerilen**
> Laboratuvarı dijital ölçü istemeye başlamış Ankaralı diş hekimleri için, [işin adı] satın almadan ya da kiralamadan önce kendi laboratuvarınızın onayını alabildiğiniz tek ağız içi tarayıcı teklifi. Okunan 10 bayi sayfasının hiçbiri bunu açıkça sunmuyor. Az vakanız varsa hasta başı kiralayın, çok vakanız varsa satın alın.

**Neden C:**
- Panelde 84 hekim "laboratuvarım onaylarsa" dedi. 3 panelde de en sık "evet"e çevirme şartı bu.
- Alıcıların ortak tetikleyicisi laboratuvarın dijital dosya istemesi.
- Rakip araştırmasında hiçbir depo herkese açık bir "kendi laboratuvarınla dene" teklifi sunmuyordu (bkz. `founder/competitors.md`).
- A ve B, C'nin altında iki ayrı teklif olarak kalıyor. Böylece kurulun "satış mı kiralama mı" bölünmesine panelin verdiği cevap korunuyor: kiralama küçük muayenehaneye, satış polikliniğe.

**"Tek teklif" ifadesi hakkında:** Bunu reklamda ancak doğrulayabilirsen kullan. Doğrulamadan "tek" demek yanıltıcı olur. Güvenli versiyon: "Satın almadan önce kendi laboratuvarınızla deneyin."

### 2. Kanallar

| Kanal | Neden bu alıcıya uyuyor | Kaba maliyet | İşe yaradığını nasıl anlarsın | Karar |
| --- | --- | --- | --- | --- |
| **Diş laboratuvarları (ortaklık)** | Hekimlerin çoğu "laboratuvarım ne derse" diyor (laboratuvarına bağlı grup: 15/100). Laboratuvar hem onay veren hem yönlendiren taraf. | Düşük para, yüksek zaman. 2–3 laboratuvara demo ve STL testi. | Yazılı STL kabul yazısı; laboratuvarın yönlendirdiği deneme sayısı | **Başla** |
| **Saha ziyareti (klinik kapı kapı, randevulu demo)** | Ürün bir deneme ile satılıyor. "Önce dener" grubu %42 alım. Kiralama modeli zaten yerinde. | Ziyaret başına 1.000 TL (senin rakamın) | Haftalık ziyaret, deneme ve onaya geçiş sayısı | **Başla** |
| **Referans hekimler ve meslektaş ağı** | "Meslektaş tavsiyesiyle alan" grup üç panelde de %0: kanıt görmeden almıyorlar. Kurucu klinikler bu kanalı açar. | Kurucu fiyat indirimi (5 × 500 € = 2.500 €) | Referans olmayı kabul eden klinik sayısı; referanstan gelen deneme | **Başla** (ilk 5 klinik) |
| Instagram (reels) | Hekimler mesleki içerik takip ediyor. Deneme ve STL'nin laboratuvara gidişini gösteren kısa videolar güveni artırabilir. | Organik: zaman. Reklam: küçük test bütçesi. | DM ile gelen deneme talebi | Organik başla; reklamı 2. haftadan sonra küçük bütçeyle test et |
| Google Ads ("ağız içi tarayıcı fiyat", "intraoral tarayıcı kiralama Ankara") | Depolar fiyatı gizlediği için fiyat arayan hekim fiyatı açık bir sayfaya gelir. | Tıklama maliyeti bilinmiyor; küçük günlük bütçeyle test | Formdan deneme talebi başına maliyet | 2. hafta küçük test |
| Dental fuarlar ve oda etkinlikleri | Panelde birkaç hekim "fuarda denerim" dedi. | Stand pahalı, ziyaretçi olarak katılmak ucuz | Toplanan deneme randevusu | Takvime göre; bu 30 günde yok |
| WhatsApp gruplarına toplu mesaj | — | — | — | **Yapma.** İzinsiz grup mesajı güveni yıkar. Referans hekimlerin kendi paylaşımı farklıdır. |
| dentalilan ilanı | İkinci el arayan fiyat avcıları burada | Ücretsiz/düşük | İlandan gelen arama | Opsiyonel; fiyat avcısı grubu üç panelde de %0 |

**Yapmadıklarımız ve nedeni:** TikTok (bu alıcı orada değil), toplu e-posta listesi satın almak (KVKK riski ve soğuk liste), "fiyat avcısı" segmentine indirim kampanyası (üç panelde de %0 alım, marjı yer).

### 3. Mesajın cevaplaması gereken itirazlar (panel v3)
1. Laboratuvar dosyayı kabul eder mi? (84) → Laboratuvar onaylı deneme + laboratuvar listesi
2. Taksit yok (43) → Kira mahsubu (onaylarsan) + kiralamayla peşinsiz başlama
3. Meslektaş kullanıyor mu? (33) → Kurucu klinikler, gerçek referanslar
4. Distribütör kapanırsa? (53) → Distribütörlük belgesi, Launca'nın doğrudan cihaz göndermesi, yazılı servis süreleri
5. Klasik ölçü işimi görüyor (32) → Bulantı refleksli hastalar, tekrar ölçü, laboratuvar talebi

### 4. On kanca (reklam / reels)
Her biri bir itirazı cevaplıyor. Video kancaları ilk 3 saniyede okunacak cümleler.

| # | Kanca | Format | Cevapladığı itiraz |
| --- | --- | --- | --- |
| 1 | "Laboratuvarınız dijital dosya istemeye mi başladı? Tarayıcı almadan önce bunu izleyin." | Reels açılışı | Tetikleyici + laboratuvar |
| 2 | "Satın almadan önce kendi laboratuvarınıza sorun: STL'yi gönderin, onayı alın, sonra karar verin." | Reklam başlığı | Laboratuvar uyumu |
| 3 | "Ayda 3 vaka için 5.000 € bağlamayın. Sadece taradığınız hasta için ödeyin." | Reklam başlığı (kiralama) | Peşin ödeme |
| 4 | "Cihaz klinikte kalmıyor, siz tarıyorsunuz, biz odaya girmiyoruz." | Reels: randevulu ziyaretin baştan sona çekimi | Kiralama nasıl işliyor, mahremiyet |
| 5 | "Bulantı refleksi olan hastanızda ölçü almak zorsa..." | Reels açılışı | Klasik ölçü yeterli mi |
| 6 | "Tarayıcı bozulursa ne olur? Ankara'da 1–2 gün içinde yedek cihaz." | Reklam başlığı | Servis ve arıza |
| 7 | "Fiyatını saklamıyoruz: 4.950 € + KDV." | Google Ads başlığı | Depoların gizli fiyatı (fiyat şeffaflığı) |
| 8 | "Tekrar tarama ücretsiz. Aynı hastayı ikinci kez taramak için ödemezsiniz." | Kısa reklam metni | Kiralama maliyeti |
| 9 | "Launca Türkiye distribütörüyüz: servisi biz veriyoruz, büyük arızada üretici yeni cihaz gönderiyor." | Reels: belge ve depo çekimi | Distribütör kalıcılığı |
| 10 | "İlk vakanızı birlikte tarayalım: kurulum ve ilk taramada yanınızdayız." | Reels / saha broşürü | Kurulum ve eğitim (onaylarsan) |

Kurallar:
- **Fiyat:** 4.950 € fiyatı reklamda KDV hariç olduğu açıkça yazılarak kullanılmalı.
- **Garanti ve bonuslar:** Kanca 10 ve offer.md'deki garantiler ancak sen onaylarsan kullanılmalı.
- **Kıyaslama:** "Premium markaların yarısı" gibi rakip kıyaslamaları doğrulanmadan kullanılmamalı.
- **Mevzuat:** Türkiye'de tıbbi cihaz tanıtımı ve hekimlere yönelik reklam kurallarını (TİTCK ve ilgili mevzuat) bir uzmana teyit ettir. Bu hukuki tavsiye değildir.

### 5. Tarihli 30 günlük kampanya
**Önerilen lansman tarihi: 11 Ocak 2027 (Pazartesi).** Kurucu klinik programı 31 Ocak 2027'de bittiği için takvim buna göre kuruldu. Tarihi değiştirirsen tüm takvim kaydırılabilir. 1 Ocak resmî tatil olduğu için hafif tutuldu.

#### Lansman öncesi (L−14 → L−1)
| Tarih | Kanal | Ne yapılacak / mesaj |
| --- | --- | --- |
| 28 Ara Pzt | Laboratuvar | Ankara'da hedef 5 laboratuvarı listele, randevu iste. "Hekimlerinizden gelecek Launca STL'lerini test etmenizi istiyoruz." |
| 29 Ara Sal | Laboratuvar | 1. laboratuvar ziyareti: demo tarama, STL'yi laboratuvara ver |
| 30 Ara Çar | Laboratuvar | 2. laboratuvar ziyareti |
| 31 Ara Per | İçerik | Reels çekimi: kutudan çıkış, tarama, STL'nin laboratuvara gönderilişi (kanca 1, 4) |
| 1 Oca Cum | — | Resmî tatil |
| 2 Oca Cmt | İçerik | Instagram profilini kur: fiyat, deneme, kiralama nasıl işler, distribütörlük belgesi |
| 3 Oca Paz | — | Dinlenme / planlama |
| 4 Oca Pzt | Laboratuvar | 3. laboratuvar ziyareti; ilk iki laboratuvardan STL sonucunu al |
| 5 Oca Sal | Saha | Kurucu klinik adaylarının listesi (laboratuvarların yönlendirdiği 10–15 klinik) |
| 6 Oca Çar | Saha | İlk 3 aday kliniğe randevulu demo (kanca 2) |
| 7 Oca Per | İçerik | Laboratuvar onay yazısı geldiyse paylaşım taslağı (laboratuvarın izniyle) |
| 8 Oca Cum | Saha | 3 aday kliniğe daha demo |
| 9 Oca Cmt | İçerik | Reels: bulantı refleksli hasta senaryosu (kanca 5); hasta yüzü yok, izinli |
| 10 Oca Paz | Hazırlık | Teklif sayfası ve form hazır (fiyat açık, kanca 7) |

#### Lansman ve sonrası (L → L+16)
| Tarih | Kanal | Ne yapılacak / mesaj |
| --- | --- | --- |
| **11 Oca Pzt (L)** | Instagram + saha | Lansman: "Satın almadan önce kendi laboratuvarınızla deneyin" (kanca 2). Kurucu klinik davetleri birebir. |
| 12 Oca Sal | Saha | 3 klinik demosu; ücretsiz deneme başlat |
| 13 Oca Çar | Instagram | Reels: kiralama ziyareti baştan sona (kanca 4) |
| 14 Oca Per | Saha | 3 klinik demosu |
| 15 Oca Cum | Google Ads | Küçük günlük bütçeyle test: "ağız içi tarayıcı fiyat", "intraoral tarayıcı kiralama Ankara" (kanca 3, 7) |
| 16 Oca Cmt | Instagram | Reels: servis ve yedek cihaz (kanca 6) |
| 17 Oca Paz | — | Haftalık ölçüm: deneme, laboratuvar onayı, ödeme |
| 18 Oca Pzt | Saha | Deneme yapan kliniklerin STL sonuçlarını takip et; onay gelenlere teklif |
| 19 Oca Sal | Saha | 3 yeni klinik demosu |
| 20 Oca Çar | Instagram | Reels: distribütörlük ve Launca güvencesi (kanca 9) |
| 21 Oca Per | Saha | Kurucu klinik görüşmeleri (referans anlaşması) |
| 22 Oca Cum | Instagram reklam | İlk küçük reklam testi: kanca 1 ve 3, Ankara diş hekimleri hedefli |
| 23 Oca Cmt | İçerik | Reels: tekrar tarama ücretsiz (kanca 8) |
| 24 Oca Paz | — | Haftalık ölçüm; Google Ads'te tıklama başına deneme maliyetine bak |
| 25 Oca Pzt | Saha | "Kurucu klinik programı 31 Ocak'ta bitiyor" hatırlatması, birebir (gerçek tarih) |
| 26 Oca Sal | Saha | Son kurucu klinik görüşmeleri |
| 27 Oca Çar (L+16) | Değerlendirme | 30 günün sonuçları: hangi kanal deneme getirdi, hangi kanca DM aldı. Kazananı ölçekle, kaybedeni durdur. |

**Yeni bir şey yokken paylaşılacaklar:** laboratuvarın STL'yi açtığı ekran (izinli), depo ve yedek cihaz rafı, kalibrasyon ve temizlik rutini, ziyaret öncesi hazırlık, ilk tarama eğitiminden kısa bölümler.

**Açılış teklifi:** Kurucu klinik programı. İlk 5 kliniğe 4.450 € + KDV, referans karşılığı, **31 Ocak 2027'ye kadar**. `founder/offer.md` sonucuna göre bu, reklam metnine değil **birebir görüşmeye** konmalı.

### 6. Bütçe (öneri, onayına bağlı)
Toplam pazarlama bütçesi belirlenmedi. Kanallar arası dağılım için bir öneri, 30 günlük bütçenin yüzdesi olarak:

| Kalem | Pay | Not |
| --- | ---: | --- |
| Saha ziyaretleri ve demolar | %45 | Ziyaret başına 1.000 TL. Ziyaret sayısını bütçe belirler. |
| Kurucu klinik indirimi | %20 | 5 × 500 € = 2.500 € (satıştan düşülür, nakit çıkışı değil) |
| İçerik üretimi (reels çekimi) | %15 | Telefonla çekim yeterli; profesyonel çekim şart değil |
| Google Ads testi | %10 | Küçük günlük bütçe, 2 hafta |
| Instagram reklam testi | %10 | Sadece kazanan kancalar |

Kesin tutarlar `/founder-cfo` ile ve kurdan sonra belirlenmeli.

### 7. Müşteri başına ödeyebileceğin en fazla tutar
**Satış (cihaz başına):**
- Brüt kalan: 4.950 € − 2.700 € = **2.250 €** (kurucu fiyatta 1.750 €)
- Panelde satın alanlar ilk ayda 1 cihaz aldı. Bir alıcı = 1 cihaz.
- **Teorik tavan: 2.250 €.** Bu tutarı harcarsan o satıştan hiç para kalmaz; servis, yedek cihaz ve sabit giderler (aylık 100.000 TL) karşılanmaz.
- **Önerilen sınır: brüt kalanın en fazla üçte biri, yaklaşık 750 €.** Kalan tutar servis, garanti ve sabit giderleri taşır. Kesin oranı CFO belirlemeli.

**Kiralama (klinik başına):**
- Tarama başına kalan = 50 € − (1.000 TL ÷ ziyaret başına tarama sayısı). Kur ve ziyaret başına tarama sayısı bilinmediği için sayıya çevrilemedi.
- Panelde kiralayanlar ilk ayda 2 tarama dedi (P016, P075, P089).
- **Formül:** Klinik başına en fazla edinme maliyeti = tarama başına kalan × aylık tarama × beklenen müşteri süresi (ay) × üçte bir.
- Kurla ve ziyaret başına tarama sayısıyla `/founder-cfo` bunu tek bir TL rakamına çevirecek.

### 8. Haftalık izlenecek üç sayı
| Sayı | Ne demek | "Bir şeyi değiştir" eşiği |
| --- | --- | --- |
| **Demo → ücretsiz deneme** | Ziyaret edilen kliniklerin kaçı denemeye başladı | %30'un altı: mesaj ya da hedef klinik yanlış |
| **Deneme → laboratuvar onayı** | Denemedeki STL'lerin kaçı laboratuvardan onay aldı | %70'in altı: laboratuvar ortaklığı ya da tarama eğitimi sorunu |
| **Onay → ödeme (satış ya da ilk kira)** | Onay alan kliniklerin kaçı ödedi | %25'in altı: engel teklif ya da ödeme şekli (taksit) |

Bu eşikler başlangıç tahminidir. İlk iki haftanın gerçek verisiyle güncellenmeli.

### Sonraki adım
- `/founder-cfo`: müşteri edinme sınırını ve bütçeyi kesin sayılara çevirir.
- `/founder-brand`: işin adı, ses tonu ve görünüm. Konumlandırmada "[işin adı]" bunun için boş bırakıldı.
- `/founder-launch`: lansman günü planı.

## Lansman planı

Tarih: 27 Kasım 2026. Girdiler: `founder/marketing.md` (lansman 11 Ocak 2027 önerisi, 30 günlük takvim), `founder/pricing.md`, `founder/offer.md`, `founder/panel/rapor.md`, `founder/board.md`, girişimcinin verdiği bilgiler.

> **Eksik:**
> - `founder/ops.md` yok (`/founder-ops` çalışmadı). Tedarik süreleri ve izinler girişimcinin verdiği bilgilerden alındı; teyit edilmesi gerekenler işaretlendi.
> - `founder/numbers.json` yok (`/founder-cfo` çalışmadı). Başa baş noktası kur bilinmediği için formül olarak verildi.
>
> Tarihler öneri; lansman tarihini değiştirirsen tüm plan kayar.

### 1. Önce ucuz bir gerçek test: "Ankara Pilot"
Kafede pop-up stand ya da tadım günü ne ise, bu işte gerçek hekimin kendi kliniğinde, kendi laboratuvarıyla yaptığı denemedir. Panel %7 dedi; bu bir üst sınır. Gerçek hekimler ne diyor, büyük para çıkmadan önce bunu görmek gerekiyor.

**Ne zaman:** 30 Kasım – 20 Aralık 2026 (3 hafta).
**Maliyet:** Sadece ziyaretler (1.000 TL/ziyaret) ve zaman. Elindeki demo cihaz ve yedek cihaz yeterli; **yeni stok alma.**

#### Testin iki parçası
**a) "Laboratuvarda Tarama Günü" (tadım gününün karşılığı)**
- 1 ortak laboratuvarda yarım günlük bir açık gün: 8–10 hekim davet edilir.
- Hekimler cihazı birbirleri üzerinde (gönüllü) dener. STL dosyası laboratuvarın ekranında anında açılır.
- Sonunda herkese kendi kliniğinde ücretsiz deneme randevusu teklif edilir.
- Maliyet: ikram ve davet; laboratuvarın mekânı.
- Hedef tarih: **12 Aralık 2026 (Cumartesi).**

**b) Klinikte pilot**
- Laboratuvarların yönlendirdiği 15 kliniğe randevulu demo ve ücretsiz deneme.
- Deneme taramalarının STL'leri hekimin kendi laboratuvarına gönderilir.
- Onay gelirse gerçek fiyatla teklif:
  - küçük muayenehaneye kiralama (50 €/hasta)
  - polikliniğe satış (4.950 € ya da kurucu klinik fiyatı 4.450 €)

#### Başarı çizgisi (testten önce yazıldı)
| Adım | Hedef (15 demodan) | Panelin öngördüğü |
| --- | ---: | --- |
| Demo → ücretsiz deneme | ≥ 8 klinik | Panelde çoğu "denerim" dedi |
| Deneme → laboratuvar onayı | ≥ 6 klinik | — |
| Onay → ödeme (ilk kira ya da satış) | **≥ 2 klinik** | %7 (üst sınır) |
| Referans olmayı kabul eden | ≥ 1 klinik | — |

**Karar kuralı:**
- **2 ya da daha fazla ödeyen klinik varsa:** Lansmana devam. Laboratuvara yönlendirilmiş klinikler genel panelden daha sıcak bir kitle olduğu için bu hedef panelden yüksek tutuldu.
- **1 ödeyen klinik varsa:** Lansmana devam, ama itiraz notlarını `/founder-offer`'a götür.
- **15 demodan hiç ödeyen yoksa:** Lansmanı ertele. Gerçek alıcılara güven, panele değil. `/founder-offer` ve `/founder-pricing` ile taksit, kira fiyatı ya da hedef segmenti değiştir.

**Test boyunca toplanacak:** her klinikten "neden aldı, neden almadı" notu (kendi cümleleriyle), laboratuvarın STL hakkındaki yazılı yorumu, ziyaret başına kaç hasta tarandığı. Bu son bilgi CFO için gerekiyor.

### 2. Geri sayım (27 Kasım 2026 → 11 Ocak 2027)
Sorumlu: aksi yazmadıkça **sen**. ★ = kritik yol (kayarsa lansman tarihi kayar).

#### Hafta 1: 27 Kas – 6 Ara
| Görev | Sorumlu | Son tarih |
| --- | --- | --- |
| ★ Ankara'da 5 laboratuvarla randevu, demo tarama, STL testi | Sen | 4 Ara |
| ★ Satış ve kiralama sözleşmesi taslağı: servis ve yedek cihaz süreleri, tekrar tarama, ücret, iptal | Sen + avukat | 6 Ara |
| Tıbbi cihaz satışı için gereken kayıtları teyit et (ör. ÜTS, Ürün Takip Sistemi; distribütör olarak muhtemelen zaten var) | Sen + muhasebeci | 6 Ara |
| Tarayıcının KDV oranını teyit et | Muhasebeci | 6 Ara |
| **KVKK:** Kiralamada taramalar senin cihazında kalıyor, yani hasta verisi. Cihazdaki verinin nasıl silineceği ve hekime nasıl aktarılacağı için yazılı bir süreç ve aydınlatma metni hazırla. | Sen + avukat | 6 Ara |
| Pilot için 15 klinik listesi (laboratuvar yönlendirmesiyle) | Sen | 6 Ara |

#### Hafta 2: 7 – 13 Ara
| Görev | Sorumlu | Son tarih |
| --- | --- | --- |
| ★ Pilot demoları: haftada en az 5 klinik | Sen | 13 Ara |
| ★ "Laboratuvarda Tarama Günü" | Sen + ortak laboratuvar | **12 Ara** |
| Launca'dan distribütörlük belgesi ve "büyük arızada doğrudan cihaz" taahhüdünü yazılı al | Sen + Launca | 13 Ara |
| Yazılımda yıllık lisans ücreti olup olmadığını Launca'ya teyit ettir | Launca | 13 Ara |

#### Hafta 3: 14 – 20 Ara
| Görev | Sorumlu | Son tarih |
| --- | --- | --- |
| ★ Pilot demolarının kalanı ve deneme takibi | Sen | 20 Ara |
| ★ En az 2 laboratuvardan yazılı "Launca STL kabul ediyoruz" | Sen | 20 Ara |
| `/founder-brand`: işin adı, logo, Instagram profili | Sen | 20 Ara |
| `/founder-cfo`: kur, ziyaret başına tarama sayısı ve pilot verisiyle | Sen | 20 Ara |

#### Hafta 4: 21 – 27 Ara (karar haftası)
| Görev | Sorumlu | Son tarih |
| --- | --- | --- |
| ★ **Pilot değerlendirmesi: başarı çizgisine göre devam ya da ertele kararı** | Sen | **23 Ara** |
| Devam kararıysa stok kararı: kiralama ve yedek için kaç cihaz? (CFO'ya göre; talep kanıtlanmadan fazla stok alma) | Sen | 27 Ara |
| Teklif sayfası ve formu (fiyat açık) | Sen | 27 Ara |
| Kurucu klinik sözleşmesi (referans şartları) | Sen + avukat | 27 Ara |

#### Hafta 5–6: 28 Ara – 10 Oca (lansman öncesi pazarlama)
- `founder/marketing.md` takvimi L−14'ten itibaren uygulanır: laboratuvar ziyaretleri, içerik çekimi, kurucu klinik adayları, profil ve sayfa hazırlığı.
- **★ Yumuşak açılış: 7 Ocak 2027 (Perşembe).** Pilotta onay veren klinikler ve ortak laboratuvarlar için ilk gerçek kiralama ziyaretleri ve ilk satış teslimatı. Süreç uçtan uca denenir: randevu → ziyaret → tarama → STL → laboratuvar → fatura.
- Son kontrol 10 Ocak: sözleşmeler imzaya hazır mı, yedek cihaz şarjlı ve kalibreli mi, form çalışıyor mu?

#### Kritik yol özeti
Laboratuvar STL onayları → pilot sonucu (23 Ara) → sözleşmeler ve KVKK süreci → yumuşak açılış (7 Oca) → **lansman (11 Oca)**.

Laboratuvar onayları ya da sözleşmeler gecikirse lansman da gecikir. Pilot başarısızsa lansman ertelenir; bu bir başarısızlık değil, büyük harcamadan önce alınmış bir sonuç.

### 3. Lansman günü: 11 Ocak 2027 (Pazartesi)
| Saat | Ne | Kanal / yer | Not |
| --- | --- | --- | --- |
| 08:00 | Cihazların şarj ve kalibrasyon kontrolü, yedek cihaz arabada | — | Risk: cihaz arızası → yedek cihaz hazır |
| 08:30 | Lansman paylaşımı: "Satın almadan önce kendi laboratuvarınızla deneyin" (kanca 2) | Instagram | Fiyat KDV hariç yazılı |
| 09:00 | Ortak laboratuvarlara teşekkür ve "bugün başladık" mesajı; hekim yönlendirmesi rica | Telefon / WhatsApp (birebir) | Toplu grup mesajı yok |
| 09:30–12:00 | 2 randevulu demo / deneme | Klinikler | Ziyaret başına tarama sayısını not et |
| 12:00 | Kurucu klinik davetleri, birebir (31 Ocak son tarih, 5 kontenjan) | Telefon / yüz yüze | Reklamda değil, birebir |
| 13:30–17:00 | 2 randevulu demo / deneme + 1 kiralama ziyareti (yumuşak açılıştan) | Klinikler | Taramadan sonra cihazdaki verinin KVKK sürecine göre aktarılıp silinmesi |
| 17:30 | Gün sonu kaydı: demo, deneme, STL gönderimi, gelen DM ve form | Tablo | |
| 18:00 | Reels: "İlk gün: X klinikte tarama yaptık" (gerçek sayıyla, hasta görüntüsü yok) | Instagram | Abartı yok |

**Bir şey bozulursa:**
- **Cihaz arızası:** Yedek cihaz kullanılır. Ziyaret ertelenecekse hekime aynı gün yeni saat teklif edilir.
- **Randevuya geç kalma:** Hekim önceden aranır. Gecikme garantisini onaylamışsan uygulanır.
- **Laboratuvar STL'yi açamazsa:** Laboratuvarla aynı gün iletişim kurulur, dosya formatı ve ayarlar kontrol edilir. Sorun çözülmeden o klinikte satış kapatılmaz.
- **Form ya da sayfa çalışmazsa:** Telefon numarası her paylaşımda yazılı olsun.

### 4. İlk 30 gün (11 Ocak – 10 Şubat 2027)
#### Haftalık izlenecek sayılar
| Sayı | Eşik: "bir şeyi değiştir" | Kaynak |
| --- | --- | --- |
| Demo → ücretsiz deneme | %30 altı | marketing.md |
| Deneme → laboratuvar onayı | %70 altı | marketing.md |
| Onay → ödeme | %25 altı | marketing.md |
| Aylık kiralama taraması ve ziyaret başına tarama | Ziyaret başına 1'in altı (1.000 TL ziyaret maliyeti tek taramayla karşılanıyor mu?) | Girişimci verisi; CFO kesinleştirecek |
| Satılan cihaz / ay | Başa baş noktasının altı (aşağıda) | CFO |

**Başa baş (kaba, CFO kesinleştirecek):**
- Aylık sabit gider 100.000 TL.
- Satışta cihaz başına brüt kalan 2.250 €.
- **Ayda gereken satış = 100.000 TL ÷ (2.250 € × €/TL kuru)**, kiralama gelirinden önce.
- Kur verilmediği için sayıya çevrilmedi.

#### Değerlendirme günleri
**7. gün (17 Ocak)**
- Pilottaki dönüşüm oranları lansmanda da tutuyor mu?
- En çok hangi itiraz duyuldu? Panelle aynı mı (laboratuvar, taksit, referans)?
- Ziyaret başına ortalama kaç hasta tarandı?

**14. gün (24 Ocak)**
- Hangi kanal deneme getirdi: laboratuvar, saha, Instagram, Google?
- Kazanmayan kanalı durdur, kazananı iki katına çıkar.
- Kurucu klinik kontenjanı kaç doldu? Referans olmayı kabul eden var mı?

**30. gün (10 Şubat)**
- Toplam satış, kiralama yapan klinik sayısı, kiralama taraması, toplam gelir. Sabit giderin ne kadarı karşılandı?
- Gerçek dönüşüm oranı panelin %7'siyle nasıl karşılaştırılıyor?
- Kiralama, ziyaret maliyetini karşılıyor mu? Karşılamıyorsa minimum tarama sayısı ya da fiyat değişikliği gerekiyor mu?
- Taksit talebi devam ediyor mu? Finansman ortağı aranmalı mı?
- Sonraki 60 gün için: ikinci cihaz alınmalı mı, yoksa mevcut kapasite yetiyor mu?

### Sonraki adım
- `/founder-cfo`: başa baş noktasını ve stok kararını kesin sayılarla verir. Kur, ziyaret başına tarama sayısı, beklenen aylık satış ve tarama sayısı, başlangıç harcamasının dağılımı gerekiyor.
- `/founder-ops`: sözleşme, KVKK süreci, servis ve yedek cihaz rutinlerini yazar.
- `/founder-plan`: hepsini tek bir iş planında birleştirir.

## Henüz yapılmayanlar

- Rakamlar: `/founder-cfo`
- Marka: `/founder-brand`
- Operasyon: `/founder-ops`

_Panel simüle alıcılardan oluşuyor; rakamlar girdilerinden yapılan projeksiyonlar. Para harcamadan önce talebi gerçek müşterilerle, maliyetleri gerçek tekliflerle doğrula. Finansal, hukuki ya da vergi tavsiyesi değildir._
