# Iris Dataset – Advanced Data Analysis

A coding practice notebook that explores the classic Iris dataset with Python, focusing on feature engineering, statistical measures and visualization.

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## What's Covered
| # | Task | Technique |
|---|------|-----------|
| 1 | Mean sepal length by species and petal size category | Pivot table, median split |
| 2 | Species with the highest combined sepal length + width mean | GroupBy, `idxmax()` |
| 3 | Percentage of flowers where petal length > sepal width | Boolean masking |
| 4 | Interquartile range (IQR) of sepal length | Quantiles |
| 5 | Species with the highest average sepal length/width ratio | Feature engineering |
| 6 | Species with the highest coefficient of variation for petal width | std / mean |
| 7 | Percentage of flowers where sepal length > 2x petal length | Boolean masking |
| 8 | Species with the highest average petal width | GroupBy + bar plot |
| 9 | Correlation matrix of numeric features | `corr()` + heatmap |
| 10 | Average sepal length by species | GroupBy + bar plot |

## Key Insights
- **Virginica** has the highest combined sepal mean (9.56), the highest sepal ratio (2.23) and the widest petals on average (2.03 cm).
- **Setosa** has the highest coefficient of variation for petal width (0.43), so its petal widths vary the most relative to their size.
- **66.67%** of flowers have a petal length greater than their sepal width.
- **33.33%** of flowers (all setosa) have a sepal length more than twice their petal length.
- The IQR of sepal length is **1.3 cm** (Q1 = 5.1, Q3 = 6.4).
- Petal length and petal width are very strongly correlated (**r ≈ 0.96**).

## How to Run
1. Open the `.ipynb` file in Google Colab or Jupyter Notebook.
2. Run all cells from top to bottom.
