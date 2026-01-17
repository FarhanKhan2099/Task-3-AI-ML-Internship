## **Task 3: Heart Disease Classification (Logistic Regression)**

### **Objective**

To develop a binary classification model capable of predicting the presence of heart disease based on clinical patient attributes.

### **Dataset & Features**

* **Source:** Medical records accessed via `KaggleHub`.
* **Key Indicators:** Age, Sex, Chest Pain Type, Resting BP, Cholesterol, Max Heart Rate, and ECG results.
* **Target:** Binary classification (Presence vs. Absence of heart disease).

### **Methodology**

1. **Exploratory Data Analysis (EDA):** Visualized feature distributions and identified medical correlations using **Seaborn**.
2. **Modeling:** Implemented **Logistic Regression** to estimate the probability of disease.
3. **Validation:** Utilized a standard Train/Test split to evaluate real-world performance.
4. **Metrics:** Beyond accuracy, the model was assessed using a **Confusion Matrix** and **ROC-AUC curves**.

### **Results & Insights**

* **Performance:** Achieved **79% accuracy** and a high **ROC-AUC score of 0.88**, indicating strong discriminatory power.
* **Clinical Accuracy:** The model effectively identified high-risk patients, though some overlap in physiological symptoms led to minor misclassifications.
* **Feature Significance:** Variables such as chest pain type and maximum heart rate emerged as high-impact predictors in the regression coefficients.

### **Conclusion**

Logistic Regression proves to be a reliable baseline for early risk screening in healthcare. While the model demonstrates high predictive value, it is designed to function as a **decision-support tool** for clinicians rather than a standalone diagnostic instrument.

### **How to Run**

1. Install dependencies (`pandas`, `scikit-learn`, `kagglehub`).
2. Open the Jupyter Notebook and execute cells in sequence to download the data and train the model.
