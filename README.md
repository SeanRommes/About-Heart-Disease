# Project-2, A Heart Disease Dataset

## In this data set I explore the highest factors related to heart disease and who is most at risk. What should you be concerned about and what can you safely ignore? The results may surprise you as I investigate this silent killer and hopefully provide you with some valuable insights! My aim is to build a pedictive machine learning model that can help doctors with the prescreening process, saving valuable time and catching it early!

###The Data:
  Source: https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction
  Every dataset used can be found under the Index of heart disease datasets from UCI Machine Learning Repository on the following link: https://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/
  
  ##Methods
  I invoke the standard methods of data cleaning and analysis to purge the data set of the ungodly horrors that are missing values and duplicate rows!
  
  I then present you with some of the outliers visually and explore each feature using histograms, boxplots, heatmaps, catplots, and lineplots.
  
  After getting a good overview of the data I prepare the model for machine learning and perform a little feature engineering to improve the accuarcy of my model
  
  Lastly I have built 4 machine learning models and pit them against each other in glorious metric analysis... ! I used a linear regression model, random forest, decision tree, and knn.
  
  ##Teasers
  ![Screenshot (36)](https://user-images.githubusercontent.com/107956865/186997334-4969ded5-1f00-4fd5-bfa3-79afc05a0e94.png)
![Screenshot (37)](https://user-images.githubusercontent.com/107956865/186997348-ce9ca689-98c5-419c-9609-cfa821746ff7.png)
![Screenshot (39)](https://user-images.githubusercontent.com/107956865/186997359-789a838d-300f-476d-a65d-73ed907d5727.png)

  ##Spoliers
  
  I decided to go with my KNN model. After some tuning it was the most well balanced and performed fairly well on the data and the least error prone of the models.
  With only an r2 score of 50 on the training set, it scored a 44 on the test set, making it the least over fit of my models. While perhaps not the highest of scores I chose it for it's balance and adaptability as well. Hopefully with more data I can get a higher scoreing model! 
  
  ## Limitations & Next Steps

   low scores and overfitting, will have to reduce bias/variance with feature engineering or a larger data set
   
   ### For further information


For any additional questions, please contact **seanrommes@gmail.com**
