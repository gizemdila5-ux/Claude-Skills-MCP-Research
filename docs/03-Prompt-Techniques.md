# Prompt Teknikleri

## 1. Prompt Nedir?

Prompt, yapay zekâ modeline verilen talimat veya istektir. Yapay zekânın üreteceği cevabın doğruluğu ve kalitesi büyük ölçüde prompt'un nasıl yazıldığına bağlıdır.

İyi hazırlanmış bir prompt;

- Açık ve anlaşılır olmalıdır.
- Gereksiz bilgiler içermemelidir.
- Beklenen çıktıyı net şekilde belirtmelidir.
- Gerekirse örnek içermelidir.
- Görevi adım adım tanımlamalıdır.

Kurumsal uygulamalarda doğru prompt kullanımı, yapay zekâdan daha kaliteli ve tutarlı sonuçlar alınmasını sağlar.

---

# 2. Prompt Yazarken Dikkat Edilmesi Gerekenler

Başarılı bir prompt hazırlamak için aşağıdaki kurallara dikkat edilmelidir.

- Açık ve net ifadeler kullanılmalıdır.
- Gereksiz detaylardan kaçınılmalıdır.
- Beklenen çıktı belirtilmelidir.
- Çıktının formatı tanımlanmalıdır.
- Gerekirse örnek verilmelidir.
- Karmaşık görevler küçük parçalara ayrılmalıdır.

---

# 3. Zero-shot Prompt

Zero-shot Prompt, modele yalnızca görevin verilmesi ve herhangi bir örnek sunulmamasıdır.

## Örnek Prompt

"Bir penetrasyon testi raporunun yönetici özetini hazırla."

### Avantajları

- Hızlıdır.
- Kullanımı kolaydır.
- Basit görevlerde başarılıdır.

### Dezavantajları

- Çıktı standart olmayabilir.
- Ayrıntı seviyesi değişebilir.
- Tutarlılık düşük olabilir.

---

# 4. One-shot Prompt

One-shot Prompt tek bir örnek verilerek oluşturulan istem tekniğidir.

## Örnek

Örnek rapor gösterilir ve benzerinin hazırlanması istenir.

### Avantajları

- Daha tutarlı sonuç verir.
- Format korunur.
- Öğrenmesi kolaydır.

### Dezavantajları

- Tek örnek yetersiz kalabilir.
- Karmaşık görevlerde başarı düşebilir.

---

# 5. Few-shot Prompt

Few-shot Prompt, modele birden fazla örnek verilerek oluşturulur.

## Örnek

Önce iki veya üç örnek güvenlik raporu gösterilir, ardından yeni rapor oluşturması istenir.

### Avantajları

- Kaliteli sonuç üretir.
- Tutarlı yapı sağlar.
- Kurumsal belgeler için uygundur.

### Dezavantajları

- Daha uzun prompt gerektirir.
- Hazırlanması zaman alabilir.

---

# 6. Role Prompting

Role Prompting tekniğinde modele belirli bir rol verilir.

## Örnek

"20 yıllık deneyime sahip bir siber güvenlik uzmanı gibi davranarak aşağıdaki güvenlik raporunu değerlendir."

### Avantajları

- Daha profesyonel cevaplar üretir.
- Uzman bakış açısı sağlar.
- Teknik konularda başarılıdır.

### Dezavantajları

- Rol doğru tanımlanmazsa istenen sonuç alınamayabilir.

---

# 7. XML Etiketleri ile Prompt Tasarımı

XML etiketleri kullanılarak prompt daha düzenli hâle getirilebilir.

## Örnek

```xml
<görev>
Penetrasyon testi raporu hazırla.
</görev>

<çıktı>
PDF formatında rapor oluştur.
</çıktı>
```

### Avantajları

- Düzenli yapı sağlar.
- Büyük projelerde okunabilirliği artırır.
- Kurumsal sistemlerde kullanımı kolaydır.

---

# 8. Task Decomposition (Görev Bölme)

Task Decomposition, büyük ve karmaşık görevleri küçük adımlara ayırma tekniğidir.

## Örnek

Bir güvenlik raporu hazırlama süreci;

1. Verileri oku.
2. Güvenlik açıklarını belirle.
3. Risk seviyesini hesapla.
4. Çözüm önerileri oluştur.
5. Yönetici özeti yaz.
6. PDF raporu oluştur.

### Avantajları

- Hata oranını azaltır.
- Büyük projelerde başarıyı artırır.
- Sürecin kontrolünü kolaylaştırır.

---

# 9. Prompt Tekniklerinin Karşılaştırılması

| Teknik | Kullanım Amacı | Avantajı | Dezavantajı |
|---------|----------------|-----------|-------------|
| Zero-shot | Basit görevler | Hızlı | Tutarsız olabilir |
| One-shot | Benzer görevler | Daha düzenli | Tek örnek yetersiz olabilir |
| Few-shot | Kurumsal belgeler | Kaliteli çıktı | Uzun prompt gerekir |
| Role Prompting | Uzman bakış açısı | Profesyonel sonuç | Rol doğru tanımlanmalıdır |
| XML Prompt | Yapısal görevler | Düzenli çıktı | Hazırlaması daha uzun sürer |
| Task Decomposition | Büyük projeler | Daha doğru sonuç | Planlama gerektirir |

---

# 10. Kurumsal Kullanım Önerileri

Kurumsal ortamlarda aşağıdaki tekniklerin birlikte kullanılması önerilmektedir.

- Teknik rapor hazırlamada Role Prompting
- Standart belge üretiminde Few-shot Prompt
- Büyük iş süreçlerinde Task Decomposition
- Sistem entegrasyonlarında XML Prompt

Bu tekniklerin birlikte kullanılması daha kaliteli, standart ve güvenilir çıktılar elde edilmesini sağlar.

---

# 11. Değerlendirme

Prompt mühendisliği, üretken yapay zekâ sistemlerinden yüksek kaliteli sonuçlar elde etmek için kritik öneme sahiptir. Doğru tekniklerin seçilmesi; çıktıların doğruluğunu, tutarlılığını ve kullanılabilirliğini artırmaktadır. Özellikle kurumsal projelerde Few-shot, Role Prompting ve Task Decomposition tekniklerinin birlikte kullanılması önerilmektedir.
