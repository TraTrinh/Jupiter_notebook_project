# [Python] Sales Analysis
## I. Introduction 
### 1. Business question 
This project will use Python to clean, transform and visualize data to identify insights and solve business questions outlined below:
1. What was the best month for sales? How much was earned that month?
2. What city has the best sales?
3. What time should we display ads to maximize the likelihood of customer's buying product
4. What products are most often sold together?
5. What product sold the most? Why do you think it sold the most?

### 2. About the dataset
The dataset consists of over 180.000 orders online sales data of different products, several merchandise and electronic in different states in USA in 2019. 

Overview of dataset: 

![Screen Shot 2025-03-24 at 23 59 08](https://github.com/user-attachments/assets/842a7d97-a2e4-411f-8775-687c64fd39ba)

### 3. About this project 
This project focuses on transforming and visualize data to identify key factors that answer business questions. 
The project will follow these steps: 
1. Clean and preprocess data

   1.1. Merge 12-month data

   1.2. Add 'Month' column

   1.3. Get rid of NaN value
3. Reporting

   2.1. Visualize monthly sales using a column chart

   2.2. Visualize sales by cities using a column chart

   2.3. Visualize sales by hours using a line chart

   2.4. Create table counting products that are bought together

   2.4. Visualize quantity sold by product using a column chart, compare with price each product

## II. Data Visualization and Comments  
### 1. What was the best month for sales? How much was earned that month?
The best month for sales is December with the highest sales at 4,6 million USD. This suggests strong end-of-year performance, due to seasonal factors like holiday shopping or year-end promotions. On the other hand, the chart shows the lowest sales occured in Januart and September, indicating slow-down trend post-holiday. 

![Screen Shot 2025-03-25 at 00 17 55](https://github.com/user-attachments/assets/8ee29add-4c9a-4ab4-af43-7d13ac13dccc)

![Screen Shot 2025-03-25 at 00 18 25](https://github.com/user-attachments/assets/4cbdf77e-ee2a-48b3-b028-6e9ed6fdf919)

### 2. What city has the best sales?
The city has the best sales is San Francisco which peak at 8 million USD. This indicates a strong market presence or business activity in the region.This distribution highlights San Francisco’s dominant position and may reflect its concentration of high-value industries, particularly in tech and innovation.

![Screen Shot 2025-03-25 at 00 24 07](https://github.com/user-attachments/assets/dc14a5e4-e5bc-48d6-87e2-e2c1950ee1f1)

![Screen Shot 2025-03-25 at 00 26 11](https://github.com/user-attachments/assets/ff0e2162-6a4f-4440-b488-7a7eb0fea4a5)

### 3. What time should we display ads to maximize the likelihood of customer's buying product
Sales begin to rise sharply from 6 AM, peaking first around 11 AM to 12 PM, indicating strong mid-morning demand. There is a second peak between 6 PM and 8 PM, marking the highest sales point of the day—likely reflecting after-work consumer behavior or evening shopping traffic.

![Screen Shot 2025-03-25 at 00 28 57](https://github.com/user-attachments/assets/cadaecf1-7db3-4937-8841-9e3d5bae44be) 

### 4. What products are most often sold together?
The top 3 product sets sold together are iPhone, Lightning Charging Cable — 882 times; Google Phone, USB-C Charging Cable — 856 times and iPhone, Wired Headphones — 361 times. This indicates strong accessory demand for both Apple and Google devices. The company could increases average order value (AOV) and boosts cart size by giving automated recommendations or creating combo discounts. 

![Screen Shot 2025-03-25 at 00 31 40](https://github.com/user-attachments/assets/c9a75aad-1d68-4e12-817e-f079ab8d22ba)

### 5. What product sold the most? Why do you think it sold the most?
AAA Batteries (4-pack) and AA Batteries (4-pack) show the highest quantities sold, despite having very low prices, indicating they are high-turnover essentials.

Apple AirPods and Wired Headphones also sold in large numbers, suggesting strong consumer demand for affordable audio accessories.

Premium products like the MacBook Pro and ThinkPad Laptop have very high prices, but relatively low sales volume, which is expected for big-ticket items.
A few products like the Lightning Charging Cable and USB-C Cable show a balanced profile — strong quantity and mid-range price — making them likely drivers of both volume and revenue.

![Screen Shot 2025-03-25 at 00 33 15](https://github.com/user-attachments/assets/6ffda781-370b-4c18-a9b0-2d76370638ce)
