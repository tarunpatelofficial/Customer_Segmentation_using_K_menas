# 🧠 Customer Segmentation Using RFM & K-Means Clustering

---

## 📝 Project Summary

This project applies **RFM (Recency, Frequency, Monetary) analysis and K-Means clustering** to segment retail customers based on purchasing behavior. The results help businesses improve **targeted marketing, customer retention, and revenue optimization** using data-driven strategies.

---

## 🎯 Business Problem

Many businesses struggle to:

- Identify **high-value vs low-value customers**
- Detect **churn risk early**
- Personalize marketing campaigns efficiently

This project solves these issues by grouping customers into **behavior-based segments** that support better **strategic business decisions**.

---

## 💡 Approach

1. **Data Cleaning & Preprocessing**
    - Handled missing values
    - Removed outliers using the **IQR method**
    - Converted data types for time-based analysis
2. **Feature Engineering**
    - Created:
        
        ```
        Amount = Quantity × UnitPrice
        ```
        
1. **RFM Analysis**
    - Recency: Days since last purchase
    - Frequency: Number of transactions
    - Monetary: Total spending

2. **Feature Scaling**    
    - Applied **Min-Max Normalization**
        
3. **K-Means Clustering**
    - Determined optimal clusters using:
        - **Elbow Method**
        - **Silhouette Score**
    - Final model used **4 customer clusters**

---

## 🛠 Tech Stack & Tools

- **Python**    
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**    

---

## 📊 Key Insights & Results

- Customers were segmented into **4 meaningful behavioral groups**
- Identified:
    - ✅ High-value loyal customers
    - 🔁 Repeat mid-value customers
    - ⚠️ At-risk low-activity customers
    - ❌ Churn-prone customers        

### 📈 Business Impact

- Improved **customer lifetime value (CLV) forecasting**
- Better **targeted marketing strategies**
- Reduced **customer churn risk**
- Enhanced **decision-making for sales & retention teams**

---

## 🧾 Dashboard Screenshots
![](Images/download(1).png)
![](Images/download(2).png)
![](Images/download(3).png)
![](Images/download(4).png)
![](Images/download(5).png)
![](Images/download(6).png)
![](Images/download(7).png)
![](Images/download(8).png)
![](Images/download(9).png)
---

## 🧪 Notebook Links

- 📓 **Main Notebook:**  
    `Customer_Segmentation.ipynb`
    
- 📂 GitHub Repository:

```
https://github.com/tarunpatelofficial/Customer_Segmentation_using_K_menas
```

---

## ▶️ How to Run the Project

```
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook Customer_Segmentation.ipynb
```

---

## 👨‍💻 Author

**[Tarun Patel]**  
Aspiring Data Analyst | Python | Machine Learning | Business Analytics  
LinkedIn: [https://www.linkedin.com/in/tarunpatelofficial/]
