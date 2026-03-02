# 01_DITA_Map_and_Topics  
## Structured Authoring Architecture (DITA-Based)

This directory contains the structured content architecture for the BYD AU Warranty & Service Knowledge Base.

All documentation in this project is designed using DITA (Darwin Information Typing Architecture) principles to ensure modularity, reuse, scalability, and governance control.

---

# Purpose

This layer defines:

- Topic-based authoring structure
- Content modularization strategy
- Reusable documentation components
- Separation of Concept / Task / Reference logic
- Controlled publishing hierarchy via DITA map

The objective is to simulate an enterprise-ready structured documentation framework aligned with automotive and compliance-driven documentation standards.

---

# Directory Contents

### byd-au-warranty-service-map.ditamap

The master DITA map controlling:

- Topic hierarchy
- Navigation structure
- Content assembly
- Publication scope

This file represents the publishing entry point for the warranty & service knowledge base.

---

### concept_warranty_overview.dita

Concept topic explaining:

- High-level warranty principles
- Scope definitions
- Customer responsibilities
- Structural overview

Purpose:
Provide foundational understanding without procedural instruction.

---

### task_maintain_warranty_eligibility.dita

Task topic defining:

- Step-by-step process requirements
- Structured procedural flow
- Compliance-sensitive instructions

Purpose:
Standardize customer-facing and internal operational steps.

---

### reference_service_intervals.dita

Reference topic providing:

- Service interval principles
- Maintenance categories
- Documentation requirements

Purpose:
Deliver factual, structured, reusable information.

---

### faq_warranty_service.dita

Concept-based FAQ topic covering:

- Common warranty questions
- Risk-sensitive phrasing
- Compliance-aware responses

Purpose:
Support pre-sales and customer service alignment.

---

# Structured Authoring Principles Applied

This directory demonstrates:

- Topic-based authoring
- One primary purpose per topic
- Modular content reuse
- Legal-safe wording structure
- Cross-topic terminology control
- DITA structural compliance

---

# Modular Strategy

Each topic is designed to:

- Be reusable across vehicle models
- Avoid duplication
- Separate procedural and descriptive content
- Support scalable expansion
- Enable automated publishing pipelines

---

# Governance Integration

All topics in this directory must comply with:

- Content Style Guide (02_Content_Style_Guide)
- Approved Terminology (03_Localization_Assets/TBX)
- QA Rulebook validation
- Lifecycle workflow controls (04_Governance_and_Workflow)

No topic may bypass terminology validation before publication.

---

# Competencies Demonstrated

This directory reflects capabilities in:

- Structured content architecture design
- DITA map hierarchy control
- Modular technical writing
- Governance-aware documentation strategy
- Enterprise documentation scalability

---

# Scope Notice

This repository is a structured documentation portfolio reconstruction based on industry best practices. It is not an official BYD publication.

---

Author:  
Technical Documentation & Product Operations Portfolio