[README.md](https://github.com/user-attachments/files/32161982/README.md)
# Kodlama Yolculuğu — Kişisel Portfolyo

Sıfırdan HTML, CSS ve JavaScript ile kodladığım kişisel portfolyo sitem. Front-end geliştirme yolculuğumu ve bu süreçte inşa ettiğim projeleri gösteriyor.

**🌐 Canlı site:** https://mustafa-portfolio.github.io/portfolio/

## Özellikler

- Gece / gündüz modu (tercih `localStorage`'da saklanır, sayfa yenilenince flaş olmadan uygulanır)
- Responsive tasarım — mobilden masaüstüne
- Open-Meteo API ile anlık hava durumu uygulaması
- Şehir arama ve otomatik tamamlama

## Sayfalar

| Dosya | Açıklama |
|---|---|
| `index.html` | Ana sayfa — yolculuk/proje zaman çizelgesi |
| `hakkimda.html` | Hakkımda ve beceri seviyelerim |
| `iletisim.html` | İletişim formu |
| `havadurumu.html` | Hava durumu uygulaması |
| `kodlar.html` | Hava durumu uygulamasının kaynak kod özeti |
| `style.css` | Tüm sayfalar için ortak stil dosyası |
| `script.js` | Tema değiştirici ve iletişim formu mantığı |

## Yerelde çalıştırma

Bu bir statik site, herhangi bir build adımı gerektirmiyor. Klonladıktan sonra `index.html`'i tarayıcıda açman yeterli:

```bash
git clone https://github.com/mustafa-portfolio/portfolio.git
cd portfolio
# index.html dosyasını tarayıcında aç
```

## Kullanılan teknolojiler

- HTML5, CSS3 (custom properties ile tema sistemi), vanilla JavaScript
- [Open-Meteo API](https://open-meteo.com/) — hava durumu ve şehir arama verisi
- [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) & [Inter](https://fonts.google.com/specimen/Inter) — Google Fonts

## Yol haritası

- [ ] Yapılacaklar uygulamasını tamamlayıp yayına almak
- [ ] Kişisel e-posta ile gerçek form gönderimi (Formspree/EmailJS)
- [ ] Yeni projeler eklendikçe zaman çizelgesini güncellemek
