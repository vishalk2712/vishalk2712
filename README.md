# Vishal Kumar

Business analytics professional completing an MSc in Business Analytics at the University of Birmingham (2026). I bring eight years of experience at Sterlite Technologies in optical fibre cable manufacturing, including six years leading the Sample Product Development team and its type-approval reporting. I focus on data quality, reproducible analysis and decisions that can be traced back to evidence.

Based in Birmingham, UK. Open to business analyst, data analyst, analytics engineering and data quality roles.

## Selected work

### [dbt profitability pipeline](https://github.com/vishalk2712/university_workshop_dbt-bigquery) · dbt, SQL, BigQuery

Runner-up at the Birmingham Business School × dbt Labs Analytics Engineering Hackathon. The project uses a tested staging → intermediate → marts pipeline to answer a product-line margin question. Its fact table has one row per sold item; a SKU-level supply aggregation prevents a join fan-out that would otherwise expand 997 item rows to 5,559. The [repository README](https://github.com/vishalk2712/university_workshop_dbt-bigquery/blob/main/README.md) documents the model lineage, checks, calculations, limitations and recommendation.

### Supplier identity resolution — Wates Group · Python, PySpark, Microsoft Fabric

Client capstone work; code is not public. Profiled a 10,000-record supplier master, designed a precision-first matching policy combining deterministic identifiers with weighted fuzzy scoring, and reduced the manual review queue by **17.3%**. Ran validation over **237,952 rows in 69 seconds** and delivered through Azure DevOps with **42 passing tests**. After testing 144 candidate lineage rules and finding none authoritative, I routed all 1,659 ambiguous groups to human review rather than committing untraceable merges. I also benchmarked Splink and recommended against its extra automated decisions because the available labels could not validate them.

### NHS hospital mortality dashboards · Python, Tableau

Built two dashboards for different audiences from one cleaned dataset. Joined 11 NHS indicator files with four external sources into a **119 × 65** master table at **100% geographic match**. Developed a composite audit-priority score and rejected a deprivation finding after checking for age confounding. View the [NHS Operational Risk Tracker](https://public.tableau.com/views/38156CapstoneSHMIDataViz/NHSOperationalRiskTracker?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) and the [second NHS dashboard](https://public.tableau.com/shared/Y4HXMPHWM?:display_count=n&:origin=viz_share_link) on Tableau Public.

### Employer brand text analytics · R

Applied structural topic modelling, lasso and random forest classifiers to **10,218 Glassdoor reviews**. Test AUC ranged from **0.730 to 0.857**; topic features outranked sentiment features **22 to 1** for distinguishing current from former employees.

## Tools and methods

| Area | Experience |
| --- | --- |
| Analysis and coding | SQL, Python, R, pandas, PySpark, RapidFuzz, pytest |
| Data platforms | dbt, BigQuery, Microsoft Fabric, Git, Azure DevOps |
| Analytics | Data profiling, validation, entity resolution, regression, classification, forecasting |
| Reporting | Tableau, Power BI (DAX), Excel |

## Contact

Birmingham, UK · [LinkedIn](https://www.linkedin.com/in/vishalky10827) · [vishalkumar.vk27@outlook.com](mailto:vishalkumar.vk27@outlook.com)
