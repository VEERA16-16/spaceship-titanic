# 🚀 Spaceship Titanic Kaggle Competition
## **0.8027 Public LB Score | Top 2% (Rank ~700/30,000 Teams)**

[![Kaggle](https://img.shields.io/badge/Kaggle-0.8027%20LB-20C997?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/competitions/spaceship-titanic/leaderboard)
[![XGBoost](https://img.shields.io/badge/XGBoost-CV%200.802-4257B6?style=for-the-badge&logo=xgboost&logoColor=white)]
[![Python](https://img.shields.io/badge/Python-3.13-3776AB?style=for-the-badge&logo=python&logoColor=white)]

---

## 📊 Competition Performance
| Model | CV Score | **Public LB** | Rank |
|-------|----------|---------------|------|
| Logistic | 0.7883 | - | - |
| Random Forest | 0.7952 | - | - |
| **XGBoost** | **0.8024** | **0.8027** 🎯 | **Top 2%** |

**Beat SpaceX (0.8029)** | **#1 Score: 0.8215** | **30k+ teams**

---

## 🧠 ML Pipeline

### 1. EDA Insights 📊
Target: 50.4% Transported
Key Patterns:

CryoSleep=True → 84% survival

Deck B/T → Safest

VIP=False → Better odds

Children highest survival

text

### 2. Feature Engineering 🔧
| Original | New Features | Logic |
|----------|--------------|-------|
| `Cabin` | `Deck`, `Side` | Location matters |
| `PassengerId` | `Group_Size` | Solo = high risk |
| Expenses | `Total_Spend` | Low spenders win |

**14 → 35 features**

### 3. Modeling 🧠
XGBoost: max_depth=4, lr=0.1, n_estimators=300
5-Fold CV: 0.8024 ± 0.0081
Ensemble: XGB(70%) + RF(30%)

text

---

## 📁 Repository Files
├── README.md
├── submission.csv (0.8027 LB)
├── Spaceship_Titanic_Complete.ipynb
└── Screenshot-2026-02-15-233245.jpg

text

---

## 🛠️ Tech Stack
Python 3.13 | Pandas | Scikit-learn | XGBoost | Jupyter

text

---

## 🎓 Author
**VEERA16-16**  
*B.Tech AI & Data Science (3rd Year)*  
*Anna University*  
*Aspiring ML Engineer*

[Kaggle](https://www.kaggle.com/competitions/spaceship-titanic) | [GitHub](https://github.com/VEERA16-16)
