# Machine-Learning-Approaches-for-Predicting-Smart-Grid-Stability
This project focuses on analyzing and predicting smart power grid stability using Machine Learning models, with a deep dive into error analysis and model behavior identification.
# Predictive Analysis of Smart Grid Stability

## 📋 Project Overview
This project focuses on predicting the stability of a smart power grid using machine learning techniques. Using a simulated dataset of a 4-node star system, we compare traditional regression models with advanced ensemble methods and perform a deep dive into error analysis to identify failure patterns.

## 🚀 Key Features
* **Regression Analysis:** Comparing Linear Regression, Decision Trees, and Random Forest.
* **Classification:** Predicting 'Stable' vs 'Unstable' grid states.
* **Systematic Error Analysis:** Investigating residuals, heteroscedasticity, and extreme failure cases.
* **Threshold Optimization:** Tuning classification thresholds to minimize critical False Negatives (missed grid collapses).

## 📊 Key Results
* **Winning Model:** Random Forest achieved an R^2 score of 0.89, significantly outperforming the linear baseline.
* **ROC-AUC:** The classification model reached an AUC of 0.978.
* **Critical Insight:** Errors are most frequent during very short reaction times (tau), suggesting a need for higher-resolution data or targeted model training in dynamic operating regions.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Google Colab / Jupyter Notebook

## 💻 How to Run
1. Clone this repository to your local machine.
2. Open the `Machine_Learning_Approaches_for_Predicting_Smart_Grid_Stability.ipynb` file in Google Colab or Jupyter Notebook.
3. Ensure you have the dataset uploaded or accessible in your environment.
4. Run the cells sequentially to reproduce the analysis and models.
