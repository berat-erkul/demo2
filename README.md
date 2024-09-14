# Satış Kayıtları Yönetim Sistemi (Sales Records Management System)

Bu proje, **Spring Boot** ve **Thymeleaf** kullanarak basit bir satış kayıtları yönetim sistemi geliştirmeyi amaçlamaktadır. Proje, kullanıcıların çeşitli ürünlerin gelir, maliyet ve kârlarını tablo halinde görüntülemesine olanak sağlar. Kâr değerine göre satırların renklerini dinamik olarak değiştiren bir arayüz sunar (kâr pozitifse yeşil, negatifse kırmızı).


<img width="1016" alt="Screenshot 2024-09-15 at 00 41 59" src="https://github.com/user-attachments/assets/6a7b6798-173e-4dfb-b51c-e39f51873981">


---

## Projede Öğrendiklerim ve Üzerinde Çalıştıklarım

### 1. Spring Boot Framework'ü Kullanımı
- **Spring Boot**'un hızlı başlangıç ve yapılandırma yeteneklerini öğrendim.
- Projede Spring Boot'un temel özelliklerini ve yapılandırmalarını kullanarak backend ve frontend iletişimini sağladım.
- Projenin dosya yapısına uygun olarak statik içeriklerin (CSS, JS) nereye yerleştirileceğini kavradım.

### 2. Thymeleaf ile Dinamik İçerik Oluşturma
- **Thymeleaf** şablon motorunu kullanarak dinamik HTML içeriği oluşturmayı öğrendim.
- `th:each`, `th:text`, `th:classappend` gibi Thymeleaf direktiflerini kullanarak verilerin tabloya dinamik şekilde nasıl yansıtılacağını deneyimledim.
- Dinamik koşullara göre CSS sınıflarını nasıl uygulayabileceğimi öğrendim. Örneğin, kâr değerine bağlı olarak satırların renginin değişmesini sağlayan `th:classappend` ifadesini kullandım.

### 3. CSS ile Modern ve Responsive Arayüz Tasarımı
- **CSS** kullanarak kullanıcı dostu, modern ve responsive bir arayüz tasarladım.
- Tabloya gölgeler, yuvarlatılmış köşeler ve hover (üzerine gelindiğinde) efektleri ekleyerek daha estetik bir görünüm sağladım.
- `@media` sorgularını kullanarak projenin mobil cihazlar için duyarlı (responsive) olmasını sağladım.

### 4. Statik Kaynakların Yönetimi
- **Spring Boot** projelerinde CSS ve JavaScript gibi statik dosyaların nasıl yönetileceğini öğrendim.
- CSS dosyalarını `src/main/resources/static` dizininde tutarak bunları projede efektif bir şekilde kullanmayı deneyimledim.

### 5. Kar Zarar Hesaplaması ve Verilerin Görselleştirilmesi
- Tablo üzerinde gelir, maliyet ve kâr arasındaki farkları hesaplamayı ve bu farklara göre verilerin görselleştirilmesini öğrendim.
- Kâr hesaplama işlemini Thymeleaf yardımıyla doğrudan arayüzde yaparak, kullanıcıya dinamik bir deneyim sundum.

---

## Proje Özellikleri

- **Gelir, Maliyet ve Kâr Tablosu:** Kullanıcı, ürünlerin gelir, maliyet ve kârlarını tablo şeklinde görebilir.
- **Renkli Kâr Zarar Göstergesi:** Kâr pozitifse satır yeşil, negatifse satır kırmızı renkte gösterilir.
- **Responsive Tasarım:** Mobil cihazlara uyumlu modern bir tablo tasarımı içerir.
- **Dinamik Veriler:** Veriler dinamik olarak şablon motoru aracılığıyla HTML sayfasına yansıtılır.

---

leri Düzey Geliştirme İmkanları

Proje temel özellikler sunmakla birlikte, daha fazla işlevsellik eklemek mümkündür:

	•	Veritabanı Entegrasyonu: Veritabanı ile satış kayıtlarını depolama ve sorgulama imkanı.
	•	Kullanıcı Girişi ve Yetkilendirme: Farklı kullanıcılar için yönetici ve normal kullanıcı yetkileri eklemek.
	•	Raporlama Özellikleri: Kâr ve zararları grafiklerle görselleştirmek.

Bu proje, Spring Boot, Thymeleaf ve CSS ile modern bir web uygulaması geliştirme deneyimi kazandırdı. Bu yapı ile daha karmaşık projeler geliştirmeye hazır olduğumu hissediyorum.
