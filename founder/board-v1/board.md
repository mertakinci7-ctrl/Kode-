# Kurul kararı: Ağız İçi Tarayıcı Satış ve Kiralama

## 1. Oy
**2 şartlı fonla, 1 geç.** Ortalama puan: **3,7 / 10** (Teklif 4, Tekel 3, Ürün 4).

| Mercek | Puan | Oy |
| --- | --- | --- |
| Teklif | 4 | ŞARTLI FONLA |
| Tekel | 3 | GEÇ |
| Ürün | 4 | ŞARTLI FONLA |

Ayrıntılar: `founder/board/offers.md`, `founder/board/monopoly.md`, `founder/board/product.md`.

## 2. Birden fazla üyenin dile getirdiği riskler (en önemliler)
1. **Hasta başı ücretin ölçümü ve tahsili tanımsız (3/3 üye).** Kullanımın nasıl sayılacağı, hekimin bu sayıma neden güveneceği, faturanın nasıl kesileceği ve az kullanılan cihazın maliyetini kimin taşıyacağı belli değil. Ölçülemeyen kiralama gelir değil, sahada bekleyen sermayedir.
2. **Başkasının cihazını satmak, emtia ve fiyat savaşı riski (3/3).** Münhasırlık ve alış fiyatı bilinmiyor. Üretici başka bayi atar, doğrudan satar ya da bir rakip aynı modeli sunarsa geriye tek fark kalmaz ve marj erir.
3. **Servis, eğitim, garanti ve laboratuvar/CAD entegrasyonu sahipsiz (3/3).** Hekim için asıl ürün "taradım ve laboratuvar dosyayı sorunsuz aldı" anıdır. Bu an bozulursa suçlanan girişim olur ama düzeltebilecek güç onda değildir.
4. **Birim ekonomisi bilinmiyor (3/3).** Alış fiyatı olmadan bir kiralık cihazın kaç hastada kendini ödediği ve 750.000 TL'nin kaç cihazı sahada taşıyabileceği hesaplanamıyor. Hesap ipucu: 50 € × 99 hasta ≈ 4.950 €. Çok tarayan klinik kısa sürede satın almayı seçer; az tarayan klinik ise cihazı atıl bırakır.
5. **Dağıtım ve kanıt yok (Teklif + Tekel).** İlk kliniklere nasıl ulaşılacağı, müşteri edinmenin kaça mal olacağı, referans ve pilot verisi yok. Az bilinen bir marka ile tanınmayan bir satıcı birleşince hekimin "bu işe yarar" inancı düşük kalır.

Tek üyenin dile getirdiği risk:
- **Odak eksikliği (Ürün).** Satış ve hasta başı kiralama iki ayrı iş: farklı operasyon, farklı nakit akışı. Bu bütçeyle ikisi birden vasat kalır.

## 3. Koşullar: kontrol listesi
Paketin sonraki adımları bunların çoğunu test edecek.

- [ ] **Distribütörlük belgesi:** Yazılı alış fiyatı, resmi bayilik ve mümkünse münhasır bölge anlaşması. Üretici doğrudan satarsa ne olacağı yazılı olmalı. (Tekel: yeniden değerlendirme şartı)
- [ ] **Birim ekonomisi:** Satış marjı, kiralık cihazın geri dönüş süresi (kaç hasta / kaç ay), bütçenin taşıyabileceği cihaz sayısı ve nakit ihtiyacı. → `/founder-cfo`
- [ ] **Tek ana model:** İlk 12 ay için satış ya da kiralamadan biri ana iş seçilmeli. Diğeri ya kesilmeli ya da ona hizmet eden bir dönüşüm adımı olmalı (ör. kiralamada ödenenin bir kısmı satış fiyatına sayılır). (Ürün)
- [ ] **Ölçülebilir kiralama sözleşmesi:** Kullanım nasıl sayılacak (yazılım sayacı, tarama dosyası, laboratuvar kaydı) ve hekim bunu nasıl doğrulayacak? Ayrıca minimum aylık kullanım veya taban ücret, iade koşulu ve satın almaya dönüşüm netleşmeli. (Teklif + Ürün)
- [ ] **Cihazın etrafında bir paket ve garanti:** Kurulum, eğitim, laboratuvar entegrasyonu, arızada belirli sürede yedek cihaz ve ilk vakalarda destek. Ardından gerçek bir garanti ve net bir isim. → `/founder-offer`
- [ ] **Uçtan uca deneyim yazılı:** İlk temas, kurulum, ilk tarama, laboratuvara dosya, arıza ve fatura adımlarının her birinin sahibi belli olmalı. Girişimin üstlenmediği adımlar için üreticiden yazılı servis/garanti taahhüdü alınmalı. → `/founder-ops`
- [ ] **Küçük bir başlangıç pazarı:** Bir şehir ve klinik tipi seçilmeli. Orada kaç klinik olduğu ve kaçında tarayıcı bulunduğu bilinmeli. → `/founder-competitors`
- [ ] **Rakip haritası:** Aynı hekime kim, hangi fiyata, hangi destekle tarayıcı satıyor veya kiralıyor? Hasta başı model sunan başka biri var mı? → `/founder-competitors`
- [ ] **Hekimin ödeme tercihi:** Hasta başı mı, aylık sabit mi, satın alma mı, hangi fiyatta? Müşteri edinme maliyeti ne? → `/founder-consumer`, `/founder-pricing`
- [ ] **Pilot:** Birkaç klinikte gerçek fiyatla deneme yapılmalı. Gerçek kullanım sayıları, hekim görüşleri ve laboratuvar uyumu belgelenmeli. Kırılan adımlar düzeltilmeden ölçeklenmemeli. → `/founder-launch`

## 4. Üyeler arasındaki ayrılık
- **Tekel merceği geçti.** Gerekçe: Ürün başkasına ait, korunaklı bir avantaj yok ve kopyalanması kolay. Münhasır bölge ya da kendi servis ağı gibi bir hendek gösterilmeden fonlamıyor.
- **Teklif ve Ürün mercekleri şartlı fonluyor.** Hasta başı modeli hekimin girişteki riskini ve eforunu gerçekten düşüren bir fikir olarak görüyorlar. Onlara göre sorun fikir değil, eksik kurgu.
- **Teklif ile Ürün arasındaki fark:** Teklif merceği iki modeli birbirine bağlamayı öneriyor (kiralamadan satışa dönüşüm). Ürün merceği ise önce tek bir modele odaklanmayı şart koşuyor.

## 5. Kurulun görebildiği en güçlü versiyon
Bu, girişimcinin anlattığından farklı. En güçlü versiyon "tarayıcı satan bayi" değil, **seçilen tek bir şehirde "ilk günden çalışan dijital ölçü" hizmeti**. Hekim kutu almıyor, sonucu alıyor: kurulum, eğitim, laboratuvar entegrasyonu ve arızada aynı gün yedek cihaz. Giriş kapısı, taban ücretli ve şeffaf sayaçlı hasta başı kiralama. Kiralamada ödenenin bir kısmı satış fiyatına sayılıyor; böylece çok tarayan klinik satın almaya kendiliğinden geçiyor ve kiralama, satışın huni başı oluyor. Bu versiyonun hendeği cihaz değil: yazılı münhasır bölge anlaşması, yerel servis hızı ve laboratuvar ilişkileri. Bunlar yoksa iş, aynı cihazı daha ucuza verecek ilk rakibe karşı savunmasız.

---
*Not: Kurul üyeleri yayımlanmış iş çerçevelerini uygulayan mercekler, gerçek kişiler değil. Bu değerlendirme finansal, hukuki ya da vergi tavsiyesi değildir.*
