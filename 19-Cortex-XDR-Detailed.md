# Palo Alto Cortex XDR — Detaylı Teknik İnceleme

**Kategori:** XDR (Extended Detection and Response)  
**Geliştirici:** Palo Alto Networks  
**Fiyatlandırma:** Prevent (endpoint başına) / Pro (GB bazlı) — talep üzerine  
**Deployment:** Cortex Data Lake (cloud) üzerinde SaaS  
**Lisans Modeli:** Ticari; Prevent ve Pro tiers

---

## Nedir ve CrowdStrike/SentinelOne'dan Ne Farkı Var?

CrowdStrike ve SentinelOne endpoint-first yaklaşımla büyüdü. Cortex XDR ise ağ güvenliği kökenli Palo Alto Networks'ün genişletilmiş görünürlük vizyonudur. En önemli fark: **Palo Alto firewall telemetrisi** ile endpoint verisini birleştiren doğal ağ + endpoint korelasyonu.

---

## Mimari

```
Cortex Data Lake
    ├── Endpoint telemetrisi (Cortex XDR Agent)
    ├── Ağ telemetrisi (Palo Alto NGFW, Prisma)
    ├── Cloud telemetrisi (Prisma Cloud)
    └── 3. taraf veri kaynakları
```

---

## Temel Özellikler Derinlemesine

### Causality Analysis Engine (CAE)
Her tespit için otomatik kök neden analizi yapar. "Bu alert neden tetiklendi?" sorusunu otomatik yanıtlar; analist iş yükünü azaltır.

### Behavioral Analytics (XDR Analytics)
Makine öğrenmesi ile kullanıcı ve varlık davranışındaki anomalileri tespit eder. Bilinmeyen tehditler (zero-day, insider threat) için kritik.

### BIOC (Behavioral Indicators of Compromise)
Kullanıcı tarafından tanımlanabilen davranışsal göstergeler. Özelleştirilmiş tespit kuralı yazımına olanak tanır.

### Network Correlation
Palo Alto firewall'larından gelen ağ trafiği ile endpoint aktivitesini korele eder. Lateral movement gibi ağ tabanlı saldırı zincirlerini uçtan uca görür.

---

## Artılar

- **Ağ + Endpoint korelasyonu:** Palo Alto ekosisteminde eşsiz bütünleşik görünürlük
- **Cortex Data Lake:** Büyük veri analitik kapasitesi; uzun dönem tehdit avı
- **Unit 42 istihbaratı:** Dünyaca tanınan tehdit araştırma ekibinden besleniyor
- **XSOAR entegrasyonu:** Playbook otomasyonu native olarak çalışır
- **Container/K8s desteği:** Modern cloud-native ortamlar için hazır

## Eksiler

- **Palo Alto ekosistemi dışında değer düşer:** NGFW yoksa ağ korelasyonu avantajı ortadan kalkar
- **Maliyet:** Büyük enterprise için erişilebilir, orta ölçek için yüksek
- **XQL öğrenme eğrisi:** Elastic'in EQL veya Splunk'ın SPL'ine benzer ancak kendine has
- **Deployment karmaşıklığı:** Özellikle büyük Cortex Data Lake kurulumları uzmanlık ister
- **Destek tutarsızlığı:** Bazı kullanıcılar teknik destek kalitesinin değişken olduğunu belirtiyor

---

## Ne Zaman Tercih Edilmeli?

Cortex XDR doğru seçimdir, eğer:
- Zaten Palo Alto NGFW altyapınız varsa
- Ağ ve endpoint telemetrisini tek konsolda birleştirmek istiyorsanız
- Cortex XSOAR ile entegre otomasyon kuruyorsanız
- Unit 42 tehdit istihbaratına entegre erişim istiyorsanız

Alternatif düşünün, eğer:
- Palo Alto ekosisteminiz yoksa
- Bütçe kısıtlaması varsa
- Hızlı deployment öncelikliyse

---

## Kaynaklar

- [Cortex XDR](https://www.paloaltonetworks.com/cortex/cortex-xdr)
- [Unit 42 Tehdit Araştırma](https://unit42.paloaltonetworks.com)
- [Cortex Data Lake](https://www.paloaltonetworks.com/cortex/cortex-data-lake)

---

*Rapor tarihi: 2025 Q2 | AltHack Security — Security Products Serisi*
