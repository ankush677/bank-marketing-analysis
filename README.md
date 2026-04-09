# 🏦 Bank Marketing Analysis and Prediction

## 📌 Project Overview
This project leverages Machine Learning to enhance the efficiency of bank marketing campaigns. By analyzing a comprehensive dataset of over 40,000 customer interactions, this pipeline predicts whether a client will subscribe to a term deposit. The insights generated allow financial institutions to optimize their telemarketing strategies, reduce operational waste, and focus on high-probability targets.

## 📊 Dataset
* **Source:** UCI Machine Learning Repository - Bank Marketing Dataset (`bank-additional-full.csv`)
* **Size:** 41,188 rows, 21 columns
* **Target Variable:** `y` (Has the client subscribed a term deposit? 'yes' or 'no')

## ⚙️ Tech Stack
* **Language:** Python 3.x
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Machine Learning:** `scikit-learn` (Random Forest Classifier, Label Encoding, Metrics)

## 💡 Key Business Insights (Exploratory Data Analysis)
1. **The "Golden Hour" of Calling:** Calls lasting longer than 8 minutes drastically increase the probability of a successful subscription. Engagement duration is the strongest behavioral predictor.
2. **Economic Sensitivity:** Customer decisions are heavily correlated with macroeconomic indicators, specifically the European interest rates (Euribor 3m) and employment variation rates.
3. **Target Demographics:** Students and retired individuals show the highest conversion rates, while blue-collar workers show the lowest.

## 🤖 Machine Learning Performance
* **Algorithm:** Random Forest Classifier
* **Handling Imbalance:** Applied `class_weight='balanced'` to address the 11% positive class imbalance.
* **Accuracy:** 92%
* **Feature Importance:** The model identified **Call Duration**, **Euribor 3m Rate**, and **Customer Age** as the top 3 drivers of subscription success.

## 📁 Repository Structure
* `Bank_Marketing_Analysis.ipynb`: The complete Jupyter Notebook containing data cleaning, EDA, and model training.
* `bank-additional-full.csv`: The dataset used for analysis.
* `bank_marketing_model.pkl`: The exported Machine Learning model.
* `Images/`: Folder containing the 12 generated visualizations (e.g., Feature Importance, Correlation Heatmap).

## 🚀 How to Run the Project
1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR-USERNAME/Bank-Marketing-Prediction.git](https://github.com/YOUR-USERNAME/Bank-Marketing-Prediction.git)
