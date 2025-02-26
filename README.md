# Windows'a Makyaj Rehberi
Windows'umun **yasb**, **komorebi**, **whkdrc** konfigürasyon dosyalarını repository'de bulabilirsiniz.

### Kurulum

Kurulum adımlarını YouTube'dan izleyebilirsiniz: [https://youtu.be/5HLV4ftJ32U](https://youtu.be/5HLV4ftJ32U)

### Yasb İkonlarının Gözükmeme Problemi
JetBrainsMono NFP fontunu [buradan](https://www.jetbrains.com/lp/mono/) indirerek ikonlarin gözükmesini sağlayabilirsiniz.

### Komorebi'ye Animasyon Ekleme
`komorebi.json` dosyasının içerisine aşağıdaki kodu ekleyiniz:

```json
{
  "animation": {
    "enabled": true,
    "animation.duration": 250,
    "animation.style": "Linear"
  }
}
```

Bu ayarlar, animasyonların etkinleştirilmesini, animasyon süresini ve stilini belirler.
