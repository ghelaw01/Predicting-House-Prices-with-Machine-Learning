# Predicting House Prices with Machine Learning — A Scaled Pipeline Approach

> **Author:** [Zemen Matebe Ghelaw](https://github.com/ghelaw01) — Data Scientist & AI/ML Specialist
> **Repository:** [`ghelaw01/Predicting-House-Prices-with-Machine-Learning`](https://github.com/ghelaw01/Predicting-House-Prices-with-Machine-Learning)

ML pipeline that applies feature scaling, removes multicollinearity, and trains predictive models (Linear Regression, Random Forest) on the Boston housing dataset.

🚀 Predicting House Prices with Machine Learning: A Scaled Pipeline Approach
💡 Want to predict house prices accurately? This project builds a machine learning pipeline that applies feature scaling, removes multicollinearity, and trains a predictive model using the Boston Housing Dataset.

🔍 Project Overview
This project focuses on predicting house prices using Linear Regression and Random Forest, while addressing key data preprocessing challenges: ✅ Feature Scaling – Standardizes independent variables for better model performance
✅ Multicollinearity Handling – Removes highly correlated features like rad & tax
✅ Pipeline Implementation – Automates preprocessing & modeling in a single function call
✅ One-Call Prediction – Predict house prices with a simple function

📌 Key Features
🔹 Dataset: Boston Housing Dataset (via OpenML)
🔹 Models: Linear Regression & Random Forest
🔹 Scaling: StandardScaler() for independent variables & TransformedTargetRegressor() for the target variable
🔹 Pipeline: Automates data transformation and model training
🔹 One-Call Function: Quickly predict house prices with a single function

⚙️ How It Works
1️⃣ Load & Preprocess Data
2️⃣ Remove Multicollinearity (Drop rad due to high correlation with tax)
3️⃣ Scale Features using StandardScaler()
4️⃣ Train Machine Learning Models (Linear Regression & Random Forest)
5️⃣ Save & Load Pipelines for Future Predictions
6️⃣ Deploy a One-Call Function for Real-Time Predictions

🖥️ Example: Predicting a House Price

predicted_price = predict_house_price(crim=0.1, zn=25.0, indus=5.0, chas=0, nox=0.5, rm=6.5,
                                      age=30, dis=5.0, tax=300, ptratio=15.0, b=380.0, lstat=5.0)

print(f"🏡 Predicted House Price: ${predicted_price:,.2f}")
💰 Output: 🏡 Predicted House Price: $25,340.00

📊 Results & Performance
🔹 R² Score (Linear Regression with Scaling): ~0.72
🔹 R² Score (Random Forest): ~0.89
✅ Random Forest outperforms Linear Regression, but both models benefit from feature scaling!

📌 Why This Matters?
🏡 House price prediction is crucial for real estate investments, mortgage approvals, and financial planning.
📈 Machine Learning pipelines help automate preprocessing & predictions efficiently.

If you're working with structured numerical data, this end-to-end ML pipeline can be adapted for various regression problems.

👨‍💻 How to Use This Project
1️⃣ Clone the repository or load the dataset
2️⃣ Train the pipeline using LinearRegression or RandomForestRegressor
3️⃣ Save the trained model for real-time predictions
4️⃣ Use the one-call function to predict house prices in a single step

🔗 Connect & Learn More
📢 Let’s discuss: What other ML techniques would you use for this problem?
💬 Drop your thoughts in the comments or DM me!

🚀 Follow me for more ML & data science projects! 🙌

---

<sub><b>Author:</b> Zemen Matebe Ghelaw (also: Zemen Ghelaw, Zemen M. Ghelaw) — Data Scientist & AI/ML Specialist based in Washington, D.C. · <a href="https://github.com/ghelaw01">github.com/ghelaw01</a><br><b>Keywords:</b> house price prediction · feature scaling · multicollinearity · Linear Regression · Random Forest · Zemen Matebe Ghelaw</sub>
