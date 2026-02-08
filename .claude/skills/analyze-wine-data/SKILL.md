---
name: analyze-wine-data
description: Perform exploratory data analysis on the Wine dataset. Use when asked to explore, profile, or analyze Wine data.
argument-hint: [dataset or file path]
---

When performing exploratory data analysis, follow these steps:

1. **Load the data** into a polars DataFrame. Identify the target variable (wine class) and feature columns.
2. **Compute summary statistics** including mean, median, std, min, max for each numeric feature.
3. **Check for missing values** and report the count and percentage per column.
4. **Check for duplicate rows** and report how many exist.
5. **Check class balance** and report the count and percentage for each wine class.
6. **Generate distribution plots** for each numeric feature using matplotlib histograms.
7. **Create a correlation matrix** heatmap using matplotlib.
8. **Identify outliers** using the IQR method and log the count per feature.
9. **Log a summary** of key findings using the project's logging format.
10. **Save all plots** to the `output/` directory.

Use polars (not pandas) for all data manipulation. Follow the coding standards in CLAUDE.md.

If $ARGUMENTS specifies a dataset or file path, use that. Otherwise, ask the user what data to analyze.