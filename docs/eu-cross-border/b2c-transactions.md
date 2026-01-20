# B2C Cross-Border Transactions: EU to Basque Country

> **Status**: Researched
> **Last Updated**: 2026-01-19

## Overview

Business-to-consumer (B2C) transactions from other EU countries to Basque Country consumers require charging **Spanish VAT** (destination country VAT). The **One-Stop Shop (OSS)** simplifies compliance.

## Key Principle

> **For B2C sales to Basque Country, Spanish VAT rates apply.**
>
> You must either register for OSS in your home country or register directly for VAT in Spain.

## The €10,000 Threshold

### Current Rules (Since July 2021)

| Situation | Treatment |
|-----------|-----------|
| Total EU cross-border B2C sales ≤ €10,000/year | May charge home country VAT |
| Total EU cross-border B2C sales > €10,000/year | Must charge destination country VAT |

**Important**: This threshold applies to your **total** cross-border B2C sales to **all EU countries** combined, not per country.

### Exception: Digital Services

For electronically supplied services (digital/SaaS), destination country VAT **always applies** for B2C, regardless of threshold. The €10,000 threshold only provides an option to charge home country VAT for goods and non-digital services.

## B2C Compliance Options

### Option 1: One-Stop Shop (OSS) - Recommended

| Aspect | Details |
|--------|---------|
| Registration | In your home EU country |
| Filing | Quarterly |
| Payment | To your home tax authority |
| Advantage | Single registration covers all EU |

### Option 2: Direct Registration in Spain

| Aspect | Details |
|--------|---------|
| Registration | With AEAT (Spanish tax authority) |
| Filing | Spanish VAT returns (quarterly) |
| Payment | To AEAT |
| Disadvantage | Additional compliance burden |

### Recommendation

**Use OSS** unless you have specific reasons to register directly in Spain (e.g., need to recover input VAT there, have local presence).

## VAT Rates for B2C to Basque Country

| Category | Rate |
|----------|------|
| **Most digital services** | 21% |
| **Most physical goods** | 21% |
| **Food products** | 10% or 4% |
| **Books (physical)** | 4% |
| **Transport/hospitality** | 10% |

*See [VAT Rates document](../vat-rules/vat-rates-basque.md) for complete list.*

## Customer Location Determination

### Why It Matters

You must prove the customer is in Spain/Basque Country to correctly apply Spanish VAT.

### Evidence Requirements

You need **two pieces of non-contradictory evidence**:

| Evidence Type | Examples |
|---------------|----------|
| Billing address | Address provided at checkout |
| IP address | Geolocation at purchase |
| Bank details | Country of payment method |
| Mobile country code | For mobile purchases |
| Delivery address | For physical goods |

### If Evidence Conflicts

1. Use the majority evidence
2. If 50/50, generally use billing address
3. Document your reasoning
4. Keep evidence for 10 years

## Process: Selling to Basque Country Consumer

### Digital Services/SaaS

```
1. Customer initiates purchase
   └─ Collect billing address
   └─ Log IP address

2. Determine location
   └─ Two evidence pieces → Spain
   └─ Apply Spanish VAT (21%)

3. Complete sale
   └─ Charge €100 + €21 VAT = €121
   └─ Issue invoice/receipt

4. End of quarter
   └─ File OSS return
   └─ Report Spanish sales
   └─ Pay VAT collected

5. Record keeping
   └─ Retain for 10 years
```

### Physical Goods

```
1. Customer places order
   └─ Delivery address in Basque Country
   └─ Billing address collected

2. Determine VAT treatment
   └─ Above €10,000 threshold? → Spanish VAT
   └─ Below threshold? → Option to charge home VAT

3. Apply correct rate
   └─ 21% for most goods
   └─ Check reduced/super-reduced categories

4. Ship goods
   └─ Include in delivery to Spain

5. Report
   └─ File via OSS quarterly
   └─ Or via local Spanish registration
```

## Invoicing for B2C

### Requirements

B2C invoices should include:

| Element | Required? |
|---------|-----------|
| Your business name/address | Yes |
| Your VAT number | Yes |
| Invoice number | Yes |
| Date | Yes |
| Description | Yes |
| Net amount | Yes |
| VAT rate | Yes |
| VAT amount | Yes |
| Gross total | Yes |
| Customer VAT number | No (it's B2C) |

### Simplified Invoice (Small Amounts)

Spain allows simplified invoices for transactions under €400:

| Element | Required? |
|---------|-----------|
| Your details | Yes |
| Date | Yes |
| Description | Yes |
| Total (VAT included) | Yes |
| VAT rate | Yes |

### Sample B2C Invoice

```
RECEIPT / INVOICE

[Your Company Name]
[Your Address]
VAT: [Your VAT Number]

Date: 2026-01-19
Invoice: INV-2026-00123

Customer: [Name if provided]
Location: Spain

Description                    Amount
---------------------------------------
Annual SaaS Subscription      €100.00
VAT (21% - Spain)              €21.00
---------------------------------------
TOTAL                         €121.00

VAT charged on supply of electronically
supplied services to Spain.
```

## OSS Filing Process

### Quarterly Returns

| Quarter | Period | Due Date |
|---------|--------|----------|
| Q1 | Jan-Mar | April 30 |
| Q2 | Apr-Jun | July 31 |
| Q3 | Jul-Sep | October 31 |
| Q4 | Oct-Dec | January 31 |

### What to Report

| Field | Description |
|-------|-------------|
| Member State | ES (Spain) |
| VAT rate | 21%, 10%, or 4% |
| Taxable amount | Net sales to Spain |
| VAT amount | VAT collected |

### Payment

- Pay total VAT due with return
- Payment to your home tax authority
- They distribute to Spain

## Special B2C Scenarios

### Scenario 1: SaaS to Basque Consumer

```
You: French SaaS company
Customer: Individual in Bilbao

→ Digital service (ESS)
→ Place of supply: Spain (customer location)
→ VAT rate: 21%
→ Charge: €50 + €10.50 = €60.50
→ Report: Q1 OSS return
```

### Scenario 2: E-commerce Goods to Basque Consumer

```
You: German online retailer
Customer: Consumer in San Sebastián
Order: Electronics, €200

→ Physical goods
→ Place of supply: Spain (destination)
→ VAT rate: 21%
→ Charge: €200 + €42 = €242
→ Ship to Spain
→ Report: OSS (or Spanish registration)
```

### Scenario 3: Subscription Box to Basque Consumer

```
You: Belgian subscription box company
Customer: Consumer in Vitoria-Gasteiz
Subscription: Food box, €30/month

→ Physical goods
→ Place of supply: Spain
→ VAT rate: 10% or 4% (depending on contents)
→ Charge: €30 + €3 = €33 (if 10%)
→ Monthly shipment to Spain
```

### Scenario 4: Online Course to Basque Consumer

```
You: Irish e-learning platform
Customer: Individual in Bizkaia
Product: Self-paced online course, €150

→ Digital service (automated, minimal human intervention)
→ Place of supply: Spain
→ VAT rate: 21%
→ Charge: €150 + €31.50 = €181.50
```

## Basque Country Specifics for B2C

### TicketBAI

**Does NOT apply to foreign B2C sellers** because:
- You're not fiscally resident in Basque Country
- You're filing via OSS (not local Basque returns)
- TicketBAI is for Basque-resident businesses

### VAT Rate Differences

**None** - Basque Country uses same VAT rates as rest of Spain.

### Consumer Rights

Spanish/EU consumer protection laws apply:
- 14-day withdrawal right (for distance sales)
- Clear pricing (including VAT)
- Language: Not required to be in Spanish, but recommended

## Record Keeping

### What to Keep (10 Years)

| Record | Purpose |
|--------|---------|
| Customer location evidence | Proves correct VAT applied |
| Invoices/receipts | Transaction record |
| Payment confirmations | Proof of sale |
| OSS returns | Filing compliance |
| Rate calculations | Audit trail |

### Format

- Electronic storage acceptable
- Must be accessible on request
- Must be readable throughout retention period

## Common Mistakes

| Mistake | Correct Approach |
|---------|------------------|
| Not collecting location evidence | Always get 2+ pieces |
| Using wrong VAT rate | Verify rate for each product type |
| Forgetting to file OSS | Quarterly filing mandatory |
| Not updating rates | Monitor rate changes |
| Mixing B2B and B2C | Apply different rules appropriately |

## Key Takeaways

1. **B2C to Basque Country = Spanish VAT** (21% for most items)
2. **OSS is the simplest option** for compliance
3. **Collect location evidence** for every B2C sale
4. **File quarterly** OSS returns
5. **TicketBAI doesn't apply** to foreign sellers
6. **No special Basque rates** - same as rest of Spain
7. **10-year record retention** required

## Sources

- [Your Europe - VAT One Stop Shop](https://europa.eu/youreurope/business/taxation/vat/one-stop-shop/index_en.htm)
- [European Commission - OSS Portal](https://vat-one-stop-shop.ec.europa.eu/index_en)
- [AEAT - OSS Information](https://sede.agenciatributaria.gob.es/Sede/en_gb/iva/iva-comercio-electronico/cuestiones-generales.html)
- [Marosa - EU VAT E-commerce Rules](https://marosavat.com/resources/vat-rules-for-e-commerce)

---

*See also: [OSS/IOSS](../vat-rules/oss-ioss.md) | [B2B Transactions](b2b-transactions.md) | [VAT Rates](../vat-rules/vat-rates-basque.md)*
