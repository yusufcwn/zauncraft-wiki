# Bakiye ve ZaunCoin

ZaunCraft'ta iki para birimi vardır.

## Bakiye ($)

Oyunda **çalışarak kazandığın** paradır. Meslekler, market satışı, teslimat ve ticaret ile kazanılır; ihale, sipariş,
takas, ender sandığı genişletme ve oyuncu mağazalarında harcanır.

- `/bakiye` ile bakiyeni gör, `/ode <oyuncu> <miktar>` ile başkasına gönder, `/zenginler` ile sıralamaya bak.
- Ekonomi bilerek **yavaş ve dengeli** tasarlandı: sunucudan eşya satın alınamaz, sadece satılır; günlük satış limitleri vardır.

## ZaunCoin

ZaunCoin **premium** para birimidir ve oyun içinde **kazanılamaz**. Sunucumuzu desteklemek isteyenler tarafından
sunucu mağazasından edinilir. ZaunCoin ile:

- [ZaunCoin Mağazası](market.md#zauncoin-magazasi)'ndan spawner ve özel aletler alınır,
- oyuncular arasında `/ode` ile transfer edilebilir ve [ihalede](ihale.md) ZaunCoin cinsinden satış yapılabilir.

{% hint style="warning" %}
Güvenlik için ZaunCoin ve büyük Bakiye transferleri kayıt altındadır. Gerçek parayla sunucu dışı satış ve hesap paylaşımı
yapılması yasaktır, tespit edilen işlemler yetkililerce incelenir.
{% endhint %}

## Para kazanma yolları (özet)

| Yol | Ne kadar? | Detay |
|---|---|---|
| Meslekler | Günlük sınırlı | [Meslekler](meslekler.md) |
| Market satışı | Eşya başına günlük limit; haftanın ürünü 2x | [Market](market.md), [Altın Fırsat](altin-firsat.md) |
| Teslimat | Günlük 3 sipariş + haftalık yarışma (kasa anahtarı) | [Teslimat](teslimat.md) |
| Oyuncu ticareti | Serbest piyasa | [İhale](ihale.md), [Sipariş](siparis.md), [Takas](takas.md) |
| Kasalar | Rastgele ödül (anahtarlar Teslimat, Bakiye ya da ZaunCoin ile) | [Kasalar](../oyun/kasalar.md) |
