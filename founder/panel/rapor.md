# Alıcı paneli raporu: Launca DL-300 satış ve hasta başı kiralama

**1 alır · 99 almaz (%1).** 100 simüle diş hekimi, seed 393267. Ham sonuç: `founder/panel/results.md`, cevaplar: `founder/panel/answers/`.

> Bunlar simüle alıcılar, gerçek müşteri değil. İtirazları ve zayıf noktaları bulmakta iyiler; gerçek satın alma oranını tahmin etmekte kötüler. Dil modelleri genelde olumlu cevaba eğilimli olduğu için alım oranını bir üst sınır olarak oku. Panel cevapları müşteri yorumu olarak kullanılamaz.

## 1. Kim aldı, kim almadı
- Alan tek kişi P046: poliklinik sahibi, "önce dener sonra alır" davranışı. **Satın almayı değil, Ankara kiralamasını** seçti, çünkü laboratuvarı dijital dosya istiyor. Onun da şartı var: laboratuvarın onayı ve hızlı servis.
- **Hiçbir grupta satın alma yok.** Yeni ve yerleşik muayenehaneler %0, poliklinikler %3 (o tek kişi).
- Davranışa göre tek pozitif grup "önce dener sonra alır" (%8). Taksitle alan, laboratuvarına bağlı, meslektaş tavsiyesiyle alan, fiyat avcısı, premium marka sadığı ve klasik ölçüden memnun gruplarının hepsi %0.

## 2. Neden almıyorlar (ilk üç neden)
| Neden | Kişi | Kendi cümleleriyle |
| --- | ---: | --- |
| **Güven** | 60 | "Adını ilk kez duyduğum bir Çin markasına 4.950 € + KDV bağlamadan önce laboratuvarın dosyayı sorunsuz alıp almadığını görmem lazım." (P001) |
| **Alışkanlık** | 22 | "Klasik silikon ölçü zaten işimi görüyor, hastam da şikâyet etmiyor." (P005) |
| **Fiyat** | 17 | "Aynı paraya ikinci el bir Medit bulurum ya da depodan taksitle bilinen bir marka alırım. Hasta başı 50 € kiralama ise birkaç ayda cihazın fiyatını geçer." (P010) |

İtirazlarda en sık geçen konular (100 kişide):
- **Türkiye'de / Ankara'da servis kimde:** 79
- **Laboratuvar dosyayı kabul eder mi:** 52
- **Hasta başı 50 €:** 93 kişi gerekçesinde ya da itirazında 50 €'yu sorun olarak andı. Yaygın hesap şu: "Ayda 20 hasta = 1.000 €, birkaç ayda cihaz fiyatını geçer."
- **Sayıma güven:** 27 kişi sordu. "Kim sayacak?" ve "Tekrar tarama da ücretli mi?" en sık iki soru.

## 3. "Hayır"ı "evet"e ne çevirir
| Ne | Kaç kişi istedi |
| --- | ---: |
| Ankara'da yerel servis (çoğu yazılı garantiyle) | 61 |
| Laboratuvarın dosyayı kabul ettiğini yazılı teyit etmesi ya da tarayıcıyı önermesi | 55 |
| Kendi kliniğinde ücretsiz deneme (birkaç gün – birkaç hafta) | 54 |
| Ankaralı bir meslektaşın aylarca sorunsuz kullanmış olması | 32 |
| Vade farksız taksit (çoğunlukla 12 ay, ayda ~400–450 €) | 32 |
| Arızada yedek cihaz (48 saat ya da aynı gün) | 20 |
| Kurulum ve eğitimin dahil olması | 12 |
| Daha düşük kira (hasta başı 15–20 €), sabit aylık ücret ya da aylık tavan | 10 |

## 4. Fiyat cevapları (satın alma, € KDV hariç, medyan)
- Çok ucuz (şüpheli): **1.500 €**
- Ucuz / fırsat: **3.000 €**
- Pahalılaşıyor: **4.500 €**
- Çok pahalı, almam: **6.500 €**

4.950 €; 45 kişi için "pahalı" eşiğinin altında, 53 kişi için "pahalı" ile "çok pahalı" arasında, 2 kişi için ise "almam" eşiğinde ya da üstünde. **Yani fiyat tek başına engel değil; asıl engel güven.** Ayrıntılı fiyat analizini `/founder-pricing` yapacak.

## 5. Para harcamadan önce neyi değiştirmeli
Teklif şu an sadece bir cihaz ve bir fiyattan ibaret. Hekimin ilk sorduğu üç şeye cevap vermiyor: servis kimde, laboratuvarım kabul eder mi, önce deneyebilir miyim. Bu üçünü teklifin içine koy: Ankara'da yazılı servis ve yedek cihaz, laboratuvar onayı ya da laboratuvar ortaklığı, ücretsiz deneme. Ayrıca taksit ekle ve kiralamayı yeniden tasarla: şeffaf sayaç, tekrar taramalar ücretsiz, aylık tavan, ödenen kiranın satın almaya sayılması. Bunu `/founder-offer` yapar. Sonra paneli yeniden çalıştırıp alım oranının değişip değişmediğine bakmak gerekir.
