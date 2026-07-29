# Few-shot Prompt Testi

## Amaç

Claude'a örnek belgeler verilerek daha kaliteli sonuç üretip üretmediğini gözlemlemek.

---

## Kullanılan Prompt

Aşağıdaki örnekleri incele ve aynı formatta yeni bir açıklama oluştur.
Örnek 1:
Girdi: SQL Injection
Çıktı: SQL Injection, saldırganın veritabanı sorgularına zararlı SQL komutları ekleyerek yetkisiz erişim sağlamasına olanak tanıyan bir web güvenlik açığıdır.
Örnek 2:
Girdi: Cross-Site Scripting (XSS)
Çıktı: XSS, saldırganın zararlı JavaScript kodlarını web sayfasına enjekte ederek kullanıcıların tarayıcısında çalıştırmasına imkan veren bir güvenlik açığıdır.
Şimdi aşağıdaki kavramı aynı formatta açıkla:
Girdi: Cross-Site Request Forgery (CSRF)
---

## Beklenen Çıktı

- Aynı başlık yapısı
- Benzer yazım dili
- Standart rapor düzeni

---

## Gözlemlenen Sonuç

Claude verilen örnekleri dikkate alarak çok daha düzenli ve kurumsal bir rapor oluşturmuştur.

---

## Değerlendirme

Avantajları

- Tutarlı sonuç üretir.
- Kurumsal raporlar için uygundur.
- Belge formatını korur.

Dezavantajları

- Prompt hazırlaması daha uzun sürmektedir.
