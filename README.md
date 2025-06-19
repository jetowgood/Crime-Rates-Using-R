# 📊 Crime Rates in the US
This project explores violent crime rates across the United States using the USArrests dataset. The data contains statistics for all 50 US states from 1973, tracking rates per 100,000 residents for Murder, Assault, Rape, and Urban Population.

## 🧠 Objective
To determine whether there is a correlation between different types of violent crimes:

- Rape vs. Murder

- Murder vs. Assault

- Assault vs. Rape

## 📁 Dataset
Source: USArrests dataset (built-in R dataset)

### Variables:

- Murder: Murder arrests (per 100,000)

- Assault: Assault arrests (per 100,000)

- Rape: Rape arrests (per 100,000)

- UrbanPop: Percent urban population

## 📊 Visualizations
### 📦 Boxplots
Boxplots were created for each violent crime variable to understand distribution and detect outliers. Urban population was excluded from the analysis due to lack of relevance to the core research question.

### 🔁 Correlation Analysis
Scatter plots with linear regression lines were created to visualize relationships between:

- Murder & Rape

- Assault & Murder

- Assault & Rape

These visualizations suggest a positive correlation between all crime pairings.

### 📈 Linear Regression
Linear models were used to quantify the strength of correlation using R-squared values:

Crime Pair	R² Value
- Rape vs Murder	0.318
- Assault vs Murder	0.643
- Assault vs Rape	0.443

## 🧪 Tools & Libraries
Language: R

Libraries: plotly, base R functions (lm, summary, boxplot)

## ✅ Conclusion
All three crime types show positive linear relationships.

The strongest correlation exists between Assault and Murder.

Results assume linearity, no hidden variables, and normal distribution.
