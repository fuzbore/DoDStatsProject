# DoDStatsProject
Defense Industry Intelligence | Statistical Modeling &amp; Geospatial Analytics  Academic Group Project | October 2026

### Defense Industry Intelligence | Statistical Modeling & Geospatial Analytics

**Academic Group Research Project | October 2026**

**Technologies:** Python, Pandas, NumPy, Statsmodels, SciPy, Matplotlib, Tableau, Statistical Modeling, Geospatial Analytics

Developed a county-level statistical analysis examining how aerospace manufacturing, scientific research and development (R&D), and shipbuilding industry concentrations relate to U.S. Department of Defense (DoD) contract spending.

Leveraged federal contracting, labor market, and demographic data to evaluate economic relationships across **2,125 U.S. counties**, combining statistical modeling, geospatial visualization, and model diagnostics to generate evidence-based insights for public-sector economic development decisions.

**Technical Highlights**

- **Data Preparation & Feature Engineering:** Analyzed a consolidated dataset containing 3,193 county records, filtering missing and nonpositive contract values to construct a 2,125-county regression sample. Applied logarithmic transformations to highly skewed financial and industry-establishment variables while incorporating population, geographic region, and metropolitan classification.
- **Statistical Modeling:** Implemented multivariate Ordinary Least Squares (OLS) regression using Python and Statsmodels to estimate relationships between defense-industry concentrations and average annual DoD contract expenditures for 2022–2024, controlling for demographic and geographic differences.
- **Model Diagnostics & Statistical Inference:** Achieved an in-sample **R² of 0.496 (adjusted R² = 0.494)**. Evaluated regression assumptions using residual diagnostics, Variance Inflation Factors (VIF), hypothesis testing, and 95% confidence intervals, identifying heteroskedasticity as a limitation of conventional statistical inference.
- **Robustness Analysis:** Compared four regression specifications, including industry-only, additional federal-employment controls, and an alternative historical spending outcome, to examine the stability of industry associations under different model assumptions.
- **Geospatial Analytics & Visualization:** Used Tableau to visualize county-level economic and defense-industry patterns, complementing Python-based exploratory analysis and statistical findings.
- **Decision Intelligence:** Identified aerospace and scientific R&D concentrations as having the strongest positive associations with defense contract expenditures in the primary model, providing analytical evidence relevant to regional industry development and investment-prioritization discussions.

**Key Findings**

After controlling for population, metropolitan status, region, and other industry concentrations, a 1% increase in (1 + establishment count) was associated with approximately:

- **0.66% higher DoD spending** for aerospace manufacturing
- **0.67% higher DoD spending** for scientific R&D
- **0.22% higher DoD spending** for shipbuilding

These findings represent statistical associations rather than causal effects and do not establish that adding establishments would increase federal contract awards.

**Outcome:** Demonstrated the ability to translate complex economic datasets into interpretable statistical models, evaluate uncertainty, communicate model limitations, and present quantitative evidence to support strategic decisions.

