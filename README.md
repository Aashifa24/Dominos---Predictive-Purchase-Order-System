# Domino’s Predictive Purchase Order System

## Project Overview
This project forecasts **pizza sales** and generates a **weekly ingredient purchase order** for Domino’s. Using historical sales data and pizza-wise ingredient requirements, the system helps optimize **inventory management**, reducing both stockouts and excess inventory.

---

## Documents Included

| File Name | Description |
|---|---|
| **Pizza_sales.csv** | Historical sales data for different pizza types (date-wise). |
| **Pizza_ingredients.csv** | Ingredient details and quantities required for each pizza type. |
| **Predictive_purchase_order_system.ipynb** | Full Jupyter Notebook containing code for data analysis, forecasting, and purchase order generation. |
| **next_week_forecast.csv** | Forecasted daily sales for each pizza for the next 7 days. |
| **final_purchase_order.csv** | Final ingredient purchase order for the next week based on forecasted pizza sales. |
| **dominos_documentation.pdf** | Complete project documentation covering approach, models, EDA, and insights. |

---

## Approach
- **Data Cleaning:** Handled date formats, missing values, and outliers.
- **Exploratory Data Analysis:** Analyzed **sales trends by day, month, and hour**, and identified top-selling pizzas.
- **Model Comparison:** Evaluated ARIMA, SARIMA, Prophet, LSTM, and Random Forest models.
- **Final Model Selection:** **Prophet** was chosen for its accuracy and ability to handle seasonality and holidays.
- **Ingredient Calculation:** Forecasted pizza sales were **converted into ingredient-level demand** using the **Pizza_ingredients.csv** file.

---

## Key Insights
- **Peak Days:** Fridays show the **highest sales**, followed by Saturdays.
- **Peak Hours:** Sales **peak at 12 PM - 2 PM**, with a smaller peak around **6-7 PM**.
- **Top Months:** **January, March, and November** have the highest sales.
- **Top Pizzas:** **Classic Deluxe, Barbecue Chicken, and Hawaiian Pizza** are the best-sellers.
- **Vegetarian pizzas** contribute more to total sales than non-vegetarian pizzas.

---

## Final Outputs
- **next_week_forecast.csv:** Pizza sales forecast for the next week.
- **final_purchase_order.csv:** Weekly ingredient purchase order for the next 7 days.

---

## Tools & Technologies Used
- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Forecasting Libraries (Statsmodels, Prophet, TensorFlow for LSTM)
- Jupyter Notebook

---

## Conclusion
This system enables **accurate demand forecasting** and **efficient ingredient procurement**, ensuring:
- **Better inventory planning.**
- **Reduced stockouts.**
- **Minimized ingredient wastage.**
