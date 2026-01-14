# Python Titanic Survival Analysis

## Project Overview
This project analyzes the **Titanic passenger dataset** to explore whether there is a correlation between passenger characteristics and their **chances of survival**.

The analysis was developed using **Python** as part of a **Data Analyst training program**, focusing on data cleaning, exploratory data analysis (EDA), visualization, and interpretation of results.

---

## Objectives
- Explore survival patterns among Titanic passengers  
- Analyze the impact of **gender, age, passenger class, and family size** on survival  
- Identify correlations between numerical variables  
- Answer research questions related to survival probability  

---

## Dataset
- **Dataset:** Titanic passenger data (educational dataset)
- **Key variables include:**
  - Passenger class (`Pclass`)
  - Survival indicator (`Survived`)
  - Gender (`Sex`)
  - Age
  - Fare
  - Family relationships (`SibSp`, `Parch`)
  - Port of embarkation (`Embarked`)

---

## Data Preparation
The following data preparation steps were performed:
- Checked missing values across all columns  
- Removed the **Cabin** column due to a high percentage of missing values  
- Filled missing **Age** values using the median age by gender  
- Filled missing **Embarked** values using the most frequent category  
- Created a **Family Size** variable: FamilySize = SibSp + Parch + 1

  
---

## Exploratory Data Analysis
The analysis included:
- Distribution of passengers by **gender**
- Survival distribution by **gender**
- Age distribution by **gender and survival status**
- Correlation analysis between numerical variables
- Survival rate by **passenger class**
- Survival rate by **family size**
- Passenger distribution by family size and class

---

## Key Insights
- **Women and children** had significantly higher survival rates  
- **First-class passengers** showed the highest survival probability  
- Passengers traveling **alone** represented the majority of travelers  
- **Families of four** had the highest survival rate among family groups  
- Passenger class shows a **moderate negative correlation** with survival  
- Fare is **positively correlated** with survival probability  

---

## Project Deliverables
- Jupyter Notebook with full analysis and visualizations  
- Presentation (PDF) summarizing methodology, insights, and conclusions  

---

## Tools Used
- **Python**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
- **Jupyter Notebook**

---

## Repository Structure
├── data/

│ └── README.md

├── notebook/

│ └── Projeto_Python.ipynb

├── presentation/

│ └── Titanic_Python_Project.pdf

└── README.md


---

## What I Learned
- Handling missing data using domain logic  
- Performing exploratory data analysis (EDA) in Python  
- Visualizing data distributions and relationships  
- Interpreting correlation matrices  
- Translating analytical results into clear conclusions  

---

## Author
**Luís Machado**  
Junior Data Analyst  

**Tools:** SQL | Excel | Power BI | Python  

