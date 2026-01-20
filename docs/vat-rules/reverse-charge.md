# VAT Reverse Charge Mechanism

> **Status**: Researched
> **Last Updated**: 2026-01-19

## Overview

The **reverse charge mechanism** shifts VAT accounting responsibility from the seller to the buyer. Instead of the seller charging VAT, the buyer self-assesses and accounts for VAT on their own return.

## When Reverse Charge Applies

### Intra-EU B2B Services

Per EU VAT Directive Article 196:

| Condition | Requirement |
|-----------|-------------|
| Seller | EU business, not established in Spain |
| Buyer | Spanish/Basque VAT-registered business |
| Supply | Services subject to B2B place of supply rule |
| Result | Buyer accounts for Spanish VAT |

### Intra-EU B2B Goods

| Condition | Requirement |
|-----------|-------------|
| Seller | EU business in another Member State |
| Buyer | Spanish/Basque VAT-registered business |
| Supply | Goods transported to Spain |
| Result | Buyer accounts for acquisition VAT |

### Spain's Extended Reverse Charge (Article 194)

Spain has implemented an **extended reverse charge** for supplies by non-established businesses:

> "Where a non-established supplier sells goods to a taxable person, domestic reverse charge applies. It is not relevant if the supplier is registered or not."

This means even domestic goods sales by non-established sellers trigger reverse charge in Spain.

## How It Works

### For the Seller (You)

```
1. Verify buyer's VAT number via VIES
2. Issue invoice WITHOUT VAT
3. Include reverse charge notation
4. Report in EC Sales List (if applicable)
```

### For the Buyer (Spanish Business)

```
1. Receive invoice without VAT
2. Calculate VAT at Spanish rate (21%, 10%, or 4%)
3. Report as both:
   - Output VAT (Box X)
   - Input VAT (Box Y) - if entitled to recovery
4. Net effect: Usually €0 (neutral)
```

## Invoice Requirements

### Mandatory Elements

| Element | Requirement |
|---------|-------------|
| Seller details | Name, address, VAT number |
| Buyer details | Name, address, **VAT number (essential)** |
| Invoice date | When issued |
| Invoice number | Unique sequential number |
| Description | Clear description of goods/services |
| Quantity/Amount | Net value excluding VAT |
| VAT rate | State 0% or "N/A" |
| VAT amount | €0.00 |
| **Reverse charge notation** | **REQUIRED** |

### Reverse Charge Notation

Must include one of:
- "Reverse charge - Article 196 of Directive 2006/112/EC"
- "Reverse charge - Article 194 of Directive 2006/112/EC"
- "VAT reverse charge applies"
- Spanish: "Inversión del sujeto pasivo"

### Sample Invoice Text

```
INVOICE #2026-001

From: [Your Company]
      [Address]
      VAT: [Your EU VAT Number]

To:   [Spanish Company]
      [Address]
      VAT: ES12345678A

Date: 2026-01-19

Description                    Amount
-----------------------------------------
SaaS License (Annual)         €10,000.00
Consulting Services           €5,000.00
-----------------------------------------
Subtotal                      €15,000.00
VAT (0% - Reverse Charge)     €0.00
-----------------------------------------
TOTAL DUE                     €15,000.00

Reverse charge - Article 196 of Directive 2006/112/EC
VAT to be accounted for by the recipient.
```

## VIES Validation

### Why Validate?

- Confirms buyer is VAT-registered
- Essential for zero-rating the supply
- Protects you from liability if buyer's number is invalid

### How to Validate

1. **VIES Portal**: https://ec.europa.eu/taxation_customs/vies/
2. Enter buyer's VAT number (including country code)
3. Save validation result and date
4. Re-validate periodically for ongoing relationships

### If Validation Fails

| Situation | Action |
|-----------|--------|
| Number not found | Do NOT zero-rate; charge VAT |
| Number invalid format | Request correct number from buyer |
| Customer refuses to provide | Treat as B2C; charge destination VAT |

## Reporting Requirements

### EC Sales List (ESL / Model 349 in Spain)

If you're registered in Spain and make intra-EU supplies:

| Threshold | Filing Frequency |
|-----------|------------------|
| < €50,000/quarter | Quarterly |
| ≥ €50,000/quarter | Monthly |

**For OSS users**: ESL not required for OSS-covered sales.

### What to Report

- Buyer's VAT number
- Total value of supplies per customer
- Type indicator (goods vs services)

## Reverse Charge and Basque Country

### No Special Treatment

Reverse charge works identically for sales to:
- Buyers in Álava
- Buyers in Bizkaia
- Buyers in Gipuzkoa
- Buyers in rest of Spain

### TicketBAI Not Triggered

When using reverse charge:
- **Seller does not need TicketBAI** (not fiscally resident)
- **Buyer may need TicketBAI** (for their own records if Basque resident)
- Your invoice requirements remain standard EU requirements

## Common Scenarios

### Scenario 1: SaaS to Spanish Business

```
You: German SaaS company
Customer: Business in Bilbao (Bizkaia)

→ B2B service
→ Place of supply: Spain (buyer location)
→ Reverse charge applies
→ Invoice: €1,000 + €0 VAT
→ Customer self-assesses: €1,000 × 21% = €210
```

### Scenario 2: Consulting to Spanish Business

```
You: French consulting firm
Customer: Company in San Sebastián (Gipuzkoa)

→ B2B service
→ Place of supply: Spain
→ Reverse charge applies
→ Invoice without VAT
→ Customer accounts for Spanish VAT
```

### Scenario 3: Physical Goods to Spanish Business

```
You: Dutch wholesaler
Customer: Retailer in Vitoria-Gasteiz (Álava)

→ B2B goods (intra-EU acquisition)
→ Zero-rated dispatch from NL
→ Customer accounts for acquisition VAT in Spain
→ Report on EC Sales List
```

## When Reverse Charge Does NOT Apply

| Situation | Treatment |
|-----------|-----------|
| B2C sales | Charge destination country VAT (use OSS) |
| Buyer not VAT-registered | Charge VAT (treat as B2C) |
| Services with specific place of supply | Depends on specific rule |
| You're established in Spain | Normal domestic VAT rules |

## Documentation Checklist

For every reverse charge transaction, maintain:

- [ ] VIES validation screenshot/printout with date
- [ ] Copy of invoice with reverse charge notation
- [ ] Contract or order confirmation
- [ ] Proof of service delivery
- [ ] Payment records
- [ ] EC Sales List filing (if applicable)

## Key Takeaways

1. **Reverse charge = no VAT on your invoice** for B2B intra-EU
2. **VIES validation is essential** - always verify customer VAT numbers
3. **Correct notation required** - state reverse charge and legal basis
4. **Same rules for Basque Country** - no provincial variations
5. **Buyer handles VAT** - they self-assess at their local rate
6. **Keep records** - document validation and all transaction details

## Sources

- [Marosa - Reverse Charge on VAT](https://marosavat.com/vat-news/vat-reverse-charge)
- [Marosa - Reverse Charge in Spain](https://marosavat.com/manual/vat/spain/reverse-charge/)
- [Avalara - EU VAT Reverse Charge](https://www.avalara.com/vatlive/en/eu-vat-rules/eu-vat-returns/reverse-charge-on-eu-vat.html)
- [Commenda - Reverse Charge Mechanism Guide](https://www.commenda.io/blog/reverse-charge-mechanism-explained-for-non-eu-businesses)
- [Marosa - Intra-Community VAT](https://marosavat.com/vat-news/intra-community-vat-what-it-is-how-apply)

---

*See also: [B2B Transactions](../eu-cross-border/b2b-transactions.md) | [VAT Rates](vat-rates-basque.md) | [OSS/IOSS](oss-ioss.md)*
