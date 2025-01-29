# Chocolate-Bar-Rating

Chocolate, a universally cherished indulgence, offers a spectrum of flavors and qualities that captivate the senses. The "Chocolate Bar Ratings" dataset, curated by Brady Brelinski of the Manhattan Chocolate Society, compiles expert evaluations of over 1,700 chocolate bars, detailing attributes such as company, cocoa percentage, and origin. 

This project aims to uncover relationships and patterns within the chocolate bar ratings dataset and offer insights into the attributes that contribute to higher quality assessments. Specifically, I will harness the power of random forest algorithm to predict chocolate bar ratings. Random forests, a powerful ensemble learning method, construct multiple decision trees during training and output the average prediction for regression tasks. It excels at capturing non-linear relationships and handling mixed datatypes.  Additionally, they provide valuable insights by ranking feature importance. Based on my model results, the top three factors influencing chocolate bar ratings are the cocoa percentage, the specific origin of the beans, and the company that crafted the chocolate bar.

In addition to random forest, I will apply the k-prototypes clustering algorithm to address the dataset's mixed data types. K-prototypes extends the k-means algorithm to accommodate mixed data types by combining the Euclidean distance metric for numerical data with a dissimilarity measure for categorical data. This method enables the grouping of chocolate bars into clusters that share similar characteristics across both numerical and categorical attributes.  However, interpreting clusters, particularly in high-dimensional spaces, can be challenging. As a result, the insights derived from clustering models are limited. 
