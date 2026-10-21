# GitBook'a yükleme (bu dosya wiki'de görünmez)

Bu klasör GitBook'un **Git Sync** biçimine uygundur (`README.md`, `SUMMARY.md`, `.gitbook.yaml`).

## Yöntem 1: GitHub ile senkron (önerilen)
1. GitHub'da boş bir depo (repository) oluştur, bu klasörün **içeriğini** depoya yükle (`.gitbook.yaml` depo kökünde olmalı).
2. https://app.gitbook.com adresinde **New space** (yeni alan) oluştur.
3. Space'te sağ üstten **Configure > Git Sync** > **GitHub** seç, hesabını bağla, depoyu ve `main` dalını seç.
4. İlk eşitlemede **GitHub → GitBook** yönünü seç. Sayfalar menüde (SUMMARY.md sırasıyla) görünür.
5. Sonraki değişikliklerde GitHub'daki dosyaları güncelle, GitBook otomatik yansıtır (ya da tersi).

## Yöntem 2: Elle yapıştırma
Her `.md` dosyasının içeriğini GitBook editöründe yeni bir sayfaya yapıştır. `{% hint %}` blokları GitBook'ta kutu olarak görünür.
Sayfa sırasını `SUMMARY.md`'ye göre kur.

## Doldurulacak yerler
- `<SUNUCU-IP>` (baslangic/nasil-baglanirim.md)
- `<DISCORD-DAVET-LINKI>` (topluluk/discord.md)
- topluluk/kurallar.md **taslaktır**, kendi kurallarınla değiştir.
- VIP rütbelerinin avantaj/fiyat bilgileri (topluluk/rutbeler.md)
