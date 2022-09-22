# classification_job_retention
Data description:
df1:
'EmployeeNumber'-numer pracownika,
'Age'-wiek pracownika,
'BusinessTravel'- informacja na temat podróży służbowych w pracy,
'DailyRate'- dzienny koszt dla pracodawcy,
'Department'- dział, w którym pacuje pracownik,
'DistanceFromHome'- odległość od domu,
'Education'- poziom edukacji [1='Below College', 2='College', 3='Bachelor', 4='Master', 5='Doctor'],
'EducationField'- dziedzina edukacji,
'EmployeeCount'-ilość osób reprezentowanych przez dany wpis,
'EnvironmentSatisfaction'- satysfakcja z otoczenia w pracy [1='Low', 2='Medium', 3='High', 4='Very High'],
'Gender'- płeć,
'HourlyRate'- stawka godzinowa,
'JobInvolvement'- zaangażowanie w pracy [1='Low', 2='Medium', 3='High', 4='Very High'],
'JobLevel'-poziom w pracy [prawdopodobnie Intern, Junior, Mid, Senior, Expert],
'JobRole'- stanowisko pracy,
'JobSatisfaction'- satysfakcja z pracy [1='Low', 2='Medium', 3='High', 4='Very High'],
'MaritalStatus'- stan cywilny,
'MonthlyIncome'- dochód miesięczny,
'MonthlyRate'- miesięczny koszt dla pracodawcy,
'NumCompaniesWorked'- liczba firm, w których przepracował wcześniej.

df2:
'EmployeeNumber'- numer pracownika,
'Over18'- powyżej 18 roku życia,
'OverTime'- nadgodziny,
'PercentSalaryHike'- podwyżka procentowa wynagrodzenia,
'PerformanceRating'- ocena wydajności,
'RelationshipSatisfaction'- zadowolenie z relacji [1='Low', 2='Medium', 3='High', 4='Very High'],
'StandardHours'- standardowa liczba godzin pracy,
'StockOptionLevel'- jaki procent akcji posiada/może posiadać pracownik,
'TotalWorkingYears'- liczba przepracowanych lat,
'TrainingTimesLastYear'- liczba szkoleń w zeszłym roku,
'WorkLifeBalance'- [1='Bad', 2='Good', 3='Better', 4='Best'],
'YearsAtCompany'- licza lat w firmie,
'YearsInCurrentRole'- liczba lat na danym stanowisku,
'YearsSinceLastPromotion'- liczba lat od ostatniego awansu,
'YearsWithCurrManager'- liczba lat z obecnym managerem,
'Attrition'- informacja czy dany pracownik odszedł z pracy, czy też nie,
'YearlyIncome'- roczne zarobki.

My task is to build a model that will predict if employee will leave the job or not.
