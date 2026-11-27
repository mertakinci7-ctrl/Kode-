# Kurul kararı v3: Ağız İçi Tarayıcı Satış ve Kiralama

Tarih: 27 Kasım 2026. Önceki kararlar: `founder/board-v1/board.md`, `founder/board-v2/board.md`.

## 1. Oy
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

## 2. Birden fazla üyenin dile getirdiği riskler
1. **Kanıt yok (3/3).** Laboratuvarlardan yazılı STL kabulü yok, referans hekim yok, işin adı yok. Son teklif (randevulu kiralama) panelde hiç test edilmedi. Teklif merceğine göre tekliflerin en çok battığı yer burası.
2. **Kiralama tek kişiye bağlı ve ölçeklenmiyor (3/3).** Hekimin hastası koltuktayken cihaz yolda olabilir. Sen hastalanırsan ya da izne çıkarsan hizmet duruyor. Bir ziyaretin yol ve zaman maliyeti bilinmediği için 50 €'nun kâr bırakıp bırakmadığı da bilinmiyor.
3. **Satış tarafı fiyat yarışına kayıyor (Teklif + Tekel).** Münhasırlık yok: Launca ikinci bir distribütör atayabilir, cihaz gri pazardan da gelebilir. Rakipler taksit veriyor, sen veremiyorsun (34 itiraz). "Daha ucuz ama peşin" teklifi hekimin "hayır" demesini kolaylaştırıyor.
4. **Laboratuvar ile klinik arasındaki devir kanıtlanmadı (Ürün + Teklif).** Hekimin asıl satın aldığı şey tarayıcı değil, laboratuvarın sorunsuz kabul ettiği bir ölçü. Burada bir kusur çıkarsa suç cihaza yazılır.

## 3. Koşullar: kontrol listesi
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

## 4. Üyeler arasındaki ayrılık
Kurul en temel soruda bölündü: **hangi kol ana iş?**
- **Ürün merceği satışı seçiyor.** Panelde alan 6 kişiden 5'i satın almayı seçti; kiralama girişimcinin takvimini tüketiyor. Ona göre kiralama ya kesilmeli ya da süre ve kapasite sınırı olan bir "satın almadan önce deneme yolu" olarak yeniden tanımlanmalı.
- **Tekel merceği kiralamayı seçiyor.** Satışta hiçbir koruma yok, ürün emtia. "Küçük pazarda büyük pay" başlangıcı yalnızca Ankara'daki hasta başı kirada görünüyor. Ama sadece bir kilit (münhasırlık ya da laboratuvar anlaşmaları) ve girişimciden bağımsız bir ölçek planı varsa fonlar.
- **Teklif merceği ikisini birden tutuyor.** Farkı fiyatta değil yığında görüyor: garanti, eğitim, laboratuvar kurulumu, kiradan satışa mahsup. Bu yığın varsa her iki kol da işler.

Bu ayrılığı kurul çözemiyor. Kiralamanın ekonomisi (`/founder-cfo`) ve son teklifin panel sonucu (`/founder-consumer`) çözecek.

## 5. Kurulun görebildiği en güçlü versiyon
Bu, anlattığın modelden farklı. En güçlü versiyon iki ayrı iş değil, tek bir huni:
- **Ana gelir satış.** Çok hekimli polikliniklere, adı konmuş bir teklifle satılıyor: ücretsiz deneme, laboratuvar onaylı STL, eğitim, 1–2 gün yedek cihaz ve "laboratuvar kabul etmezse iade" garantisi.
- **Ankara'daki hasta başı kiralama huninin girişi.** Peşin ödeyemeyen ya da emin olamayan hekim önce kiralıyor. Ödediği kiralar satın almaya geçince fiyattan düşülüyor. Böylece taksidin işlevi senin ek finansman riskin olmadan görülüyor.
- **Hendek laboratuvarlar.** Hekimin çalıştığı 2–3 Ankara laboratuvarıyla yapılmış yazılı STL kabul ve yönlendirme anlaşmaları ve ilk referans hekimler. Münhasırlık alınabilirse ikinci kilit olur.

Bu versiyon Ürün merceğinin "satış ana iş" görüşüyle, Tekel merceğinin "laboratuvar anlaşmaları kilit olur" görüşünü birleştiriyor. Kiralamanın kapasite sorunu da huni girişi olduğu için daha az önem taşıyor.

---
*Kurul üyeleri yayımlanmış iş çerçevelerini uygulayan mercekler, gerçek kişiler değil. Bu değerlendirme finansal, hukuki ya da vergi tavsiyesi değildir.*
