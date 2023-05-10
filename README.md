# Customer_Segmentation

Customer segmentation models are often used for dividing a company’s clients into different user groups. Customers in each group display shared characteristics that distinguish them from other users.

We have used an E-Commerce Dataset from Kaggle that contains transaction information from around 4,000 customers.
[Dataset link](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

We have done analysis to have a basic understanding of the dataset.

Then we have found the three important features of Customer analysis which are RFM.

📅R:Recency
🔁F:Frequency
🤑M:Monetary Value

Later we removed the outliers of data by removing instances that has zscore>3. 
To maintain a normal distribution 📊 of all three features we scaled the features accordingly.

For final clustering, we used K-means clustering.

To decide K(number of clusters) wwe have used the heuristic Elbow approach.

Final clustering is done iwth decided K value and then predictions happens.

And then we visualise our data and cluster.




