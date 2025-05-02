# 🔐 SIEM Ortamı Kurulumu ve Brute-Force Saldırı Tespiti

Bu projede açık kaynaklı güvenlik izleme aracı olan **Wazuh** kullanılarak bir **SIEM (Security Information and Event Management)** ortamı kurulmuş ve **Brute-Force saldırılarının tespiti** uygulanmıştır.
Bu raporda teknik hatalar veya eksiklikler olabileceğini kabul ediyorum, çünkü öğrenme sürecindeyim.

## 🎯 Proje Hedefi

- SIEM ortamı kurma sürecini öğrenmek
- Wazuh agent ve server entegrasyonunu yapmak
- Brute-force saldırılarını simüle ederek tespit edilebilirliğini test etmek

## ⚙️ Kullanılan Teknolojiler

- Ubuntu 20.04 LTS (Wazuh Server)
- Windows Server 2019 (Hedef sistem)
- Wazuh 4.7
- Hydra (Brute-Force aracı)
- VMware Workstation
- RDP bağlantısı

## 📌 Proje Adımları

1. Ubuntu üzerine Wazuh kurulumu
2. Windows Server kurulumu
3. Wazuh Agent konfigürasyonu
4. Brute-force saldırısının Hydra ile simülasyonu
5. Event ID 4625 üzerinden tespit ve uyarı üretimi

## 🧪 Brute-Force Senaryosu

- Kali Linux kullanılarak Hydra üzerinden başarısız RDP giriş denemeleri yapılmıştır.
- Bu girişimler Event Viewer’da 4625 ID'si ile loglanmış, Wazuh tarafından algılanarak dashboard'da uyarı olarak gösterilmiştir.

## 📎 Rapor
Bu süreçte yalnızca teknik bilgiler değil, aynı zamanda dokümantasyon hazırlama ve sorun giderme gibi önemli beceriler de kazandım.
Her ne kadar projeyi başarıyla tamamlasam da, öğrenme yolculuğumun henüz başındayım. Karşılaştığım hatalar ve zorluklar, siber güvenlik alanında sürekli gelişmenin ne kadar önemli olduğunu bana gösterdi. Bu deneyimlerden öğrenmeye devam ediyorum ve kendimi gelecekte siber güvenlik alanında bir profesyonel olarak görmek için kararlılıkla çalışıyorum.
👉 [Raporu buradan görüntüleyebilirsiniz.](SIEM_RAPORU_.pdf)



## 📚 Kaynaklar

- [Wazuh Documentation](https://documentation.wazuh.com)
- [Wazuh Dashboard Kullanım Kılavuzu](https://documentation.wazuh.com/current/user-manual/wazuh-dashboard/index.html)
- [Wazuh Manager Kullanım Kılavuzu](https://documentation.wazuh.com/current/user-manual/manager/index.html)
- [Deploying Wazuh in a Corporate Environment - Sean Nanty (Medium)](https://medium.com/@nantysean/deploying-wazuh-in-a-corporate-environment-5138ac209f1c)
- [Install and Configure Wazuh Agent on Windows - Songer.pro](https://www.songer.pro/install-and-configure-wazuh-agent-windows/)

---

> Proje sahibi: **Hasan Bayraktar**  
> [LinkedIn Profilim](https://linkedin.com/in/hasan-bayraktar)  
> 📧 İletişim: bayraktarh317@gmail.com
