# Swiggy_Food_Delivery_Dashboard
# Business Requirement
Connect to the sample dataset for one of the top food delivery service providers, which has data for a few months for the year 2021, which tracks the time taken to deliver their orders or the time taken for pickup along with the Dollar amount involved for each order. Join both the tables based on your analysis and the expected number count will give you an idea if the specified join is correct.
 
# Instructions
Use Food Delivery Order Items Dataset.xls data.
Note that you can use either Tableau Public or Desktop to find the answer.
If you are using Tableau Desktop, the Sample Superstore dataset should be present in the Saved Data sources.
Data should be an Extract and not a ‘Live’ connection.

# Tableau Project Requirement
The Workbook should have a Story consisting of several Story points based on requirement.
Each worksheet/view/chart should meet the business requirement.
All worksheets should be hidden.
Workbook should be published to Tableau Public if possible.

## View 1: Sales Revenue
Build a scorecard showing the Total Sales in $ using the Amount Paid field.
- **Format**: As per your choice.
- **Number should match**.

  ![image](https://github.com/Steffi-9/Swiggy_Food_Delivery_Dashboard/assets/58806839/568e3111-9921-4c55-b903-f4b557c3e8e8)


## View 2: Average Order $
Build a scorecard showing the Average Order $.
- **Format**: As per your choice.
- **Number should match**.

![image](https://github.com/Steffi-9/Swiggy_Food_Delivery_Dashboard/assets/58806839/09b46ca4-8620-4a13-a02e-18318def2754)


## View 3: Total Orders
Build a scorecard showing the Total Orders.
- **Format**: As per your choice.
- **Number should match**.

![image](https://github.com/Steffi-9/Swiggy_Food_Delivery_Dashboard/assets/58806839/a7595880-15d4-4732-be69-b6bd6391d9ea)


## View 4: ARPU (Average Revenue Per User)
Build a scorecard showing the ARPU.
- **Format**: As per your choice.
- **Number should match**.

![image](https://github.com/Steffi-9/Swiggy_Food_Delivery_Dashboard/assets/58806839/c709eaff-14a0-417e-b486-6c501242ee3b)


## View 5: Area Chart showing Daily Trending Metrics for the above 4 views
Build an Area chart showing the Daily trends and Metrics from the below metrics (Use Parameters).
- **Format**: As per your choice.
- **Number should match**.

## View 6: Mins taken on an average for a Delivery or Pick up depending on the selection
Build a simple text chart showing minutes taken on average for either pickup or delivery.
- If the value is less than or equal to 15.5 then format minutes to green.
- If greater, format to red.
- **Number should match**.

## View 7: Mins taken on an average for a Delivery or Pick up depending on the selection
Build the below view showing the average minutes breakdown by weekday.
- Use red-green diverging with Step size 7.
- If the value is greater than 15 then shades should be running towards red.
- If less, they should be running towards green.
- If 15, they should be running towards grey.
- Time should be formatted as shown in the AM/PM format. (Hint: Use the calculated field to get the hour and concatenate with the string field or any other approach you can think of).

