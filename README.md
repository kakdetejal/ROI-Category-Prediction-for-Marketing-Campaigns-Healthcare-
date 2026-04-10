# ROI-Category-Prediction-for-Marketing-Campaigns-Healthcare-

This project develops a machine learning model to **predict the ROI category (Low, Medium, High)** of marketing campaigns using only **pre-campaign features** such as budget, planned impressions/clicks, historical performance, and engagement expectations.

The goal is to enable organizations to **make better campaign decisions before execution**, reducing risk and improving marketing efficiency.

---

##  Project Workflow

- Performed **Exploratory Data Analysis (EDA)** to understand distributions, correlations, and class imbalance  
- Cleaned data by handling **missing values, duplicates, and outliers**  
- Applied **feature engineering** (e.g., extracting month from campaign date)  
- Converted categorical variables using **Label Encoding and One-Hot Encoding**  
- Experimented with **PCA** for dimensionality reduction  
- Built and compared models including **Random Forest** and **Logistic Regression**  
- Addressed class imbalance using **class_weight='balanced'**

---

##  Final Model

- **Logistic Regression (with class balancing)**  
- **Accuracy:** 77%  
- **High ROI Recall:** 63% (significant improvement from baseline)  

---

##  Business Impact

- Helps identify **high ROI campaigns before launch**  
- Supports **better budget allocation** by prioritizing high-performing campaigns  
- Reduces spending on **low-performing strategies**  
- Enables **data-driven decision making** for marketing teams  
- Improves overall **campaign efficiency and ROI**  

---

##  Key Insight

> Focusing on improving **High ROI detection (recall)** is more valuable than just maximizing accuracy, as it directly impacts business profitability.


---

##  Outcome

The model successfully identifies potential high ROI campaigns, enabling **smarter marketing strategies and optimized resource utilization**.
