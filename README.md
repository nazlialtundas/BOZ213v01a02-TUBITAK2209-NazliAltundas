# Halüsinasyon Avı
### Yapay zekâ tarafından üretilen bilgileri sorgulamak ve kaynak temelli değerlendirme becerilerini geliştirmek için etkileşimli bir öğrenme aracı.

##  Proje Hakkında

**Halüsinasyon Avı**, üniversite öğrencilerinin üretken yapay zekâ araçları tarafından oluşturulan bilgileri eleştirel bir bakış açısıyla değerlendirmelerini, akademik kaynakları incelemelerini ve kararlarını kanıtlara dayandırmalarını desteklemek amacıyla geliştirilen yapay zekâ destekli bir web uygulamasıdır.

Günümüzde ChatGPT ve Gemini gibi üretken yapay zekâ araçları, kullanıcıların sorularına hızlı ve akıcı yanıtlar sunabilmektedir. Ancak bu yanıtlar her zaman doğru olmayabilir. Yapay zekâ modellerinin gerçekte var olmayan bilgileri üretmesi veya yanlış bilgileri güvenilir bir ifadeyle sunması, *yapay zekâ halüsinasyonu* olarak adlandırılmaktadır.

Halüsinasyon Avı, bu probleme yönelik olarak kullanıcıların yalnızca yapay zekâ tarafından sunulan yanıtları tüketmesini değil, bu yanıtları sorgulamasını ve ilgili kaynaklarla karşılaştırmasını hedeflemektedir.

Proje kapsamında Python programlama dili ve Streamlit kullanılarak geliştirilen web uygulaması, akademik kaynak arama sistemlerini ve üretken yapay zekâ teknolojilerini bir araya getirmektedir.

##  Projenin Amacı

Projenin temel amacı, üniversite öğrencilerinin yapay zekâ tarafından üretilen bilgileri kaynak temelli değerlendirme becerilerini destekleyen etkileşimli bir öğrenme ortamı oluşturmaktır.

Bu doğrultuda öğrencilerin:

- Yapay zekâ tarafından oluşturulan bilgileri sorgulamaları,
- Akademik kaynakları incelemeleri,
- Bilgileri farklı kaynaklarla karşılaştırmaları,
- İddiaları somut kanıtlarla değerlendirmeleri,
- Kararlarını gerekçelendirerek açıklamaları

amaçlanmaktadır.

##  Nasıl Çalışır?

Halüsinasyon Avı, kullanıcıların bir soru üzerinden bilgi doğrulama ve kaynak değerlendirme sürecine katılmalarını sağlayan bir sistem olarak tasarlanmıştır.

Uygulamanın temel çalışma aşamaları şöyledir:

**1. Soru oluşturma**

Kullanıcı, merak ettiği bir konuyla ilgili soru girer veya uygulamada sunulan hazır sorulardan birini seçer.

**2. Akademik kaynakların aranması**

Sistem, girilen soruyla ilişkili akademik yayınları OpenAlex ve Crossref gibi kaynak altyapıları üzerinden arar. Elde edilen yayın bilgileri ve erişilebilir içerikler değerlendirme sürecinde kullanılır.

**3. Yapay zekâ tarafından alternatif yanıtların oluşturulması**

Google Gemini API kullanılarak ilgili soru ve kaynak bilgileri doğrultusunda iki alternatif yanıt oluşturulur. Bu yanıtlar, kullanıcının kaynakları inceleyerek aralarındaki bilgi ve kanıt farklılıklarını değerlendirebilmesi için sunulur.

**4. Kaynakların incelenmesi**

Kullanıcı, sunulan akademik kaynakları inceler. İngilizce kaynak içerikleri için Türkçe çeviri desteğinden yararlanabilir.

**5. Yanıtların değerlendirilmesi**

Kullanıcı, hangi yanıtın kaynaklarla daha iyi desteklendiğini belirler ve kararını ilgili kaynaklardan elde ettiği kanıtlarla açıklar.

**6. Sonuçların kaydedilmesi**

Tamamlanan değerlendirmeler katılımcı koduyla birlikte kaydedilir. Böylece önceki sorular, alternatif yanıtlar ve kullanıcı değerlendirmeleri araştırma sürecinde incelenebilir.

##  Kullanılan Teknolojiler

| Teknoloji | Kullanım amacı |
|---|---|
| Python | Uygulamanın temel programlama dili |
| Streamlit | Web arayüzünün geliştirilmesi |
| Google Gemini API | Yapay zekâ destekli içerik üretimi ve Türkçe çeviri |
| OpenAlex | Akademik yayınların aranması |
| Crossref | Akademik yayın metadata bilgilerinin alınması |
| SQLite | Katılımcı değerlendirmelerinin saklanması |
| JSON | Yapılandırılmış veri ve soru içeriklerinin tutulması |
| Python-dotenv | Ortam değişkenlerinin ve API anahtarlarının yönetimi |


##  Eğitimsel Yaklaşım

Halüsinasyon Avı, öğrencilerin yapay zekâ tarafından sunulan bilgileri doğrudan kabul etmeleri yerine, bu bilgileri sorgulamalarını ve kaynaklarla karşılaştırmalarını teşvik eden uygulamalı bir öğrenme yaklaşımına dayanmaktadır.

Uygulama içerisinde öğrencilerden yalnızca bir yanıt seçmeleri değil, seçimlerini kanıtlarla açıklamaları da beklenmektedir.

Bu yönüyle proje; yapay zekâ okuryazarlığı, bilgi okuryazarlığı, eleştirel düşünme ve kanıta dayalı değerlendirme becerileriyle ilişkilidir.

https://youtu.be/sma7naP8oN4?si=rFwr4yfJcpTj4-dj
