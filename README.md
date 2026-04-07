## Employee Attrition Analysis

### Objective
Analyze employee data to identify key factors influencing employee performance and support data-driven HR decisions.

### Dataset
- Source: Kaggle  
- Contains employee demographic, job, satisfaction, and performance-related variables

---

### Key Visualizations & Insights

#### Gender Distribution
![Gender](gender_distribution.png)
- Workforce shows higher representation of male employees

#### Marital Status Distribution
![Marital](marital_distribution.png)
- Majority of employees are married, followed by single employees

#### Age vs Income
![Age Income](age_income.png)
- Employee income shows a positive relationship with age and experience, indicating structured career progression but also highlighting income disparity within    similar age groups
- Significant variation exists within the same age group  

#### Job Involvement vs Satisfaction
![Involvement](involvement_satisfaction.png)
- Higher job involvement is associated with higher job satisfaction  
- Most employees fall in moderate to high levels  

#### Age vs Performance (with Experience)
![Performance](age_performance.png)
- Performance tends to improve with experience and age  
- Higher-rated employees show greater variability in experience

### Predictive Modeling

To enhance the analysis, machine learning models were applied to predict employee performance.

#### Models Used
- Random Forest  
- XGBoost  
- Gaussian Naive Bayes  
- Decision Tree  

#### Model Performance
- Random Forest achieved the highest accuracy of **86.12%**, making it the most reliable model  
- XGBoost followed closely with an accuracy of **84.69%**  
- Gaussian Naive Bayes and Decision Tree showed moderate performance with accuracy around **78%**  

#### ROC Analysis (AUC Score)
- Random Forest: **74% AUC**  
- XGBoost: **71% AUC**  

---

### Key Takeaways
- Employee satisfaction and involvement are strongly related  
- Experience plays a major role in performance improvement  
- Workforce shows demographic imbalance (gender, marital status)  
- Income growth is linked with age but varies across employees
- Machine learning models can predict employee performance with up to **86% accuracy**, indicating strong potential for data-driven performance evaluation.

---

### Tools Used
- Excel  
- Python (basic data analysis)

### Business Recommendations

- Focus on improving job satisfaction to enhance employee performance and retention  
- Develop targeted strategies for early-career employees to reduce turnover risk  
- Implement engagement programs to increase job involvement levels  
- Align compensation structures with experience and performance trends
- Enables identification of high-performing employees with high accuracy  
- Supports proactive performance management strategies  
- Improves decision-making using predictive insights

---

### Conclusion
This project demonstrates how HR analytics can be used to understand workforce patterns, improve employee performance, and support data-driven decision-making.
