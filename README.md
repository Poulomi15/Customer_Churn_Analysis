# 📊 Customer Churn Analysis - Banking Sector

A Python-based data science project focused on analyzing customer churn in the banking industry. Through Exploratory Data Analysis (EDA), this project reveals patterns and relationships between customer profiles, behaviors, and churn outcomes.

---

## 📌 Project Goal
To pinpoint the main drivers of customer attrition in a bank using data visualization and statistical techniques, supporting banks in making informed, data-backed strategies to minimize customer loss.

---

## 📁 Dataset Information
- **File Name:** `Bank_Churn.csv`
- **Source:** Publicly available, simulated bank customer dataset
- **Features:**
  - `CreditScore`
  - `Geography`
  - `Gender`
  - `Age`
  - `Tenure`
  - `Balance`
  - `NumOfProducts`
  - `HasCrCard`
  - `IsActiveMember`
  - `EstimatedSalary`
  - `Exited` *(Target variable: 1 = Churned, 0 = Retained)*

---

## 📚 Tools & Libraries
- **Programming Language:** Python 🐍
- **Libraries:** 
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scipy

---

## 🔍 EDA Workflow
- Imported and cleaned the dataset
- Handled missing data and validated data types
- Visualized churn statistics
- Studied demographic influences (Age, Gender, Geography)
- Examined customer engagement (Tenure, Product Holdings, Account Activity)
- Investigated financial variables (Credit Score, Balance, Salary)
- Built a correlation matrix using Pearson’s method

---

## 🎯 Major Findings
- Customers aged 40 and above exhibited higher churn rates.
- German customers were more likely to churn compared to others.
- Tenure, number of products held, and account balance strongly correlated with churn risk.
- Estimated salary and credit score had lesser influence on churn decisions.

---

## 📈 Data Visualizations
- Bar and pie charts for churn overview
- Countplots and histograms to analyze demographics
- Boxplots highlighting behavioral and financial trends
- Correlation heatmap for feature relationships

---

## ✅ Conclusion
The analysis successfully identified critical customer segments at higher risk of leaving, equipping banks with insights to design effective retention strategies.

---

## 📌 Future Enhancements
- Build predictive Machine Learning models for churn forecasting
- Integrate customer feedback and transactional data
- Perform customer segmentation based on churn risk profiles

---

## 🙋‍♂️ About the Author
**B Devendranadh Venkat**  
Student | Aspiring Data Scientist  
Course: *Data Science Toolbox with Python (INT375)*

---

## 📄 License
This project is licensed under the [MIT License](LICENSE). Feel free to use and adapt it!

