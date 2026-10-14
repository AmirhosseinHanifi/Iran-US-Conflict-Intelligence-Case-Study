# Iran–US Conflict Intelligence Case Study

## Overview

This repository contains three files that together form a professional case study in **Open-Source Intelligence (OSINT), structured data analysis, probabilistic assessment, and intelligence reporting**.

The work focuses on assessing the probability of renewed large-scale conflict between Iran and the United States across different time horizons.

The three files represent the main stages of the analytical workflow:

**Data → Analytical Output → Intelligence Assessment**

---

## Files

### `iran_us_war_mega_dataset_v3.json`

This is the structured OSINT dataset used for the assessment.

It contains **2,234 unique events**, including **1,339 war-relevant events**, collected from multiple open-source families and covering the assessment period from **27 February 2026 to 14 October 2026**.

The dataset combines information from sources and feeds including news media, GDELT, Google News, OSINT sources, Reddit, Telegram, Wikipedia, think tanks, and other open sources.

The dataset also contains structured dimensions, relevance information, source families, and analytical signals used in the assessment.

---

### `oracle_run_results_v3.json`

This file contains the analytical output generated from the dataset.

It includes the results of the analytical process, including:

- Scenario assessment
- Probability estimates
- Bayesian analysis
- Monte Carlo simulation
- Scenario ranking
- Key drivers
- Uncertainty ranges
- Analytical signals and assessments

The underlying **ORACLE analytical engine is proprietary**. This repository contains the resulting analytical output for demonstration and portfolio purposes, not the private source code, internal architecture, or intellectual property of the engine.

---

### `ارزیابی-احتمال-جنگ-گسترده-ایران-آمریکا (1).docx`

This is the full intelligence assessment report produced from the dataset and analytical results.

The report presents the methodology, data landscape, source composition, timeline analysis, probability assessment, scenario analysis, uncertainty analysis, key drivers, monitoring indicators, and conclusions.

The assessment uses a five-layer analytical approach combining:

- Baseline assessment
- Scenario Decision Analysis (SDA)
- Bayesian Logit
- Monte Carlo simulation
- Corpus/data-driven monitoring

The report estimates the probability of renewed large-scale conflict at approximately:

| Horizon | Estimated Probability |
|---|---:|
| 1 month | **35%** |
| 3 months | **66%** |
| 6 months | **77%** |

These values are analytical estimates based on the available data and methodology, not guarantees or claims of certainty.

---

## Analytical Workflow

```text
OSINT Sources
      ↓
Event Collection
      ↓
Deduplication & Structuring
      ↓
Signal Extraction
      ↓
ORACLE Analytical Processing
      ↓
Probabilistic Assessment
      ↓
Scenario Ranking
      ↓
Driver & Uncertainty Analysis
      ↓
Intelligence Assessment Report
```

---

## Purpose of This Repository

This repository is intended as a **professional portfolio case study** demonstrating practical capability in:

- OSINT collection
- Intelligence data structuring
- Geopolitical risk analysis
- Probabilistic assessment
- Scenario analysis
- Bayesian reasoning
- Monte Carlo simulation
- Uncertainty analysis
- Intelligence reporting

It is not presented as an official governmental, military, or institutional assessment.

---

## Author

**Amirhossein Hanifi**

Independent Intelligence & Data Analyst

**Focus:** OSINT · Geopolitical Risk · Intelligence Analysis · Probabilistic Modeling · Data Analysis

---

## Assessment Date

**14 October 2026**

**Case Study Version:** 3
