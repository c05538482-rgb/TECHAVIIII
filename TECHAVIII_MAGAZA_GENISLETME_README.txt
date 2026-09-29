TECHAVIII MAGAZA GENISLETME

Bu paket mevcut TechAvı koduna şu canlı mağazaları ekleyen patch'i içerir:
- Pazarama
- Çiçeksepeti
- Boyner

Pazarama ve Çiçeksepeti mevcut server altyapısında zaten bulunuyordu; patch bunları arayüzde görünür ve filtrelenebilir hale getirir.
Boyner için ReefAPI arama endpoint'i ve fiyat normalizasyonu eklenir.

Uygulama:
1) TECHAVIII repo klasöründe bu patch dosyasını açın.
2) Git kullanıyorsanız:
   git apply TECHAVIII_MAGAZA_GENISLETME.patch
3) npm install gerekmez; yeni bağımlılık eklenmedi.
4) Render'a normal commit/push işleminizi yapın.

Not:
Koçtaş, Vivense, PttAVM, Dolap, Etsy ve Shopier için canlı veri kaynağı doğrulanmadan sahte/boş entegrasyon eklenmedi.
GittiGidiyor aktif olmadığı için eklenmedi.
TikTok Shop da Türkiye için aynı şekilde doğrudan aktif mağaza gibi eklenmedi.
