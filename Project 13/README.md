# Taxi Order Prediction – Sweet Lift Taxi

---

## Project Overview  
Sweet Lift Taxi has collected historical data on taxi orders at airports. To attract more drivers during peak hours and improve service efficiency, this project aims to develop a machine learning model that predicts the number of taxi orders for the next hour.

The goal is to ensure that the model's Root Mean Squared Error (RMSE) on the test set does not exceed **48**.

---

## Project Objectives  
✔️ Load and resample historical taxi order data by one-hour intervals  
✔️ Conduct exploratory data analysis to understand trends and patterns  
✔️ Train and evaluate multiple models with various hyperparameters  
✔️ Use 10% of the initial dataset as a test sample for model validation  
✔️ Select the best-performing model based on RMSE metric  
✔️ Provide conclusions on model performance and practical use  

---

## Data Description  
The dataset is provided in the following file:  

`/datasets/taxi.csv`  

**Key Column:**  
- `num_orders` — Number of taxi orders placed within a time period  

**Resampling Requirement:**  
The dataset should be resampled by **one-hour intervals**, summing the total number of orders within each hour.

---

## Project Steps  

**1. Data Loading & Resampling**  
- Download and resample the dataset by hourly intervals  

**2. Exploratory Data Analysis (EDA)**  
- Visualize trends, distributions, and seasonality patterns  

**3. Data Preparation**  
- Handle missing values if present  
- Feature engineering for time-based predictions  

**4. Model Development**  
- Train multiple models with different hyperparameter settings  
- Consider options like linear models, tree-based algorithms, and others  

**5. Model Evaluation**  
- Use RMSE as the primary evaluation metric  
- Ensure RMSE on the test sample does not exceed **48**  

**6. Findings & Conclusion**  
- Summarize key insights from model performance  
- Provide recommendations based on results  

---

## Project Evaluation Criteria  

✅ Followed all project steps as outlined  
✅ Data prepared effectively and resampled correctly  
✅ Considered multiple models with different hyperparameters  
✅ Avoided unnecessary code duplication  
✅ Presented clear findings and insights  
✅ Maintained clean, well-structured code  

---

## Conclusion  
Accurately forecasting the number of taxi orders allows Sweet Lift Taxi to manage driver availability more effectively, especially during high-demand periods. This project demonstrates the use of time series modeling to improve service efficiency and support business decision-making.  

## Author  
**Justin Watts** — Data Science Portfolio  
[LinkedIn](https://www.linkedin.com/in/justin-watts-0234562a7)  
[Email](mailto:wattsjay28@gmail.com)  