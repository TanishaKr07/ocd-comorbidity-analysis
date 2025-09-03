# OCD Comorbidity Analysis  

This project explores whether demographic factors can predict comorbidities of Obsessive-Compulsive Disorder (OCD), using a synthetic dataset of 1,500 patients.  

👉 [View the full project on GitHub](https://github.com/TanishaKr07/ocd-comorbidity-analysis)  

## Overview  
Obsessive-Compulsive Disorder (OCD) often co-occurs with Anxiety, Depression, or both.  
This project uses demographic factors (age, sex, ethnicity, marital status, education) to explore whether these comorbidities can be predicted.  

## Key Findings  
- No strong associations between demographics and comorbidity outcomes.  
- Logistic Regression and Random Forest both performed poorly (~25% accuracy, near random).  
- K-means clustering revealed no distinct groupings.  
- Overall: demographic factors are not strong predictors of OCD comorbidity in this dataset.  

## Visuals  
Here are a few key graphs:  
![Pie chart of comorbidities](images/comorbidity_pie.png)  
![Heatmap of sex × ethnicity](images/heatmap.png)  
![Sankey diagram](images/sankey.png)  

## Tools  
Python, Jupyter Notebook, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly  

---