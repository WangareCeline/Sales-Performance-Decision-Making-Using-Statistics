# Sales Data Analysis Project

## 📊 Project Overview
This project demonstrates how statistical methods can be used to analyze sales data and drive business decisions. The analysis covers descriptive statistics, data visualization, sampling concepts, and error analysis using real-world retail sales data.

## 📁 Dataset
- **File:** `statistics_sales_project_data.csv`
- **Contents:** Sales data including revenue, store types, regions, dates, and units sold
- **Time Period:** 3 years of monthly data

## 🔧 Requirements
```python
pandas
matplotlib
```

## 📋 Project Tasks

### Part 1: Descriptive Statistics

#### Task 1.1 – Central Tendency
Calculate measures of central tendency for monthly revenue:
- **Mean:** Average revenue value
- **Median:** Middle value when sorted
- **Mode:** Most frequent revenue value

**Key Insight:** Median is the best representation of revenue as it's not affected by outliers.

#### Task 1.2 – Dispersion
Calculate measures of spread:
- **Range:** Difference between maximum and minimum revenue
- **Variance:** Average squared deviation from mean
- **Standard Deviation:** Square root of variance

**Key Insight:** High standard deviation indicates unstable sales patterns.

#### Task 1.3 – Shape of Distribution
- Plot a histogram of revenue
- Identify distribution shape (normal, positively/negatively skewed)

**Finding:** Revenue distribution is positively skewed (right-skewed).

### Part 2: Data Visualization

#### Visualizations Created:
1. **Line Chart:** Revenue trends over time
2. **Bar Chart:** Total revenue by store type (online vs physical)
3. **Box Plot:** Revenue distribution by region
4. **Scatter Plot:** Units sold vs Revenue correlation

**Insights:**
- Line chart reveals seasonal patterns and trends
- Bar chart shows physical stores outperform online stores
- Box plot identifies regional performance differences and outliers
- Scatter plot examines relationship between units sold and revenue

### Part 3: Sampling Concepts

#### Task 3.1 – Population vs Sample
- **Population:** All data collected over three years
- **Sample:** Subset of data (e.g., one year's data)

#### Task 3.2 – Sampling Bias
- **Bias Type:** Undercoverage bias (only urban stores sampled)
- **Impact:** Results may not generalize to all stores
- **Solution:** Stratified random sampling by location type

### Part 6: Error Analysis

#### Task 6.1 – Statistical Errors
- **Type I Error (False Positive):** Concluding an effect exists when it doesn't
- **Type II Error (False Negative):** Failing to detect a real effect

**Business Example of Type I Error:**
- Testing new merchandise arrangement in 20 stores
- Seeing 15% revenue increase (statistically significant)
- Rolling out to all 500 stores
- **Result:** $2M implementation cost with no actual benefit
