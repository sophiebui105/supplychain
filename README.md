**Project Background
**
Amazon is an E-commerce company which sells a variety of products worldwide via its website and mobile app. 

The company has attempted to increase its delivery time, since it often receives complaints about late delivery from customers. This project thoroughly analyzes the shipments of Amazon in order to uncover the cause of late delivery to improve Amazon’s customer satisfaction. 

**Data Structure Overview
**
Amazon’s database structure consists of one table, with a total row count of 180,519 records. 

 

**Overview of Findings
**The two factors affecting Late delivery are Shipping Mode and Product Category. The shipping mode which causes most delays is the Second Class shipping mode. The 5 most delayed product categories are: Soccer, Crafts, Basketball, Fitness Accessories, and Boxing & MMA. The shipping mode shows a clear relationship with late delivery. Second class shipping mode shows significantly higher late shipment than the other modes. 



**Insights deep dive:
**We performed the relationships among late delivery and order region, order country, shipping mode, and category name using Chi-square method. We find that there is no relationship between late delivery and order region and order country, yet there is a strong relation between late delivery and shipping mode and category name. 

For shipping mode, the second class has the highest late delivery rate, following up with the First Class and the Same Day. The Standard Class has almost no late delivery. 

The late shipment for Second Class is significantly higher than the other classes, indicating inefficiencies or system delay in this mode. 

The reasons for late shipment in Second Class might be:
Lower priority in carrier logistics.
Longer processing and transit times.
Potential congestion in regional distribution centers.

For the product categories, the top 5 products with the most delays are:
	Soccer
	Crafts
	Basketball
	Fitness Accessories
	Boxing & MMA
There may be supply chain bottlenecks, inventory management issues, or carrier-related delays specific to their shipping requirements. The reasons of late delivery for these 5 categories might be: 
 	Bulky or irregular packaging leading to slower handling.
High demand and inventory stock outs delaying dispatch times.
Warehousing constraints impacting order fulfillment speed.

**Recommendation:
**
Based on the uncovered insights, the following recommendations have been provided:
	With the highest late shipment rate for the Second Class, customers should be recommended to choose Same Day or Standard Class for the best experience. 
	Cut down on budget allocation for Second Class shipment and invest more on the Same Day or Standard Class.
	Improve Inventory Management for Delay Categories with actions like: Pre-stock high-demand items in multiple fulfillment centers; 
Optimize Packaging and Handling for Bulky Items: Work with carriers to ensure better handling of fragile or oversized packages, Improve sorting efficiency in fulfillment centers by grouping commonly ordered items together, Use standardized packaging for large items like Basketballs and Fitness Accessories to reduce warehouse handling time.
	Reroute High-Delay Items for Faster Shipping Methods: Automatically upgrade shipping for high-risk categories when delays exceed a set threshold, Use regional fulfillment centers to ensure large and frequently delayed items are stored closer to end customers.


	

