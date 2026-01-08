# DATA-CLEANING-AND-DATA-PREPROCESSING-PROJECT
"Data cleaning and EDA project on Titanic (CSV) and Financial (XLSX) data. Features advanced Titanic visualizations (Pairplots, Jointplots, Boxplots and many more) and financial data integrity using Forward Fill (ffill), Mean Imputation, and categorical encoding with pd.get_dummies."
This project contains my data cleaning and Exploratory Data Analysis (EDA) work using *Jupyter Notebook*. I processed two different types of datasets to demonstrate how to handle various data challenges.

## 🛠️ Datasets & Techniques

### 1. Titanic Dataset (titanic.csv)
*Goal:* Prepare passenger data for analysis.
* *Profiling:* Used .head(), .tail(), and .describe() to inspect the data.
* *Missing Values:* Used .isna().sum() and *Heatmaps* to find null values.
* *Imputation:* Filled missing Age values with the *Mean* and used *'Unknown'* for missing text data.
* *Encoding:* Applied pd.get_dummies to convert categories into numbers.
* *Visualizations:* Created *Boxplots, **Histplots, **Countplots, **Pairplots, and **Jointplots* to find patterns.

### 2. Financial Sample (Financial_sample.xlsx)
*Goal:* Clean business data and ensure logical consistency.
* *Logical Filling:* Used *Forward Fill (ffill)* to handle missing sequential values.
* *Data Integrity:* Used .describe() to verify financial figures and identified outliers.
* *Cleaning:* Dropped unnecessary columns and handled missing values to ensure the data is ready for reporting.

---

## 🖥️ Project Environment
* *Platform:* Jupyter Notebook
* *Libraries:* Numpy, Pandas, Matplotlib, Seaborn

## 📂 How to view my work
1. Click on the .ipynb files in this repository.
2. GitHub will automatically render the notebook so you can see my code and the plots (Heatmaps, Boxplots, etc.) directly in your browser.
