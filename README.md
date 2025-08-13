# Zomato analysis-Data analysis(interactive Dashboard creation Using Power Bi)

## Project Objective
The objective of the Zomato Sales Analysis project is to analyze customer order data to identify key sales trends, understand customer behavior, and evaluate restaurant performance. The project aims to extract actionable insights that can help optimize marketing strategies, improve customer satisfaction, enhance restaurant partnerships, and increase overall revenue. This will be achieved by using data analytics tools to explore patterns in sales volume, order frequency, delivery time, pricing, ratings, and geographical distribution.

## Dataset Used
- <a href="https://github.com/ashwinireddy09/Zomato-analysis/blob/main/Zomato%20restaurant%20analysis.pbix">Zomato sales data</a>

## Questions (KPI's)
Zomato sales analysis(Questionaries)

1. Build a Data Model using the Sheets in the Excel File

2. Build a Calendar Table using the Columns Datekey_Opening (Which has Dates from Minimum Dates and Maximum Dates) Add all the below Columns in the Calendar Table using the Formulas.
   
   A. Year
   
   B.Monthno
   
   C.Monthfullname
   
   D.Quarter (Q1, Q2,Q3,Q4)
   
   E. YearMonth (YYYY-MMM)
   
   F. Weekdayno
   
   G. Weekdayname
   
   H.FinancialMonth (April FM1, May= FM2 March FM12)
   
   I. Financial Quarter (Quarters based on Financial Month FQ-1. FQ-2..)

4. Convert the Average cost for 2 column into USD dollars (currently the Average cost for 2 in local currencies

5. Find the Numbers of Resturants based on City and Country.

6. Numbers of Resturants opening based on Year, Quarter, Month

7. Count of Resturants based on Average Ratings

8. Create buckets based on Average Price of reasonable size and find out how many resturants falls in each buckets

9. Percentage of Resturants based on "Has_Table_booking"

10. Percentage of Resturants based on "Has_Online_delivery"

11. Develop Charts based on Cusines, City, Ratings (Candidate have to think about new KPI to analyse)

12. Build a Dashboard for the KPI's Above.

** KPI are not limited only to above, you can experiment on the other KPI as well.
- Dashboard Interaction
- <a href="https://github.com/ashwinireddy09/Zomato-analysis/blob/main/Screenshot%202025-06-18%20130203.png">View Dashboard</a>


## Process
- Data Import – Load Zomato restaurant data into Power BI from Excel or CSV sources.

- Data Cleaning – Use Power Query to clean nulls, standardize cuisines, and format country/city names.

- Data Modeling – Create relationships between tables (e.g., country, cuisine, votes, rating) and build necessary calculated columns/measures (like average rating).

- Visualization – Design visuals like maps, bar charts, pie charts, and KPIs to show restaurant count, cuisines, delivery, booking, and ratings.

- Interactivity – Add slicers for country/year filters and enhance with tooltips and dynamic visuals for user-friendly exploration.


## Dashboard 

<img width="1920" height="1080" alt="Screenshot 2025-06-18 130203" src="https://github.com/user-attachments/assets/4b265e8f-d4fb-48be-8f27-c293fd74ba1b" />



## Project Insights
- Restaurant Reach: The dataset includes 9,551 restaurants spread across 141 cities and 15 countries, indicating Zomato’s broad international presence.

- Average Rating: The overall average rating is 2.89, suggesting that user satisfaction is moderate and there may be room for service or food quality improvement.

- Popular Cuisines: North Indian, Chinese, and Fast Food are the most offered cuisines, highlighting strong demand for these food types.

- Online Delivery & Booking: A large portion of restaurants (74.3%) offer online delivery and 85.4% support table booking, showing a high level of digital adoption.

- User Engagement: With over 1 million votes, there is significant customer interaction, indicating that users actively review and rate their dining experiences.


## Final Coclusion
The Zomato analysis reveals a strong global presence with high user engagement and digital service adoption across 15 countries. While popular cuisines like North Indian and Chinese dominate the market, the overall average rating of 2.89 highlights potential areas for service or quality improvement. With most restaurants offering online delivery and table booking, Zomato is well-positioned in the competitive food service landscape. These insights can guide strategic decisions to enhance customer satisfaction and optimize restaurant performance.












