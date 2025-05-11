# Employee-Data-Analysis
This project is an analysis on an employee data for a company with frequent attrition of employees using a python-based data analysis techniques. 

This analysis would be focusing on each feature in the data to check the reason for the attrition and predict whether there would be more employees leaving the company. 

We would continue with the Exploratory Data Analysis to help unravel the reason for continuous employee attrition.

With the rate of attrition of employees, the management of the company should have to check the infeerence fron the anaylsis to determine what drives the attrition of their employees and the period they leave the company.

**The dataset (employee_data.csv) has 1470 entries (rows) and 35 features (columns)**:  
Age, Attrition, BusinessTravel, DailyRate, Department, DistanceFromHome, Education, EducationField, EducationField, EmployeeNumber, EnvironmentSatisfaction, Gender, HourlyRate, JobInvolvement, JobLevel, JobRole, JobSatisfaction, MaritalStatus, MonthlyIncome, MonthlyRate, NumCompaniesWorked, Over18, OverTime, PercentSalaryHike, PerformanceRating, RelationshipSatisfaction, StandardHours, StockOptionLevel, TotalWorkingYears, TrainingTimesLastYear, WorkLifeBalance, YearsAtCompany, YearsInCurrentRole, YearsSinceLastPromotion and YearsWithCurrManager.

**Methodolgy**
**The analysis makes use of these python libraries:**
pandas for data reading and manipulation, numpy for numerical operations, matplotlib for visualization seaborn for enhanced visualization, scikit-learn for preprocessing categorical data.

The categorical variables like gender' and 'overtime' were encoded using the mapping and LabelEncoder to enhance numerical analysis.

**Key Findings**
**Summary Statistics**
The describe function was used on the data to output statistical values like mean, stanndard deviation (std), the minimum and maximum values and the 3 percentile/quartile (25th, 50th and 75th) values of  the numerical features in the data. 

The age feature had 1470 counts, a mean to be 36.92,  a std of about 9.14, minimum and maximum values of 18 and 60 respectively. The 25th, 50th and 75th percentile of the age feature is 30, 36 and 43 accordingly.

**Relationship Analysis And Visualization**
Pie plots between 'Age' and 'Attrition', 'Gender' and 'Attrition'  as well as bar plots on 'Attrition' and 'Overtime', 'Monthlyincome' and 'Attrition' were done to check their relationship and how they affect each other. 

These visualizations amongst others was to check if the age, gender, monthlyincome or overtime coyld be possible reasons for employees leaving the company in large numbers.

**Model Building**
The features with extreme values were scaled so that the values do not affect the outcome of the model.
THe data was splitted in to train data to train the model and test data to test if the model learnt well on the train data.
Logistic regression model was used for the prediction. Accuracy of the model was checked after model building.
**Conclusion**
The analysis help determine possible reasons for the attrition of the company employees using the employee data.
