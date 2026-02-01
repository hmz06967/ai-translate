# ai-translate
LMSuite, LM Studio Server API'si üzerinden doğal dil modeline (örneğin Llama-3, Mistral) prompt vererek metin üreten bir grafik arayüz (GUI) uygulamadır. Kullanıcıya büyük bir metin ve küçük bir prompt alanını sağlar, bu iki metni birleştirip API'ye gönderir, ardından modelden dönen cevabı gösterir ve kopyala butonu ile kolayca kullanabilir.

# LMSuite — LM Studio ile Metin Oluşturma GUI Uygulaması

> **LMSuite**, [LM Studio](https://lmstudio.ai/) Server API'si üzerinden doğal dil modeline (örneğin Llama-3, Mistral) prompt vererek metin üreten bir **grafik arayüz** (GUI) uygulamadır.  
> Kullanıcı büyük bir metin ve kısa bir prompt girer, sistem bunları birleştirir, modelden sonuç alır ve kopyalama ile doğrudan kullanabilir.

---

## 📦 Özellikler

- ✅ Büyük metin alanı (scroll bar destekli, kullanıcı dostu)
- ✅ Kısa prompt giriş alanı
- ✅ Otomatik prompt birleştirme: `Metin: [büyük metin] \n\n Prompt: [küçük metin]`
- ✅ LM Studio API'si üzerinden model çağrısı (örneğin: Llama-3-8B-Instruct)
- ✅ Cevap doğrudan ekranda gösterilir
- ✅ "Kopyala" butonu ile sonuç hızlıca kopyalanır
- ✅ Hata yönetimi (boş giriş, API hatası, bağlantı sorunları)

---

## 🚀 Nasıl Çalıştırılır?

### 1. LM Studio Server Başlat

Terminalde şu komutu çalıştır:

```bash
lm-studio-server --host 0.0.0.0 --port 1234
python lg.py

