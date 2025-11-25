# AVISHKAAR-Virtual-Hackathon


# ***THEME: AGRICULTURE AND FOOD TECHNOLOGY***


### **PROBLEM STATEMENT:** 

*Many farmers still rely on middlemen to sell their produce, losing a major share of their income. They lack a simple and transparent way to connect directly with buyers, limiting fair pricing and market access*


**DESCRIPTION:**

*Farmers often face challenges in accessing markets, leading to lower income due to middlemen. This gap restricts their ability to sell produce at fair prices.Create a mobile application that connects farmers directly with consumers and retailers. The app should include features for listing produce, negotiating prices, and managing transactions, thereby reducing dependence on intermediaries*


-----



### **Medthology** -

* Data Collection: Gather historical crop prices across markets, districts, and states along with agronomic features (soil, irrigation, weather, yield).

* Data Preprocessing: Clean data, handle missing values, remove duplicates, and standardize dates.

* Price Forecasting: Use time-series models (e.g., Prophet) with relevant regressors to predict next 7–15 days crop prices; evaluate with R² and MAPE.

* Forecast Storage & Visualization: Store predictions in structured tables; display interactive charts for selected crop, district, and markets.

* LLM-Based Market Recommendation: Feed forecast data to an LLM to suggest optimal nearby markets for maximum revenue.

* User Interface & Deployment: Provide a user-friendly interface (Gradio/notebook) for farmers to access forecasts, graphs, and AI-driven market suggestions
