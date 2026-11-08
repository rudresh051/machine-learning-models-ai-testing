# Unsupervised Learning models Testing in Engineering phase

## Introduction to Unsupervised Learning in the ML models with example


**Unsupervised Learning**  

1. **Definition:** Unsupervised learning is an ML approach where the model is trained using input data (features) without predefined output labels (Y). Unlike supervised learning, the model discovers patterns independently.

2. **Example – Targeted Ads:** Platforms like Instagram and Facebook group users based on demographics such as age, gender and location to deliver relevant advertisements.

3. **Clustering:** The algorithm groups similar data points into clusters based on common characteristics. Example: Users from similar locations and age groups may belong to the same cluster.

4. **Cluster Configuration:** Developers can define the number of clusters required based on business needs. The model assigns new data points to appropriate clusters.

5. **Business Applications:**

- Targeted advertising based on customer demographics.
- Customer segmentation.
- Sales analysis and identifying purchasing patterns.
- Identifying high-performing customer groups.

6. **QA Perspective:** First identify whether the ML model uses supervised or unsupervised learning. For unsupervised models, focus on input data quality, clustering behaviour, correct grouping and consistency of results.

**Key takeaway:** Supervised learning predicts using labelled data, whereas unsupervised learning discovers hidden patterns and groups in unlabelled data.

## Testing scope on Unsupervised Learning with Data point patterns&Cluster scores

> Explore how unsupervised learning groups data point patterns into clusters, uses silhouette scores, and performs white-box quality assurance checks with underfitting, overfitting, and validation data.

1. **Unsupervised Learning:** The algorithm identifies patterns and creates clusters from unlabelled input data. Example: grouping customers by demographics to identify high-sales regions.

2. **Black-box Functional Testing:**

- Provide validation data and check whether new data points are assigned to the expected clusters.
- Underfitting: Insufficient training data; clusters are immature and outputs are inaccurate or random.
- Good fit: Data points are correctly grouped, and the algorithm identifies meaningful patterns.
- Overfitting: With excessive training, new data points may deviate from their expected clusters, reducing output quality.

3. **White-box Testing:** Coordinate with developers to use Python utilities and evaluate clustering performance.

4. **Silhouette Score:**

- Range: -1 to +1.
- +1: Data point is close to its intended cluster.
- 0: Data point is near cluster boundaries or deviating.
- -1: Data point is likely assigned to the wrong cluster.

5. **QA Responsibility:** Monitor clustering quality across training iterations, identify underfitting/overfitting, and run continuous smoke tests. Stop training and tune hyperparameters when performance starts degrading.

**Key Takeaway:** QA validates clustering behaviour through black-box testing and uses metrics like Silhouette Score with developer support to assess model quality.


## Revision on Unsupervised Learning with cluster score analysis

