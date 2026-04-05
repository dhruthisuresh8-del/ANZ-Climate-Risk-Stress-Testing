# Climate Risk Assessment and Stress Testing of ANZ Bank

## Introduction
This report examines the climate-related financial risk exposure of Australia and 
New Zealand Banking Group (ANZ), analyzing how physical and transition climate 
risks influence its portfolio performance, credit quality, and capital resilience. 
Physical risks such as floods, bushfires, and sea-level rise threaten the value 
of collateral and borrower repayment capacity across ANZ's housing and agribusiness 
portfolios in Queensland, Northern NSW, and New Zealand. Transition risks arising 
from carbon pricing, regulatory tightening under APRA and NGFS frameworks, and 
technological disruption create long-term financial implications for carbon-intensive 
clients and investment exposures. Using Value-at-Risk (VaR) and climate 
stress-testing methodologies, the report quantifies ANZ's potential losses under 
both normal and disorderly transition scenarios, based on daily market data from 
2021 to 2024.

---

## Research Objectives
- Identify and categorize ANZ's physical and transition climate risk exposures
- Review and compare quantitative risk methods: VaR, ES, stress testing, Climate VaR
- Compute Value-at-Risk for ANZ's portfolio under normal market conditions
- Measure ANZ's sensitivity to climate transition risk using the BMG factor regression
- Simulate a disorderly climate transition stress scenario and quantify portfolio losses
- Provide strategic recommendations for embedding climate risk into ANZ's risk framework

---

## Tools & Methods
| Tool | Purpose |
|------|---------|
| Excel VBA | VaR calculations, stress testing models, scenario dashboards |
| Yahoo Finance | ANZ (ASX: ANZ), ASX 200, BMG Index daily data (2021–2024) |
| Value-at-Risk (VaR) | Maximum expected loss under normal market conditions |
| Climate Beta Regression | Sensitivity to Brown-minus-Green (BMG) transition factor |
| Climate Stress Testing | Disorderly transition scenario simulation |
| APRA / NGFS Frameworks | Regulatory alignment for climate scenario design |

---

## Key Findings

### 1. Physical & Transition Risk Exposure
| Risk Type | Key Drivers | ANZ Exposure | Financial Impact |
|---|---|---|---|
| Physical — Acute | Floods, cyclones, bushfires | Housing & agribusiness lending | Loan impairments, insurance dependency |
| Physical — Chronic | Drought, sea-level rise | Coastal property & agricultural loans | Higher default probability, reduced collateral |
| Transition — Policy | Carbon pricing, emission caps | Energy & manufacturing clients | Stranded assets, compliance costs |
| Transition — Technology | Shift to renewables, EV adoption | Energy & transport lending | Revenue loss for legacy industries |
| Transition — Reputation | ESG expectations, litigation | Institutional financing | Reputational loss, litigation costs |

---

### 2. Value-at-Risk (VaR) — Normal Market Conditions
| Metric | Result |
|---|---|
| Daily Volatility (σ) | 1.1% |
| 95% VaR | **A$18,150** |
| 99% VaR | **A$25,630** |
| Portfolio Value | A$1,000,000 (notional) |

- Under normal conditions, ANZ has a **95% chance** daily losses stay below A$18,150
- Only a **1% chance** of losing more than A$25,630 on any given day

---

### 3. Climate Factor Sensitivity Regression
| Factor | Coefficient | Interpretation |
|---|---|---|
| Market Beta (β_MKT) | 1.73 | ANZ moves 1.73x with the ASX 200 |
| Climate Beta (β_CLIMATE) | -0.008 | Mild negative sensitivity to brown-asset declines |
| R² | 0.65 | 65% of daily price changes explained by market and climate factors |

- Negative climate beta confirms ANZ's stock **falls modestly** when brown 
  sectors underperform
- Suggests **mild vulnerability** to climate-policy shocks but not high systemic risk

---

### 4. Climate Stress Testing — Disorderly Transition Scenario
| Scenario Assumption | Shock Applied |
|---|---|
| ASX 200 | -10% |
| Brown Index | -25% |
| Green Index | +10% |
| Brown-Green Combined Shock | -35% |

**Combined Portfolio Impact:**
- Market Impact = 1.73 × (-0.10) = **-17.3%**
- Climate Impact = -0.008 × (-0.35) = **+0.3%**
- Combined Impact = **-17.1%** → Estimated Loss = **A$170,593**

---

### 5. Normal vs Climate Stress Comparison
| Metric | Loss (A$) |
|---|---|
| 95% VaR | A$18,150 |
| 99% VaR | A$25,630 |
| Climate Stress Loss | **A$170,593** |

- Climate stress loss is **9 times larger** than the 99% VaR
- Confirms that **standard VaR alone cannot capture extreme climate 
  transition events**
- Climate transition risk is a **tail event** beyond normal statistical loss ranges

---

## Conclusion
The report concludes that climate change presents a **material financial threat** 
to ANZ. Stress-test results reveal potential losses nearly **nine times greater** 
than those predicted under standard market VaR models, underscoring the limitations 
of conventional risk metrics in capturing extreme transition shocks.

To strengthen resilience, ANZ must embed climate risk assessment into its 
governance, capital planning, and portfolio management frameworks. Incorporating 
**Climate VaR metrics**, conducting regular stress tests aligned with APRA and 
NGFS expectations, and enhancing real-time monitoring through **Key Risk Indicators 
(KRIs)** will improve early detection of climate-sensitive exposures. By integrating 
climate considerations into strategic decision-making and disclosure, ANZ can 
mitigate downside risks while positioning itself as a leader in sustainable and 
climate-aligned banking.

---

## Recommendations
- **Governance:** Establish a dedicated Climate Risk Committee aligned with 
  TCFD standards and link executive incentives to climate performance goals
- **Portfolio:** Reduce exposure to high-emission borrowers and increase 
  sustainable finance allocations
- **Monitoring:** Adopt KRIs linked to carbon exposure, sectoral sensitivity, 
  and borrower transition progress with real-time dashboards
- **Hedging:** Use green-bond futures or ESG derivatives to offset 
  transition shocks
- **Reporting:** Strengthen data partnerships and transparency to meet 
  evolving regulatory expectations under APRA and NGFS frameworks

---

## Files in this Repository
| File | Description |
|---|---|
| Dhruthi_SRM2.pdf | Full climate risk research report |
| Dhruthi_StressTest_VaR_Excel.xlsx | Excel VBA stress testing model |

---

**Institution:** RMIT University — Master of Finance
**Course:** Sustainable Financial Risk Management (BAFI3294)
**Submitted:** October 2025
