
---

# ✈ Flight Price Prediction – Exploratory Data Analysis & Feature Engineering

## 📌 Overview

We Showcase **Exploratory Data Analysis (EDA)** and **Feature Engineering** on a real-world flight price dataset to identify factors influencing airfare and prepare the data for **predictive modeling**.
The workflow covers data cleaning, transformation, visualization, and encoding to produce a **model-ready dataset** for future machine learning applications.

---

## 📊 Dataset

* **Source:** Flight price dataset (CSV)
* **Rows:** \~11,000
* **Columns:** Includes Airline, Date of Journey, Departure Time, Arrival Time, Duration, Total Stops, Source, Destination, and Price.

---

## 🛠️ Key Steps

### 1️⃣ Data Cleaning

* Removed irrelevant columns such as `Route`
* Handled missing values in `Total_Stops`
* Corrected inconsistent data formats
* Converted date and time fields into standard numerical values

### 2️⃣ Feature Engineering

* Extracted **day, month, year** from `Date_of_Journey`
* Parsed **arrival and departure times** into `hour` and `minute` features
* Converted `Total_Stops` into numerical categories
* Transformed `Duration` into hours/minutes for easier analysis
* Created 8+ new predictive features

### 3️⃣ Categorical Encoding

* Applied **One-Hot Encoding** to `Airline`, `Source`, and `Destination`
* Generated dummy variables for categorical attributes to prepare data for machine learning

### 4️⃣ Exploratory Data Analysis

* Visualized relationships between **airline, stops, duration, and ticket prices**
* Identified top price drivers using correlation heatmaps and box plots
* Observed trends in flight prices based on month, stops, and airline

---

## 📈 Insights

* **Airline type**, **number of stops**, and **flight duration** are major drivers of price.
* Non-stop flights tend to be significantly more expensive than multi-stop ones.
* Peak travel months see higher ticket prices across most airlines.

---

## 💻 Tech Stack

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

---

