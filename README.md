### Analysis and Recommendation of Rental Listings

### Team Members
  - Rakesh Amireddy 
  - Saliha Mehboob
  - Sadia Yousafzai 
  - Thasleem Tajudeen
  
 #### Airbnb Dataset:
   [Airbnb Dataset](http://insideairbnb.com/get-the-data.html)
   
  #### Steps
   - DataPrep_Preprocess.ipynb -> Preprocessing Data Set to select Relevant features and impute missing values
   - Content-Based-Recommender.ipynb -> Provide Top N listing recommendation to users based on Cosine similarity in Listings Description
  ###Sentiment Analysis
  Pyspark is used to perfrom sentiment analysis on reviews dataset.
  Go to Foler Sentiment Analysis and open jupyter notebook and run 
  ```
  Accuracy_sentiment_analyzer.ipynb
  ```
  
  #### Hybrid Recommmendation steps
   ##### Required Packages
       Pandas
       sns, Matplotlib
       pyspark.mllib.recommendation 
       pyspark.sql
  1. [Download](Recommendation%20systems/Hybrid_Preprocess.ipynb) and run Hybrid_Preprocess.ipynb. This will save clean_ratings.csv
  2. Use the saved csv file, [Download](Recommendation%20systems/Hybrid_Airbnb_Recommendation.ipynb) and run Hybrid_Airbnb_Recommendation.ipynb to get recommendations
       
       
