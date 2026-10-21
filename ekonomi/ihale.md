# İhale (açık artırma)

`/ihale` (kısa yol `/ah`) oyuncuların birbirine eşya sattığı pazardır. İki türde satış yapabilirsin:

- **Sabit fiyat:** Tek fiyat koyarsın, ilk alan alır.
- **Açık artırma:** Başlangıç fiyatı koyarsın, oyuncular teklif verir. İstersen bir **"Hemen al" fiyatı** da belirlersin;
  biri bu fiyatı öderse artırma anında biter.

## Ana ekran

| Düğme | İşlevi |
|---|---|
| Kategori | Tümü, Bloklar, Silahlar, Zırhlar, Aletler, Yemekler, İksirler, Redstone, Diğer |
| Para birimi | Tümü, Bakiye veya ZaunCoin |
| Arama | Eşya adıyla ara (Türkçe, örneğin "elmas kılıç") |
| Sıralama | Yeniden eskiye, eskiden yeniye, fiyat artan, fiyat azalan |
| Bekleyen Eşyalar | Süresi dolan, iptal edilen ya da alınamayan eşyalar |
| Satışlarım | Kendi ilanların ve yeni ilan verme |
| ◀ ▶ | Sayfa değiştir |

## Eşya satma

1. İhalede **Satışlarım > Yeni ilan ver**'e gir.
2. Envanterinden satmak istediğin eşyaya tıkla (sol tık: tüm yığın, sağ tık: tek adet).
3. **Para birimini** (Bakiye ya da ZaunCoin), **süreyi** (12 / 24 / 48 / 72 saat) ve **satış türünü** seç.
4. Fiyatı yaz (açık artırmada başlangıç fiyatı, isteğe bağlı hemen al fiyatı).
5. **İlanı yayınla**'ya bas.

Hızlı yol: eşyayı elinde tutup `/ihale sat <fiyat>` ya da `/ihale artirma <başlangıç> [hemen al]`.

## Açık artırmada teklif verme

- İlana tıkla: **Minimum teklifi ver**, **Teklif yaz** (istediğin tutar) ya da varsa **Hemen al**.
- Verdiğin teklifin tutarı **hemen bloke edilir**; biri seni geçerse paran anında iade edilir.
- Her yeni teklif, mevcut teklifin en az **%5 fazlası** olmalıdır.
- **Son saniye koruması:** bitmesine 2 dakikadan az kala teklif gelirse süre 2 dakikaya uzar.
- Süre bitince en yüksek teklifi veren eşyayı kazanır; eşya **Bekleyen Eşyalar**'a gelir.

## Kurallar ve vergi

- Satış vergisi **Bakiyede %5**, ZaunCoin'de %0'dır (satıcının kazancından kesilir).
- Aynı anda verebileceğin ilan sayısı rütbene bağlıdır: Oyuncu 5, VIP 15, MVIP 20, ZVIP 25, ZVIP+ 30.
- Teklif almış bir açık artırmayı iptal edemezsin.
- İhale için en az **60 dakika** oynamış olmalısın; aynı ağdaki (IP) hesaplar birbirinin ilanını alamaz.
- Satılmayan eşya kaybolmaz, **Bekleyen Eşyalar**'da seni bekler.
