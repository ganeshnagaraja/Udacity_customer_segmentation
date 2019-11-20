# Udacity_customer_segmentation

Creating Customer Segments

Analyze data on various customers' annual spending amounts (reported in monetary units) of diverse product categories for internal structure. Describe the variation in the different types of customers that a wholesale distributor interacts with. Doing so would equip the distributor with insight into how to best structure their delivery service to meet the needs of each customer.

Used feature relevence technique to determine the critical data points of the dataset.Plotted a scatter matrix to visualize feature distribution which gave an insight into the data - check if the data is skewed, do data points have any correlation amongst them.
Preprocessd the data by feature scaling(applied natural logarithm). detecting the outlier by using Turkey's method- which segregates the data based on the percentage of data in percentile range in a bell curve and eliminating such data points. Implemented PCA to explain variance in data between different principal components. I also implemented K-means and Gaussian Mixture Model to visualize the different clusters to which the customer falls. 
