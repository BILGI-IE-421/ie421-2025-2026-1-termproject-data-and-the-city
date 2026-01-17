# IE 421 - Data Science for Engineers Term Project

> **Team:** Data and The City
> **Course:** IE 421 Data Science for Engineers
> **Institution:** Istanbul Bilgi University
> **Term:** Fall 2024-2025

---

## Overview

This project explores **120+ years of Olympic Games data** to answer three research questions using descriptive analytics, regression, and classification techniques. We analyze historical patterns from 1896-2016 and incorporate Paris 2024 athlete registration data for contemporary insights.

---

## Student Names

- Mehmet Fatih Cetinkaya (121205031)
- Mehmet Tolga Cakan (121203029)
- Demet Irem Yilmaz (121203095)
- Sila Kahya (123203018)
- Eylul Balci (122203020)

---

## Files

| Folder/File | Description |
|-------------|-------------|
| `data/` | Contains the datasets used |
| `scripts/` | Python scripts for data processing and analysis |
| `visuals/` | Generated visualizations (PNG files) |
| `css/` | Stylesheet for the web interface |
| `index.html` | Main project webpage |
| `requirements.html` | Detailed analysis and results page |

---

## Research Questions

### Q1: Gender Parity Analysis
*How has gender participation evolved in the Olympics?*

- Analyzes female participation trends from 1896 to 2016
- Examines discipline-level gender balance at Paris 2024
- **Method:** Descriptive statistics with time-series visualization

### Q2: Medal Count Prediction
*Can we predict a nation's medal count?*

- Predicts total medals using delegation size and historical performance
- Training: 1960-2012 | Validation: 2016 Rio Olympics
- **Method:** Multiple Linear Regression
- **Focus:** Top-20 performing nations

### Q3: Athlete Success Classification
*Do physical attributes predict medal success?*

- Classifies athletes as medalists vs non-medalists
- Features: Age, Height, Weight, Sex
- **Method:** Logistic Regression with threshold tuning
- **Scope:** Post-2000 Olympics, high-physicality sports

---

## Datasets

| Dataset | Period | Records | Source |
|---------|--------|---------|--------|
| Historical Olympics | 1896-2016 | 271,116 | [Kaggle](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results) |
| Paris 2024 Athletes | 2024 | 11,113 | [Kaggle](https://www.kaggle.com/datasets/piterfm/paris-2024-olympic-summer-games) |

---

## Quick Start

```bash
# Install dependencies
pip install -r requirements.txt

# Run all analyses
python scripts/generate_all.py
```

---

## Key Results

| Question | Metric | Value |
|----------|--------|-------|
| Q1 | Female ratio (2016) | 45.03% |
| Q1 | Female ratio (Paris 2024) | 49.09% |
| Q2 | R² (All NOCs) | 0.8927 |
| Q2 | RMSE (All NOCs) | 9.49 |
| Q3 | ROC-AUC | 0.5975 |
| Q3 | F1 Score | 0.2381 |

---

## Technologies

- Python 3.x
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- HTML/CSS

---

## License

Educational project for IE 421 Data Science course at Istanbul Bilgi University.
