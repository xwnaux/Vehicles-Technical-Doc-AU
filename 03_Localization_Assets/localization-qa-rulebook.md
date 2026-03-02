# BYD AU Warranty & Service  
## Localization QA Rulebook  
**Version 1.0**  
Owner: Technical Documentation & Pre-Sales Operations  

---

## 1. Purpose

This QA Rulebook defines linguistic, terminological, formatting, and compliance validation rules to ensure consistency, regulatory alignment, and audit readiness across BYD Australia warranty and service documentation.

This rulebook applies to:

- DITA topic content  
- Sales enablement materials  
- Warranty & service handbook extracts  
- Customer-facing compliance documentation  

---

## 2. Terminology Consistency Rules

### 2.1 Preferred Terms Enforcement

| Preferred Term | Disallowed / Deprecated |
|---------------|-------------------------|
| Scheduled Service | Regular Check |
| Warranty Eligibility | Warranty Qualification |
| Authorized Service Centre | Approved Workshop |
| Over-the-Air (OTA) Update | Wireless Update |

**QA Check:**
- Termbase validation must flag deprecated terms.
- Only preferred terms may appear in customer-facing documentation.

---

### 2.2 Abbreviation First-Use Rule

- Spell out full form on first occurrence:
  - Battery Management System (BMS)
  - Over-the-Air (OTA)
- Abbreviation allowed after first reference.

**QA Check:**
- Detect abbreviation without prior expansion.

---

## 3. Numeric & Unit Rules (AU English Standard)

### 3.1 Unit Format

- kWh (not KWh / kwh)  
- km (not KM)  
- °C (not C degrees)  
- 12-month (hyphenated when adjective)  

**QA Check:**  
Use regex validation to flag incorrect casing or formatting.

---

### 3.2 Number Formatting

- Use space between number and unit: `60 kWh`  
- Use comma for thousands: `10,000 km`  
- No space before `%`  

Correct:
- 80%  

Incorrect:
- 80 %  

---

## 4. Legal & Warranty Language Controls

### 4.1 Avoid Absolute Guarantees

**Disallowed phrasing:**
- “Guaranteed replacement”
- “Full coverage in all cases”

**Required phrasing:**
- “Subject to warranty terms”
- “Final determination follows internal review”

**QA Check:**  
Flag absolute certainty words (always, guaranteed, never).

---

## 5. Structural DITA Compliance Rules

### 5.1 Topic Granularity

- Concept topics: no procedural steps.  
- Task topics: must include structured steps.  
- Reference topics: factual tone only, no instructional language.  

**QA Check:**  
Validate DITA structure integrity before publishing.

---

### 5.2 Sentence Length

- Maximum recommended: 25–30 words per sentence.  
- Avoid nested subordinate clauses.

Purpose:  
Improve clarity for non-technical customers.

---

## 6. Consistency & Cross-Topic Validation

- Terms in TBX must match TMX memory.  
- No conflicting definitions across topics.  
- Version number must align across:
  - Release notes  
  - Warranty overview topic  
  - Service interval reference  

---

## 7. Translation-Specific Controls (EN ↔ ZH)

### 7.1 Tone Consistency

English:
- Formal, neutral, compliance-oriented.  

Chinese:
- 专业、严谨、避免口语化表达。

---

### 7.2 Semantic Risk Words

| English | Risk Translation |
|----------|----------------|
| May affect | 不一定影响 ❌ |
| Subject to review | 必须通过审核 ❌ |
| Wear and tear | 损坏 ❌ |

Use TBX-approved equivalents only.

---

## 8. Workflow & Governance Controls

QA must be performed at:

1. Draft completion  
2. SME review  
3. Pre-release validation  

Each release requires:

- Terminology validation  
- Numeric check  
- Legal phrase audit  
- Structural DITA validation  
- Version confirmation  

---

## 9. Tool Compatibility

Designed for:

- Trados Studio QA Checker  
- Phrase QA Settings  
- Xbench Glossary Control  
- Regex-based automated validation  

---

## 10. Compliance Objective

The QA system ensures documentation is:

- Terminology-controlled  
- Structurally modular  
- Legally safe  
- Audit-ready  
- Localization-consistent  
- Reusable across product lines  