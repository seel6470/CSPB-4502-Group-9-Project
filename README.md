# Trends and Analysis of eCommerce Data 

## Team Members
Francesca Barrios frba7936@colorado.edu
Laura Brown labr1398@colorado.edu
Seth Ely seel6470@colorado.edu
Darby Hansen daha2377@colorado.edu

## Project Description
When looking at eCommerce, it is critical do understand consumer behavior and market trends in order to succeed in the industry. In this project, our group's objective was to gain insights from a dataset sourced form a multi-category online store. The dataset ranges from October 2019 to April 2020. From this dataset, we worked to identify different trends and patterns accross various brands and categories. To accomplish this, we started by cleaning the data removing erroneous and duplicate entries. From there, we were able to transform the data by grouping it into different subsections. This grouped data was then filtered and used to create visualizations that showed different trends and patterns. 

## Questions and Discoveries
Which brands, or item categories exhibit the highest volume of sales and profits during the specified period? 
After creating frequency bar plots for category and brand, the construction category and the Samsung brand had the highest volume of sales over the seven month period. In terms of profits, the construction category and the Apple brand were the most profitable. 

Among the features of brands and item categories, which ones demonstrate the highest purchases per view ratio? 
After analyzing the data it seems that the lowest revenue producer, stationery.paper, has the highest purchases per view. This is most likely due to people intentionally visting those products to purchase and not visiting for leisure. 

Can seasonal patterns be identified within the 7-month window of the dataset? 
In the plots generated, the top five grossing brands and categories are plotted. In both, the top two grossing categories and brands have the highest degree of change while the other have very little change. For the brand plot, the lines representing Apple and Samsung both experience a peak in December.  In the category plot, the line representing the construction category also experiences a peak in December with a significant drop from February to March. When looking at the line for electronics, profits are fairly consistent until March when it experiences a significant jump.

Which products are similar, and can we generate a suggested list of items for users based on this data? 
To discover this a K-Means algorithm was implemented usign category_code and brand pairings. Scatter plots were created and showed that there were similar products associated with almost every brand. Using the output of the K-Means algorithm, we would easily be able to create a new characteristic for each product representing it's associated cluster, and a random generator could be used to retrieve several items belonging to the same cluster as the product being viewed.

## Application of Findings
After analyzing the data, it became evident that certain brands and item categories stand out in terms of both sales volume and profitability.These findings can help this company do better in catering to their customers. By knowing which brands and categories have the highest sales and profits, they can allocate resources, such as marketing budgets and inventory, more effectively by focusing on the products that generate the highest returns. They can also prioritize innovation and investment in products within these categories to capitalize on consumer demand and preferences. The seasonal trends observed can also help with this. Seeing where different categories jump in profits will help the company focus on when to promote products within those categories.

The K-means algorithm is useful in predicting products similar to what is being viewed. It can suggest other products within the same category or other items that were frequently bought with the currently viewed item. The company can use it to entice users to buy more items or help them find similar items that are a different brand or price. It will help improve the customer's shopping experience and their satisfaction. By predicting products, it can help guide them to products they might not have found otherwise and increase the probability of a purchase.

## Video Demonstration
[Group 9 Video Presentation](https://youtu.be/I1ga_mxDZSs)

## Final Project Link
[09_TrendsAndAnalysisofeCommerceData_Part4](./09_TrendsAndAnalysisofeCommerceData_Part4.pdf)
