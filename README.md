# 🤖 Global AI Adoption & Workforce Impact — Complete ML Pipeline

---

## 📋 Executive Summary

### Problem Statement
Predict the **AI Adoption Rate (%)** for companies worldwide using firmographic features, AI maturity signals, workforce metrics, and country-level macro-indicators.

### Dataset — 3 Files
| File | Description | Key Columns |
|------|-------------|-------------|
| `ai_company_adoption.csv` | **Main** — company-quarter records | `ai_adoption_rate` (TARGET), `country`, `industry`, `company_size`, `productivity_change_percent` |
| `ai_industry_summary.csv` | Industry-level aggregates | `avg_ai_adoption_rate`, `avg_jobs_displaced/created` |
| `country_ai_index.csv` | Country macro-indicators | `gdp_per_capita`, `digital_maturity_index`, `ai_patent_filings_2024` |

### Target
`ai_adoption_rate` (%) — **Regression**

### Key Insights Preview
- 🏢 **Technology** sector leads adoption (~42.5%)
- 🌍 **Singapore & USA** lead country-level AI maturity
- 💼 Every 10% rise in AI adoption → ~1.1% productivity improvement
- 🔄 AI creates **more jobs than it displaces** across all industries

---
