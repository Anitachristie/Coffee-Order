# Coffee Order Transaction
An order transaction project carried out in Microsoft Excel on data cleaning and gathering, use of Excel functions (such as IF, VLOOKUP, INDEX, MATCH), Pivot tables and Pivot charts to create an interactive dashboard.

# Table of Content
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Excel Utilization for Data Cleaning and Visualization](#excel-utilization-for-data-cleaning-and-visualization)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results or Findings](#results-or-findings)
- [Recommendation](#recommendation)
- [Limitations](#limitations)

## Project Overview
This project analyzes coffee order data from 2019 to 2022, focusing on key business metrics such as order details, customer demographics, and product sales performance. The analysis aims to track coffee orders across different time periods, locations, and customer segments, explore customer purchase behavior by analyzing frequency, country of origin, and top buyers, and assess the popularity and profitability of various coffee types, roast types, and sizes. Dashboards and charts were created to visualize sales trends, customer distributions, and product performance, ultimately aiding in business decision-making. By analyzing these aspects, the project seeks to identify trends, provide data-driven recommendations, and gain a deeper understanding of the company’s overall performance. [coffee Orders Data Project.xlsx](https://github.com/user-attachments/files/17394776/coffee.Orders.Data.Project.xlsx). 

![CoffeeOrderDashboard](https://github.com/user-attachments/assets/99b89415-4a99-4064-aca2-022155bda79a)

## Data Source
The primary dataset used for this analysis is the "[coffeeOrdersData.xlsx](https://github.com/user-attachments/files/17394768/coffeeOrdersData.xlsx)" file, containing detailed information about each order transaction made by the customer.

## Tools
- Microsoft Excel

## Excel Utilization for Data Cleaning and Visualization
I utilized Excel for:
- Table population using functions such as IF, VLOOKUP, INDEX, and MATCH functions.
- Date and Currency formatting.
- Removing duplicates or blank cells.
- Substituting abbreviations with full words to ensure clarity and ease of comprehension.
- Generating pivot tables and pivot charts to visualize findings.
- Compiling all charts and filters into a cohesive dashboard.

## Exploratory Data Analysis
This involved exploring the sales data to answer key questions, such as:
- What are the total sales trends over time?
- Which coffee types are generating the most profit?
- Who are the top 5 customers?
- Which countries contribute most to the sales?

## Data Analysis
This includes some interesting functions I worked with:
- ```=VLOOKUP(C2,products!$A$1:$B$1001,2,FALSE)```
- ```=IF(VLOOKUP(F2,products!$B$1:$C$1001,2,FALSE)=0,"Nil",VLOOKUP(F2,products!$B$1:$C$1001,2,FALSE))```
- ```=INDEX(orders!$A$1:$G$49,MATCH($D2,orders!$A$1:$A$49,0),MATCH(I$1,orders!$A$1:$G$1,0))```
- ```=IF(I2="Rob","Robusta",IF(I2="Exc","Excelsa",IF(I2="Ara","Arabica",IF(I2="Lib","Liberica",""))))```

## Results or Findings
1. The coffee sales dashboard reveals fluctuating total sales from January 2019 to July 2022, with distinct peaks and troughs indicating varying demand. Sales generally dip in the early months of the year but rise significantly during spring and holiday seasons. Notably, 2020 experienced substantial growth, likely due to effective marketing strategies. External factors such as economic conditions and market trends also influence sales performance.
2. The sales distribution reveals that a significant majority of sales (79%) come from United States, followed by the Ireland (15%) and the United Kingdom (6%). This highlights United States as the primary market for coffee sales.
3. Among the coffee types analyzed, Liberica and Excelsa are the most profitable, demonstrating strong demand and higher price points. Arabica also contributes notably, while Robusta shows the lowest profit margin.
4. The analysis identifies the top five customers, with Allis Winmore leading in total sales at over $310, followed closely by Brenn Dundregbe and others. This indicates a concentrated customer base that could be targeted for loyalty programs or special offers.

## Recommendation
Based on the analysis, I recommend the following actions:
- Leverage data on peak sales months and popular coffee types (like Liberica and Excelsa) to design targeted marketing campaigns during high-demand periods, particularly around holidays and seasonal promotions.
- Enhance and promote loyalty card programs, as data indicates potential differences in purchasing behavior between loyal and non-loyal customers. Offering exclusive rewards or discounts can incentivize repeat purchases.
- Explore expanding the product line to include limited-time offerings or seasonal flavors, especially during months with lower sales, to attract more customers and encourage higher spending.
- Use sales data to optimize inventory management, ensuring that popular coffee types and sizes are well-stocked during peak periods while minimizing overstock of less popular items.
- Engage with top customers through personalized offers or exclusive events to foster loyalty and increase sales, considering that a small number of customers contribute significantly to total revenue.

## Limitations
Aside from substituting words with their full forms for better understanding, I did not face any challenges while working on this project.








