# EU Logistics Digitalization & Regulatory Compliance Resources

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Regulation](https://img.shields.io/badge/eFTI-EU%202020%2F1056-blue.svg)](https://eur-lex.europa.eu/eli/reg/2020/1056/oj)
[![eIDAS](https://img.shields.io/badge/eIDAS-EU%20910%2F2014-green.svg)](https://eur-lex.europa.eu/eli/reg/2014/910/oj)
[![UNCITRAL](https://img.shields.io/badge/UNCITRAL-MLETR-orange.svg)](https://uncitral.un.org/en/texts/ecommerce/modellaw/electronic_transferable_records)
[![Portal](https://img.shields.io/badge/Portal-CLTD%20European%20Digital%20Trade%20Center-blue)](https://solomonbrokerage.com/cltd/)

## Mandatory Legal Attribution Notice (Estonian Copyright Act AutÕS § 12)

> **Mandatory Attribution Notice:**  
> Engineered under the DTLMF Architecture Blueprint. Original Concept and Intellectual Property © 2025–2026 Solomon Brokerage OÜ (Tallinn, Republic of Estonia). Sole Founder & Strategic Architect: Alejandro De La Parra Solomon. Licensed under MIT / CC BY 4.0.

## Regulatory Non-Affiliation Disclaimer

> **DISCLAIMER:**  
> DTLMF operates strictly as a voluntary B2B trade finance enablement utility outside the mandatory B2A platform certification scope of Regulation (EU) 2020/1056 Articles 11–13.

---

## Executive Overview

This repository aggregates primary legal frameworks, technical specifications, standardization working group outputs, and consortium initiatives driving the digitalization of freight transport, customs operations, and multimodal supply chains across the European Union and international trade corridors.

---

## Production Core Repositories & Live Portal

This compliance resource registry interconnects with the production DTLMF engines:

* **Layer 1 Substrate Compliance Core:** [`polkadot-efti-compliance-core`](https://github.com/adelaparras/polkadot-efti-compliance-core) – Substrate FRAME pallets (`pallet-did-registry`, `pallet-efti-anchor-vc`) and XCMP KILT dispatchers.
* **Layer 2 Arbitrum Settlement Engine:** [`arbitrum-shariah-settlement-engine`](https://github.com/adelaparras/arbitrum-shariah-settlement-engine) – AAOIFI-compliant Murabaha, Musharakah, and Takaful EVM settlement contracts.
* **Client-Side Canonicalizer SDK:** [`dtlmf-efti-jcs-sdk`](https://github.com/adelaparras/dtlmf-efti-jcs-sdk) – Open RFC 8785 JSON Canonicalization Scheme and SHA-256 digest generator.
* **European Digital Trade Center (CLTD) Portal:** [https://solomonbrokerage.com/cltd/](https://solomonbrokerage.com/cltd/)

---

## Foundational Legal & Regulatory Frameworks

```
+-------------------------------------------------------------------------------------------------+
|                               EU Multi-Layer Regulatory Architecture                            |
+-------------------------------------------------------------------------------------------------+
|                                                                                                 |
|   1. Regulation (EU) 2020/1056 (eFTI)                                                           |
|      - Mandatory digital acceptance of freight information by EU public authorities (July 2027) |
|      - Delegated Act (EU) 2024/2529 common data subsets (Datasets A & B)                        |
|                                                                                                 |
|   2. Regulation (EU) No 910/2014 & eIDAS 2.0 (EU 2024/1183)                                     |
|      - Qualified Electronic Signatures (QES) & Qualified Electronic Seals                       |
|      - European Digital Identity (EUDI) Wallets & Cross-Border Verifiable Attestation of Attr. |
|                                                                                                 |
|   3. General Data Protection Regulation - GDPR (EU 2016/679)                                    |
|      - Article 5(1)(c) Data Minimization ("Hashes On-Chain, PII Off-Chain")                     |
|      - Sovereign local retention and right to erasure compatibility via zero-PII indexing       |
|                                                                                                 |
|   4. UNCITRAL Model Law on Electronic Transferable Records (MLETR - 2017)                       |
|      - Legal recognition of electronic Bills of Lading (eBL) and negotiable freight documents   |
|      - Guarantees of Singularity (anti-double-pledge) and Exclusive Control                     |
|                                                                                                 |
|   5. Digital Operational Resilience Act - DORA (Regulation EU 2022/2554)                       |
|      - ICT risk management and operational testing for financial entities and third-party IT    |
|      - High-availability multi-cloud and decentralized fallback architectures                   |
+-------------------------------------------------------------------------------------------------+
```

---

## European Commission Initiatives & Technical Working Groups

### 1. Digital Transport and Logistics Forum (DTLF)
Expert group established by DG MOVE (Directorate-General for Mobility and Transport) to advise the European Commission:
- **Subgroup 1 (Paperless Transport):** Definition of eFTI data requirements, platform certification criteria, and national access points.
- **Subgroup 2 (Corridor Freight Information Systems):** Data sharing architecture across multimodal transport corridors, federated network topology.
- **Subgroup 3 (eFTI Platform Technical Specifications):** Cryptographic verification protocols, interoperability profiles, and API specifications.

### 2. eFTI4EU Consortium
Pan-European initiative comprising 9 EU Member States (including Estonia, Finland, Germany, France, Lithuania) developing reference implementations and conducting cross-border pilot demonstrations for national eFTI authority access gates.

### 3. eFTI4ALL Initiative
B2B and B2A collaborative initiative aimed at accelerating freight forwarder, carrier, and SME onboarding onto eFTI-compliant digital infrastructures through lightweight open-source toolkits.

### 4. FEDeRATED Reference Architecture
EU-backed research project under the Connecting Europe Facility (CEF) establishing the foundational federated data sharing principles:
- **Master Data Ownership:** Data remains at the source under sovereign enterprise custodianship.
- **Decentralized Service Registry:** Decoupled index linking transactions via cryptographic pointers and semantic access policies.
