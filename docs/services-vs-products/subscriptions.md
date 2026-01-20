# Subscription Services VAT Treatment

> **Status**: Researched
> **Last Updated**: 2026-01-19

## Overview

Subscription services have specific VAT considerations around:
- Classification (goods vs services vs digital)
- Tax point (when VAT becomes due)
- Ongoing supply treatment
- Customer location changes
- Refunds and cancellations

## Classification by Subscription Type

| Subscription Type | Classification | B2C VAT Treatment |
|-------------------|----------------|-------------------|
| SaaS/Software | Digital Service | Customer location (OSS) |
| Streaming (music/video) | Digital Service | Customer location (OSS) |
| Cloud storage | Digital Service | Customer location (OSS) |
| Online courses (automated) | Digital Service | Customer location (OSS) |
| Digital publications | Digital Service | Customer location (OSS) |
| Physical product box | Goods | Destination country |
| Print magazine | Goods | Destination country |
| Professional services retainer | Service | Usually supplier location* |
| Maintenance contracts | Service | Depends on nature |

*Unless specific exceptions apply

## Tax Point (Time of Supply)

### When Does VAT Become Due?

The **tax point** determines when VAT must be accounted for.

| Payment Model | Tax Point |
|---------------|-----------|
| Monthly billing | Each billing date |
| Quarterly billing | Each billing date |
| Annual prepayment | When payment received |
| Pay-as-you-go | When billed |
| Free trial → Paid | When first payment received |

### Continuous Supply Rules

For ongoing subscriptions, VAT is typically due:
- On each payment date, OR
- At the end of each billing period (if billed in arrears)

### Example: Annual SaaS Subscription

```
Scenario: €1,200/year SaaS subscription
Customer: Consumer in Basque Country
Payment: Paid upfront on January 1

Tax Point: January 1 (when payment received)
VAT Due: €1,200 × 21% = €252
When to Report: Q1 OSS return (due April 30)
```

### Example: Monthly SaaS Subscription

```
Scenario: €100/month SaaS subscription
Customer: Consumer in Basque Country
Payment: Charged monthly

Tax Point: Each billing date
VAT Due: €100 × 21% = €21 per month
When to Report: Quarter containing each billing date
```

## B2B Subscriptions

### Treatment

B2B subscriptions follow standard reverse charge rules:

| Element | Treatment |
|---------|-----------|
| Invoice | Without VAT |
| Notation | "Reverse charge applies" |
| Customer action | Self-assesses VAT |
| Your reporting | EC Sales List (if required) |

### Invoice Frequency Options

| Approach | Considerations |
|----------|----------------|
| Monthly invoices | Clear for customer's accounting |
| Quarterly invoices | Less administrative burden |
| Annual invoice | May cause cash flow issues |
| Invoice per period with regular payments | Common for enterprise |

### Sample B2B Subscription Invoice

```
INVOICE

To: [Spanish Business Customer]
VAT: ESB12345678

Subscription: Enterprise SaaS License
Period: January 1, 2026 - December 31, 2026
Amount: €12,000.00
VAT: €0.00 (Reverse charge)
Total: €12,000.00

Reverse charge - Article 196 VAT Directive 2006/112/EC
```

## B2C Subscriptions

### Digital Subscriptions

For digital service subscriptions to Basque Country consumers:

1. **Determine customer location** (2 evidence pieces)
2. **Charge Spanish VAT** (21% for most digital)
3. **File via OSS** quarterly
4. **Retain records** for 10 years

### Physical Subscriptions

For physical product subscriptions (e.g., subscription boxes):

1. **Place of supply** = Where goods delivered
2. **Charge Spanish VAT** (rate depends on goods)
3. **File via OSS** or local registration
4. **Ensure delivery compliance**

## Customer Location Changes

### What Happens If Customer Moves?

| Scenario | Treatment |
|----------|-----------|
| Customer moves within Spain | No change (still Spanish VAT) |
| Customer moves to another EU country | Apply new country's VAT from move date |
| Customer moves outside EU | Different rules apply |

### Best Practice

- Request notification of address changes in T&Cs
- Update billing information regularly
- Apply new rate from next billing cycle
- Document the change and reasoning

## Free Trials

### VAT Treatment

| Trial Type | VAT Treatment |
|------------|---------------|
| Free trial (no payment) | No VAT due |
| Free trial → Auto-convert | VAT due when first charge |
| €1 trial | VAT on €1 when charged |
| Extended free period | No VAT until paid |

### Conversion to Paid

When free trial converts to paid subscription:
- Tax point = date of first payment
- VAT applies from that date
- No retrospective VAT on free period

## Upgrades and Downgrades

### Upgrades

| Scenario | Treatment |
|----------|-----------|
| Mid-cycle upgrade | Additional supply; new tax point |
| Upgrade at renewal | New subscription; normal tax point |
| Pro-rated charge | VAT on pro-rated amount |

### Downgrades

| Scenario | Treatment |
|----------|-----------|
| Mid-cycle downgrade | Credit note for reduction |
| Downgrade at renewal | Lower price going forward |
| Refund of difference | Adjust VAT accordingly |

## Cancellations and Refunds

### Full Cancellation

| Timing | Treatment |
|--------|-----------|
| Before service starts | Full refund, no VAT impact |
| Mid-subscription | Pro-rata refund, adjust VAT |
| After period ends | No refund typically due |

### Partial Refunds

- Issue credit note for refunded amount
- Adjust VAT proportionally
- Update OSS return if in same quarter

### Credit Notes

Must include:
- Reference to original invoice
- Amount being credited
- VAT adjustment
- Reason for credit

## Multi-Year Subscriptions

### Prepaid Multi-Year

| Aspect | Treatment |
|--------|-----------|
| Tax point | When payment received |
| VAT rate | Rate at time of payment |
| Rate changes mid-term | Original rate usually applies |

### Billed Annually

| Aspect | Treatment |
|--------|-----------|
| Tax point | Each annual billing date |
| VAT rate | Rate at each billing date |
| Rate changes | New rate applies to new period |

## Bundled Subscriptions

### Mixed Digital + Physical

When subscription includes both digital and physical:

| Approach | When to Use |
|----------|-------------|
| Single supply | One element is principal |
| Multiple supplies | Elements are distinct and separate |

### Determining Treatment

Ask: "What is the customer primarily paying for?"

| Bundle | Likely Treatment |
|--------|------------------|
| SaaS + occasional merchandise | Single supply (digital) |
| Product box + digital access | Depends on value split |
| Magazine + digital archive | Often single (whichever is principal) |

## Compliance Checklist for Subscriptions

### Setup
- [ ] Classify subscription type correctly
- [ ] Determine if B2B or B2C
- [ ] Set up customer location evidence collection
- [ ] Configure correct VAT rates per country

### Ongoing
- [ ] Apply correct VAT rate each billing cycle
- [ ] Update rates when they change
- [ ] Handle customer location changes
- [ ] Process refunds correctly

### Reporting
- [ ] File OSS returns quarterly (B2C)
- [ ] Include all subscription revenue
- [ ] Report by Member State
- [ ] Retain records for 10 years

## Spain/Basque-Specific Notes

### VAT Rate
- Digital subscriptions: **21%**
- Physical subscriptions: Varies by content (4-21%)
- No Basque-specific rates (same as rest of Spain)

### TicketBAI
- **Does not apply** to foreign sellers
- Only applies if fiscally resident in Basque Country

### Language
- Invoices can be in any EU language
- Spanish appreciated but not required for OSS

## Key Takeaways

1. **Tax point** = billing date (usually)
2. **Digital subscriptions** → always customer location VAT
3. **B2B** → reverse charge, no VAT on invoice
4. **B2C** → charge destination VAT, file via OSS
5. **Customer moves** → apply new rate from change date
6. **Free trials** → no VAT until first payment
7. **Refunds** → adjust VAT proportionally

## Sources

- [European Commission - VAT on E-commerce](https://ec.europa.eu/taxation_customs/business/vat/vat-e-commerce_en)
- [Norman Finance - OSS Guide](https://norman.finance/blog/one-stop-shop)
- [Marosa - EU VAT Rules for E-commerce](https://marosavat.com/resources/vat-rules-for-e-commerce)
- [Lawants - VAT OSS Scheme Guide](https://www.lawants.com/en/oss-scheme/)

---

*See also: [Digital Services](digital-services.md) | [OSS/IOSS](../vat-rules/oss-ioss.md) | [Classification Guide](classification-guide.md)*
