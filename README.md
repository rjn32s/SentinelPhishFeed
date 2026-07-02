![Auto Update](https://img.shields.io/badge/feed-auto--updated-brightgreen)


# SentinelPhishFeed
![SentinelPhishFeed Banner](assets/banner.png)

SentinelPhishFeed is an **automated phishing threat intelligence feed**
that provides continuously updated **phishing URLs, malicious IPs,
domains, and IOC data** for defensive cybersecurity use.

It is designed for **SOC teams, blue teams, security researchers,
and detection engineers** who need a reliable, high-signal
**phishing feed** without per-source attribution.

---

## What SentinelPhishFeed provides

- **Phishing URLs feed** → `urls.txt`
- **Malicious IP address feed** → `ips.txt`
- **Phishing & malware domains** → `domains.txt`
- **File hash IOCs** → `hashes.txt`
- **Metadata & timestamps** → `metadata.json`

All indicators are deduplicated, normalized, and ingestion-ready.

---

## Intended use cases

- Phishing detection and prevention
- SOC alert enrichment
- SIEM / SOAR ingestion
- Threat hunting
- Security research

---

<!-- STATS:START -->
## Latest Statistics

- IPs: 201,399
- URLs: 22,437
- Domains: 391,561
- Hashes: 10,089

Last updated: 2026-07-02T19:23:04Z
<!-- STATS:END -->

---

## Update frequency

SentinelPhishFeed updates automatically multiple times per day.
Each update fully replaces the previous dataset.

---

## Disclaimer

This repository is provided **for defensive security purposes only**.
Indicators are provided *as-is*, without warranty or guarantees.
False positives may exist.
