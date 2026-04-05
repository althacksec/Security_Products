# SentinelOne (Platform Genel Bakış)

**Kategori:** Siber Güvenlik Platformu (EDR / XDR / CNAPP / ITDR / AI-SIEM)  
**Geliştirici:** SentinelOne, Inc.  
**Kuruluş:** 2013, Tel Aviv | Borsa: NYSE: S  
**Fiyatlandırma:** Core $69.99 → Enterprise talep üzerine  
**Deployment:** Cloud-native SaaS

---

## Platform Genel Bakışı

SentinelOne, 2013'te Tel Aviv'de kuruldu. İlk odak noktası endpoint güvenliğiydi; zaman içinde kimlik, cloud ve SIEM kapasitelerini satın alımlarla platformuna kattı. Bugün, tek AI motoru etrafında şekillenmiş, çok katmanlı bir güvenlik platformuna dönüştü.

---

## Büyüme Haritası

| Yıl | Gelişme |
|---|---|
| 2013 | Endpoint güvenlik odaklı kuruluş |
| 2022 | Attivo Networks satın alımı → ITDR kapasitesi |
| 2023 | PingSafe satın alımı → CNAPP kapasitesi |
| 2024 | AI-SIEM (Purple AI) ve Singularity Data Lake olgunlaşması |
| 2025 | 5. kez Gartner EPP Magic Quadrant Leader |

---

## Platform Katmanları

```
┌────────────────────────────────────────────┐
│           Singularity Platform             │
├──────────────┬──────────────┬──────────────┤
│  Endpoint    │   Identity   │    Cloud     │
│  (EDR/XDR)  │   (ITDR)    │   (CNAPP)    │
├──────────────┴──────────────┴──────────────┤
│         Singularity Data Lake              │
├────────────────────────────────────────────┤
│    Purple AI / AI-SIEM / Threat Hunting    │
└────────────────────────────────────────────┘
```

---

## Platform Farkı: Özerklik

SentinelOne'ın temel iddiası: **otonom müdahale**. Agent, tehdit tespit ettiğinde bulut bağlantısı olmadan bile kendi başına:
- Prosesi öldürür
- Karantinaya alır
- Dosyaları geri alır (VSS Rollback)
- Uyarı gönderir

Bu yaklaşım, tepki süresini insan müdahalesinden bağımsız kılar.

---

## Artılar

- Otonom yanıt; 7/24 insan gerekmeden tehdit müdahalesi
- VSS Rollback; ransomware sonrası dosya kurtarma
- Storyline; otomatik saldırı zinciri görselleştirme
- Geniş platform kapsami; endpoint + kimlik + cloud + SIEM
- 5 yıl üst üste Gartner Leader

## Eksiler

- Complete paketi fiyatı yüksek ($179.99+)
- Policy granülaritesi sınırlı
- 3. taraf entegrasyon geliştirme alanı var
- DFIR hizmet kalitesi kullanıcılar arasında tartışmalı

---

## Kaynaklar

- [SentinelOne Resmi Site](https://www.sentinelone.com)
- [Singularity Platform Paketleri](https://www.sentinelone.com/platform-packages/)

---

*Rapor tarihi: 2025 Q2 | AltHack Security — Security Products Serisi*
