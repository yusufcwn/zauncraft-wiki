# Takas

`/takas <oyuncu>` iki oyuncunun **yüz yüze, güvenli** şekilde eşya ve para takası yapmasını sağlar.

## Nasıl yapılır?

1. `/takas <oyuncu>` yaz. Karşı tarafa tıklanabilir **[KABUL] [RED]** mesajı gider (istek 60 saniye geçerli).
2. Karşı taraf `/takas kabul` yazarsa ortak takas penceresi açılır.
3. Pencerede **sol taraf senin**, **sağ taraf karşı tarafın** teklifidir.
   - Envanterindeki eşyaya tıklayarak teklife koy (sol tık: tüm yığın, sağ tık: tek adet). Teklifteki eşyaya tıklarsan geri alırsın.
   - **Para teklifi:** alttaki `-1000 -100 -10 +10 +100 +1000` düğmeleri ya da `/takas para <miktar>`.
4. İkiniz de **Hazırım** düğmesine basınca 3 saniyelik geri sayım başlar ve takas gerçekleşir.

{% hint style="success" %}
Teklifte **herhangi bir değişiklik** olursa iki tarafın da onayı sıfırlanır. Böylece son saniyede teklif değiştirilerek
dolandırıcılık yapılamaz.
{% endhint %}

## Güvenlik

- Pencere kapatılırsa ya da biri oyundan çıkarsa takas iptal olur, eşyalar sahiplerine geri verilir.
- Para takas anında iki taraftan birden doğrulanır; yetersiz bakiye ya da dolu envanter varsa takas gerçekleşmez.
- Bir takasta en fazla **50.000$** teklif edilebilir. Takas için **60 dakika** oynama şartı vardır.
- Aynı ağdaki (IP) hesaplar arasında **para** teklifi yapılamaz (eşya takası serbesttir).
- Tüm takaslar kayıt altındadır.
