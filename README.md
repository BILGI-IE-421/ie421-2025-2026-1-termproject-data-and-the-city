# Olympic Games Data Analysis

> IE 421 - Data Science for Engineers | Istanbul Bilgi University 

---

## About The Project

This project analyzes **120+ years of Olympic history** (1896-2016) combined with **Paris 2024** athlete data to explore gender equality trends, predict national medal counts, and investigate whether physical attributes influence athletic success.

---

## Project Website

**Web Page:** https://cetinkayafatih.github.io/dataandthecity-olympics/

**Repository:** https://github.com/cetinkayafatih/dataandthecity-olympics

---

## Team: Data and The City

| Name | Student ID |
|------|------------|
| Mehmet Fatih Cetinkaya | 121205031 |
| Mehmet Tolga Cakan | 121203029 |
| Demet Irem Yilmaz | 121203095 |
| Sila Kahya | 123203018 |
| Eylul Balci | 122203020 |

---

## Research Questions & Results

### Q1: Gender Parity in the Olympics

**Question:** How has female participation changed over 120 years?

![Gender Timeline](visuals/q1_gender_timeline.png)

**Key Findings:**
- 1896: 0% female athletes
- 2016: 45.03% female athletes
- Paris 2024: 49.09% female athletes (near parity!)

![Paris 2024 Parity](visuals/q1_paris2024_parity.png)

---

### Q2: Predicting Medal Counts

**Question:** Can we predict how many medals a country will win?

![Medal Prediction](visuals/q2_prediction_scatter.png)

**Model Performance (2016 Validation):**
| Metric | All NOCs | Top-20 NOCs |
|--------|----------|-------------|
| R² | 0.8927 | 0.7779 |
| RMSE | 9.49 | 27.04 |

---

### Q3: Athlete Success Classification

**Question:** Do biometrics (age, height, weight) predict medal success?

![Classification Results](visuals/q3_classification_results.png)

**Results:**
| Metric | Value |
|--------|-------|
| ROC-AUC | 0.5975 |
| F1 Score | 0.2381 |
| Best Threshold | 0.51 |

**Conclusion:** Physical attributes alone are weak predictors of medal success.

---

## Data Sources

- **Historical Data (1896-2016):** [Kaggle](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)
- **Paris 2024 Data:** [Kaggle](https://www.kaggle.com/datasets/piterfm/paris-2024-olympic-summer-games)
