# Record Retention Requirements

> **Status**: Researched
> **Last Updated**: 2026-01-19

## Overview

E-invoicing and VAT compliance require maintaining records for specified periods. For foreign EU sellers to Basque Country, the primary requirements come from:
- **EU VAT Directive** (for OSS users)
- **Your home country** tax rules
- **Spanish law** (if directly registered in Spain)

## Key Retention Period: 10 Years

For OSS users (most foreign EU sellers), the EU requires:

> **10-year retention** for all records related to OSS transactions

This is the most stringent requirement and should be your default.

## Retention Periods Summary

### For OSS Users (Recommended Approach)

| Document Type | Retention Period | Legal Basis |
|---------------|------------------|-------------|
| Invoices/receipts | **10 years** | EU VAT Directive |
| Customer location evidence | **10 years** | OSS requirements |
| OSS returns | **10 years** | OSS requirements |
| Payment records | **10 years** | OSS requirements |
| VIES validation records | **10 years** | Best practice |

### For Direct Spanish VAT Registration

If you register directly in Spain (not recommended for most):

| Document Type | Retention Period | Legal Basis |
|---------------|------------------|-------------|
| Invoices issued | **4-6 years** | Spanish Commercial Code |
| VAT records | **4 years** | Spanish VAT regulations |
| Accounting records | **6 years** | Spanish Commercial Code |

**Note**: OSS 10-year requirement is longer, so default to that.

### For B2B (Reverse Charge) Transactions

| Document Type | Retention Period | Reasoning |
|---------------|------------------|-----------|
| Invoices | Per your home country rules | You're the supplier |
| VIES validation | Match invoice retention | Proves zero-rating validity |
| EC Sales Lists | Per your home country rules | Your filing obligation |
| Contracts | Per your home country rules | Supporting documentation |

## What Records to Keep

### Essential Records for All Transactions

| Record | Purpose | Format |
|--------|---------|--------|
| Invoice copies | Transaction proof | PDF or original format |
| Payment confirmations | Proof of receipt | Electronic acceptable |
| Customer details | Identity verification | Secure storage required |

### B2B Specific Records

| Record | Purpose | Critical? |
|--------|---------|-----------|
| VIES validation screenshot | Proves valid VAT number | **Yes** |
| Date of validation | Contemporaneous evidence | **Yes** |
| Customer's VAT number | Identifies buyer | **Yes** |
| Reverse charge notation | Compliance proof | **Yes** |
| EC Sales List filings | Reporting compliance | If applicable |

### B2C Specific Records (OSS)

| Record | Purpose | Critical? |
|--------|---------|-----------|
| Customer location evidence | Proves correct VAT rate | **Yes** |
| Evidence type 1 (e.g., billing address) | Location determination | **Yes** |
| Evidence type 2 (e.g., IP address) | Location confirmation | **Yes** |
| VAT rate applied | Audit trail | **Yes** |
| OSS return copies | Filing proof | **Yes** |
| Payment to tax authority | Compliance proof | **Yes** |

### Digital Service Subscriptions

| Record | Purpose | Notes |
|--------|---------|-------|
| Subscription agreement | Terms of service | Keep full duration + 10 years |
| Each billing record | Individual tax points | 10 years from each bill |
| Customer location changes | Rate changes | Document date of change |
| Cancellation/refund records | Adjustments | 10 years |

## Storage Requirements

### Format Requirements

| Requirement | Detail |
|-------------|--------|
| Authenticity | Must prove who issued document |
| Integrity | Must prove document not altered |
| Legibility | Must be readable throughout retention period |
| Accessibility | Must be available on request |

### Acceptable Formats

| Format | Acceptable? | Notes |
|--------|-------------|-------|
| PDF | Yes | Ensure long-term readability |
| Original XML | Yes | Preserve structure |
| Scanned paper | Yes | If authenticity ensured |
| Database records | Yes | Must be exportable |
| Screenshots | Yes | For VIES validation |

### Electronic Storage

- Electronic storage is fully permitted
- No requirement to keep paper copies
- Must ensure data integrity and backup
- Must be able to produce on request

### Location of Storage

For OSS users:
- Can store outside Spain
- Must provide **online access** to tax authorities if requested
- Your home country's tax authority is primary contact
- Spain may request via your home authority

## Evidence Requirements Detail

### Customer Location (B2C Digital Services)

You need **two pieces of non-contradictory evidence**:

| Evidence Type | What to Record |
|---------------|----------------|
| Billing address | Full address as provided |
| IP address | IP and derived country |
| Bank/card country | Country of payment method |
| SIM country code | For mobile purchases |

**Store**: The actual evidence, not just the conclusion

### VIES Validation (B2B)

| What to Record | Example |
|----------------|---------|
| Customer VAT number | ESB12345678 |
| Validation date | 2026-01-19 |
| Validation result | Valid/Active |
| Screenshot or API response | PDF or image |

## Organizing Your Records

### Recommended Structure

```
records/
├── 2026/
│   ├── Q1/
│   │   ├── invoices/
│   │   ├── vies-validations/
│   │   ├── customer-evidence/
│   │   └── oss-return/
│   ├── Q2/
│   └── ...
├── 2025/
└── ...
```

### Naming Conventions

| Document Type | Suggested Format |
|---------------|------------------|
| Invoice | `INV-YYYY-NNNNN.pdf` |
| VIES validation | `VIES-VATNUM-YYYYMMDD.png` |
| OSS return | `OSS-YYYY-QN.pdf` |
| Customer evidence | `CUST-ID-evidence-YYYYMMDD.pdf` |

## Access and Audit

### Tax Authority Access

If requested, you must provide:
- Records within reasonable timeframe
- In readable format
- With ability to verify authenticity

### Audit Preparation

Maintain index/register of:
- All invoices by period
- Total VAT collected by country
- OSS filings and payments
- VIES validations performed

## Penalties Overview

### For OSS Non-Compliance (Spain as consumption country)

Per Spanish rules:
| Violation | Penalty Range |
|-----------|---------------|
| Late registration | €400 (reducible to €200) |
| Incorrect VAT returns | €150 |
| Non-payment of VAT | 50-150% surcharge |
| Missing invoices | 1-2% of amounts involved |

### Record Keeping Failures

- May lose right to zero-rate (B2B)
- May face estimated assessments
- May face penalties for incorrect VAT
- Potential audit adjustments

## Best Practices

### Do's

- [x] Keep records for **full 10 years** (OSS standard)
- [x] Use consistent naming and organization
- [x] Backup regularly (3-2-1 rule: 3 copies, 2 media, 1 offsite)
- [x] Test retrieval procedures annually
- [x] Document your retention policy
- [x] Automate where possible

### Don'ts

- [ ] Don't delete records early
- [ ] Don't store only in one location
- [ ] Don't use formats that may become unreadable
- [ ] Don't forget to back up VIES validations
- [ ] Don't commingle personal and business records

## System Integration

Your e-invoicing/accounting system should:

| Feature | Importance |
|---------|------------|
| Automatic archiving | Essential |
| Immutable audit trail | Essential |
| Export capability | Essential |
| Search functionality | Important |
| Backup automation | Essential |
| Access controls | Important |

## Key Takeaways

1. **10 years** is the safe retention period (OSS requirement)
2. **Two evidence pieces** for customer location (B2C)
3. **VIES validation** must be documented (B2B)
4. **Electronic storage** is fully acceptable
5. **Organize systematically** for easy retrieval
6. **Backup regularly** to prevent data loss
7. **Test your retrieval** process annually

## Sources

- [EC Spain VAT Rules - OSS](https://vat-one-stop-shop.ec.europa.eu/national-vat-rules/spain-vat-rules_en)
- [European Commission - OSS Guidelines](https://vat-one-stop-shop.ec.europa.eu/guides_en)
- EU VAT Directive 2006/112/EC - Articles 241-249
- [Strong Abogados - EU E-Commerce Compliance Guide](https://www.strongabogados.com/articles/guide-for-eu-e-commerce-compliance)

---

*See also: [Audit Trails](audit-trails.md) | [Digital Storage](digital-storage.md) | [OSS/IOSS](../vat-rules/oss-ioss.md)*
