# Online-Learning-Analytics
The project is implemented using python for data science concepts
Name : Jinal Nilesh Talati
Enrollment number : 240090107059

Information regarding the project are as follows : 
# Online Learning Engagement Analytics

## 📌 What this project does
This project studies data from 50,000 online students to understand:
- Why some students get good grades and others don't
- Why some students drop out of courses
- How to find "at-risk" students early, before they drop out

## 📂 Dataset
- File: `online_learning_engagement_dataset.csv`
- 50,000 students, 18 columns (age, country, device used, study hours, 
  quiz scores, attendance, final grade, dropout status, etc.)

## 🛠️ Tools Used
- **Python** – main programming language
- **Pandas & NumPy** – to clean and organize the data
- **Matplotlib & Seaborn** – to make normal charts and graphs
- **SciPy** – to run statistical tests (checking if a pattern is real or just chance)
- **Scikit-learn** – to build machine learning models
- **Plotly** (extra topic, beyond the syllabus) – to make interactive charts you can click, zoom, and hover on

## 🔍 What was done (step by step)
1. **Loaded and checked the data** – looked for missing values, wrong values, and errors
2. **Cleaned the data** – fixed impossible values (like negative time) and checked outliers
3. **Explored the data** – used Pandas to group and summarize students by country, device, engagement level, etc.
4. **Ran statistical tests** – checked things like "do students who attend more classes drop out less?"
5. **Made charts** – showed grade distributions, dropout patterns, and correlations
6. **Built machine learning models**
   - One model predicts a student's **final grade**
   - Another model predicts if a student will **drop out**
   - Used clustering to group students into 4 types of learners
7. **Made interactive charts with Plotly**
   - A world map showing dropout rate by country
   - A 3D chart of student groups
   - Charts with dropdown menus and hover details

## 📊 Main Results
- Students who attend classes regularly and submit assignments get better grades and drop out less
- Things like device type, gender, or country barely matter for grades
- The dropout-prediction model correctly
