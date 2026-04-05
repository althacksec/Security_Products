# Splunk SOAR (eski adı: Phantom)

**Kategori:** SOAR  
**Geliştirici:** Splunk (Cisco)  
**Fiyatlandırma:** Kullanıcı/olay hacmi bazlı; Splunk ES ile paket seçeneği  
**Deployment:** On-premise, Splunk Cloud, hybrid  
**Lisans Modeli:** Ticari

---

## Nedir?

Splunk SOAR (eski adı Phantom), güvenlik uyarılarını otomatize etmek, güvenlik araçlarını orkestre etmek ve olay müdahale süreçlerini hızlandırmak için kullanılan bir SOAR platformudur. Splunk Enterprise Security ile doğal entegrasyonu en büyük avantajıdır. Splunk SIEM'den gelen uyarıları doğrudan SOAR'a aktararak kesintisiz güvenlik operasyonu sunar.

---

## Temel Özellikler

| Özellik | Açıklama |
|---|---|
| **Visual Playbook Editor** | Drag-and-drop görsel iş akışı oluşturma; minimal kod bilgisi yeterli. |
| **100+ Hazır Playbook** | Phishing triage, Recorded Future enrichment, CrowdStrike triage dahil. |
| **Automation Broker** | Hybrid ortamlarda on-premise eylemler için güvenli yürütme. |
| **Event Playbooks** | Olay tiplerine göre otomatik tetiklenen playbook'lar. |
| **Splunk ES Entegrasyonu** | Splunk SIEM ile sıkı native bağlantı; uyarıdan eyleme sıfır sürtünme. |
| **400+ App/Connector** | Splunk SplunkBase üzerinden uygulama ekosistemi. |
| **Custom Playbook Blocks** | Python ile özel blok yazımı. |

---

## Artılar

- **Splunk ES ile mükemmel entegrasyon:** Splunk zaten altyapıda varsa en mantıklı SOAR seçimi.
- **Hazır playbook'lar:** 100+ prebuilt; yaygın use case'ler için hızlı başlangıç.
- **Kullanıcı dostu:** Görsel editör, az kod deneyimi ile playbook oluşturmaya izin veriyor.
- **Hybrid destek:** Automation Broker ile on-premise eylemler cloud'dan tetiklenebilir.
- **Geniş uygulama ekosistemi:** SplunkBase'in dev topluluğundan besleniyor.
- **MTTR iyileştirmesi:** Kullanıcılar olay çözüm süresinin önemli ölçüde düştüğünü raporluyor.

---

## Eksiler

- **Splunk bağımlılığı:** Splunk SIEM'den uzaklaşırsanız SOAR büyük değer kaybeder.
- **Yüksek kurulum maliyeti:** Cortex XSOAR'a göre daha yüksek initial setup maliyeti.
- **Playbook drift:** Zamanla bakım gerektiren karmaşık playbook'lar birikir.
- **Splunk dışı ortam:** Non-Splunk veri kaynaklarıyla entegrasyon daha az native.
- **Büyük ekip gereksinimi:** Etkili kullanım için playbook bakımı tam zamanlı kaynak istiyor.

---

## Kullanım Alanları

- Splunk ES kullanan kuruluşların SOAR otomasyonu
- Phishing triage otomasyonu
- IOC enrichment ve tehdit istihbaratı iş akışları
- Olay yanıtının orkestrasyonu

---

## Kaynaklar

- [Splunk SOAR](https://www.splunk.com/en_us/products/soar.html)
- [Splunk SOAR Playbooks](https://www.splunk.com/en_us/blog/security/soar-playbooks.html)

---

*Rapor tarihi: 2025 Q2 | AltHack Security — Security Products Serisi*
