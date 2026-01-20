# Digital Services (Electronically Supplied Services)

> **Status**: Researched
> **Last Updated**: 2026-01-19

## Overview

**Electronically Supplied Services (ESS)** have special VAT rules in the EU. For B2C sales, they are **always taxed where the customer is located**, regardless of where the seller is established.

## Definition

Per EU VAT Implementing Regulation 282/2011, electronically supplied services are:

> Services delivered over the internet or electronic network, where the nature of the service renders its supply essentially automated, involving minimal human intervention, and impossible without information technology.

## What Qualifies as Digital Services

### Included (ESS)

| Category | Examples |
|----------|----------|
| Software | Downloads, SaaS, apps, plugins |
| Content | E-books, music, videos, images |
| Gaming | Online games, in-app purchases |
| Cloud | Storage, hosting, computing |
| Streaming | Music streaming, video streaming |
| Education | Automated online courses, e-learning platforms |
| Information | News subscriptions, data feeds |
| Advertising | Online ad placements |

### NOT Included (Not ESS)

| Category | Why Not ESS |
|----------|-------------|
| Physical goods ordered online | Goods, not services |
| Hotel bookings made online | Service performed offline |
| Professional advice via email | Human intervention required |
| Live online tutoring | Significant human intervention |
| Video conference consultations | Human-driven service |
| Goods with minor digital element | Primarily physical |

## EU Annex I - Definitive List

The EU provides a definitive list of what constitutes ESS:

1. Website supply, web-hosting, remote maintenance of programs and equipment
2. Supply of software and updates
3. Supply of images, text, and information
4. Access to databases
5. Downloading of music, films, games
6. Subscription to online newspapers/journals
7. Supply of space for games online
8. Supply of advertising space on a website
9. Distance teaching when automated with minimal human intervention

## VAT Treatment Summary

### B2B Digital Services

| Element | Treatment |
|---------|-----------|
| Place of supply | Where customer is established |
| VAT mechanism | **Reverse charge** |
| Seller charges VAT | No |
| Rate applied | Customer's local rate (self-assessed) |

### B2C Digital Services

| Element | Treatment |
|---------|-----------|
| Place of supply | Where customer is located |
| VAT mechanism | Seller charges destination VAT |
| Rate applied | Customer's country rate |
| Filing | Via **OSS** (recommended) |

**Key Point**: B2C digital services are ALWAYS taxed at customer location, even below the €10,000 threshold (unlike physical goods).

## Customer Location Rules (B2C)

### Evidence Requirements

For B2C digital services, you need **two pieces of non-contradictory evidence** to determine customer location:

| Evidence Type | Description |
|---------------|-------------|
| Billing address | Address provided by customer |
| IP address | Geolocation at time of purchase |
| Bank details | Country of payment method |
| Country code of SIM | For mobile purchases |
| Fixed landline location | Country code |

### Evidence Hierarchy

If evidence conflicts:
1. Use the majority evidence
2. If tied, generally use billing address
3. Document your reasoning

## Selling Digital Services to Basque Country

### B2B to Basque Business

```
You: EU SaaS Company
Customer: Business in Bilbao (Bizkaia)

1. Verify customer's VAT number (VIES)
2. Classify as B2B (business customer)
3. Invoice WITHOUT VAT
4. Add: "Reverse charge - Art 196 VAT Directive"
5. Customer self-assesses Spanish VAT (21%)
```

### B2C to Basque Consumer

```
You: EU SaaS Company
Customer: Consumer in San Sebastián (Gipuzkoa)

1. Determine customer location (two evidence pieces)
2. Location = Spain → Charge Spanish VAT (21%)
3. Invoice with VAT included
4. File via OSS in your home country
5. Pay VAT to your home tax authority
6. They distribute to Spain
```

## SaaS-Specific Guidance

### Classification

SaaS (Software as a Service) is classified as an **electronically supplied service** because:
- Delivered via internet
- Automated provisioning
- Minimal human intervention
- Cannot function without IT infrastructure

### VAT Treatment for SaaS

| Customer Type | Treatment |
|---------------|-----------|
| Business (B2B) | Reverse charge |
| Consumer (B2C) | Charge destination VAT |
| Mixed use | Determine primary purpose |

### Subscription Considerations

| Aspect | Treatment |
|--------|-----------|
| Monthly billing | Each month is a taxable supply |
| Annual prepayment | Tax point at payment |
| Free trial | No VAT until paid |
| Upgrades | Additional supply at time of upgrade |
| Cancellation/refund | Adjust VAT accordingly |

## Other Common Digital Services

### Cloud Storage/Hosting

- Classification: ESS
- VAT: 21% to Spanish/Basque consumers
- B2B: Reverse charge

### Streaming Services

- Classification: ESS
- VAT: 21% to Spanish/Basque consumers
- Music, video, gaming all treated same

### E-books

- Classification: ESS
- VAT: Generally 21% in Spain
- *Note*: Physical books are 4%, but digital typically 21%

### Online Advertising

- Classification: ESS
- VAT: Per normal ESS rules
- B2B: Reverse charge common

### App Store Purchases

- Classification: ESS
- Note: Platform (Apple/Google) may be the seller of record
- If you sell direct: standard ESS rules apply

## Record Keeping for Digital Services

### Mandatory Records (10 Years)

| Record | Purpose |
|--------|---------|
| Customer location evidence | Proves correct VAT applied |
| Invoice copies | Transaction record |
| VAT rate applied | Compliance verification |
| Payment records | Confirms transaction |
| Refund/adjustment records | Complete audit trail |

### OSS-Specific Records

- Quarterly returns filed
- VAT by Member State breakdown
- Total reportable sales

## Common Mistakes

| Mistake | Correct Approach |
|---------|------------------|
| Not collecting location evidence | Get 2+ pieces for every B2C sale |
| Treating all online sales as ESS | Only truly automated services qualify |
| Using seller country rate for B2C | Must use customer location rate |
| Not validating B2B customer VAT | Always verify via VIES |
| Mixing OSS and local registration | Keep separate or choose one |

## Decision Tree: Digital Services

```
Is the service delivered electronically with minimal human intervention?
│
├─ NO → Not ESS, apply standard service rules
│
└─ YES → Electronically Supplied Service
    │
    └─ Who is the customer?
        │
        ├─ BUSINESS (B2B)
        │   └─ Verify VAT number (VIES)
        │   └─ Invoice without VAT
        │   └─ Reverse charge applies
        │
        └─ CONSUMER (B2C)
            └─ Determine customer location
            └─ Charge destination country VAT
            └─ File via OSS (recommended)
```

## Key Takeaways

1. **ESS = automated internet delivery** - minimal human intervention required
2. **B2C always taxed at customer location** - no exception for digital services
3. **B2B uses reverse charge** - same as other services
4. **21% rate** for most digital services in Spain
5. **Two evidence pieces** required for customer location (B2C)
6. **OSS is the simple solution** for B2C compliance
7. **10-year record retention** for all transactions

## Sources

- [EU VAT Implementing Regulation 282/2011](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32011R0282)
- [European Commission - OSS Portal](https://vat-one-stop-shop.ec.europa.eu/index_en)
- [1StopVAT - VAT Compliance for SaaS](https://1stopvat.com/articles/vat-compliance-saas-digital-services-eu)
- [vatcalc - VAT on B2B Digital Services](https://www.vatcalc.com/global/vat-on-cross-border-b2b-digital-services/)

---

*See also: [Subscriptions](subscriptions.md) | [Classification Guide](classification-guide.md) | [OSS/IOSS](../vat-rules/oss-ioss.md)*
