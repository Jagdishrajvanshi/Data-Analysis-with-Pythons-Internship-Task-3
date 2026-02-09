# Data-Analysis-with-Pythons-Internship-Task-3
Internship project showcasing Titanic data analysis using Python.  Includes exploratory data analysis, feature engineering, and  visualizations to understand survival patterns.
## 📌 Task Objective
- Perform Exploratory Data Analysis on the Titanic dataset
- Handle missing values
- Create new features for better insights
- Analyze survival patterns using visualizations

---

## 📊 Dataset
- Titanic Dataset  
- Source: Kaggle / Seaborn Titanic Dataset

---

## 🧹 Data Cleaning
- Missing values in the **Age** column were filled using the median value
- Rows with missing **Embarked** values were removed

---

## 🧠 Feature Engineering
- **AgeGroup** created by categorizing passengers into:
  - Child, Teen, Young Adult, Adult, Senior
- **FamilySize** created using:
  - `FamilySize = SibSp + Parch + 1`

---

## 📈 Exploratory Data Analysis Performed
- Survival rate analysis by **Age Group**
- Survival rate analysis by **Embarkation Port**
- Survival rate analysis by **Family Size**
- Correlation analysis using a **heatmap**

---

## 📊 Visualizations
- Bar chart: Survival Rate by Age Group
- Bar chart: Survival Rate by Embarkation Port
- Bar chart: Survival Rate by Family Size
- Correlation Heatmap of numerical features

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- Seaborn
- Matplotlib
- Google Colab / Jupyter Notebook

---

## ✅ Key Insights
- Children and young adults had higher survival rates
- Survival varied based on embarkation port
- Small to medium family sizes showed better survival chances
- Passenger class and fare showed correlation with survival

---

## 📂 File Included
- `Titanic_EDA_Data_Analysis_Task3_Jagdish.ipynb`

---

## 👤 Author
**Jagdish Rajvanshi**  
Data Science with Python Internship – Week 3
