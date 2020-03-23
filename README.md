# Books-Recommendation-System

###### Building different types of recommendation system using various similarity measures like correlation and learning algorithms like unsupervised machine learning &amp; reinforcement learning for recommending books.

BX-Books dataset available in internet is taken and used for exploring various concepts of recommendation system and make a comparative study on the type of the RSs built with respect to changes made in the type of learning method and measures. 

A Non-personalized (popularity-based) RS is built based on the popularity of the books among the users. To identify the popular books among the users:

    1. "highly_rated" books are identified based on a threshold value of 7 and all books are assigned a boolean value.
    2. Count of the highly_rated books is stored to the variable "ratings_count"
    3. Top 10 popular books are thus identified and recommended.
