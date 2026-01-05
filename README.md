# **Credit Risk Analysis Project**

A data analysis project exploring borrower characteristics, loan behavior, and credit risk patterns using Python and Jupyter Notebook.

---

## 📌 **Project Overview**

This project analyzes credit risk data for Nova Bank to uncover insights that support data-driven decisions in loan approvals, customer evaluation, and risk management.

The analysis focuses on:
- Borrower demographics  
- Loan performance trends  
- Default indicators  
- Income-to-loan relationships  
- Credit history and utilization  
- Risk segmentation  

## **Data Cleaning Summary**
The data was first cleaned before undergoing exploration. 
Data cleaning steps include:
- Removed null values.
- Dealt with logical inconsistencies i.e employment length
- Did data validations across columns
- Checked unique values in categorical columns

## **Exploratory Data Analysis Summary**

The exploratory data analysis was conducted to identify statistically relevant borrower, loan, and credit behavior variables associated with loan default risk. Emphasis was placed on feature relationships, distribution behavior, and risk-separating signals suitable for downstream modeling.

### **Borrower Demographics**
- Borrowers are concentrated within the prime working-age range, with employment length showing a negative relationship with default probability.
- Income displays high variance and non-normal distribution; lower-income segments exhibit higher sensitivity to loan size and interest rates.
- Home ownership status contributes to risk differentiation, with renters demonstrating higher default incidence relative to homeowners and mortgage holders.

### **Loan Characteristics**
- Loan amounts scale with income; however, elevated loan-to-income ratios significantly increase default likelihood.
- Loan intent exhibits class imbalance, with certain intents consistently associated with higher risk.
- Loan grade shows strong monotonic relationships with both interest rate and loan status, reinforcing its predictive strength as a categorical risk variable.

### **Credit Behavior**
- Credit utilization ratio is a strong discriminator between default and non-default populations.
- Prior delinquencies materially increase default probability and act as a high-signal risk indicator.
- Credit history length demonstrates an inverse relationship with default risk.
- Debt-to-income and loan-to-income ratios emerged as key engineered features with high explanatory power.

### **Geographic Patterns**
- Default rates vary across states and cities, suggesting spatially driven economic effects.
- Urban regions account for higher loan volumes, while certain locations show concentrated default behavior.

### **Overall Insight**
The interaction of borrower financial capacity, loan structure, and historical credit behavior drives credit risk. Features such as credit utilization, debt-to-income ratio, loan grade, employment length, and past delinquencies exhibit strong predictive relevance. They are well-suited for inclusion in supervised credit risk models.

## **Tools & Technologies used**
- Python
- Pandas, Numpy, Seaborn, Matplotlib
- Jupyter Notebook
- Claude AI


All work was completed in **Jupyter Notebook**, and visualizations are included in the repository.




