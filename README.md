
Customer segmentation is a popular data analysis technique used in retail for identifying similar groups of customers. In this project, we apply K-Means clustering to group customers with similar purchasing patterns.

The primary steps in this project include:

Data loading and preprocessing.
Applying the Elbow method to determine the optimal number of clusters.
Clustering customers and visualizing the clusters.
Analyzing cluster characteristics.


Dataset
The dataset Mall_Customers.csv contains the following columns:

CustomerID: Unique identifier for each customer (not used in clustering).
Gender: Gender of the customer.
Age: Age of the customer.
Annual Income (k$): Customer’s annual income in thousands.
Spending Score (1-100): A score assigned by the store based on customer spending patterns.
Project Structure
Mall_Customers.csv - Input dataset containing customer data.
customer_segmentation.py - Script to perform K-Means clustering.
README.md - Project documentation.
Requirements
To run this project, install the following libraries:

pip install pandas numpy matplotlib seaborn scikit-learn


Implementation

Data Preprocessing:

Load and inspect the data.
Drop any irrelevant columns (e.g., CustomerID).
Standardize the Annual Income and Spending Score features for improved clustering performance.
Optimal Clusters with Elbow Method:

Use the elbow method to determine the ideal number of clusters by plotting inertia values.
K-Means Clustering:

Apply K-Means with the selected number of clusters.
Assign each customer to a cluster and add this information to the dataset.

Visualization:

Visualize the customer segments to observe distinct clusters.
