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

🔗 [View Full Project]
