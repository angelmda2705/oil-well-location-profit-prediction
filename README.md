# oil-well-location-profit-prediction
## 📊 Project Overview

OilyGiant, an oil extraction company, wants to identify the best locations to drill 200 new oil wells. Since drilling operations are extremely expensive, the company needs a data-driven approach to maximize profit and minimize financial risk.

This project uses machine learning and statistical analysis to predict oil reserves and determine the most profitable region for drilling new wells.

---

## 🎯 Business Objective

The goal is to build a predictive model that helps OilyGiant:

- Estimate oil reserves in potential wells
- Select the 200 wells with the highest predicted reserves
- Identify the region with the highest expected profit
- Evaluate financial risk using bootstrapping

---

## 📂 Dataset

The dataset contains geological data from three different oil regions.

Each oil well includes:

- Well identifier
- Geological characteristics
- Estimated oil reserves

These features are used to train regression models that predict oil production.

---

## ⚙️ Methodology

The project follows a structured Data Science workflow:

1. **Data Exploration**
   - Understanding dataset structure
   - Identifying patterns and distributions

2. **Data Preparation**
   - Feature selection
   - Train-test split

3. **Model Training**
   - Linear Regression model used to predict oil reserves

4. **Profit Calculation**
   - Selection of the top **200 predicted wells**
   - Estimation of potential regional profit

5. **Risk Analysis**
   - Bootstrapping applied to simulate profit distributions
   - Calculation of **confidence intervals and loss probability**

---

## 📈 Model Evaluation

Model performance was evaluated using:

- **RMSE (Root Mean Squared Error)**  
  Measures prediction accuracy of the regression model.

---

## 💰 Profit & Risk Analysis

Bootstrapping was used to simulate multiple scenarios of well selection in order to estimate:

- Average expected profit
- Confidence intervals
- Probability of financial loss

This approach helps identify the **most profitable region while controlling financial risk**.

---

## 🧠 Key Insights

- Machine learning can significantly improve decision-making in oil exploration.
- Bootstrapping allows risk estimation in uncertain environments.
- Selecting wells based on predicted reserves maximizes expected profit.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## 👨‍💻 Author

Angel Mendiola Del Angel  
Industrial Engineer | Data Scientist
