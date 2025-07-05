# Customer Churn Prediction — Interconnect Telecom

---

## Project Overview  
Interconnect, a telecommunications provider, is implementing a predictive analytics solution to forecast customer churn. The goal is to build a reliable machine learning model that identifies clients likely to cancel their services, enabling targeted retention offers such as promotional codes or customized plans.

This project combines customer data from multiple sources to develop a predictive model evaluated primarily by the AUC-ROC metric, ensuring actionable insights for the marketing team.

---

## Interconnect's Services  
Interconnect offers a variety of services including:  
✔️ Landline communication with multi-line connections  
✔️ Internet via DSL or fiber optic cable  
✔️ Internet security packages (DeviceProtection, OnlineSecurity)  
✔️ Technical support options (TechSupport)  
✔️ Cloud storage and backup (OnlineBackup)  
✔️ Streaming services (StreamingTV, StreamingMovies)  
✔️ Flexible contracts: Monthly, 1-year, or 2-year agreements  

---

## Data Description  
The project uses multiple datasets containing key information about customers:  

| File Name       | Description                         |  
|-----------------|--------------------------------------|  
| `contract.csv`  | Contract details per customer       |  
| `personal.csv`  | Demographic and personal information|  
| `internet.csv`  | Internet service details            |  
| `phone.csv`     | Telephone service details           |  

➡️ All datasets are linked via the `customerID` column.

**Target Feature:**  
- Predict churn status: Customers with `'EndDate' = 'No'` are considered active  

---

## Project Steps  

**1. Data Integration**  
- Merge datasets for a complete customer profile  

**2. Exploratory Data Analysis (EDA)**  
- Assess missing values, service usage patterns, and churn distribution  

**3. Data Preparation**  
- Encode categorical variables  
- Handle missing data  
- Scale features as needed  

**4. Model Development**  
- Train machine learning models to predict churn probability  
- Use AUC-ROC as the primary evaluation metric, with Accuracy as a secondary metric  

**5. Model Evaluation & Optimization**  
- Tune hyperparameters and compare model performance  
- Target optimal AUC-ROC performance per the following criteria:  

| AUC-ROC Score  | Project Score (SP) |  
|----------------|--------------------|  
| < 0.75         | 0 SP               |  
| 0.75 - 0.80    | 4 SP               |  
| 0.81 - 0.84    | 4.5 SP             |  
| 0.85 - 0.86    | 5 SP               |  
| 0.87 - 0.87    | 5.5 SP             |  
| ≥ 0.88         | 6 SP (Excellent)   |  

---

## Project Deliverables  
✔️ Clean, structured Jupyter Notebook containing:  
- Code, visualizations, and findings  
- Step-by-step model development  
- Evaluation results and conclusions  

---

## Conclusion  
Predictive modeling for customer churn enables Interconnect to proactively engage clients at risk of leaving, improving retention and revenue stability. This project demonstrates the power of machine learning to enhance customer lifecycle management in the telecom industry.  

## Author  
**Justin Watts** — Data Science Portfolio  
[LinkedIn](https://www.linkedin.com/in/justin-watts-0234562a7)  
[Email](mailto:wattsjay28@gmail.com)  