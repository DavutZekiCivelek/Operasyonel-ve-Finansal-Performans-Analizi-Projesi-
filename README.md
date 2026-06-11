# Operasyonel-ve-Finansal-Performans-Analizi-Projesi-

# 📊 Perakende ve Tedarik Zinciri İş Zekası (BI) Projesi

Bu proje; perakende satış, şube performansı, tedarikçi lojistik süreçleri ve operasyonel verimliliği uçtan uca analiz etmek amacıyla geliştirilmiş kapsamlı bir **Power BI İş Zekası** çalışmasıdır. 

Projede ham veriler temizlenmiş, ilişkisel veri modeli kurulmuş ve karar vericilerin stratejik kararlar almasını sağlayacak dinamik paneller tasarlanmıştır.

---

## 🎯 Bu Projede Ne Başardım? (Kilit Noktalar)

Çok Boyutlu Operasyonel ve Finansal Analiz: Şirketin hem operasyonel teslimat süreçlerini hem de şube/personel bazlı ciro ve kârlılık performansını tek bir çatı altında birleştirdim.
Gelişmiş Veri Modelleme & DAX: Dağıtık ham verilerden anlamlı KPI'lar (Toplam Kâr, Ciro, Ortalama Teslimat Süreleri) üreten dinamik analitik metrikler kurguladım.
Gelişmiş Kullanıcı Deneyimi (Tooltip / Detay Pencereleri): Grafiklerin üzerine gelindiğinde ya da tıklandığında açılan **Dinamik Tooltip (Araç İpucu)** sayfaları tasarlayarak, kullanıcının ana ekranı terk etmeden ürün bazlı miktar, kâr ve ciro kırılımlarını (Örn: `Urun_Adi`, `Sum of Miktar`, `KAR`, `CİRO`) görebilmesini sağladım.
Koşullu Biçimlendirme ve Görsel Hiyerarşi: Performans gruplarını (İyi, Orta, Kötü) net eşik değerlerine bağlayarak yönetim seviyesindeki kullanıcılar için "ilk bakışta teşhis" imkanı sundum.

---

## 🖥️ Rapor Sayfaları ve Öne Çıkan Başarılar

### 1. Operasyonel Performans ve Miktar Analiz Paneli
Bu sayfa, şubelerin ürün bazlı stok/satış miktarlarını ve teslimat süreçlerinin operasyonel verimliliğini ölçer.

 Öne Çıkan Detaylar:
  16,02 günlük genel "Ortalama Teslimat Süresi" takibi ve bu sürenin Mağaza/Online kanallarına göre dinamik filtrelenmesi.
  Şubelerin (A, B, C, D, E) ürün kategorilerine göre dağılım matrisi.
  Müşteri puan gruplarına göre (`İyi > 3.5`, `Kötü < 2.75`, `Orta`) personel satış miktarlarının analizi.
  Satışların şehir bazlı (`Şanlıurfa`, `Kocaeli`, `Adana`, `İstanbul`) dengeli dağılımının %25'lik dilimlerle pasta grafiği üzerinden takibi.

#### 📸 Panel Görselleri:
  Genel Görünüm: `operasyonel_1.png`
   Dinamik Ürün Detay Penceresi (Tooltip): `operasyonel_2.png`

---

### 2. Finansal Gelişim, Ciro ve Kârlılık Paneli
Bu sayfa; şirketin finansal hacmini, tedarikçi performanslarını ve personel bazlı ciro kırılımlarını analiz eder.

   Öne Çıkan Detaylar:**
    474,74M Kâr ve 1M Satış Miktarı gibi makro KPI'ların unvan bazlı (Örn: İşçi) kırılımlarla takibi.
      Tedarikçi Lojistik Performansı:** Tedarikçilerin (`Akdeniz Gıda`, `Anadolu Taşımacılık`, `Has Elektronik` vb.) ürün bazında ortalama teslimat sürelerinin matris analizi (Örn: En hızlı ve en yavaş lojistik        partnerlerinin tespiti).
   Şube bazında personellerin (`Bahar Öztürk`, `Ece Yıldız`, `Mert Polat` vb.) ciroya katkı oranlarının %100 yığılmış çubuk grafikle gösterimi.
  Toplam kâra en çok katkı sağlayan ürün gruplarının (`Günlük Ayakkabı`, `Deri Bot`, `Keten Gömlek` vb.) Pareto eğilimli analizi.

#### 📸 Panel Görselleri:
   Genel Görünüm: `finansal_1.png`
    Dinamik Finansal Detay Penceresi (Tooltip): `finansal_2.png`

---

## 🛠️ Teknik Yetkinlikler ve Araçlar

BI Platformu: Microsoft Power BI
Veri Modelleme:Yıldız Şeması (Star Schema), Tablo İlişkileri
Diller: DAX (Data Analysis Expressions) ile dinamik KPI ve kümülatif hesaplamalar
UX/UI Özellikleri: Dinamik Tooltip Sayfaları, Dilimleyiciler (Slicers), Koşullu Renklendirme, Temizleme Butonları (`Clear all slicers`)
