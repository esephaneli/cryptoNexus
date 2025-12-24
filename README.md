# cryptoNexus
# Crypto Nexus (Concept Demo)

Crypto Nexus, kripto para piyasalarında kullanılan klasik teknik indikatörlerin  
büyük dil modelleri (LLM) ile **yorumlayıcı** bir katman üzerinden nasıl birleştirilebileceğini
gösteren konsept bir çalışmadır.

## Bu repoda ne var?
- CoinGecko API üzerinden **Top 20 kripto** verisinin çekilmesi
- Teknik indikatör örnekleri:
  - SMA (7 / 14 / 30)
  - RSI (14)
  - Volatilite
  - Dönemsel getiri
- Hesaplanmış metrikler üzerinden **LLM tabanlı anlatı (yorum) yaklaşımı**
- Sadeleştirilmiş, öğretici demo kodları (Notebook formatında)

## Bu repoda ne yok?
- Production FastAPI / Gradio servis kodları
- Tam backend mimarisi
- Maliyet, rate-limit ve güvenlik katmanlarının detaylı implementasyonu

## Tasarım Felsefesi
Bu projede büyük dil modeli:
- **Karar verici** olarak değil,
- Hesaplanmış teknik metrikleri **açıklayan bir anlatı katmanı** olarak konumlandırılmıştır.

Tüm sayısal hesaplamalar deterministik olup sistem tarafından yapılır.

> Bu çalışma eğitim ve konsept gösterimi amaçlıdır.  
> Yatırım tavsiyesi değildir.

