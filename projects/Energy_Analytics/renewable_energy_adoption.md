#### Energy Analytics: Modeling Renewable Energy Adoption and CO₂ Emissions
**Objective**:

To assess the relationship between the share of renewables in a country’s energy mix and its national CO₂ emissions, while controlling for GDP, population, and energy intensity. The project also aims to forecast future emissions using time-series modeling.

**Methodology**:

* Conducted exploratory data analysis on global energy trends (2000–2023).
* Built multiple regression models to test the effect of renewable energy adoption on CO₂ emissions.
* Used ARIMA time-series models with exogenous variables (renewables share, GDP) to predict future emissions.
* Tested hypotheses on emissions per GDP, emissions per capita, and moderating effects of energy intensity.

**Tools/Technologies**:

`pandas`, `statsmodels`, `scikit-learn`, `matplotlib`, `seaborn`, `ARIMA`, `OLS Regression`

**Key Findings and Results**:

* A higher share of renewable energy was significantly associated with lower CO₂ emissions, even after accounting for GDP and population.
* Energy intensity moderated this effect: countries with lower intensity saw greater emission reductions from renewables.
* Forecasting models that included renewable share outperformed models that used only historical CO₂ data, demonstrating the predictive value of renewable adoption rates.

🔗 [View Full Project]
