# Diabetes Regression Analysis — Exploring Predictors and Sex Differences

This project applies **linear regression analysis** to a subset of the classic scikit-learn Diabetes dataset, with a specific focus on understanding the impact of the **sex variable** on predicted disease progression. The analysis combines exploratory data work, regression modelling, and careful interpretation to explore how biomedical predictors contribute to outcomes.

Rather than treating this solely as a mathematical exercise, the project extends the core task by examining whether prediction and interpretation differ between male and female observations. The findings suggest that **sex information contributes meaningfully to model behaviour**, with potential implications for understanding sex-specific testing and treatment strategies.

---

## What’s in this repository

- **Jupyter Notebook:** full regression analysis (`diabetes.ipynb`)  
- **Dataset:** `diabetes_dirty.csv`  
- **Images:** visual summaries of model results  
- **Requirements:** Python dependencies (`requirements.txt`)  

---

## Project Context

The Diabetes dataset includes ten feature variables — age, sex, body mass index, average blood pressure, and six blood serum measurements — alongside a quantitative measure of disease progression one year after baseline.

The core task was to clean the dataset and build a **linear regression model** to predict disease progression. This project extends that task by explicitly examining the role of the sex variable and considering how its inclusion affects both model performance and interpretability.

---

## Approach Overview

The analysis follows a structured regression workflow:

- Data inspection, cleaning, and validation  
- Feature preparation and alignment for linear modelling  
- Construction and evaluation of a baseline linear regression model  
- Inclusion and exclusion of the sex variable to assess its impact  
- Interpretation of coefficients and model behaviour  

Throughout the analysis, emphasis was placed on understanding *why* predictors matter, not just whether they improve numerical performance.

---

## Key Insights / Findings

- Including the sex variable altered both coefficient values and overall model interpretation.  
- Sex was found to contribute meaningfully to variation in predicted disease progression.  
- Regression coefficients provided interpretable insights into how physiological factors relate to outcomes.  
- The analysis highlighted the importance of careful feature consideration when modelling biomedical data.  

Overall, the project reinforced that seemingly simple variables can have important implications for interpretation and downstream decision-making.

---

## Skills Demonstrated

**Analysis**
- Exploratory data analysis and feature inspection  
- Data cleaning and preparation for regression  

**Modelling**
- Linear regression modelling  
- Coefficient interpretation and comparison  

**Evaluation**
- Assessment of feature relevance and model behaviour  

**Tools**
- Python  
- pandas  
- scikit-learn  
- matplotlib / seaborn  
- Jupyter Notebook  

---

## Requirements

Install the required Python packages with: `pip install -r requirements.txt`

---

## Why this project belongs in my portfolio
This project demonstrates my ability to apply regression modelling thoughtfully in a biomedical context and to extend a standard task through careful questioning and interpretation.

By examining the role of sex as a predictor — rather than accepting default model configurations — the analysis reflects an approach focused on understanding data, assumptions, and real-world implications, rather than optimisation alone.

