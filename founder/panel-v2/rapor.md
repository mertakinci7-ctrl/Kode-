# Alıcı paneli raporu v2: güncellenmiş teklif

**6 alır · 94 almaz (%6).** İlk panelde (v1) bu oran **1 alır · 99 almaz (%1)** idi. İki panelde aynı 100 hekim kartı kullanıldı (seed 393267), yani fark yalnızca teklifteki değişikliklerden geliyor. Ham sonuçlar: `founder/panel/results.md` (v2), `founder/panel-v1/` (v1).

> Bunlar simüle alıcılar, gerçek müşteri değil. Dil modelleri olumlu cevaba eğilimli olduğu için alım oranını bir üst sınır olarak oku. Panel cevapları müşteri yorumu olarak kullanılamaz.

**Teklife eklenenler:**
- Türkiye genelinde teknik servis
- Arızada yedek cihaz
- İlk birkaç hastada ücretsiz deneme
- Kiralamada tekrar taramaların ücretsiz olması

## 1. Kim aldı
| Grup | v1 | v2 |
| --- | ---: | ---: |
| Poliklinik / çok hekimli klinik sahibi | %3 | **%17** (5/30) |
| Yerleşik muayenehane | %0 | %2 (1/40) |
| Yeni muayenehane | %0 | %0 |
| "Önce dener sonra alır" | %8 | **%25** |
| "Taksitle alan" | %0 | **%17** |
| Diğer davranışlar (laboratuvarına bağlı, meslektaş tavsiyesi, fiyat avcısı, klasik ölçüden memnun, premium marka sadığı) | %0 | %0 |

- **6 alıcının 5'i satın almayı seçti, 1'i kiralamayı.** Satın alanlar çok hekimli kliniklerdi. Onlara göre kiralama birkaç ayda cihaz fiyatını geçiyor, 4.950 € ise fuardaki markalara göre ucuz.
- Satın alanların ortak şartı şu: ücretsiz denemede laboratuvarın dosyayı sorunsuz kabul etmesi.

## 2. Neden almıyorlar
| Neden | v1 | v2 | Kendi cümleleriyle (v2) |
| --- | ---: | ---: | --- |
| Güven | 60 | **44** | "Laboratuvarın sorunsuz kabul ettiğinden emin olmadığım bir Çin markasına 5.000 € bağlamam." (P001) |
| Alışkanlık | 22 | 26 | "Silikon ölçüyle yıllardır sorunsuz çalışıyorum, hastalarım da şikâyet etmiyor." (P005) |
| Fiyat | 17 | 23 | "4.950 € + KDV'yi peşin bırakacak durumum yok, taksit de yazmıyor." (P019) |

**Ne değişti:** Güven itirazı 60'tan 44'e indi. Servis artık itirazların zirvesinde değil. Bu kez öne çıkan iki eksik var:
- **Laboratuvar uyumu:** 72 kişi itirazında andı.
- **Taksit yokluğu:** 34 kişi itirazında andı.

Kiralamada sayaca güven sorusu hâlâ duruyor (24 kişi: "Kim sayacak?"). Tekrar taramaların ücretsiz olması işe yaradı ama yetmedi. Hekim, sayımı kendisinin de görebileceği bir kayıt istiyor.

## 3. "Hayır"ı "evet"e ne çevirir (v2)
| İstek | Kaç kişi |
| --- | ---: |
| Ücretsiz denemede laboratuvarın dosyayı sorunsuz kabul ettiğini görmek ya da laboratuvarın tarayıcıyı önermesi | 71 |
| Vade farksız taksit (çoğunlukla 12 ay, ayda ~400–450 €) | 42 |
| Ankaralı bir meslektaşın aylarca sorunsuz kullanmış olması (referans) | 38 |
| Daha düşük fiyat (3.000–4.000 €) | 19 |
| Kurulum ve eğitimin yerinde yapılması | 9 |
| Servis ve yedek cihaz süresinin yazılı olması (saat ya da gün olarak) | ~9 |
| Görülebilir sayaç (cihazın kendi tarama kaydı) | birkaç kişi |

## 4. Fiyat (satın alma, € KDV hariç, medyan)
Çok ucuz **1.500** · ucuz **3.000** · pahalılaşıyor **4.500** · çok pahalı **6.500**. Bu değerler v1 ile aynı. 4.950 € kabul edilebilir aralıkta kalıyor; engel fiyatın kendisi değil, ödeme şekli (taksit yok) ve güven.

## 5. Sonraki adım
1. **Laboratuvar ortaklığı.** Ankara'daki 2–3 laboratuvardan Launca dosyalarını kabul ettiklerine dair yazılı onay al ve bunu teklife yaz. Etkisi en büyük tek değişiklik bu.
2. **Taksit.** Vade farksız 12 taksit ekle (ayda ~413 € + KDV).
3. **İlk referanslar.** İlk 3–5 kliniğe indirimli kurulum karşılığında referans olma şartı koy. Meslektaş tavsiyesiyle alan grup hâlâ %0.
4. **Kiralamada şeffaflık.** Cihazın tarama kaydından üretilen aylık rapor ve aylık tavan ekle.
5. **Hedefi daralt.** İlk müşteri olarak çok hekimli poliklinikleri ve "önce dener" profilini hedefle. Yeni muayenehaneler bu teklifle %0.

Bu teklifi `/founder-offer` kurar. Fiyat cevaplarının ayrıntılı analizini ise `/founder-pricing` yapar.
