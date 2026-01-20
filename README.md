Bu Java projesi, bir öğrencinin akademik başarısını ölçmek ve detaylı bir durum raporu sunmak amacıyla tasarlanmış kapsamlı bir Not Hesaplama ve Analiz Sistemidir.

Kodlarda görülen temel işleyiş ve özellikler şunlardır:

1. Veri Girişi ve Hesaplama
Program kullanıcıdan Vize, Final ve Ödev olmak üzere üç farklı not girişi alır. Bu notları şu ağırlıklara göre işleyerek dönem sonu ortalamasını hesaplar:

Vize: %30

Final: %40

Ödev: %30

2. Başarı Değerlendirme Kriterleri
Sistem sadece ortalamayı hesaplamakla kalmaz, öğrencinin durumunu çeşitli kurallara göre analiz eder:

Geçme/Kalma Durumu (isPassingGrade): Öğrencinin dersi geçebilmesi için iki şart aranır: Genel ortalamanın 50 veya üzeri olması VE Final notunun en az 50 olması.

Harf Notu (getLetterGrade): Ortalamaya karşılık gelen harf notunu (A, B, C, D veya F) standart aralıklara göre belirler (Örn: 90-100 arası A).

Onur Listesi (isHonorList): Öğrencinin genel ortalaması 85'in üzerindeyse ve diğer tüm notları (vize, final, ödev) 70'ten yüksekse, öğrenci "Onur Listesi"ne dahil edilir.

Bütünleme Hakkı (hasRetakeRight): Eğer öğrencinin ortalaması 40 ile 50 arasındaysa, sistem öğrencinin bütünleme sınavına girme hakkı olduğunu ("VAR") belirtir.

3. Raporlama
Son aşamada, girilen notlar ve hesaplanan tüm veriler (Ortalama, Harf Notu, Geçti/Kaldı Durumu, Onur Listesi ve Bütünleme bilgisi) kullanıcıya düzenli bir rapor halinde konsol ekranında sunulur.

Özetle bu proje, basit bir hesap makinesinin ötesinde, üniversite not sistemlerinde kullanılan koşullu geçme ve başarı kriterlerini simüle eden modüler bir uygulamadır.
