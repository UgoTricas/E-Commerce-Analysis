# Behavioral Analysis, Customer Segmentation, and Sales Forecasting for an e-commerce Retailer

🇫🇷 [Read the French version](README_fr.md)

This data analysis project focuses on e-commerce sales data to extract insights and forecast future revenues. The analysis covers customer segmentation, product performance, market basket analysis, and time series forecasting using an ARIMA model.

Two notebooks are provided:

* `ecommerce_analysis_en.ipynb` : [English version](ecommerce_analysis_en.ipynb)
* `ecommerce_analysis_fr.ipynb` : [French version](ecommerce_analysis_fr.ipynb)

---

## Data Used

The data can be found at the following link:  
[https://www.kaggle.com/datasets/carrie1/ecommerce-data](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

The dataset consists of sales transactions including invoice dates, products, and prices. It concerns an e-commerce retailer based in the UK over a one-year period between 2010 and 2011, selling its goods internationally.

---

## Analysis Organization

The project is organized into four main parts:

### 1 - Exploratory Sales Analysis
- Data cleaning
- Product performance analysis
- Geographic revenue analysis
- Identification of countries with growing contributions

### 2 - Customer Segmentation
- RFM data preparation
- Optimization of cluster numbers
- Cluster visualization
- Cluster interpretation

### 3 - Market Basket Analysis
- Identification of association rules with the highest lift
- Function to find the top x products frequently bought with a given antecedent

### 4 - Sales Forecasting (ARIMA Model)
- Choice of time granularity
- Stationarity testing
- Determination of optimal ARIMA orders p and q
- Coefficients significance testing
- Residual analysis (Ljung-Box, Jarque-Bera, Breusch-Pagan tests)
- Weekly sales forecasting

---

## Running the Project

### Prerequisites

Install the required libraries via pip:

```pip install -r requirements.txt```

### Run the Notebook

Use Jupyter to run the notebook:

```jupyter notebook ecommerce_analysis_en.ipynb```

