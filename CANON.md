# DOMAINS — CANON

inherits: /CANONIC/

---

## Axiom

**DOMAINS = DETROS. Content layer.**

---

## Structure

```
DOMAINS/
├── MED/            — pan-MED ontologies
│   ├── SNOMED/
│   ├── ICD/
│   ├── LOINC/
│   ├── RXNORM/
│   └── CPT/
├── ONCO/           — pan-ONCO
│   ├── MCODE/
│   ├── TNM/
│   └── HGVS/
└── MAMMO/          — breast-specific
    ├── NCCN/
    └── BIRADS/
```

---

## Flow

```
DOMAINS (content) → DETROS (filter) → SHOP (trade)
```

SHOP/MED inherits DOMAINS/MED.

---

## DETROS Mapping

| Dim | DOMAINS role |
|-----|--------------|
| D | Ontology definitions |
| E | Evidence sources |
| T | Version history |
| R | Hierarchy (MED→ONCO→MAMMO) |
| O | Query endpoints |
| S | Schema (FHIR, mCODE) |

---

## Constraints

1. DOMAINS = canonical evidence.
2. SHOP inherits DOMAINS.
3. DETROS filters DOMAINS.

---

*DOMAINS | DETROS | Content*
