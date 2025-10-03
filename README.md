# Amazon Product Sales Prediction

## 📌 Project Overview

This project predicts **Amazon product sales performance** using **Machine Learning models**.
The primary goal is to analyze product attributes (such as price, discount, buy box availability, etc.) and predict whether a product will **sell successfully**.

The project includes:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Model training & evaluation (Logistic Regression, K-Nearest Neighbors, Linear Regression)
* Insights on the most impactful product features

---

## 🧠 Models Used

* **Logistic Regression** – for binary classification (sale success vs. failure).
* **K-Nearest Neighbors (KNN)** – for instance-based classification.
* **Linear Regression** – for baseline numerical trend analysis.

---

## 📊 Dataset

* **Source**: Amazon products dataset (`amazon_products_sales_data_uncleaned.csv`)
* **Cleaning Steps**:

  * Dropped irrelevant columns (`image_url`, `product_url`)
  * Encoded categorical variables using `LabelEncoder`
  * Handled missing values
  * Scaled numerical features using `StandardScaler`

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/amazon-sales-prediction.git
cd amazon-sales-prediction
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Jupyter Notebook

```bash
jupyter notebook project.ipynb
```

---

## 🚀 Usage

* Open the notebook `project.ipynb`.
* Run all cells sequentially.
* The notebook will:

  * Load and clean the dataset.
  * Train models (Logistic Regression, KNN, Linear Regression).
  * Evaluate performance using accuracy and other metrics.
  * Generate insights & visualizations.

---

## 📈 Results & Insights

* **Logistic Regression** and **KNN** performed as strong predictors of product sales success.
* Features such as **price, discount percentage, and buy box availability** were most significant.
* The analysis highlights that **optimized pricing and discounts** have the greatest effect on boosting sales.

---

## 🔮 Future Work

* Add more advanced models (Random Forest, XGBoost, Neural Networks).
* Deploy the model with a **Flask/Django API**.
* Build a **dashboard** (e.g., with Streamlit) for real-time predictions.
* Expand dataset with customer reviews & ratings for sentiment analysis.

---

## 📦 Requirements

* Python 3.8+
* NumPy, Pandas
* Scikit-learn
* Seaborn, Matplotlib
* Jupyter Notebook

(These can be installed via `requirements.txt`)

---

## 📜 License

This project is licensed under the MIT License – feel free to use, modify, and distribute.
