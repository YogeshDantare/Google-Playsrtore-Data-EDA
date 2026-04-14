# Google Play Store — EDA

Exploratory data analysis on 10,000+ Google Play Store apps across 33 categories.

---

## Objective
To clean, explore, and extract meaningful insights from the Google Play Store dataset — understanding what drives app ratings, installs, and pricing patterns.

---

## Roadmap
1. Data Cleaning - duplicates, missing values, type conversions
2. Univariate Analysis - distributions of Rating, Reviews, Installs, Price, Size
3. Categorical Analysis - Category, Type, Content Rating breakdowns
4. Correlation Analysis - relationships between numeric features
5. Category Deep Dive - top categories by installs and rating

---

## Libraries used
1. numpy
2. pandas
3. matplotlib.pyplot
4. seaborn
---

## Insights
- **Rating** is left-skewed , most apps cluster at 4.0–4.5, median (4.3) is a better measure than mean (4.19)
- **93% of apps are free** - Free and Paid behave as separate populations
- **Reviews and Installs** follow a power law and require log transformation before any analysis
- **Reviews - Installs** correlation is r = 0.957  nearly identical signals, never use both in the same model
- **Price predicts nothing**  near-zero correlation with all other features
- **FAMILY and GAME** make up 31% of all apps and dominate dataset-wide averages
