# Books-Recommendation-System

#### Building different types of recommendation system using various similarity measures like correlation and learning algorithms like unsupervised machine learning &amp; reinforcement learning for recommending books.

BX-Books dataset available in internet is taken and used for exploring various types of recommendation system and make a comparative study on the types of the RSs built with respect to changes made in the type of learning method and measures. 

### Non-Personalized Recommendation System
A Non-personalized (popularity-based) RS is built by following the below-mentioned steps. To identify the popular books among the users:

1. "highly_rated" books are identified based on a threshold value of 7 and all books are assigned a boolean value.
2. Count of the highly_rated books is stored to the variable "ratings_count"
3. Top 10 popular books are thus identified and recommended.

Since non-personalized recommendation system takes the ratings provided by many users as input and provides same recommendations for all users i.e. not personalized it does not satisfy many users. 

### Content-based Filtering Recommendation System
This type of RecSys is identified to be fast and reliable as the recommendations provided are completely based on the content. There will never be any lack of information in this type of method as the system will not require very large data for working. This model takes item-data as input and provide recommendations based only on the item-to-item similarity. This method do not require user-data for processing. Content-based filtering never faces any type of cold-start problem as the similarity is calculated based on items only. 
