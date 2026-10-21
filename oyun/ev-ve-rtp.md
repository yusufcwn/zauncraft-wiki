# Ev ve rastgele ışınlanma

## Ev sistemi

`/home` (ya da `/ev`) komutu **ev menüsünü** açar. Menüden evlerini görür, ışınlanır, taşır ya da silersin.

| Komut | Açıklama |
|---|---|
| `/home` | Ev menüsünü aç |
| `/home <isim>` | O eve ışınlan |
| `/sethome <isim>` | Bulunduğun yeri ev yap |
| `/delhome <isim>` | Evi sil |

- **Ev hakkı:** Oyuncu 1, VIP 2, MVIP 3, ZVIP ve ZVIP+ 5 ev ([VIP avantajları](../topluluk/rutbeler.md)).
- Ev isimleri harf, rakam, `-` ve `_` içerebilir (en fazla 16 karakter).
- **Lobide ve arena dünyasında ev kurulamaz.**
- Menüde **Yeni ev ekle** düğmesine basıp ismi sohbete yazarak da ev ekleyebilirsin.

### Işınlanma bekleme süresi

Eve ışınlanırken **3 saniye** beklersin. Bu sürede **hareket edersen ya da hasar alırsan** ışınlanma iptal olur.
Hasar aldıktan sonra **10 saniye** boyunca ışınlanma başlatılamaz.

## Rastgele ışınlanma (RTP)

`/rtp` menüsünde üç düğme vardır: **Dünya**, **Nether** ve **End**. Seçtiğin bölgede rastgele bir yere ışınlanırsın (doğrudan komut: `/rtp dunya`, `/rtp nether`, `/rtp end`).

| Bölge | Mesafe (spawn'dan) | Not |
|---|---|---|
| Dünya | 250 - 8500 blok | Okyanus ve nehir seçilmez |
| Nether | 150 - 3000 blok | Lavdan uzak, saglam bir zemine ışınlanırsın. **Tehlikelidir** |
| End | 1200 - 4000 blok | End'in dış adaları. **Tehlikelidir** |

- **Başka bir oyuncunun yakınına (300 blok) ışınlanmazsın.**
- Kullanımlar arasında **60 saniye** beklemen gerekir.
- **3 saniye hareket etmeden beklemelisin**; hasar alırsan ya da kıpırdarsan iptal olur.

{% hint style="info" %}
Uzak ve yeni keşfedilen bölgelere ışınlanırken haritanın yüklenmesi birkaç saniye sürebilir; sunucu bu sırada donmaz.
{% endhint %}

## Işınlanma istekleri

Arkadaşına gitmek için `/tpa <oyuncu>` yaz; o `/tpaccept` derse yanına ışınlanırsın. `/tpahere <oyuncu>` ile onu yanına çağırırsın.
`/back` ile önceki konumuna dönersin.
