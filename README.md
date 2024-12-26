# Data Analysis Portfolio: Layoffs Dataset

This repository demonstrates data analysis and cleaning techniques applied to a layoffs dataset using SQL.

## Key Skills Demonstrated:

* **Data Cleaning:**
    * **Duplicate Removal:** Identifying and removing duplicate rows using `ROW_NUMBER()` and CTEs.
    * **Data Standardization:** Trimming, standardizing industry names, and handling inconsistent date formats.
    * **Missing Value Handling:** Identifying and handling missing values in various columns.
    * **Data Consistency:** Leveraging self-joins to correct inconsistencies in the `industry` column.

* **Exploratory Data Analysis (EDA):**
    * **Descriptive Statistics:** Calculating summary statistics like maximum values, sums, and averages.
    * **Aggregations:** Grouping and summarizing data by company, country, year, stage, and month.
    * **Time Series Analysis:** Analyzing trends in layoffs over time using rolling sums.
    * **Ranking:** Identifying top-performing entities using `DENSE_RANK()`.

* **SQL Fundamentals:**
    * Utilizing `SELECT`, `FROM`, `WHERE`, `GROUP BY`, `ORDER BY`, `JOIN`, `UPDATE`, `DELETE`, and other core SQL commands.
    * Working with data types (e.g., `DATE`, `INT`).
    * Creating and manipulating temporary tables.

## Key Findings (Preliminary):

* The highest number of layoffs occurred in 2023.
* The United States experienced the most significant number of layoffs, followed by India behind that, and Netherlands following.
* Post-IPO company stages experienced the highest number of layoffs.

## Further Exploration:

* Incorporate data visualization techniques (e.g., using libraries like Matplotlib or Seaborn in Python) to enhance the presentation of results.
* Conduct more in-depth industry-level analysis.
* Investigate potential correlations between different variables.
* Perform outlier detection and handle outliers appropriately.
