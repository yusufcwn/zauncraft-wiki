# Düello arenası

PvP'yi sever misin? Özel **arena dünyasında** diğer oyuncularla düello yapabilirsin. Düello **kendi eşyalarınla** yapılır;
ölürsen eşyaların kaybolmaz. Sadece bahis varsa bahse konan para (ya da eşya bahsinde bahse konan eşyalar) el değiştirir.

## Düello isteği

| Komut | Açıklama |
|---|---|
| `/duello <oyuncu>` | Bahissiz düello isteği |
| `/duello <oyuncu> <miktar>` | Bakiye bahisli düello isteği |
| `/duello accept <oyuncu>` / `/duello deny <oyuncu>` | İsteği kabul et / reddet (mesajdaki [KABUL] [RED] butonlarına da basabilirsin) |
| `/duello toggle` | Düello isteklerini aç/kapat |
| `/duello stats [oyuncu]` | İstatistiklerini gör |
| `/duello top` | Sıralamalar |
| `/izle <oyuncu>` | Süren bir düelloyu izle |

Ana menüde **Arena** düğmesi de komutları gösterir.

## Bahis kuralları

Bahisli düellolar ekonomiyi korumak için sınırlandırılmıştır:

- En yüksek bahis **250$**.
- Bir oyuncu günde en fazla **1000$** bahis oynayabilir.
- Aynı oyuncuyla günde en fazla **3 bahisli düello** yapabilirsin.
- Bahisli düello için iki hesabın da en az **24 saatlik** olması gerekir.
- **Aynı ağdaki (IP) hesaplar** birbirine bahis oynayamaz.
- Kazanan paradan **%5 arena vergisi** kesilir.
- Eşya bahsi günde en fazla 5 düelloyla sınırlıdır.

{% hint style="warning" %}
Düello sırasında `/home`, ışınlanma ve çoğu komut **kullanılamaz**. Düello süresi en fazla 10 dakikadır; süre dolarsa berabere sayılır.
{% endhint %}
