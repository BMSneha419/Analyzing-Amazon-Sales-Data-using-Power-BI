# Analyzing-Amazon-Sales-Data-using-Power-BI
This project presents an interactive Power BI report designed to analyze a dataset of Amazon sales, focusing on product performance, customer feedback, and pricing strategies. It demonstrates key business intelligence concepts, data visualization techniques, and Power BI functionalities for e-commerce analytics. The dataset is sourced from Kaggle.

**Page 1: Executive Summary**
**Purpose:** Provides a high-level overview of key financial and performance indicators (KPIs) for the entire dataset, offering an immediate snapshot of the business's overall health and key trends.
**Visualizations:** Total Revenue (Discounted & Actual), Total Unique Customers, Average Product Rating, Overall Discount Percentage, and Top 3 Categories by Discounted Revenue.
**Insights:**
**Significant Revenue Leakage due to Discounting:** A striking observation is the substantial difference between `Total Revenue (Actual Price)` (₹7.69M) and `Total Revenue (Discounted Price)` (₹4.46M), indicating that approximately **₹3.23 Million** in potential revenue was foregone due to discounts. This is corroborated by a very high `Overall Discount Percentage` of **41.93%**. This raises critical questions about the sustainability of current pricing strategies and whether these deep discounts are necessary for sales volume.
**Healthy Customer Base & Solid Satisfaction:** With **1186 unique customers** and a strong `Average Product Rating` of **4.1**, the business demonstrates a reasonably engaged customer base with generally positive sentiment. This indicates good product quality and/or effective customer expectation management.
**Extreme Revenue Concentration:** The "Electronics" category overwhelmingly dominates, accounting for roughly **75%** of all discounted sales (approx. ₹3.95M out of ₹4.46M total discounted revenue). This highlights a heavy reliance on a single category, prompting consideration for revenue diversification strategies and a closer look at the discount strategies within Electronics.

**Page 2: Product Performance & Quality**
**Purpose:** Delves deeper into product-level performance, analyzing revenue contributions, rating distributions, and average discount percentages by category.
**Visualizations:** Top 10 Products by Discounted Revenue, Distribution of Product Ratings (overall), Average Discount Percentage by Category, and Revenue Contribution by Product Rating.
**Insights:**
**Top Performers Driving Revenue:** "Sony Bravia 164 c..." leads the "Top 10 Products by Discounted Revenue," emphasizing the strong performance of large electronic items (likely TVs). These products are key revenue champions and should be prioritized for inventory and marketing.
**Overwhelmingly Positive Product Quality:** The vast majority of products (1214) are rated "Very Good," with a significant number (96) also being "Excellent." This indicates a high level of overall product quality and customer satisfaction across the product catalog, with very few critically underperforming items.
**Varied Discount Strategies by Category:** "Home Improvement" (57.50%), "Computers & Accessories" (53.22%), and "Health & Personal Care" (53.00%) show the highest average discounts, suggesting they are either highly competitive or prone to clearance sales. Conversely, "Office Products" (12.35%) and "Toys & Games" (0.00%) have significantly lower discounts, indicating different pricing strategies or higher demand elasticity.
**"Very Good" Products as Revenue Powerhouses:** The bulk of revenue (approx. ₹4.2M) originates from products rated "Very Good," significantly more than "Excellent" rated products. This suggests that while "Excellent" products exist, "Very Good" products are the primary volume and revenue drivers.

**Page 3: Customer Feedback & Reviews**
**Purpose:** Dedicated to understanding customer sentiment and engagement through reviews, providing both quantitative and qualitative insights into customer feedback.
**Visualizations:** Top 10 Products by Review Volume, Average Rating by Product Category, Distribution of Reviews by Rating, Total Unique Reviewers, and a table of All Customer Reviews.
**Insights:**
**High Engagement for Specific Products:** "Amazon Basics High-Speed HDMI Cable" and "boAt Bassheads" are among the products with the highest review volumes, indicating strong customer interest and usage. These products warrant close monitoring of customer feedback.
**Strong Overall Customer Satisfaction:** The distribution of reviews shows an overwhelming majority (over 96%) are "Very Good" or "Excellent," reinforcing the generally positive customer experience. Only a minimal number of reviews fall into "Good" or "Average."
**Category-Specific Satisfaction Varies:** While most categories hover around 4.0-4.2 average rating, "Office Products" and "Toys & Games" lead with 4.3. "Car & Motorbike" stands out with a notably lower average rating of 3.8, flagging it as a potential area for product quality or customer expectation review.
**Direct Customer Voice:** The "All Customer Reviews" table provides invaluable qualitative feedback, allowing for direct insights into customer pain points ("except for the sound" for a TV) or specific features they appreciate ("Spectacular Specification, Build Quality").

**Page 4: Pricing & Discount Strategy**
**Purpose:** Focuses on analyzing the financial impact of pricing and discounting decisions, identifying where discounts are concentrated and their relationship with product ratings.
**Visualizations:** Key Financial Metrics (Total Revenue, Discount Given, Avg Discount %), Revenue Breakdown by Product Category (showing discount vs. collected revenue), Discount Percentage vs. Average Rating (scatter plot by product), and a Decomposition Tree for Top Discount Contributors.
**Insights:**
**Quantified Discount Cost:** The "Total Discount Given" of approximately **₹3.22 Million** explicitly quantifies the direct financial impact of the discounting strategy, underscoring the high cost of current promotions.
**Discount Concentration in High-Revenue Categories:** The 100% Stacked Column Chart clearly shows that the largest absolute discounts are given in "Electronics" and "Home & Kitchen." This suggests these categories are either highly competitive or strategically used for aggressive sales, impacting their net profitability significantly.
**Discounts Not Solely for Poorly Rated Products:** The Scatter Plot reveals no strong direct correlation between discount percentage and average rating. Many highly-rated products (4.0-4.5) are also heavily discounted. This suggests discounts are a broad sales tactic rather than solely a means to clear unpopular or low-quality inventory. It also identifies opportunities for margin improvement on popular, well-rated items that might be unnecessarily discounted.
**Targeted Optimization through Decomposition:** The Decomposition Tree, when interacted with, allows for pinpointing the exact products or subcategories contributing the most to the total discount given, enabling highly targeted strategic adjustments to pricing.

**Page 5: Individual Product Deep Dive**
**Purpose:** This serves as a powerful drill-through page, providing a comprehensive, single-product view of all relevant details, from basic information and pricing to review content and rating distribution.
**Visualizations:** Product Overview (Name, Category, Subcategory), Product Image, Direct Product Link, "About This Product" description, Pricing & Rating Summary (detailed), Customer Reviews table, and Rating Distribution for the specific product (Pie Chart).
**Insights:**
**Holistic Product View:** Provides a 360-degree understanding of a specific product's performance and customer perception, essential for product managers and marketing teams.
**Product-Specific Discount Impact:** Shows the exact average discount percentage for the individual product (e.g., 47% for the "10000mAh Li-Polym..." product), allowing for granular profitability assessment.
**Granular Customer Sentiment:** The Rating Distribution Pie Chart provides a precise breakdown of ratings (e.g., ~88% "Very Good" and ~8% "Excellent" for the example product), reinforcing the average rating and highlighting specific areas of satisfaction.
**Direct Feedback for Product Teams:** The "Customer Reviews" table offers invaluable qualitative feedback, helping to identify precise features users praise or specific issues they encounter (e.g., "except for the sound" for a TV).


