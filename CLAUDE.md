# Basque Country E-Invoicing System - Project Overview

> **Session State Saved**: 2026-01-19
> **To Resume**: Review "Session Recovery" section below and TODO.md

---

## Session Recovery

### Last Session Summary (2026-01-19)

**Completed research and documentation for Phases 1-6 of the project.**

### Key Findings Discovered

1. **TicketBAI does NOT apply** to foreign EU sellers without fiscal residence in Basque Country
2. **OSS (One-Stop Shop) is recommended** for B2C sales - no Spanish VAT registration needed
3. **Reverse charge** applies for B2B - invoice without VAT, customer self-assesses
4. **VAT rates are identical** to rest of Spain: 21% (general), 10% (reduced), 4% (super-reduced)
5. **10-year record retention** required for OSS transactions
6. **No Basque-specific VAT rates** - harmonized across Spain

### Documents Completed

| Document | Status |
|----------|--------|
| `docs/QUICK-REFERENCE.md` | Complete - one-page summary |
| `docs/legal-compliance/concierto-economico.md` | Complete |
| `docs/tax-codes/nif-cif-requirements.md` | Complete |
| `docs/vat-rules/vat-rates-basque.md` | Complete |
| `docs/vat-rules/oss-ioss.md` | Complete |
| `docs/vat-rules/reverse-charge.md` | Complete |
| `docs/eu-cross-border/place-of-supply.md` | Complete |
| `docs/eu-cross-border/b2b-transactions.md` | Complete |
| `docs/eu-cross-border/b2c-transactions.md` | Complete |
| `docs/ticketbai/overview.md` | Complete |
| `docs/services-vs-products/classification-guide.md` | Complete |
| `docs/services-vs-products/digital-services.md` | Complete |
| `docs/services-vs-products/subscriptions.md` | Complete |
| `docs/record-keeping/retention-periods.md` | Complete |

### Documents Still Needed

| Document | Priority |
|----------|----------|
| `docs/tax-codes/basque-tax-codes.md` | Low |
| `docs/tax-codes/eu-vat-numbers.md` | Low |
| `docs/vat-rules/intra-eu-vat.md` | Medium |
| `docs/eu-cross-border/thresholds.md` | Low |
| `docs/services-vs-products/mixed-supplies.md` | Low |
| `docs/ticketbai/technical-specs.md` | Low (not needed for foreign sellers) |
| `docs/ticketbai/alava-requirements.md` | Low (not needed for foreign sellers) |
| `docs/ticketbai/bizkaia-requirements.md` | Low (not needed for foreign sellers) |
| `docs/ticketbai/gipuzkoa-requirements.md` | Low (not needed for foreign sellers) |
| `docs/record-keeping/digital-storage.md` | Low |
| `docs/record-keeping/audit-trails.md` | Medium |
| `docs/legal-compliance/penalties.md` | Medium |
| `docs/legal-compliance/registration-requirements.md` | Low |
| `docs/legal-compliance/eu-directives.md` | Low |

### Next Steps to Resume

1. Review `TODO.md` for detailed task status
2. Start with `docs/QUICK-REFERENCE.md` for overview
3. Phase 7 (Implementation Planning) is next if continuing
4. Phase 8 (Validation & Review) follows

### Progress by Phase

| Phase | Status | Completion |
|-------|--------|------------|
| Phase 1: Foundation Research | Complete | 90% |
| Phase 2: Cross-Border EU Rules | Complete | 85% |
| Phase 3: Classification | Complete | 90% |
| Phase 4: TicketBAI | Complete | 70% |
| Phase 5: Record Keeping | Complete | 50% |
| Phase 6: Scenario Mapping | Complete | 100% |
| Phase 7: Implementation | Not Started | 0% |
| Phase 8: Validation | Not Started | 0% |

---

## Project Purpose

Research and implementation guide for an e-invoicing system compliant with Basque Country (Spain) tax regulations, specifically for **cross-border EU sales** into the Basque Autonomous Community (Euskadi).

## Key Challenge Areas

### 1. TicketBAI Compliance
The Basque Country has implemented **TicketBAI**, a mandatory e-invoicing and tax reporting system. Each of the three Basque provinces (Diputaciones Forales) has its own implementation:
- **Álava** - Diputación Foral de Álava
- **Bizkaia** - Diputación Foral de Bizkaia (called BATUZ)
- **Gipuzkoa** - Diputación Foral de Gipuzkoa

**KEY FINDING**: TicketBAI does NOT apply to foreign EU sellers without fiscal residence.

### 2. Cross-Border EU VAT Rules
Sales from another EU country to Basque Country involve:
- **B2B transactions**: Reverse charge mechanism applies - invoice without VAT
- **B2C transactions**: Use OSS (One-Stop Shop) - charge Spanish VAT (21%)
- **OSS (One-Stop Shop)**: Recommended approach for B2C compliance

### 3. Product vs Service vs Subscription Classification
Different VAT treatment based on:
- Physical goods (destination country VAT for B2C)
- Services (reverse charge for B2B, OSS for B2C)
- Digital services (always customer location VAT)
- Subscription services (tax point at each billing)

### 4. Foral Tax System
The Basque Country operates under a unique **Concierto Económico** (Economic Agreement) but:
- VAT rates are harmonized (same as rest of Spain)
- Foreign sellers typically don't interact with Basque authorities
- Use AEAT (national) or OSS instead

---

## Directory Structure

```
basque/
├── CLAUDE.md                    # This file - project overview and state
├── TODO.md                      # Task tracking and progress
├── docs/
│   ├── QUICK-REFERENCE.md       # One-page summary (START HERE)
│   │
│   ├── tax-codes/
│   │   └── nif-cif-requirements.md  # [COMPLETE] Tax ID requirements
│   │
│   ├── vat-rules/
│   │   ├── vat-rates-basque.md      # [COMPLETE] VAT rates guide
│   │   ├── reverse-charge.md        # [COMPLETE] B2B reverse charge
│   │   └── oss-ioss.md              # [COMPLETE] OSS compliance
│   │
│   ├── ticketbai/
│   │   └── overview.md              # [COMPLETE] TicketBAI (not applicable)
│   │
│   ├── record-keeping/
│   │   └── retention-periods.md     # [COMPLETE] 10-year retention
│   │
│   ├── legal-compliance/
│   │   └── concierto-economico.md   # [COMPLETE] Basque tax system
│   │
│   ├── eu-cross-border/
│   │   ├── place-of-supply.md       # [COMPLETE] Place of supply rules
│   │   ├── b2b-transactions.md      # [COMPLETE] B2B guide
│   │   └── b2c-transactions.md      # [COMPLETE] B2C guide
│   │
│   └── services-vs-products/
│       ├── classification-guide.md  # [COMPLETE] Classification
│       ├── digital-services.md      # [COMPLETE] Digital/SaaS rules
│       └── subscriptions.md         # [COMPLETE] Subscription VAT
```

---

## Quick Reference: Core Answers

### For B2B Sales (Business Customers)
- Verify VAT number via VIES
- Invoice WITHOUT VAT
- Add "Reverse charge - Article 196 VAT Directive"
- No Spanish registration needed
- TicketBAI: NOT APPLICABLE

### For B2C Sales (Consumers)
- Charge Spanish VAT (usually 21%)
- File via OSS in your home country quarterly
- No Spanish registration needed
- TicketBAI: NOT APPLICABLE

### VAT Rates
- 21% - Most goods/services, digital, SaaS
- 10% - Food, hotels, transport
- 4% - Basic food, books, medicines

---

## Official Sources

### Key URLs
- **VIES Validation**: https://ec.europa.eu/taxation_customs/vies/
- **OSS Portal**: https://vat-one-stop-shop.ec.europa.eu/
- **EU VAT Rates**: https://ec.europa.eu/taxation_customs/vat-rates_en
- **Spanish Tax Agency**: https://sede.agenciatributaria.gob.es

### Basque Tax Authorities (for reference only)
- **Álava**: https://web.araba.eus/es/hacienda
- **Bizkaia**: https://www.bizkaia.eus/ogasuna
- **Gipuzkoa**: https://www.gipuzkoa.eus/es/web/ogasuna

### TicketBAI Official (for reference only)
- https://www.batuz.eus (Bizkaia)
- https://ticketbai.araba.eus (Álava)
- https://www.gipuzkoa.eus/ticketbai (Gipuzkoa)

---

## Best Practices

### Documentation Standards
- Each doc file includes: Purpose, Key Points, Sources, Last Updated date
- Status marked as "Researched" when complete
- Sources linked at bottom of each document

### Disclaimers

> **Important**: This documentation is for research and planning purposes only.
> Tax and legal compliance matters should be verified with qualified professionals
> (tax advisors, legal counsel) before implementation.
>
> Regulations change frequently. Always verify current requirements with official sources.

---

*Last Updated: 2026-01-19*
