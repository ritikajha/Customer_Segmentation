# Customer_Segmentation

Customer segmentation models are often used for dividing a company’s clients into different user groups. Customers in each group display shared characteristics that distinguish them from other users.

The E-Commerce Dataset from Kaggle that contains transaction information from around 4,000 customers is used.
[Dataset link](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

Analysis to have a basic understanding of the dataset is done.

Then, the three important features of Customer analysis which are RFM is done.

📅R:Recency
🔁F:Frequency
🤑M:Monetary Value

Later removed the outliers of data by removing instances that has zscore>3. 
To maintain a normal distribution 📊 of all three features we scaled the features accordingly.

For final clustering,K-means clustering is used.

To decide K(number of clusters) the heuristic Elbow approach is used.

Final clustering is done with decided K value and then predictions happens.

And then, visualisation of data and clusters is done.




