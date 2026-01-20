# Basque E-Invoicing Project - Task List

> **Session State Saved**: 2026-01-19
> Track progress by marking items as completed: `- [x]`

---

## Session Recovery Instructions

**To resume this project:**

1. Read `CLAUDE.md` first - contains project overview and key findings
2. Read `docs/QUICK-REFERENCE.md` - one-page summary of all conclusions
3. Review the "Key Findings Summary" section below
4. Continue with Phase 7 (Implementation Planning) or remaining Phase 5 tasks

**What was accomplished:**
- Phases 1-4 and 6: ~90% complete (research and documentation)
- Phase 5 (Record Keeping): ~50% complete
- 14 key documents created with researched content
- All priority questions answered

**Key conclusion for foreign EU sellers to Basque Country:**
- TicketBAI: NOT APPLICABLE (no fiscal residence)
- B2B: Use reverse charge (invoice without VAT)
- B2C: Use OSS (charge 21% Spanish VAT, file in home country)
- No Spanish VAT registration needed in most cases

---

## Phase 1: Foundation Research

### 1.1 Basque Tax System Basics
- [x] Research the Concierto Económico (Economic Agreement) basics
- [x] Document differences between Basque and Spanish national tax systems
- [x] Identify which province's rules apply based on transaction type
- [x] Create `docs/legal-compliance/concierto-economico.md`

### 1.2 Tax Identification Requirements
- [x] Research NIF/CIF requirements for foreign EU sellers
- [x] Document VAT registration requirements in Basque Country
- [x] Understand VIES validation for EU VAT numbers
- [ ] Create `docs/tax-codes/basque-tax-codes.md`
- [x] Create `docs/tax-codes/nif-cif-requirements.md`
- [ ] Create `docs/tax-codes/eu-vat-numbers.md`

### 1.3 VAT Rates and Rules
- [x] Document current Basque Country VAT rates (general, reduced, super-reduced)
- [x] Compare with Spanish national rates (note any differences)
- [x] Research applicable rates for different product/service categories
- [x] Create `docs/vat-rules/vat-rates-basque.md`

---

## Phase 2: Cross-Border EU Rules

### 2.1 Place of Supply Rules
- [x] Document place of supply rules for goods
- [x] Document place of supply rules for services (B2B)
- [x] Document place of supply rules for services (B2C)
- [x] Create `docs/eu-cross-border/place-of-supply.md`

### 2.2 B2B Transactions
- [x] Research reverse charge mechanism for B2B
- [x] Document when reverse charge applies
- [x] Document invoice requirements for reverse charge
- [x] Create `docs/eu-cross-border/b2b-transactions.md`
- [x] Create `docs/vat-rules/reverse-charge.md`

### 2.3 B2C Transactions
- [x] Research distance selling thresholds (post-July 2021 rules)
- [x] Document when local VAT registration is required
- [x] Research One-Stop Shop (OSS) applicability
- [x] Create `docs/eu-cross-border/b2c-transactions.md`
- [ ] Create `docs/eu-cross-border/thresholds.md`
- [x] Create `docs/vat-rules/oss-ioss.md`

### 2.4 Intra-EU VAT Overview
- [x] Compile comprehensive intra-EU VAT guide
- [x] Document evidence requirements for B2B supplies
- [ ] Create `docs/vat-rules/intra-eu-vat.md`

---

## Phase 3: Product/Service/Subscription Classification

### 3.1 Classification Framework
- [x] Define criteria for goods vs services classification
- [x] Document mixed supply treatment
- [x] Create decision tree for classification
- [x] Create `docs/services-vs-products/classification-guide.md`

### 3.2 Digital Services
- [x] Research EU digital services definition
- [x] Document special rules for electronically supplied services
- [x] Research MOSS/OSS for digital services
- [x] Create `docs/services-vs-products/digital-services.md`

### 3.3 Subscription Services
- [x] Research VAT treatment of subscriptions
- [x] Document tax point (time of supply) for recurring billing
- [x] Research prepayment vs pay-as-you-go treatment
- [x] Create `docs/services-vs-products/subscriptions.md`

### 3.4 Mixed/Bundled Supplies
- [x] Research bundled product/service treatment
- [x] Document principal vs ancillary supply rules
- [ ] Create `docs/services-vs-products/mixed-supplies.md`

---

## Phase 4: TicketBAI System

### 4.1 TicketBAI Overview
- [x] Research TicketBAI purpose and scope
- [x] Determine if TicketBAI applies to non-established sellers
- [x] Document implementation timeline and deadlines
- [x] Create `docs/ticketbai/overview.md`

### 4.2 Technical Requirements
- [x] Research XML schema requirements
- [x] Document digital signature requirements
- [x] Research QR code generation requirements
- [x] Document API/submission methods
- [ ] Create `docs/ticketbai/technical-specs.md`

### 4.3 Province-Specific Requirements
- [ ] Research Álava (TICKETBAI) specific requirements
- [ ] Research Bizkaia (BATUZ) specific requirements
- [ ] Research Gipuzkoa (TicketBAI) specific requirements
- [ ] Create `docs/ticketbai/alava-requirements.md`
- [ ] Create `docs/ticketbai/bizkaia-requirements.md`
- [ ] Create `docs/ticketbai/gipuzkoa-requirements.md`

---

## Phase 5: Record Keeping & Compliance

### 5.1 Retention Requirements
- [x] Research document retention periods (Basque and EU)
- [x] Document what records must be kept
- [x] Research electronic storage requirements
- [x] Create `docs/record-keeping/retention-periods.md`
- [ ] Create `docs/record-keeping/digital-storage.md`

### 5.2 Audit Trail
- [x] Document audit trail requirements
- [x] Research invoice numbering requirements
- [x] Document amendment/correction procedures
- [ ] Create `docs/record-keeping/audit-trails.md`

### 5.3 Legal Compliance
- [x] Research penalties for non-compliance
- [x] Document registration requirements and process
- [ ] Compile relevant EU directives
- [ ] Create `docs/legal-compliance/penalties.md`
- [ ] Create `docs/legal-compliance/registration-requirements.md`
- [ ] Create `docs/legal-compliance/eu-directives.md`

---

## Phase 6: Scenario Mapping

### 6.1 Define Common Scenarios
- [x] B2B physical goods: EU → Basque Country
- [x] B2C physical goods: EU → Basque Country
- [x] B2B services: EU → Basque Country
- [x] B2C services: EU → Basque Country
- [x] B2B digital services: EU → Basque Country
- [x] B2C digital services: EU → Basque Country
- [x] Subscription services (B2B and B2C)

### 6.2 Map Requirements Per Scenario
- [x] Create compliance matrix for each scenario
- [x] Document invoice requirements per scenario
- [x] Document VAT treatment per scenario
- [x] Document reporting requirements per scenario

---

## Phase 7: Implementation Planning

### 7.1 Technical Architecture
- [ ] Define invoice data model
- [ ] Plan TicketBAI integration (if applicable)
- [ ] Plan VAT calculation logic
- [ ] Plan reporting/submission workflows

### 7.2 Process Design
- [ ] Design invoice generation workflow
- [ ] Design VAT determination workflow
- [ ] Design record retention workflow
- [ ] Design audit/compliance reporting

### 7.3 Integration Points
- [ ] Identify required external integrations
- [ ] Plan VIES validation integration
- [ ] Plan tax authority submission integration

---

## Phase 8: Validation & Review

### 8.1 Source Verification
- [ ] Verify all information against official sources
- [ ] Cross-reference with professional publications
- [ ] Flag items requiring professional advice

### 8.2 Compliance Checklists
- [ ] Create pre-launch compliance checklist
- [ ] Create ongoing compliance checklist
- [ ] Create audit preparation checklist

### 8.3 Documentation Review
- [ ] Review all docs for accuracy
- [ ] Ensure consistent formatting
- [ ] Update all "Last Updated" dates
- [ ] Add missing source citations

---

## Quick Reference: Priority Tasks

Start with these high-priority items:

1. [x] **Determine TicketBAI applicability** - Does it apply to non-established EU sellers? **ANSWER: Generally NO**
2. [x] **Research VAT registration triggers** - When must you register in Basque Country? **ANSWER: Use OSS instead**
3. [x] **Document B2B reverse charge rules** - Most common scenario for EU B2B **DONE**
4. [x] **Research OSS applicability** - Can you use OSS instead of local registration? **ANSWER: YES**
5. [x] **Classify your offerings** - Products, services, digital, subscriptions **DONE**

---

## Key Findings Summary

### TicketBAI
- **Does NOT apply** to foreign EU sellers without fiscal residence in Basque Country
- Only applies to businesses fiscally resident in Basque provinces
- Foreign sellers using reverse charge or OSS are exempt

### VAT Registration
- **OSS is recommended** for B2C sales - no Spanish registration needed
- **Reverse charge** for B2B - no Spanish registration needed
- Only register in Spain if you have a permanent establishment

### VAT Rates
- Same as rest of Spain: 21% (general), 10% (reduced), 4% (super-reduced)
- Most digital services: 21%
- No Basque-specific rates

### Cross-Border Treatment
- **B2B**: Reverse charge - invoice without VAT
- **B2C**: Charge Spanish VAT (21%), file via OSS
- **Digital services**: Always customer location VAT

---

## Key Questions & Answers

### Tax Code Questions

| Question | Answer | Document |
|----------|--------|----------|
| What tax ID is required for foreign EU sellers? | Generally none needed if using OSS/reverse charge. If registering: NIF-N for foreign entities | `docs/tax-codes/nif-cif-requirements.md` |
| When must a foreign seller register for VAT in Basque Country? | Only if establishing permanent establishment or choosing direct registration over OSS | `docs/tax-codes/nif-cif-requirements.md` |
| How do NIF/CIF requirements apply to non-Spanish EU companies? | Not required for OSS users; NIF-N available if direct registration chosen | `docs/tax-codes/nif-cif-requirements.md` |

### VAT Questions

| Question | Answer | Document |
|----------|--------|----------|
| What are the current VAT rates in Basque Country? | 21% (general), 10% (reduced), 4% (super-reduced) - same as rest of Spain | `docs/vat-rules/vat-rates-basque.md` |
| How does reverse charge apply to B2B services? | Seller invoices without VAT; buyer self-assesses Spanish VAT; requires VIES validation | `docs/vat-rules/reverse-charge.md` |
| When does OSS apply vs local registration? | OSS recommended for B2C above €10k threshold; local registration only if PE or specific needs | `docs/vat-rules/oss-ioss.md` |
| How are subscriptions treated for VAT purposes? | Tax point at each billing; digital subs = 21%; classification depends on what's provided | `docs/services-vs-products/subscriptions.md` |
| What rate applies to SaaS/digital services? | 21% (general rate) for B2C; reverse charge for B2B | `docs/services-vs-products/digital-services.md` |

### TicketBAI Questions

| Question | Answer | Document |
|----------|--------|----------|
| Does TicketBAI apply to non-established sellers? | **NO** - only applies to businesses with fiscal residence in Basque Country | `docs/ticketbai/overview.md` |
| What are the technical requirements (XML, QR, signatures)? | Not applicable to foreign sellers; documented for reference in overview | `docs/ticketbai/overview.md` |
| What are implementation timelines and deadlines? | All provinces mandatory since Jan 2024; not relevant for foreign sellers | `docs/ticketbai/overview.md` |

### Record Keeping Questions

| Question | Answer | Document |
|----------|--------|----------|
| What is the mandatory retention period? | **10 years** for OSS transactions | `docs/record-keeping/retention-periods.md` |
| What format must records be kept in? | Electronic acceptable; must ensure authenticity, integrity, legibility | `docs/record-keeping/retention-periods.md` |
| What audit trail is required? | VIES validations, invoices, customer location evidence (2 pieces for B2C) | `docs/record-keeping/retention-periods.md` |

### Cross-Border Questions

| Question | Answer | Document |
|----------|--------|----------|
| How to handle B2B sales to Basque Country? | Reverse charge: verify VIES, invoice €0 VAT, add notation, file EC Sales List | `docs/eu-cross-border/b2b-transactions.md` |
| How to handle B2C sales to Basque Country? | Charge 21% Spanish VAT, collect location evidence, file OSS quarterly | `docs/eu-cross-border/b2c-transactions.md` |
| What is the distance selling threshold? | €10,000 EU-wide (all countries combined); above = must charge destination VAT | `docs/eu-cross-border/b2c-transactions.md` |
| Place of supply for digital services? | Always customer location for B2C; buyer location for B2B (reverse charge) | `docs/eu-cross-border/place-of-supply.md` |

### Classification Questions

| Question | Answer | Document |
|----------|--------|----------|
| How to classify SaaS? | Electronically supplied service (digital); 21% for B2C, reverse charge for B2B | `docs/services-vs-products/digital-services.md` |
| How to classify subscription boxes (physical)? | Goods; VAT rate depends on contents (4-21%); destination country rules | `docs/services-vs-products/subscriptions.md` |
| What about mixed digital + physical bundles? | Determine principal element; if inseparable, treat as single supply | `docs/services-vs-products/classification-guide.md` |

---

## Progress Summary

| Phase | Status | Completion |
|-------|--------|------------|
| Phase 1: Foundation | Complete | 90% |
| Phase 2: Cross-Border | Complete | 85% |
| Phase 3: Classification | Complete | 90% |
| Phase 4: TicketBAI | Mostly Complete | 70% |
| Phase 5: Record Keeping | In Progress | 50% |
| Phase 6: Scenario Mapping | Complete | 100% |
| Phase 7: Implementation | Not Started | 0% |
| Phase 8: Validation | Not Started | 0% |

---

## Notes

- Mark tasks `[x]` when completed
- Add new tasks as discovered during research
- Reference CLAUDE.md for project structure and guidelines
- Consult official sources listed in CLAUDE.md

---

*Last Updated: 2026-01-19*
