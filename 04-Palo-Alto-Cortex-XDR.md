# Palo Alto Networks Cortex XDR

**Kategori:** XDR / EDR  
**Geliştirici:** Palo Alto Networks  
**Fiyatlandırma:** Talep üzerine (Cortex XDR Prevent / Pro per Endpoint, per GB modeli)  
**Deployment:** Cloud-native (Cortex Data Lake üzerinde)  
**Lisans Modeli:** Ticari, abonelik tabanlı

---

## Nedir?

Palo Alto Networks Cortex XDR, endpoint, ağ, cloud ve üçüncü taraf veri kaynaklarından gelen telemetriyi birleştirerek tehditleri tespit eden, araştıran ve müdahale eden birleşik bir XDR platformudur. Palo Alto'nun geniş güvenlik ekosistemine (Prisma Cloud, XSOAR, Strata firewall) native entegrasyon ile bağlanır. Cortex Data Lake üzerinde çalışır ve büyük veri analitiği kapasitesi sunar.

---

## Temel Özellikler

| Özellik | Açıklama |
|---|---|
| **Cortex Data Lake** | Endpoint, ağ ve cloud verisini birleştiren merkezi veri gölü. |
| **Behavioral Analytics (XDR Analytics)** | ML tabanlı anomali tespiti; bilinmeyen tehditleri yakalar. |
| **Causality Analysis Engine (CAE)** | Her tespite kök neden ve saldırı zinciri analizi ekler. |
| **Exploit Protection** | Memory injection, stack pivot ve heap spray korumaları. |
| **Threat Intelligence (AutoFocus)** | Palo Alto Unit 42 tehdit istihbaratı ile beslenir. |
| **XSOAR Entegrasyonu** | Cortex XSOAR ile native playbook ve otomasyon bağlantısı. |
| **Live Terminal** | Uzaktan canlı terminal erişimi ile anlık müdahale. |
| **BIOC / IOC** | Davranışsal ve imza tabanlı göstergeler ile özel tespit kuralları. |

---

## Artılar

- **Palo Alto ekosistemine entegrasyon:** NGFW, Prisma Cloud ve XSOAR ile bütünleşik çalışma.
- **Veri gölü mimarisi:** Büyük hacimli log ve telemetri analizi için güçlü altyapı.
- **Unit 42 tehdit istihbaratı:** Palo Alto'nun aktif araştırma ekibinden beslenen güncel tehdit verisi.
- **Kök neden analizi:** CAE ile her olay için otomatik zincir oluşturma.
- **Ağ görünürlüğü:** Firewall telemetrisi ile endpoint verisini birleştirme yeteneği.
- **Container güvenliği:** Kubernetes ve container ortamlarında çalışma desteği.

---

## Eksiler

- **Palo Alto ekosistemi bağımlılığı:** Tam değer Palo Alto ürünleri ile kullanımda ortaya çıkar.
- **Fiyat:** Enterprise segmentinde üst düzey fiyatlandırma; Palo Alto tek başına XDR için pahalı.
- **Öğrenme eğrisi:** Cortex Query Language (XQL) öğrenmesi ve platform karmaşıklığı.
- **Deployment karmaşıklığı:** Cortex Data Lake kurulumu ve yapılandırması uzmanlık gerektirir.
- **Destek değişkenliği:** Bazı kullanıcılar teknik destek kalitesinin tutarsız olduğunu belirtiyor.
- **Non-Palo Alto ortamlarda sınırlı:** Üçüncü taraf entegrasyon CrowdStrike veya SentinelOne'a kıyasla daha az zengin.

---

## Kullanım Alanları

- Palo Alto Networks firewall altyapısı kullanan kuruluşlar
- Ağ ve endpoint telemetrisini birleştirmek isteyen SOC ekipleri
- Büyük enterprise ortamlarında kök neden analizi
- Cortex XSOAR ile entegre otomasyon iş akışları

---

## Kaynaklar

- [Cortex XDR Ürün Sayfası](https://www.paloaltonetworks.com/cortex/cortex-xdr)
- [Unit 42 Threat Intelligence](https://unit42.paloaltonetworks.com)
- [Cortex Data Lake](https://www.paloaltonetworks.com/cortex/cortex-data-lake)

---

*Rapor tarihi: 2025 Q2 | AltHack Security — Security Products Serisi*
