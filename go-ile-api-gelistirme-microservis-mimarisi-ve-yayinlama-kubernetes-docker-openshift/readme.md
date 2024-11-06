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

### **Gün 1: Go Programlama Diline Giriş ve API Geliştirme Temelleri**

- **Go’ya Giriş:** Go dilinin tarihçesi, temel özellikleri ve diğer programlama dillerine göre avantajları. Hangi alanlarda kullanıldığı ve neden tercih edildiği üzerine genel bilgi.
- **Go Kurulumu ve Geliştirme Ortamı:** Geliştirme ortamının kurulması, Go araçları ve paket yöneticisi `go mod` kullanımı. Temel dosya yapısı ve Go kodunun yapısı.
- **Go ile API Geliştirme Temelleri:** Go ile basit bir RESTful API geliştirmeye giriş. `net/http` paketi ile HTTP sunucusu oluşturma, API endpoint'lerinin oluşturulması ve JSON yanıtlarının işlenmesi.
- **Veritabanı Bağlantısı:** Go'da veritabanı işlemleri, `database/sql` ve popüler ORM araçları (GORM). API üzerinden CRUD (Create, Read, Update, Delete) işlemlerinin yapılması.
- **API Testi ve Hata Yönetimi:** API'lerin test edilmesi için birim testleri yazma. Hata yönetimi ve loglama stratejileri. Go'da error handling’in önemi ve en iyi uygulamalar.

### **Gün 2: Microservis Mimarisine Giriş ve Go ile Microservis Geliştirme**

- **Microservis Mimarisi Nedir?**: Monolitik uygulamalardan microservis mimarisine geçiş. Microservislerin sağladığı avantajlar: bağımsız ölçeklenebilirlik, esneklik, bağımsız deploy edilebilme.
- **Microservislerde İletişim ve Bağlantı:** Microservisler arası iletişimde kullanılan yöntemler (REST, gRPC, mesaj kuyrukları). Go ile gRPC servisleri yazma ve uygulama.
- **API Gateway ve Service Discovery:** Microservisler için API Gateway rolü. Load balancing ve service discovery. Popüler servis keşif araçlarının (etcd, Consul) kullanımı ve Go ile entegrasyonu.
- **Microservislerde Veritabanı Yönetimi:** Her bir microservisin kendi veritabanı ile çalışma ilkesi. Veritabanı şemalarının dağıtık ortamda yönetilmesi ve veri tutarlılığının sağlanması.
- **Go ile Microservislerin Test Edilmesi:** Microservislerin birim ve entegrasyon testlerinin yapılması. Test stratejileri ve pratik uygulamalar.

### **Gün 3: Docker ile Uygulamaların Konteynerize Edilmesi**

- **Docker Nedir ve Neden Kullanılır?**: Docker’ın temel kavramları (image, container, registry). Docker'ın modern yazılım geliştirmede neden kritik olduğu ve microservis mimarisinde nasıl bir rol oynadığı.
- **Go Uygulamalarının Konteynerize Edilmesi:** Go uygulamaları için Dockerfile oluşturma. Çok aşamalı (multi-stage) Docker build süreçleri ile küçük ve optimize edilmiş imajlar oluşturma.
- **Docker Compose ile Microservislerin Yönetimi:** Docker Compose ile çoklu container yapılarının oluşturulması ve Go microservislerinin bağımlılıklarıyla birlikte orkestrasyonu.
- **Docker Registry ve İmaj Yönetimi:** Docker Hub ve özel registry kullanımı. Imajların push, pull ve versiyon yönetimi.
- **Konteyner Güvenliği ve En İyi Uygulamalar:** Konteyner güvenliği için alınacak önlemler, Docker imajlarında güvenlik taraması ve en iyi uygulamalar. Secrets yönetimi ve ağ politikalarının uygulanması.

### **Gün 4: Kubernetes ile Orkestrasyon ve Yayınlama**

- **Kubernetes’e Giriş:** Kubernetes’in temelleri, mimarisi ve bileşenleri (pods, deployments, services, configmaps, secrets). Kubernetes'in avantajları ve microservis mimarisi ile uyumu.
- **Kubernetes Cluster’ı Kurma ve Yapılandırma:** Kubernetes ortamının kurulumu. Minikube veya yerel bir ortamda Kubernetes cluster’ının ayağa kaldırılması. Namespace, pod ve service kavramları.
- **Go Microservislerinin Kubernetes’de Deploy Edilmesi:** Go microservislerini Kubernetes üzerinde çalıştırma. Deployment ve service tanımları, replica set ve autoscaling kavramları.
- **ConfigMap ve Secrets Yönetimi:** Kubernetes ile yapılandırma ve gizli verilerin (şifreler, API anahtarları) yönetimi.
- **Loglama, Monitoring ve Sorun Giderme:** Kubernetes üzerinde çalışan microservislerin loglanması. Popüler loglama ve monitoring araçları (Prometheus, Grafana) ile entegrasyon. Kubernetes’de sorun giderme ve hata yönetimi.

### **Gün 5: OpenShift ile Dağıtım ve CI/CD Süreçlerinin Yönetimi**

- **OpenShift Nedir?**: OpenShift’in Kubernetes üzerine kurulu yapısı, farkları ve sağladığı ek özellikler. OpenShift’in container orkestrasyonundaki rolü ve avantajları.
- **OpenShift ile Go Microservislerinin Yayınlanması:** OpenShift ortamına Go microservislerinin entegre edilmesi. OpenShift ile continuous integration (CI) ve continuous delivery (CD) süreçlerinin yönetimi.
- **Source-to-Image (S2I) ile Uygulama Dağıtımı:** OpenShift’te Source-to-Image (S2I) yapısının kullanımı. Git repository’sinden direkt olarak imaj oluşturma ve otomatik dağıtım.
- **CI/CD Pipeline'larının Kurulumu:** OpenShift Pipelines kullanarak microservislerin otomatik test, build ve deploy süreçlerinin yönetimi. Jenkins, Tekton gibi araçlarla entegrasyon.
- **Yüksek Ölçeklenebilirlik ve Güvenlik:** OpenShift'te uygulamaların güvenli bir şekilde ölçeklenmesi. RBAC (Role Based Access Control), güvenlik politikaları ve network güvenliği.
- **Sonuç ve Özet:** Microservis mimarisinde Go’nun rolü, Docker, Kubernetes ve OpenShift entegrasyonu ile modern uygulama geliştirme süreçlerinin tamamlanması.

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
