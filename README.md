# 🏠 Egyptian Real Estate Price Analysis & Prediction

> **C-DE211: Data Analysis** — Spring 2026  
> Team Leader: Razan Waleed (ID: 24-101157)  
> Team Members: Khaled Ahmed (24-101263) · Youssef Mohamed (25-101800) · Hamza Mohamed (24-101038)

---

## 📌 Project Overview

This project analyzes the Egyptian real estate market using real-world listing data scraped from Egyptian property platforms. The goal is to identify the key factors that influence residential property prices — such as area, number of bedrooms, and location — and build a regression model to predict prices.

---

## 📂 Repository Structure

```
├── data_cleaning_and_preprocessing_part_2.ipynb   # Main analysis notebook
├── proposal_final.docx                             # Project proposal document
└── README.md                                       # Project documentation
```

---

## 📊 Dataset

| Attribute     | Details                                                                 |
|---------------|-------------------------------------------------------------------------|
| **Name**      | Egyptian Real Estate Listings                                           |
| **Source**    | [Kaggle](https://www.kaggle.com/datasets/hassankhaled21/egyptian-real-estate-listings) |
| **Size**      | 19,925 rows × 12 columns (CSV)                                          |
| **Features**  | Price, area, bedrooms, bathrooms, location, type, payment method, etc.  |
| **Origin**    | Real-world data scraped from Egyptian real estate platforms             |

---

## ❓ Problem Statement

The Egyptian real estate market has experienced significant price changes in recent years. Understanding what drives property prices — whether it is the size, number of rooms, or location — is valuable for both buyers and sellers. This project uses real listing data to identify the key factors influencing residential property prices across Egypt.

---

## 🔬 Research Hypothesis

- **H₀:** There is no significant relationship between property features (area, bedrooms, location) and price.  
- **H₁:** Properties with larger area, more bedrooms, and premium locations have significantly higher prices in the Egyptian real estate market.

---

## 🔄 Project Workflow

| Step | Phase               | Description                                              |
|------|---------------------|----------------------------------------------------------|
| 1    | Data Collection     | Load dataset from Kaggle (19,925 rows × 12 columns)      |
| 2    | Data Cleaning       | Handle missing values, fix data types, remove duplicates |
| 3    | EDA                 | Explore distributions, correlations, and patterns        |
| 4    | Visualization       | Charts for price vs. area, location, bedrooms            |
| 5    | Hypothesis Testing  | Statistical tests to accept or reject H₀                |
| 6    | ML Model            | Regression model to predict property prices              |

---

## 🛠️ Technologies Used

- **Python 3**
- `pandas` · `numpy` — data manipulation
- `matplotlib` · `seaborn` — visualization
- `scipy.stats` — statistical hypothesis testing
- `scikit-learn` — machine learning (Linear Regression, Label/One-Hot Encoding)

---

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   cd YOUR_REPO_NAME
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy scikit-learn
   ```

3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/hassankhaled21/egyptian-real-estate-listings) and place `egypt_real_estate_listings.csv` in the project folder.

4. Open and run the notebook:
   ```bash
   jupyter notebook data_cleaning_and_preprocessing_part_2.ipynb
   ```

---

## 📈 Key Findings *(to be updated after analysis)*

- Results from hypothesis testing and the regression model will be documented here upon completion.

---

## 📄 License

This project is submitted as part of **C-DE211: Data Analysis**, Spring 2026. For academic use only.
