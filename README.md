# **Airway Passenger Satisfaction – End-to-End Data Project**

<p align="center"> <p align="center"> <b>Data Cleaning • Imputation • Outlier Detection • EDA • Feature Engineering</b> </p>

# **🛫 Project Overview**

Air travel generates massive amounts of operational and passenger feedback data.
But before any analysis or machine learning, the most important step is data cleaning, which typically takes 80% of the total effort in real-world data projects.

This repository demonstrates a complete, industry-standard pipeline for preparing a high-quality dataset for Airway Passenger Satisfaction analysis, using a structured multi-notebook workflow that is clean, reproducible, and easy to follow.

# **📥 1. Data Source**

The original raw dataset was downloaded from Kaggle:

👉 Airline Passenger Satisfaction Dataset

# **🧹 2. Data Preprocessing (Notebook 1)**

This is the most crucial part of the project.
Here:

✔ Loaded raw dataset
✔ Performed extensive data cleaning
✔ Detected missing values
✔ Applied multiple imputation techniques:

Simple Imputer

KNN Imputer

Random Forest Imputer

# **🚨 3. Outlier Detection & Treatment (Notebook 2)**

This notebook safely identifies and handles outliers based on statistical & domain logic.

✔ Applied IQR and Z-score methods
✔ Visualized via scatterplots, boxplots
✔ Studied Flight Distance vs Arrival Delay outliers
✔ Detected true vs false outliers
✔ Safely separated datasets

# **📊 4. Exploratory Data Analysis (Notebook 3)**
# **🔧 5. Feature Engineering (Notebook 4)**

# **🛠️ Tools & Libraries Used**

Data Handling	Pandas, NumPy
Visualization	Matplotlib, Seaborn
Imputation	Scikit-Learn, RandomForestRegressor
Outlier Detection	IQR, Z-Score
Notebook Styling	Markdown, HTML
Version Control	Git & GitHub



Airway-Passenger-Satisfaction (filing structure)
│

├── raw_data.csv

├── Data preprocessing.ipynb

├── Airway-PassengerSatisfaction_cleaned.csv

├── Outlier_Detection.ipynb

├── cleaned_without_outliers.csv

├── airways-outlier.csv

├── only_outliers.csv

├── insights_ready.csv

├── Feature_Engineering.ipynb

├── model_ready_data.csv


└── README.md


# **🙋‍♂️ About the Author – Muhammad Usman**

Data Enthusiast • Machine Learning Learner • Clean Coding Practitioner

# **🔗 Connect With Me**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammad-usman736/)  [![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:usman.rizz6769@gmail.com)  [![Hotmail](https://img.shields.io/badge/Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white)](mailto:Muhammad_usman2023@hotmail.com)
