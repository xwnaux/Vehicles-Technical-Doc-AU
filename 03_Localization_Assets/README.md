# 03_Localization_Assets  
## BYD AU Warranty & Service – Localization Engineering Assets

This directory contains structured localization assets designed to simulate an enterprise-level technical documentation and governance workflow for BYD Australia warranty and service materials.

The assets in this folder demonstrate terminology governance, translation memory management, and quality assurance control in a structured DITA-based documentation environment.

---

## 📂 File Overview

### 1. `byd-au-warranty-termbase.tbx`
Basic TBX terminology file containing controlled bilingual terminology (EN-AU ↔ ZH-CN).

Includes:
- Preferred terminology
- Definitions
- Domain tagging
- Structured concept entries

Purpose:
- Terminology consistency across warranty and service documentation
- Importable into Trados / Phrase
- Supports automated term validation

---

### 2. `byd-au-warranty-termbase-enterprise.tbx`
Enterprise-level TBX asset aligned with ISO 30042.

Includes:
- Preferred / admitted / deprecated terms
- Subject field classification
- Part-of-speech tagging
- Usage notes
- Administrative metadata (approval date, ownership)
- Compliance-aware terminology governance

Purpose:
- Demonstrates structured terminology lifecycle management
- Supports QA automation and regulatory-ready documentation

---

### 3. `byd-au-warranty-memory.tmx`
Translation Memory (TMX 1.4b format) aligned with the approved termbase.

Includes:
- Sentence-level translation units
- Domain metadata
- Status tagging
- Creation metadata
- Terminology alignment with TBX

Purpose:
- CAT tool interoperability (Trados / Phrase compatible)
- Ensures cross-document translation consistency
- Enables reuse of validated segments

---

### 4. `localization-qa-rulebook.md`
Localization Quality Assurance governance framework.

Defines:
- Terminology enforcement rules
- Abbreviation and numeric standards
- Legal risk phrase control
- DITA structural compliance validation
- Cross-topic consistency checks
- EN ↔ ZH linguistic alignment rules

Purpose:
- Establishes audit-ready QA validation workflow
- Supports automated QA configuration in CAT tools
- Reduces legal and compliance risk in customer-facing materials

---

## 🔧 Workflow Integration Model

These assets are designed to function together within a structured documentation lifecycle:

1. Content authored in DITA topics  
2. Terminology validated against TBX  
3. Segments translated using TMX memory  
4. QA validated via Rulebook  
5. Release governed by version control  

This modular system supports:

- Content reuse across vehicle models  
- Regulatory alignment  
- Terminology consistency  
- Cross-department collaboration  
- Pre-sales documentation scalability  

---

## 🧠 Competencies Demonstrated

This folder reflects capabilities in:

- Localization Engineering  
- Terminology Governance  
- Translation Memory Architecture  
- Structured Content Strategy  
- QA Automation Design  
- Documentation Lifecycle Governance  

---

## Compliance & Scope Notice

This repository is a professional portfolio reconstruction based on public industry patterns and structured documentation best practices. It is not an official BYD publication.

---

Author:  
Technical Documentation & Product Operations Portfolio