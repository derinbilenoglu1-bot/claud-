# 📡 BorsaRadar — ABD Borsası Anlık Haber & Sinyal Merkezi

ABD borsası (NYSE / NASDAQ) için KAP benzeri, tek sayfalık bir haber ve sinyal paneli.
Haberler anlık olarak akar, her haber otomatik duygu analizinden geçer ve hisse bazında
"Yükseliş · Al / Düşüş · Sat / İzle" sinyalleri üretilir.

## Özellikler

- **💼 Alım-satım simülasyonu (paper trading)** — başlangıç sermayeni kendin belirle, sanal
  parayla güncel fiyatlardan al-sat yap; nakit, hisse değeri, toplam varlık ve kâr/zarar anlık
  hesaplanır; işlem geçmişi tutulur; sinyaldeki hisseye tıklayınca işlem kutusu otomatik dolar.
  Demo modda simüle fiyatlar, canlı modda gerçek Finnhub fiyatları kullanılır. Portföy tarayıcıda
  saklanır; istediğin zaman sıfırlayıp yeni sermayeyle başlayabilirsin.
- **📰 Anlık haber akışı** — yeni haberler otomatik olarak akışın en üstüne düşer
- **🧠 Duygu analizi** — her haber başlık + özet üzerinden pozitif / negatif / nötr olarak puanlanır
- **🎯 Habere dayalı sinyaller** — son 24 saatin haberleri hisse bazında toplanır, yakın tarihli
  haberler daha ağır basar; skorlara göre AL / SAT / İZLE sinyali ve güven çubuğu gösterilir
- **⭐ İzleme listesi** — sembol ekleyin, sadece kendi hisselerinizin haberlerini filtreleyin
  (tarayıcıda saklanır)
- **🔎 Filtre & arama** — pozitif/negatif/nötr filtreleri, sembol veya kelimeyle arama,
  haberdeki sembole tıklayarak hızlı filtre
- **📈 Endeks bandı** — S&P 500, NASDAQ, Dow ve büyük hisseler için kayan fiyat bandı
- **🕐 Piyasa durumu** — New York saatiyle NYSE açık / pre-market / after-hours / kapalı göstergesi
- **🏷️ Otomatik kategori** — Bilanço, Makro/Fed, Analist, Birleşme & Satın Alma, Teknoloji vb.

## Canlı mod ve demo mod

- **Demo mod (varsayılan):** API anahtarı gerekmez; site gerçekçi simüle haberlerle çalışır,
  böylece arayüz her zaman canlı görünür.
- **Canlı mod:** Ücretsiz bir [Finnhub.io](https://finnhub.io/register) API anahtarı alıp
  ⚙️ Ayarlar'dan yapıştırın. Anahtar yalnızca tarayıcınızın `localStorage`'ında tutulur,
  hiçbir sunucuya gönderilmez. Gerçek piyasa haberleri ve fiyat teklifleri belirlediğiniz
  aralıkta (varsayılan 60 sn) çekilir.

## Çalıştırma

Derleme yok, sunucu yok — `index.html` dosyasını tarayıcıda açmanız yeterli.
GitHub Pages ile de doğrudan yayınlanabilir.

## ⚠️ Yasal Uyarı

Bu sitedeki sinyaller, haber başlıklarının otomatik duygu analiziyle üretilen **bilgilendirme
amaçlı** göstergelerdir; **yatırım tavsiyesi değildir**. Haber duyarlılığı fiyat hareketini
garanti etmez. Alım-satım kararlarınızı kendi araştırmanıza ve/veya lisanslı bir yatırım
danışmanına dayandırın.
