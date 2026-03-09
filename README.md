# Medicare Part D Drug Spending Analysis (2019–2023)

![Python](https://img.shields.io/badge/Python-3.10-blue) ![pandas](https://img.shields.io/badge/pandas-2.0-green) ![matplotlib](https://img.shields.io/badge/matplotlib-3.7-orange) ![Data](https://img.shields.io/badge/Data-CMS%20Medicare-lightblue)

**Analyzing $276 billion in Medicare Part D drug spending to uncover cost drivers, price inflation trends, and generic substitution opportunities.**

> Author: Afriyie Karikari Bempah, PharmD | [LinkedIn](https://linkedin.com/in/afriyiekarikaribempah) | [GitHub](https://github.com/akbempah1)

---

## Overview

This project applies exploratory data analysis to the Centers for Medicare & Medicaid Services (CMS) Medicare Part D Drug Spending dataset, covering 2019–2023. Using Python, I investigate which drugs are driving Medicare costs, how prices have changed over five years, and where the biggest opportunities for cost reduction lie.

The analysis is informed by clinical pharmacy expertise, which shapes both the questions asked and the interpretation of findings.

---

## Key Findings

| Finding | Insight |
|---|---|
| **Eliquis leads total spend** | A single anticoagulant accounts for the largest share of Medicare Part D spending, reflecting both high unit cost and long-term daily use |
| **14.8% YoY spend increase** | Medicare Part D costs grew from $240B to $276B in a single year (2022–2023) |
| **Generic drugs drive price volatility** | The fastest-growing drug prices belong to generics, not brand-names — a counterintuitive finding reflecting market consolidation and supply shocks |
| **Orphan drugs cost $400K–$1.4M per patient** | Rare disease treatments create a hidden affordability crisis invisible in aggregate spending charts |
| **91% of spending is on brand-name drugs** | Despite generics being 10x cheaper per dose, brand drugs dominate Medicare expenditure — highlighting significant generic substitution opportunities |
| **Ozempic price dropped in 2023** | After rising steadily, Ozempic's per-dose cost fell sharply in 2023, consistent with the Inflation Reduction Act's Medicare negotiation provisions |

---

## Analyses & Visualizations

1. **Top 20 Drugs by Total Medicare Spend (2023)** — Identifies chronic disease medications as the primary cost drivers
2. **Top 20 Fastest Growing Drug Prices (CAGR 2019–2023)** — Reveals generic price inflation as a systemic problem
3. **Price Trend Analysis (2019–2023)** — Tracks Eliquis, Ozempic, Xarelto, and Pantoprazole Sodium across 5 years
4. **Spending vs Beneficiaries Scatter Plot** — Separates high-volume drugs from high-cost-per-patient drugs
5. **Cost Burden Per Patient (Top 20)** — Exposes orphan drug affordability crisis
6. **Brand vs Generic Comparison** — Quantifies the spend gap and generic substitution opportunity

---

## Dataset

- **Source:** [CMS Medicare Part D Drug Spending Data](https://data.cms.gov/summary-statistics-on-use-and-payments/medicare-medicaid-spending-by-drug/medicare-part-d-spending-by-drug)
- **Years covered:** 2019–2023
- **Records:** ~3,600 drugs across multiple manufacturers
- **Key note:** Dataset includes both individual manufacturer rows and an "Overall" aggregate row per drug. Analysis uses "Overall" rows to avoid double-counting.

---

## Technical Stack

- **Python** — pandas, matplotlib
- **Jupyter Notebook** — for reproducible analysis
- **Data cleaning** — manufacturer deduplication, missing value handling, column reshaping

---

## How to Run

```bash
# Clone the repository
git clone https://github.com/akbempah1/medicare-drug-spending-analysis.git

# Install dependencies
pip install pandas matplotlib jupyter

# Launch notebook
jupyter notebook medicare_analysis.ipynb
```

---

## About the Author

I am a pharmacist and data scientist with a PharmD and dual MSc degrees in Finance and Computer Science. I build health data analytics tools for African pharmacy markets through [Aduru Analytics](https://aduruanalytics.com) and conduct public health research using large-scale datasets including CDC BRFSS, NHANES, and NIS.

This project is part of a broader portfolio applying data science to real-world healthcare and pharmaceutical challenges.

---

*Data Source: Centers for Medicare & Medicaid Services (CMS). Analysis and interpretations are independent and not affiliated with CMS.*
