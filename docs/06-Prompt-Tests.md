# Prompt Testleri

## 1. Giriş

Bu bölümde Claude üzerinde farklı prompt teknikleri test edilmiştir. Amaç, farklı istem (prompt) yöntemlerinin çıktılar üzerindeki etkisini gözlemlemek ve hangi tekniğin hangi durumlarda daha uygun olduğunu değerlendirmektir.

Testlerde aşağıdaki teknikler kullanılmıştır:

- Zero-shot Prompt
- One-shot Prompt
- Few-shot Prompt
- Role Prompting

---

# Test 1 – Zero-shot Prompt

## Kullanılan Prompt

"Bir penetrasyon testi raporunun yönetici özetini hazırla."

##  Çıktı 1

![Uploading WhatsApp Image 2026-07-29 at 14.56.20.jpeg…]()



## Gözlem

- Hızlı sonuç üretmiştir.
- Genel bir özet sunmuştur.
- Çıktı doğru olsa da ayrıntı seviyesi düşüktür.

## Değerlendirme

Zero-shot Prompt, basit ve hızlı görevlerde başarılıdır. Ancak kurumsal raporlama gibi standart gerektiren işlerde tek başına yeterli olmayabilir.

---

# Test 2 – One-shot Prompt

## Kullanılan Prompt

"Örnek olarak verilen yönetici özetine benzer biçimde yeni bir penetrasyon testi özeti oluştur."

## Örnek Çıktı

Claude, verilen örnek yapıyı takip ederek yeni bir yönetici özeti hazırlamıştır. Başlıklar, dil ve rapor düzeni örnekle uyumlu olmuştur.

## Gözlem

- Çıktı daha düzenlidir.
- Format korunmuştur.
- Tutarlılık artmıştır.

## Değerlendirme

One-shot Prompt, belirli bir formatın korunması gereken durumlarda faydalıdır. Ancak tek örnek her zaman yeterli olmayabilir.

---

# Test 3 – Few-shot Prompt

## Kullanılan Prompt

"Verilen üç örnek güvenlik raporunu incele ve aynı formatta yeni bir rapor oluştur."

## Örnek Çıktı

Claude, örneklerdeki yapı ve yazım tarzını dikkate alarak ayrıntılı ve düzenli bir rapor hazırlamıştır.

## Gözlem

- En tutarlı sonuç elde edilmiştir.
- Başlık yapısı korunmuştur.
- Çıktı profesyonel görünmektedir.

## Değerlendirme

Few-shot Prompt, kurumsal raporlama ve standart belge üretimi için en uygun yöntemlerden biridir.

---

# Test 4 – Role Prompting

## Kullanılan Prompt

"20 yıllık deneyime sahip bir siber güvenlik uzmanı gibi davran ve aşağıdaki güvenlik bulgularını değerlendir."

## Örnek Çıktı

Claude, teknik terimler kullanarak profesyonel bir analiz gerçekleştirmiş ve güvenlik açıklarını önem sırasına göre değerlendirmiştir.

## Gözlem

- Teknik anlatım güçlenmiştir.
- Uzman bakış açısı sağlanmıştır.
- Çözüm önerileri daha ayrıntılı olmuştur.

## Değerlendirme

Role Prompting, uzman görüşü gerektiren teknik konularda oldukça başarılı sonuçlar vermektedir.

---

# Prompt Tekniklerinin Karşılaştırılması

| Teknik | Avantajı | Dezavantajı | Kullanım Alanı |
|---------|-----------|-------------|----------------|
| Zero-shot | Hızlıdır | Ayrıntı az olabilir | Basit görevler |
| One-shot | Format korunur | Tek örnek yetersiz olabilir | Benzer belge üretimi |
| Few-shot | Tutarlı sonuç verir | Hazırlaması zaman alır | Kurumsal raporlar |
| Role Prompting | Uzman bakış açısı sunar | Rol doğru tanımlanmalıdır | Teknik analizler |

---

# Genel Değerlendirme

Yapılan testler sonucunda farklı prompt tekniklerinin farklı ihtiyaçlara uygun olduğu görülmüştür.

- Hızlı ve basit işlemler için Zero-shot Prompt yeterlidir.
- Belirli bir formatın korunması gerektiğinde One-shot Prompt tercih edilmelidir.
- Kurumsal rapor ve standart belge hazırlamada Few-shot Prompt daha başarılı sonuç vermektedir.
- Teknik analiz ve uzman görüşü gerektiren konularda ise Role Prompting en etkili yöntem olarak öne çıkmaktadır.

Kurumsal uygulamalarda bu tekniklerin birlikte kullanılması, daha kaliteli ve tutarlı çıktılar elde edilmesini sağlayacaktır.
