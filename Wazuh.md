# Wazuh

**Kategori:** SIEM / XDR / Açık Kaynak  
**Geliştirici:** Wazuh, Inc.  
**Fiyatlandırma:** On-premise: Ücretsiz | Cloud SaaS: $500/ay'dan (sınırsız endpoint)  
**Deployment:** On-premise, private cloud, SaaS (Wazuh Cloud)  
**Lisans Modeli:** GPL-2.0 (açık kaynak) | Ticari destek paketleri mevcut

---

## Nedir?

Wazuh, 2015 yılında OSSEC fork'u olarak doğan, günümüzde tam kapsamlı açık kaynak XDR ve SIEM platformuna dönüşmüş bir güvenlik çözümüdür. Endpoint agent'ları, merkezi yönetim sunucusu, OpenSearch tabanlı indexer ve web dashboard'dan oluşan modüler mimarisi sayesinde on-premise, cloud veya hybrid ortamlarda konuşlandırılabilir. NASA, Salesforce ve eBay dahil 100.000'den fazla kurumsal kullanıcı tarafından tercih edilmektedir.

---

## Mimari Bileşenler

| Bileşen | Görev |
|---|---|
| **Wazuh Agent** | Endpoint'lere kurulur; log, FIM, zafiyet ve sistem verisi toplar. |
| **Wazuh Server** | Decoder + kural tabanlı analiz motoru; aktif yanıt koordinasyonu. |
| **Wazuh Indexer** | OpenSearch tabanlı; uyarı ve olayları depolar ve indeksler. |
| **Wazuh Dashboard** | Web arayüzü; görselleştirme, agent yönetimi, tehdit avı. |

---

## Temel Özellikler

| Özellik | Açıklama |
|---|---|
| **Log veri analizi** | Syslog, Windows Event Log, uygulama logları kural tabanlı analiz. |
| **File Integrity Monitoring (FIM)** | Dosya değişikliklerini, izin ve sahiplik değişimlerini izler. |
| **Zafiyet yönetimi** | CVE veritabanı ile karşılaştırarak software inventory'yi tarar. |
| **Compliance** | PCI DSS, HIPAA, NIST, GDPR için hazır kural setleri ve raporlar. |
| **MITRE ATT&CK entegrasyonu** | Her uyarı ATT&CK taktik/teknik ID ile eşlenir. |
| **Aktif yanıt** | Tehdit tespitinde otomatik blocking, process sonlandırma. |
| **Container güvenliği** | Docker, Kubernetes ortamlarında container izleme. |
| **Agentless izleme** | Firewall ve router gibi cihazlar için Syslog/SSH/API desteği. |
| **Açık kaynak** | Tam kaynak kodu şeffaflığı; özelleştirme ve genişletme özgürlüğü. |

---

## Artılar

- **Lisans maliyeti sıfır:** On-premise kurulum tamamen ücretsiz.
- **Kapsamlı uyum desteği:** PCI DSS, HIPAA, NIST için hazır raporlar ve kurallar.
- **Geniş platform desteği:** Windows, Linux, macOS, Solaris, HP-UX, AIX.
- **Topluluk:** Dünyanın en büyük açık kaynak güvenlik topluluklarından biri; hızlı geliştirme döngüsü.
- **Tam şeffaflık:** Kaynak kodu denetlenebilir; vendor lock-in yok.
- **FIM üstünlüğü:** Dosya bütünlüğü izleme yeteneği, ticari alternatiflere göre daha granüler.
- **MITRE ATT&CK:** Her olay ATT&CK çerçevesiyle haritalanır.
- **Aktif geliştirme:** 2025'te 4.11.x ve 4.12.0 sürümleri; AI agent entegrasyonu eklendi.

---

## Eksiler

- **İnsan kaynağı maliyeti:** Sıfır lisans, yüksek operasyonel maliyet anlamına gelebilir. Uzman ekip gerektirir; median yıllık destek harcaması ~$16.234.
- **Ölçekleme karmaşıklığı:** Çok yüksek event hızında dikkatli mimari planlama şart.
- **ML tabanlı tespit zayıflığı:** CrowdStrike gibi ML-driven EDR'lara kıyasla real-time tespit puanı daha düşük.
- **SOAR entegrasyon gecikmesi:** Splunk/Elastic native plugin'leri kaldırıldı (v4.6+); forwarder tabanlı polling gecikmesi.
- **UI sınırlılıkları:** Dashboard özelleştirme ticari alternatiflere kıyasla sınırlı.
- **Üçüncü taraf destek:** Topluluk desteği ücretsiz ama SLA garantisi yok; kurumsal destek ek ücretli.

---

## Kullanım Alanları

- Uyum gereksinimi yüksek, bütçe kısıtlı kuruluşlar
- Tam kontrol ve özelleştirme isteyen güvenlik ekipleri
- SOC laboratuvar ortamları ve eğitim altyapıları
- Vendor lock-in'den kaçınmak isteyen organizasyonlar
- Hybrid cloud + on-premise ortamlar

---

## Fiyatlandırma Özeti

| Model | Fiyat |
|---|---|
| On-premise (self-hosted) | Ücretsiz |
| Wazuh Cloud (managed) | $500/ay'dan (sınırsız endpoint) |
| Ticari destek kontratı | Talep üzerine |
| Eğitim | Ücretli kurslar mevcut |

---

## Kaynaklar

- [Resmi Site](https://wazuh.com)
- [GitHub](https://github.com/wazuh/wazuh)
- [Dokümantasyon](https://documentation.wazuh.com)

---

*Rapor tarihi: 2025 Q2 | AltHack Security — Security Products Serisi*
