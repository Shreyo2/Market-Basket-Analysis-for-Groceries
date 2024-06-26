# Market Basket Analysis for Groceries
Market Basket Analysis is a powerful tool for businesses aiming to optimize product offerings, boost cross-selling opportunities, and refine marketing strategies, ultimately leading to increased revenue, heightened customer satisfaction, and overall business success. This analysis reveals customer purchase behavior, identifying item combinations in shopping carts. This insight guides shelf planners in grouping items effectively and informs retail managers on warehouse stocking to avoid shortages. Here our focus is on forecasting which products a user is likely to buy again.

## Data Collection:
For this project, the datasets at hand comprises of 38,765 transaction records, including member IDs, transaction dates, and item names. This dataset with member IDs was employed to construct a basket model based on customer IDs.

## Analysis:

In this project analysis, I utilized various visualization techniques to gain insights into customer purchasing behavior and product relationships.

•I started by creating a bar chart to identify the 40 most frequently sold items from which “Whole Milk” secured the top position.

•Then, I quickly examined the relationships between different items to get the support value using the Apriori algorithm to create association rules.

•The Apriori algorithm is used to discover frequent item sets in large transactional datasets. The key concepts related to association rule analysis are:

  1.Antecedents: These are the starting items in the association rule, representing the "if" part.

  2.Consequents: These are the items typically purchased along with the antecedents, representing the "then" part of the association rule.

  3.Support: This metric measures the frequency of a specific combination of items appearing in the dataset. It reflects the proportion of transactions in which the items are bought together.

  4.Confidence: Confidence quantifies the likelihood of purchasing the consequent item when the antecedent item is already in the basket. It represents the probability of buying the consequent item given the presence of the antecedent item.

  5.Lift: Lift assesses the strength of association between antecedent and consequent items, considering the baseline purchase probability of the consequent item. A value greater than 1 indicates a positive association, while a value less than 1 indicates a negative association.

•After identifying whole milk as the item with the highest support, I selected it for further basket analysis. I thereafter determined the top five items frequently purchased immediately after buying whole milk.

•Heatmaps helps to know how strong the association is based on lift values so using a heatmap, I reviewed the association between antecedents and consequent.

•Finally, I used a network graphic to understand and see the connections between the top 10 percentile items. Whole milk has the highest number of connections with other items.

•This approach helped me gain insights into customer behavior and make informed decisions about product offerings and marketing strategies.

## Conclusion:
Market basket analysis sheds light on customer purchase behavior, crucial for shelf planning and inventory management. The top 10 items, led by whole milk, provide insights into popular purchases. Notably, consequents of whole milk which are other vegetables, rolls/buns, soda, tropical fruit, and yogurt reveal common pairings, aiding in strategic product placement. High confidence levels indicate strong associations with whole milk, guiding effective inventory stocking. Overall, this analysis enables retailers to optimize product arrangements and prevent stock shortages.

For further future analysis, leveraging transaction dates and customer IDs presents opportunities to delve deeper into sales trends and customer behavior. Also, exploring consequents of other items can aid in mitigating product insufficiency by ensuring adequate stocking levels and optimizing inventory management.
