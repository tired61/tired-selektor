# tired-selektor

Basit ve hafif bir araç selektör (flash) scripti. FiveM sunucunuzdaki araçların tek bir tuşla hızlıca selektör yapmasını sağlar.

## Özellikler
- **Tek Tuşla Selektör**: Varsayılan olarak `TAB` tuşu ile çalışır.
- **Akıllı Durum Kaydı**: Selektör yaptıktan sonra farlarınız eski haline (kapalı, kısa veya uzun) geri döner.
- **Ayarlanabilir Hız**: Yanıp sönme hızı ve sayısı `client/main.lua` üzerinden kolayca ayarlanabilir.
- **Standalone**: Hiçbir framework (ESX, QB) gerektirmez, direkt çalışır.

## Kurulum
1. Dosyayı `resources` klasörüne atın.
2. `server.cfg` dosyasına `ensure tired-selektor` ekleyin.
3. Sunucuyu yeniden başlatın.

## Yapılandırma
`client/main.lua` dosyasının en üst kısmından ayarları değiştirebilirsiniz:
```lua
Config.Keybind = 37 -- Tetikleme tuşu (Varsayılan: TAB)
Config.FlashCount = 3 -- Kaç kere yanıp söneceği
Config.FlashSpeed = 150 -- Yanıp sönme hızı (ms)
```

