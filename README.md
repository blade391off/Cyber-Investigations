# Cyber-Investigations
Open-source cyber threat investigations, malware intelligence, IOCs, TTPs, threat actor research and YARA detection rules.

## 🎯 About

**Cyber-Investigations** is a collection of defensive cybersecurity investigations focused on malware, cyber threat actors and real-world campaigns.

Each investigation is based on publicly available technical reports, security research and other open-source intelligence.

The goal is to organize technical evidence in a structured and useful format for malware analysis and threat intelligence research.

## 🧬 Malware Investigations

Each malware investigation may contain:

* Technical overview
* Malware family
* Threat actor attribution
* Confidence level
* Tactics, Techniques and Procedures (TTPs)
* Timeline
* Indicators of Compromise (IOCs)
* Related tools and infrastructure
* Sources and references
* YARA detection rule

Each malware directory contains a small, focused YARA rule designed around the strongest available detection characteristics.

## 🕵️ Threat Actor Research

Threat actor investigations document:

* Known aliases
* Associated malware and tools
* Targeted organizations or sectors
* Known campaigns
* TTPs
* Infrastructure
* Timeline
* Attribution evidence
* Confidence level
* References

Attribution is treated as an assessment rather than an absolute fact unless it is directly confirmed by reliable sources.

## 📊 Confidence Levels

Attribution and other investigative assessments use the following confidence levels:

| Level            | Meaning                                                             |
| ---------------- | ------------------------------------------------------------------- |
| 🟢 **Confirmed** | Directly confirmed by reliable evidence                             |
| 🔵 **High**      | Strong evidence supports the assessment                             |
| 🟡 **Moderate**  | Multiple indicators support the assessment, but uncertainty remains |
| 🟠 **Low**       | Limited or indirect evidence                                        |
| ⚪ **Unknown**    | Insufficient evidence to make an assessment                         |

Confidence levels are applied to individual claims where appropriate, rather than automatically treating an entire investigation as equally certain.

## 🧪 YARA

YARA rules are included for malware detection and research purposes.

Rules are designed for:

* YARA **4.5.0** compatibility
* Low false-positive potential
* Strong and meaningful detection characteristics
* Malware-family or sample-specific identification where possible

Rules are validated before being added to the repository.

## 🔍 IOCs

Depending on the investigation, collected indicators may include:

* SHA-256
* SHA-1
* MD5
* File names
* Domains
* IP addresses
* URLs
* File paths
* Registry keys
* Mutexes
* Other technical indicators

IOCs are accompanied by their sources whenever possible.

## 📚 Sources

Research is based on publicly available information from sources such as:

* Security vendors
* CERTs and government agencies
* MITRE ATT&CK
* Malware analysis platforms
* Incident response reports
* Academic and independent security research

Sources are provided for individual investigations to allow the underlying evidence to be independently reviewed.

## ⚠️ Disclaimer

This repository is intended for **defensive cybersecurity research, malware analysis and threat intelligence purposes**.

The information is provided to help researchers understand and detect cyber threats. No content in this repository is intended to facilitate unauthorized access, disruption of systems or other malicious activity.

## 👤 Author

**blade391off**

Cybersecurity and malware analyst

---

⭐ If you find the research useful, consider starring the repository.

