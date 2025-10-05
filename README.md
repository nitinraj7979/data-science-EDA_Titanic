# EDA – Titanic Dataset

**Goal:** Explore Titanic passenger data to identify factors that influenced survival and prepare features for a simple predictive model.

## Dataset
- Source: Kaggle — *Titanic: Machine Learning from Disaster* 
- Files included: `titanic.csv`

## What I did
1. Data overview and missing value analysis  
2. Univariate & bivariate analysis (Pclass, Sex, Age, Fare, Embarked, Family)  
3. Feature engineering: `Title`, `FamilySize`, `IsAlone`, `CabinLetter`, `AgeBin`  
4. Missing value handling (Age imputed by Title median, Fare median, Embarked mode)  
5. Simple baseline model: Logistic Regression with preprocessing pipeline  
6. Key findings and recommendations

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook

## Key findings (summary)
- Gender (female) had significantly higher survival rates.  
- Higher passenger class and lower fare correlated with lower survival.  
- Family size had an effect: very small or very large families had different survival rates.  

## Files
- `titanic_eda.ipynb` — Jupyter notebook with all code, plots and narrative  
- `titanic.csv` — datasets

## How to reproduce
1. Clone repo  
2. Create virtualenv and install `requirements.txt`  
3. Open `titanic_eda.ipynb` and run all cells

---

If you find this project useful, feel free to ⭐ the repo or reach out at nitinraj.7979@gmail.com
