# SALES ANALYSIS USING POWER BI

# INTRODUCTION
In this project, we will dive into a large sales dataset to extract valuable insights. We will explore sales trends over time, identify the best-selling products, calculate revenue metrics such as total sales and profit margins and create visualizations to present our findings effectively, enabling us to make data-driven recommendations for optimizing sales strategies.

# DATA OVERVIEW
This dataset, obtained from MeriSKILL forms the cornerstone of a comprehensive sales analysis project during my internship. Covering 19 different electronic gadgets and accessories sales from January 2019 to December 2019, it boasts 19 unique products across 11 columns, totalling 185,950 rows. Modified for in-depth analysis, it includes fields such as order_id, product, quantity_ordered and price, offering a rich source of insights into sales trends and customer behaviour. Utilizing the power bi tool, I meticulously visualized this dataset, unearthing actionable insights to inform strategic decision-making and drive business growth.

# BUSINESS OBJECTIVE
Our objective is to derive actionable insights from raw data to optimize strategies, enhance decision-making and drive sustainable growth. 

To unlock actionable insights, we’ve addressed key questions:
1.	What is the sales trend over time?
2.	Which products are the best-selling and how do their sales compare?
3.	What are the top 5 best-selling products and how does the quantity sold differ?
4.	Cities with the highest sales in terms of total revenue generated?
5.	What day of the week do we sell more? 
6.	Calculate the revenue metrics (Total profit, sales quantity and profit margin)

# DATA TRANSFORMATION AND PREPROCESSING
STEP 1: I downloaded the dataset, uploaded it using the 'Get Data' option in Power BI and then proceeded to transform the data using the power query editor.

STEP 2: The column headers were identified in the first row and were kept as headers by following the steps below

![image](https://github.com/Orie05/Sales_Analysis/assets/149834782/35a6f90e-bf4c-4d2f-bb2e-d235c47986dd)

STEP 3: After promoting the headers, I navigated to the 'Transform' tab and selected 'Detect Data Type.' This action automatically identified the data type of each column and converted them as needed. 

STEP 4: I split the datetime into date and time stamp
The aforementioned process starts with selecting the desired column. Following the selection, the option to split the column becomes visible. 
 • Choose the 'Split Column' option and select the space as the delimiter. 
• Upon completing the data transformation, click on 'Close & Apply' located at the top left. 


# ANALYSIS AND INSIGHTS
## 1.	What is the sales trend over time?

![image](https://github.com/Orie05/Sales_Analysis/assets/149834782/b227c833-972d-4435-9fe7-2654d7e8d604)
   
•	Sales show generally increasing trend throughout the year, with peaks in December (4.6M) and October (3.7M)
•	The highest month for sales is December, indicating potentially strong holiday shopping.
•	Sales are relatively consistent from February to August, ranging between 2.2M to 2.8M.
•	The lowest sales occur in January (1.8M) and September (2.1M), suggesting potential seasonal patterns or market trends.


## 2.	Which products are the best-selling and how do their sales compare?

![image](https://github.com/Orie05/Sales_Analysis/assets/149834782/108dbaaa-4db9-4dd4-8384-a54b04a26283)

•	iPhone emerges as the top selling product with 6.84k units sold, indicating strong customer demand.
•	The 27-inch 4k Gaming monitor follows closely behind, with 6.23k units sold, showing a significant market presence
•	Google phone and Macbook Pro laptop rank third and fourth respectively, with 5.53k and 4.72k units sold, showcasing competitive sales figures. 
•	Thinkpad laptop rounds out the top five, with 4.13k units sold highlighting its popularity among consumers.


## 3.	What are the top 5 best-selling products and how does the quantity sold differ?

![image](https://github.com/Orie05/Sales_Analysis/assets/149834782/9ce66d4a-6158-4305-9b65-ccc909259d80)


•	The top five best-selling products by quantity ordered including AAA batteries, AA batteries, USB-C charging cable, lightning charging cable and wired headphones indicate a high demand for essential electronic accessories.
•	AAA and AA batteries known for their universal use top the list, followed closely by USB-C and lightning charging cables reflecting increasing reliance on electronic devices requiring charging.
•	The popularity of wired headphones amidst a market dominated by wireless options suggests continued demand for traditional audio solutions.
•	Overall, the sales distribution aligns with consumer needs for reliable, everyday electronic accessories driving consistent sales and revenue.


## 4.	Cities with the highest sales in terms of total revenue generated?

![image](https://github.com/Orie05/Sales_Analysis/assets/149834782/1ad1a462-d137-4a2c-8f56-68c8887a4302)

•	Sales distribution by city indicates San Francisco as the highest revenue-generating location, with $8.26M followed by Los Angeles and New York City contributing $5.45M and $4.66M respectively.
•	The presence of major metropolitan areas such as Boston, Atlanta and Dallas in the top 5 highlights urban centers as significant market for sales.
•	Emerging tech hubs like Seattle and Portland underscore the importance of regional economic factors and consumer preferences in driving sales patterns.


## 5.	What day of the week do we sell more?

![image](https://github.com/Orie05/Sales_Analysis/assets/149834782/fbf4cbcb-470c-49ff-9f5c-1eaa8d02a06b)

•	The sales distribution across the days of the week indicates relatively consistent performance with Tuesday recording the highest sales.
•	Despite slight fluctuations, sales remain relatively stable from Monday to Sunday suggesting consistent consumer engagement throughout the week.
•	These findings imoly that there may not be significant day-of-week effects on sales, highlighting the need for further analysis to identify underlying factors influencing consumer behaviour and purchasing patterns.


## 6.	Calculate the revenue metrics (Total profit, sales quantity and profit margin)
   ![image](https://github.com/Orie05/Sales_Analysis/assets/149834782/66e3da38-3dff-48bd-b5e3-94bf782343a4)


•	The total quantity ordered amounted to an impressive 209.8 thousand units depicting strong consumer demand for the products offered.
•	The profit margin, calculated as 58.83% indicates a healthy financial performance, showcasing effective cost management and pricing strategies.
•	With total revenue reaching $34.49 million, the business demonstrates substantial sales volume and revenue generation capabilities, underling its market competitiveness and potential for growth.


 # RECOMMENDATIONS 
 
1.	Diversify product offerings: Expand product range strategically to capitalize on high-demand categories, boosting sales and revenue diversification.
2.	Leverage Data Analytics: Continue leveraging data analytics to gain actionable insights into customer behavior and market trends, guiding informed decision-making.
3.	Optimizing pricing strategies: Implement dynamic pricing algorithms to adjust prices based on market demand, maximizing profit margins while ensuring competitiveness.
4.	Enhance Customer experience: Invest in customer service training and technology to provide exceptional service, fostering loyalty and positive branch perception.
5.	Focus on Customer Feedback: Actively seek and incorporate customer feedback to address pain points and improve product offerings, fostering customer satisfaction and loyalty. 
6.	Targeted Marketing campaigns: Utilize customer segmentation insights to tailor marketing efforts, ensuring more effective targeting and higher conversion rates.


# FULL VISUALIZATION

![image](https://github.com/Orie05/Sales_Analysis/assets/149834782/ced05c84-2fb4-4ed4-83fc-47b30575f9b0)


   





