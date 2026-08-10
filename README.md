# 🚀 Vanity Swapper

Bu proje, [@Swozinc](https://www.youtube.com/@Swozinc) tarafından geliştirilen açık kaynaklı ve topluluk destekli bir uygulamadır.

## 📽️ Tanıtım Videosu

[![Tanıtım Videosu](https://img.youtube.com/vi/sEIylcQV85o/maxresdefault.jpg)](https://youtube.com/@Swozinc)

👆 Projeyi daha iyi anlamak için tanıtım videomuzu izleyebilirsiniz.

## ✨ Özellikler

| Özellik | Açıklama |
|---------|----------|
| 🔁 Vanity URL Taşıma | Bir sunucudaki vanity URL'yi başka bir sunucuya otomatik taşır |
| 🔐 MFA Fix | Şifre ile MFA akışını otomatik tamamlar |
| 🧹 Otomatik Silme | Eski vanity URL'yi serbest bırakmak için invite'i siler |
| 🎯 Hızlı Patcher | URL boşalır boşalmaz hedef sunucuya bağlar |
| ⚡ HTTP/2 İstekler | Hızlı ve düşük gecikmeli istekler için HTTP/2 kullanır |

## 🛠️ Kurulum

Node.js (v18 veya üzeri) kurulu olması gerekir.

```bash
node swapper.mjs
```

Ekstra bağımlılık kurulumuna gerek yoktur.

## 📖 Kullanım

1. `node swapper.mjs` komutuyla başlat.
2. Sorulan bilgileri sırayla gir:
   - **Silinecek URL:** Taşımak istediğin vanity URL
   - **Guild ID:** URL'nin taşınacağı hedef sunucu ID
   - **URL'yi Silecek Token:** URL'nin silineceği sunucuda yetkisi olan token
   - **URL'yi Alacak Token:** URL'nin çekileceği sunucuda yetkisi olan token
   - **Url'yi silicek tokenin sifresi:** URL'nin silineceği sunucuda yetkisi olan tokenin şifresi
   - **Url'yi alicak tokenin sifresi:** URL'nin çekileceği sunucuda yetkisi olan tokenin şifresi
3. `MFA Fixlendi` çıktısını gördükten sonra **Enter**'a bas.
4. İşlem tamamlanana kadar bekle; işlem sonucu ekranda görünecek.

> 💡 Her iki hesabın da **iki adımlı doğrulaması (2FA)** açık olmalıdır.

## 💬 Destek ve Topluluk

Herhangi bir sorunla karşılaşırsanız veya yardım almak isterseniz, destek sunucumuza katılabilirsiniz:

[![Discord Banner](https://api.weblutions.com/discord/invite/json/)](https://discord.gg/json)

## 🪪 Lisans

Bu proje, [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0) ile lisanslanmıştır. Detaylar için `LICENSE` dosyasına göz atabilirsiniz.

## 📄 Sorumluluk Reddi Beyanı

Bu araç yalnızca eğitim amaçlı ve kavram ispatı için hazırlanmıştır. Üçüncü tarafların gerçekleştirdiği yasadışı, beklenmedik eylemlerden ve Kullanım Şartları ihlallerinden sorumlu değilim.

This tool was made for educational purposes and proof of concepts. I'm not accountable for any unlawful, unprecedented action and any violation of ToS administered by a third party.
