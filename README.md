💻 Laptop Price Analysis & Prediction 📊


📌 Project Overview

This project focuses on analyzing laptop specifications and predicting laptop prices using data analysis and machine learning techniques. The goal is to understand how different features, such as brand, RAM, processor, storage, and display, affect laptop pricing and to build a reliable price prediction model.
________________________________________________________________________________________________________________________
🎯 Objectives

🔍 Analyze laptop features and pricing patterns
📊 Perform Exploratory Data Analysis (EDA) with visual insights
🤖 Build machine learning models for price prediction
📈 Compare model performance and identify key price drivers
________________________________________________________________________________________________________________________
🗂 Dataset Description

The dataset contains information about various laptops with the following key attributes:

🏷 Company – Manufacturer name
💾 RAM – Memory size
⚙️ CPU Frequency – Processor speed
🎮 GPU Company – Graphics card manufacturer
💽 Storage Type – HDD / SSD / Hybrid
🖥 Screen Size (Inches)
✋ Touchscreen – Yes / No
🌈 IPS Display – Panel type
📐 Resolution & PPI – Display quality
💰 Price (Euros) – Target variable
________________________________________________________________________________________________________________________
🧹 Data Preprocessing

✔ Checked for missing and duplicate values
✔ Removed non-informative columns
✔ Converted categorical variables into numerical form
✔ Split data into training and testing sets
________________________________________________________________________________________________________________________
📊 Exploratory Data Analysis (EDA)

Key insights from EDA include:

💸 Laptop prices are right-skewed, with most devices in the budget to mid-range category
🏷 Brand has a strong influence on pricing
💾 Higher RAM and faster CPUs lead to higher prices
🖥 IPS, touchscreen, and high-resolution displays increase laptop cost
________________________________________________________________________________________________________________________
🤖 Model Building

Since the laptop price is a continuous value, regression models were used:

📐 Linear Regression – Baseline model
🌲 Random Forest Regressor – Advanced model for non-linear patterns
________________________________________________________________________________________________________________________
📈 Model Evaluation

📉 Mean Absolute Error (MAE) is used to measure prediction error
📊 R² Score used to evaluate model accuracy
🌲 Random Forest outperformed Linear Regression
_________________________________________________________________________________________________________________________
⭐ Feature Importance

The most important features influencing laptop price:

💾 RAM
⚙️ CPU Frequency
💽 Storage Type
🖥 Display Quality (Resolution & PPI)
🏷 Brand
__________________________________________________________________________________________________________________________🏁 Conclusion

This project successfully demonstrates how laptop prices are influenced by a combination of hardware specifications, display features, and brand value. The Random Forest model provided better accuracy and captured complex pricing relationships effectively.
_________________________________________________________________________________________________________________________
🚀 Future Scope

🔧 Hyperparameter tuning
📉 Outlier handling & feature scaling
🌐 Deploy model using Flask / Streamlit
🛒 Integrate real-time market data
_________________________________________________________________________________________________________________________
🛠 Tools & Technologies

🐍 Python
📦 Pandas, NumPy
📊 Matplotlib, Seaborn
🤖 Scikit-learn
_________________________________________________________________________________________________________________________
🙌 Acknowledgement

This project was developed as part of a data science/machine learning journey to gain hands-on experience in real-world data analysis and predictive modeling.
