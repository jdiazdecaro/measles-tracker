# US Measles Outbreak & MMR Vaccination Coverage Tracker

A public health dashboard tracking confirmed measles cases and MMR vaccination coverage across the United States. Built to make CDC surveillance data more accessible and actionable for the public, researchers, and health communicators.

🔗 **[View the live dashboard](https://jdiazdecaro.github.io/measles-tracker/)** 

---

## Why this exists

Measles cases in the United States reached a 34-year high in 2025, and 2026 is on track to be worse. Despite this, publicly available data is scattered across multiple CDC pages and difficult for non-specialists to interpret quickly.

This dashboard brings together two key datasets (confirmed case counts by state and kindergarten MMR vaccination coverage) to tell a clearer story: where measles is spreading, where it is clustered in outbreaks, and how vaccination gaps are driving transmission.

---

## What the dashboard shows

- **Case map** — confirmed measles cases by state for 2026 (year-to-date), with a toggle to view MMR vaccination coverage by state
- **Active outbreak clusters** — current outbreaks with location, case counts, and transmission status
- **MMR vaccination rates** — kindergarten MMR coverage by state, highlighting states below the 95% herd immunity threshold
- **Key headline statistics** — total 2026 cases, number of active outbreaks, proportion of cases that are outbreak-associated, and national MMR coverage

---

## Data sources & methodology

| Data | Source | Update frequency |
|------|--------|-----------------|
| Confirmed measles case counts by state | [CDC Measles Data & Research](https://www.cdc.gov/measles/data-research/index.html) | Weekly (Thursdays) |
| MMR kindergarten vaccination coverage | [CDC School Vaccination View](https://www.cdc.gov/schoolvaxview/data/index.html) | Annually (fall) |

**Case data** reflects confirmed measles cases only, as reported by state and local health departments to CDC. Probable cases are excluded. Cases are assigned to a year based on the epidemiological week of rash onset. Data is updated weekly on Thursdays.

**Vaccination coverage** reflects the percentage of kindergartners who received the MMR vaccine, by state, for the 2024–25 school year. The 95% threshold represents the level of coverage generally needed to maintain herd immunity against measles. Two states (Montana and West Virginia) did not report 2024–25 data and are shown as "not reported."

**Outbreak clusters** are updated manually based on CDC outbreak reports and state health department announcements. An outbreak is defined as 3 or more epidemiologically linked cases.

---

## How to cite

If you use or reference this dashboard, please cite it as:

> Diaz-Decaro, J.D. (2026). *US Measles Outbreak & MMR Vaccination Coverage Tracker*. Black Swan Causal Labs, LLC. https://jdiazdecaro.github.io/measles-tracker/

---

## Disclaimer

This dashboard is for informational purposes only. Data reflects official CDC sources and is subject to revision as case investigations are completed. This tool is not intended as medical or public health advice. Please consult your local or state health department for guidance on measles exposure, vaccination, or outbreak response.

---

## Contact

**John D. Diaz-Decaro, PhD, MS**  
Black Swan Causal Labs, LLC  
📧 jdiazdecaro@gmail.com
