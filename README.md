# 🛫 Indigo Passenger Referral Prediction ✈️

<img src="https://github.com/vivekMishra121/-Airline-Passenger-Referral-Prediction/assets/143250429/172fc675-9a58-4c95-811a-882aa5403538" alt="Airline Referral Prediction Banner" style="height: 450px; width: 1000px;">

## 📌 Overview
This project focuses on predicting whether airline passengers would **recommend their experience** to others, using **Machine Learning classification models**. The dataset comprises global airline reviews from **2006 to 2019**, gathered via multiple-choice and free-text inputs. The goal is to help airlines identify **satisfied customers likely to refer their services**, enabling better strategic decision-making and targeted marketing.

---

## 🚀 Problem Statement
The airline industry thrives on **customer satisfaction** and **word-of-mouth referrals**. This project aims to:

✅ Classify passengers based on **likelihood of referral**  
✅ Identify **key factors** influencing customer satisfaction  
✅ Support airlines in optimizing **codeshare agreements**, **pricing**, and **market positioning**  
✅ Improve service areas (e.g., food, entertainment, cabin comfort) that affect referral rates

---

## 📂 Dataset Description

The dataset contains **131,895 rows** and **17 columns**, including:

| Column | Description |
|---|---|
| `airline_name` | Name of the airline |
| `overall_rating` | Customer's overall rating |
| `value_for_money` | Satisfaction with value for money |
| `cabin_service` | In-flight cabin service rating |
| `entertainment` | Entertainment rating |
| `seat_comfort` | Seat comfort score |
| `ground_service` | Ground staff & service score |
| `food_beverages` | Food and drink rating |
| `recommended` | Whether the customer would recommend the airline |
| `type_of_traveller`, `cabin_flown`, `route`, `date_flown` | Additional contextual information |

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Key Insights:
✔ Majority of passengers fly **Economy Class (~72%)**, followed by Business (19.4%)  
✔ Ratings are mostly in the **1–5 range** (except overall_rating: 1–10 scale)  
✔ **Value for Money** and **Cabin Service** were highly correlated with positive referrals  
✔ Data cleaning included fixing date formats, encoding categorical variables, and handling NaNs

---

## 🛠 Data Preprocessing & Feature Engineering

📌 **Data Cleaning:**
- Converted `date_flown` to datetime
- Handled missing/null values
- Corrected inconsistent rating scales

📌 **Feature Engineering:**
- Encoded categorical columns
- Applied **Principal Component Analysis (PCA)**  
- Retained top **6 components**, capturing **92% variance**

---

## ⚙️ Machine Learning Pipeline

### 🔢 Classification Models Used:
1. **Decision Tree**
   - Initially overfit; resolved via pruning & cross-validation
2. **K-Nearest Neighbors (KNN)**
3. **Support Vector Machine (SVM)**
4. **Random Forest Classifier**

📌 **Best Performing Model:**  
✔ **SVM** outperformed others in F1 Score, Precision, and Accuracy (~90%+ across all models)

---

## 📈 Feature Importance

Top features contributing to the model’s predictions:

- 🏷 **Value for Money**  
- 🛎 **Cabin Service**  
- 🍽 **Food & Beverages**  
- 🎥 **Entertainment**  
- 🛬 **Ground Service**

---

## 📦 Deployment

Deployment files include:

| File | Purpose |
|---|---|
| `model.pkl` | Pickled model file |
| `model.joblib` | Joblib model version for scalability |

---

## 📷 Sample Visuals

> *(Optional — add your images here if available)*

- 📊 Word clouds for feedback analysis  
- 📉 Model performance metrics comparison  
- 🧮 PCA component variance plots  
- 🧾 Confusion matrix for classification models  

---

## 🏆 Conclusion & Future Scope

✅ Successfully developed and validated multiple classification models  
✅ Identified actionable insights for **referral-based customer segmentation**  
✅ Found **SVM** to be most effective for predicting referrals  
✅ Recommended improvements in **cabin service, food, and seat comfort** to boost satisfaction

🔮 **Future Enhancements:**
- Integrate **sentiment analysis** from review text  
- Use **XGBoost** or **LightGBM** for better performance  
- Build a **web-based dashboard** for real-time predictions and customer profiling

---

## 📜 Technologies Used

| Tool | Purpose |
|---|---|
| **Python** | Programming Language |
| **Pandas, NumPy** | Data Wrangling |
| **Matplotlib, Seaborn** | Visualization |
| **Scikit-learn** | Machine Learning |
| **PCA** | Dimensionality Reduction |
| **SVM, KNN, Decision Tree, Random Forest** | Classification Models |
| **Pickle, Joblib** | Model Deployment |

---

## 📌 Project Structure
📂 Airline_Passenger_Referral_Prediction
│── 📁 data                   # Raw & processed datasets
│── 📁 notebooks              # Jupyter Notebooks
│── 📁 models                 # Pickle/Joblib model files
│── 📁 visuals                # Plots and charts
│── 📄 README.md              # Project Documentation


---

## 📬 Contact

📩 **Email:** [abhityagi4733@gmail.com](mailto:abhityagi4733@gmail.com)  
🔗 **LinkedIn:** [linkedin.com/in/abhishektyagi02](https://linkedin.com/in/abhishektyagi02)  
🔗 **GitHub:** [github.com/abhishek-tyagi-da](https://github.com/abhishek-tyagi-da)

---

🚀 *Let data fly your business forward.*

⭐ *If you found this project insightful, don’t forget to give it a ⭐ on GitHub!*

