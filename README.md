# Data Analysis & Visualization

## 🎯 Objective

The purpose of this task is to explore the Titanic dataset by generating statistical summaries and visualizations to understand the relationships between features and uncover hidden patterns in the data.

---

## 📝 Key Steps Performed

1. **Generate summary statistics**
   - Calculated **mean**, **median**, **standard deviation**, and other basic statistics using `.describe()` and `.agg()` functions.

2. **Visualize distributions**
   - Created **histograms** and **boxplots** for numerical columns like `Age`, `Fare`, `SibSp`, and `Parch`.

3. **Explore feature relationships**
   - Used **pairplot** and **correlation heatmap** to visualize relationships and correlations between features.

4. **Identify patterns and anomalies**
   - Observed trends in age groups, fare brackets, and family size, including outliers and skewness in distributions.

5. **Make basic inferences from visuals**
   - Derived feature-level insights such as:
     - Younger passengers had higher survival rates.
     - Female passengers were more likely to survive.
     - Passengers in higher classes tended to survive more.

---

### 📊 Plots Used

- Histogram and KDE plots (Age, Fare)
- Count plots (Sex, Pclass, Embarked vs Survived)
- Boxplots (Age vs Pclass, Fare vs Pclass)
- Bar charts (Sex vs Survival, Embarked vs Survival)
- Heatmap (Feature correlation matrix)

---

## 💡 Insights Gained

- **Age and Survival**: Younger passengers had better survival rates.
- **Gender Role**: Women had a significantly higher survival rate.
- **Fare Distribution**: Highly skewed; presence of outliers.
- **Family Size Impact**: Passengers with small families had higher survival.
- **Class-Based Trend**: First-class passengers had the highest survival rate.

---
