Zomato Restaurant Analytics Dashboard
Tableau-Powered Insights for the Food Industry

1. Dashboard Title & Overview
🍽️ Zomato Explorer: Global Restaurant Performance Dashboard
An interactive Tableau dashboard designed to analyze restaurant trends, customer preferences, and market opportunities using Zomato’s global dataset.

Purpose:
Empower restaurant owners, marketers, and analysts with data-driven insights on pricing, cuisines, ratings, and geographic performance.

 Questions

. Build a Data Model using the Sheets in the Excel File

. Build a Calendar Table using the Columns Datekey_Opening ( Which has Dates from Minimum Dates and Maximum Dates)

  Add all the below Columns in the Calendar Table using the Formulas.
  
   A.Year
   
   B.Monthno
   
   C.Monthfullname
   
   D.Quarter(Q1,Q2,Q3,Q4)
   
   E. YearMonth ( YYYY-MMM)
   
   F. Weekdayno
   
   G.Weekdayname
   
   H.FinancialMOnth ( April = FM1, May= FM2  …. March = FM12)
   
. Convert the Average cost for 2 column into USD dollars (currently the Average cost for 2 in local currencies

.Find the Numbers of Resturants based on City and Country.

.Numbers of Resturants opening based on Year , Quarter , Month

. Count of Resturants based on Average Ratings

. Create buckets based on Average Price of reasonable size and find out how many resturants falls in each buckets

.Percentage of Resturants based on "Has_Table_booking"

.Percentage of Resturants based on "Has_Online_delivery"

. Develop Charts based on Cusines, City, Ratings ( Candidate have to think about new KPI to analyse)

. Build a Dashboard for the KPI's Above.  

2. Technology Stack
Tool	Usage
Tableau Desktop/Public	Primary dashboard development & visualization
Tableau Prep	Data cleaning & transformation
SQL (Optional)	Advanced data querying for large datasets
Excel/CSV	Initial data storage & preprocessing
3. Data Source
Primary Dataset: Zomato API or public datasets (Kaggle)

Includes:

Restaurant names, locations (city/country)

Cuisine types, price ranges (₹/$/€)

Average ratings, number of reviews

Delivery/Dine-in availability

4. Key Features & Visualizations
A. Business Problem Solved
Restaurants struggle to benchmark performance against competitors.

Marketers need insights on trending cuisines and pricing strategies.

Investors seek high-growth locations for expansion.

B. Dashboard Highlights
✅ Interactive Filters:

Location (Country/City)

Price Range (Budget, Mid-range, Premium)

Cuisine Type (Indian, Italian, Chinese, etc.)

📊 Key Visualizations:

Geographic Heatmap

Restaurant density & average ratings by region.

Tooltip: Click to see top-rated restaurants in a city.

Cuisine Popularity Chart

Bar chart or treemap showing most-ordered cuisines.

Insight: Identify gaps (e.g., "Low Italian restaurants but high demand").

Price vs. Rating Scatter Plot

Correlation between cost and customer satisfaction.

Trendline: Do expensive restaurants always rate higher?

Top 10 Restaurants Table

Sorted by ratings, votes, or affordability.

Actionable: Use for competitor benchmarking.

Time Trend Analysis (Optional)

How ratings change seasonally (e.g., "Do ratings drop in winter?").

5. Business Impact & Insights
Stakeholder	Benefit
Restaurant Owners	Optimize menu pricing & cuisine offerings.
Food Marketers	Target underrated cuisines or locations.
Investors	Identify high-potential markets for expansion.
Customers	Discover best-rated restaurants in their budget.
Example Insights:

"Mexican cuisine has high demand but low supply in Berlin → Opportunity for new restaurants."

"Premium restaurants (>₹1000) have lower ratings than mid-range ones—why?"

6. Why Tableau?
Interactive: Users can drill down into specific regions/cuisines.

Real-time Updates: Connect to live Zomato API (if available).

Shareable: Publish to Tableau Public/Server for team access.

7. Screenshots / Demo

Dashboard View 1: Geographic Analysis
![dashboard preview](https://github.com/Vipin2197/zomato-restaurant-dashboard-tblu/blob/main/zomato%20restaurant%20dashboard%20.png)
