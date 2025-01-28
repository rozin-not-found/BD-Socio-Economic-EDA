# Exploratory Data Analysis (EDA) of Bangladesh's Economic and Demographic Trends

##  Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on a dataset containing economic and demographic indicators of Bangladesh, including **GDP, Inflation Rate, Literacy Rate, Population Growth, and Net Migration Rate**. The primary objective is to analyze key trends, identify correlations, and prepare the data for further regression analysis.

##  Dataset Description
The dataset includes:
- **Year**: The time period of observation
- **GDP**: The Gross Domestic Product (in billion USD)
- **Inflation Rate (%)**: The annual inflation rate
- **Literacy Rate (%)**: The percentage of literate individuals
- **Population Growth Rate (%)**: The annual population growth rate
- **Net Migration Rate**: The net number of people migrating per year

##  Data Cleaning & Preprocessing
To ensure data consistency and accuracy, several preprocessing steps were applied:
1. **Column Name Cleaning**: Removed unwanted characters and spaces.
2. **GDP Value Conversion**: Stripped `"$"` and `"B"`, then converted values to numeric.
3. **Percentage Columns Transformation**: Removed `%` symbols and converted values to decimal format.
4. **Numeric Data Conversion**: Transformed numeric columns stored as strings.
5. **Missing Value Handling**: Filled missing values with column medians.

##  Data Visualization & Insights
###  1. Correlation Analysis
- A **correlation heatmap** was generated to analyze relationships between features.
- A strong correlation was observed between **GDP and Literacy Rate**, suggesting that economic growth influences education levels.

###  2. GDP & Inflation Trends Over Time
- A **line plot** demonstrated fluctuations in GDP and Inflation.
- Significant spikes in **Inflation Rate** often coincide with GDP slowdowns.

###  3. Literacy Rate vs Population Growth
- A **comparative trend analysis** of Literacy Rate and Population Growth was performed.
- While literacy rates increased steadily, population growth exhibited a declining trend.

###  4. Outlier Detection Using Boxplots
- Boxplots helped identify outliers in **GDP, Inflation Rate, and Literacy Rate**.
- Inflation showed the most volatility over time.

##  Key Findings
✔ **GDP growth is positively associated with Literacy Rate improvements.**  
✔ **Inflation volatility affects economic stability, correlating with GDP fluctuations.**  
✔ **The Population Growth Rate is gradually declining, while the Literacy Rate is on the rise.**  
✔ **Outliers in Inflation indicate economic instability in specific periods.**  

## 🚀 Next Steps: Regression Analysis
This EDA lays the foundation for **Regression Analysis**, where we aim to predict GDP based on economic indicators. The cleaned dataset will be used for model training and evaluation.

---

##  Technologies Used
- **Python**: Data handling with `pandas`
- **Seaborn & Matplotlib**: Data visualization
- **NumPy**: Numerical operations
