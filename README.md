# classification_job_retention
Data description:
df1:
'EmployeeNumber',
'Age',
'BusinessTravel',
'DailyRate',
'Department',
'DistanceFromHome',
'Education' [1='Below College', 2='College', 3='Bachelor', 4='Master', 5='Doctor'],
'EducationField',
'EmployeeCount',
'EnvironmentSatisfaction'[1='Low', 2='Medium', 3='High', 4='Very High'],
'Gender',
'HourlyRate',
'JobInvolvement'[1='Low', 2='Medium', 3='High', 4='Very High'],
'JobLevel'[ Intern, Junior, Mid, Senior, Expert],
'JobRole',
'JobSatisfaction' [1='Low', 2='Medium', 3='High', 4='Very High'],
'MaritalStatus',
'MonthlyIncome',
'MonthlyRate',
'NumCompaniesWorked'.

df2:
'EmployeeNumber',
'Over18',
'OverTime',
'PercentSalaryHike',
'PerformanceRating',
'RelationshipSatisfaction' [1='Low', 2='Medium', 3='High', 4='Very High'],
'StandardHours',
'StockOptionLevel',
'TotalWorkingYears',
'TrainingTimesLastYear',
'WorkLifeBalance'- [1='Bad', 2='Good', 3='Better', 4='Best'],
'YearsAtCompany',
'YearsInCurrentRole',
'YearsSinceLastPromotion',
'YearsWithCurrManager',
'Attrition',
'YearlyIncome'.

My task is to build a classification model that will predict if employee will leave the job or not.
