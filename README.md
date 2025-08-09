

# Bitcoin Market Sentiment & Historical Trader Data Analysis

## Overview

This project is part of a hiring process assignment that involves analyzing two datasets — **Bitcoin Market Sentiment** and **Historical Trader Data from Hyperliquid** — to derive insights, visualize patterns, and prepare the results for evaluation.
The goal is to **explore the relationship between market sentiment and trader performance** while performing data cleaning, transformation, and analysis.



##  Datasets Used

1. **Bitcoin Market Sentiment Dataset**

   * Columns: `Date`, `Classification` (Fear/Greed)
   * Represents daily sentiment indicators for the Bitcoin market.

2. **Historical Trader Data from Hyperliquid**

   * Columns include:
     `account`, `symbol`, `execution price`, `size`, `side`, `time`,
     `start position`, `event`, `closedPnL`, `leverage`, etc.
   * Contains trade-level details for multiple accounts over time.



##  Approach & Methodology

### 1. Data Loading

* Imported datasets using `pandas`.
* Parsed dates and ensured proper data types.

### 2. Data Cleaning

* Handled missing/null values.
* Removed duplicates.
* Converted timestamps to human-readable formats.
* Standardized column names.

### 3. **Data Merging**

* Merged Bitcoin sentiment data with trader data based on the date.
* Ensured alignment between time zones and formats.

### 4. **Exploratory Data Analysis (EDA)**

* Summary statistics for trade performance metrics.
* Visualized sentiment distribution over time.
* Plotted trader PnL trends against market sentiment.

### 5. **Feature Engineering**

* Extracted new columns like:

  * **Daily PnL per Account**
  * **Win/Loss Trade Count**
  * **Average Leverage**
  * **Sentiment Impact Score**

### 6. **Visualization**

* Used `matplotlib` & `seaborn` for:

  * Heatmaps (PnL correlation with sentiment)
  * Bar charts (Win rate by sentiment type)
  * Time series plots (PnL trends vs. sentiment changes)

### 7. **Insights & Findings**

* Identified patterns where traders performed better/worse during Fear vs. Greed days.
* Measured correlation between sentiment and profit/loss outcomes.



## Tech Stack

* **Python**: Data analysis & processing
* **Pandas**: Data manipulation
* **Matplotlib/Seaborn**: Data visualization
* **Jupyter Notebook**: Code execution & documentation



##  Output

The final results include:

* Cleaned datasets
* Visualizations
* Key insights & recommendations



##  Author

**Samala Laxmi Prasanna**
BTech in Artificial Intelligence & Data Science
GitHub: [https://github.com/22211a7254](https://github.com/22211a7254)
LinkedIn: [https://www.linkedin.com/in/laxmi-prasanna-samala-8bb244259/](https://www.linkedin.com/in/laxmi-prasanna-samala-8bb244259/)

