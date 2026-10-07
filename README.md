# Week-3-Statistical-Analysis-of-iris-flower-Python
Statistical analysis of Iris flower data using Python, including data cleaning, hypothesis testing, Welch’s ANOVA, Games-Howell post-hoc analysis, confidence intervals, and visualizations.
This project focuses on statistical analysis and hypothesis testing using Python with the Iris flower dataset. The main objective is to determine whether the mean petal length differs significantly among three Iris species: Iris-setosa, Iris-versicolor, and Iris-virginica.

The analysis follows a complete scientific data analysis workflow, beginning with data inspection, cleaning, missing-value handling, and duplicate detection. Descriptive statistics and visualizations were then used to understand the distribution of petal length across the three species.

Statistical assumption testing was performed using the Shapiro–Wilk test for normality and Levene's test for equality of variances. Since the variance assumption was not satisfied, Welch's ANOVA was selected for comparing the group means. A Games–Howell post-hoc test was then performed to identify which species pairs showed significant differences. The analysis also includes 95% confidence intervals and Hedges' effect sizes to evaluate both statistical significance and the magnitude of the differences.

The results showed highly significant differences in petal length among all three species. Python libraries including Pandas, NumPy, SciPy, Pingouin, and Matplotlib were used throughout the project. This project demonstrates practical skills in scientific data analysis, statistical testing, visualization, interpretation, and reproducible Python-based research.
