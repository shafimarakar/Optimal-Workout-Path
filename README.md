# 🏋️ Fitness, Nutrition & Workout Performance Analytics

## 📌 Project Overview
This project analyzes **fitness performance, workout efficiency, cardio health, and nutrition patterns** using a comprehensive dataset covering workouts, body metrics, heart rate data, and dietary intake.

The goal is to uncover **actionable insights** on:
- Workout effectiveness
- Calorie burn patterns
- Cardio intensity & heart health
- Nutrition balance across difficulty levels
- Exercise-level calorie efficiency

The analysis is built using **Power BI** with a strong focus on **data cleaning, KPI design, and business-relevant visualization**.

---

## 🛠 Tools & Technologies
- **Power BI**
- **Power Query (ETL & data cleaning)**
- **DAX (Measures & KPIs)**
- **Python (EDA & Correlation Analysis – Jupyter Notebook)**

---

## 📊 Dashboard Pages

### 1️⃣ Fitness Overview
Provides a high-level snapshot of overall fitness metrics.

**Key KPIs**
- Average BMI  
- Average Body Fat %  
- Average Calories Burned  
- Average Session Duration  

**Insights**
- Clear relationship between session duration and calories burned
- Balanced gender participation
- Experience level strongly impacts calorie expenditure

📸 *Screenshot:*  
![Fitness Overview](images/fitness_overview.PNG)

---

### 2️⃣ Workout Performance Analysis
Analyzes workout intensity and effectiveness across workout types and difficulty levels.

**Highlights**
- HIIT workouts burn significantly more calories than non-HIIT
- Advanced workouts consistently show higher calorie burn
- Strong correlation between BPM, session duration, and calorie burn

📸 *Screenshot:*  
![Workout Performance](images/workout_performance.PNG)

---

### 3️⃣ Cardio & Heart Rate Analysis
Focuses on heart health and workout intensity.

**Key Metrics**
- Average % of Max Heart Rate
- Resting Heart Rate trends
- BPM distribution across workouts

**Insights**
- Most workouts operate around ~80% of Max HR
- Higher BPM correlates with higher calorie burn
- Certain strength exercises reach high cardio intensity

📸 *Screenshot:*  
![Cardio Analysis](images/cardio_heart_rate.PNG)

---

### 4️⃣ Nutrition & Diet Analysis
Examines how macronutrient intake varies by difficulty level and diet type.

**Analysis Includes**
- Calories from Carbs, Proteins, and Fats
- Diet types vs average calories burned
- Meal-type calorie distribution

**Insights**
- Carbohydrates dominate calorie intake across all difficulty levels
- Protein intake remains consistent, supporting muscle recovery
- Diet type shows marginal differences in calorie burn

📸 *Screenshot:*  
![Nutrition Analysis](images/nutrition_diet.PNG)

---

### 5️⃣ Exercise-Level Insights
Drills down into individual exercises.

**Focus Areas**
- Minimum calories burned per exercise (30 min)
- Muscle group targeting
- Exercise-level efficiency

**Insights**
- Compound exercises burn more calories than isolation movements
- Certain exercises show high effort but low calorie efficiency
- Useful for optimizing workout plans

📸 *Screenshot:*  
![Exercise Level](images/exercise_level.PNG)

---

## 🧹 Data Cleaning & Preprocessing
- Negative values in **physical and nutrition metrics** were treated as data quality issues and corrected
- Deviation-based metrics like **Efficiency** retained negative values to preserve analytical meaning
- Standardized units and removed outliers where necessary

---

## 📈 Advanced Analysis
- Correlation heatmap used to identify relationships between fitness, nutrition, and performance metrics
- Strong correlations found between:
  - Session duration ↔ Calories burned
  - Macronutrients ↔ Total calorie intake
  - Heart rate metrics ↔ Workout intensity

📸 *Screenshot:*  
![Correlation Heatmap](images/heatmap.png)

---

## 🚀 Key Takeaways
- HIIT and advanced workouts deliver the highest calorie efficiency
- Nutrition balance remains consistent across difficulty levels
- Cardio intensity is a strong driver of calorie burn
- Exercise-level analysis helps identify high-impact workouts

---

```text
fitness-analytics-project
├── README.md
├── Key_Insights.md
├── db.pbix
├── Final_data (1).csv
├── cleaned_data.csv
├── images/
│   ├── fitness_overview.PNG
│   ├── workout_performance.PNG
│   ├── cardio_heart_rate.PNG
│   ├── nutrition_diet.PNG
│   ├── exercise_level.PNG
│   ├── work_efficiency_type.png
│   └── heatmap.png
└── notebook/
    └── final_analysis.ipynb
```
---

## 👤 Author

**Muhammed Shafi**  
Aspiring Data Analyst | Power BI | Python | Data Visualization  
🔗 [LinkedIn](https://www.linkedin.com/in/muhammed-shafi-08a87326a)

