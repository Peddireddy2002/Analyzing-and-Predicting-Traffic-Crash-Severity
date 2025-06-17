# 🚦 Analyzing & Predicting Traffic Crash Severity

This project aims to analyze traffic crash data and predict the severity of accidents using machine learning. The insights help traffic authorities, city planners, and emergency responders assess risk, allocate resources, and improve road safety strategies.

---

📊 **Dataset Overview**  
The dataset contains records of traffic accidents including environmental, temporal, and vehicle-related information.

Dataset: https://drive.google.com/file/d/1roN0eod59a6W9fR_FXEZF5N6E2DdxXZs/view?usp=sharing

**Features Include:**  
- **Crash Details**: Crash severity, date & time, location coordinates  
- **Environmental Conditions**: Weather, lighting, road surface  
- **Vehicle & Driver Data**: Vehicle type, number of vehicles involved, driver age/behavior  
- **Target Variable**: Severity category (e.g., Slight, Serious, Fatal)

---

🧹 **Data Preprocessing**  
- **Missing Values**: Imputed or removed using statistical methods  
- **Encoding**: One-hot / label encoding for categorical variables  
- **Normalization**: Scaled numerical features for consistent input  
- **Outlier Handling**: Removed or capped extreme values to reduce noise  
- **Resampling**: Applied SMOTE or class-weight balancing to address severity imbalances

---

📈 **Exploratory Data Analysis (EDA)**  
- Checked distribution of severity classes (imbalanced)  
- Analyzed feature relationships:  
  - Time of day vs. crash severity  
  - Weather and lighting conditions  
  - Road surface types  
- Visualized patterns using heatmaps, barplots, and geospatial mapping  
- Identified key outliers and cleaned affected samples

---

🤖 **Model Building & Evaluation**

**Algorithms Used:**  
- Random Forest  
- Logistic Regression  
- Decision Tree  
- Multi-Layer Perceptron (MLP)

**Evaluation Strategy:**  
- Split data into train/test sets  
- Performance measured using:  
  - Accuracy  
  - Precision / Recall / F1‑Score  
  - Confusion Matrix  
  - ROC-AUC (for binary severity classification)

---

✅ **Results & Insights**  
- **Best Model Accuracy**: ~90% (Random Forest)  
- Random Forest consistently outperformed others across metrics  
- **Important Features** identified:  
  - Time of day, weather conditions, driver age, road surface  
- **Business & Public Impact:**  
  - Enhanced crash severity forecasting  
  - Data informs road safety interventions  
  - Supports emergency response planning

---

🛠️ **Tools & Technologies**  
- Python  
- Pandas, NumPy – Data processing  
- Scikit-learn – Modeling  
- Matplotlib, Seaborn – Visualization  
- Imbalanced-learn (SMOTE) – Handling imbalance  
- Jupyter Notebook – Interactive analysis

---

📚 **Conclusion**  
This project demonstrates how machine learning can effectively predict traffic crash severity. By identifying key risk factors and using interpretable models, stakeholders gain actionable insights to enhance road safety and reduce accident impact.

---

📌 **Future Improvements**  
- Integrate geospatial mapping dashboards for high-risk zones  
- Evaluate advanced models like XGBoost, LightGBM  
- Incorporate time-series or sequential analysis for accident trends  
- Deploy the model as an interactive web app for real-time decision support
