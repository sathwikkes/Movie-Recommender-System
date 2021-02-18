# TMDB Movie Data Analysis & Simple Recommender System  
This is my **Second Capstone** for Springboard's Data Science Career Track curriculum  
The project is split into three parts, beginning with data exploration to model building to recommendation engine  
 
### Motivation/Context   
My final undergraduate project was focused on Google’s Page Rank and the mathematics behind it (*Perron Frobenius thm*). Learning how a search engine works was very similar to understanding what goes in the background of how a recommender system functions. Recommendation engines are everywhere and just to list a few popular applications: Spotify, YouTube, Amazon, Netflix, Facebook. *The Social Dilemma* is a great documentary that focused on data privacy and uncovered how big corporations leverage personal data for their own benefit. What better way to understand how the mechanism works than trying to build it?  
  
### Problem Statement  
Company XYZ is a video streaming platform that lets its members watch TV shows and movies without advertisements on any internet-connected device. Company XYZ wants to build a model based on movie attributes to recommend the right movie and increase their cick rate.       

*If you would like to see a simple diagram of the whole workflow, check out the workflow pdf* 

1. Data     
   - Kaggle: Data was retrieved from [Link to Kaggle Data Source](https://www.kaggle.com/rounakbanik/the-movies-dataset)     

2. Data Cleaning      

3. Exploratory Data Analysis  

4. Algorithms & Machine Learning  
*Ran tree based algorithms and hyperparameter tuned the models using RandomizedCV*
   - Random Forest Regressor    
   - Gradient Boosting Regressor    
   - XGBoost Regressor    

5. Method    
   - Collaborative Filtering using Similarity, Correlation, & K-Nearest Neighbors        
   - Content Filtering       
   - Hybrid Technique based of IMDB Formula        

6. Predictions    
   - Matrix Factorization   
   - Singular Value Decomposition  

7. Future Improvements  
Looking ahead, I would like to rerun my machine learning models from my second jupyter notebook with the imputed predicted ratings from my recommender portion to see if I would get better results. In addition, I want to deploy an improved recommender system, possibly using deep learning, on my personal website for interactive purposes.     

8. Conclusion  
Recommender Systems are very common in present day technology. Items can get suggested in many ways and the best feeling is discovering something new and that you like. 
