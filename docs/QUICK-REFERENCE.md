# Quick Reference: EU → Basque Country E-Invoicing

> **One-page summary of key requirements for cross-border sales**
> **Last Updated**: 2026-01-19

---

## Decision Flowchart

```
EU Company selling to Basque Country
│
├─ WHO is your customer?
│   │
│   ├─ BUSINESS (B2B)
│   │   └─ Verify VAT number (VIES)
│   │   └─ Invoice WITHOUT VAT
│   │   └─ Add "Reverse charge" notation
│   │   └─ Customer self-assesses Spanish VAT
│   │   └─ NO Spanish registration needed
│   │   └─ TicketBAI: NOT APPLICABLE
│   │
│   └─ CONSUMER (B2C)
│       └─ Determine customer location (2 evidence pieces)
│       └─ Charge Spanish VAT (usually 21%)
│       └─ File via OSS in your home country
│       └─ NO Spanish registration needed
│       └─ TicketBAI: NOT APPLICABLE
```

---

## VAT Rates at a Glance

| Rate | Percentage | Common Applications |
|------|------------|---------------------|
| **General** | **21%** | Digital services, SaaS, most goods, consulting |
| **Reduced** | **10%** | Food, hotels, transport, hospitality |
| **Super-Reduced** | **4%** | Basic food, books, medicines |

**Note**: Basque Country uses identical rates to rest of Spain.

---

## B2B Transaction Checklist

- [ ] Verify customer's VAT number via [VIES](https://ec.europa.eu/taxation_customs/vies/)
- [ ] Save VIES validation screenshot with date
- [ ] Invoice WITHOUT VAT (€0.00)
- [ ] Include: "Reverse charge - Article 196 VAT Directive 2006/112/EC"
- [ ] Include customer's full VAT number (ESxxxxxxxx)
- [ ] File EC Sales List if required by your home country
- [ ] Retain records for 10 years

---

## B2C Transaction Checklist

- [ ] Collect customer location evidence (2 pieces):
  - [ ] Billing address
  - [ ] IP address, payment country, or other
- [ ] Above €10,000 EU threshold? → Must charge destination VAT
- [ ] Apply Spanish VAT rate (21% for most digital/SaaS)
- [ ] File quarterly OSS return in home country
- [ ] Pay VAT to home tax authority
- [ ] Retain records for 10 years

---

## TicketBAI Summary

| Question | Answer |
|----------|--------|
| Does TicketBAI apply to foreign EU sellers? | **NO** (generally) |
| Why not? | You're not fiscally resident in Basque Country |
| When would it apply? | Only if you establish fiscal residence/PE there |
| What should you use instead? | Reverse charge (B2B) or OSS (B2C) |

---

## OSS Quick Facts

| Aspect | Detail |
|--------|--------|
| What | One-Stop Shop for EU VAT compliance |
| Where to register | Your home EU country |
| Filing frequency | Quarterly |
| Due dates | Apr 30, Jul 31, Oct 31, Jan 31 |
| Record retention | 10 years |
| Advantage | Single registration covers all EU countries |

---

## Invoice Requirements Summary

### B2B Invoice (Reverse Charge)

```
✓ Your company name, address, VAT number
✓ Customer company name, address, VAT number
✓ Invoice number and date
✓ Clear description of goods/services
✓ Net amount (no VAT)
✓ "Reverse charge - Article 196 VAT Directive"
```

### B2C Invoice (With VAT)

```
✓ Your company name, address, VAT number
✓ Customer name (if provided)
✓ Invoice number and date
✓ Description of goods/services
✓ Net amount
✓ VAT rate (21%, 10%, or 4%)
✓ VAT amount
✓ Gross total
```

---

## Common Scenarios

| Scenario | VAT Treatment |
|----------|---------------|
| SaaS to Spanish business | Reverse charge, 0% on invoice |
| SaaS to Spanish consumer | 21% via OSS |
| Consulting to Spanish business | Reverse charge, 0% on invoice |
| Physical goods to Spanish business | Zero-rated dispatch, buyer accounts for VAT |
| Physical goods to Spanish consumer | Spanish VAT via OSS (usually 21%) |
| Subscription (digital) to consumer | 21% via OSS |

---

## Key URLs

| Resource | URL |
|----------|-----|
| VIES Validation | https://ec.europa.eu/taxation_customs/vies/ |
| OSS Portal | https://vat-one-stop-shop.ec.europa.eu/ |
| EU VAT Rates | https://ec.europa.eu/taxation_customs/vat-rates_en |
| Spanish Tax Agency | https://sede.agenciatributaria.gob.es |

---

## Warning Signs: When to Get Professional Help

Consult a tax advisor if:
- [ ] You're establishing a physical presence in Basque Country
- [ ] You're considering registering for VAT directly in Spain
- [ ] Your transactions don't fit the standard B2B/B2C patterns
- [ ] You have complex mixed supplies or unusual business models
- [ ] You're unsure about classification of your offerings
- [ ] You need to recover input VAT in Spain

---

## Key Takeaways

1. **TicketBAI doesn't apply** to most foreign EU sellers
2. **OSS is your friend** for B2C - single filing point
3. **Reverse charge simplifies B2B** - no VAT on your invoice
4. **VAT rates are harmonized** - same across all of Spain
5. **VIES validation is essential** - always verify B2B customers
6. **10-year record retention** - keep everything
7. **When in doubt, consult a professional**

---

*For detailed information, see individual documents in the `docs/` directory.*
