# Global Terrorism Database Analysis
## 🛡️ Terrorist Group Prediction using Machine Learning

## 📌 Project Overview

Terrorism remains one of the most pressing global challenges, with incidents often going unattributed due to the absence of claims from perpetrator groups. This project leverages the **Global Terrorism Database (1970–2021)** — a rich dataset with over **214,000 incidents** and **135 attributes** — to build machine learning models that predict the **terrorist group (gname)** responsible for an attack, based on incident characteristics.

Our primary goal is to explore the potential of **data-driven methods** in supporting faster investigations, better resource allocation, and enhanced counter-terrorism strategies.

---

## 👥 Team Contribution

This project was a collaborative effort where every member actively contributed to data preprocessing, feature engineering, model building, and visualization. Together, we combined technical knowledge, patience, and enthusiasm to reach impactful results.

---

## 📂 Dataset Information

The project uses the **Global Terrorism Database (GTD)**, publicly available for research.
Some important columns include:

* **`gname` (Target Variable)** → Terrorist group name responsible for the attack.
* **`country_txt`** → Country where the incident took place.
* **`attacktype1_txt`** → Type of attack (e.g., Bombing, Armed Assault, Assassination).
* **`targtype1_txt`** → Primary target type (e.g., Military, Police, Private Citizens, Business).
* **`weaptype1_txt`** → Type of weapon used.
* **`region_txt`** → Geographical region of the incident.
* **`nkill`** → Number of people killed.
* **`nwound`** → Number of people wounded.
* **Other features** such as year, month, success of attack, suicide indicator, etc.

---

## 🔍 Exploratory Data Analysis (EDA)

We performed extensive **data exploration and visualization** to identify key insights, including:

* Trends of terrorist attacks over time.
* Most targeted countries, regions, and sectors.
* Common attack types and weapon types.
* Correlation of features with the target variable (`gname`).
* Handling of **missing values**, **class imbalance**, and **noisy data**.

Color maps like `viridis`, `plasma`, and `RdBu` were used for clear and impressive visualizations.

---

## ⚙️ Methodology

### 1. **Data Preprocessing**

* Cleaned missing and inconsistent data.
* Encoded categorical variables.
* Normalized numerical values.
* Addressed **class imbalance** with appropriate techniques.

### 2. **Model Building**

Applied multiple machine learning algorithms:

* Logistic Regression
* Decision Tree
* Random Forest ✅
* AdaBoost
* XGBoost

### 3. **Evaluation & Tuning**

* Data split using **Train-Test Split**.
* Model evaluation using **Accuracy, Precision, Recall, and F1-score**.
* Achieved **82% accuracy** with **Random Forest**, which performed best.
* Performed **GridSearchCV** for hyperparameter tuning.
* Applied **K-Fold Cross Validation** for robust evaluation.

---

## 📊 Results

* **Best Model:** Random Forest Classifier
* **Accuracy:** **82%**
* Hyperparameter tuning and validation improved consistency of results.

---

## 🚀 Future Work

* Experiment with **deep learning models (LSTMs/Transformers)** for text-based features.
* Implement **real-time prediction pipelines**.
* Explore **explainable AI (XAI)** methods for better interpretability.

---

## 🛠️ Tech Stack

* **Language:** Python 🐍
* **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost
* **Version Control:** Git & GitHub

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use, modify, and distribute with attribution.

---

Would you like me to also **add sample code snippets** (like EDA plots or model training) into the README to make it even more impressive for GitHub recruiters?
