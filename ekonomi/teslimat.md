# Teslimat

`/teslimat` günlük siparişler ve haftalık yarışma sistemidir. Ödülü **kasa anahtarıdır**: anahtarla lobideki
[Teslimat Kasası](../oyun/kasalar.md)'nı açarsın.

## Günlük siparişler

- Her gün (gece yarısı yenilenir) **herkese aynı 3 sipariş** verilir.
- Siparişteki eşyaları envanterinden teslim et, her tamamlanan sipariş **1 Teslimat Anahtarı** verir.
- Siparişlerdeki eşya ve adetler pazar fiyatlarına göre dengelenir; ucuz eşyadan çok, pahalı eşyadan az istenir.

## Haftalık yarışma

- Her hafta **rastgele tek bir eşya** seçilir ("haftanın eşyası").
- Hafta boyunca o eşyayı en çok teslim eden **ilk 3 oyuncu** anahtar kazanır:

| Sıra | Temel ödül |
|---|---|
| 1. | 10 anahtar |
| 2. | 6 anahtar |
| 3. | 3 anahtar |

- Ödül, haftanın eşyasının **zorluğuna göre** çarpılır (kolay ve ucuz eşyada x0,7'ye kadar düşer, zor ve pahalı eşyada
  x3'e kadar çıkar). Eşya ne kadar değerliyse ödül o kadar büyür.
- Yarışma **pazartesi 00:00'da** sonuçlanır, ödüller otomatik verilir ve sohbette duyurulur.
- `/teslimat` menüsünde sıralamayı, kalan süreyi ve ödülleri görürsün.

## Kurallar

- Teslimat için en az **60 dakika** oynamış olman gerekir (yeni hesapla ödül kasmayı önler).
- Adlandırılmış, büyülü ya da hasarlı eşyalar **kabul edilmez**.
- Kendi siparişini kendi kendine tekrar tamamlayamazsın; her sipariş günde bir kez ödüllenir.
