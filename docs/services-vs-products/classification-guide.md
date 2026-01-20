# Product vs Service vs Subscription Classification Guide

> **Status**: Research in Progress
> **Last Updated**: 2026-01-19

## Why Classification Matters

The classification of your supply determines:
1. **Place of supply** (which country's VAT applies)
2. **VAT rate** applicable
3. **Invoice requirements**
4. **Reporting obligations**
5. **TicketBAI applicability** (potentially)

## Classification Categories

### 1. Goods (Physical Products)
**Definition**: Tangible, movable property

**Characteristics**:
- Physical item that can be shipped
- Ownership transfers to buyer
- Can be stored, returned, resold

**VAT Treatment (EU → Basque Country)**:
- B2B: Zero-rated + reverse charge
- B2C: Taxed at destination (Spain/Basque)

### 2. Services (General)
**Definition**: Any supply that is not goods

**Characteristics**:
- Intangible
- No physical item transferred
- Consumed as provided

**VAT Treatment (EU → Basque Country)**:
- B2B: Reverse charge (place of supply = customer location)
- B2C: Typically seller's country VAT (exceptions apply)

### 3. Electronically Supplied Services (Digital)
**Definition**: Services delivered over the internet with minimal human intervention

**Examples**:
- Software downloads
- SaaS platforms
- Digital content (music, video, ebooks)
- Online courses (automated)
- Website hosting
- Cloud storage

**NOT Digital Services**:
- Services merely ordered online (e.g., booking a hotel)
- Professional services via email/video call
- Online courses with significant teacher interaction

**VAT Treatment (EU → Basque Country)**:
- B2B: Reverse charge
- B2C: **Always** taxed where customer is located (special rule)

### 4. Subscription Services
**Depends on what is being provided**:

| Subscription Type | Classification | VAT Treatment |
|-------------------|----------------|---------------|
| SaaS subscription | Digital service | B2C: Customer location |
| Physical product subscription (box) | Goods | B2C: Destination country |
| Magazine subscription (print) | Goods | B2C: Destination country |
| Magazine subscription (digital) | Digital service | B2C: Customer location |
| Professional services retainer | Service | B2C: Usually seller location |
| Streaming service | Digital service | B2C: Customer location |

## Decision Tree

```
START: What are you supplying?
│
├─ Physical item?
│   └─ YES → GOODS → Go to Goods Rules
│   └─ NO → Continue ↓
│
├─ Delivered electronically with minimal human intervention?
│   └─ YES → DIGITAL SERVICE → Go to Digital Service Rules
│   └─ NO → Continue ↓
│
└─ Everything else
    └─ SERVICE (General) → Go to Service Rules
```

## Mixed/Bundled Supplies

When you supply both goods and services together:

### Single Supply vs Multiple Supplies
- **Single supply**: One element is principal, others are ancillary
- **Multiple supplies**: Each element is distinct and independent

### Determining Principal Element
Ask: What is the customer really paying for?
- If goods are the main thing → Treat as goods
- If service is the main thing → Treat as service

### Examples
| Bundle | Likely Classification |
|--------|----------------------|
| Software + installation | Single supply (digital service) if installation is standard |
| Hardware + support subscription | Multiple supplies (goods + service) |
| Training course + materials | Single supply (service) if materials are ancillary |

## Subscription Specific Considerations

### Tax Point (Time of Supply)
When does VAT become due?

| Payment Type | Tax Point |
|--------------|-----------|
| Prepayment (annual) | On payment |
| Monthly billing | Each billing date |
| Continuous supply | End of each billing period |

### Changes in Customer Location
If a B2C customer moves during a subscription:
- [RESEARCH NEEDED: How to handle mid-subscription location changes]

### Free Trials and Upgrades
- Free trials: No VAT until paid service starts
- Upgrades: Additional supply, treat according to its nature

## Key Questions to Resolve

- [ ] How is a bundled SaaS + support contract classified?
- [ ] What evidence is needed for customer location on subscriptions?
- [ ] How do subscription renewals interact with TicketBAI?
- [ ] How are partial refunds treated for VAT purposes?

## Practical Checklist

For each product/service you offer:

1. [ ] Classify: Goods / Service / Digital Service
2. [ ] Determine if subscription or one-time
3. [ ] Identify customer type: B2B or B2C
4. [ ] Determine place of supply
5. [ ] Identify applicable VAT rate
6. [ ] Document invoice requirements
7. [ ] Determine reporting obligations

## Sources

- EU VAT Directive - Article 24 (services definition)
- EU VAT Directive - Article 58 (electronically supplied services)
- EU Implementing Regulation 282/2011 - Annex I (digital services list)
- [RESEARCH: Spanish/Basque specific guidance]

---

*See also: [Digital Services](digital-services.md) | [Subscriptions](subscriptions.md) | [Mixed Supplies](mixed-supplies.md)*
