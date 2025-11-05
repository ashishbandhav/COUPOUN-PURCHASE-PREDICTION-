# COUPOUN-PURCHASE-PREDICTION
# 🏷️ COUPON-PURCHASE-PREDICTION  

### 📘 Overview
This repository contains the full implementation of **Coupon Purchase Prediction**, a project developed to forecast the likelihood of a customer purchasing a coupon using machine learning models.  
It is based on the **Recruit Coupon Purchase Prediction Challenge**, leveraging advanced data analysis, feature engineering, and ensemble models for predictive accuracy.

---

### 🎯 Objective
To build a **data-driven predictive system** that identifies customer preferences and purchase intentions based on:
- User behavior data  
- Coupon metadata  
- Purchase history  
- Geolocation and temporal patterns  

The aim is to improve targeted marketing, enhance recommendation systems, and reduce marketing cost inefficiencies.

---

### ⚙️ Technologies Used
- **Python**
- **Pandas**, **NumPy**, **Scikit-learn**, **SciPy**
- **XGBoost**, **Chainer**
- **Sklearn-pandas** for pipeline management
- **Matplotlib** and **Seaborn** for data visualization  

---

### 🧩 Methodology
1. **Data Preprocessing**
   - Cleaning missing values and merging multiple CSV datasets.
   - Feature extraction from user and coupon data.
   - Encoding categorical variables and normalizing continuous data.

2. **Feature Engineering**
   - Added geolocation, month, and user preferences through multiple custom scripts.
   - Generated derived features like distance-based similarity and temporal purchase trends.

3. **Modeling**
   - Built an **XGBoost** and **Chainer-based ensemble** for prediction.
   - Optimized hyperparameters via **grid search** and **cross-validation**.
   - Achieved a **top 5% leaderboard score** (Private LB: 0.008776).

4. **Evaluation**
   - Evaluated using **Precision@K**, **MAP@K**, and **ROC-AUC**.
   - Compared performance across baseline and tuned models.

---


Dependency (development environment)
OS: Ubuntu 14.04
Python: 2.7
pip: numpy(1.9), scipy, pandas, sklearn, sklearn-pandas, chainer


### 📁 Repository Structure

📦 COUPOUN-PURCHASE-PREDICTION

 ┣ 📂 COUPOUN PURCHASE PREDICTION PROJECT FILES
 
 ┣ 📄 FINAL_SUBMISSION.csv
 
 ┣ 📜 LICENSE
 
 ┣ 📜 README.md
 
 ┣ 📜 add-geolocation.py
 
 ┣ 📜 add_month_data.py
 
 ┣ 📜 add_prefication_to_userlist.py
 
 ┣ 📜 coupons6.py
 
 ┣ 📜 get_answer_file.py

 ┣ 📜 get_distance_user_coupon.py
 
 ┣ 📜 look_at_data.py
 
 ┣ 📜 sex_id.py
 
 ┗ 📜 translation.py
