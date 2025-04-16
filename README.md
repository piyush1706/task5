#  Task 5: Exploratory Data Analysis (EDA) - Titanic Dataset

##  Objective
Perform Exploratory Data Analysis (EDA) on the Titanic dataset to extract meaningful insights and visualize relationships between features that may influence survival.

---

##  Files Used
- train.csv: Training dataset containing labeled data
- test.csv: Test dataset for future prediction (not used directly in this EDA)
- titanic_eda.ipynb: Jupyter Notebook performing all EDA steps
- titanic_eda_report.pdf: Exported report containing visualizations and written insights

---

##  Tools & Libraries
- Python
  - pandas
  - numpy
  - matplotlib
  - seaborn

---

##  Steps Performed

### 1. *Initial Exploration*
- Loaded train.csv and previewed data
- Used .info(), .describe(), .value_counts() for data overview
- Checked for missing values and data types

### 2. *Univariate Analysis*
- Plotted histograms and countplots to observe distributions of features like:
  - Age
  - Fare
  - Survived
  - Pclass
  - Sex

### 3. *Bivariate Analysis*
- *Boxplot*: Age vs Survived to identify survival trends by age group
- *Countplot*: Survival rate by Sex and Pclass
- *Heatmap*: Correlation matrix of numerical features

### 4. *Multivariate Visualization*
- Optional: Pairplot and scatterplots to observe multiple features together

---

##  Key Visuals
- Boxplot: Age vs Survival
- Heatmap: Feature correlation
- Countplot: Gender and Pclass impact on survival

---

##  Insights (Summary)
- *Females had higher survival rates* than males.
- *Younger passengers* were more likely to survive.
- *1st class passengers* had better survival chances than 2nd or 3rd class.
- *Fare* and *Pclass* showed moderate correlation with survival.

---

##  Output
-  Jupyter Notebook: titanic_eda.ipynb
-  PDF Report: titanic_eda_report.pdf

---

##  Note
This EDA is only for visualization and insight generation. No model training is involved in this task.

---

##  Author
PIYUSH KUMAR 
Information Technology 
