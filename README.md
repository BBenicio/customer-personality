# Customer Personality Analysis

Customer Personality Analysis is a detailed analysis of a company’s ideal customers. It helps a business to better understand its customers and makes it easier for them to modify products according to the specific needs, behaviors and concerns of different types of customers. From https://www.kaggle.com/imakash3011/customer-personality-analysis

In the `customer_personality.ipynb` Jupyter Notebook, we analyse the data, process it, and cluster using different algorithms. After clustering we attempt to visualize it and analyse each of the clusters to see what each cluster represents.

The chosen algorithm and number of clusters achieved a silhouette score of `0.531930125140841`

Our findings are summarized in the text that follows.

## Final Remarks
Cluster 0:
- Income centered around 60k
- Focused on customers with no kids but teens at home
- All of the _21_ customers who complained are in this cluster
- Median buyers, prefer web or store
- Accepted the 3rd offer

Cluster 1:
- Higher income (around 80k)
- Focused on customers with no kids or teens at home
- High-spenders, spent more than any other cluster
- Accepted more of the 1st and 5th offers

Cluster 2:
- Lower income (around 40k)
- Focused on customers with kids or teens at home
- Low-spenders, spent little money on all products
- Customers who don't make many purchases but visit the website a lot more
- Didn't accept the offers

Cluster 3:
- Only 30 customers
- Customers seem to spend some money on products
- All accepted the 2nd offer
- More customers accepted the final offer than not
