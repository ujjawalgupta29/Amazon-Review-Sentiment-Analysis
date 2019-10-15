# Amazon-Review-Sentiment-Analysis
## Product Category:
#### Sports & Outdoor Reviews
Dataset I worked on is available [here](http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Sports_and_Outdoors_5.json.gz)
_Dataset size_:
296,337 x 10 [ rows x columns ]

| Column headers | description                      |
| -------------- | -------------------------------  |
|  asin          |  Product ID                      |
|  summary       |  Title of review                 |
|  reviewText    |  Written review                  |
|  overall       |  Rating 1-5 (stars)              |
|  reviewerID    |  Reviewer ID                     |
|  reviewerName  |  Person's name (no standard format)  |
|  helpful       |  Helpfulness rating of the review    |
|  reviewTime    |  YYYY-MM--DD                     |
|  unixReviewTime|  Time of the review (unix time)  |
|  pos_neg       |  (1) Positive for 4-5 or (2) Negative for 1-3 Overall rating  |

# Project Outline:

<u>Business motivation</u> :  
For ecommerce sites and outfitters to stay competitive and innovate, they must be able to draw and hold dedicated customers. One particularly effective approach in recent years has been to build personalized recommendation engines into their platform or interface. Determining the specific topics and sentiments associated with given sports and outdoors products is essential in building a recommendation engine. This project is mainly to understand the concepts covered in class and apply them to a specific domain.

<u>Problem formulation</u> :

1. Explore and Process the data in order to glean basic insights about the data and prep to utilize models

2. Finding a classification model that works best with the data.

3. Understanding the topics and words that describe the broad categories of Sports and Outdoors product sold over Amazon.

4. Given the data and model performance, determine what is the best course of actions going forward.
