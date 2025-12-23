# EXPLORATORY-DATA-ANALYSIS-ON-A-TITANIC-DATASET
* Introduction
    This report presents an exploratory data analysis of the Titanic passenger dataset from Kaggle, which contains demographic and travel information for 891 passengers along with their survival status. The         objective   is to understand which factors are most strongly associated with survival using summary statistics and visualizations in Python, Pandas, Matplotlib, and Seaborn.

* Data understanding and cleaning
    The dataset includes features such as passenger class (Pclass), sex, age, number of siblings/spouses (SibSp), number of parents/children (Parch), fare, cabin, and port of embarkation (Embarked). Missing values were mainly present in the Age, Cabin, and Embarked columns, so Age was imputed with the median, Embarked with the most frequent category, and Cabin was dropped due to a very high proportion of missing entries. Duplicate records were checked and removed if present to ensure data quality.

* visualizations
    A key visualization in this analysis is a Seaborn count plot showing passenger survival by gender, which clearly highlights the strong impact of sex on survival outcomes. In the chart, the x‑axis represents gender (male and female), the bars are split by survival status, and the heights show passenger counts, making it easy to see that a much larger proportion of women survived compared to men. This visual evidence supports the conclusion that gender was one of the most important factors influencing survival on the Titanic.

* Tech Stack: Python, Pandas, Matplotlib, Seaborn, google colab

