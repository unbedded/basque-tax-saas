# NIF/CIF Requirements for Foreign EU Sellers

> **Status**: Researched
> **Last Updated**: 2026-01-19

## Tax ID Types in Spain

### NIF (Número de Identificación Fiscal)

The universal tax identification number in Spain for all businesses and individuals.

| NIF Type | Description | Format |
|----------|-------------|--------|
| NIF | Spanish citizens | 8 digits + letter (12345678A) |
| NIE | Foreign individuals (X, Y, Z prefix) | X/Y/Z + 7-8 digits + letter |
| NIF-N | Foreign legal entities abroad | N + 7 digits + letter |
| NIF-W | Permanent establishments of non-residents | W + 7 digits + letter |

### NIE (Número de Identidad de Extranjero)

Required for foreign individuals (both EU and non-EU) for:
- Filing taxes
- Opening bank accounts
- Establishing businesses
- Most official procedures

**Format**: X, Y, or Z + 7-8 digits + letter (e.g., X12345678A)

### Spanish VAT Number Format

Spanish VAT numbers follow the pattern: **ES** + NIF

Example: `ESB12345678` (B indicates a limited company)

## Requirements for Foreign EU Companies

### Scenario 1: Selling B2B (Reverse Charge)

**Do you need a Spanish NIF?** Generally NO.

- Reverse charge shifts VAT obligation to Spanish buyer
- Invoice without VAT, with "Reverse charge" notation
- Your home country VAT number is sufficient
- Verify buyer's VAT number via VIES

### Scenario 2: Selling B2C Below €10,000 Threshold

**Do you need a Spanish NIF?** Generally NO.

- Charge your home country VAT rate
- No Spanish registration required
- Keep evidence of customer locations

### Scenario 3: Selling B2C Above €10,000 Threshold

**Option A: Use OSS (Recommended)**
- No Spanish NIF needed
- Register for OSS in your home country
- File single quarterly return
- Charge Spanish VAT rate (21%, 10%, or 4%)

**Option B: Register for VAT in Spain**
- Obtain NIF-N (foreign legal entity)
- Register for Intra-Community operations (ROI)
- File Spanish VAT returns directly

### Scenario 4: Establishing Presence in Spain

**Required**: Full VAT/NIF registration

- NIF-W for permanent establishment, or
- NIF-N for foreign company
- Register in ROI (Registro de Operadores Intracomunitarios)
- Partners/administrators need NIE

## Registration Process

### For EU Companies (Without Permanent Establishment)

1. **Not Required for OSS** - use home country registration
2. **If choosing direct registration**:
   - Submit Form 036 (census declaration)
   - Provide company documentation (apostilled/translated)
   - Appoint tax representative (recommended, not mandatory for EU)

### For EU Companies (With Permanent Establishment)

1. All partners/legal representatives must have NIE
2. Submit Form 036 with required documentation
3. Provide apostilled/translated company documents
4. Register in ROI for intra-community operations

### Documentation Requirements

| Document | Requirement |
|----------|-------------|
| Company registration | Apostilled + Spanish translation |
| Powers of attorney | Apostilled + Spanish translation |
| Partner/director IDs | NIE required |
| Proof of address | Original or certified copy |

## Intra-Community VAT Registration (ROI)

### What is ROI?

The **Registro de Operadores Intracomunitarios** is Spain's official register for businesses conducting cross-border EU trade.

### Why Register?

- Enables VIES verification of your Spanish VAT number
- Required for B2B intra-community transactions
- Allows zero-rating of intra-EU supplies
- Mandatory for Pan-EU sellers (e.g., Amazon FBA)

### ROI vs Domestic NIF

| Aspect | Domestic NIF Only | NIF + ROI |
|--------|-------------------|-----------|
| Domestic sales | ✓ | ✓ |
| B2B intra-EU | ✗ | ✓ |
| VIES verification | ✗ | ✓ |
| EC Sales Lists | N/A | Required |

## Practical Recommendations

### For Most EU Sellers to Basque Country

```
START: What type of sales?
│
├─ B2B only?
│   └─ No Spanish registration needed
│   └─ Use reverse charge mechanism
│   └─ Verify buyer VAT via VIES
│
├─ B2C below €10,000/year (all EU)?
│   └─ No Spanish registration needed
│   └─ Charge home country VAT
│
└─ B2C above €10,000/year (all EU)?
    └─ RECOMMENDED: Use OSS in home country
    └─ ALTERNATIVE: Register NIF + ROI in Spain
```

### Key Decision Factors

| Factor | Recommendation |
|--------|----------------|
| B2B only | No Spanish registration |
| Low volume B2C | Home country VAT |
| High volume B2C | OSS (simplest) |
| Warehousing in Spain | Full registration required |
| Services only | OSS for B2C, reverse charge for B2B |

## Common Mistakes to Avoid

1. **Registering unnecessarily** - OSS often eliminates need for Spanish VAT registration
2. **Missing ROI registration** - Required if you do register and conduct B2B
3. **Not validating customer VAT** - Always verify via VIES for B2B
4. **Incorrect invoice wording** - Must state "Reverse charge" for B2B
5. **Mixing domestic and OSS** - Keep separate if registered in Spain

## Sources

- [Spanish Tax Agency - Legal NIF](https://sede.agenciatributaria.gob.es/Sede/en_gb/censos-nif-domicilio-fiscal/solicitar-nif/nif-juridica.html)
- [Fonoa - Spain VAT Guide](https://www.fonoa.com/resources/country-tax-guides/spain)
- [Balcells Group - CIF and NIF in Spain](https://balcellsgroup.com/cif-nif-tax-identification-numbers/)
- [Strong Abogados - NIE, CIF, VAT Guide](https://www.strongabogados.com/tax-id-spain)
- [VATai - Spanish VAT NIF vs Intra-Community](https://www.vatai.com/blog/understanding-spanish-vat)

---

*See also: [EU VAT Numbers](eu-vat-numbers.md) | [Registration Requirements](../legal-compliance/registration-requirements.md)*
