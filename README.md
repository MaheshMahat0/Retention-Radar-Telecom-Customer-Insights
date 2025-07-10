# Retention-Radar Telecom-Customer-Insights

## 📝 Overview

This project demonstrates an end-to-end data science pipeline using Python and Power BI. From data preprocessing and model training to insightful visual storytelling, this collaborative effort showcases how a dataset can be transformed into valuable business insights. The project was executed by **Analytics Alley** consisting of three members: Mahesh Mahto, Ashwin Kumar, and AnasZaki.

---

## 👥 Team Members

- **Mahesh Mahto** – Data Cleaning, Feature Scaling, Correlation Analysis  
- **Ashwin Kumar** – Model Training, Feature Engineering, Accuracy Evaluation  
- **Anas Zaki** – Power BI Dashboarding, GitHub Repository Management

---

## 🧾 Dataset
The dataset used for this project is a structured table with numerical and categorical columns suitable for supervised machine learning tasks and visualization.

**Features Include:**  
Various attributes related to the target variable including product/category columns, date/time fields, numerical fields for prediction, and customer-related metadata.

---

## 📁 Project Structure
```
RetailPulse/
│── 📄 README.md                               # Project documentation
│── 📂 data/                                  # Contains raw and cleaned datasets
│   │── 📄 Train_Data.csv                      # Use for train the model
│   │── 📄 Cleaned_Data.csv                    # Use for Power Bi dashboard and Visualization
│   │── 📄 Test_Data.csv                       # Use for prediction
│── 📂 notebooks/                              # Jupyter notebooks for EDA and ML
│   │── 📄 EDA_and_Model.ipynb                 # Preprocessing and ML notebook
│   │── 📄 Customer_Insights_Dashboard.pbix    # Power Bi for final dashboard
```



---

## 🧹 Data Preprocessing

We performed multiple preprocessing steps using **pandas** and **numpy** to prepare the data for analysis:

- Removed missing values and outliers
- Standardized data types and column formats
- Encoded categorical variables into numerical form
- Scaled numeric features to enable machine learning
- Used correlation heatmaps to identify key relationships

---

## 📈 Model Training

The machine learning model was built using **Scikit-learn** with the following steps:

- Splitting dataset into training and testing sets  
- Selecting features based on correlation  
- Model training using Logistic Regression  
- Evaluating the accuracy and confusion matrix  

Final accuracy achieved: **87%**

---

## 📊 Power BI Dashboard

Power BI was used to design a fully interactive business dashboard. Features include:

- **KPI Cards** for total customers, churned customers, churn rate %, Average monthly charges, and revenue
- **Dynamic Filters & Slicers** for contract and genders
- **Pie Chart** for sales contribtion by Contract
- **Bar Charts** for Average CLTV by Tenure Group

📸 **Screenshot Preview:**

### 🔹 Power BI Dashboard
![power bi-1](https://github.com/user-attachments/assets/7f1babf6-bc6b-4e5a-b802-8c2e553f3524)


---

## ✅ Key Features
✔️ Cleaned and preprocessed data using **Pandas**  
✔️ Feature scaling and encoding for ML compatibility  
✔️ ML model trained with **Scikit-learn**  
✔️ KPI-driven **Power BI** dashboard  
✔️ GitHub used for version control and team collaboration

---

## 🔧 Setup & Installation

1. **Clone this repository**
```bash
git clone https://github.com/Anas-Zaki/Retention-Radar-Telecom-Customer-Insights.git
cd Retention-Radar-Telecom-Customer-Insights
```

2. **Install Python dependencies**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
3. **Open Power BI File**
```bash
Open PowerBI_Dashboard.pbix using Power BI Desktop
(Download from: https://www.microsoft.com/en-us/download/details.aspx?id=58494)
```

## 🔮 Future Improvements
- Use more advanced ML models like Random Forest or XGBoost
- Add SHAP/Explainable AI tools for feature importance
- Connect Power BI to a real-time SQL server
- Automate report generation with Python


## 📬  Acknowledgments
Thanks to our mentors and peers for their support, and special appreciation to Masai School for providing us with this hands-on opportunity to explore the entire data science lifecycle.

## 📜 License
This project is open-source and available for modification and distribution.

---

📩 **Contributions & Feedback**         
We welcome suggestions, forks, and contributions!


Happy Learning! 🙌🚀

