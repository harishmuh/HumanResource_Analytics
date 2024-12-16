![HRBackdrop](https://github.com/harishmuh/HumanResource_Analytics/blob/main/Backdrop%20HR%20Analytics.PNG)

# Human Resource Analytics


## Context
**Human Resource roles in an organization**

Human Resources (HR) is a crucial department within any organization that responsible for managing various aspects related to employees. This includes recruiting and hiring new talent, training and development, performance management, employee relations, compensation and benefits, and ensuring compliance with labor laws. HR plays a vital role in shaping the company culture, fostering employee engagement, and ensuring the well-being and productivity of the workforce.

**Urgency of HR Analytics**

HR Analytics, also known as people analytics, is the application of data analysis techniques to HR data. It involves collecting, analyzing, and reporting HR data to improve decision-making and enhance HR processes. The importance of HR Analytics in a company includes:

* Improved Decision-Making: By analyzing HR data, companies can make more informed decisions regarding hiring, promotions, and other HR activities. This helps in identifying the best candidates, understanding employee performance, and planning for future workforce needs.

* Employee Retention: HR Analytics can help identify factors that contribute to employee turnover. By understanding these factors, companies can implement strategies to improve employee satisfaction and retention, thereby reducing costs associated with hiring and training new employees.

* Cost Reduction: Effective use of HR Analytics can lead to significant cost savings. For instance, optimizing recruitment processes, reducing turnover rates, and improving workforce planning can all contribute to lower operational costs.

* Improved Employee Experience: By analyzing data on employee engagement, satisfaction, and well-being, companies can create a better work environment. This leads to higher employee morale, increased productivity, and a more positive company culture.

**Attrition**
* In the field of Human Resources (HR), attrition refers to the gradual reduction of the workforce within an organization due to factors such as resignations, retirements, or other voluntary or involuntary separations, without the organization actively replacing the departed employees.

**HR Analytics Role in managing Attrition**

HR analytics plays a pivotal role in helping companies manage attrition by turning employee-related data into actionable insights. By analyzing patterns and trends, HR teams can identify key factors contributing to employee turnover, such as dissatisfaction with compensation, limited career growth, or poor work-life balance. 

### **Problem Statement**

Employee attrition poses a crucial challenge to the healthcare sector, where retaining skilled talent is crucial for maintaining operational efficiency and customer satisfaction. High attrition rates disrupt organizational productivity, damage reputation, and increase the costs associated with recruitment and training. Despite efforts to address this issue, the company lacks data-driven insights into the underlying factors contributing to employee departures.

### **Goal**

The company in healthcare industry want to leverage data analytics to identify the key factors influencing employee attrition.

### **Objective**
* Analyze and compare demographic and internal conditions between active employees and those who have left to uncover patterns or disparities.
* Investigate whether differences in income or compensation are associated with attrition.
* Evaluate employees' perspectives on the work environment, job satisfaction, and office conditions to identify areas needing improvement.
* Assess differences in employee tenure between those who remain and those who leave to determine if tenure impacts attrition risk.

## **Data analysis**

### **Numerical variables**

![num1](https://github.com/harishmuh/HumanResource_Analytics/blob/main/numerical%20var1.PNG)

![num2](https://github.com/harishmuh/HumanResource_Analytics/blob/main/numerical%20var2.PNG)

![num3](https://github.com/harishmuh/HumanResource_Analytics/blob/main/numerical%20var3.PNG)

**Insights of Numerical Variables**
* The median age of the active employees (36) is higher than the median age of non active employees (31)
* The median DailyRate of active employees (818) is higher than the non-active employees (703)
* The DistanceFromHome from the worksite of the non active employees (9 miles) is further than the active employees (7 miles).
* The median MonthlyIncome of active employees (USD 5270) is higher than the non-active employees (USD 3140).
* The median MonthlyRate of non-active employees (14470) is little bit higher than the active employees (14222)
* The median NumCompaniesWorked of active employees (2 companies) is higher than the median non-active employees (1 company)
* The TotalWorkingYears of active employees (10) are relatively higher than the median of non active employees (7). The active employees usually have longer experience than the non-active employees.
* The active employee have received longer time of TrainingTimesLastYear (3 training times) than the non active employees (2 training times).
* The active employee have two times longer spend YearsAtCompany than the non active employee (3 years).
* The median YearsAtCurrentRole of active employees (3) is higher than the median non-active employees (2).
* The active employees have spent longer time in YearsWithCurrManager (3 years) than the non active employees (2 years).
* There is no difference between active employees and non-active employees in median of HourlyRate and PercentSalaryHike

### **Categorical variables**

![AgeGroup](https://github.com/harishmuh/HumanResource_Analytics/blob/main/AgeGroup.PNG)
* AgeGroup: Most employees who have left company majority from the AgeGroup of 18-25 (36.8% of overall leaving employees)

![Department](https://github.com/harishmuh/HumanResource_Analytics/blob/main/Department.PNG)
* Department: Sales department had the highest percentage of leaving employees in comparison to other departments

![Gender](https://github.com/harishmuh/HumanResource_Analytics/blob/main/Gender.PNG)
* Gender: Male employees are slightly higher in percentage to leave the company than female

![MaritalStatus](https://github.com/harishmuh/HumanResource_Analytics/blob/main/MaritalStatus.PNG)
* MaritalStatus: Most leaving employees are single which two times higher in percentage than the married employees

![OverTime](https://github.com/harishmuh/HumanResource_Analytics/blob/main/OverTime.PNG)
* OverTime: Almost 1/3 of leaving employees have experienced working overtime and the percentage is three times higher than the active employees

![BusinessTravel](https://github.com/harishmuh/HumanResource_Analytics/blob/main/BusinessTravel.PNG)
* BusinessTravel: Most leaving employees have traveled frequently for the business purposes

![Education](https://github.com/harishmuh/HumanResource_Analytics/blob/main/Education.PNG)
* Education: Employee with lower education levels (Education 1 and 3) have higher attrition proportion (17.58% and 17.12%). High education level of 5 has the lowest attrition proportion (11.11%)

![EducationalBackground](https://github.com/harishmuh/HumanResource_Analytics/blob/main/EducationField.PNG)
* EducationalBackground: The educational background of leaving employees mostly consists of Human Resources (26.9%), technical degree (24.8%), and marketing (22.2%) which account for almost 3/4 of overall educational background.

![JobRole](https://github.com/harishmuh/HumanResource_Analytics/blob/main/JobRole.PNG)
* JobRole: Sales Representative are the most JobRole with highest percentage (39.8%) of leaving employees

![JobInvolvement](https://github.com/harishmuh/HumanResource_Analytics/blob/main/JobInvolvement.PNG)
* JobInvolvement: Employees with the lowest JobInvolvement (1) show the highest attrition rate (32.50%)

![JobLevel](https://github.com/harishmuh/HumanResource_Analytics/blob/main/JobLevel.PNG)
* JobLevel: Attrition is higher for entry-level positions (Job Level 1, 26.59%), while senior roles (Job Level 4 and 5) experience much lower attrition (4.72% and 7.58%).

![EnvironmentSatisfaction](https://github.com/harishmuh/HumanResource_Analytics/blob/main/EnvironmentSatisfaction.PNG)
* EnvironmentSatisfaction: Employees with low Environment Satisfaction (1) exhibit the highest attrition rate (25.56%). Those with better satisfaction (4) have significantly reduced attrition (13.48%).



![RelationshipSatisfaction](https://github.com/harishmuh/HumanResource_Analytics/blob/main/RelationshipSatisfaction.PNG)
* JobSatisfaction and RelationshipSatisfaction: Job and Relationship Satisfaction levels of 1 correlate with high attrition (22.55% and 20.45%).

![SalarySlab](https://github.com/harishmuh/HumanResource_Analytics/blob/main/SalarySlab.PNG)
* SalarySlab: The group of employees with SalarySlab up to 5k is the group with highest percentage of leaving employees.

## **Insights**

**Demographic and Internal Conditions**
* Analysis revealed significant demographic and internal differences between active and departing employees. Departing employees tend to be younger (median age: 31) and live farther from work (median distance: 9 km), indicating that these factors contribute to higher attrition risks.
* Demographic variables such as marital status, age group, and job role are associated with attrition, while education level and relationship satisfaction do not appear to play a significant role.

**Income and Compensation Differences**
* Lower income levels were identified as a critical factor influencing attrition. Departing employees had a significantly lower median monthly income (USD 3,140 vs. USD 5,207 for active employees). Similarly, daily rates showed a meaningful disparity, while other compensation-related parameters (e.g., hourly rate, salary hikes) did not show significant differences.
* The association between salary slabs and attrition further emphasizes the importance of competitive compensation to retain employees.

**Work Environment and Job Satisfaction**
* Key workplace factors, including job satisfaction, overtime, work-life balance, and involvement, were significantly associated with attrition.
* Frequent business travel and unsatisfactory environmental conditions contributed to employee dissatisfaction.

**Tenure and Career Growth**
* Employees with shorter tenures, less experience, and fewer training opportunities were more likely to leave.
* Active employees had longer total working years (10 years vs. 7 years), more years with their current manager, and more time spent in training sessions.

## **Recommendations**
**Enhance Compensation Packages**
* Review and adjust salary structures, focusing on competitive monthly income and daily rates.
* Increase access to stock options and other benefits for entry-level and mid-level employees.

**Address Work-Life Balance**
* Implement flexible work arrangements, reduce overtime, and provide better support for frequent travelers.
* Promote initiatives to improve work-life balance and employee satisfaction.

**Target Younger Employees for Retention**
* Create mentorship programs for younger employees to enhance their engagement.
* Offer incentives for early-career development and growth opportunities.

**Increase Training and Development**
* Provide more frequent and meaningful training sessions.
* Align training programs with career advancement goals to promote employee retention.

**Improve Retention Strategies by JobRole**
* Focus retention efforts on job roles like Sales Representatives, Laboratory Technicians, and Human Resources staff, which exhibit higher attrition rates.
* Develop customized strategies for each department based on their specific needs and challenges.

## Assets
* [Notebook of HR Analytics](https://github.com/harishmuh/HumanResource_Analytics/blob/main/HR_Analytics_Notebook.ipynb)
* [Slides (PDF)](https://github.com/harishmuh/HumanResource_Analytics/blob/main/HR_ANALYTICS.pdf)
