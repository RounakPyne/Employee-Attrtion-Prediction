# Employee-Attrtion-Prediction and analysis

* This document provides an overview of the Employee Retention Analysis project where logistic regression was used to predict employee attrition with an accuracy of 86%.

**Attrition:- company losing its customer base**

Attrition is a process in which the workforce dwindles at a company, following a period in which a number of people retire or resign, and are not replaced.

* A reduction in staff due to attrition is often called a hiring freeze and is seen as a less disruptive way to trim the workforce and reduce payroll than layoffs
* In this NoteBook our Aim will be to analyze the datasets completely wrt each and feature and find the reasin behind Attrition of Employees.
* And what the top factors which lead to employee attrition?
  
* **Description about the data**

* Age: A period of employee life, measured by years from birth.
* Attrition: The departure of employees from the organization.
* BusinessTravel: Did the employee travel on a business trip or not.
* DailyRate: Employee salary for the period is divided by the amount of calendar days in the period.
* Department: In which department the Employee working.
* DistanceFromHome: How far the Employee live from the office location.
* Education: In education 1 means 'Below College', 2 means 'College', 3 means 'Bachelor', 4 means 'Master', 5 means 'Doctor'
* EducationField: In which field Employee complete his education.
* EmployeeCount: How many employee working in a department
* EmployeeNumber: An Employee Number is a unique number that has been assigned to each current and former State employee and elected official in the Position and Personnel DataBase (PPDB).
* Job involvement: Is the degree to which an employee identifies with their work and actively participates in it where 1 means 'Low', 2 means 'Medium', 3 means 'High', 4 means 'Very High'
* JobLevel: Job levels, also known as job grades and classifications, set the responsibility level and expectations of roles at your organization. They may be further defined by impact, seniority, knowledge, skills, or job title, and are often associated with a pay band. The way you structure your job levels should be dictated by the needs of your unique organization and teams.
* JobRole: What is the jobrole of an employee.
* JobSatisfaction: Employee job satisfaction rate where, 1 means 'Low', 2 means 'Medium', 3 means 'High', 4 means 'Very High'
* MaritalStatus: Marital status of the employee.
* MonthlyIncome: total monetary value paid by the organization to an employee.
* MonthlyRate: The per-day wage of the employee.
* NumCompaniesWorked: Before joining this organization how many organizations employee worked.
* Over18: Is the employee age over than 18 or not.
* OverTime: A Employee works more than 9 hours in any day or for more than 48 hours in any week.
* PercentSalaryHike:
* PerformanceRating 1 'Low' 2 'Good' 3 'Excellent' 4 'Outstanding'
* EnvironmentSatisfaction 1 'Low' 2 'Medium' 3 'High' 4 'Very High'
* RelationshipSatisfaction 1 'Low' 2 'Medium' 3 'High' 4 'Very High'
* StandardHours: Is the number of hours of production time that should have been used during an working period.
* StockOptionLevel: Employee stock options, also known as ESOs, are stock options in the company’s stock granted by an employer to certain employees. Typically they are granted to those in management or officer-level positions. Stock options give the employee the right to buy a certain amount of stock at a specific price, during a specific period of time. Options typically have expiration dates as well, by which the options must have been exercised, otherwise they will become worthless.
* TotalWorkingYears: Total years the employee working in any organization
* TrainingTimesLastYear: Last year how many times employee took training session.
* WorkLifeBalance 1 'Bad' 2 'Good' 3 'Better' 4 'Best'
* YearsAtCompany: How many years the employee working in the current organization
* YearsInCurrentRole: How many years the employee working in the current position
* YearsSinceLastPromotion: How many years the employee working in the current position after promotion
* YearsWithCurrManager: How many years the employee working under the current manager

***Model Summary***

A logistic regression model was employed to predict employee attrition based on the above features. The model achieved an accuracy of 86%, indicating a high level of predictive performance.

***Key Findings***

Age and YearsAtCompany were significant predictors of attrition.
Employees with lower JobSatisfaction and WorkLifeBalance ratings were more likely to leave.
DistanceFromHome and OverTime also played a significant role in predicting attrition.

***Conclusion***

This analysis provides valuable insights into the factors contributing to employee attrition. The logistic regression model with 86% accuracy can be used to identify at-risk employees and develop targeted retention strategies.
