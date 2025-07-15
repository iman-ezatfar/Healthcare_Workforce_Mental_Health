# Maternal-Health-Risk

Overview
The Healthcare Workforce Mental Health Dataset provides structured data designed
for exploring and visualizing workplace mental health trends in the healthcare
industry. With 5,000 synthetic employee records, this dataset captures key
workforce-related mental health factors, including stress levels, burnout frequency,
job satisfaction, mental health absences, and turnover intention.
This dataset is ideal for data analysts, students, and career changers looking to
practice data exploration, workforce analytics, and interactive dashboard creation. It
is fully compatible with a Power BI Dashboard Template, which provides pre-built
visualizations for uncovering trends in burnout, stress factors, and turnover risks

-----------------------------------------------------------------------------------

Columns in the Dataset
1. Employee ID – Unique identifier for each employee (e.g., HCP-00001).
2. Employee Type – Role in the healthcare system (e.g., Registered Nurse,
Physician, Medical Assistant).
3. Department – Department where the employee works (e.g., General Medicine,
ICU, Pediatrics).
4. Workplace Factor – Primary workplace challenge affecting the employee (e.g.,
Heavy Workload, Poor Work Environment, Career Stagnation).
5. Stress Level – A 1-10 scale measuring workplace-related stress.
6. Burnout Frequency – Categorical variable indicating how often an employee
experiences burnout:
○ Never
○ Occasionally
○ Often
7. Job Satisfaction – 1-5 scale rating job satisfaction:
○ 1 = Very Dissatisfied
○ 5 = Very Satisfied
8. Access to EAPs – Whether the employee has access to Employee Assistance
Programs (Yes/No).
9. Mental Health Absences – Number of mental health-related leave days taken.
10. Turnover Intention – Whether the employee is considering leaving their role
(Yes/No).
--------------------------------------------------------------------------------


Key Data Relationships & Trends
These relationships between columns provide meaningful insights into workforce
mental health:
✔ Employee Type → Workplace Factor: Different roles experience unique stressors.
● Example: Registered Nurses report Heavy Workload, while Healthcare
Administrators report Career Stagnation.
✔ Workplace Factor → Stress Level: Certain stressors have a stronger impact on
workplace stress.
● Example: Heavy Workload is associated with higher stress levels.
✔ Stress Level → Burnout Frequency: Higher stress levels increase burnout
occurrence.
● Employees with a stress level of 8-10 are more likely to experience frequent
burnout.
✔ Burnout Frequency → Job Satisfaction: Employees who frequently experience
burnout report lower job satisfaction.
● Those in the "Often" burnout category tend to have job satisfaction scores of
1-2.
✔ Job Satisfaction + Stress Level → Turnover Intention: Employees with low job
satisfaction and high stress are more likely to consider leaving.
● Example: Employees with Job Satisfaction ≤ 2 and Stress Level ≥ 7 are high
turnover risks.
✔ Access to EAPs → Mental Health Absences: Employees with access to Employee
Assistance Programs (EAPs) take fewer mental health absences.
● Those without access to EAPs tend to have higher absence rates due to stress.
