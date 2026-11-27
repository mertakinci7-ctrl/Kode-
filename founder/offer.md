# Teklif: "Laboratuvar Onaylı Dijital Ölçü"

Tarih: 27 Kasım 2026. Yöntem: kurulun Teklif merceği (yayımlanmış bir teklif çerçevesinin özeti; bir kişinin sözleri değil).
Girdiler: `founder/panel/rapor.md` (panel v3), `founder/board.md`, `founder/pricing.md`, girişimcinin verdiği maliyetler.

> `founder/numbers.json` henüz yok, çünkü `/founder-cfo` çalışmadı. Maliyetler girişimcinin verdiği rakamlardan kaba olarak hesaplandı: cihaz 2.700 €, klinik ziyareti 1.000 TL. Euro/TL kuru verilmediği için TL ve € karışık gösterildi.

## 1. Problem listesi (hekimin gözünden)
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

## 2. Çözümler: değer ve maliyet
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

## 3. Test edilen yığın (pitch v4)
`founder/pitch-v4.md`. Ana ürün, sonuç olarak anlatıldı ("Laboratuvar Onaylı Dijital Ölçü"). Eklenenler: B, C, D, E, F, G, H.

**Girişimci onayı gerekenler:** B, C, D, E, G, H henüz senin onayladığın maddeler değil. Panelde etkilerini görmek için test edildi. Gerçek teklife girmeden önce her birini teyit etmelisin.

## 4. Değer denklemi (1–10, Teklif merceği)
| Unsur | v3 teklifi | v4 yığını | Neyi değiştirdi |
| --- | ---: | ---: | --- |
| Hayal edilen sonuç | 6 | 6 | Değişmedi |
| Algılanan olasılık | 4 | 4 | Garanti (B) ekledi, ama referans ve yazılı laboratuvar listesi (L, M) olmadan güven artmadı |
| Sonuca ulaşma süresi | 6 | 6 | Değişmedi |
| Efor / fedakârlık | 5 | 6 | Kira mahsubu (E) ve ücretsiz kurulum (H) biraz düşürdü; taksit olmadığı için peşin ödeme engeli sürüyor |

## 5. Yeniden test sonucu (kısa panel)
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

## 6. Öneri
**Satış metnini v3'te bırak** (`founder/pitch.md` v3'e geri alındı). v4 yığını `founder/pitch-v4.md` olarak saklandı.

Teklife bonus eklemek yerine şu üç gerçek kanıtı topla. Panel ve kurul en çok bunları istiyor:
1. **Laboratuvar listesi (M):** Ankara'da 2–3 laboratuvardan "Launca DL-300 STL dosyalarını kabul ediyoruz" yazısı.
2. **İlk referanslar (L):** 3–5 klinik. Gerekirse kurucu klinik fiyatıyla (F), ama teklif metnine değil, birebir görüşmede.
3. **Yazılı güvence (I, J, K):** Servis ve yedek cihaz sürelerinin sözleşmede olması, Launca distribütörlük belgesi ve (doğruysa) "yıllık yazılım ücreti yok."

**Kira mahsubu (E)** panelde 25 kişinin kendiliğinden istediği şeydi. Kısa testte tek başına bir şeyi değiştirmedi, ama düşük maliyetli olduğu için gerçek denemelerde test etmeye değer.

**Taksit (N)** konusu açık kalıyor. Üç panelde de en sık ikinci istek bu oldu. Bir banka ya da finansman şirketiyle konuşmak, teklife eklenebilecek en etkili madde olabilir.

## Sonraki adım
- `/founder-cfo`: kira mahsubu, kurucu klinik fiyatı ve garantilerin maliyetini, ayrıca kiralamanın ziyaret başına ekonomisini hesaplar. Eksik girdiler: euro/TL kuru, ziyaret başına tarama sayısı, beklenen aylık satış ve tarama sayısı, başlangıç harcamasının dağılımı.
- `/founder-marketing`: v3 teklifi ve itiraz listesiyle mesajları hazırlar.
