Real Time Period Wise Analysis of Quick Commerce Platforms Using Web Scraping

Real Time Quick Commerce Analysis Blinkit vs BigBasket
Project Overview :

This project focuses on real time web scraping and data analysis of quick commerce platforms like Blinkit and BigBasket.

The main objective is to analyze how prices, discounts, delivery charges, and stock availability change throughout the day across different locations and product categories.

Data is collected four times daily Morning Afternoon Evening and Night using Selenium automation and analyzed using Exploratory Data Analysis techniques.

Objectives :

Collect real time product data using web scraping

Analyze pricing patterns MRP vs Selling Price

Study discount and offer trends

Compare delivery charges and delivery time

Analyze stock availability across categories

Compare Blinkit and BigBasket performance

Identify the best time to order products

Tech Stack :

Web Scraping
Python
Selenium

Data Analysis
Pandas
NumPy

Data Visualization
Matplotlib
Seaborn

Dataset Information :

Total Records 2098
Total Columns 18
Numerical Columns 5
Categorical Columns 13

Columns include :
Category
Platform
Period
Location
MRP
Selling Price
Offer Percentage
Delivery Time
Delivery Charges
Stock Availability
Climate Condition

Data Collection :

Platforms Blinkit and BigBasket

Locations :
KPHB Colony
Madhapur
Beeramguda

Data Collection Frequency :
Morning
Afternoon
Evening
Night

Data Cleaning and Preparation :

Removed duplicate columns

Handled duplicate rows

Managed missing values

Converted data types

Performed outlier analysis

Created additional columns for better interpretation

Outliers in MRP were not removed since they represent real high value products

Exploratory Data Analysis :

Univariate Analysis:

Platform Distribution
Blinkit 54.39 percent
BigBasket 45.61 percent

Price Distribution
Most products fall in the range of 0 to 50

Category Distribution
Vegetables have the highest share around 33.94 percent
Meat has the lowest share around 5.05 percent

Delivery Time
Most deliveries happen between 8 to 13 minutes

Stock Availability
Most products are available

Bivariate Analysis :

Pricing Relationship
Strong positive relationship between MRP and Selling Price with high correlation

Discount Analysis
Eggs have the highest average discount
Vegetables have moderate discounts
Meat has moderate discounts
Milk and Chicken have very low or no discounts

Delivery Charges
Blinkit average delivery charge around 28
BigBasket average delivery charge around 23

Multivariate Analysis :

Location Based Analysis
Blinkit has higher delivery charges especially in Madhapur
BigBasket is comparatively cheaper across all locations

Time Based Analysis
Afternoon has lowest delivery charges
Night has highest delivery charges

Stock Analysis
Vegetables have the highest out of stock cases
Afternoon has the most stock issues
Milk demand is highest at night

Key Insights :

BigBasket provides better discounts and lower delivery charges

Blinkit charges more for delivery

Vegetables are most frequently out of stock

Afternoon is best for cheaper delivery

Evening is the best overall time to order products

Project Workflow :

Step 1 Web Scraping using Selenium
Step 2 Data Storage in files
Step 3 Data Cleaning
Step 4 Feature Engineering
Step 5 Exploratory Data Analysis
Step 6 Visualization and Insights
