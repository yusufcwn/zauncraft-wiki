# Oyuncu komutları

Herkesin kullanabildiği komutlar. `<...>` zorunlu, `[...]` isteğe bağlı değerdir.

## Işınlanma ve ev

| Komut | Açıklama |
|---|---|
| `/rtp` | Rastgele ışınlanma menüsü (3 sn bekleme, hareket/hasarla iptal olur) |
| `/spawn`, `/lobi` | Lobiye git |
| `/home`, `/ev`, `/evler` | Ev menüsünü aç. `/home <isim>` o eve ışınlar |
| `/sethome <isim>`, `/evayarla` | Bulunduğun yeri ev yap (3 ev, VIP ve üstü 5) |
| `/delhome <isim>`, `/evsil` | Ev sil |
| `/tpa <oyuncu>`, `/tpahere <oyuncu>` | Işınlanma isteği gönder |
| `/tpaccept`, `/tpdeny` | İsteği kabul et / reddet |
| `/back` | Önceki konumuna dön |

## Ekonomi

| Komut | Açıklama |
|---|---|
| `/bakiye` | Bakiyeni göster |
| `/ode <oyuncu> <miktar>` | Para gönder |
| `/zenginler` | En zengin oyuncular |
| `/zauncoin`, `/zc` | ZaunCoin bakiyen |

## Alışveriş ve ticaret

| Komut | Açıklama |
|---|---|
| `/market`, `/pazar` | Eşya sat, ZaunCoin mağazası |
| `/ihale`, `/ah` | Oyuncu ihalesi (satış ve açık artırma) |
| `/ihale sat <fiyat> [bakiye\|zauncoin]` | Elindeki eşyayı sabit fiyatla sat |
| `/ihale artirma <başlangıç> [hemen al]` | Elindeki eşyayı açık artırmaya koy |
| `/ihale teklif <ilan no> <tutar>` | Açık artırmaya teklif ver |
| `/ihale ara <metin>` | İhalede eşya ara |
| `/siparis`, `/siparisler` | Eşya siparişi ver / siparişlere teslimat yap |
| `/siparis ver <adet> <fiyat>` | Elindeki eşya için hızlı sipariş |
| `/takas <oyuncu>` | Güvenli takas isteği. `/takas kabul`, `/takas red`, `/takas para <miktar>` |
| `/teslimat` | Günlük siparişler ve haftalık yarışma |
| `/dukkan` | Oyuncu mağazası (QuickShop) |

## Meslek, arena ve kasa

| Komut | Açıklama |
|---|---|
| `/meslek` | Meslek seç, bırak, istatistiklere bak |
| `/duello <oyuncu> [miktar]` | Düello isteği (bahisli ya da bahissiz) |
| `/izle <oyuncu>` | Süren bir düelloyu izle |
| `/crates` | Kasa menüsü |
| `/keys` | Kaç anahtarın olduğunu göster |

## Diğer

| Komut | Açıklama |
|---|---|
| `/ec`, `/enderchest` | Ender sandığını aç (Bakiye ile genişletilebilir) |
| `/menu`, `/zaun` | Ana menü |
| `/sb` | Skor tablosunu aç/kapat |
| `/msg <oyuncu> <mesaj>`, `/r` | Özel mesaj, son yazana cevap |
| `/mail`, `/ignore <oyuncu>` | Mesaj bırak, oyuncuyu engelle |
| `/afk`, `/list`, `/rules`, `/help` | AFK ol, çevrimiçi liste, kurallar, yardım |
| `/voicechat` | Sesli sohbet ayarları |

{% hint style="info" %}
`/sell`, `/worth` ve `/tpr` gibi bazı varsayılan komutlar bilerek kapalıdır; yerlerine yukarıdaki sunucuya özel
komutlar kullanılır (örneğin `/market`, `/rtp`).
{% endhint %}
