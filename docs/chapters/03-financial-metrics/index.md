# Chapter 3: Financial Metrics

## Introduction

Market selection identifies where to invest; financial analysis determines whether a specific property deserves your capital. Real estate financial metrics provide standardized methods for evaluating investment performance, comparing opportunities, and making data-driven decisions.

This chapter covers the essential calculations every investor must master: net operating income (NOI), capitalization rate (cap rate), cash-on-cash return, gross rent multiplier (GRM), debt service coverage ratio (DSCR), internal rate of return (IRR), equity multiple, and expense ratios. Each metric illuminates different aspects of a property's financial profile, and skilled investors use multiple metrics in concert to build a complete picture.

## Net Operating Income (NOI)

Net Operating Income represents the annual income a property generates after operating expenses but before debt service and capital expenditures.

### Formula

```
NOI = Gross Operating Income - Operating Expenses
```

Where:
- **Gross Operating Income** = Gross Scheduled Income - Vacancy Loss + Other Income
- **Operating Expenses** = Property taxes + Insurance + Utilities + Maintenance + Management + Other recurring operating costs

### What NOI Excludes

Critically, NOI excludes:
- Mortgage principal and interest payments (debt service)
- Capital expenditures (roof replacement, major renovations)
- Depreciation (non-cash accounting expense)
- Income taxes

This exclusion allows NOI to represent the property's operational performance independent of financing structure, making it useful for comparing properties with different debt levels.

### Worked Example

Consider a quadplex investment:

| Income Item | Annual Amount |
|-------------|---------------|
| Gross Scheduled Rent (4 units × $1,200 × 12) | $57,600 |
| Vacancy Loss (5% of GSI) | -$2,880 |
| Laundry Income | $600 |
| **Gross Operating Income** | **$55,320** |

| Expense Item | Annual Amount |
|--------------|---------------|
| Property Taxes | $4,800 |
| Insurance | $1,500 |
| Utilities (common areas) | $1,200 |
| Maintenance & Repairs | $2,500 |
| Property Management (8% of GOI) | $4,426 |
| HOA Fees | $0 |
| **Total Operating Expenses** | **$14,426** |

**NOI = $55,320 - $14,426 = $40,894**

!!! note "NOI Importance"
    NOI is the foundation for commercial property valuation. While residential properties are valued via comparable sales, commercial properties (5+ units) are valued based on NOI divided by market cap rates.

## Capitalization Rate (Cap Rate)

The capitalization rate measures the relationship between a property's value and its NOI, representing the expected annual return on an all-cash purchase.

### Formula

```
Cap Rate = (NOI / Property Value) × 100
```

### Applications

**Valuation:**
```
Property Value = NOI / Cap Rate
```

If a property generates $50,000 NOI and the market cap rate is 6%, the property value is:
```
Value = $50,000 / 0.06 = $833,333
```

**Investment Comparison:**
Higher cap rates indicate higher returns but typically correlate with higher risk (worse locations, older properties, less stable tenants). Lower cap rates indicate lower returns but greater stability and appreciation potential.

**Typical Cap Rate Ranges:**

| Property Type | Cap Rate Range |
|---------------|----------------|
| Class A Multifamily (major metros) | 3.5% - 5.5% |
| Class B Multifamily | 5.5% - 7.5% |
| Class C Multifamily | 7.5% - 10% |
| Retail (grocery-anchored) | 6% - 8% |
| Office (CBD) | 5% - 7% |
| Self-Storage | 6% - 9% |

### Worked Example

Using the quadplex from the NOI example:
- Purchase Price: $450,000
- NOI: $40,894

```
Cap Rate = ($40,894 / $450,000) × 100 = 9.09%
```

A 9.09% cap rate is strong for a small multifamily property, indicating good income relative to price.

!!! warning "Cap Rate Limitations"
    Cap rates ignore financing, appreciation potential, and future income growth. They provide a snapshot of current yield but not total return. Additionally, cap rates vary significantly by market and property class—a 6% cap rate in San Francisco differs fundamentally from a 6% cap rate in Toledo.

## Cash-on-Cash Return

Cash-on-cash return measures the annual pre-tax cash flow relative to the actual cash invested, accounting for financing.

### Formula

```
Cash-on-Cash Return = (Annual Pre-Tax Cash Flow / Total Cash Invested) × 100
```

Where:
- **Annual Pre-Tax Cash Flow** = NOI - Annual Debt Service
- **Total Cash Invested** = Down payment + Closing costs + Immediate repairs

### Worked Example

Continuing the quadplex example:
- Purchase Price: $450,000
- Down Payment (25%): $112,500
- Closing Costs: $13,500
- Immediate Repairs: $4,000
- **Total Cash Invested: $130,000**

Financing:
- Loan Amount: $337,500 (75% LTV)
- Interest Rate: 7.0%
- Term: 30 years
- Annual Debt Service: $26,831

Cash Flow Calculation:

| Item | Amount |
|------|--------|
| NOI | $40,894 |
| Annual Debt Service | -$26,831 |
| **Annual Pre-Tax Cash Flow** | **$14,063** |

```
Cash-on-Cash Return = ($14,063 / $130,000) × 100 = 10.82%
```

A 10.82% cash-on-cash return is excellent, exceeding most investors' minimum threshold of 8-10%.

!!! tip "Cash-on-Cash vs. Cap Rate"
    Leverage amplifies returns when cap rates exceed interest rates. In this example, the cap rate was 9.09%, but leverage boosted cash-on-cash return to 10.82%. However, leverage also increases risk—if NOI declines, debt service obligations remain fixed.

## Gross Rent Multiplier (GRM)

GRM provides a quick valuation shortcut by comparing property price to gross rental income.

### Formula

```
GRM = Property Price / Gross Annual Rent
```

### Application

Lower GRMs indicate better value relative to income. Typical ranges:

| Market Type | GRM Range |
|-------------|-----------|
| Strong rental markets | 8 - 12 |
| Average markets | 12 - 15 |
| Weak markets | 15+ |

### Worked Example

Quadplex example:
- Purchase Price: $450,000
- Gross Annual Rent: $57,600

```
GRM = $450,000 / $57,600 = 7.81
```

A GRM of 7.81 is very favorable, indicating strong income relative to price.

!!! note "GRM Limitations"
    GRM ignores operating expenses, vacancy rates, and financing. It's useful for quick screening but should never replace comprehensive analysis. Two properties with identical GRMs may have vastly different NOI due to expense differences.

## Debt Service Coverage Ratio (DSCR)

DSCR measures a property's ability to cover debt obligations, indicating financial stability and lending risk.

### Formula

```
DSCR = NOI / Annual Debt Service
```

### Interpretation

- **DSCR > 1.25:** Excellent coverage; property comfortably pays debt
- **DSCR 1.15 - 1.25:** Adequate coverage; most lenders require minimum 1.20
- **DSCR 1.00 - 1.15:** Marginal coverage; high risk
- **DSCR < 1.00:** Insufficient income to cover debt; cash flow negative

### Worked Example

Quadplex example:
- NOI: $40,894
- Annual Debt Service: $26,831

```
DSCR = $40,894 / $26,831 = 1.52
```

A DSCR of 1.52 indicates strong debt coverage. The property generates 52% more income than required for debt service, providing a healthy cushion against income declines or expense increases.

!!! warning "Lender Requirements"
    Most commercial lenders require DSCR ≥ 1.25. Properties with lower coverage may only qualify for portfolio lenders or require larger down payments. Residential mortgages (1-4 units) don't explicitly require DSCR but effectively assess it through debt-to-income ratios.

## Internal Rate of Return (IRR)

IRR represents the annualized compound return over an investment's entire holding period, accounting for cash flows and time value of money.

### Concept

IRR is the discount rate that makes the net present value (NPV) of all cash flows equal to zero:

```
0 = Initial Investment + CF₁/(1+IRR)¹ + CF₂/(1+IRR)² + ... + (CFₙ + Sale Proceeds)/(1+IRR)ⁿ
```

Where CF = annual cash flow in each year.

### Calculation Method

IRR cannot be calculated algebraically and requires iterative methods or financial calculators. Excel's `IRR()` function automates this calculation.

### Worked Example

Quadplex 5-year hold scenario:

| Year | Cash Flow | Description |
|------|-----------|-------------|
| Year 0 | -$130,000 | Initial investment |
| Year 1 | $14,063 | Operating cash flow |
| Year 2 | $14,765 | Operating CF (5% growth) |
| Year 3 | $15,503 | Operating CF (5% growth) |
| Year 4 | $16,278 | Operating CF (5% growth) |
| Year 5 | $231,092 | Operating CF + sale proceeds |

Assumptions for Year 5:
- Property Value: $550,000 (3% annual appreciation)
- Remaining Mortgage: $313,456
- Sales Costs (6%): $33,000
- Net Sale Proceeds: $203,544
- Year 5 Operating CF: $27,548
- **Total Year 5: $231,092**

Excel IRR Calculation:
```
=IRR({-130000, 14063, 14765, 15503, 16278, 231092})
= 20.37%
```

An IRR of 20.37% is exceptional, combining strong cash flow with appreciation and debt paydown.

!!! tip "IRR Interpretation"
    IRR accounts for timing of cash flows, making it superior to simple average returns. Earlier cash flows are worth more than later ones. However, IRR assumes reinvestment of cash flows at the IRR rate, which may be unrealistic. Use IRR alongside other metrics for comprehensive analysis.

## Equity Multiple

Equity multiple measures total return as a ratio of money returned to money invested.

### Formula

```
Equity Multiple = Total Cash Returned / Total Cash Invested
```

### Worked Example

Quadplex example:
- Initial Investment: $130,000
- Total Operating Cash Flow (5 years): $88,199
- Net Sale Proceeds: $203,544
- **Total Cash Returned: $291,743**

```
Equity Multiple = $291,743 / $130,000 = 2.24×
```

An equity multiple of 2.24× means investors more than doubled their money over five years.

### Interpretation

| Equity Multiple | Return Quality |
|-----------------|----------------|
| < 1.5× | Weak return |
| 1.5× - 2.0× | Acceptable return |
| 2.0× - 3.0× | Strong return |
| > 3.0× | Excellent return |

!!! note "Equity Multiple vs. IRR"
    Equity multiple ignores time—a 2.0× return over 3 years (IRR ≈ 26%) is superior to 2.0× over 10 years (IRR ≈ 7.2%). Use equity multiple alongside IRR to capture both magnitude and timing of returns.

## Expense Ratios

Expense ratio measures operating expenses as a percentage of gross income, indicating operational efficiency.

### Formula

```
Expense Ratio = (Operating Expenses / Gross Operating Income) × 100
```

### Worked Example

Quadplex example:
- Operating Expenses: $14,426
- Gross Operating Income: $55,320

```
Expense Ratio = ($14,426 / $55,320) × 100 = 26.1%
```

### Typical Ranges

| Property Type | Expense Ratio Range |
|---------------|---------------------|
| Single-Family Rentals | 35% - 45% |
| Small Multifamily (2-4) | 30% - 40% |
| Large Multifamily (50+) | 25% - 35% |
| Class A Properties | 20% - 30% |
| Class C Properties | 35% - 50% |

An expense ratio of 26.1% is excellent for a quadplex, indicating efficient operations or lower property taxes in the market.

!!! warning "Seller Pro Formas"
    Many sellers provide optimistic expense projections. Always verify actual expenses from tax returns, invoices, and property management statements. Underestimated expenses are the primary cause of disappointing investment performance.

## Putting It All Together

No single metric tells the complete story. Comprehensive analysis uses multiple metrics:

**Quick Screening:**
- GRM for initial value assessment
- Cap rate for yield comparison

**Detailed Analysis:**
- NOI for operational performance
- Cash-on-cash return for levered cash flow
- DSCR for debt coverage and risk

**Hold Period Projections:**
- IRR for time-adjusted returns
- Equity multiple for total return magnitude
- Sensitivity analysis for downside scenarios

### Comparative Example

Consider two investment opportunities:

| Metric | Property A | Property B |
|--------|-----------|-----------|
| Purchase Price | $450,000 | $450,000 |
| NOI | $40,894 | $36,000 |
| Cap Rate | 9.09% | 8.00% |
| Cash-on-Cash Return | 10.82% | 7.58% |
| DSCR | 1.52 | 1.34 |
| 5-Year IRR | 20.37% | 14.22% |
| Equity Multiple | 2.24× | 1.83× |
| Market Growth | 3% annual | 5% annual |

Property A has superior current cash flow metrics, while Property B is in a higher-growth market with more appreciation potential. The choice depends on investor priorities: immediate cash flow versus long-term appreciation.

## Summary

Mastering financial metrics enables objective property evaluation and comparison. NOI measures operational performance; cap rate indicates yield; cash-on-cash return accounts for leverage; DSCR assesses risk; and IRR/equity multiple project long-term returns. No property should be purchased without calculating these core metrics and comparing them to investment criteria and alternative opportunities. The next chapter will explore how financing strategies impact these returns through leverage and loan structures.
