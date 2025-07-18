# Investigating Changes in Fertility Rates Over Time in Nigeria

## Project Overview
This repository contains an exploratory analysis of fertility trends in Nigeria from 1990 to 2021. Using national survey data, the project examines age-specific fertility rates (ASFR), total fertility rate (TFR), wanted fertility rate, general fertility rate (GFR), and crude birth rate (CBR). The goal is to uncover patterns in reproductive behavior and inform targeted health and policy interventions.

---

## Problem Statement
Despite periodic national surveys, Nigeria lacks a consolidated analysis of fertility changes across age groups. This limits the effectiveness of reproductive health programs and policy decisions.

---

## Objectives
- Analyze ASFR for women aged 15–49
- Track trends in TFR, wanted fertility, GFR, and CBR
- Compare actual vs. desired fertility rates
- Identify age cohorts with the highest fertility burden
- Recommend age-specific reproductive health interventions

---

## Methodology

### Data Acquisition
- Source: DHS-derived CSV file (1990–2021)
- Format: National fertility indicators

### Data Cleaning
- Removed metadata rows
- Converted key fields to numeric
- Dropped columns with >90% missing values

### Analysis & Visualization
- Summary statistics
- Line plots for ASFR, TFR, GFR, CBR
- Comparative charts for actual vs. wanted fertility
- Age cohort breakdowns and trend shifts

---

## Key Insights

| Insight | Description |
|--------|-------------|
| TFR Decline | Dropped from 5.85 (1990) to 4.70 (2021) |
| Teen Fertility | Ages 15–19 declined from 146 to 103 births per 1,000 |
| Fertility Gap | Actual vs. wanted fertility peaked at 0.45 children per woman in 2018 |
| GFR Trend | Fell from 207 to 164 births per 1,000 women aged 15–49 |
| CBR Trend | Declined from 38.1 to 32.4 per 1,000 population |
| Peak Fertility Age | Ages 25–29 had the highest average fertility |
| ASFR Change | Largest drops in ages 20–24, 25–29, and 15–19 |
| Stable Fertility | Ages 30–34 remained consistently high |
| Older Age Fertility | Ages 45–49 showed low but persistent fertility |
| Early Childbearing | Combined fertility for ages 15–24 remains high |
| Age Contribution | Younger women (15–24) contribute significantly more than older women (40–49) |

---

## Repository Structure


---

## Technologies Used
- Python
  - `pandas` for data manipulation
  - `matplotlib` and `seaborn` for visualization

---

## Recommendations
- Expand reproductive health education for adolescents
- Strengthen family planning services for peak fertility age groups
- Address gaps between desired and actual fertility through policy

---

## License
This project is licensed under the MIT License.
