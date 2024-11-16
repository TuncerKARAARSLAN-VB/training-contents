# Java Spring ile Microservis Mimarisi ve Yayınlama (Kubernetes, Docker, OpenShift)

## Eğitim Süresi:

**Format 1**

- **5 Gün**
- **Ders Süresi:** 50 dakika
- **Eğitim Saati:** 10:00 - 17:00

**Format 2**

- **12 Gün**
- **Ders Süresi:** 50 dakika
- **Eğitim Saati:** 10:00 - 17:00

## Eğitim İçeriği

### **Bölüm 1: Microservis Mimarisi ve Java Spring ile Geliştirme**

1. **Microservis Mimarisi Nedir?**
   - **Microservislerin Tanımı ve Temel Kavramlar:**
     - Microservislerin genel yapısı ve monolitik yapılarla karşılaştırılması
     - Microservislerin avantajları ve zorlukları
   - **Microservislerin Genel Özellikleri:**
     - Bağımsız geliştirme, dağıtım ve ölçeklendirme
     - Dağıtık sistemler ve servisler arası iletişim
   - **Microservis Mimarisi için Temel Prensipler:**
     - Kendi veritabanına sahip olma
     - API-gateway kullanımı
     - Her servisin işlevsel odaklı olması

2. **Java Spring ile Microservis Geliştirme**
   - **Spring Framework Nedir?**
     - Spring Boot, Spring Cloud ve Spring MVC'nin özellikleri
     - Spring ile microservis geliştirme neden yaygın ve tercih edilen bir yöntemdir?
   - **Spring Boot ile Microservis Geliştirme:**
     - Spring Boot ile hızlı uygulama kurulumları
     - RESTful API’ler oluşturma (Controllers, RequestMapping)
     - JSON ve XML veri işleme
     - Spring Data JPA ile veritabanı bağlantıları ve CRUD işlemleri
   - **Spring Cloud ile Microservis Tabanlı Mimari:**
     - **Eureka:** Servis keşfi ve load balancing
     - **Spring Cloud Config:** Merkezi yapılandırma yönetimi
     - **Hystrix:** Servisler arası iletişimde hata yönetimi
     - **Zuul / Spring Cloud Gateway:** API Gateway kullanımı
   - **DevOps ve Spring Boot ile Microservis CI/CD Süreçleri:**
     - Jenkins veya GitLab CI kullanarak Spring Boot projelerinin derlenmesi ve dağıtılması
     - Unit testler ve entegrasyon testleri

3. **Microservisler Arası İletişim**
   - **REST API İletişimi:** 
     - HTTP metodları (GET, POST, PUT, DELETE) ve JSON formatı
     - Spring WebClient ve RestTemplate kullanımı
   - **Mesajlaşma ile İletişim:**
     - **RabbitMQ / Kafka:** Mesaj kuyruğu kullanarak servisler arası iletişim
     - **Spring AMQP ve Spring Kafka** entegrasyonu
   - **gRPC:** Hızlı ve düşük gecikmeli iletişim protokolü
   - **API Gateway ile Yönetim:** Servislerin dış dünyaya açılmasını sağlamak için API Gateway kullanımı

---

### **Bölüm 2: Docker ile Konteynerleştirme**

1. **Docker’a Giriş**
   - **Docker Nedir?**
     - Konteynerleştirme nedir ve microservisler ile ilişkisi
     - Docker’ın avantajları ve uygulama dağıtımındaki rolü
   - **Docker Bileşenleri:**
     - **Docker Image:** Uygulamanın çalıştırılabilir hali
     - **Docker Container:** Çalışan bir image
     - **Dockerfile:** İmajın nasıl oluşturulacağına dair talimatlar
   - **Docker Komutları ve Kullanımı:**
     - `docker build`, `docker run`, `docker ps`, `docker logs` komutları
     - **Docker Compose** ile çoklu servislerin yönetimi

2. **Spring Boot Uygulamasını Docker ile Konteynerleştirme**
   - **Dockerfile Yazma:**
     - Spring Boot için Dockerfile yazma
     - **Multi-stage Dockerfile** kullanarak imaj boyutunun azaltılması
   - **Spring Boot Microservislerini Docker Konteynerinde Çalıştırma:**
     - Java uygulamasını Docker konteynerinde çalıştırma
     - Veritabanı entegrasyonu (örneğin, PostgreSQL, MySQL) ve çevresel değişkenlerin kullanımı
   - **Docker Compose ile Çoklu Servislerin Yönetimi:**
     - Birden fazla microservisin çalıştırılması için `docker-compose.yml` dosyasının hazırlanması
     - Bağımlı servislerin (DB, MQ, vs.) birlikte çalıştırılması

---

### **Bölüm 3: Kubernetes ile Orkestrasyon**

1. **Kubernetes’e Giriş**
   - **Kubernetes Nedir?**
     - Kubernetes’in tanımı, amacı ve özellikleri
     - Kubernetes’in microservis mimarilerindeki rolü
     - Pod, Deployment, Service, ReplicaSet, ConfigMap gibi temel bileşenler
   - **Kubernetes Mimarisine Genel Bakış:**
     - Master ve Worker Node’lar
     - Pod’lar ve Deployment’lar
     - Service ve Ingress ile dış erişim sağlama
   - **Kubernetes CLI Aracı (kubectl) Kullanımı:**
     - `kubectl` komutlarıyla Kubernetes kaynaklarını yönetme

2. **Spring Boot Microservislerini Kubernetes Üzerinde Dağıtma**
   - **Kubernetes Deployment ve Pod Yapılandırması:**
     - Spring Boot uygulamalarının Kubernetes üzerinde çalıştırılması
     - Docker container’ları Kubernetes pod’larında çalıştırma
   - **Kubernetes Service ve Load Balancer Yapılandırması:**
     - Service kullanarak pod’lara erişim sağlama
     - External ve Internal servisler
   - **Kubernetes ile Auto-Scaling:**
     - Horizontal Pod Autoscaler kullanarak mikroservislerin otomatik olarak ölçeklenmesi

3. **Kubernetes ile DevOps Entegrasyonu**
   - **CI/CD Pipeline’ları Oluşturma:**
     - Jenkins, GitLab CI, veya Azure DevOps kullanarak Kubernetes üzerinde otomatik derleme ve dağıtım
     - Kubernetes ve Helm ile uygulama dağıtımı
   - **Helm ile Kubernetes Uygulama Dağıtımı:**
     - Helm Charts kullanarak Spring Boot microservislerinin Kubernetes ortamında dağıtılması

---

### **Bölüm 4: OpenShift ile Yayınlama ve Yönetim**

1. **OpenShift’e Giriş**
   - **OpenShift Nedir?**
     - Kubernetes’in kurumsal versiyonu olan OpenShift’in avantajları
     - OpenShift ekosistemi, GUI ve CLI araçları
   - **OpenShift ve Kubernetes Arasındaki Farklar:**
     - OpenShift ekosisteminin özellikleri ve Kubernetes üzerinde sağladığı avantajlar
     - OpenShift’in güvenlik, kullanıcı yönetimi ve izleme özellikleri
   - **OpenShift CLI (`oc`) ile Uygulama Yönetimi**

2. **Spring Boot Microservislerini OpenShift Üzerinde Dağıtma**
   - **OpenShift’te Proje Oluşturma ve Konfigürasyon:**
     - OpenShift üzerinde bir proje oluşturma ve kaynakları yönetme
   - **OpenShift Deployment ve Pod Yönetimi:**
     - Spring Boot uygulamalarını OpenShift üzerinde dağıtmak
   - **OpenShift Routes ve External Erişim:**
     - OpenShift Routes kullanarak dış erişim sağlama
   - **OpenShift ile Kaynak Yönetimi ve İzinler:**
     - OpenShift RBAC (Role-Based Access Control) kullanarak kaynaklara erişimi yönetme

3. **OpenShift ile CI/CD Yönetimi**
   - **OpenShift Pipelines (Tekton) ile DevOps Süreçleri:**
     - OpenShift Pipelines kullanarak Spring Boot microservislerinin otomatik dağıtım süreçleri
   - **OpenShift ve Jenkins ile Entegrasyon:**
     - Jenkins kullanarak OpenShift üzerinde microservis CI/CD pipeline’ları oluşturma

---

### **Bölüm 5: Microservis Yönetimi, İzleme ve Güvenlik**

1. **Microservis İzleme ve Performans Yönetimi**
   - **Prometheus ve Grafana ile İzleme:**
     - Kubernetes ve OpenShift üzerinde Prometheus ve Grafana ile izleme
   - **ELK Stack ile Log Yönetimi:**
     - Elasticsearch, Fluentd, Kibana kullanarak logları toplama ve analiz etme

2. **Microservis Güvenliği**
   - **OAuth2 ve JWT ile Kimlik Doğrulama ve Yetkilendirme:**
     - Spring Security kullanarak JWT token oluşturma ve doğrulama
   - **Mutual TLS ile Güvenli İletişim:**
     - Microservisler arası güvenli iletişim için mutual TLS yapılandırması
   - **API Gateway ve Rate Limiting:**
     - API Gateway kullanarak

---

[Eğitim ana materyalleri, sadece eğitmenler için](https://github.com/TuncerKARAARSLAN-VB/training-kit-java-spring-ile-mikro-servis-mimarisi)
