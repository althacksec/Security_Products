# Elastic Security

**Kategori:** SIEM / EDR / XDR  
**Geliştirici:** Elastic N.V.  
**Fiyatlandırma:** Elastic Cloud: $95/ay'dan (8GB RAM) | Enterprise talep üzerine | Self-managed: ücretsiz basic  
**Deployment:** Elastic Cloud (SaaS), self-managed, on-premise, hybrid  
**Lisans Modeli:** Açık kaynak (temel), ticari (gelişmiş özellikler)

---

## Nedir?

Elastic Security, Elastic Stack (Elasticsearch + Kibana + Beats/Agent) altyapısı üzerine inşa edilmiş birleşik bir güvenlik platformudur. SIEM, EDR ve tehdit avcılığı yeteneklerini tek bir platformda sunar. EQL (Event Query Language) tabanlı tespit kuralları, MITRE ATT&CK ile tam örtüşme ve açık kaynak prebuilt rule seti ile ayrışır. Özellikle detection engineering ekiplerine hitap eder.

---

## Temel Özellikler

| Özellik | Açıklama |
|---|---|
| **EQL (Event Query Language)** | Elastic'e özgü olay sorgu dili; zaman bazlı sekans tespiti için güçlü. |
| **Elastic Agent** | Tek agent ile log, metrik ve güvenlik verisi toplama. |
| **Prebuilt Detection Rules** | 1.000+ MITRE ATT&CK hizalı hazır tespit kuralı; GitHub'da açık kaynak. |
| **Timeline Investigations** | Olay soruşturması için kronik zaman çizelgesi görünümü. |
| **Osquery Entegrasyonu** | Canlı endpoint sorgulama; anlık system state analizi. |
| **Machine Learning Jobs** | Anomali tespiti için hazır ML modelleri. |
| **Threat Intelligence** | STIX/TAXII entegrasyonu; harici TI akışları. |
| **SOAR Entegrasyonu** | Tines, Cortex XSOAR gibi SOAR araçlarıyla entegrasyon. |
| **Kibana Dashboards** | Kapsamlı görselleştirme ve özel dashboard desteği. |

---

## Artılar

- **EQL gücü:** Sekans bazlı tespit kuralları yazmak için en güçlü açık sorgu dili.
- **Açık kaynak detection kuralları:** Prebuilt rule setleri GitHub'da açık — topluluğa katkı.
- **MITRE ATT&CK örtüşmesi:** Her kural ATT&CK ID ile eşlenir; coverage açıkça görülür.
- **Esneklik:** Self-managed veya Elastic Cloud; tam kontrol veya yönetilen seçenek.
- **Maliyet verimliliği:** Temel özellikler için self-managed ücretsiz; Splunk'a kıyasla daha uygun.
- **Osquery entegrasyonu:** Canlı endpoint sorgulama rakiplerinde nadir.
- **Performans:** Büyük log hacimlerinde Elasticsearch'ün hızlı arama yeteneği.

---

## Eksiler

- **Uzmanlık gereksinimi:** Elasticsearch mimarisini yönetmek ve EQL öğrenmek zaman alır.
- **Ölçekleme karmaşıklığı:** Self-managed büyük cluster yönetimi çaba gerektirir.
- **ML özellikler ücretli:** Gelişmiş ML anomali tespiti, Platinum/Enterprise lisans gerektirir.
- **Native SOAR yok:** SOAR için harici araçlara bağımlı; Splunk SOAR veya Cortex XSOAR gerekir.
- **Büyük kurumsal destek:** Kritik ortamlarda enterprise destek beklentisi karşılanmayabilir.
- **UI öğrenme eğrisi:** Kibana güçlü ama yeni kullanıcılar için karmaşık.

---

## Kullanım Alanları

- Detection engineering ekipleri (özellikle EQL kural yazımı)
- MITRE ATT&CK örtüşme analizi ve raporlama
- Büyük hacimli log analizi gerektiren SOC'lar
- DevSecOps ekosistemiyle entegre güvenlik izleme
- Wazuh ile birlikte kullanım (Wazuh indexer olarak Elasticsearch)

---

## Kaynaklar

- [Elastic Security](https://www.elastic.co/security)
- [Elastic Detection Rules GitHub](https://github.com/elastic/detection-rules)
- [EQL Dokümantasyonu](https://www.elastic.co/guide/en/elasticsearch/reference/current/eql.html)

---

*Rapor tarihi: 2025 Q2 | AltHack Security — Security Products Serisi*
