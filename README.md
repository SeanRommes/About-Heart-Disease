# Project-2, A Heart Disease Dataset

## In this data set I explore the highest factors related to heart disease and who is most at risk. What should you be concerned about and what can you safely ignore? The results may surprise you as I investigate this silent killer and hopefully provide you with some valuable insights! My aim is to build a pedictive machine learning model that can help doctors with the prescreening process, saving valuable time and catching it early!

### Data:

  Source: https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction
  Every dataset used can be found under the Index of heart disease datasets from UCI Machine Learning Repository on the following link: https://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/
 
### Methods

  I meticulosly examine and clean each column line by line, investigating any abnormalities as I go.
  
  I then present you with some of the outliers visually and explore each feature using histograms, boxplots, heatmaps, catplots, and lineplots.
  
  After getting a good overview of the data I prepare the model for machine learning and perform a little feature engineering to improve the accuarcy of my model
  
  Lastly I have built 4 machine learning models, visualize the metrics, and determine which model is most suited for deployment using a statisical approach. In my machine learning I instantiate a logistics regression model, random forest, decision tree, and knn.
  
### Univariate and Mulitvariate Analysis

![Screenshot (36)](https://user-images.githubusercontent.com/107956865/186997334-4969ded5-1f00-4fd5-bfa3-79afc05a0e94.png)
![Screenshot (37)](https://user-images.githubusercontent.com/107956865/186997348-ce9ca689-98c5-419c-9609-cfa821746ff7.png)
![Screenshot (39)](https://user-images.githubusercontent.com/107956865/186997359-789a838d-300f-476d-a65d-73ed907d5727.png)

### Outcome
  
  I decided to go with my random forest model. After some tuning it was the most well balanced and performed incredibly well on the dataset with only a 4% margin of     error. It was able to accuratly identify 97% of the true negatives and 96% of the true positives meaning only about 1 in 20 patients could miss out on treatment as     an error in prediction.
  
### Limitations & Next Steps

   The model was overfit by about 10% indicating it has a higher tendency for variance and may struggle with new data. The sample size only contained 918 patients so      with a larger dataset to fit the model on, the variance would be reduced. I could also try and reduce some of the model complexity to regularize it somewhat.
   
### For further information


For any additional questions, please contact **seanrommes@gmail.com**
