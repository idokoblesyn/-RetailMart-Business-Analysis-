# **RetailMart-Business-Analysis**

## **Overview**

RetailMart is an online retail platform operating across multiple locations and offering a wide range of products. 
Although overall sales performance appears healthy, its management has sought insights into customer purchasing behaviour, product and category level sales performance, as well as the underlying causes of low order completion rates and payment failures. 

## **Data Set**

Transactional data consisting of five key tables ranging from: **_customers_**, **_products_**, **_orders_**, **_order items_**, and **_payments_** was provided. 
These tables captured comprehensive information on customer demograph, product details, order details and payment outcomes.
#these steps are highlighted below:

## **Methodology**

Analysis was performed using SQL. The following steps were applied:

 - Creation of dadatabase and table 
 - data importation 
 - cleaning. 
 - Calculated metrics were performed using SQL techniques such as inner joins, group by, aggregations, where, case when logic, filtering, and sorting were applied

## **Findings**
- The analysis revealed that at the product level, Bag of Rice generated the highest total sales, contributing 28% of total completed sales, making it a key revenue driver for RetailMart. At the category level, the Home category performed best, accounting for 29% of total sales, indicating strong customer demand for essential household products. To sustain this performance, RetailMart should ensure adequate stock availability, targeted promotions, and high online visibility for these high-demand items.

- Order status analysis showed that only 32% of orders were completed, while approximately two-thirds were either cancelled (35%) or pending (33%). This represents a critical operational challenge, as a significant share of potential revenue is either lost or delayed, negatively impacting cash flow and overall business performance.
  
- Further analysis indicates that payment status alone does not fully determine order completion, pointing to operational or customer-experience challenges. This is evident by the fact that despite successful payments, the order completion rate remained at 32%, compared to 31% for failed payments. This marginal difference suggests that post payment operational challenges, such as delayed confirmation could be drivers of cancelled and pending orders rather than payment failure alone.
  
- Analysis of customer order patterns reveals that Anna Ojo placed the highest number of orders (9 orders), while Andrew Lawal recorded the highest total purchase value at ₦6,686.00. This indicates that a higher order frequency does not necessarily translate into higher revenue contribution. The findings highlight the presence of loyal, high-value customers who contribute disproportionately to overall sales performance. This underscores the importance of implementing targeted customer loyalty programs, personalized incentives, and retention strategies to maximize customer lifetime value and sustain revenue growth.
  
- Location analysis revealed that Lagos generated the highest sales, identifying it as a strong-performing market. This suggests that targeted marketing campaigns, enhanced logistics efficiency, and inventory prioritization in high-performing locations can further improve business performance. Meanwhile, lower-performing locations may require tailored growth strategies, such as localized promotions, improved delivery timelines, and increased brand awareness initiatives to stimulate demand.

