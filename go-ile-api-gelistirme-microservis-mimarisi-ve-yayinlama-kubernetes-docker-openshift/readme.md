# Go ile API Geliştirme, Microservis Mimarisi ve Yayınlama (Kubernetes, Docker, OpenShift) Eğitimi

## Eğitim Süresi:

- **5 Gün**
- **Ders Süresi:** 50 dakika
- **Eğitim Saati:** 10:00 - 17:00

**Format 2**

- **12 Gün**
- **Ders Süresi:** 50 dakika
- **Eğitim Saati:** 10:00 - 17:00

## Eğitim Hedefi:

Bu eğitim, katılımcıların Go programlama diliyle API geliştirmeyi, microservis mimarisi ile uygulamaların nasıl tasarlanacağını, Docker ile konteynerize edilip Kubernetes ve OpenShift ortamlarında dağıtım süreçlerinin nasıl gerçekleştirileceğini öğretmeyi amaçlamaktadır. Eğitim sonunda katılımcılar, modern yazılım geliştirme süreçlerinde kullanılan en güncel teknolojilerle hem API hem de microservis mimarisini baştan sona inşa edebilir hale gelecekler.

## Eğitim İçeriği:

### **Bölüm 1: Microservis Mimarisi ve Go’ya Giriş**

1. **Microservis Mimarisi Nedir?**
   - **Microservis Tanımı ve Temel Kavramlar:**
     Microservisler, büyük, monolitik uygulamaları daha küçük, bağımsız ve yönetilebilir parçalara ayıran bir yazılım mimarisidir. Her bir servis belirli bir işlevi yerine getirir ve birbirinden bağımsız çalışabilir.
   - **Microservislerin Avantajları:**
     - Yüksek ölçeklenebilirlik
     - Bağımsız dağıtım ve geliştirme
     - Hızlı hata tespiti ve düzeltme
   - **Microservislerin Zorlukları:**
     - Servisler arası iletişim
     - Veri tutarlılığı
     - Dağıtık sistemler yönetimi

2. **Go ile Microservis Geliştirme**
   - **Go Dilinin Microservis Geliştirmeye Uygunluğu:**
     Go’nun hızlı çalışma süresi, düşük bellek kullanımı ve yüksek performansı, onu microservis geliştirme için ideal bir dil haline getirir.
   - **Go Dilinin Temel Özellikleri:**
     - Go dilinde concurrency (eşzamanlılık)
     - HTTP sunucuları ve REST API'leri geliştirme
     - Paket yönetimi ve modüller
   - **Go ile Microservis Geliştirme Çerçeveleri:**
     - **Go-kit:** Microservisler için modüler bir çerçeve
     - **Gin ve Echo:** Hızlı HTTP sunucuları geliştirmek için popüler Go çerçeveleri

---

### **Bölüm 2: Docker ile Konteynerleştirme**

1. **Docker’a Giriş ve Temel Kavramlar**
   - **Docker Nedir?**  
     Docker, yazılımları ve uygulamaları bağımlılıklarıyla birlikte izole edilmiş konteynerlerde çalıştıran bir platformdur. Uygulamanın her ortamda aynı şekilde çalışmasını sağlar.
   - **Docker’ın Temel Bileşenleri:**
     - **Docker Image**: Uygulamanın bağımlılıklarıyla birlikte paketlenmiş hali.
     - **Docker Container**: Çalışan bir Docker image.
     - **Dockerfile**: Docker imajlarını oluşturmak için kullanılan yapılandırma dosyası.
   - **Docker Komutları ve Kullanımı:**
     - `docker build`, `docker run`, `docker ps`, `docker logs`
     - Docker Compose ile birden fazla konteyneri yönetme

2. **Go Uygulamasını Docker ile Konteynerleştirme**
   - **Go Uygulaması İçin Dockerfile Yazma**
     - Go uygulaması için uygun bir Dockerfile oluşturma
     - Multi-stage build kullanarak Docker imajını optimize etme
   - **Docker ile Go Microservisini Çalıştırma ve Test Etme**
     - Go uygulamasını Docker konteynerinde çalıştırma
     - Veritabanı ve diğer mikro hizmetlerle entegrasyon
   - **Docker Compose ile Çoklu Go Microservislerinin Yönetilmesi**
     - Docker Compose ile birden fazla Go mikro servisi çalıştırma
     - Konteynerler arası ağ yapılandırması

---

### **Bölüm 3: Kubernetes ile Orkestrasyon**

1. **Kubernetes’e Giriş**
   - **Kubernetes Nedir?**
     Kubernetes, konteynerleştirilmiş uygulamaların dağıtımı, ölçeklendirilmesi ve yönetilmesi için açık kaynaklı bir platformdur.
   - **Kubernetes Bileşenleri:**
     - **Pod:** En küçük dağıtım birimi.
     - **Deployment:** Pod’ları yönetme, güncelleme ve ölçeklendirme.
     - **Service:** Mikro hizmetlerin birbirine bağlanması ve dış dünyaya açılması.
     - **Ingress:** Dışarıdan gelen isteklerin yönlendirilmesi.
   - **Kubernetes API Server, Controller Manager ve Scheduler**

2. **Go Microservislerini Kubernetes Üzerinde Yayınlama**
   - **Kubernetes Deployment Oluşturma:**
     - Go uygulamaları için Kubernetes deployment’ları oluşturma
     - Pod’ların ölçeklenmesi
   - **Kubernetes Service ve Ingress Kullanımı:**
     - Go microservisleri arasındaki iletişimi sağlayacak Kubernetes servisleri oluşturma
     - Dışa açık erişim için Ingress yapılandırması
   - **Kubernetes ile Yük Dengeleme ve Auto-Scaling:**
     - Yük dengeleme
     - Horizontal Pod Autoscaler ile otomatik ölçeklendirme
     - Kaynak yönetimi (CPU, bellek)

3. **Kubernetes ile DevOps Entegrasyonu**
   - **CI/CD Pipeline’ları Kurma:**
     - Kubernetes üzerinde CI/CD süreçlerinin yapılandırılması
     - Jenkins, GitLab CI, CircleCI ile entegrasyon
   - **Kubernetes ve Helm ile Uygulama Dağıtımı**
     - Helm Charts kullanarak Kubernetes üzerinde Go microservis dağıtımı

---

### **Bölüm 4: OpenShift ile Yayınlama ve Yönetim**

1. **OpenShift’e Giriş**
   - **OpenShift Nedir?**
     OpenShift, Kubernetes tabanlı, kurumsal düzeyde konteyner yönetim platformudur. Kubernetes’i geliştirir ve birçok ek özellik sunar.
   - **OpenShift ile Kubernetes Arasındaki Farklar:**
     - OpenShift, güvenlik, çoklu kullanıcı yönetimi ve geliştirme araçları sunar.
   - **OpenShift Komutları ve Yönetim Araçları (oc CLI)**

2. **Go Microservislerini OpenShift Üzerinde Yayınlama**
   - **OpenShift ile Deployment ve Pod Yönetimi**
     - Go uygulamalarını OpenShift üzerinde dağıtmak için deployment ve pod’lar oluşturma
   - **OpenShift ile Service ve Route Yönetimi**
     - Mikroservislere dış erişim sağlamak için OpenShift Route oluşturma
   - **OpenShift ile Kaynak Yönetimi ve İzinler:**
     - Role-Based Access Control (RBAC)
     - OpenShift Security Context ve Network Policies

3. **OpenShift CI/CD Entegrasyonu**
   - **OpenShift Pipelines (Tekton) ile CI/CD Süreçleri:**
     - OpenShift üzerinde pipeline’lar kurma ve otomatik dağıtım yapma
     - Jenkins ile OpenShift entegrasyonu
   - **Automated Builds ve Deployments**
     - OpenShift ile Go uygulamalarını otomatik olarak derleyip dağıtma

---

### **Bölüm 5: Mikro Servislerin Yönetimi ve İzlenmesi**

1. **Mikro Servislerin İzlenmesi (Monitoring)**
   - **Prometheus ve Grafana ile İzleme:**  
     - Prometheus kullanarak Go microservislerini izleme
     - Grafana ile metriklerin görselleştirilmesi
   - **EFK Stack (Elasticsearch, Fluentd, Kibana) ile Log Yönetimi:**
     - Mikro servislerin loglarını toplama ve görselleştirme

2. **Mikro Servislerin Hata Yönetimi ve Debugging**
   - **Distributed Tracing ve Jaeger ile İzleme:**  
     - Go microservislerinde distributed tracing kullanma
     - Jaeger ile hataların izlenmesi
   - **Health Check ve Readiness Probe ile Servis Sağlığı İzleme:**
     - Kubernetes üzerinde sağlık kontrolleri ve hazır olma denetimleri

---

### **Bölüm 6: Uygulama Güvenliği ve İleri Düzey Konular**

1. **Mikro Servislerde Güvenlik**
   - **OAuth2 ve JWT ile Kimlik Doğrulama ve Yetkilendirme**
   - **Mutual TLS ile Güvenli Mikro Servis İletişimi**
   - **API Gateway ve Rate Limiting ile Güvenlik**

2. **Servis Mesh ile Mikro Servis İletişimi ve Güvenliği**
   - **Istio ve Linkerd ile Servis Mesh Kullanımı**
   - **Servis Mesh ile Tracing ve Monitoring**

3. **Yüksek Erişilebilirlik ve Felaket Kurtarma**
   - **Kubernetes ve OpenShift ile Yüksek Erişilebilirlik**
   - **Failover ve Yedekleme Stratejileri**

---

### **Bölüm 7: Proje Yönetimi ve En İyi Uygulamalar**



1. **Microservis Tasarımı ve İyi Uygulamalar**
   - **Domain-Driven Design (DDD) ve Microservis Tasarımı**
   - **Veritabanı Tasarımı: Veritabanı Şeması ve Veri Tabanı Bağımsızlığı**
   - **İletişim Modelleri: Synchronous vs Asynchronous**

2. **Microservislerin Performans Yönetimi ve Optimizasyonu**
   - **Performans Testleri ve Profilleme**
   - **Caching ve Load Balancing Stratejileri**

## Eğitim Yöntemi:

- **Teorik Bilgi Aktarımı:** Her gün belirli konuların teorik anlatımı.
- **Uygulamalı Atölyeler:** Gerçek dünya senaryolarına dayalı uygulamalı çalışmalar. Katılımcılar, Go ile API ve microservis geliştirip Docker, Kubernetes ve OpenShift ile uygulamaları dağıtacaklar.
- **Grup Çalışmaları:** Katılımcıların küçük gruplar halinde çalışarak gerçek bir microservis mimarisi geliştirmeleri ve dağıtmaları.
- **Vaka Çalışmaları:** Gerçek hayattan başarılı Go microservis projelerinin incelenmesi, karşılaşılan zorluklar ve çözüm stratejileri üzerine tartışmalar.

## Eğitim Çıktıları:

Bu eğitimi tamamlayan katılımcılar;
- Go programlama dilinde API ve microservis geliştirme becerilerini kazanmış olacaklar,
- Uygulamalarını Docker ile konteynerize etmeyi öğrenmiş olacaklar,
- Kubernetes üzerinde uygulama dağıtımı ve yönetimi konusunda deneyim kazanacaklar,
- OpenShift ortamında CI/CD süreçlerini kurarak modern bir yazılım geliştirme sürecini baştan sona yönetebileceklerdir.

## Hedef Kitle:

- **Yazılım Geliştiriciler ve Mühendisler:** API ve microservis geliştirme konularında uzmanlaşmak isteyen yazılımcılar.
- **DevOps Uzmanları:** Kubernetes ve OpenShift ile container orkestrasyonu ve CI/CD süreçlerini yönetmek isteyen DevOps profesyonelleri.
- **Sistem Mimarları:** Microservis mimarisi ile yüksek ölçeklenebilir ve esnek sistemler tasarlamak isteyen mimarlar.
- **Teknik Yöneticiler:** Modern yazılım geliştirme süreçlerinde yer almak ve ekibine bu teknolojileri entegre etmek isteyen yöneticiler.

[Eğitim ana materyalleri, sadece eğitmenler için](https://github.com/TuncerKARAARSLAN-VB/training-kit-go-ile-mikro-servis-mimarisi)
