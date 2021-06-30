# Extracting & Visualization Stocks data


- In this project, we are going to extract and visualize stocks prices and revenues over a period of time.

- This data and visualizations will help decision-makers to make more accurate data-driven financial decisions related to selling, purchasing, shortselling and investing in these stocks.

- Our focus will be on **Tesla(TSLA)** and **GameStop(GME)**.



# **Environment** & **Packages**


| Package Name | Functionality or Usage purpose |
|---------------|-------------------------------|
| Pandas        | For data handling and manipulation|
| yfinance |  A package for extracting stocks financial data |
| plotly.graph_objects        | Adding interactive graphical objects|
| plotly.subplots  | Adding subplots to interactive dashboards    |



# **Data Sources**

- [TSLA-Revenues](https://www.macrotrends.net/stocks/charts/TSLA/tesla/revenue): A data scource containing Tesla Quarterly Revenue
(Millions of US $)

- [GME_Revenues](https://www.macrotrends.net/stocks/charts/GME/gamestop/revenue): A data scource containing GME Quarterly Revenue
(Millions of US $)

- Prices-Data: Collected through **yfinance API**, which is a reliable method of gathering financial data.



# **Data Cleaning**

- Dropping null values from TSLA_revenues_data.
- Removing dollar signs and thousands separators from TSLA_revenues_data. 
- Removing dollar signs and thousands separators from GME_revenues_data.
- Editing data types for both TSLA & GME data to be relevant for our analysis:
  - Changing the date column to datetime.
  - Changing the revenues column to float. 


# **Results**


- An interactive dashboard that conveys the trends of TSLA's prices (US $) and revenues (Millions of US $).
![TSLA](https://github.com/Ayman947/Analyzing-Stocks-TSLA-GME/blob/main/TSLA_Plotly.PNG)




- An interactive dashboard that conveys the trends of GME's prices (US $) and revenues (Millions of US $).
![GME](https://github.com/Ayman947/Analyzing-Stocks-TSLA-GME/blob/main/GME_Plotly.PNG)

