# TicketBAI System Overview

> **Status**: Researched
> **Last Updated**: 2026-01-19

## What is TicketBAI?

TicketBAI is a mandatory electronic invoicing and **fiscal control system** implemented by the three Basque provincial tax authorities (Diputaciones Forales). It requires businesses to:

1. Generate invoices using **certified software**
2. Include a **digitally signed identification code** (TBAI)
3. Generate a **QR code** for each invoice
4. Report invoice data to tax authorities in **real-time**

## Provincial Implementations

| Province | System Name | Tax Authority | Status |
|----------|-------------|---------------|--------|
| Álava/Araba | TicketBAI | Diputación Foral de Álava | **Mandatory** |
| Bizkaia | BATUZ | Diputación Foral de Bizkaia | **Mandatory (Jan 2024)** |
| Gipuzkoa | TicketBAI | Diputación Foral de Gipuzkoa | **Mandatory** |

## Who Must Comply?

### Subject to TicketBAI

TicketBAI applies to all natural and legal persons who:
- Conduct **economic activities** within Basque Tax Administration jurisdiction
- Have **fiscal residence** (domicilio fiscal) in the Basque Country
- Are subject to:
  - Personal Income Tax (IRPF)
  - Corporate Income Tax (Impuesto sobre Sociedades)
  - Non-Resident Income Tax **with permanent establishment**

### NOT Subject to TicketBAI (Generally)

- Foreign companies **without** fiscal residence in Basque Country
- Companies selling **into** Basque Country from other EU countries
- Non-resident sellers using **reverse charge** or **OSS**

## Applicability to Foreign EU Sellers

### Key Finding

**TicketBAI generally does NOT apply to foreign EU sellers** making cross-border sales into the Basque Country, because:

1. **Fiscal residence required**: TicketBAI applies to businesses with fiscal residence in Basque Country
2. **B2B reverse charge**: Foreign sellers don't charge VAT; Spanish buyer accounts for it
3. **B2C via OSS**: Foreign sellers file in their home country, not Spain
4. **No permanent establishment**: Without PE in Basque Country, no TicketBAI obligation

### When TicketBAI WOULD Apply

TicketBAI would apply to a foreign company if it:
- Establishes a **permanent establishment** in Basque Country
- Has its **fiscal headquarters** in Basque Country
- Becomes a Basque **tax resident** for corporate purposes

### Decision Tree

```
Is your company fiscally resident in Basque Country?
│
├─ NO → TicketBAI does NOT apply
│   └─ Use reverse charge (B2B) or OSS (B2C)
│
└─ YES → TicketBAI APPLIES
    └─ Must use certified software
    └─ Must generate TBAI codes
    └─ Must submit to provincial treasury
```

## Technical Requirements

### 1. TBAI Identifier (39 characters)

Each invoice must contain a unique TBAI identifier composed of:
- Issuer's NIF
- Invoice date
- Invoice number/series
- Chained hash from previous invoice

### 2. Digital Signature

- XML files must be **electronically signed**
- Requires recognized digital certificate
- Ensures authenticity and integrity

### 3. QR Code

Every invoice must include a QR code containing:
- TBAI identifier
- Verification URL
- Key invoice data

### 4. Certified Software

- Must use software registered in **Official TicketBAI Approved Software Register**
- Software must be issued by a trusted, registered developer
- Generates compliant XML, signatures, and QR codes

### 5. Real-Time Submission

- XML file submitted **automatically** to provincial treasury
- Submission is real-time or near-real-time
- Each province has its own submission endpoint

## Implementation Timeline

| Province | Effective Date | Notes |
|----------|----------------|-------|
| Gipuzkoa | 2022 | Phased rollout complete |
| Álava | 2022 | Phased rollout complete |
| Bizkaia | January 1, 2024 | Now mandatory for all |

**All three provinces now have full TicketBAI/BATUZ requirements in effect.**

## Comparison: TicketBAI vs VeriFactu

| Aspect | TicketBAI (Basque) | VeriFactu (Rest of Spain) |
|--------|-------------------|---------------------------|
| Status | Mandatory now | Coming (phased 2025-2026) |
| Scope | Basque Country only | Rest of Spain |
| Real-time | Yes | Yes |
| QR Code | Required | Required |
| Certified software | Required | Required |

## Penalties for Non-Compliance

| Violation | Penalty Range |
|-----------|---------------|
| Not using certified software | [Province-specific] |
| Missing TBAI identifier | [Province-specific] |
| Late submission | [Province-specific] |
| Falsified records | Severe penalties + potential criminal |

*Note: Specific penalty amounts vary by province. Consult official sources.*

## Official Resources

### Provincial Portals
- **Bizkaia BATUZ**: https://www.batuz.eus
- **Álava TicketBAI**: https://ticketbai.araba.eus
- **Gipuzkoa TicketBAI**: https://www.gipuzkoa.eus/ticketbai

### Software Registry
- Each province maintains a list of certified software
- Check provincial websites for approved vendors

## Key Takeaways for Foreign EU Sellers

1. **TicketBAI likely does not apply** to cross-border sales from other EU countries
2. **No action needed** if using reverse charge (B2B) or OSS (B2C)
3. **Consult a specialist** if considering establishing presence in Basque Country
4. **Monitor VeriFactu** for rest-of-Spain obligations (separate system)

## Sources

- [Stripe - TicketBAI in the Basque Country](https://stripe.com/resources/more/ticket-bai-basque-country)
- [Fiskaly - TicketBAI & VeriFactu Legal Obligations](https://www.fiskaly.com/blog/legal-obligations-for-ticketbai-and-verifactu)
- [EDICOM - Ticket BAI System Overview](https://edicomgroup.com/blog/ticket-bai-spain-new-invoicing-and-tax-compliance-system)
- [Fiscal Solutions - What is TicketBAI](https://www.fiscal-requirements.com/news/1169)
- [i3S - Final Stretch for TicketBAI](https://www.i3s.es/en/blog/final-stretch-for-basque-companies-with-the-implementation-of-ticketbai/)

---

*See also: [Technical Specifications](technical-specs.md) | [Province-Specific Requirements](alava-requirements.md)*
