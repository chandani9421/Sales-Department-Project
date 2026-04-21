# Sales-Department-Project

## 📌 Overview

This project focuses on analyzing sales data to uncover insights that can enhance sales strategies and performance

## 📂 Project Structure

```text
├── Sales_Department_Png/             # Visualizations generated during analysis
├── store.csv                         # Dataset containing store information
├── train.csv                         # Dataset containing sales transaction records
├── Sales_Project.ipynb               # Jupyter Notebook with analysis and findings
└── README.md                         # Project documentation
```

## 📊 Datase

The project utilizes two primary datases:

1 store.csv: Contains information about different stores, including:

 * Store ID: Unique identifier for each stoe.
 * Type: Categorical variable indicating the type of stoe.
 * Size: The physical size of the stoe.

2 train.csv: Includes historical sales data with features such as:

 * Store ID: Reference to the stoe.
 * Date: The date of the sales recod.
 * Weekly Sales: Sales figures for the given wek.
 * Holiday Flag: Indicator of whether the week includes a holidy.
 * Temperature: Average temperature for the wek.
 * Fuel Price: Cost of fuel during the wek.
 * CPI:Consumer Price Indx.
 * Unemployment: Unemployment rate during the wek.

## 🚀 Installation

### 1️⃣ Clone the repository:

```bash
https://github.com/chandani9421/Sales-Department-Project
```

### 2️⃣ Install dependencies:

Ensure you have the following Python packages installed:

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

You can install them using pip:

 ```bash 
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 🔍 Methodology

### 1. Data Preprocessing
 * Handling Missing Value: Identified and addressed any missing data in the dataets.
 * Feature Engineerin: Created new features to better capture temporal patterns, such as extracting month and year from the Date feld.
 * Data Mergin: Combined store.csv and train.csv datasets based on Store ID to consolidate informaion.

### 2. Exploratory Data Analysis (EDA)
 * Sales Trends Analysi: Examined sales patterns over time to identify seasonal effects and trnds.
 * Impact of Holiday: Analyzed how holidays influence weekly sales figres.
 * Correlation Analysi: Explored relationships between sales and external factors like Temperature, Fuel Price, CPI, and Unemploymnt.

### 3. Predictive Modeling
 * Sales Forecastin: Developed regression models to predict future sales based on historical data and external variales.
 * Model Evaluatio: Assessed model performance using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RSE).


## 📊 Visualizations
Here are some visualizations from the project:

<img width="831" height="468" alt="groupby month customer" src="https://github.com/user-attachments/assets/e8001618-70ea-44d1-8dca-63c41060480b" /><br>
<img width="840" height="468" alt="groupby month" src="https://github.com/user-attachments/assets/285320ec-4b5c-48cc-96b7-62e55f90c94e" /><br>
<img width="1670" height="1778" alt="heatmap" src="https://github.com/user-attachments/assets/9e4e28bf-f134-4812-8579-b73b4cd46888" /><br>
<img width="988" height="590" alt="sales_predictions" src="https://github.com/user-attachments/assets/b1013656-697e-4467-bebd-1e24ec376f7a" /><br>
<img width="1624" height="833" alt="sales_train_all_df pivot_table" src="https://github.com/user-attachments/assets/5b9529e1-f8e0-4394-bcaf-d29964c9839b" /><br>
<img width="1632" height="1604" alt="sales_train_df_hist" src="https://github.com/user-attachments/assets/cb134bc9-6d67-44e4-aed5-08619dd03b99" /><br>
<img width="1606" height="1604" alt="store_info_df hist" src="https://github.com/user-attachments/assets/4575a2ea-d098-40c4-95fb-9512feeccc8b" /><br>

## 🛠️ Technologies Used

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* Jupyter Notebook

## 📌 Future Improvements
* Advanced Time Series Moels: Implement models like ARIMA or Prophet for more accurate sales foreasting.
* Incorporate Additional ata: Integrate external data sources such as economic indicators or competitor pricing to enhance model perfrmance.
* Interactive Dashbords: Develop dashboards using tools like Tableau or Power BI for real-time sales monitoring and decision upport.








