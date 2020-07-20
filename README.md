# Problem Statement
Building a product recommendation system for an online e-commerce website like Amazon etc.

# Amazon_Product_Recommendation_System
Recommendation algorithms are best known for their use on e-commerce web sites. Online shopping is one of the most popular things on internet. E-commerce websites Walmart, amazon etc use different recommendation systems to provide recommendations to each customer. These websites are known now only for their verities of product but also for their strong recommendation system.<br>

In this project we are going to build recommendation model for the fine-food products of Amazon. We use data set of amazon fine-food products taken from kaggle. We are considering the reviews and ratings given by the user to different products as well as his/her reviews about his/her experience with the product(s). Based on these inputs, we used Collaborative Filtering recommendation model based on matrix factorization and popularity-based recommendation model.<br>

Popularity-based recommendation model: This system works based on popularity. It uses the items which are in trend right now. There is some problem with popularity based recommendation system as well. The problem is that there is no personalization available with this method. Even though you know the behaviour of the user you cannot recommend items accordingly.<br>

Collaborative Filtering recommendation model: It matches each of the user’s purchased and rating items to similar items, then combines those similar items into a recommendation list. To determine the most-similar match for a given item, the algorithm builds a similar-items table by finding items that customers tend to purchase together. We could build a product-to-product matrix by iterating through all item pairs and computing a similarity metric for each pair.<br>

# Conclusion
Recommendation model provides a type of personalized shopping experience for each customer. For retailers like Amazon, a good recommendation algorithm is required. In our project we analysed the fine food items dataset and trained our model. We split the data randomly into train data and test data into 80:20 ratio i.e. 80% train data and 20% test data. Then we use collaborative filtering model based on matrix factorization and popularity based recommendation model.

# DataSet
Dataset is taken from https://hck.re/VWh7Yz
