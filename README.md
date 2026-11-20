# **Bank Marketing Campaign & Customer Segmentation Analysis**

## **Project Overview**

This project explores the UCI Bank Marketing Dataset to understand customer responses to a bank's term deposit marketing campaigns.

The objective is to identify customer characteristics and campaign-related factors associated with subscription decisions and derive insights that can help improve future marketing strategies.

## **Dataset**

* **Source:** [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing)  
* **File:** `bank-full.csv`  
* **Records:** 45,211  
* **Features:** 17

The dataset contains customer demographics, account information, campaign details and the final subscription outcome.

## **Tools & Technologies**

* Python  
* Pandas  
* NumPy  
* Matplotlib  
* Seaborn  
* Google Colab

## **Data Cleaning & Preparation**

The dataset was examined for missing values, duplicate records, incorrect data types and invalid values.

Key observations and decisions:

* No missing values or duplicate records were found.  
* Data types were appropriate for analysis.  
* `unknown` values were retained as categorical values.  
* The `-1` value in `pdays` was retained as it represents customers who were not previously contacted.  
* Valid extreme values were retained rather than automatically removed as outliers.

No original records were removed or modified.

## **Analysis Performed**

The project includes:

* Overall subscription rate analysis.  
* Customer segmentation by age, job, education and marital status.  
* Account balance comparison between subscribers and non-subscribers.  
* Campaign contact frequency analysis.  
* Communication method and previous campaign outcome analysis.  
* Numerical distribution and correlation analysis.  
* Monthly subscription performance.  
* Multivariable customer segment analysis.

Visualizations include bar charts, count plots, box plots, scatter plots, a correlation heatmap and a monthly trend chart.

## **Key Findings**

* The overall subscription rate was **11.70%**.  
* Customers aged 61+ showed a subscription rate of **42.26%**.  
* Students had the highest subscription rate among job categories at **28.68%**.  
* Customers with a successful previous campaign outcome had a subscription rate of **64.73%**.  
* Cellular communication showed a subscription rate of **14.92%**.  
* Call duration showed a positive correlation with subscription (0.39).  
* March recorded the highest monthly subscription rate at **51.99%**.

## **Business Recommendations**

* Prioritize customer segments with higher observed subscription rates.  
* Improve communication strategies and avoid excessive repeated contacts.  
* Use previous campaign outcomes to identify promising prospects.  
* Evaluate monthly campaign performance when planning future campaigns.

## **Limitations**

* The target variable is imbalanced, with a relatively small proportion of subscribers.  
* Some categorical variables contain unknown values.  
* The analysis identifies associations and does not establish causation.  
* Call duration is available only after a call and cannot directly support pre-call targeting.  
* Monthly comparisons are based on unequal sample sizes.

## **Project Structure**

```
Project Structure
Bank Marketing EDA/
│
├── data/
│   └── raw/
│       └── bank-full.csv
│
├── notebooks/
│   └── Bank_Marketing_EDA.ipynb
│
├── reports/
│   └── Bank_Marketing_Report.pdf
│
├── presentation/
│   └── Bank_Marketing_EDA_Presentation.pdf
│
└── README.md

```

Conclusion

This exploratory analysis identifies customer and campaign characteristics associated with term deposit subscriptions. The findings provide a starting point for more informed customer targeting and marketing campaign planning.

&nbsp;
