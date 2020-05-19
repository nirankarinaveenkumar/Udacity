# Data-Science
# How to Predict Life Expectancy using Machine Learning
You can find the link to the Medium Post here - https://medium.com/@nirankari.naveen.13et1136/how-to-predict-life-expectancy-using-machine-learning-5c253ab25125

Life expectancy refers to the average age a person is estimated to live and is an important factor to determine the population health of any country. In the pre-modern world, Life expectancy was very less close to about 30 years but after 19th Century life expectancy started to increase and it nearly doubled. There has been constant debate regarding how developed countries have more life expectancy as compared to developing or underdeveloped countries and hence to get a clear picture of this I decided to analyze the Life Expectancy dataset which I took from Kaggle.

## Data Understanding
As we can clearly see that the Developed countries had high Life expectancy as compared to developing countries apart from a few exceptions in the years 2008 and 2009.

## How do Infant and Adult mortality rates affect life expectancy?
Infant death rates do not show much of a relationship with life expectancy. Adult mortality does have a significant relationship with life expectancy.

## What is the impact of schooling on the lifespan of humans?
Schooling also does not have a significant effect on life expectancy, we can see that people who have low schooling can also live more and those who have more schooling also live more.

## What is the impact of Immunization coverage on life Expectancy?
The immunization of Polio does impact Life expectancy and can be used for predicting it.

# Data Preprocessing
Filling missing values with mean or median based on their current Country or Status i.e Developed or Developing.

### Using Standard Scaler for scaling because the data is skewed and does not follow normal distribution from the above graphs, and even to address the outliers where the data will be standardized.

# Fitting the model
Used grid search to find the best parameters for Support Vector Machine using ‘rbf’ kernel. The Best parameters were C=100 and gamma=0.01. The train score is 94% and the test score is 90%.

# Conclusion
Life expectancy is more in developed countries and less in developing countries and using machine learning techniques we can correctly predict life expectancy. The places where there are immunization and less adult mortality the life expectancy is more.
