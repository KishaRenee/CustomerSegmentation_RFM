Marketing Analytics -Unsupervised Learning clustering algorithmn.

Objective : We are performing customer segmentation based on key attributes Recency, Frequency & Monetary (RFM) using K-means.

What is customer segmentation and why bother ?

What is customer segmentation ?
Customer segmentation is the division of customers into various groups based on specific attributes. Segmentation types may vary based on these four main characteristics/variable-types:

1. Demographics (eg. age, incme, gender etc.) 
2. Geographic regions (eg. country, region, city, town etc.)
3. Psychographic (eg. interests, personality traits, attitudes, views )
4. Behaviour (eg. actual spending pattern/actual purchases)
Benefits of Segmentation

Marketers segment customers because it allows them to better understand the various types of customers and hence better serve their needs to ultimately yield increase in revenue. Better served customers are happier customers and happier customers spend more leading to a more favourle company bottom-line.

So, in short, if we adopt a more tailored approach to they way we market products/services to our customer the customers feel more valued and the company benefits financially. This bets the one-size fits all approach (when no differentiation is made among customers).

This segmentation of customers also helps companies to identify customers that are their most valuable customers and hence direct more efforts at those customers and less on the customers that have been the least profitable. Segmentation based on behaviour (type #4 above) offers this approach where, based on attributes such as : (i) Recency (R) - the last time a purchase was made (ii) Frequency (F) - the cummulative number of transactions conducted. (iii) Monetary Value (M) - the total cummulative amount spent.

This is known as RFM segmentation and scoring.

Our work will be focused on RFM using K-Means Machine Learning Clustering technique.

Methodology for Model Building
Steps :
Problem Definition

Data Collection

Dataset : Online retail dataset (source:http://archive.ics.uci.edu/ml/datasets/online+retail)

Data Preparation
(i) Data Exloration
(ii) Data Cleaning
(iii) Data Analysis
(iv) Feature Selection
    - Identify Recency, Frequency & Monetary Value features (RFM)
(v) Data Preprocessing
    - Scale features
Perform K-Means clustering based on RFM features

Choose optimal K clusters

   - uses Elbow method (visualization of average distance across clusters for k number of clusters,
     choosing the cluster kn where kn+1 reflects a marginal decrease in the avg. distance )
Identify best customers, valuable customers at highest risk of churn

Main Python Libraries used:
pandas - mainly for EDA
numpy - mainly for EDA
sklearn - machine learning
Matplotlib - visualizations
