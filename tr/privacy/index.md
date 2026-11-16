---
layout: page
title: Gizlilik Politikası
permalink: /tr/privacy/
---

**Yürürlük tarihi:** 16 Kasım 2026

Volura ("uygulama"), Türkiye'de bireysel geliştirici olarak çalışan Umut Ulaş Demir
("biz") tarafından geliştirilmektedir. Bu politika, uygulamanın hangi verileri
kullandığını, bu verilerin nereye gittiğini ve senin hangi seçeneklere sahip
olduğunu açıklar. English version: [Privacy Policy](../../privacy/).

## Özet

- Hesap açman gerekmez. Verilerini satmayız, reklam göstermeyiz, seni başka
  şirketlerin uygulama ve sitelerinde takip etmeyiz.
- Antrenmanların, programların, profilin ve ölçümlerin cihazında ve **kendi iCloud
  hesabında** saklanır. Bunları biz göremeyiz.
- Verilerin yalnızca **Yapay Zekâ Koçu**'nu kullandığında ve sen izin verdikten
  sonra sunucumuza gider. Sağlık verileri koçla ancak bunu ayrıca açarsan
  paylaşılır.
- Uygulama, sorunları bulup uygulamayı geliştirebilmemiz için **anonim kullanım
  istatistikleri ve çökme raporları** gönderir. Bunlarda hiçbir zaman mesajların,
  adın, antrenman, beslenme, uyku ya da sağlık verilerin bulunmaz.

## Cihazında ve iCloud'unda saklanan veriler

Uygulama; profilini ve profil fotoğrafını, antrenmanlarını ve kaydettiğin setleri,
takvimini, özel antrenman ve programlarını, kaydettiğin içerikleri, vücut
ölçümlerini, tercihlerini ve uygulamada oluşturduğun diğer kayıtları saklar. Bu
veriler cihazında tutulur ve diğer cihazlarında da kullanılabilmesi için Apple'ın
iCloud hizmetiyle (özel CloudKit veritabanı ve iCloud anahtar-değer depolaması)
eşitlenir. Veriler Apple hesabına bağlıdır ve bizim erişimimize açık değildir. Koç
sohbetleri yalnızca cihazında saklanır.

## Apple Sağlık {#apple-health}

İzin vermen hâlinde:

- iPhone uygulaması, ilerlemeni güncel tutmak için vücut ağırlığını, vücut yağ
  oranını ve yağsız vücut kütlesini **okur**;
- iPhone uygulaması, uykunu gösterebilmek için uyku analizini ve uyku sırasında
  kaydedilen nabız ve solunum hızını **okur**;
- Apple Watch uygulaması antrenman sırasında nabız ve aktif enerjiyi **okur**,
  antrenmanlarını ve aktif enerjiyi Apple Sağlık'a **kaydeder**.

Sağlık verileri yalnızca bu özellikler için kullanılır. Reklam amacıyla
kullanılmaz, satılmaz, kullanım istatistiklerine ya da çökme raporlarına hiçbir
zaman eklenmez ve Yapay Zekâ Koçu'nun sağlık verilerini kullanmasına izin
vermediğin sürece sunucumuza gönderilmez (aşağıya bakınız). Bu izinleri istediğin
zaman Ayarlar uygulamasında Sağlık bölümünden değiştirebilirsin. Volura verilerini
silmek Apple Sağlık'tan hiçbir şey silmez.

## Yapay Zekâ Koçu

Yapay Zekâ Koçu sorularını yanıtlar ve planını düzenleyebilir. İlk mesajın cihazdan
çıkmadan önce uygulama senden izin ister.

**Koçu kullandığında gönderilenler:** mesajın ve koçun yanıt verebilmesi için
gereken antrenman verileri; örneğin antrenmanların, kaydettiğin setler, programın,
hedeflerin ve egzersiz geçmişin. **Vücut ölçümleri, antrenman nabzı ve aktif kalori
yalnızca sağlık verilerine ayrıca izin verirsen gönderilir**; sen açmadıkça bu
kapalıdır. Uygulamada koçun hangi alanlara bağlanabileceğini de (Antrenman, Uyku,
Beslenme ve Vücut) seçersin; kapattığın bir alan koça hiçbir zaman gönderilmez.

**Nereye gider:** istekler Cloudflare üzerinde çalışan sunucumuzdan geçer ve yanıtın
oluşturulması için **OpenAI**'ye iletilir. OpenAI bu verileri kendi API koşul ve
politikalarına göre işler; bkz.
[openai.com/policies](https://openai.com/policies).

**Sunucumuzun sakladıkları:**

- günlük ve aylık kullanım hakkını saymak ve isteklerin uygulamanın gerçek bir
  kopyasından geldiğini doğrulamak için rastgele bir kurulum kimliği ve
  desteklenen cihazlarda Apple App Attest anahtar kimliği;
- bu kullanım hakkı için istek sayaçları;
- kısa teknik kayıtlar (zaman, istek türü, sonuç kodu, süre, model ve kurulum
  kimliğinin kısaltılmış, geri döndürülemez bir özeti). **Kayıtlarda hiçbir zaman
  mesajların, koçun yanıtları ya da antrenman verilerin bulunmaz.**

**Seçeneklerin:** izni geri almak, sağlık verilerini ya da bir alanı kapatmak için
istediğin zaman uygulamada Ayarlar > Gizlilik ve Zekâ bölümünü kullanabilirsin.
İzin olmadan koça hiçbir veri gönderilmez.

## Kullanım istatistikleri ve çökme raporları

Sorunları bulmak ve uygulamanın hangi bölümlerinin iyi çalıştığını anlamak için
uygulama iki tür teknik bilgi gönderir. Bunlar reklam için kullanılmaz, satılmaz ve
başka şirketlerin verileriyle birleştirilmez.

**Kullanım istatistikleri (PostHog, sunucular Amerika Birleşik Devletleri'nde):**
uygulamanın nasıl kullanıldığına dair anonim olaylar; örneğin hangi ekranın
açıldığı, hangi kontrolün kullanıldığı, bir ekranın ya da işlemin ne kadar sürdüğü,
antrenmanı bitirmek gibi bir işlemin tamamlanıp tamamlanmadığı, uygulamanın kısa
süreli donması ve bir koç isteğinin başarılı olup olmadığı. Her olay uygulama
sürümünü, iOS sürümünü, cihaz modelini, uygulama dilini, eşlenmiş bir Apple Watch
olup olmadığını, uygulamanın kurulduğu haftayı ve analiz kütüphanesinin cihazında
oluşturduğu rastgele bir kimliği içerir. Olaylarda **hiçbir zaman** adın,
mesajların, yazdığın serbest metin ya da antrenman, beslenme, uyku, vücut veya
sağlık verilerinin değerleri bulunmaz ve kişisel bir profil oluşturulmaz.

**Çökme raporları (Sentry, sunucular Avrupa Birliği'nde):** uygulama çöktüğünde ya
da ciddi bir hatayla karşılaştığında kod konumu, uygulama sürümü, iOS sürümü ve
cihaz modelini içeren teknik bir rapor gönderilir. Raporlarda kişisel veri, ekran
görüntüsü ya da hata mesajı metni bulunmaz.

Bu raporlar test ve geliştirme sürümlerinden gönderilmez. Kurulumunla ilişkili
raporların silinmesini istersen bizimle iletişime geç.

## Egzersiz videoları

Bazı egzersizlerde YouTube videosu gösterilir. Bir videoyu oynattığında video,
YouTube'un gizlilik odaklı alan adından (youtube-nocookie.com) yüklenir ve Google,
videoyu iletmek için gereken bilgileri (örneğin IP adresini) alır. Bkz.
[Google Gizlilik Politikası](https://policies.google.com/privacy?hl=tr).

## Yapmadıklarımız

- Reklam yok, reklam SDK'sı yok.
- Başka şirketlerin uygulama ve sitelerinde takip yok.
- Kişisel verilerin pazarlama amacıyla satılmaz ya da paylaşılmaz.
- Sağlık verileri reklam veya veri madenciliği için kullanılmaz.

## Dışa aktarma, saklama ve silme

- **Dışa aktarma:** uygulamada Ayarlar > Veriler ve Gizlilik > Verilerini dışa
  aktar bölümünden bu iPhone'daki Volura verilerinin bir kopyasını CSV ya da JSON
  dosyası olarak kaydedebilirsin.
- **Silme:** Ayarlar > Veriler ve Gizlilik > Tüm Volura verilerini sil, Volura
  verilerini bu iPhone'dan ve iCloud hesabından kaldırır. Apple Sağlık'taki
  verileri, dışa aktardığın ya da başka yerlerle paylaştığın kopyaları, diğer
  cihazlarında yerel olarak saklanan kopyaları ve yukarıda açıklanan kullanım
  istatistikleri ile çökme raporlarını silmez.
- Cihazındaki veriler uygulamayı sildiğinde de kaldırılır. iCloud'daki verileri
  Ayarlar uygulamasında adın > iCloud > Saklama Alanını Yönet bölümünden
  silebilirsin.
- Sunucumuzdaki istek sayaçları ve teknik kayıtlar mesaj içeriği barındırmaz.
  Kurulumunla ilişkili bir verinin silinmesini istersen bizimle iletişime geç.

## Çocuklar

Uygulama 13 yaşından küçük çocuklara yönelik değildir.

## Hakların

6698 sayılı Kişisel Verilerin Korunması Kanunu (KVKK) ve bulunduğun yere göre AB
Genel Veri Koruma Tüzüğü (GDPR) kapsamında kişisel verilerine erişme, bunları
düzeltme veya silme ve işlenmesine itiraz etme hakların olabilir. Volura
verilerini uygulamada dışa aktarabilir ve silebilirsin; diğer hakların için bizimle
iletişime geç.

## Değişiklikler

Uygulamanın veri uygulamaları değiştiğinde bu sayfayı günceller ve yukarıdaki
yürürlük tarihini yenileriz.

## İletişim

[umutulas.uud@icloud.com](mailto:umutulas.uud@icloud.com)
