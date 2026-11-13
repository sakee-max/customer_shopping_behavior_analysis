# Customer Shopping Behavior Insights - Project Overview
## The goal of this project is to determine how the company can leverage sales data to improve customer engagement and optimise product and marketing strategies.
This is a company using e-commerce and physical retail stores to sell apparel, footwear, outerwear, and accessories nationwide via website, mobile app, and in-store pickup. The company has significant amounts of data on its sales, marketing efforts, operational efficiency, product offerings, and loyalty program that has been previously underutilised. This project thoroughly analyses and synthesises this data to uncover critical insights that will improve the store’s commercial success.

## Dataset Structure
The dataset, as seen below, consists of a table containing customer_shopping information.

<img width="1587" height="2245" alt="image" src="https://github.com/user-attachments/assets/33dbf1f4-414a-4f24-988b-a562556c3b86" />

## Insights Summary
#### To evaluate sales performance, we focused on the following key metrics:

- **Sales**: Total money you made from orders.
- **AOV**: How much each person spends per order on average.
- **Orders**: How many times people bought.

#### Sales
- Across categories, Health for All and Benefit Updates performed nearly 2-3x better than the average CTR at 34.56% and 22.02%, respectively.
- Within the two categories with high CTR, Customer Testimonial-based campaign and Policy Information had relatively low CTR (32.46% and 16.81%, respectively).
- Family coverage Plan data showed high impressions but few clicks (0.03%) – this needs to be investigated and could be due to missing data or issues with campaign tagging.

#### AOV

- Across campaign categories, Health for All campaigns had the best-performing signup rate (3.0%) and the second-highest number of signups (3.5k).
- This high signup rate is due to the Policy Information campaign type, which had by far the highest signup rate across all campaign types (4.18%).
-Interestingly, the most expensive campaign, which had the highest number of signups. #HealthLiving – had a comparably low
Signup rate at 0.28%

#### Orders
- Across campaign categories, Golden Years Security had by far the highest cost per signup ($124.1), as well as the lowest number of signups (23), compared to an average of $2.2.
- Within the two campaign categories with the highest cost per signup, Product Promotion drove the high costs per signup.

## Recommendations
- Health for All: Reallocate budget from Golden Years Security, which had a high cost per acquisition, to Health for All campaigns. The second category outperforms across all key metrics, yet we have invested a  relatively low amount ($2K) in it.    
- Health awareness: Within Health for All campaigns, focus on Policy Information-type campaigns, and less on Offer Announcement-type campaigns, which had low signup rate and CTR.
- Golden Years Campaigns: Investigate the cause of high cost per signup for these campaign categories, which had high CACs compared to an average signup cost of $2.2. Consider removing these campaigns altogether after exploring the root cause. 
- #HealthLiving: Decrease investment in this campaign category, which has the highest spend ($4.6k) but mediocre signup rates compared to Health for All campaigns.

## Dashboard
 The dashboard can be found on Tableau Public <a href="https://public.tableau.com/app/profile/ithen.yayo/viz/CustomerBehaviorAnalysisDBproduct/Dashboard1?publish=yes">here</a>   

 The dashboard enables users to filter by gender, Location, date, and review rating, and focuses on trends in sales, AOV and Orders.

 <img width="946" height="512" alt="Screenshot 2026-11-13 180444" src="https://github.com/user-attachments/assets/f9840bdc-4372-45ba-8667-1f167619443f" />










