# Superstore Sales Dashboard

## Data Source
Superstore Sales: https://www.kaggle.com/datasets/ishanshrivastava28/superstore-sales

## Background

Every day, the retail industry produces tons of transactional data. Without the right analysis, those numbers don’t mean much. A dashboard turns that raw data into clear visuals, making it easier to spot insights and support smarter business decisions.

To address these challenges, I developed an interactive Tableau dashboard using the Superstore dataset, which represents a U.S.-based retail business. This dashboard is designed to provide a comprehensive view of sales performance, profitability, customer retention, and product trends. By combining multiple perspectives into one platform, it allows decision-makers to quickly identify key insights and take data-driven actions.

## Dashboard

You can access the full interactive dashboard [here](https://public.tableau.com/app/profile/evelyn.lo5792/viz/Portofolio1_17127575164480/Dashboard1)

<p align="center">
 <img width="1391" height="769" alt="image" src="https://github.com/user-attachments/assets/c51b98e2-7b6a-4437-8e0e-46f5f559aebe" />
</p>

The dashboard offers a dynamic experience with filters for year and customer segment in the top-right corner. Users can also refine their analysis further using state filters in Section 2 and product category filters in Section 4.

### Section 1: Sales and Profit Overview

This section highlights three key metrics, which are Total Profit, Total Sales, and Total Customer. Together, they provide a quick snapshot of the company's overall performance.

<p align="center">
 <img width="800" height="80" alt="Image" src="https://github.com/user-attachments/assets/8058acff-6be6-41f1-b96a-f2b2b94ab04d" />
</p>

-  Comparing sales and profit helps identify whether high revenue also translates into healthy margins. According to the Food Industry Association, the average profit margin for grocery store chains between 2011 and 2014 was around 1.9%–2.3% before taxes [1]. In this section, the Superstore dataset shows a profit margin of about 10%, which indicates performance well above the industry average for grocery retailers.
- For customers, the table shows that in 2012 there was a significant drop especially in consumer and corporate segment compared to other years. After 2012, the number of customers steadily increased, reaching its highest point in 2014.


| Year | 2011 | 2012 | 2013 | 2014 | 
| ----- | -- | -- | -- | -- | 
| Consumer | 311 | 295 | 330 | 361 |
| Corporate | 179 | 165 | 194 | 204 |
| Home office | 105 | 113 | 113 | 112 |
| Total Customers | 595 | 573 | 637 | 693 |


### Section 2: Profit by States

This section illustrates how profitable each state is for Superstore. States with higher profitability are shown in darker green, while less profitable states appear lighter. California and New York stand out as the most profitable, suggesting strong potential for business expansion or opening new branches. In contrast, Texas show significant losses, which highlights areas where the business strategy may need to be reevaluated. 

<p align="center">
  <img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/cf156947-50fb-47f4-9e35-845d83ad06e9" />
</p>
  
### Section 3: Retention Rate by Customers

Section 3 tracks how well the business retain its customer over time, offering insights into loyalty and the effectiveness of engagement strategies. Over the span of four years, customer retention almost doubled from 25% in the first quarter to 55% by Q16. This steady rise reflects stronger customer loyalty and the effectiveness of retention initiatives. While the first ten quarters showed gradual improvements, retention accelerated notably after Q11 (Q3 2013), indicating the positive impact of new customer engagement strategies. The upward trend not only reduces acquisition costs but also builds a stronger foundation for long-term profitability.

<p align="center">
 <img width="500" height="250" alt="image" src="https://github.com/user-attachments/assets/1f7138ff-f460-4643-bbc4-921b39b42732" />
</p>

### Section 4: Sales by Product Category

Superstore’s retail business is divided into three main product categories: Furniture, Office Supplies, and Technology. Section 4 showcases which products drive the most sales within each category, helping to identify key items to prioritize in inventory and marketing strategies. Across the U.S., Office Supplies lead in sales volume, with binders and paper each surpassing 5,000 units sold. Interestingly, this pattern remains consistent across different customer segments and years, highlighting the strong and stable demand for these products.

<p align="center">
 <img width="900" height="225" alt="image" src="https://github.com/user-attachments/assets/de49a4a5-978a-4843-85a6-2d98fd106533" />
</p>

### Section 5: Best Selling Product Treemap Chart

This treemap points out Superstore’s best-selling products. Staples dominate overall sales, reflecting their role as an everyday essential for customers. In Furniture, the KI Adjustable-Height Table emerges as the top performer, while in Technology, the Kingston DataTraveler USB 2.0 leads the category. This section helps identify specific products that drive the highest demand, ensuring inventory and marketing strategies remain focused on the right items.

<p align="center">
 <img width="600" height="500" alt="image" src="https://github.com/user-attachments/assets/5e964140-d59a-4c29-bb5e-9039362530b4" />
</p>

## Business Recommendation
Based on the insights from the Superstore dashboard, several strategic actions can be considered to improve business performance and long-term growth:
- Keep expanding in profitable regions like in California and New York, while reassessing strategies in underperforming states such as Texas and Pennyslvania.
- Introduce product bundling in the Furniture and Technology categories to boost overall sales. 
- Strengthen inventory planning for high-demand products such as, staples, tables, and USB drives to ensure consistent availability.
- Continue and ehance engagement strategies introduced after Q11 which proved effective in significantly improving customer retention

## Reference
[1] https://www.fmi.org/our-research/food-industry-facts/grocery-store-chains-net-profit
