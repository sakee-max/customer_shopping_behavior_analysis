Project Background

This is a company using e-commerce and physical retail stores to sell apparel, footwear, outerwear, and accessories nationwide via website, mobile app, and in-store pickup.
The company has significant amounts of data on its sales, marketing efforts, operational efficiency, product offerings, and loyalty program that has been previously underutilized. This project thoroughly analyzes and synthesizes this data in order to uncover critical insights that will improve the store’s commercial success.

Insights and recommendations are provided on the following key areas:
      
      1. Boost Subscriptions
      2. Customer Loyalty Programs
      3. Review Discount Policy
      4. Product Positioning
      5. Targeted Marketing

Data Structure & Initial Checks

The dataset, as seen below, consists of a table: customer_shopping, with a total row of 3,900 customer transaction records, with 18 columns

Table Schema   

<img width="1587" height="2245" alt="image" src="https://github.com/user-attachments/assets/33dbf1f4-414a-4f24-988b-a562556c3b86" />


Prior to analysis, quality control checks were performed for data integrity and familiarization.

Executive Summary

Overview of Findings

The company has built a solid customer base with strong loyalty, but critical imbalances in subscription adoption, customer acquisition, gender representation, and category performance limit growth potential. Key performance indicators reveal both strengths and opportunities for improvement across the business. Below is the overview page from the Power BI dashboard.  

 <img width="948" height="521" alt="image" src="https://github.com/user-attachments/assets/e3a3b491-0a1f-40f9-bd64-9939642a6baa" />
 

 Sales Trends 
 
    Category Performance
• Clothing is the largest revenue driver (>$3M), followed by Accessories, then Footwear.

• Outerwear generates the lowest revenue – a clear growth opportunity through seasonal campaigns.

    Revenue by Age Group
• Young Adults (18-30) generate the highest revenue, followed by Middle-aged (31-45), then Seniors (65+), then Adults (46-64).

• Revenue distribution is relatively balanced across all age groups.

    Sales by Age Group
• Sales ranking mirrors revenue ranking – Young Adults lead, followed by Middle-aged, Seniors, then Adults – indicating consistent purchasing behavior.

    Subscription Status
• Non-subscribers represent 73% of the 3.9K customer base.

• Subscribers represent only 27% – a significant conversion opportunity.

    Average Purchase Amount
• Overall average: $59.76

• Category averages range from $50K-$100K across Clothing, Accessories, Footwear, and Outerwear.

    Average Review Rating
• Overall rating: 3.75 / 5.0

• Indicates satisfactory but not exceptional satisfaction – room for quality improvement.

Product Performance

• Clothing is the company's dominant category, generating approximately 55% of total revenue. This category benefits from high purchase frequency, with customers buying weekly or fortnightly across items including Pants, Shirts, Sweaters, Dresses, and Skirts.

• Accessories represent the second-largest category at 25% of revenue, driven by Handbags, Backpacks, Scarves, Jewelry, Sunglasses, Gloves, Hats, and Belts. Accessories also dominate the top-rated product list, with Gloves (3.86), Sandals (3.84), Boots (3.82), Hat (3.80), and Skirt (3.78) receiving the highest average review ratings.

• Footwear accounts for 12% of revenue, with Sneakers, Sandals, and Boots as top performers. Footwear products perform strongly in customer satisfaction, capturing three of the top five positions in average ratings.

• Outerwear generates the lowest revenue share at 8%, driven by Coats and Jackets. Despite being a seasonal necessity, Outerwear significantly underperforms other categories, representing a clear growth opportunity through winter-focused campaigns.

• Five products receive discounts at rates between 47-50%: Hat (50.0%), Sneakers (49.7%), Coat (49.1%), Sweater (48.2%), and Pants (47.4%). Top-rated products such as Sneakers and Coats are among the most heavily discounted, indicating margin erosion on items that could likely sell at full price.

• The accessory category shows strong customer satisfaction with Gloves (3.86) and Hats (3.80) ranking in the top five highest-rated products. However, the Hat presents a paradox – it is the most discounted product (50%) yet achieves a top-5 rating, suggesting customers like the product but perceive the full price as too high.

• Clothing products, despite driving 55% of revenue, are notably absent from the top-rated list except for Skirt (3.78). The highest-rated Clothing item ranks fifth, indicating that volume is not translating to satisfaction in this core category.

Recommendations

Based on the uncovered insights, the following strategic recommendations have been provided:

1. Promote Exclusive Benefits for Subscribers
   
With only 27% of customers currently subscribed (73% non-subscribers) and subscription showing no incremental loyalty benefit (91.0% subscriber repeat rate vs. 88.5% non-subscriber repeat rate), the current program is under-performing its potential.

    • Launch a 30-day free trial to remove sign-up friction and allow customers to experience benefits firsthand before committing.
    
    • Add compelling exclusive benefits, including 15% off every purchase and free express shipping to create a meaningful value gap between subscribers and non-subscribers.
    
    • Target the 2,518 repeat non-subscribers with conversion campaigns highlighting potential savings ("You already shop like a member – subscribe and save 15% on your next order").
    
    • Introduce tiered subscription levels (Basic, Plus, Premium) to appeal to different customer segments and price points.
      
2. Reward Repeat Buyers to Move Them into the "Loyal Segment."
   
The store has achieved exceptional retention with 79.9% of customers already in the Loyal segment. However, 701 Returning customers (18.0%) represent a conversion opportunity, and the 83 New customers (2.1%) highlight a severe acquisition gap.

    • Create a formal loyalty tier structure (Bronze → Silver → Gold → Platinum) with clear progression paths and escalating benefits.
    
    • Launch accelerator campaigns for Returning customers ("Make 3 more purchases in 60 days and receive $15 off + free express shipping") to convert them to Loyal status.
    
    • Establish a "Platinum Loyal" tier for customers with 30+ previous purchases, offering premium benefits such as 20% off, free express shipping, and exclusive product access.
    
    • Implement a referral program leveraging the 3,116 loyal customers to acquire new buyers, offering rewards to both the referrer and the referred friend.

3. Review Discount Policy: Balance Sales Boosts with Margin Control
   
Discounts are applied to approximately 98% of all transactions, with five products receiving discounts at rates between 47-50%: Hat (50%), Sneakers (49.7%), Coat (49.1%), Sweater (48.2%), and Pants (47.4%). Top-rated products like Sneakers and Coats are among the most heavily discounted, representing margin erosion on items that could likely sell at full price.

    • Reduce Sneakers discount from 50% to 20% and test full-price periods to measure true pricing power without significant volume loss.
    
    • Reduce Coats discount from 49% to 20% and promote at full price during pre-winter peak season when demand is highest.
    
    • Investigate the Hat paradox – high rating (3.80) but highest discount rate (50%). Test a permanent 15-20% price reduction instead of 50% flash discounts.
    
    • Shift from single-item discounts to bundle discounts (e.g., Coat + Hat + Gloves) to protect margin while increasing average order value.
    
    • Implement a product-tiered discount strategy where top-rated, high-demand products receive fewer and shallower discounts than seasonal or clearance items.
    
4. Product Positioning: Highlight Top-Rated and Bestselling Products in Campaigns
   
The highest-rated products are Gloves (3.86), Sandals (3.84), Boots (3.82), Hat (3.80), and Skirt (3.78). However, no product achieves a 4.0+ average rating, and bestselling Clothing items are notably absent from the top-rated list despite driving 55% of revenue.

    • Feature top-rated products (Gloves, Sandals, Boots) in homepage hero banners and email campaigns, emphasizing their high customer ratings as social proof.
    
    • Create "Customer Favorites" collections for each category, bundling top-rated items with bestselling products to increase average order value.
    
    • Use color and size popularity data (Gray, Black, Maroon; sizes M and L) to guide inventory purchasing and reduce waste.
    
    • Bundle bestselling Clothing items (Pants + Shirt) with top-rated Accessories (Gloves + Hat) at a modest bundle discount to drive both volume and margin.
    
    • Set a quality improvement target of achieving a 4.2+ average rating on at least three products within 12 months.

5. Targeted Marketing: Focus Efforts on High-Revenue Age Groups and Express Shipping Users
   
Revenue is balanced across all four age groups: Young Adult (26.7%), Middle-aged (25.4%), Adult (24.0%), and Senior (23.9%). Express shipping users spend only **$2.02 (3.5%) more** than Standard shipping users ($60.48 vs. $58.46). Male customers generate **2.1x more revenue** than female customers ($157,890 vs. $75,191).

    • Maintain equal marketing investment across all age groups (25% each) to preserve the balanced revenue distribution.
    
    • Tailor marketing channels by age group – use Instagram/TikTok for Young Adults, Facebook/Email for Middle-aged, Email/Direct mail for Adults, and Email/Phone for Seniors.
    
    • Create age-specific messaging – emphasize trends and social proof for Young Adults, comfort and durability for Seniors.
    
    • Use express shipping as a loyalty reward rather than a standalone segment – offer free express shipping to Loyal and Subscriber segments on orders over $75 to incentivize larger baskets.
    
    • Launch female-targeted marketing campaigns to close the $82K revenue gap – expand female product lines, partner with female influencers, and create female-focused loyalty offers.
    
    • Geographically target top states that represent approximately 35% of transactions, with localized ads and store pickup promotions.














