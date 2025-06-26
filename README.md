# Predicting Airbnb Prices in Melbourne 🇦🇺

This is a group project we completed for the **BUSA8001 – Applied Predictive Analytics** unit at Macquarie University. The goal was to predict Airbnb listing prices in Melbourne using real data provided through a Kaggle-style competition. We approached it as a real-world data science challenge — covering everything from messy data cleaning to model tuning and interpretation.

## 🧠 Project Goal

The main aim was to build a predictive model that could estimate the nightly price of Airbnb listings based on property features like location, amenities, host status, reviews, and more. To make things more realistic, price was log-transformed and Kaggle evaluated our predictions using RMSE.

## 👨‍👩‍👦 Team Members & Roles

This was a collaborative effort from three team members:

- **Muhammad Pasha Arrighi Effendi** – Problem framing and exploratory analysis (Me)
- **Sulaiman Yusuf Zakaria** – Data wrangling, feature engineering, and preprocessing
- **Muhammad Akbar Ibrahim** – Model building, tuning, and final submission

We worked closely together, but each of us led one of the core stages to simulate real team-based workflows.

## 🧰 Tools & Techniques

- **Languages & Libraries**: Python, Pandas, NumPy, Scikit-learn, XGBoost, LightGBM
- **Visualisation**: Seaborn, Matplotlib
- **Modelling**: Random Forest, Gradient Boosting (XGBoost, LightGBM), Cross-Validation
- **Preprocessing**: Missing value imputation, categorical encoding, text feature extraction, geospatial features, date handling

## 🗃️ What’s Inside

- `BUSA8001_FinalGroup.ipynb` – The full Jupyter Notebook with our workflow (cleaning → EDA → modelling)
- `Data/` – Raw and processed datasets (local folder during dev)
- `submission.csv` – Our final output file submitted to Kaggle

## 📈 Model Highlights

We compared multiple models using 5-fold cross-validation. Our final LightGBM model achieved strong performance with relatively low RMSE on the test set. We also spent time understanding which features (like location, number of amenities, host status) had the most influence on price predictions.

## 💡 Why This Project Matters

This project reflects how we work on real-life data problems:
- Dealing with unclean and inconsistent data
- Creating meaningful features beyond what’s in the raw dataset
- Iterating across models while avoiding overfitting
- Communicating results clearly to a non-technical audience

It’s not just about making a model that "works" — it’s about the full pipeline, collaboration, and learning how to tell the story behind the numbers.

---

📌 _This project is part of my data science portfolio and demonstrates my ability to work with real data, build ML models, and communicate insights effectively._
