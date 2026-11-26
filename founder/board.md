# Yönetim Kurulu Kararı — Ağız İçi Tarayıcı Kiralama ve Satış

## 1. Oylama
**3 ŞARTLI FONLA, 0 FONLA, 0 GEÇ — ortalama puan 4,0 / 10**

| Lens | Puan | Oy | Tek cümlelik gerekçe |
| --- | --- | --- | --- |
| Offers | 4 | ŞARTLI FONLA | Teklif şu an "cihaz + fiyat"; paket, garanti ve kanıt yok, yani emtia. |
| Monopoly | 4 | ŞARTLI FONLA | Ürün başkasının, sır yok; münhasırlık yoksa altı ayda fiyat savaşına döner. |
| Ürün | 4 | ŞARTLI FONLA | İşin "tek şeyi" belli değil: kiralama mı, satış mı? |

Kimse fikri reddetmedi, ama kimse olduğu haliyle de fonlamıyor. Bu puan "fikir kötü" değil, "fikir henüz bir iş değil, sadece bir ürün" demek.

## Güncelleme — kiralama birimi: hasta başı 50 € + KDV
Kurucu, kiralamanın **hasta başı** olduğunu netleştirdi. Bu, kurulun iki senaryosundan (günlük/aylık) farklı, üçüncü bir model: **kullandıkça öde.** Üyelerin puanları bilinmeyen birime göre verildi; aşağıdaki not başkanın, yalnızca verilen fiyatlarla yaptığı değerlendirmedir.

**Ne değişti (lehte):**
- 4.950 € / 50 € = **99 hasta**. Ayda 99'dan fazla tarama yapan bir klinik için satın almak daha ucuz hale gelir. Yani yoğun klinik doğal olarak satışa döner, az tarama yapan klinik kirada kalır. Bu, kurulun "kiralama satışın önündeki deneme kapısıdır" önerisiyle örtüşüyor ve aylık senaryodaki "kiralama satışı yer" riskini büyük ölçüde ortadan kaldırıyor.
- Hekim için risk çok düşük: hastası yoksa ödemiyor. Offers lensinin değer denklemindeki "çaba ve fedakârlık" kısmı küçülüyor.
- Fiyat hekimin kendi hasta ücretine bağlanabildiği için satılması kolay bir cümle: "Taramayı hastaya yansıtın, cihaz parası ödemeyin."

**Ne yeni risk getirdi:**
1. **Kullanım nasıl ölçülecek?** Cihaz klinikte kalıyorsa, hasta sayısı hekimin beyanına mı, cihaz/yazılım kayıtlarına mı dayanacak? Launca yazılımının tarama sayısını size raporlayıp raporlamadığı bilinmiyor. Ölçülemeyen kullanım eksik beyan ve tahsilat sorunu demek.
2. **Cihaz klinikte boşta kalırsa geliriniz sıfır.** Gelir, kliniğin hasta sayısına bağlı; cihaz başına aylık asgari kullanım olmadan nakit akışı öngörülemez. Asgari aylık hasta sayısı veya sabit taban ücret gerekip gerekmediği `/founder-cfo` ile hesaplanmalı.
3. **Cihaz randevu başına getiriliyorsa** iş, hasta başı bir teknisyen/ulaşım operasyonuna döner ve 50 €'nun ne kadarının bu maliyete gideceği bilinmiyor (`/founder-ops`, `/founder-cfo`).
4. **Hijyen ve sarf:** Hasta başı kullanımda tarayıcı uçlarının sterilizasyonu ya da tek kullanımlık sarf maliyetinin kimde olduğu tanımlanmalı.

**Kontrol listesine eklenenler:**
- [x] Kiralama birimi netleşti: hasta başı.
- [ ] Cihazın klinikte mi kalacağı, randevu başına mı getirileceği seçilecek.
- [ ] Hasta sayısının nasıl ölçüleceği ve faturalanacağı yazılacak (yazılım kaydı, beyan, denetim hakkı).
- [ ] Cihaz başına asgari aylık kullanım veya taban ücret gerekip gerekmediği hesaplanacak. → `/founder-cfo`
- [ ] Kiradan satışa geçiş kuralı yazılacak (ör. ödenen hasta ücretlerinin bir kısmının satış fiyatından düşülmesi). → `/founder-offer`
- [ ] Uç sterilizasyonu / sarf maliyetinin sorumlusu belirlenecek. → `/founder-ops`

**Başkanın görüşü:** Hasta başı model, kurulun ortak bulduğu en büyük riski (kiralama birimi) olumlu yönde çözüyor; ortalama puanın yeniden oylamada yükselmesi beklenir. Ama işin kaderi artık "kullanımı güvenilir şekilde ölçüp tahsil edebilmek" ve "Launca yetkisi" sorularına bağlı.

## 2. Birden fazla üyenin çıkardığı riskler (önce bunlar)
1. **Kiralama biriminin belirsizliği (3/3 üye).** 4.950 € / 50 € = 99 birim.
   - *Günlük ise:* Cihaz 99 kiralama gününde (kesintisiz kiralanırsa ~3,3 ay) satış fiyatını geri getirir. Model çalışabilir, ama iş her gün tekrarlanan bir lojistik, temizlik, kalibrasyon ve hasar operasyonuna döner. Doluluk oranı bilinmiyor.
   - *Aylık ise:* 99 ay (~8,25 yıl). Cihaz büyük ihtimalle bu sürede eskir, müşterinin satın almak için nedeni kalmaz ve kiralama satışı yer. Kurul bu senaryoda modeli zarar ettirici görüyor.
2. **Launca ile ilişki ve yasal yetki belirsiz (3/3 üye).** Yetkili distribütör/bayi olup olmadığınız, bölgesel münhasırlık, garanti ve yazılım lisansının devri, tıbbi cihaz kayıt durumu bilinmiyor. Bu olmadan ne garanti verilebilir ne de kopyalanmaya karşı bir koruma vardır.
3. **Fiyat dışında bir fark yok, emtia riski (Offers + Monopoly).** Aynı cihazı satabilen herkes aynı teklifi verebilir; tek fark fiyat olursa marj erir.
4. **Hizmet zinciri sahipsiz (Offers + Ürün).** Değer cihazda değil; kurulum, eğitim, laboratuvara ilk dosya, arızada yedek cihaz zincirinde. Ekip ve servis kabiliyeti tanımlı değil. Kötü bir ilk tarama deneyimi son deneyim olur.
5. **Talep ve dağıtım kanıtı yok (3/3 üye).** İlk müşterilerin nereden geleceği, hangi şehirde başlanacağı ve hekimin almak mı kiralamak mı istediği bilinmiyor.

Ayrıca: 750.000 TL'nin kaç cihaz ettiği, € alış maliyeti, kur, gümrük ve kayıt giderleri bilinmeden hesaplanamıyor. Kurul burada sayı uydurmadı; bunu **/founder-cfo** cevaplayacak.

## 3. "Şu şartla fonlarım" — birleştirilmiş kontrol listesi
Sonraki skill'ler bunların çoğunu test edecek.

- [ ] **Kiralama birimi yazılı olarak netleşecek** (gün / hafta / ay). *(3 üye)*
- [ ] **Cihaz başına geri dönüş süresi** gerçek alış maliyeti, kur ve gümrükle hesaplanacak; geri dönüş süresi cihaz ömrünün yarısını aşıyorsa kira fiyatı yeniden kurgulanacak (ör. asgari süre, ödenen kiranın satıştan düşülmesi). → `/founder-cfo` *(3 üye)*
- [ ] **İlk 6 ay için tek ana model seçilecek**, örneğin "satışa dönüşen deneme kiralaması" ya da "yalnızca satış"; seçim iki senaryonun karşılaştırmasıyla gerekçelendirilecek. → `/founder-cfo` *(Ürün)*
- [ ] **Launca veya yetkili Türkiye distribütöründen yazılı satış/kiralama yetkisi**, garanti ve yazılım lisansı devri, cihazın tıbbi cihaz kayıt durumu belgelenecek. *(3 üye)*
- [ ] **En az bir şehir/bölge için yazılı bayilik veya münhasırlık** sağlanacak. *(Monopoly)*
- [ ] **İsimli, yazılı bir paket ve garanti:** kurulum, eğitim, ilk vaka desteği, saat olarak tanımlı yedek cihaz süresi; garantinin maliyeti karşılanabilir bulunacak. → `/founder-offer`, `/founder-cfo` *(Offers + Ürün)*
- [ ] **Tek sayfalık deneyim haritası:** teslimden iadeye / satış sonrası ilk 30 güne kadar her adım ve sorumlusu; en az bir yedek cihaz ayrılacak. → `/founder-ops` *(Ürün)*
- [ ] **Talep kanıtı:** seçilen tek şehirde en az 10 hekim veya laboratuvardan ön sipariş, depozito ya da imzalı kiralama niyeti. → `/founder-consumer`, `/founder-launch` *(Offers + Monopoly)*
- [ ] **Pilot:** en az 5 hekim/laboratuvar; en az 3'ü ilk taramayı yardımsız tamamlayıp dosyayı laboratuvara başarıyla gönderecek. *(Ürün)*
- [ ] **Rakip haritası:** aynı şehirde ağız içi tarayıcı satan ve kiralayan herkes, fiyatlarıyla. Kiralama yapan doğrudan rakip yoksa niş doğrulanmış sayılacak. → `/founder-competitors` *(3 üye)*
- [ ] **Kademeli bütçe:** 750.000 TL'nin tamamı baştan stoğa bağlanmayacak; ilk dilim yetki belgesi ve talep kanıtı sağlandıktan sonra açılacak. *(Offers + Monopoly)*

## 4. Kurulun görebildiği en güçlü versiyon
Kurulun gördüğü en güçlü iş, sizin sunduğunuzdan biraz farklı: **"tarayıcı satan bir bayi" değil, tek bir şehirde "dijital ölçüye geçişi garanti eden hizmet."** Kiralama ayrı bir gelir kalemi olarak değil, satışın önündeki deneme kapısı olarak kurgulanır: hekim cihazı kısa bir süre kiralar, kurulum, eğitim ve laboratuvara ilk dosyanın gönderilmesi sizin sorumluluğunuzdadır, arızada belirli saat içinde yedek cihaz gelir ve ödediği kira satın alırsa fiyattan düşülür. Bu yapı aylık 50 € senaryosunun kendini yeme sorununu çözer, fiyat dışında bir fark (hizmet ve risk almama) yaratır ve kiralama filosunu en ucuz müşteri kazanma kanalına çevirir. Kalıcılık ürüne değil, yazılı bölgesel yetkiye ve yerel hizmet ününe dayanır.

## Kurulun anlaşamadığı noktalar
- **Kiralamanın yeri:** Monopoly lensi kiralamayı "sahiplenilebilecek küçük pazar" ve işin en değerli kısmı olarak görüyor. Ürün lensi ise ilk 6 ayda kiralama ve satıştan birinin dışarıda bırakılabileceğini, hatta "yalnızca satış"ın da geçerli bir seçenek olduğunu söylüyor.
- **Kalıcılık nereden gelir:** Monopoly lensi önceliği yazılı münhasırlığa veriyor. Offers lensi teklif paketi ve garantiye, Ürün lensi deneyimin dikişsiz olmasına veriyor. Üçü de gerekli, ama ilk paranın hangisine gideceği sizin kararınız.
- **Hedef müşteri genişliği:** Ürün lensi ilk aşamada hekim veya laboratuvardan birinin dışarıda kalmasını öneriyor; diğer iki lens ikisini birlikte kabul ediyor.

---
Ayrıntılar: `founder/board/offers.md`, `founder/board/monopoly.md`, `founder/board/product.md`. Lensler yayımlanmış çerçevelerin özetidir; kurul üyeleri o kişiler değildir ve onlar adına konuşmaz.
