# Fiyatlama: Launca DL-300 Kablosuz

Tarih: 27 Kasım 2026. Girdiler:
- Panel fiyat eğrisi: `founder/pricing-curve.md` (100 simüle hekim, panel v3)
- Rakip fiyatları: `founder/competitors.md`
- Girişimcinin verdiği maliyet: 2.700 € (nakliye ve gümrük dahil)

> Simüle alıcıların fiyat cevapları neyin test edileceğini seçmeye yarar, kanıt değildir. `founder/numbers.json` henüz yok, çünkü `/founder-cfo` çalışmadı. Aşağıdaki marjlar yalnızca **fiyat − 2.700 €** hesabıdır; satış, yol, servis, yedek cihaz ve sabit giderler dahil değil. Gerçek marjı ve başa baş noktasını CFO hesaplayacak.

## 1. Alıcıların söylediği (Van Westendorp, satın alma, € KDV hariç)
| Nokta | Fiyat | Anlamı |
| --- | ---: | --- |
| PMC | 2.506 € | Bunun altında çok kişi "fazla ucuz, kalitesizdir" der |
| OPP | 2.525 € | En az direnç noktası |
| IPP | 3.795 € | "Ucuz" diyenle "pahalı" diyen eşit |
| PME | 5.497 € | Bunun üstünde çok kişi "almam" der |

**Kabul edilebilir aralık: 2.506 € – 5.497 €.** Medyan cevaplar: çok ucuz 1.500 €, ucuz 3.000 €, pahalılaşıyor 4.500 €, çok pahalı 6.500 €.

**4.950 € aralığın içinde, ama üst kısmında.** IPP ile PME arasında duruyor ve medyan "pahalılaşıyor" eşiğinin (4.500 €) biraz üstünde. Aralığın tavanına (5.497 €) 547 € mesafe var.

## 2. Rakiplerle karşılaştırma
| Seçenek | Fiyat | Ne dahil | Kaynak |
| --- | --- | --- | --- |
| **Senin teklifin** | **4.950 € + KDV** | Yeni cihaz, ücretsiz deneme, STL ile laboratuvar onayı, servis, 1–2 gün yedek cihaz (Ankara/İstanbul) | — |
| İkinci el Medit i700 | ~5.000 € | Az kullanılmış cihaz, 5 taksit; garanti ve servis belirsiz | dentalilan (arama sonucu) |
| Gri pazar DL-300 Kablosuz | 4.250–4.750 USD | Yurt dışından ithal; Türkiye'de garanti ve servis yok | Bonker, Drpridemart (arama sonucu) |
| FUSSEN S6500 (DMO kamu kataloğu) | 178.767 ₺ + %10 KDV | Kamu alımı kataloğu | dmo.gov.tr |
| Türk depoları (Dentrealmarket, Merkez Diş, Osstem, Çatak, Medoral) | Fiyat gizli (üye girişi ya da satış ekibi) | Çoğunda **vade farksız taksit**, eğitim, teknik servis | founder/competitors.md |
| Referans: Aoralscan 3 kablolu | Önerilen perakende 10.999 USD | Üretici fiyatı | shining3ddental.com |

**Sonuç:** Türkiye'de görülen yeni ve servisli seçenekler arasında 4.950 € düşük tarafta. Ama ikinci el Medit ve gri pazar DL-300 ile neredeyse aynı fiyatta. Senin farkın fiyat değil; deneme, laboratuvar onayı, servis ve yedek cihaz. Rakiplerin asıl üstünlüğü taksit.

## 3. Marj (yalnızca fiyat − 2.700 € maliyet)
| Fiyat | Brüt kalan | Brüt marj |
| ---: | ---: | ---: |
| 3.795 € (IPP) | 1.095 € | %29 |
| 4.450 € | 1.750 € | %39 |
| **4.950 € (mevcut)** | **2.250 €** | **%45** |
| 5.497 € (PME) | 2.797 € | %51 |

**Kiralama:** Hasta başı 50 € ile bir cihaz 54 taramada maliyetini çıkarıyor. 25 €'ya inersen bu sayı 108'e çıkar. Yol ve zaman maliyeti dahil değil; CFO hesaplayacak.

## 4. Karar: fiyat
**Liste fiyatı 4.950 € + KDV olarak kalsın.** Gerekçeler:
- Kabul edilebilir aralığın içinde.
- Türkiye'deki yeni ve servisli rakiplerin altında görünüyor.
- En yüksek brüt marjı veriyor (%45), ki bu marj servis, yedek cihaz ve ücretsiz deneme maliyetlerini taşımak zorunda.
- Panelde fiyat itirazlarının neredeyse hepsi fiyatın kendisine değil, **peşin ödemeye** ve **taksit yokluğuna** yönelikti (bkz. bölüm 7). Fiyatı düşürmek bu itirazı çözmez, marjı düşürür.

Fiyatı indirmek yerine ödeme şeklini kolaylaştır: **kira mahsubu** (bkz. merdiven).

## 5. Fiyat merdiveni
| Basamak | Kime | Fiyat | Bir üste çıkma nedeni |
| --- | --- | --- | --- |
| **Kiralama** (Ankara) | Küçük ve yeni muayenehaneler; ayda birkaç vaka | Hasta başı 50 € + KDV, peşin yok | Vaka sayısı arttıkça kira birikir. **6 ay içinde satın alırsan ödenen kiranın tamamı cihaz fiyatından düşülür.** |
| **Satın alma** | Çok hekimli poliklinikler, yüksek hacim | 4.950 € + KDV | Cihaz her an elinde; randevuya bağlı değilsin |
| **Satın alma + paket** (öneri) | İkinci cihaz isteyen ya da ekibini eğitmek isteyen poliklinikler | Fiyat CFO'dan sonra belirlenecek | Örneğin yerinde ekip eğitimi, uzatılmış garanti, ek tarama ucu. Maliyetleri bilinmediği için fiyat konmadı. |

Kira mahsubu, panelde 25 kişinin kendiliğinden istediği şeydi. Taksit veremediğin için taksidin işini görür. Senin riskin de yok, çünkü para peşin geliyor; sadece daha önce ödenmiş oluyor.

## 6. Açılış teklifi
**"Kurucu klinik" programı.** İlk 5 klinik **4.450 € + KDV**'ye satın alır. Karşılığında:
- Referans olmayı kabul eder: meslektaşlarına gösterim ve adının kullanılması.
- Laboratuvarının STL onayını yazılı olarak paylaşır.

**Son tarih: 31 Ocak 2027** ya da 5 klinik dolunca, hangisi önce gelirse. Bu indirim değil, referans karşılığı verilen bir fiyat. Tarihi ve kontenjanı belli olduğu için hekimleri "indirimi bekleyeyim" alışkanlığına itmez. Bu fiyattan cihaz başına brüt kalan tutar 1.750 € (%39).

Kurul ve panel en çok meslektaş referansının eksik olduğunu söyledi. Bu program o eksiği kapatmanın en ucuz yolu.

## 7. Gerçek hekimlerle test
**Test 1: ödeme şekli (fiyat aynı).**
- A: 4.950 € peşin
- B: 4.950 €, 6 ay kira mahsubuyla

İkisini Ankara'da 10'ar kliniğe sun. Ölç: denemeye kaç klinik başladı, kaçı laboratuvar onayı aldı, kaçı satın aldı ya da kiraladı.

**Test 2: fiyat (aralığın içinde iki nokta).**
- 4.950 € ile 4.450 €'yu iki ayrı klinik grubuna sun. Ölç: denemeden satın almaya geçiş oranı.

4.450 € gerçekten daha çok satıyorsa, kaybedilen 500 €'nun hacimle telafi edilip edilmediğini CFO hesaplasın.

**Kiralama fiyatı:** Panelde 8 kişi hasta başı 15–25 € istedi. Ama kiralayan 4 hekimin hepsi 50 €'yu kabul etti. Kiralama fiyatını şimdilik değiştirme. Gerçek denemelerde "pahalı" itirazı çok çıkarsa ayda bir tavan ücreti (örneğin "ayda en fazla X €") test edilebilir. X'i CFO belirlesin.

## 8. Panelin fiyat itirazları (kendi cümleleriyle, en sık üç tema)
1. **Peşin ödeme ve taksit yok:** "4.950 € + KDV'yi tek seferde ödeyecek nakdim yok, depodan bildiğim markaları vade farksız taksitle alabiliyorum." (P063)
2. **Aynı paraya alternatif var:** "4.950 € + KDV peşin, taksitsiz; aynı paraya ikinci el bir Medit bulurum ya da depodan taksitle bilinen bir marka alırım." (P010)
3. **Kiralama birikiyor:** "Ayda 20 civarı ölçü alıyorum, kiralama hasta başı 50 € ile ayda bin euroyu geçer, o yüzden olacaksa satın alırım." (P011)

Bu cümleler gerçek müşteri yorumu değil; pazarlamada itirazlara cevap hazırlamak için kullanılmalı.

## Not: KDV
Teklif KDV hariç fiyatlanmış. Ağız içi tarayıcının KDV oranını muhasebecinle teyit et (DMO kataloğunda bir tarayıcı %10 KDV ile listelenmiş). Hekim KDV dahil ~5.400–5.900 € görecek. Bir panel üyesi (P052) bunu açıkça yazdı: "KDV ile neredeyse 6.000 €."

## Sonraki adım
- `/founder-cfo`: `founder/numbers.json` oluşturur, gerçek marjı, başa baş noktasını ve kiralama kapasitesini hesaplar.
- `/founder-offer`: kira mahsubunu, kurucu klinik programını ve laboratuvar onayını teklife yerleştirir.
