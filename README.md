#  Titanic Survival Analysis – EDA Project


An **Exploratory Data Analysis (EDA)** project that dives into the classic **Titanic dataset** to uncover factors that influenced passenger survival.  
This analysis explores passenger demographics, ticket class, fare, and more — to understand what determined who survived the tragic event.

---

##  Dataset Summary

**File:** `train.csv`  
**Data Range:** Passenger data from the **1912 Titanic shipwreck**

### **Key Columns**
- **Survived:** (0 = No, 1 = Yes)  
- **Pclass:** Ticket class (1st, 2nd, 3rd)  
- **Sex**  
- **Age**  
- **Fare**  
- **SibSp:** Siblings/Spouses aboard  
- **Parch:** Parents/Children aboard  
- **Embarked:** Port of Embarkation  

---

##  Key Analysis & Conclusions

This project includes:
- **Univariate Analysis:** Examining individual features  
- **Bivariate Analysis:** Comparing relationships between features and survival

---

###  **Univariate Analysis Conclusions**

- **Passenger Class (Pclass):**  
  Most passengers traveled in **3rd class**, but **1st class** passengers had a much higher chance of survival.

- **Survival Rate (Survived):**  
  Approximately **62%** of passengers did not survive.

- **Gender (Sex):**  
  About **64%** of the passengers were **male**.

- **Family (SibSp & Parch):**  
  Most passengers traveled **alone**. These columns were combined into a **Family Size** feature for deeper insights.

- **Age:**  
  The age distribution resembled a **normal curve**. Around **20%** of values were missing and were **imputed using the mean**.

- **Fare:**  
  The **Fare** was highly skewed — often representing a **group or family**. Adjustments were made to calculate **individual fare**.

---

###  **Bivariate Analysis Conclusions**

- **Gender vs Survival:**  
  **Females** had a significantly higher chance of survival.

- **Class vs Survival:**  
  **1st class** passengers had the highest probability of survival.

- **Fare vs Survival:**  
  Passengers with **higher fares** were more likely to survive, correlating with **higher class**.

- **Embarked vs Survival:**  
  Passengers who **embarked from Cherbourg (C)** had a better survival rate.

---

##  Overall Project Conclusion

The **Titanic Survival Analysis** reveals that survival was not purely by chance — it was shaped by **social, economic, and gender factors**.  

- **Females and children** were prioritized (“women and children first”).  
- **1st class** passengers had a significant advantage.  
- **Higher fare** correlated strongly with **higher survival probability**.  

This analysis brings the Titanic tragedy into focus through **data visualization and storytelling**, showing how inequality played a defining role in survival outcomes.
