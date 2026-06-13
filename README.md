Titanic Dataset — Univariate Exploratory Data Analysis (EDA)

In this notebook, I performed a complete univariate exploratory data analysis on the famous Titanic dataset containing information about 891 passengers.

What I covered:
- Loaded and explored the dataset using shape, dtypes, and info
- Detected missing values — Age (177), Cabin (687), Embarked (2)
- Analyzed numeric columns (Age, Fare) using descriptive statistics, histograms, boxplots, and skewness interpretation
- Analyzed categorical columns (Survived, Pclass) using value counts and bar charts
- Identified class imbalance in the Survived column (61.6% not survived vs 38.4% survived)
- Detected natural outliers in Age column (passengers above 65)

Key Findings:
- Age is approximately normally distributed with slight right skew (+0.39)
- Fare is heavily right skewed (skewness +4.8) — log transformation needed before ML
- Majority of passengers traveled in 3rd class (55%)
- Mild class imbalance exists in target column (Survived)

Libraries used: Pandas, Matplotlib, Seaborn

