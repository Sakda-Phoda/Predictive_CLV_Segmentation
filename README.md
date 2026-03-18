# Predictive_CLV_Segmentation

## 📌 Project Overview
This project applies machine learning and probabilistic models to analyze customer purchasing behavior, predict future value, and segment customers. The goal is to move from historical reporting to predictive analytics, helping the business allocate marketing budgets more effectively and prevent customer churn.

## 💼 Business Impact
- **Optimized Marketing Budget:** By predicting the exact CLV for the next 90 days, the marketing team knows the maximum acquisition cost (CAC) or retention budget they should spend per segment.
- **Proactive Churn Prevention:** Identified the "Need Attention" segment before they fully churn, allowing for timely win-back campaigns.

## 🛠️ Tech Stack & Methodology
- **Language & Libraries:** Python, Pandas, Matplotlib, Seaborn, Scikit-learn, Lifetimes.
- **Cohort Analysis:** To track trends in customer retention.
- **Probabilistic Models (Lifetimes):**
    - **BG/NBD Model:** To predict the probability of a customer being active and their expected number of purchases in the next 90 days.
    - **Gamma-Gamma Model:** To estimate the expected average spend per transaction.
- **Clustering (Machine Learning):** 
    - **Gaussian Mixture Model (GMM):** Selected over K-Means to handle the heteroscedasticity (elliptical distribution) of the P(Alive) and CLV feature space, clustering customers into 5 actionable segments.

## 📊 Key Findings & Strategic Insights
1. **Value Distribution:** The **Promising** segment contributes the highest total CLV (42%), followed closely by **Loyal Customers** (34%). These two groups are the backbone of the business's revenue and profit.
2. **Efficiency vs. Volume:** While the 'Promising' segment brings in the most total money, **Loyal Customers** have the highest *Average CLV per person*, making them the most cost-efficient group to maintain.
3. **Behavioral Preferences:** The 'Promising' and 'Loyal' segments dominate revenue across *all* store types and product categories, indicating strong brand loyalty that can be leveraged for new product launches.

## 📂 Data Source
[Chocolate Sales Dataset (2023-2024) on Kaggle](https://www.kaggle.com/datasets/ssssws/chocolate-sales-dataset-2023-2024)

<img width="1138" height="684" alt="image" src="https://github.com/user-attachments/assets/4f89f6b3-bfe7-4cc0-aae5-33922bf3bcf5" />
<img width="694" height="679" alt="image" src="https://github.com/user-attachments/assets/9f73f1a9-3c29-4894-ad09-d8d635b218ab" />
<img width="2519" height="590" alt="image" src="https://github.com/user-attachments/assets/d486a72d-890b-4a4e-a3b7-16d669218d37" />


