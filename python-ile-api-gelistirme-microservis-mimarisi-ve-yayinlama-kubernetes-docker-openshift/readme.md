# Python ile Microservis Mimarisi ve Yayınlama (Kubernetes, Docker, OpenShift)

## Eğitim Süresi:

**Format 1**

- **5 Gün**
- **Ders Süresi:** 50 dakika
- **Eğitim Saati:** 10:00 - 17:00

**Format 2**

- **12 Gün**
- **Ders Süresi:** 50 dakika
- **Eğitim Saati:** 10:00 - 17:00

**Python ile Microservis Mimarisi ve Yayınlama (Kubernetes, Docker, OpenShift) Eğitimi**

**Eğitim Amacı:**
Bu eğitim, Python ile microservis mimarisini tasarlama, geliştirme ve yönetme süreçlerini kapsamlı bir şekilde ele alır. Katılımcılar, Python ile microservislerin nasıl geliştirileceğini, Docker, Kubernetes ve OpenShift gibi modern konteynerleştirme ve orkestrasyon araçlarıyla nasıl dağıtılacağını öğrenerek bu araçları iş süreçlerine entegre etme konusunda derinlemesine bilgi sahibi olacaklardır. Ayrıca, bu eğitimin sonunda, katılımcılar, yüksek ölçeklenebilir ve güvenli mikro hizmet mimarileri inşa etme konusunda yeterli bilgiye sahip olacaklardır.

**Eğitim Süresi:**  
3-4 Gün (Teorik + Pratik)

---

### **Bölüm 1: Microservis Mimarisi ve Python’a Giriş**
1. **Microservis Mimarisi Nedir?**
   - **Microservis Tanımı ve Temel Kavramlar:**  
     Microservisler, büyük, monolitik uygulamaları küçük, bağımsız çalışabilen servisler halinde bölerek geliştirmeyi amaçlayan bir yazılım mimarisidir. Her bir mikro servis tek bir işlevi yerine getirir ve bağımsız olarak çalışabilir.
   - **Monolitik Yapılar ile Microservis Mimarisi Karşılaştırması**
   - **Microservislerin Avantajları ve Zorlukları:**
     - Avantajlar: Esneklik, ölçeklenebilirlik, hızlı dağıtım
     - Zorluklar: Servisler arası iletişim, veri tutarlılığı, hata yönetimi

2. **Python ile Microservis Geliştirme**
   - **Python İçin Microservis Framework'leri:**
     - **Flask ve FastAPI:** Flask, mikro hizmetler için minimal bir web çatısı olarak, FastAPI ise hızlı API geliştirme için idealdir.
     - **Django Rest Framework (DRF):** Django ile RESTful API’ler geliştirmek için kullanılır.
   - **Python ile HTTP ve REST API Geliştirme:**  
     - HTTP protokolü, GET, POST, PUT, DELETE istekleri ve RESTful API ilkeleri.
   - **Microservisler İçin Veritabanı Tasarımı:**  
     - Her mikro servisin kendi veritabanına sahip olması, veri tutarlılığı ve entegrasyonu.
     - Veritabanı yönetimi için Python araçları: SQLAlchemy, Tortoise ORM, Django ORM.

---

### **Bölüm 2: Docker ve Konteynerleştirme**
1. **Docker'a Giriş ve Temel Kavramlar**
   - **Docker Nedir?**  
     Docker, yazılım uygulamalarının, bağımlılıklarıyla birlikte bir konteynırda paketlenmesini sağlar. Bu, taşınabilirlik ve izole çalışma ortamları sağlar.
   - **Docker’ın Temel Bileşenleri:**
     - **Docker Image**: Yazılımın tüm bağımlılıklarıyla birlikte paketlendiği dosya.
     - **Docker Container**: Docker Image’tan çalıştırılabilir bir konteyner.
     - **Dockerfile**: Uygulamanın nasıl paketleneceğini ve çalıştırılacağını belirten dosya.
   - **Docker Komutları ve Kullanım:**
     - `docker build`, `docker run`, `docker ps`, `docker logs`
     - Docker Compose ile çoklu konteyner yönetimi

2. **Python Uygulamasını Docker ile Konteynerleştirme**
   - **Python Uygulaması İçin Dockerfile Yazma**
   - **Konteynerleştirilmiş Python Microservisini Çalıştırma ve Test Etme**
   - **Docker Compose ile Microservislerin Yönetilmesi:**
     - Çoklu Python mikro servislerini bir arada çalıştırma
     - Veritabanı bağlantılarının yapılandırılması
     - Konteyner ağlarının oluşturulması

---

### **Bölüm 3: Kubernetes ile Orkestrasyon**
1. **Kubernetes Nedir?**
   - **Kubernetes Temel Kavramları ve Yapısı:**
     - **Pod**: Kubernetes'teki en küçük dağıtım birimi.
     - **Deployment**: Pod’ların çoğaltılması ve yönetilmesi için kullanılan yapı.
     - **Service**: Mikro servislerin birbirine bağlanmasını ve dış dünyaya açılmasını sağlar.
     - **ConfigMap ve Secret**: Konfigürasyon ve gizli verilerin yönetilmesi.
     - **Ingress Controller**: Dışarıdan gelen isteklerin yönlendirilmesi.
   - **Kubernetes Cluster Yapılandırması:**
     - Kubernetes kontrol düğümü ve işçi düğümleri
     - Kubernetes API Server, Controller Manager, Scheduler, Kubelet

2. **Python Microservislerinin Kubernetes Üzerinde Dağıtılması**
   - **Kubernetes Pod ve Deployment Oluşturma:**
     - Kubernetes YAML dosyaları ile deployment oluşturma
     - Replikasyon ve ölçekleme
   - **Kubernetes ile Servis Yönlendirme:**
     - Python mikro servislerinin birbirine bağlanması
     - Kubernetes Service türleri: ClusterIP, NodePort, LoadBalancer
   - **Kubernetes ile Yük Dengeleme ve Auto-Scaling:**
     - Yük dengeleme ve otomatik ölçekleme (Horizontal Pod Autoscaler)
     - Kaynak yönetimi ve limitler (CPU, bellek)

3. **Kubernetes ile DevOps Entegrasyonu**
   - **CI/CD (Continuous Integration/Continuous Deployment) Pipeline’ları:**  
     - Kubernetes üzerinde CI/CD süreçlerinin yapılandırılması
     - Jenkins, GitLab CI, CircleCI ile Kubernetes entegrasyonu

---

### **Bölüm 4: OpenShift ile Microservislerin Yönetimi**
1. **OpenShift Nedir?**
   - **OpenShift’in Temel Özellikleri ve Kubernetes ile Farkları**
     - OpenShift, Kubernetes üzerine inşa edilen ve kurumsal düzeyde güvenlik, çoklu ortam yönetimi ve uygulama yönetim araçları sağlayan bir platformdur.
   - **OpenShift Cluster Yapılandırması**
     - OpenShift projeleri, namespace'ler, kullanıcı yönetimi
     - OpenShift CLI (oc) kullanımı

2. **Python Microservislerini OpenShift Üzerinde Yayınlama**
   - **OpenShift ile Deployment ve Pod Yönetimi**
   - **OpenShift Route ile Dış Erişim Sağlama**
   - **OpenShift ile Kaynak Yönetimi ve İzinler:**
     - OpenShift Security Context, Network Policies, Role-Based Access Control (RBAC)
     - OpenShift Secrets ve ConfigMaps yönetimi

3. **OpenShift CI/CD Entegrasyonu**
   - **Jenkins ile OpenShift Entegrasyonu**
   - **OpenShift Pipelines (Tekton) ile CI/CD Otomasyonu**
   - **Automated Builds and Deployments**

---

### **Bölüm 5: Mikro Servislerin Yönetimi ve İzlenmesi**
1. **Mikro Servislerin İzlenmesi (Monitoring)**
   - **Prometheus ve Grafana ile İzleme:**  
     - Prometheus kullanarak microservislerin izlenmesi
     - Grafana ile metriklerin görselleştirilmesi
   - **Elasticsearch, Fluentd ve Kibana (EFK Stack) ile Log Yönetimi:**
     - Mikro servislerin loglarının toplanması ve analizi

2. **Mikro Servislerin Hata Yönetimi ve Debugging**
   - **Distributed Tracing ve Jaeger ile İzleme:**  
     - Microservisler arasında isteklerin izlenmesi
     - Jaeger kullanarak hataların ve gecikmelerin tespiti
   - **Health Check ve Readiness Probe ile Servis Sağlığı İzleme**

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
1. **Microservis Proje Yönetimi**
   - **Microservis Geliştirme ve Dağıtımında En İyi Uygulamalar**
   - **CI/CD ile Sürekli Dağıtım ve Sürekli Entegrasyon**
   - **Modülerlik ve Servis Bağımlılıkları Yönetimi**

2. **Sürekli Öğrenme ve İyileştirme**
   - **Mikro Servislerin Sürekli Geliştirilmesi

[Eğitim ana materyalleri, sadece eğitmenler için](https://github.com/TuncerKARAARSLAN-VB/training-kit-python-ile-mikro-servis-mimarisi)
