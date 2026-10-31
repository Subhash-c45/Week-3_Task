


This project analyzes student exam performance using Python, Pandas,
Matplotlib, and Seaborn. It demonstrates data cleaning, outlier detection,
distribution analysis, and correlation analysis.


The sample dataset contains 200 student records with the following features:

- Student_ID
- Gender
- Parental_Education
- Study_Hours
- Attendance
- Previous_Score
- Exam_Score

The dataset was generated for educational purposes and does not represent
real student records.

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## 1. Boxplot: Outlier Identification

![Boxplot](charts/boxplot.png)

### Key Takeaways

- The boxplot displays the distribution and spread of the numerical metrics.
- Potential outliers are identified using the 1.5 × IQR rule.
- Extreme observations are capped at the calculated IQR bounds.

## 2. Distribution Analysis

![Distribution Plot](charts/distribution_plot.png)

### Key Takeaways

- The exam score histogram reveals the distribution of student marks.
- The study hours histogram shows how study time varies across the sample.
- Gender-based distributions allow a descriptive comparison of exam scores.

## 3. Correlation Heatmap

![Correlation Heatmap](charts/correlation_heatmap.png)

### Key Takeaways

- The heatmap summarizes linear correlations between numerical variables.
- Study hours, attendance, and previous scores can be compared with exam scores.
- Correlation indicates association, not causation.

## Data Cleaning and Methodology

1. Inspected missing values and duplicate records.
2. Imputed missing numerical values using column medians.
3. Imputed missing categorical values using the mode.
4. Identified potential outliers using the IQR method.
5. Capped extreme values at the calculated lower and upper bounds.
6. Generated boxplots, distribution plots, and a correlation heatmap.

## Project Files

- `Student_Exam_Performance_Visualizer.ipynb`
- `student_exam_performance_raw.csv`
- `student_exam_performance_cleaned.csv`
- `charts/boxplot.png`
- `charts/distribution_plot.png`
- `charts/correlation_heatmap.png`
- `README.md`

## Conclusion

This project demonstrates how visualization and statistical analysis
can help explore student performance data, identify unusual observations,
understand distributions, and examine relationships between variables.
