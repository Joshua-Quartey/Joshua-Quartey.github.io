## Joshua Quartey | Data Science &amp; Analytics Portfolio
### Introduction
I’m a graduate student in the Master of Data Science and Analytics program at the University of Calgary, specializing in Data Science.

My academic background combines computer science with applied research in energy consumption, urban development, and health data.

I’m passionate about using data to solve real-world problems and aim to build a career in data science focused on impactful, evidence-based decision making.
<a href="assets/files/Resume.pdf" target="_blank">View my resume (PDF)</a>

### Contact Information
* 📧 Email: jquartt@gmail.com
* GitHub: github.com/joshua-quartey
 
### Project Showcase
#### Urban & Housing Analytics: Understanding Urban Development Patterns in Edmonton

**Objective**:

To explore how construction activity—measured through building permits and construction value—reflects broader trends in zoning policy, urban development, and changing property values across Edmonton from 2009 to 2023.

**Methodology**:

* Analyzed City of Edmonton building permit data to track construction volume and investment by neighborhood and permit type.
* Investigated correlations between construction activity and property assessment values to assess patterns of reinvestment.
* Integrated contextual policy changes (e.g., 2020 City Plan, 2024 Zoning Bylaw) to frame development shifts.

**Tools/Technologies**:

`pandas`,  `Tableau`, `seaborn`, `geopandas`

**Key Findings and Results**:

* A small number of neighborhoods (e.g., Glenora, Oliver, and Garneau) accounted for a disproportionately large share of high-value permits.
* Older neighborhoods with infill potential showed rising permit activity, suggesting gentrification trends.
* Redevelopment and construction value were unevenly distributed across the city, raising concerns about equitable investment and accessibility.

🔗 [View Full Project]("projects/Urban_Housing_Analytics/Understanding_Urban_Development_Patterns_in_Edmonton.ipynb")


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

🔗 [View Full Project]("projects/Energy_Analytics/Modeling_Renewable_Energy_Adoption_and_CO₂_Emissions.ipynb")

#### Energy Analytics: Alberta Electricity Load Pattern Analysis

**Objective**:
To analyze Alberta’s hourly electricity demand data using unsupervised and supervised learning approaches in order to (1) extract dominant daily load patterns, (2) cluster days into operational types, and (3) predict high-demand days based on early-morning signals.

**Methodology**:

* Applied Principal Component Analysis (PCA) to reduce daily 24-hour load curves into 2–3 key components.
* Used k-means clustering to group days into distinct operational “day types” (e.g., winter peaks, weekend troughs).
* Built decision tree and logistic regression models to predict whether a given day would be in the top 10% of demand using only early morning load values and day-of-week indicators.
* Extracted interpretable decision rules to support operational forecasting.

**Tools/Technologies**:

`scikit-learn`, `pandas`, `matplotlib`, `seaborn`, `PCA`, `k-means`, `logistic regression`, `decision trees`

**Key Findings and Results**:

* Two principal components captured the majority of variation in daily load curves, revealing winter-heavy and weekday/weekend usage differences.
* Cluster analysis identified meaningful day types such as “cold-morning peaks” and “weekend valleys.”
* Early-morning signals were highly predictive: the classification model achieved strong accuracy in identifying high-demand days.
* Extracted rules can help grid operators trigger early warnings, improving grid efficiency and reliability.

🔗 [View Full Project]("projects/Energy_Analytics/Alberta_Electricity_Load_Pattern_Analysis.ipynb")




### Technical Skills Inventory

#### Data Visualization & Reporting

* **Tools**: Tableau, Power BI, Excel, matplotlib, seaborn, ggplot2
* **Skills**: Dashboard creation, trend analysis, dual-axis plotting, partition/ordinal plots, geospatial mapping with `geopandas`

#### Statistical Analysis & Modeling

* **Techniques**: Linear/Logistic Regression, ANOVA, Hypothesis Testing, Time Series Forecasting (ARIMA), PCA
* **Tools**: `statsmodels`, `R` (`base`, `MASS`, `caret`), `scikit-learn`, `pandas`, `NumPy`

#### Machine Learning & Predictive Modeling

* **Techniques**: Decision Trees, K-means Clustering, Logistic Regression, LDA, Classification Models
* **Libraries**: `scikit-learn`, `caret`, `pandas`, `NumPy`
* **Applications**: Forecasting high electricity demand

#### Data Wrangling & Processing

* **Tools**: `pandas`, SQL (MariaDB), Excel
* **Skills**: Data cleaning, merging/joining datasets, handling missing values, feature engineering

#### Domain Expertise & Applied Contexts

* **Domains**: Urban Development, Energy Systems, Environmental Modeling
* **Strengths**: Translating domain problems into analytical solutions, integrating policy and data

  
### Soft Skills Inventory
* Collaborative team player with experience using Git for version control and seamless project coordination
* Time management & task prioritization
* Project planning & execution
* Communication & data storytelling
* Attention to detail
* Research framing & hypothesis development
* Adaptability in fast-paced analytical work



### Education and Coursework

**Master of Data Science and Analytics**

*University of Calgary, Alberta* — *Expected Dec 2025*
• Specialization: Business Analytics and Applied Machine Learning
• Relevant Coursework:
- Working with Data and Visualization
- Statistical Data Analysis
- Statistical Modeling with Data
- Big Data Management
• Participating in the Science Co-op Internship Program for hands-on industry experience



### Blog 
#### Posts
* [Addressing Class Imbalance in High-Demand Electricity Load Prediction
]("Blog/posts/2025-06-13-class-imbalance-electricity.md")
