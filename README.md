<p align="center">
  <img src="ekranlar/kapak.png" alt="AtomixServis" width="720">
</p>

# AtomixServis

**Oto servisler için iş emri, araç kabul, QR etiket ve stok takibi.**
Web paneli + iOS / Android mobil uygulama. Elazığ'da, atomiXbilişim tarafından geliştiriliyor.

[![App Store](https://img.shields.io/badge/App_Store-Yayında-000000?logo=apple&logoColor=white)](https://apps.apple.com/tr/app/atomixservis/id6831888179)
![Google Play](https://img.shields.io/badge/Google_Play-Kapalı_test-34A853?logo=googleplay&logoColor=white)
[![Web](https://img.shields.io/badge/Web-atomixservis.com-0b7a3e)](https://atomixservis.com)

> Bu depo bir **vitrin** deposudur. AtomixServis ticari bir üründür; kaynak kodu gizli (private) depoda tutulur.

## Ekranlar

<p>
  <img src="ekranlar/1-panel.png" width="180" alt="Panel">
  <img src="ekranlar/2-kanban.png" width="180" alt="Kanban iş takibi">
  <img src="ekranlar/3-isemri.png" width="180" alt="İş emri">
  <img src="ekranlar/4-arac.png" width="180" alt="Araç kartı">
  <img src="ekranlar/5-tara.png" width="180" alt="QR etiket tarama">
</p>

## Neler yapıyor

- **Araç kabul ve iş emri:** müşteri, araç, şikâyet, yapılan işlem, parça ve işçilik tek kayıtta
- **Kanban iş takibi:** araç hangi aşamada (kabul, işlemde, parça bekliyor, hazır) bir bakışta
- **QR etiket:** araca/parçaya etiket bas, telefonla okut, kayda anında ulaş
- **Stok takibi:** parça girişi/çıkışı, iş emrine bağlı stok düşümü
- **Mobil uygulama:** firma koduyla ya da QR ile bağlan, sahada iş emirlerini gör ve güncelle, fotoğraf ekle
- **Bildirimler:** iş durumu değiştiğinde ekibe haber
- **KVKK:** bildirim metinlerinde kişisel veri yok, uygulama içinden "bu telefondaki verileri sil"

## Teknoloji

| Katman | Kullanılan |
|---|---|
| Sunucu / web paneli | PHP 8, MySQL / SQLite |
| Mobil | Capacitor 8 (iOS + Android), vanilla JS |
| Derleme / dağıtım | Codemagic (iOS), Gradle AAB (Android), imzalı güncelleme paketleri |
| Barındırma | cPanel + Cloudflare, firma başına alt alan adı |

## Durum

- Web sürümü: firmalarda kullanımda
- iOS: App Store'da yayında
- Android: Google Play kapalı testte

## İletişim

**atomiXbilişim** · [atomixservis.com](https://atomixservis.com) · iletisim@atomixbilisim.com
Canlı demo için sitedeki "Demo" bağlantısını kullanabilirsiniz.

© atomiXbilişim. Tüm hakları saklıdır.
