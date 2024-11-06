# Sıfırdan Zirveye Kubernetes Eğitimi

**Format 1**

- **5 Gün**
- **Ders Süresi:** 50 dakika
- **Eğitim Saati:** 10:00 - 17:00

**Format 2**

- **12 Gün**
- **Ders Süresi:** 50 dakika
- **Eğitim Saati:** 10:00 - 17:00

### Eğitim Hedefi:

Bu eğitim, katılımcılara Kubernetes’in temel prensiplerini, mimarisini ve uygulama senaryolarını öğretmeyi amaçlamaktadır. Eğitim sonunda katılımcılar, kendi Kubernetes küme yapılandırmalarını oluşturabilecek, yönetebilecek ve uygulama dağıtımlarını gerçekleştirebilecek düzeye geleceklerdir.

### Eğitim İçeriği:

#### **1. Gün: Kubernetes’e Giriş ve Kurulum**

- **Kubernetes Nedir?**
  - Tanım ve Tarihçe
  - Kubernetes’in Avantajları: Mikroservislerin yönetiminde Kubernetes'in rolü
- **Kubernetes Mimarisi**
  - Pod, ReplicaSet, Deployment, Service kavramları
  - Kubernetes bileşenleri (Master Node, Worker Node)
- **Kubernetes Kurulumu**
  - Minikube ile Kubernetes kurulumu
  - kubeadm ile Multi-node Cluster Kurulumu
  - Managed Kubernetes Hizmetleri (GKE, EKS, AKS)
- **Kubernetes CLI Kullanımı**
  - Kubectl CLI komutları ve temel işlemler
  - Codespace ortamında Kubernetes ile çalışma

#### **2. Gün: Pod ve Uygulama Yönetimi**

- **Pod Kavramı ve Yönetimi**
  - Pod içindeki konteynerlerin yönetimi
  - Pod Lifecycle ve Restart Policy
  - Pod Disruption Budget
- **Deployment Yönetimi**
  - Deployment oluşturma, güncelleme ve rollback
  - Versiyon kontrol stratejileri
- **Service Türleri ve İletişim**
  - ClusterIP, NodePort, LoadBalancer
  - Service ile Pod’lar arası iletişim
- **Stateful ve DaemonSet Uygulamaları**
  - StatefulSets ile Stateful uygulamalar
  - DaemonSets kullanımı

#### **3. Gün: İleri Seviye Kubernetes Konseptleri**

- **ConfigMap ve Secret Yönetimi**
  - Uygulama yapılandırmaları ve gizli bilgilerin yönetimi
- **Depolama Yönetimi**
  - Kalıcı depolama birimleri (Persistent Volume, Persistent Volume Claim)
  - Farklı depolama çözümleri
- **Ağ ve Ingress Yönetimi**
  - Kubernetes ağ politikaları ve yönetimi
  - Ingress Controller yapılandırması
- **Scheduler ve Node Yönetimi**
  - Kubernetes Scheduler ve Node Affinity
  - Pod yerleştirme stratejileri (affinities, taints/tolerations)
- **Ağ Güvenliği**
  - Network Policies ile uygulamalar arası güvenlik

#### **4. Gün: Kubernetes Güvenliği ve İzleme**

- **RBAC ve Güvenlik Prensipleri**
  - Role-Based Access Control (RBAC) yapılandırması
  - Güvenlik politikalarının belirlenmesi
- **İzleme ve Günlükleme**
  - Prometheus ile izleme
  - Grafana ile görselleştirme
  - ELK Stack ve alternatif günlükleme çözümleri (Loki, Fluentd)
- **Yedekleme ve Geri Yükleme**
  - Velero ile yedekleme ve geri yükleme işlemleri
- **Cluster Upgrade Stratejileri**
  - Kubernetes versiyon yükseltme yolları

#### **5. Gün: Uygulama Dağıtımı ve En İyi Uygulamalar**

- **Uygulama Dağıtımı**
  - CI/CD süreçleri ve Kubernetes entegrasyonu
  - GitOps ile Kubernetes yönetimi (ArgoCD, FluxCD)
- **Helm ile Uygulama Yönetimi**
  - Helm kullanarak paket yönetimi
- **Kubernetes En İyi Uygulamaları**
  - Kaynak yönetimi ve otomasyon
  - Horizontal ve Vertical Pod Autoscaling
  - Cluster Autoscaler ile node yönetimi
- **Uygulama Senaryoları ve Çoklu Cluster Yönetimi**
  - Gerçek dünyadan örneklerle uygulama dağıtımı
  - Çoklu cluster yönetimi (KubeFed)
  - Sorun çözme yolları ve pratik çözümler

### Eğitim Yöntemi:

- **Teorik Bilgi:** Güncel bilgiler ve konseptlerin anlatımı.
- **Uygulamalı Örnekler:** Gerçek senaryolarla pratik uygulamalar.
- **Etkileşimli Tartışmalar:** Katılımcıların fikirlerini paylaşabileceği oturumlar.

### Hedef Kitle:

- Yazılım Geliştiriciler
- Sistem Yöneticileri
- DevOps Mühendisleri
- IT Profesyonelleri

[Eğitim ana materyalleri, sadece eğitmenler için](https://github.com/TuncerKARAARSLAN-VB/training-kit-ileri-seviye-kubernetes-egitimi)
