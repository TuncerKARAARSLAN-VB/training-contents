# Red Hat Linux Eğitim Paketi

## Eğitim Süresi:

- **5 Gün**
- **Ders Süresi:** 50 dakika
- **Eğitim Saati:** 10:00 - 17:00

**Alternatif Format 2**

- **12 Gün**
- **Ders Süresi:** 50 dakika
- **Eğitim Saati:** 10:00 - 17:00

#### Eğitim Hedefleri

- Red Hat Linux’un temel bileşenlerini anlama
- Sistem kurulumu ve konfigürasyonu yapabilme
- Ağ yönetimi, güvenlik ve kullanıcı yönetimi bilgisi kazanma
- Temel komut satırı becerilerini geliştirme
- Sistem güncellemeleri ve paket yönetimini anlama
- Yedekleme ve kurtarma işlemlerini yapabilme
- Git versiyon kontrol sisteminin kullanımını öğrenme
- **Docker ve Kubernetes kurulumu ve yönetimini öğrenme**
- Uygulama kurulumları ve güncelleme işlemlerini yapabilme

---

### Eğitim İçeriği

#### 1. Giriş ve Temel Kavramlar

- Linux ve RHEL nedir?
- Linux’un tarihçesi ve dağıtım türleri
- RHEL’in özellikleri ve avantajları
- Komut satırı arayüzüne (CLI) giriş

#### 2. Sistem Kurulumu

- Red Hat işletim sisteminin kurulumu
  - Gereksinimler
  - Kurulum medyası oluşturma
  - Kurulum adımları
- Temel yapılandırma
  - Ağ ayarları
  - Zaman ayarları
  - Kullanıcı oluşturma

#### 3. Temel Linux Komutları

- Dosya ve dizin yönetimi
- Dosya izinleri ve sahiplik
- Temel sistem bilgisi komutları (`uname`, `top`, `df`, `free`, vb.)
- Gelişmiş dosya yönetimi komutları (`find`, `grep`, `tar`, `rsync`)

#### 4. Paket Yönetimi

- DNF ve YUM paket yöneticileri
- Paket kurma, kaldırma ve güncelleme
- Bağımlılık yönetimi
- Yazılım kaynaklarını yönetme

#### 5. Uygulama Kurulumları ve Güncelleme

- Uygulama kurulum yöntemleri
  - Yazılım kaynaklarından uygulama kurulumu
  - RPM paketleri ile kurulum
- Güncellemelerin yönetimi

    ```bash
    dnf update
    ```

  - Belirli bir paketin güncellenmesi

    ```bash
    dnf upgrade paket_adi
    ```

- Uygulama kaldırma işlemleri
  - Uygulama kaldırma

    ```bash
    dnf remove paket_adi
    ```

#### 6. Ağ Yönetimi

- Temel ağ kavramları (IP, DNS, DHCP)
- Ağ arayüzlerinin yapılandırılması
- Firewall ve güvenlik ayarları
- Ağ izleme ve sorun giderme araçları (`ping`, `traceroute`, `netstat`)

#### 7. Kullanıcı ve Grub Yönetimi

- Kullanıcı ekleme, silme ve düzenleme
- Grupların yönetimi
- Kullanıcı ve grup izinleri
- Sudo ve root erişimi

#### 8. Sistem Güvenliği

- SELinux hakkında bilgi
- Güvenlik duvarı yapılandırması
- SSH ile güvenli uzaktan erişim
- Güncellemelerin ve yamaların yönetimi

#### 9. Yedekleme ve Kurtarma

- Yedekleme stratejileri
- `tar` ve `rsync` kullanarak yedekleme
- Sistem kurtarma yöntemleri
- Boot ortamı ve kurtarma diskleri

#### 10. Sistem İzleme ve Performans Yönetimi

- Sistem izleme araçları (top, htop, vmstat)
- Disk kullanımını izleme (df, du)
- Sistem performansını artırma stratejileri
- Log dosyalarının yönetimi

#### 11. Uygulama Yönetimi

- Web sunucusu (Apache/Nginx) kurulumu ve yapılandırması
- Veritabanı sunucusu (MySQL/PostgreSQL) kurulumu
- Basit uygulama dağıtım senaryoları

#### 12. Git Kurulumu ve Kullanımı

- Git’in temel kavramları (repository, commit, branch, merge)
- Git kurulumu

    ```bash
    dnf install git
    ```

- Yeni bir repository başlatma

    ```bash
    git init
    ```

- Dosya ekleme ve commit yapma

    ```bash
    git add dosya_adi
    git commit -m "İlk commit"
    ```

- Uzak repository ile çalışma
  - Uzak repository ekleme

    ```bash
    git remote add origin uzak_repository_url
    ```

  - Değişiklikleri itme ve çekme

    ```bash
    git push origin master
    git pull origin master
    ```

#### 13. Docker Kurulumu ve Temel Kullanımı

- Docker nedir ve neden kullanılır?
- Docker mimarisi
- Docker kurulumu ve yapılandırılması
  - Docker Engine kurulumu
  - Docker komutları (run, pull, push, images, ps)
- Dockerfile ile görüntü oluşturma
- Docker Compose kullanarak çoklu konteyner yapılandırması
- Konteynerlerin izlenmesi ve yönetimi
- Docker üzerinde basit uygulama dağıtımı

#### 14. Kubernetes Kurulumu ve Yönetimi

- Kubernetes’in tanımı ve mimarisi
- Kubernetes kurulumu (Docker, kubelet, kubeadm, kubectl)
- Kubernetes kümesi oluşturma ve yönetme
  - `kubectl` ile yönetim (Namespace, Pod, servis, deployment)
    - Örnek: Pod oluşturma ve yönetimi
      ```bash
      kubectl create deployment my-app --image=my-image
      ```
    - Servis oluşturma ve yönetimi
      ```bash
      kubectl expose deployment my-app --type=LoadBalancer --port=80
      ```
- Kubernetes üzerinde uygulama dağıtımı
- Temel sorun giderme ve izleme komutları (`kubectl logs`, `kubectl get pods`)

---

### Eğitim Yöntemleri

- **Teorik Dersler**: Konuların anlatıldığı, sunum ve etkileşimli tartışmalar.
- **Pratik Uygulamalar**: Katılımcıların öğrendiklerini uygulamalı olarak deneyimleyebileceği laboratuvar çalışmaları.
- **Proje Çalışmaları**: Gerçek dünya senaryolarında proje çalışmaları.

### Gereksinimler

- Temel bilgisayar bilgisi
- Önceki Linux deneyimi, tercih sebebi fakat zorunlu değildir
- Kendi dizüstü bilgisayar veya sanal makine (Vagrant, VirtualBox) ile RHEL kurulumu yapılmış olması önerilir.

Bu eğitim paketi, katılımcılara Red Hat Linux, Docker ve Kubernetes yönetim becerilerini kazandırmayı amaçlar. Eğitim sonunda, RHEL sistemlerinin etkin bir şekilde yönetilmesi, Docker ve Kubernetes ortamlarının kurulması ve yönetimi konularında bilgi sahibi olunması hedeflenir.