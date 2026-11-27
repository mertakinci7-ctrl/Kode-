# Özet

## Karar: EKSİK (sayılardan hesaplandı, `compile.py`)
Kararı belirleyen üç sayı:

| # | Sayı | Durum |
| --- | --- | --- |
| 1 | **Simüle alıcı oranı: %7** (100 hekimden 7'si aldı; eşik %25) | ✗ Geçmiyor |
| 2 | **Cihaz başına brüt kalan: 2.250 €** (4.950 € − 2.700 € maliyet; servis, yol ve diğer giderler hariç) | CFO doğrulamadı |
| 3 | **Başa baş noktası ve 1. yıl kârı: hesaplanamadı** (aylık sabit gider 100.000 TL; euro/TL kuru, beklenen satış ve tarama sayısı ve başlangıç harcamasının dağılımı eksik) | Eksik |

**Karar neden "Eksik":** `founder/numbers.json` yok, çünkü `/founder-cfo` çalışmadı. Birim kârı, 1. yıl kârı ve başa baş kontrolleri yapılamadı. Panelden geçmeyen tek kontrol de alıcı oranı: %7, eşik %25.

**Eşik hakkında:** %25 varsayılan bir eşik ve aslında tüketici ürünleri için konmuş. 5.000 €'luk bir tıbbi cihazı, ilk kez duyan hekimlerin almasını ölçen bir panel için yüksek olabilir. Ama eşiği düşürmek kararı değiştirmez: rakamlar olmadan karar zaten "Eksik" kalır. Eşiği değiştirmedim.

## İş ne, kimin için
Launca DL-300 kablosuz ağız içi tarayıcının Türkiye distribütörü olarak iki teklif:
- **Satış:** 4.950 € + KDV, öncelikle çok hekimli polikliniklere.
- **Ankara'da randevulu kiralama:** hasta başı 50 € + KDV, peşin yok, öncelikle küçük ve yeni muayenehanelere.

İkisi de ücretsiz deneme ve hekimin kendi laboratuvarından STL onayıyla başlıyor.

## Panel ve kurul neyde anlaştı, neyde ayrıldı
**Anlaştıkları:**
- En büyük engel güven ve kanıt. Panelde 84 hekim "laboratuvarım onaylarsa" dedi. Kurulun üç üyesi de laboratuvar teyidi ve referans hekim istedi.
- Fiyat engel değil. 4.950 € kabul edilebilir aralıkta (2.506–5.497 €); engel peşin ödeme ve taksit yokluğu.

**Ayrıldıkları:**
- Kurul "satış mı kiralama mı ana iş" diye bölündü.
- Panel bunu kısmen cevapladı: kiralayanların hepsi küçük muayenehane, satın alanların hepsi poliklinik. Yani iki kol iki ayrı müşteriye hitap ediyor.
- Kurulun Tekel merceği ise münhasırlık olmadığı için hâlâ "geç" diyor.

## En büyük risk ve yapılacak
**Risk:** Kanıt olmadan hekimin "hayır" demesi. Laboratuvar onayı yok, referans hekim yok, distribütörün kalıcılığına dair güvence zayıf.

**Yapılacak:**
- Ankara Pilot: 15 klinik ve bir laboratuvar tarama günü, 30 Kasım – 20 Aralık.
- 2 laboratuvardan yazılı STL onayı.
- İlk referans klinikler.

Daha fazla bonus eklemek işe yaramadı; kısa panel testinde alım arttırmadı (bkz. `founder/offer.md`).

## Başlamak için gerekenler
- **Nakit:** CFO hesaplamadan belli değil. Elde 750.000 TL bütçe var, aylık sabit gider 100.000 TL.
- **İlk test:** Ankara Pilot. Yeni stok almadan, elindeki demo ve yedek cihazla yapılacak.
- **Başarı çizgisi:** 15 demodan en az 2 ödeyen klinik (bkz. `founder/launch.md`).

## Bu hafta yapılacak tek şey
**`/founder-cfo`'yu çalıştır.** Bunun için şu dört bilgiyi ver:
1. Euro/TL kuru
2. Bir kiralama ziyaretinde kaç hasta taranıyor
3. Beklenen aylık satış ve tarama sayısı
4. 750.000 TL'nin dağılımı (kaç cihaz stok, tanıtım, kuruluş)

Karar ancak bu rakamlarla "Kârlı" ya da "Henüz değil" olabilir. Aynı hafta Ankara'daki ilk laboratuvar randevularını al.

---
*Panel simüle alıcılardan oluşuyor, rakamlar projeksiyon. Gerçek müşteriler ve gerçek teklifler bunları doğrulamalı. Bu belge finansal, hukuki ya da vergi tavsiyesi değildir.*
