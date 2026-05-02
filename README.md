# 📊 User Behavior Analysis Dashboard (R Shiny)

An **interactive data visualization dashboard** built using **R Shiny**, designed to analyze and explore user behavior patterns such as app usage, screen time, and battery consumption.

---

## 🚀 Features

### 📈 Exploratory Data Analysis (EDA)

* Summary statistics of key variables:

  * App Usage Time
  * Screen On Time
  * Battery Drain

---

### 📊 Visualizations

#### 🔹 Bar Charts

* Gender distribution
* Operating System distribution

#### 🔹 Histograms

* App Usage Time
* Battery Drain

#### 🔹 Boxplots

* Screen On Time vs Operating System
* App Usage Time vs Gender

---

### 📉 Statistical Modeling

#### ✔ Normal Distribution Fit

* Fits a normal distribution to App Usage Time
* Overlay curve visualization

#### ✔ Linear Regression Model

* Predicts **Battery Drain** using:

  * Screen On Time
  * App Usage Time

Includes:

* Regression plot
* Model summary
* Confidence intervals

---

## 🧠 Technologies Used

* **R**
* **Shiny**
* **ggplot2**
* **dplyr**
* **MASS**
* **fitdistrplus**

---

## 📂 Dataset

* File: `user_behavior_dataset.csv`
* Contains:

  * Device Model
  * Operating System
  * Gender
  * App Usage Time
  * Screen On Time
  * Battery Drain

---

## 🛠️ How to Run

### Step 1: Install Required Packages

```r id="f3xj9p"
install.packages(c("shiny", "ggplot2", "dplyr", "MASS", "fitdistrplus"))
```

### Step 2: Run the App

```r id="2n9q4m"
library(shiny)
runApp("app.R")
```

> Make sure your dataset (`user_behavior_dataset.csv`) is in the same directory.

---

## 🎨 UI Highlights

* Gradient background styling
* Responsive layout using **sidebar + tabs**
* Clean and interactive plots
* Organized sections for analysis

---

## 📋 Tabs Overview

| Tab                     | Description              |
| ----------------------- | ------------------------ |
| Bar Charts              | Gender & OS distribution |
| Histograms              | Usage & Battery patterns |
| Boxplots                | Comparative analysis     |
| Normal Distribution Fit | Statistical fitting      |
| Regression Model        | Prediction + insights    |

---

## 👩‍💻 Team Members

* **Sadaf Saqlain** (23F-0692)
* **Rida Mehmood** (23F-0554)
* **Faryal** (23F-0606)
* **Maryam Asif** (23F-6030)
* **Adan Sajid** (23F-0691)

---

## 🎯 Learning Outcomes

* Data visualization using **ggplot2**
* Building interactive dashboards with **Shiny**
* Applying statistical models in R
* Understanding user behavior patterns
* UI/UX customization in Shiny apps

---

## 📌 Future Improvements

* Add filters (date, device type, etc.)
* Real-time data integration
* Advanced ML models (prediction)
* Export reports (PDF/CSV)
* Deploy on **ShinyApps.io**

---
