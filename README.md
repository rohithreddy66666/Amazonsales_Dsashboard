# Amazonsales_Dsashboard

Dataset :
The dataset that I am using is Amazon India clothes sales and shipping (kaggle) it 
consists of approximately 129,000 rows of sales data from an Amazon store. The 
dataset size is approximately 72MB, indicating a substantial amount of information 
to analyze. It includes details such as order IDs, dates, order statuses, fulfillment 
methods, sales channels, shipping service levels, product styles, SKUs, categories, 
sizes, ASINs, courier statuses, quantities, currencies, amounts, shipping locations, 
promotional IDs, B2B indicators, fulfillment methods, and an unnamed column. 
With this dataset, we can explore and gain insights into sales trends, customer 
behavior and more through data visualizations. The dataset provides a 
comprehensive view of the e-commerce sales activities and can serve as a valuable 
resource for analytical purposes.
Link - https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-ecommerce-sales-data?select=Amazon+Sale+Report.csv

Objectives :
• Analyzing Sales Performance: The visualizations aims to analyze the sales 
performance of the clothes category on Amazon India. It explores the quantity 
of clothes shipped, sales channels used to provide insights into overall sales 
trends.
• Identifying Key Markets: The visualizations focuses on identifying key 
markets by analyzing the quantity of clothes shipped across different states. It 
highlights the top-performing states, such as Maharashtra, Karnataka, and Tamil 
Nadu, to understand geographical demand patterns.
• Evaluating Sales Channels: The visualizations assesses the effectiveness of 
different sales channels by comparing the quantity of clothes sold on Amazon.in 
versus Non-Amazon channels. This evaluation helps understand the dominance 
of Amazon's own platform and the potential impact of external sales channels.
• Identifying Popular Ship Service Levels: The visualizations ranks states based 
on quantity and category, considering the ship service levels used. This analysis 
helps identify popular ship service options and their impact on sales and 
customer satisfaction.
• Identifying Popular Clothes Sub Category: The visualizations examines the 
cloth sub category with the total amount , so that the organization can 
concentrate more on one.
• Monitoring Order Status and Courier Performance: The visualizations 
examines the quantity of clothes by status and category to understand the 
distribution across different stages of the order process. Additionally, it assesses 
the quantity by courier status and category to evaluate the performance of 
different courier services.

Visualizations :
• Map: Quantity by States
The visualization "Map: Quantity by States" provides insights into the quantity of 
clothes shipped across different states. Based on the data, the top three states with 
the highest quantity of clothes shipped are:
1. Maharashtra: The state of Maharashtra leads with a total quantity of 20,328 
clothes shipped.
2. Karnataka: Following closely is Karnataka, with a significant quantity of 
15,901 clothes shipped.
3. Tamil Nadu: Tamil Nadu secures the third position with a quantity of 10,412 
clothes shipped.
These findings highlight the importance of these states as key markets for the 
clothes category on Amazon India. Understanding the distribution of sales quantity 
across states allows us to identify areas of high demand and tailor marketing and 
inventory strategies accordingly. Maharashtra, Karnataka, and Tamil Nadu present 
promising opportunities for growth and further market penetration in the clothes 
category.

Steps to develop :
In the visualization "Map: Quantity by States," I have utilized default latitudes and 
longitudes developed by Tableau to represent the quantity of clothes shipped across 
different states. To create this visualization, I employed the "sum of quantity" as 
the primary measure and utilized the fields "ship state" and "ship country" to 
geographically map the data. By leveraging these default coordinates, I was able to 
effectively visualize the distribution of clothes quantity across various states, 
providing a clear understanding of the sales patterns on a geographical level. This 
visualization offers valuable insights into which states have higher demand for 
clothes, allowing for targeted marketing strategies and optimized inventory 
management in those regions.

• Clothes Sub Category and Total Amount
The visualization "Clothes Sub Category and Total Amount" reveals the top three 
clothes subcategories based on their total sales amount. These subcategories are:
1. Set: The "Set" subcategory has achieved the highest total sales amount 
(39,204,124) among all clothes subcategories.
2. Kurta: Following closely is the "Kurta" subcategory, which also demonstrates 
a significant total sales amount (21,299,547).
3. Western Dress: The "Western Dress" subcategory secures the third position in 
terms of total sales amount(11,216,073).
These findings emphasize the popularity and profitability of these subcategories 
within the clothes category on Amazon India. The success of "Set," "Kurta," and 
"Western Dress" subcategories suggests that they resonate well with customers, 
potentially indicating strong demand and customer preference. Understanding the 
performance of specific subcategories allows for strategic decision-making, such 
as inventory management and marketing efforts, to further capitalize on these 
successful subcategories.

Steps to develop :
In this visualization "Clothes Sub Category and Total Amount," I examined the 
relationship between different clothes subcategories and their corresponding total 
sales amounts. By aggregating the data based on categories, I determined the total 
amount associated with each subcategory. This analysis provides valuable insights 
into the popularity and profitability of different subcategories within the clothes 
category. By understanding which subcategories generate higher sales amounts, we 
can make informed decisions regarding inventory management, marketing 
strategies, and product development.

• Top 5 States by Quantity and Shipping Type
The visualization "Top 5 States by Quantity and Shipping Type" highlights the top 
five states based on the quantity of clothes shipped, categorized by shipping type. 
The states are as follows:
1. Maharashtra: Maharashtra is the top state in terms of the quantity of clothes 
shipped.
2. Karnataka: Following closely is Karnataka, securing the second position in 
terms of the quantity of clothes shipped.
3. Tamil Nadu: Tamil Nadu ranks third among the top five states based on the 
quantity of clothes shipped.
The visualization provides valuable insights into the distribution of clothes shipped 
across different states and allows us to understand the preferences for shipping 
types in each state. By analyzing these top states, we can identify key markets and 
tailor our logistics and shipping strategies accordingly to optimize the delivery 
process and enhance customer satisfaction.

Steps to develop :
In the visualization "Top 5 States by Quantity and Shipping Type," I explored the 
top five states based on the quantity of clothes shipped, categorized by ship service 
level. By aggregating the data and analyzing the sum of quantity for each state and 
ship service level, and have filtered the data by taking only top 5 using the edit 
filter option, here we can gain insights into the preferences and trends in shipping 
methods. Additionally, I considered the category of the clothes being shipped as a 
filter.
This visualization allows us to identify the states that have the highest quantities of 
clothes shipped and understand the specific ship service levels chosen by 
customers in those states.

• Quantity by Sales Channel
The visualization "Quantity by Sales Channel" presents the distribution of clothes 
quantity based on different sales channels. The analysis reveals the following 
insights:
1. Amazon.in: The sales channel Amazon.in stands out as the dominant 
platform, accounting for a substantial quantity of 116,482 clothes shipped.
2. Non-Amazon: Non-Amazon channels, on the other hand, contribute a 
comparatively smaller quantity of 167 clothes shipped.
This visualization underscores the significance of Amazon's own platform, 
Amazon.in, as the primary sales channel for the clothes category on Amazon India. 
The large quantity associated with Amazon.in highlights its strong presence and 
customer reach, indicating its influence on overall sales performance. While the 
contribution from Non-Amazon channels is relatively smaller, it still represents an 
opportunity for growth and diversification. Analyzing the quantity by sales channel 
allows us to understand the market landscape and make informed decisions 
regarding channel optimization and resource allocation.

Steps to develop :
In the visualization "Quantity by Sales Channel," I examined by createing a square 
using the quantity of clothes sold across different sales channels. By aggregating 
the data and analyzing the sum of quantity for each sales channel, I gained insights 
into the distribution of sales among various channels. Additionally, I considered the 
category of the clothes as a filter .
This visualization allowed me to identify the dominant sales channel, Amazon.in, 
which accounted for a significant quantity of clothes sold. I also observed a smaller 
quantity of clothes sold through Non-Amazon channels.

• Quantity by Status of the Delivery
The visualization "Quantity by Status of the Delivery" provides insights into the 
distribution of clothes quantity based on the status of delivery. Here are the key 
findings:
1. Shipped: The majority of clothes, with a quantity of 77,851, are in the 
"Shipped" status. This indicates that these orders have been dispatched for 
delivery.
2. Shipped - Delivered to Buyer: A significant quantity of 28,886 clothes have 
been successfully delivered to the buyers.
3. Cancelled: A smaller quantity of 5,656 clothes orders have been cancelled.
4. Shipped and Returned to Seller: A quantity of 1,970 clothes orders were 
initially shipped but subsequently returned to the seller.
5. Shipped - Pickup: There are 977 clothes orders in the "Shipped - Pickup" 
status.
6. Pending: A total of 657 clothes orders are currently in the "Pending" status.
By examining the quantity by status of the delivery, we gain insights into the 
various stages of the delivery process and order fulfillment. This information 
allows us to monitor the performance of the delivery system, identify potential 
bottlenecks, and take corrective actions to improve customer satisfaction.

Steps to develop :
In the visualization "Quantity by Status of the Delivery," I created a bar chart to 
explore the distribution of clothes quantity based on different delivery statuses. By 
selecting and dragging the appropriate chart type, I visually represented the sum of 
quantity for each delivery status. Additionally, I took into account the category of 
the clothes being delivered.

Interactive Dashboard Filter:
In the design of this interactive dashboard, filtering functionality has been 
implemented based on clothing subcategories. Users can leverage the interactive 
filters to refine the data and focus on specific subcategories of interest. By 
selecting a particular subcategory, the visualizations dynamically update to display 
insights and patterns specific to that clothing subcategory. This filtering capability 
allows users to drill down into the data, analyze individual subcategories in detail, 
and gain a deeper understanding of their performance and trends. By filtering 
based on clothing subcategories, users can explore and extract valuable insights 
tailored to their specific areas of interest within the clothes category. This 
interactive feature enhances the usability and flexibility of the dashboard, 
empowering users to perform targeted analysis and make data-driven decisions 
related to different clothing subcategories.

Key Principles Employed :
The successful implementation of Gestalt principles of visual perception has 
greatly enhanced the clarity and organization of the dashboard used in this report. 
By strategically applying principles such as proximity, similarity, and closure, 
related elements have been intuitively grouped together, enabling viewers to easily 
identify patterns and establish a cohesive visual structure. This design approach 
ensures that the dashboard effectively communicates information and facilitates 
efficient data interpretation.
Furthermore, inclusivity and accessibility have been prioritized throughout the 
design process. I took the initiative to check for color blindness issues using the 
Coblis website, ensuring that the chosen color palette is accessible to individuals 
with different color perception abilities. By addressing potential barriers to 
comprehension, the dashboard accommodates a wider audience and promotes 
equal access to information.
Additionally, the selection of an appropriate font significantly contributes to the
overall clarity and legibility of the dashboard. 
By choosing a font that is clear, visually 
appealing, and suitable for the content, the 
readability of the presented information is 
enhanced. This careful font selection ensures 
that viewers can comfortably engage with the 
data, eliminating any unnecessary strain or 
difficulty in reading.

In conclusion, through the thoughtful 
application of Gestalt principles, consideration for accessibility, and the use of an 
appropriate font, the dashboard design for this report successfully delivers 
information in a visually appealing and accessible manner. By utilizing these 
design strategies, the dashboard not only effectively communicates insights but 
also promotes better comprehension and engagement. It serves as a valuable tool 
for data analysis and decision-making, and I am confident in the quality and 
effectiveness of the visualizations presented in my report.

Conclusion:
In conclusion, the visualizations presented in this dashboard provide valuable 
insights into the sales and shipping analytics of the clothes category on Amazon 
India. Through the use of interactive and visually appealing visualizations, I have 
explored various aspects of the data, including quantity by states, sales channel 
distribution, clothing subcategories, top-performing states by quantity and shipping 
type, and quantity by delivery status. These visualizations enable us to identify key 
market trends, understand customer preferences, optimize sales channels, and 
evaluate the efficiency of the delivery process.
By leveraging the Gestalt principles of visual perception, I have enhanced the 
clarity and organization of the dashboard, allowing for easy comprehension and 
data exploration. Additionally, I have considered accessibility by checking for 
color blindness issues and selecting an appropriate font, ensuring inclusivity and 
improved readability for all users.
The interactive features of the dashboard, such as filtering by clothing subcategory, 
further enhance user engagement and enable customized data exploration. Users 
can drill down into specific subcategories to uncover deeper insights and make 
informed decisions based on their specific interests.
Overall, this dashboard provides a comprehensive and actionable view of the sales 
and shipping analytics in the clothes category on Amazon India. It serves as a 
valuable tool for decision-making, enabling us to optimize inventory management, 
tailor marketing strategies, improve delivery processes, and ultimately enhance 
customer satisfaction. By leveraging the insights gained from these visualizations, 
we are well-equipped to drive growth, maximize profitability, and make datadriven decisions in the dynamic e-commerce landscape.

THE END
