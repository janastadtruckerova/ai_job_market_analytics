# AI Job Market Analytics
### Exploratory Data Analysis + Interactive Portfolio Application

A end-to-end data analytics project exploring an AI job market dataset across five analytical dimensions — delivered as a single-file interactive web application.

**[→ View Live Application](https://your-username.github.io/ai-job-market-analytics)**

---

## Project Overview

This project covers the full analytical pipeline: from data profiling and quality assessment through five thematic analyses to a synthesised strategic summary. Each analytical layer was designed to answer a specific business question about the AI job market.

| Dimension | Key Question |
|---|---|
| Salary Analysis | Which roles, industries and locations command premium compensation? |
| Automation Risk | Where does risk concentrate — and does it correlate with salary or growth? |
| Job Growth | Which roles and industries are expanding vs. contracting? |
| Skills Gap | Which skills consistently appear in growing, low-risk positions? |
| Geography | Which cities offer the strongest combination of salary, growth and low risk? |

---

## Dataset

- **Source:** Kaggle — [AI Job Market Insights](https://www.kaggle.com)
- **Size:** 500 records · 10 variables
- **Note:** Synthetic dataset. Perfectly balanced categories and zero missing values confirm a generated source. Conclusions are directional — the analytical methodology and cross-dimensional consistency of findings are the core portfolio value.

| Variable | Type | Unique Values |
|---|---|---|
| Job_Title | Categorical | 10 |
| Industry | Categorical | 10 |
| Location | Categorical | 10 |
| Company_Size | Categorical | 3 |
| AI_Adoption_Level | Categorical | 3 |
| Automation_Risk | Categorical | 3 |
| Required_Skills | Categorical | 10 |
| Salary_USD | Numeric | 500 |
| Remote_Friendly | Binary | 2 |
| Job_Growth_Projection | Categorical | 3 |

---

## Key Findings

### The Red Thread
**Machine Learning + UX/UI Design** emerged as the protective skill combination independently across all four analytical dimensions. This was not targeted — it surfaced consistently from separate salary, risk, growth, and skills gap analyses.

### Cross-Analysis Paradoxes

**AI Adoption Paradox**
High AI adoption firms pay $5,771 less on average and show the highest job decline rate (37.4%). The data suggests AI is substituting labour rather than complementing it.

**Retail Salary Inversion**
Declining Retail positions pay $8,877 more than growing ones — a classic signal of retention spending on legacy roles being phased out by automation.

**Safe but Stagnant**
Communication skill carries the highest low-risk share (47%) paired with the highest decline rate (44%). These roles are not being automated away — they simply are not growing.

### Winners & Losers

| Role | Net Growth Score | Avg Salary | Signal |
|---|---|---|---|
| Operations Manager | +12 | $96,937 | Strong across all dimensions |
| Product Manager | +5 | $90,803 | Growing, mixed risk |
| Marketing Specialist | -12 | $90,961 | Highest decline rate |
| HR Manager | -8 | $89,252 | Under pressure |

| Industry | Net Growth Score | Avg Salary |
|---|---|---|
| Finance | +8 | $94,355 |
| Education | +8 | $93,799 |
| Retail | -10 | $91,233 |
| Energy | -8 | $92,764 |

---

## Application Features

The analysis is packaged as a **single-file interactive HTML application** with no backend or external dependencies required.

- **7 sections** — Overview, Salary, Automation Risk, Job Growth, Skills Gap, Geography, Key Insights
- **Live filter controls** on every analytical page — filter by industry, location, risk level, growth projection, company size, and AI adoption level
- **Dynamic recalculation** — all charts, KPI cards and tables update instantly on filter change
- **Deployable anywhere** — single HTML file, works offline, no server needed

---

## Tech Stack

| Tool | Usage |
|---|---|
| Python | Data analysis and EDA |
| pandas | Data manipulation and aggregation |
| Chart.js | Interactive scatter and bar charts |
| Vanilla JS | Filter logic and dynamic rendering |
| HTML / CSS | Application layout and styling |

---

## Project Structure

```
ai-job-market-analytics/
│
├── index.html          # Complete interactive application (single file)
├── README.md           # This file
└── analysis/
    └── eda.py          # Python EDA script (pandas)
```

---

## How to Run Locally

No installation required. Simply open `index.html` in any modern browser.

```bash
git clone https://github.com/your-username/ai-job-market-analytics.git
cd ai-job-market-analytics
open index.html
```

---

## Author

Built as a portfolio project demonstrating end-to-end analytical thinking — from raw data assessment through multi-dimensional analysis to interactive delivery.

> *"While many can build a model, the value is in building the right solution that drives actionable insight."*

---

*Data source: Kaggle · Synthetic dataset · Portfolio project 2025*
