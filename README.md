---
title: "Problem A"
author: "Raphael Dizon"
date: "2024-01-24"
output:
  word_document: default
  html_document:
    df_print: paged
  pdf_document: default
---

# Data Cleaning and Processing
![](https://shorturl.at/isHU1)
![](https://shorturl.at/qsG38)

The first step is to clean and process the data. I transposed the data in Excel from rows to columns for better analysis. The dataset was then restructured to include three columns: Date, User Type, and Total. Afterward, I uploaded the data into Tableau for further analysis and visualizations.

# Figure 1: User Type Recorded per Month (Pie Chart)
![](https://shorturl.at/aQUVZ)

#### Figure is generated using Tableau
In the first figure of visualization, shows the User type Recorded per Month. With this figure represented in pie chart, we can get the picture of how the flow users use the app and it composes of percentage and summation of information from the users recorded including their total from the following 5 months.

# Figure 2: Total User Types (Bar-Chart)
![](https://shorturl.at/juDL7)

In this figure, illustrate the total users in the app. With this figure, we can start to draw insights about the users and the app. Based on this figure, there is a high record of total users who signed up. And the least recorded are Total active users.

**Problem**: 

The Ridehailing App is challenged between the escalating number of users who sign up for the service and a disproportionately low count of active users. Despite a growing record in user signups, user who requested a booking, and user who phone verified there exists an evident gap in converting sign-ups into sustained and active users with the application.

**To Answer the question: What actions would you commit to fix the problem based on this data?**

-	To address the problem using the data and insights here are some actions that might fix the problem.
o	Commit to implementing a comprehensive plan that will consistently focuses on the growth of users.
o	Analyzing user behavior, on how and when they mostly used the apps per time of the day, season of the year, and overtime.


![](https://shorturl.at/gSTZ5)

In this figure, there is a representation of what has the most recorded users overtime and shows a trend on what needs to be prioritized in order to maximize the number of active users and increase the frequency of usage on the Ridehailing app platform.

Considering the analytical goals to answer the following questions for analysis:
1.	Pick up your most high priority task and create stories for development. 
2.	How will you implement your suggestions? What will you prioritize and why?

***Analytical Goal for Development***

***WHY***: Impact on Ridhailing app and It’s users
-	Why do we need do we need to maximize active users why not just the one’s who book
-	Why are signed app users are not fully active users

***HOW***:
***Story 1 – Engage Users***
•	User should be able to sign up using email or social media accounts.
•	Provide a guided tour highlighting key app features during onboarding.
•	Minimize steps required for account setup and personalization.
***Users Wants***: As a new user, I want the process to be intuitive and efficient, so I can quickly start using the Ridehailing app.

***Story 2 – Lure in the users by Personalized Notification System (Maximization of user)***
•	Develop and Implement an intelligent notification system that considers historical user behavior.
•	Allow users to set preferences for notification frequency and content.
•	Ensure notifications are relevant and provide value.
***Users Wants***: As a user, I want to receive personalized notifications based on my usage patterns, so I am reminded to use the ridehailing app when it aligns with my typical travel times.

***Story 3 – Increase the frequency of usage from the app***.
•	Integrate user catching features such as badges, achievements, or leaderboards.
•	Ensure features elements are non-intrusive and enhance the overall user experience.
•	Provide clear feedback on how users can earn rewards through the new features.
***User Wants***: As a user, I want the Ridehailing app to include elements and features that make my experience more enjoyable, so I am motivated to use the app regularly.

***In conclusion, to answer the question:***

What will you track to measure the success of your features/implementation?
To measure the success of the features and implementation aimed at increasing active users on the ride-hailing app, a set of key performance indicators (KPIs) should be tracked. These metrics will provide insights into various aspects of user engagement and the overall effectiveness of implemented strategies. Some relevant KPIs to monitor include:

***1.	Active User:***
•	Track the percentage of users who sign up and become actively engaged with the app on a regular basis.

***2.	Retention Rate:***
•	Measure the percentage of users who continue to use the app over a specific period, indicating sustained engagement.

***3.	Feature Evaluation***
•	Evaluate the new features or enhancements introduced to improve user engagement.

***4.	Time Spent in the App:***
•	Track the average time users spend within the app, providing insights into overall engagement and user experience.

***5.	Customer Support Interaction:***
•	Monitor the volume and nature of customer support interactions, as a decrease may indicate improved user experience.

***6.	Promotional Campaign Effectiveness:***
•	Assess the impact of marketing campaigns on user acquisition and retention, tracking the conversion rates from promotional efforts.

---
title: "Problem B"
author: "Raphael Dizon"
date: "2024-01-24"
output:
  word_document: default
  html_document: default
---

# Data Cleaning and Processing
![](https://shorturl.at/EMQW6)

Removed rows that have a “Status if Order: Completed” but has no Total CBV, because it will affect the integrity and analysis of data.

![](https://shorturl.at/hkwA2)

Also removed rows with “0” # of orders but has completed, canceled, no drivers found, and Other/Failed/Timeout status because it will skew the analysis of data and create confusion because there’s no basis of the CBV.

In the case of Other/Failed/Timeout: Bug in the system with 0 values on # of orders. Its somewhat relevant to the analysis of data.

After removing irrelevant rows for data analysis, there were 2,769 rows left from the original uncleaned data of 3,211. A total of 442 rows removed.

After that I replace blank values in the Total CBV column and replace it with the value 0, in order to create analysis and visualization.

![](https://shorturl.at/fpKW2)

In this pie-chart shows the sum total Cash booking value per Service app in percentage, where App-ride has produced the highest from the data.

![](https://shorturl.at/nyDOU)

In this line chart highlights the total number of orders per month by service app, It shows that theirs is an increasing trend from the first quarter and a huge drop on the start of 2nd quarter. 

![](https://shorturl.at/iMU06)

In this Bar-chart, It highlights the average order per day inclusive of any status of order whether completed, canceled, no drivers found, and Other/Failed/Timeout status. 

However, for April there is only 1 day recorded which means there are still data that going to be added and be included in the analyzation process.

![](https://t.ly/6-XM5)

In this Bar-Chart, shows the total sum of Cash Booking values from the various Status of orders. Looking at a business perspective, potential CBV Loss can be analyzed if we take the total values from Cancelled, Failed/Timeout, No Driver Found, and Other which approximately $197 Billion.

In addition to visually analyze the data, I added a slicer to further see specific values from the Status of Orders.

***Insights:***

1.	In the pie chart, the most utilized APP was the APP-Ride. With about 67.49% compared to other apps

2.	In the line chart, there an increasing trend on the number of orders and surely see that the next quarter will project better numbers.

3.	Taking the average order from the first quarter, shows quite good results. However for April, it has a pleasing good start, but needs to be consistent and maintained.

***Summary:***

•	With the results of the data it illustrates a consistent and substantial increase in the number of orders placed through our platform over the past quarter.

•	This upward trajectory is indicative of a growing demand for our services, presenting a strategic opportunity for expansion.

***Recommendation:***

•	Develop and Implement an Action Plan. Since there is a good standard that is on the trend of the data it’s important to scale on the next steps.

•	Strengthen data analytics capabilities to extract deeper insights into user behavior, preferences, and market trends. Utilize these insights for informed decision-making and strategic planning.

•	Establish an enhanced and systematic customer feedback mechanism as it is the metric that drives order completion rates among the APPS.

***Commitment to the next quarter and to long-term goals:***

•	Initiate and Intensify the utilization of all the Apps that are used by increase marketing efforts to leverage the positive trends.

---
title: "Problem C"
author: "Raphael Dizon"
date: "2024-01-24"
output:
  word_document: default
  html_document: default
---

# Data Query - Results and Explained

***Question 1***:

Write a query to return all employees still working for the company with last names starting with "Smith" sorted by last name then first name.

```
SELECT *
FROM `my-data-project-1-399301.Problem_C.employee`
WHERE LastName LIKE 'Smith'
  AND employment_status = 'Active'
ORDER BY LastName, FirstName;
```

![Result](https://shorturl.at/fgpG8)

***Explanation:***

Here the query selects all employees who are currently working for the company (TerminationDate IS NULL) and have last names starting with "Smith" Then the results are sorted first by last name and then by first name.

***Question 2***:

Given the `Employee` and `AnnualReviews` tables, write a query to return all employees who have never had a review sorted by HireDate.

![Result](https://shorturl.at/jqzAS)

```
select *
from `my-data-project-1-399301.Problem_C.employee`

where id not in 
(
  select empid 
  from `my-data-project-1-399301.Problem_C.reviews`
  )
order by hiredate;
```

***Explanation:***

Here the query selects employees who have never had a review by using a LEFT JOIN with the AnnualReviews table. And then it filters out rows where there is no corresponding review and sorts the results by HireDate.

***Question 3***:

Write a query to calculate the difference (in days) between the most and least tenured employee still working for the company.

```
SELECT 
    MAX(HireDate) - MIN(HireDate) AS TenureDifference
FROM 
    `my-data-project-1-399301.Problem_C.employee`
WHERE 
    Employment_Status = 'Active'
```

![Result](https://shorturl.at/avw49)

***Explanation:***

Here the query calculates the tenure difference by finding the maximum and minimum hire dates for employees who are still working for the company (TerminationDate IS NULL).

***Question 4***:

Given the employee table above, write a query to calculate the longest period (in days) that the company has gone without a hiring or firing anyone

```
SELECT
MAX(HireDate) - MIN(HireDate) AS LongestPeriod
FROM `my-data-project-1-399301.Problem_C.employee`;
```

![Result](https://shorturl.at/ewPXY)

***Explanation***

Here the query calculates the longest period by finding the maximum termination date and the minimum hire date across all employees.

***Question 5***:

Write a query that returns each employee and for each row/employee include the greatest number of employees that worked for the company at any time during their tenure and the first date that maximum was reached. Extra points for not using cursors

```
WITH EmployeeCount AS (
  SELECT
    HireDate,
    COUNT(*) AS NumEmployees
  FROM `my-data-project-1-399301.Problem_C.employee`
  GROUP BY HireDate
)
SELECT
  *,
  EC.NumEmployees AS MaxEmployees,
  EC.HireDate AS DateMaxEmployeesReached
FROM `my-data-project-1-399301.Problem_C.employee`
JOIN EmployeeCount EC ON `my-data-project-1-399301.Problem_C.employee`.HireDate = EC.HireDate
ORDER BY ID, EC.NumEmployees DESC;
```

![Result](https://shorturl.at/adrG4)

***Explanation:***

Here the query uses a common table expression (CTE) to calculate the number of employees hired on each date. Then it joins this information with the Employee table to associate the maximum number of employees and the date it was reached for each employee.

---
title: "Problem D"
author: "Raphael Dizon"
date: "2024-01-24"
output:
  pdf_document: default
  html_document: default
---

Here at ridehailing app we have 10 core values that we follow:

1) IT'S NOT ABOUT YOU

    • Puts the company above themselves
    
    • Obsesses about customer problems, not personal problems 
    
    • Has a purpose beyond personal success 

2) STAND UP FOR WHAT YOU BELIEVE IN

    • Says what they mean 
    
    • Has courage to disagree  
    
    • Has a strong moral compass

3) COLLABORATE WITH COMPASSION 

    • Is a pleasure to work with 
    
    • Supports others in areas beyond their scope 
    
    • Considers how their actions affects others

4) BE FAST AND FEARLESS

    • Takes calculated risk 
    
    • Values failure as much as success 
    
    • Has strong sense of urgency

5) EARN YOUR TITLE

    • Walks the talk 
    
    • Gets down in the trenches 
    
    • Trusts their team 

6) BECOME A SCIENTIST

    • Follows the numbers intensively 
    
    • Finds solutions in unexpected places 
    
    • Learns independently and shares knowledge  

7) ALWAYS BE PREPARED 

    • Does their homework 
    
    • Plans out every scenario 
    
    • Takes action to reduce risk 

8) CRITICISM IS A GIFT 

    • Actively seeks feedback from others 
    
    • Gives helpful feedback to others unprompted 
    
    • Genuinely acts upon feedback given

9) COMMUNICATE WITH PURPOSE 

    • States objectives in every interaction 
    
    • Aligns early and consistently 
    
    • Focuses on what is actionable

10) SHOOT FOR GREATNESS

    • Goes the extra mile 
    
    • Thinks big 
    
    • Loves to challenge themselves
    
# ANSWERS

***Q: What is a specific example of a time where you showed strength in one of the 10 values?***

During a complex data analysis project, the initial approach wasn't yielding the expected results. Rather than sticking to a predefined methodology, I took the initiative to reassess the problem and explore alternative solutions.

I delved deeper into the data, following the numbers intensively and conducting a thorough review of various statistical models. Recognizing that the solution might not be found in conventional methods, I expanded my analysis to include data sources that were initially deemed unrelated.

In the process, I discovered a pattern in a seemingly unrelated dataset that provided crucial insights into the main problem. This unorthodox approach not only led to a more accurate and insightful analysis but also uncovered unexpected correlations that significantly enhanced the overall project.

Moreover, I actively shared my findings with the team, fostering a culture of collaborative learning. By presenting my thought process and discoveries, I contributed to the collective knowledge of the team, emphasizing the importance of thinking creatively and exploring unconventional avenues to find solutions.

This experience not only showcased my commitment to following the numbers intensively but also highlighted my willingness to step outside traditional boundaries to find innovative solutions, embodying the essence of "BECOME A SCIENTIST" in the field of data analysis.

***Q: What is a specific example of a time where you showed weakness in one of the 10 values?***

In a particular project as a Data Analyst, I demonstrated a weakness in the value of "BE FAST AND FEARLESS." The project involved a tight deadline for delivering insights to inform a critical business decision. Faced with time constraints, I opted for a more conservative and traditional approach to data analysis, choosing well-established methods that I was familiar with.

In retrospect, this decision hindered the speed and agility needed for the project. By avoiding taking calculated risks and exploring more innovative techniques, I missed an opportunity to potentially uncover faster and more efficient ways to analyze the data. The fear of potential failure and the desire for a proven approach led to a slower pace of analysis.

This weakness became apparent during a project review when it was evident that a more fearless and experimental approach could have yielded quicker results without compromising the quality of insights. The lesson learned from this experience is the importance of balancing the need for reliability with the value of being fast and fearless, especially in situations where time is of the essence.

Moving forward, I am committed to being more open to calculated risks and exploring unconventional methods when appropriate, ensuring a balance between established practices and the need for speed and innovation. This experience has reinforced the understanding that being fast and fearless is not only about quick decision-making but also about embracing new and potentially more efficient approaches.

***Q: What are the top 3 values that matter the most to you? Why?***

***BECOME A SCIENTIST:***

Why: This value aligns closely with the core responsibilities of a Data Analyst. Following the numbers intensively, finding solutions in unexpected places, and learning independently are essential aspects of ensuring the accuracy and depth of data analysis. Embracing a scientific mindset promotes continuous improvement and innovation in data analysis techniques.

***ALWAYS BE PREPARED:***

Why: Data analysis often involves dealing with complex datasets and scenarios. Being prepared by doing thorough homework, planning out every scenario, and taking action to reduce risks is crucial. This value ensures that I approach each analysis with a well-thought-out strategy, minimizing the chances of oversight and ensuring the reliability of the insights generated.

***COMMUNICATE WITH PURPOSE:***

Why: Effective communication is vital for the success of any Data Analyst. Clearly stating objectives in every interaction, aligning early and consistently, and focusing on actionable insights help in conveying complex analytical findings in a meaningful way. This value not only enhances collaboration within the team but also ensures that the results of data analysis contribute directly to informed decision-making.

These values collectively support a data-driven, collaborative, and purposeful approach to data analysis. They reinforce the importance of continuously improving analytical skills, being well-prepared for any analysis, and communicating findings in a way that adds tangible value to the organization.

---
title: "Problem E"
author: "Raphael Dizon"
date: "2024-01-24"
output:
  pdf_document: default
  html_document: default
---

# APP-PULS

## Scenario

A product owner from the APP-PULS product wants to increase the number of active customers and transactions on APP-PULS for next month. However, the only customers who can use APP-PULS are ridehailing app customers who use APP-PAY. (You cannot use Cash to buy APP-PULS.) The PM wants more ridehailing app cash users to convert into a APP-PAY and APP-PULS user.

The Product Owner believes that cash users on ridehailing app would be more likely to use APP-PULS if only they knew how easy APP-PULS was to use. The Product Owner wants to use the APP-POINTS redeemable voucher system to give out free APP-PULS vouchers to see if people will end up using APP-PULS more often if only they were able to experience it for themselves.

Design an experiment to test the Product Owner's hypothesis. 

Include details on how would you segment your users?

What data would you analyze to come to your conclusion of whether or not the Product Owner's hypothesis was true?

## Insights:

1.	Increase the number of active customers and transactions on APP-PULS for next month.

2.	Customers who can only use APP-PULS are customers who use APP-PAY

3.	PM wants to convert ridehailing app cash users to convert into APP-PAY for APP-PULS

4.	Cash users on ridehailing app would be more likely to use APP-PULS if only they knew how easy APP-PULS was to use.

5.	The Product Owner wants to use the APP-POINTS redeemable voucher system to give out free APP-PULS vouchers to see if people will end up using APP-PULS more often if only they were able to experience it for themselves.

## PO Hypothesis

•	The Product Owner believes that cash users on ridehailing app would be more likely to use APP-PULS if only they knew how easy APP-PULS was to use.

•	The Product Owner wants to use the APP-POINTS redeemable voucher system to give out free APP-PULS vouchers to see if people will end up using APP-PULS more often if only they were able to experience it for themselves.

***Problem Statement: ***

Closing the User Engagement Gap between Cash, App-Pay, and App-Plus users on Ridehailing APP.

***Background Problem:***

Cash users may be hesitant to adopt digital payment methods like APP-PULS due to various reasons, and might not be fully aware on the convenience of using APP-PULS.

# Analytical Goals

***WHY:***  Quantity of impact on customers and transactions
-	Why do we need to increase in the first place
-	Why are we interested in getting cash users to convert 
-	We want to quantify the impact of closing the gap with user engagement.

***HOW:*** Identify what cash users want to know about.

***Answering the, WHY:***

Quantity of impact on customers and transactions
-	For this to be quantified, the data between the various users must be analyzed specifically the number of cash users and APP-Pay users. With this we can identify trends and focus on the downward trends from cash users.

-	Thus, it has to do something about online literacy.

***Answering the, HOW:***

Identify what cash users want to know about.

-	Identification of factors influencing the behavior of both user groups and understanding their specific needs and preferences.
-	By then, we can categorize their needs and preferences and address it.

## Summary

***WHY: *** User involvement can address the concerns and misconceptions of cash users, emphasizing the advantages of transitioning to APP-PULS.

***HOW: ***Establish a feedback mechanism to continually understand user sentiments, challenges, and satisfaction levels, allowing for iterative improvements.

***Possible Solution:***

Develop and conduct campaigns concerning in-app guidance and tutorials specifically tailored for cash users to ease their transition to APP-PAY or digital payments in order to access APP-PULS.


***PO Hypothesis:*** PO hypothesis is also thru, but looking at a different perspective by connecting to the users will close the gap between cash users and digital payment users, that may help increase the number of active customers and transactions for the next month and following months.

## Next Steps:

-	Continue to gather feedback from users. (as they are the key component)

-	Develop Guidance Campaigns

-	Test and Implement guidance guidelines to users.

***Further Steps: (Continuous Improvement)***

-	Utilize in-app notifications and emails, to convey relevant information and promotions relevant to each user.

-	Adopt the Product Owners idea, through incentive programs tailored for each user group, encouraging engagement and adoption of additional services.
