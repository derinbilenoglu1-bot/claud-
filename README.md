# Kampüs Ajandam

Derin'e özel, tek dosyalık üniversite ajandası — 2026-2027 ve sonrası için.

## Özellikler

- **Bugün ekranı**: açılışta günün özeti — bugünkü dersler, teslim edilecekler, gecikmişler, önümüzdeki 7 gün.
- **Takvim**: ay görünümü; her günün üzerinde ders rengine göre noktalar, güne tıklayınca o günün ders ve görev listesi.
- **Görevler**: ödev / sınav / quiz / proje / lab / okuma / kişisel türleriyle, ders etiketi, tarih-saat, önem işareti ve notlarla tam bir checklist.
- **Ders programı**: haftalık düzen, ders başına renk ve derslik bilgisi.
- **Bildirimler**: sayfa açıkken günlük özet, ders başlamadan 20 dk önce ve saatli teslimlerden önce tarayıcı bildirimi (Ayarlar'dan açılır).
- **Dönem hafta sayacı**: güz/bahar tarihlerine göre "Güz dönemi · 5. hafta" gibi; tarihler Ayarlar'dan her yıl güncellenebilir.
- **Yedekleme**: JSON olarak dışa/içe aktarma.

## Veri saklama

- Claude Artifact olarak yayınlandığında veriler `data/state.json` dosyasına kaydedilir (artifact `files publish`), böylece her cihazdan aynı veriye erişilir; ayrıca `localStorage` yerel yedek olarak kullanılır ve iki kaynaktan yeni olan kazanır.
- Düz statik barındırmada (ör. GitHub Pages) yalnızca `localStorage` kullanılır.

## Çalıştırma

Tek dosya: `index.html`. Herhangi bir statik sunucuyla ya da doğrudan tarayıcıda açarak kullanılabilir.
