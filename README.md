🧠 OCD Comorbidity Analysis

Author: Tanisha Kumar<br>
Date: September 2025<br>
Language/Tools: Python, Jupyter Notebook, Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn

📌 Project Overview

Obsessive-Compulsive Disorder (OCD) is a complex mental health condition that can co-occur with other mental health disorders such as Anxiety and Depression. Understanding whether demographic factors (age, sex, ethnicity, education, marital status) influence OCD comorbidity patterns may provide insights into patient vulnerability and treatment planning.

This project uses a synthetic dataset of 1,500 simulated OCD patients to explore potential patterns and relationships between demographic factors and OCD comorbidities. It focuses on exploratory data analysis (EDA) and baseline predictive modeling.

🎯 Objectives

Explore the distribution of OCD comorbidities (Anxiety Only, Depression Only, Both, None) in the dataset.

Analyze how demographic variables interact with comorbidity patterns.

Evaluate whether demographic factors can predict comorbidity status using baseline predictive models (Logistic Regression, Random Forest).

Explore clustering using K-Means to identify any natural groupings among patients.

📊 Dataset

Source: Kaggle (synthetic dataset) Link to dataset

Size: 1500 rows × 17 columns

Relevant Features:

Age: Patient age (18–75)

Sex: Biological sex at birth (Male/Female)

Ethnicity: (African, Asian, Caucasian, Hispanic)

Marital Status: (Single, Divorced, Married)

Education Level: (High School, Some College, College Degree, Graduate Degree)

Depression Only: Binary indicator for depression diagnosis alongside OCD

Anxiety Only: Binary indicator for anxiety diagnosis alongside OCD

⚠️ Note: The dataset is synthetic and intended solely for analysis and demonstration purposes. Observed patterns do not represent real patients.

🔎 Analysis Approach
1. Data Preprocessing

Missing value checks (none found)

Binary encoding of depression and anxiety diagnoses

Creation of multi-class labels: Depression Only, Anxiety Only, Both, None

One-hot encoding for categorical features

2. Exploratory Data Analysis (EDA)

Overall distribution of comorbidities

Age-wise and demographic comparisons

Heatmaps, mosaic plots, and Sankey diagrams to visualize interactions

3. Predictive Modeling

Logistic Regression (multinomial)

Random Forest Classifier

Evaluation of predictive performance (classification reports & confusion matrices)

4. Clustering

K-Means clustering to explore natural groupings among patients

📈 Key Findings

No strong association observed between demographic variables and OCD comorbidity.

Age, sex, ethnicity, education, and marital status do not significantly differentiate comorbidity categories.

Predictive models (Logistic Regression, Random Forest) performed poorly, with accuracies around or below random guessing levels for a four-class problem.

K-Means clustering did not reveal meaningful clusters that correspond to comorbidity patterns.

➡️ Overall, demographic factors in this synthetic dataset are minimally informative for predicting OCD comorbidity.

📊 Visualizations

The project includes:

Pie charts and bar plots showing comorbidity distributions

Boxplots for age comparisons across demographics

Heatmaps for gender × ethnicity interactions

Mosaic plots for education × marital status interactions

Sankey diagrams showing demographic flows to comorbidity outcomes

📷 Screenshots of key visualizations are included in the notebook for reference.

Additionally, two key plots have been exported as interactive HTML files (via Plotly) and hosted on GitHub Pages for direct exploration:

🔗 Interactive Heatmap
 — corresponds to the notebook section “OCD Comorbidity by Sex × Ethnicity”.

🔗 Interactive Sankey Diagram
 — corresponds to the notebook section “OCD Patients Through Ethnicity, Education Level, Marital Status: A Flow to OCD Comorbidity”.

These links are provided so stakeholders and readers can interact with the visualizations directly, beyond static screenshots.

✅ Conclusion

This project demonstrates a structured approach to EDA, baseline predictive modeling, and clustering, even when no strong patterns are present. It highlights the importance of careful data exploration before attempting prediction or inference, and provides a framework for similar health informatics analyses.