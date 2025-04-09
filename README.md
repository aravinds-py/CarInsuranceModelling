# 🧮 Car Insurance Modelling with Python

This project applies statistical modeling techniques to predict the **frequency of car insurance claims** using demographic and vehicle-related features. The main focus is on **count data modeling** using **Poisson regression**, a common approach in actuarial science and risk analysis.

---

## 📊 Dataset Overview

The dataset includes the following features:

- `age_of_driver`: Age of the driver  
- `car_age`: Age of the car  
- `region`: Categorical variable indicating the driver's region (Urban, Rural, Suburban)  
- `number_of_claims`: Target variable representing the number of insurance claims filed  

---

## 🎯 Objective

The objective of this project is to build a **Generalized Linear Model (GLM)** using a **Poisson distribution** to estimate how frequently a driver might file an insurance claim. The insights can assist insurers in:

- Setting premiums
- Managing risk
- Improving pricing strategies

---

## 🛠️ Key Steps

- **Exploratory Data Analysis (EDA)**  
  - Visualizing distributions  
  - Exploring the relationship between features and the number of claims  

- **Data Preprocessing**  
  - One-hot encoding for categorical variables (`region`)  
  - Splitting into training and testing sets (80/20 split)  
  - Handling data types and ensuring numerical compatibility  

- **Model Building**  
  - Fitting a **Poisson GLM** using `statsmodels`  
  - Optional: Negative Binomial model for handling overdispersion  

- **Model Interpretation**  
  - Evaluating statistical significance of predictors  
  - Understanding the impact of age, car age, and region on claims  

---

## 📈 Key Insights

- Older drivers are less likely to file claims.
- Car age shows a weak (non-significant) positive relationship with claim frequency.
- No statistically significant difference in claim frequency across regions.

---

## 📦 Libraries Used

- `pandas`
- `numpy`
- `matplotlib` / `seaborn`
- `statsmodels`
- `scikit-learn` (for train-test splitting)

---

## 🧠 Conclusion

This project demonstrates how Poisson regression can be used to model insurance claim frequency. It highlights the importance of preprocessing categorical variables and evaluating model assumptions in predictive analytics.

---

