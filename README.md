# Netflix EMEA Production Finance Analysis

A data analysis project exploring content trends, production finance modelling and market insights across 35+ markets in Europe, the Middle East and Africa.

---

## Project Overview

This project covers end-to-end data analysis across the following areas:

- Data extraction, cleaning and transformation using Python
- SQL queries via SQLite in Jupyter Notebooks for business reporting
- Financial data modelling based on Netflix public spending reports
- EMEA market analysis across 35+ countries
- Stakeholder-ready visualisations and executive presentation

---

## Key Findings

| Metric | Finding |
|---|---|
| EMEA titles analysed | 2,223 from 8,807 global titles |
| Top market by volume | United Kingdom with 736 titles |
| Peak content year | 2020 driven by pandemic streaming surge |
| Movies share of EMEA | 72.4% |
| Top genre | International Movies with 996 titles |
| Africa vs Europe cost gap | 3.9% with markets rapidly converging |

---

## Stakeholder Map

This analysis was framed around the following stakeholder needs:

| Stakeholder | Data Need |
|---|---|
| Production Finance Team | Show-level spend, vendor costs, budget trends |
| Public Relations and Government Relations | EMEA market contribution, job creation by country |
| Finance and Strategy | Regional spend trends, year-on-year growth |
| Executive Leadership | Clean visual summary, non-technical reporting |

---

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Python (Pandas, NumPy) | Data cleaning and transformation |
| Matplotlib and Seaborn | Data visualisation |
| SQL via SQLite | Business reporting queries in Jupyter |
| Google Sheets | Stakeholder summary dashboard |
| Jupyter Notebooks via Anaconda | Analysis environment |
| PowerPoint | Executive presentation |

---

## Project Structure

```
netflix-emea-production-finance-analysis/
│
├── Netflix_EMEA_Production_Analysis.ipynb   # Main analysis notebook
├── netflix_emea_summary.csv                 # Modelled financial summary export
│
├── charts/
│   ├── emea_content_volume.png              # Content volume by EMEA market
│   ├── emea_content_type.png                # Movies vs TV Shows breakdown
│   ├── emea_top_genres.png                  # Top 15 genres across EMEA
│   ├── emea_growth_trends.png               # Content growth 2015 to 2021
│   └── emea_production_spend.png            # Modelled production spend
│
├── Netflix_EMEA_Production_Finance_Analysis.pdf    # Executive presentation
└── README.md
```

---

## Notebook Structure

```
1. Introduction
2. Data Loading and Exploration
   2.1 First Look at the Data
   2.2 Dataset Structure and Data Types
   2.3 Missing Values Assessment
3. Data Cleaning
   3.1 Handling Missing Values
   3.2 Fixing Data Types
   3.3 Creating EMEA Country Filter
   3.4 Clean EMEA Primary Country Column
4. EMEA Market Analysis
   4.1 Content Volume by Country
   4.2 Content Type Distribution Across EMEA
   4.3 Content Growth Trends Over Time
   4.4 Top Genres Across EMEA Markets
5. SQL Analysis
   5.1 Setting Up SQL Database in Jupyter
   5.2 Query 1 - EMEA Content Overview by Country
   5.3 Query 2 - Content Growth by Year
   5.4 Query 3 - Content Rating Distribution
   5.5 Query 4 - African Market Performance
6. Financial Modelling
   6.1 Building the EMEA Production Finance Dataset
   6.2 Loading Financial Data into SQL
   6.3 Query 5 - Production Spend by EMEA Market
   6.4 Production Spend Visualisation
   6.5 Query 6 - African Market Cost Efficiency Analysis
7. Insights and Recommendations
   7.1 Summary of Key Findings
   7.2 Strategic Recommendations
   7.3 Conclusion
```

---

## Data Sources

**Content Data:**
Netflix Titles Dataset via Kaggle.
[https://www.kaggle.com/datasets/shivamb/netflix-shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
8,807 titles with country, genre, rating, release year and date added.

**Financial Model:**
Modelled production finance data built on publicly available sources:

- Netflix 2024 Annual Report, total content spend of approximately 17 billion dollars globally
- EMEA accounts for approximately 20% of global content spend per Netflix investor relations reports
- Production cost benchmarks from Variety, Deadline and The Hollywood Reporter
- Vendor spend fixed at 30%, crew cost at 40%, location spend at 15% of production budget per title

Note: This is a simulated financial model for analytical purposes. It demonstrates data modelling methodology using realistic industry benchmarks. In a live environment, analysis would use internal financial systems and proprietary production data.

---

## Key Insights

**1. United Kingdom Dominates EMEA**
The UK accounts for 736 titles, more than double second-placed France, and carries the largest modelled production budget across the region.

**2. 2020 Was the Peak Content Year**
EMEA content additions peaked in 2020, driven by the global pandemic streaming surge. Netflix accelerated acquisitions to serve record subscriber growth across the region.

**3. African Markets Are Undervalued**
The 3.9% cost difference between African and European productions signals that markets are converging. The strategic case for African investment is not cost efficiency. It is audience reach. Africa represents 1.4 billion potential subscribers across a rapidly growing middle class.

**4. Kenya, Ghana and Ethiopia Are Underserved**
Despite significant population size and growing middle class income, these markets are significantly underrepresented in the Netflix EMEA content library relative to Nigeria and South Africa.

**5. Movies Dominate EMEA Output**
72.4% of EMEA content is Movies. International Movies and Dramas are the top genres, reflecting strong demand for locally produced, culturally relevant storytelling.

---

## Strategic Recommendations

1. Accelerate original content investment across Nigeria, South Africa and Kenya
2. Target underserved East and West African markets including Kenya, Ghana and Ethiopia
3. Optimise post-pandemic content scheduling with a data-driven quarterly model
4. Diversify content ratings to broaden subscriber demographics across African markets
5. Consolidate EMEA vendor management to improve cost efficiency at scale

---

## About the Analyst

**Brandon Muchenje**
Data Analyst based in Johannesburg, South Africa

- GitHub: [github.com/brandonmuch](https://github.com/brandonmuch)
- Email: brandonmuchenje01@gmail.com

**Certifications:**
- IBM Data Science Professional Certificate, 10 courses, ACE Accredited
- Microsoft Power BI Data Analyst Professional Certificate, In Progress
- Data Science and Machine Learning, 360 Careers, Udemy
- Google Prompting Essentials

**Education:**
- Postgraduate Diploma in Risk Management, UNISA, Expected March 2027
- Bachelor of Commerce in Law, Cum Laude, Monash University South Africa
