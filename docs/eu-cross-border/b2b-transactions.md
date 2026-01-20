# B2B Cross-Border Transactions: EU to Basque Country

> **Status**: Researched
> **Last Updated**: 2026-01-19

## Overview

Business-to-business (B2B) transactions from other EU countries to the Basque Country follow standard EU intra-community rules. The **reverse charge mechanism** is the primary VAT treatment.

## Key Principle

> **For B2B transactions, the Basque Country is treated identically to the rest of Spain.**
>
> There are no special Basque-specific B2B VAT rules. Standard EU intra-community provisions apply.

## Place of Supply Rules

### Services (General B2B Rule)

Per EU VAT Directive Article 44:

| Element | Rule |
|---------|------|
| Place of supply | Where the **customer** is established |
| Who accounts for VAT | Customer (via reverse charge) |
| Seller charges VAT | No |

**Result**: Services supplied to a Basque/Spanish business are taxed in Spain, with the customer accounting for Spanish VAT.

### Goods (Intra-EU Supplies)

| Element | Rule |
|---------|------|
| Place of supply | Where goods **arrive** |
| Seller treatment | Zero-rated dispatch |
| Buyer treatment | Acquisition VAT in Spain |

**Result**: Goods sent to Basque Country are zero-rated by the seller; buyer accounts for acquisition VAT.

## Step-by-Step: B2B Service Sale

### 1. Before the Sale

- [ ] Confirm customer is a business (not consumer)
- [ ] Obtain customer's VAT number
- [ ] Validate VAT number via VIES
- [ ] Document the validation (screenshot + date)

### 2. During the Sale

- [ ] Issue invoice **without VAT**
- [ ] Include reverse charge notation
- [ ] Include customer's validated VAT number
- [ ] Describe service clearly

### 3. After the Sale

- [ ] File EC Sales List if required
- [ ] Keep records for required retention period
- [ ] Update accounting systems

## Step-by-Step: B2B Goods Sale

### 1. Before the Sale

- [ ] Validate customer's VAT number (VIES)
- [ ] Confirm dispatch and delivery arrangements
- [ ] Document the validation

### 2. During the Sale

- [ ] Issue invoice **without VAT** (zero-rated)
- [ ] Include "Intra-community supply" or equivalent
- [ ] Include customer's validated VAT number

### 3. After Dispatch

- [ ] Obtain proof of transport/delivery
- [ ] File EC Sales List
- [ ] Keep all documentation

## Invoice Template: B2B Services

```
INVOICE

From: [Your Company Name]
      [Your Address]
      VAT: [Your VAT Number, e.g., DE123456789]

To:   [Spanish/Basque Company Name]
      [Their Address]
      VAT: ES[Their NIF, e.g., ESB12345678]

Invoice No: 2026-0001
Date: 2026-01-19
Due Date: 2026-02-19

Description                              Amount (EUR)
-----------------------------------------------------
Annual SaaS License (Enterprise)            12,000.00
Implementation Consulting (40 hrs)           8,000.00
-----------------------------------------------------
Subtotal                                    20,000.00
VAT (0% - Reverse Charge)                        0.00
-----------------------------------------------------
TOTAL DUE                                   20,000.00

Payment Terms: Net 30 days
Bank: [Your Bank Details]
IBAN: [Your IBAN]

Note: Reverse charge - Article 196 of VAT Directive 2006/112/EC.
VAT to be accounted for by the recipient.
```

## Invoice Template: B2B Goods

```
INVOICE

From: [Your Company Name]
      [Your Address]
      VAT: [Your VAT Number]

To:   [Spanish/Basque Company Name]
      [Their Address]
      VAT: ES[Their NIF]

Invoice No: 2026-0002
Date: 2026-01-19

Description                              Amount (EUR)
-----------------------------------------------------
Product A (100 units @ €50)                  5,000.00
Product B (50 units @ €120)                  6,000.00
Shipping                                       250.00
-----------------------------------------------------
Subtotal                                    11,250.00
VAT (0% - Intra-EU Supply)                       0.00
-----------------------------------------------------
TOTAL DUE                                   11,250.00

Intra-Community supply of goods.
Exempt with right to deduct per Article 138 VAT Directive.

Delivery: [Carrier name, tracking number]
Incoterms: [e.g., DDP Bilbao]
```

## VIES Validation

### Why It's Critical

| Without VIES Validation | With VIES Validation |
|------------------------|----------------------|
| Cannot zero-rate | Can zero-rate |
| Must charge VAT | Reverse charge applies |
| You're liable for VAT | Customer handles VAT |

### Validation Process

1. Go to: https://ec.europa.eu/taxation_customs/vies/
2. Select country: **ES** (Spain)
3. Enter VAT number (without ES prefix)
4. Click "Verify"
5. Save/screenshot the result with date

### Handling Invalid Numbers

| Result | Action |
|--------|--------|
| Valid | Proceed with zero-rating |
| Invalid | Request correct number |
| Still invalid | Do NOT zero-rate; charge VAT |
| Customer refuses to provide | Treat as B2C |

## Reporting: EC Sales List (ESL)

### Who Must File

Businesses making intra-EU B2B supplies must report to their home tax authority.

### What to Report

| Field | Description |
|-------|-------------|
| Customer VAT number | Full number including country code |
| Value of supplies | Total for reporting period |
| Indicator | Goods (G) or Services (S) |

### Filing Frequency

| Volume | Frequency |
|--------|-----------|
| < €50,000/quarter | Quarterly |
| ≥ €50,000/quarter | Monthly |

*Note: Thresholds may vary by home Member State.*

## Special Service Categories

### Services Following B2B Rule

Most services follow the general B2B rule (customer location):
- Professional services (consulting, legal, accounting)
- Advertising
- Data processing
- Hiring of movable goods
- Transfer of IP rights
- Digital/electronic services

### Services with Special Rules

Some services have specific place of supply rules even for B2B:

| Service | Place of Supply |
|---------|-----------------|
| Services related to immovable property | Where property is located |
| Passenger transport | Route taken |
| Restaurant services | Where performed |
| Cultural/sporting events admission | Where event takes place |

## Common B2B Scenarios

### Scenario 1: SaaS to Basque Business

```
Seller: German SaaS company
Buyer: Technology company in Bilbao

→ Service follows B2B general rule
→ Place of supply: Spain (where buyer is)
→ Reverse charge applies
→ German company invoices €10,000 + €0 VAT
→ Bilbao company self-assesses: €2,100 (21%)
→ Report on German EC Sales List
```

### Scenario 2: Consulting to Basque Business

```
Seller: French consultancy
Buyer: Manufacturing company in Vitoria-Gasteiz

→ Professional service, B2B rule applies
→ Place of supply: Spain
→ Reverse charge
→ Invoice without VAT
→ Customer accounts for VAT
```

### Scenario 3: Equipment Sale to Basque Business

```
Seller: Dutch manufacturer
Buyer: Distributor in San Sebastián

→ Intra-EU supply of goods
→ Zero-rated dispatch from Netherlands
→ Buyer accounts for acquisition VAT at 21%
→ Proof of transport required
→ Report on Dutch EC Sales List
```

### Scenario 4: Training at Customer Site (Basque Country)

```
Seller: UK training company (post-Brexit)
Buyer: Company in Bizkaia

→ Note: UK is now non-EU!
→ Different rules apply
→ May need to register or charge VAT
→ Consult specialist for non-EU scenarios
```

## Basque-Specific Considerations

### TicketBAI

- **Does NOT apply to you** (the foreign seller)
- May apply to your **customer** for their own records
- No action required on your part

### Filing Location

Your customer files VAT with:
- **Basque Diputación Foral** (if they're Basque tax resident)
- **AEAT** (if they're Spanish national tax resident)

This does not affect you - you file in your home country.

### VAT Rate Applied by Customer

Customer will self-assess at Spanish rate:
- 21% (general rate) - most services and goods
- 10% (reduced) - certain categories
- 4% (super-reduced) - specific items

## Documentation Checklist

Maintain for each B2B transaction:

- [ ] Customer's VAT number
- [ ] VIES validation proof (dated)
- [ ] Copy of invoice
- [ ] Contract or purchase order
- [ ] Proof of service delivery / goods transport
- [ ] Payment confirmation
- [ ] EC Sales List filing confirmation

## Key Takeaways

1. **B2B to Basque = Standard EU rules** - no special provincial treatment
2. **Always validate VAT numbers** via VIES before zero-rating
3. **Reverse charge notation** is mandatory on invoices
4. **Keep proof** of validation and transaction
5. **File EC Sales List** as required by your home country
6. **TicketBAI doesn't apply to you** as the foreign seller

## Sources

- [Marosa - Intra-Community VAT](https://marosavat.com/vat-news/intra-community-vat-what-it-is-how-apply)
- [Marosa - Reverse Charge in Spain](https://marosavat.com/manual/vat/spain/reverse-charge/)
- [Avalara - EU VAT Reverse Charge](https://www.avalara.com/vatlive/en/eu-vat-rules/eu-vat-returns/reverse-charge-on-eu-vat.html)
- [European Commission - Invoicing](https://taxation-customs.ec.europa.eu/taxation/vat/vat-businesses/invoicing_en)

---

*See also: [Reverse Charge](../vat-rules/reverse-charge.md) | [B2C Transactions](b2c-transactions.md) | [Place of Supply](place-of-supply.md)*
