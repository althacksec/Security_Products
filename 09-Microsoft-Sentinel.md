# Microsoft Sentinel

**Kategori:** SIEM / SOAR  
**Geliştirici:** Microsoft  
**Fiyatlandırma:** Veri ingest bazlı ($2.46-$2.76/GB) veya Commitment Tier (indirimli)  
**Deployment:** Cloud-native (Azure)  
**Lisans Modeli:** Azure tüketim bazlı

---

## Nedir?

Microsoft Sentinel, Azure altyapısı üzerinde çalışan cloud-native SIEM ve SOAR platformudur. AI destekli tehdit analitikleri, entegre playbook otomasyonu (Logic Apps) ve Microsoft güvenlik ekosistemiyle native bütünleşme sunar. Microsoft 365 E5 müşterileri belirli servisler için ücretsiz veri ingest hakkı elde eder. Bulut ölçeğinde elastik mimari, geleneksel on-premise SIEM'lerin altyapı yönetim yükünü ortadan kaldırır.

---

## Temel Özellikler

| Özellik | Açıklama |
|---|---|
| **Data Connectors (300+)** | Microsoft ve üçüncü taraf kaynaklardan otomatik log toplama. |
| **KQL (Kusto Query Language)** | Azure Native sorgu dili; güçlü ama Splunk SPL'den farklı öğrenme eğrisi. |
| **UEBA** | Kullanıcı ve varlık davranışı analitikleri; insider threat tespiti. |
| **Analytic Rules** | Özel ve hazır korelasyon kuralları; NRT (neredeyse gerçek zamanlı) kurallar. |
| **Logic Apps Playbooks** | SOAR yetenekleri; Azure Logic Apps ile otomatik müdahale iş akışları. |
| **Threat Intelligence** | Microsoft TI entegrasyonu; TAXII/STIX desteği. |
| **Workbooks** | Özelleştirilebilir görsel raporlar ve dashboard'lar. |
| **Copilot for Security** | KQL sorgu üretimi ve olay soruşturması için AI yardımcısı. |
| **Fusion ML** | Multi-stage saldırılar için ML tabanlı korelasyon motoru. |

---

## Artılar

- **Sıfır altyapı:** Azure yönetir; kapassite planlaması veya donanım yönetimi yok.
- **Microsoft ekosistemi ile mükemmel entegrasyon:** Azure AD, M365, Teams, Defender — native bağlantı.
- **E5 ücretsiz veri ingest:** M365 E5 lisansında Office 365 ve Azure AD logları ücretsiz.
- **Kurulum kolaylığı:** Out-of-the-box data connector'lar deployment süresini kısaltır.
- **Elastik ölçeklenme:** Ani log hacmi artışlarında otomatik ölçekleme.
- **NRT kuralları:** Neredeyse gerçek zamanlı tehdit tespiti.
- **Copilot desteği:** AI destekli sorgu yazımı ve olay analizi.
- **Gartner 4.6/5 rating:** 224 doğrulanmış kullanıcı değerlendirmesi.

---

## Eksiler

- **Azure bağımlılığı:** Backend Azure Cloud'dur; değiştirilemez. Azure dışına çıkış = vendor değişimi.
- **Microsoft dışı entegrasyon sınırlılığı:** Splunk'ın 1.500+ entegrasyonuna karşılık Sentinel daha dar.
- **Logic Apps kısıtlaması:** Playbook otomasyonu ağırlıklı Azure ortamları için; non-Microsoft araçlarla karmaşık.
- **Maliyet şeffaflığı sorunu:** Arşivleme, geri yükleme ve arama ücretleri iç içe; beklenmedik fatura riski.
- **KQL öğrenme eğrisi:** Sentinel'e özgü sorgu dili; SPL veya EQL'den farklı öğrenme gerektirir.
- **Üçüncü taraf destek yavaşlığı:** Non-Microsoft cihaz entegrasyonları ek yapılandırma istiyor.

---

## Kullanım Alanları

- Azure/Microsoft 365 ağırlıklı enterprise ortamlar
- Altyapı yönetiminden kurtulmak isteyen ekipler
- Cloud-native kuruluşlar
- Insider threat izleme ve UEBA
- Hybrid log yönetimi

---

## Fiyatlandırma Notu

Tüketim bazlı: ~$2.46-2.76/GB (Pay-As-You-Go). Commitment Tier ile belirli günlük hacimler için indirim. M365 E5'te belirli kaynaklar ücretsiz. 90 gün ücretsiz veri saklama; sonrası ücretli.

---

## Kaynaklar

- [Microsoft Sentinel](https://azure.microsoft.com/en-us/products/microsoft-sentinel/)
- [Sentinel Fiyatlandırma](https://azure.microsoft.com/en-us/pricing/details/microsoft-sentinel/)
- [MITRE ATT&CK Coverage](https://docs.microsoft.com/en-us/azure/sentinel/mitre-coverage)

---

*Rapor tarihi: 2025 Q2 | AltHack Security — Security Products Serisi*
