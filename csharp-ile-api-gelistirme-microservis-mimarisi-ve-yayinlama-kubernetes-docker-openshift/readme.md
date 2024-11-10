# C# ile Microservis Mimarisi ve Yayınlama (Kubernetes, Docker, OpenShift)

## Eğitim Süresi:

**Format 1**

- **5 Gün**
- **Ders Süresi:** 50 dakika
- **Eğitim Saati:** 10:00 - 17:00

**Format 2**

- **12 Gün**
- **Ders Süresi:** 50 dakika
- **Eğitim Saati:** 10:00 - 17:00

## C# ile Microservis Mimarisi ve Yayınlama (Kubernetes, Docker, OpenShift)**

Bu eğitim, yazılım geliştirme dünyasında giderek daha fazla önem kazanan mikroservis mimarisi, konteynerleştirme ve bulut tabanlı dağıtım süreçleri konularında derinlemesine bilgi edinmek isteyen yazılım geliştiricileri, DevOps mühendisleri ve sistem yöneticileri için tasarlanmıştır. Eğitim, C# dilinde mikroservis geliştirme, Docker ile konteynerleştirme ve modern bulut platformları olan Kubernetes ve OpenShift üzerinde dağıtım yapma süreçlerini kapsamlı bir şekilde ele alacaktır.

Bu 5 günlük eğitim, katılımcıların mikroservis mimarisine dair sağlam bir temel oluşturmalarına ve mikroservislerin nasıl geliştirileceği, yönetileceği, ölçeklendirileceği ve dağıtılacağı konusunda pratik bilgi edinmelerine olanak tanır. Katılımcılar, günümüz yazılım geliştirme ve operasyon süreçlerinde yaygın olarak kullanılan Docker konteyner teknolojileri, Kubernetes orkestrasyon araçları ve OpenShift platformu üzerinde uygulamalarını nasıl yönetebileceklerini öğreneceklerdir.

## Eğitim Hedefi:

- Katılımcılar, mikroservis mimarisinin temellerini öğrenip, modern yazılım geliştirme süreçlerinde nasıl etkili bir şekilde uygulayabileceklerini keşfedecekler.
- C# dilinde mikroservis geliştirme konusunda derinlemesine bilgi sahibi olacaklar.
- Docker ile mikroservislerin konteynerleştirilmesini ve Docker Compose ile çoklu servisin nasıl yönetileceğini öğrenecekler.
- Kubernetes ile konteynerleştirilmiş uygulamaların nasıl orkestre edileceği ve yönetileceği hakkında bilgi sahibi olacaklar.
- OpenShift üzerinde uygulamaların yönetimi, dağıtımı ve ölçeklenmesi konularında uygulamalı bilgiler edinerek bulut tabanlı ortamlarda üretim uygulamaları geliştirme yetkinliği kazanacaklar.

## Eğitim İçeriği:

### **1. Gün: Mikro Servis Mimarisi ve Temelleri**

**1.1. Mikro Servis Mimarisi Tanıtımı**

- Mikro servislerin ne olduğu ve monolitik mimariden farkları.
- Mikro servislerin avantajları ve zorlukları.
- Mikro servislerin modern yazılım geliştirmedeki rolü.

**1.2. Mikro Servis Tasarımı**

- Mikro servislerin tasarımı: Bağımsız servisler, API’ler ve veri yönetimi.
- Domain-Driven Design (DDD) prensipleri.
- Veri yönetimi ve veri paylaşımı (Event Sourcing, CQRS).
- API Gateway kavramı ve rolü.

**1.3. Mikro Servis İletişimi**

- Servisler arası iletişim: Synchronous vs Asynchronous iletişim.
- REST API, gRPC ve mesajlaşma protokolleri (Kafka, RabbitMQ).
- API Gateway ve Load Balancer kullanımı.

**1.4. Temel Araçlar ve Kütüphaneler**

- **C# ile mikro servis geliştirme için temel araçlar**: ASP.NET Core, Entity Framework Core, MediatR.
- Bağımlılık yönetimi: Dependency Injection (DI) ve Inversion of Control (IoC).
- API geliştirme ve versiyonlama.

---

### **2. Gün: C# ile Mikro Servis Geliştirme**

**2.1. Mikro Servislerin C# ile Geliştirilmesi**

- ASP.NET Core kullanarak temel mikro servis oluşturma.
- API oluşturma, Controller ve Routing kullanımı.
- JSON formatında veri gönderme ve alma (Serialization & Deserialization).

**2.2. Veritabanı Yönetimi ve Entegrasyonu**

- Mikro servislerde veritabanı yönetimi: Her servis için bağımsız veritabanı tasarımı.
- Entity Framework Core ile veritabanı bağlantıları.
- Veritabanı şemaları ve migration yönetimi.

**2.3. Servisler Arası İletişim ve Veri Paylaşımı**

- RESTful servisler arası iletişim.
- C# ile HTTP Client kullanarak dış servislerle iletişim.
- JSON Web Token (JWT) ile güvenli API erişimi.

**2.4. Mikro Servislerde Hata Yönetimi ve Logging**

- Hata yönetimi, exception handling ve retry mekanizmaları.
- Logging (Serilog, NLog) ve metrikler ile uygulama izleme.
- Circuit Breaker ve Resilience Patterns.

---

### **3. Gün: Docker ile Konteynerleştirme**

**3.1. Docker Nedir?**

- Docker’ın temel kavramları: Container, Image, Dockerfile, Docker Compose.
- Docker’ın mikro servis mimarisindeki rolü.

**3.2. C# Uygulamasını Docker ile Konteynerleştirme**

- ASP.NET Core uygulamasını Docker konteyneri içinde çalıştırma.
- Dockerfile oluşturma ve C# mikro servisini Docker imajına dönüştürme.
- Docker Compose kullanarak birden fazla servisi yönetme.

**3.3. Konteyner Yönetimi**

- Docker CLI komutları ile konteyner yönetimi (docker run, docker ps, docker logs).
- Docker hub ve özel registry kullanımı.

**3.4. Docker Networking**

- Docker ağları: Bridge, Host, Overlay.
- Konteynerler arası iletişim: Docker network kullanımı.

---

### **4. Gün: Kubernetes ile Dağıtım ve Yönetim**

**4.1. Kubernetes Temelleri**

- Kubernetes’in mikro servis mimarisindeki yeri.
- Kubernetes kavramları: Pod, Deployment, Service, ReplicaSet, Namespace.
- Kubernetes Cluster’ı kurma ve temel komutlar (`kubectl`).

**4.2. Kubernetes ile C# Mikro Servisi Dağıtma**

- Kubernetes’te pod oluşturma ve yönetme.
- Docker imajını Kubernetes’e dağıtma (Deployment, Service).
- Pod’lar arasında yük dengeleme ve servis keşfi.

**4.3. Kubernetes Configuration ve Secret Management**

- ConfigMap ve Secret kullanımı.
- Kubernetes’te çevresel değişkenler ve konfigürasyon yönetimi.

**4.4. Kubernetes ile Ölçeklenebilirlik**

- Pod’ları ölçeklendirme (horizontal scaling).
- ReplicaSet ve Auto-scaling.
- Rolling updates ve deployment stratejileri.

---

### **5. Gün: OpenShift ile Gelişmiş Dağıtım ve Yönetim**

**5.1. OpenShift Temelleri**

- OpenShift nedir, Kubernetes ile farkları.
- OpenShift özellikleri: BuildConfig, DeploymentConfig, Route.
- OpenShift CLI (oc) ve web konsolu kullanımı.

**5.2. OpenShift’te C# Mikro Servis Dağıtımı**

- OpenShift üzerinde C# mikro servislerinin dağıtımı.
- DeploymentConfig, Route ve Service yönetimi.
- OpenShift ile Docker imajlarını yönetme.

**5.3. CI/CD ile Mikro Servis Dağıtımı**

- Jenkins, GitLab CI, OpenShift Pipelines ile sürekli entegrasyon ve dağıtım.
- GitOps yaklaşımı ile sürüm yönetimi ve otomatik dağıtımlar.
- Helm kullanarak uygulama paketleme.

**5.4. İzleme ve Log Yönetimi**

- OpenShift Monitoring ve Logging araçları.
- Prometheus ve Grafana ile metrik toplama ve izleme.
- ELK Stack (Elasticsearch, Logstash, Kibana) ile log yönetimi.

**5.5. Eğitim Kapanışı ve Değerlendirme**

- Katılımcıların öğrendiklerini uygulayabilecekleri bir proje çalışması.
- Mikro servis mimarisi ile ilgili en iyi uygulamaların tartışılması.
- Katılımcıların soruları ve geri bildirimlerinin alınması.

---

## **Eğitim Yöntemi:**

- **Teorik Dersler**: Temel kavramların anlatımı, mikro servislerin temelleri.
- **Canlı Kodlama**: Gerçek dünyadan örnekler üzerinden mikro servislerin adım adım geliştirilmesi.
- **Uygulamalı Projeler**: Katılımcıların öğrendiklerini uygulamalı olarak geliştirmeleri.
- **Etkileşimli Tartışmalar ve Soru-Cevap**: Katılımcıların soruları üzerinden derinlemesine tartışmalar.
- **Proje Tabanlı Öğrenme**: Eğitim sonunda katılımcılara, öğrendikleri bilgileri projelere uygulama fırsatı.

---

## **Hedef Kitle:**

- Yazılım geliştiriciler ve mühendisler.
- C# ile mikro servis geliştirmeyi öğrenmek isteyenler.
- Kubernetes, Docker ve OpenShift üzerinde dağıtım yapacak profesyoneller.
- DevOps mühendisleri ve yazılım mimarları.
- Yeni teknolojilere ilgi duyan ve mikro servis mimarisi ile bulut çözümlerini öğrenmek isteyen tüm profesyoneller.

## **Katılımcılardan Beklentilerimiz**

1. **Temel Linux Bilgisi:**
   Katılımcıların temel Linux bilgisine sahip olmaları, eğitimde kullanılan ortamların yönetimi ve terminal komutları ile çalışmada kolaylık sağlayacaktır.

2. **Temel Konteyner ve Kubernetes Bilgisi:**
   Temel seviyede konteyner ve Kubernetes bilgisi, eğitimde işlenecek kavramların daha iyi anlaşılmasına yardımcı olacaktır. Ancak, bu bilgi zorunlu değildir; temel kavramlar eğitim sırasında açıklanacaktır.

3. **Temel Programlama Bilgisi (C#):**
   Katılımcıların C# diline temel düzeyde aşina olmaları, eğitimdeki API geliştirme süreçlerini daha verimli takip etmelerini sağlayacaktır.

4. **Web ve API Geliştirme Konseptlerine Hakimiyet:**
   Katılımcıların API geliştirme ve RESTful servisler gibi temel web geliştirme konseptlerine dair bilgi sahibi olmaları, eğitimdeki C# API geliştirme kısmını daha kolay anlamalarına yardımcı olacaktır.

5. **Aktif Katılım:**
   Eğitim sürecinde katılımcıların aktif katılım göstermeleri, grup çalışmaları, kodlama pratikleri ve tartışmalara dahil olmaları beklenir. Bu, öğrenilen bilgilerin daha hızlı ve etkin bir şekilde pekişmesini sağlar.

6. **Öğrenmeye İstekli Olma:**
   Katılımcıların yeni konulara ve teknolojiye açık olmaları, öğrenmeye istekli olmaları eğitim sürecini daha verimli hale getirecektir.

7. **Takım Çalışmasına Yatkınlık:**
   Microservices ve Kubernetes gibi konular, takım çalışmasını gerektirir. Katılımcıların işbirliği yaparak çözümler geliştirebilmesi, projelerin başarıyla tamamlanmasına katkı sağlar.

8. **Problem Çözme Yeteneği:**
   Katılımcıların, karşılaştıkları teknik sorunları çözme ve farklı çözüm yolları geliştirme yeteneğine sahip olmaları, eğitimde işlenecek konuları daha kolay uygulamalı hale getirecektir.

9. **Zaman Yönetimi:**
   Eğitimde verilen sürelere uyum sağlamak ve belirli zaman dilimlerinde görevleri tamamlamak, eğitimde başarıyı artıracaktır.

10. **Sürekli Geri Bildirim Alabilme:**
    Katılımcıların geri bildirim almayı ve bu geri bildirimleri kişisel gelişimlerine dahil etmeyi kabul etmeleri gereklidir.

11. **Esneklik ve Adaptasyon Yeteneği:**
    Microservices mimarisi ve Kubernetes gibi dinamik teknolojilerle çalışırken, katılımcıların esnek olmaları ve yeni teknolojiye hızla adapte olmaları gerekmektedir.

12. **Eleştirel Düşünme ve Analitik Yaklaşım:**
    Katılımcıların, geliştirme süreçlerini eleştirel bir bakış açısıyla değerlendirebilmeleri, daha iyi çözümler geliştirebilmelerine olanak tanır.

13. **Kendi Gelişimini Takip Etme:**
    Katılımcıların eğitim süreci boyunca kendi gelişimlerini takip etmeleri ve eksik olduğu alanlarda öğrenmeye devam etmeleri beklenir.

14. **Pratik Uygulamalar Yapabilme:**
    Eğitimde öğrendikleri teorik bilgileri gerçek dünya senaryolarında uygulayabilme yeteneğine sahip olmaları, katılımcıların daha hızlı gelişmelerine yardımcı olur.

[Eğitim ana materyalleri, sadece eğitmenler için](https://github.com/TuncerKARAARSLAN-VB/training-kit-csharp-ile-mikro-servis-mimarisi)
