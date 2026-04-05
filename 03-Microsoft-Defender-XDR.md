# Microsoft Defender XDR

**Kategori:** XDR / SIEM / EDR  
**Geliştirici:** Microsoft  
**Fiyatlandırma:** Microsoft 365 E5 paketi dahil ($57/kullanıcı/ay) | Bağımsız bileşenler ayrı lisans  
**Deployment:** Cloud-native (Azure tabanlı)  
**Lisans Modeli:** Microsoft 365 / Azure aboneliği

---

## Nedir?

Microsoft Defender XDR, Microsoft'un genişletilmiş tespit ve müdahale platformudur. Daha önce ayrı ürünler olarak sunulan Defender for Endpoint, Defender for Identity, Defender for Office 365, Defender for Cloud Apps ve Microsoft Sentinel bileşenlerini tek bir güvenlik portalında birleştirir. Microsoft ekosistemi içindeki kuruluşlar için en doğal seçimdir: M365 E5 lisansına sahip bir organizasyon ek maliyet olmadan tam XDR kapasitesi elde eder.

---

## Temel Bileşenler

| Bileşen | Kapsam |
|---|---|
| **Defender for Endpoint (P2)** | EDR, NGAV, saldırı yüzeyi azaltma, threat hunting |
| **Defender for Identity** | Active Directory / Entra ID kimlik tehditleri, lateral movement |
| **Defender for Office 365 (P2)** | Email, link ve ek güvenliği; phishing koruma |
| **Defender for Cloud Apps** | CASB; SaaS uygulama görünürlüğü ve kontrol |
| **Microsoft Sentinel** | Cloud-native SIEM (ayrı ücretlendirme — veri ingest bazlı) |
| **Copilot for Security** | Generatif AI destekli soruşturma ve tehdit avcılığı |

---

## Temel Özellikler

| Özellik | Açıklama |
|---|---|
| **Unified SOC portal** | Tüm Defender bileşenleri tek konsoldan yönetilir. |
| **Automatic Attack Disruption** | Aktif saldırıyı insan müdahalesine gerek kalmadan otomatik durdurur. |
| **UEBA (User & Entity Behavior Analytics)** | Kullanıcı ve varlık davranış analitikleri ile insider threat tespiti. |
| **Copilot for Security** | Doğal dille olay soruşturma, script analizi, KQL sorgu üretimi. |
| **Threat Intelligence (MSTIC)** | Microsoft Threat Intelligence Center'ın global tehdit verisi. |
| **MITRE ATT&CK Mapping** | Tespitlere otomatik ATT&CK ID eşleme. |
| **Azure Active Directory entegrasyonu** | Entra ID ile native bütünleşme; koşullu erişim politikaları. |

---

## Artılar

- **M365 E5 ile dahil:** Zaten Microsoft ekosistemi kullanan kuruluşlar için ek maliyet yok.
- **Entegrasyon kolaylığı:** Azure AD, Exchange, Teams, SharePoint ile native entegrasyon.
- **Deployment hızı:** Out-of-the-box data connector'lar kurulumu kolaylaştırır.
- **Ölçeklenebilirlik:** Azure altyapısına dayandığı için elastik ölçekleme.
- **UEBA kalitesi:** Insider threat ve anormal davranış tespitinde güçlü.
- **Copilot for Security:** Doğal dil ile KQL sorgusu yazmak analist üretkenliğini artırır.
- **Geniş platform desteği:** Windows, macOS, Linux, iOS, Android.

---

## Eksiler

- **Microsoft ekosistemi bağımlılığı:** Microsoft dışı ortamlarda veri toplama ve entegrasyon daha karmaşık.
- **Sentinel veri maliyeti:** Log ingest'e göre fiyatlandırma beklenmedik maliyetlere yol açabilir.
- **Sınırlı üçüncü taraf entegrasyonu:** Splunk veya Wazuh gibi araçlara kıyasla daha az 3. taraf bağlantı.
- **KQL öğrenme eğrisi:** Kusto Query Language güçlü ama karmaşık; analistler zaman harcamalı.
- **Logic Apps SOAR kısıtlaması:** Playbook otomasyonu Azure Logic Apps'a bağlı; Microsoft dışı araçlara adapte zorlu.
- **Fiyat opak** Microsoft paketleri karmaşık; gerçek maliyet hesaplamak zordur.

---

## Kullanım Alanları

- Microsoft 365 / Azure ağırlıklı kuruluşlar
- Kimlik tabanlı saldırı tespiti ve müdahale
- Email güvenliği ve phishing koruması
- Entegre SOC operasyonu arayan Microsoft kurumsal müşterileri
- Insider threat yönetimi

---

## Kaynaklar

- [Microsoft 365 Defender Portalı](https://security.microsoft.com)
- [Copilot for Security](https://www.microsoft.com/en-us/security/business/ai-machine-learning/microsoft-copilot-security)
- [Microsoft Sentinel Fiyatlandırma](https://azure.microsoft.com/en-us/pricing/details/microsoft-sentinel/)

---

*Rapor tarihi: 2025 Q2 | AltHack Security — Security Products Serisi*
