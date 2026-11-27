# Ağız İçi Tarayıcı Satış ve Kiralama (çalışma adı): tek sayfa

**Karar: EKSİK** (`compile.py` ile hesaplandı). Rakamlar (`/founder-cfo`) tamamlanmadan "Kârlı" ya da "Henüz değil" denemez.

| Kararı belirleyen sayı | Değer | Durum |
| --- | --- | --- |
| Simüle alıcı oranı | %7 (100 hekimden 7'si; eşik %25) | ✗ Geçmiyor |
| Cihaz başına brüt kalan | 2.250 € (4.950 € − 2.700 €; servis, yol ve diğer giderler hariç) | CFO doğrulamadı |
| Başa baş ve 1. yıl kârı | Hesaplanamadı (sabit gider 100.000 TL/ay; kur, hacim ve başlangıç harcamasının dağılımı eksik) | Eksik |

**Problem:** Ankara'daki laboratuvarlar dijital ölçü istemeye başladı. Ama hekimler 5.000 €'luk bir tarayıcıyı peşin almadan önce cihazın kendi laboratuvarlarıyla çalışacağından emin olmak istiyor. Depolar fiyatı gizliyor, taksitle satıyor ve kiralama sunmuyor.

**Müşteri:**
- Küçük ve yeni muayenehaneler (kiralama)
- Çok hekimli poliklinikler (satış)

İkisinde de tetikleyici, laboratuvarın dijital dosya istemeye başlaması.

**Teklif ve fiyat:**
- Launca DL-300 Kablosuz, Launca Türkiye distribütöründen.
- Satış: 4.950 € + KDV.
- Ankara'da randevulu kiralama: hasta başı 50 € + KDV, peşin yok, tekrar taramalar ücretsiz.
- Ücretsiz deneme ve hekimin kendi laboratuvarından STL onayı.
- Servis distribütörde; yedek cihaz Ankara ve İstanbul'a 1–2 günde, diğer illere 5 günde.

**Kanıt (henüz simülasyon ve masa araştırması):**
- **Panel (100 simüle hekim):** %7 aldı. Kiralayanların hepsi küçük muayenehane, satın alanların hepsi poliklinik. Fiyat kabul edilebilir aralıkta (2.506–5.497 €); engel güven, laboratuvar onayı ve peşin ödeme.
- **Rakip boşluğu:** Okunan 10 bayi sayfasının hiçbirinde kiralama ya da hasta başı ücret yok. Fiyatlar üye girişinin arkasında.
- **Kurul:** 2 şartlı fonla, 1 geç; ortalama 4,0/10.
- **Gerçek test:** Henüz yapılmadı. Ankara Pilot planlandı: 30 Kasım – 20 Aralık 2026, başarı çizgisi 15 demodan en az 2 ödeyen klinik.

**Para ne için:** Kuruluş bütçesi 750.000 TL. Dağılımı henüz belirlenmedi (CFO). Pilot yeni stok almadan, elde olan demo ve yedek cihazla yapılıyor. Talep kanıtlanmadan ek cihaz alınmayacak.

**İstenen:** Şu an dışarıdan bir talep yok. Bu hafta yapılacaklar:
1. `/founder-cfo` için eksik dört bilgi: euro/TL kuru, ziyaret başına tarama sayısı, beklenen aylık satış ve tarama sayısı, bütçe dağılımı.
2. Ankara'da ilk laboratuvar randevuları.

---
*Panel simüle alıcılardan oluşuyor, rakamlar projeksiyon. Gerçek müşteriler ve gerçek teklifler doğrulamalı. Finansal, hukuki ya da vergi tavsiyesi değildir.*
