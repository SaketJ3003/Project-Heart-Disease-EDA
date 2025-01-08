# Data Visualization on Heart Disease Dataset

This project focuses on using **data visualization** to explore and understand patterns, trends, and relationships in a heart disease dataset. Visualization tools such as scatter plots, line plots, bar plots, and histograms are employed to extract meaningful insights from the data.

---

## Prerequisites
Before running this project, ensure the following Python libraries are installed:
- `Pandas`
- `Seaborn`
- `Matplotlib`

---

## Project Overview

**Why Data Visualization?**
Data visualization is a powerful way to identify patterns and relationships within a dataset and communicate findings effectively. Choosing the right visualization type can significantly enhance the understanding of the dataset and its implications.

### Common Visualization Types:
1. **Scatter Plots**: Explore relationships between two numerical variables, e.g., age vs. cholesterol levels.
2. **Line Plots**: Visualize trends over time, e.g., changes in blood pressure.
3. **Bar Plots**: Compare categorical data, e.g., heart disease prevalence across age groups.
4. **Histograms**: Understand the distribution of numerical variables, e.g., cholesterol level distribution.

---

## Project Structure

The project is divided into six parts:

### 1. Heart Disease EDA - Age (DistPlot)
- **Goal**: Analyze the distribution of age within the dataset using a distribution plot (DistPlot).
- **Tool**: Seaborn `distplot` function to show the spread of ages and identify potential outliers.

### 2. Heart Disease EDA - Categorical Columns (Pie Charts)
- **Goal**: Visualize proportions of categorical variables such as gender or heart disease presence.
- **Tool**: Matplotlib pie charts to represent category distributions clearly.

### 3. Heart Disease EDA - ViolinPlot
- **Goal**: Analyze the distribution and variability of numerical data across different categories.
- **Tool**: Seaborn `violinplot` to highlight spread, density, and comparison within groups.

### 4. Heart Disease EDA - Correlation (HeatMap)
- **Goal**: Understand the correlation between numerical variables in the dataset.
- **Tool**: Seaborn `heatmap` to visually represent relationships between variables.

### 5. Heart Disease EDA - Correlation (PairPlot)
- **Goal**: Explore pairwise relationships between multiple numerical variables.
- **Tool**: Seaborn `pairplot` to create a grid of scatter plots.

### 6. Heart Disease EDA - Correlation (JointPlot)
- **Goal**: Analyze the relationship between two variables in more detail.
- **Tool**: Seaborn `jointplot` to combine scatter plots and histograms for a comprehensive view.

---
