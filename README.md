# Project one: FIFA MoneyBall by Ziga Kolar

#### OBJECTIVES 

## Clean and explore dataset 

For simplicty purposes the main statistics of this dataset will be used, so I have removed the rest part of data.

In preparation for exploration and later on our machine learning model,
several column have been converted to numerical types and non numberical charatheristics removed.

Also check for possible null values and correlations between variables.

## Use visuals methods to answer 3 questions:

1. most preferred player foot 
Most players are right footed - unsuprising, since right limbs is the preferred in humans by nature.

2. Comparing wage and age of player
We see best paid players are between 19-24 years of age. However a suprising spike between 27-28, though very small. 

3. Highest paid by country 

Amongst most highly paid players come from England, Germany, Spain, France and Brasil.

## se linear regression model to try predict player value

Aim to normalize the dataset with a boxcox transformation approach,
make a dataset with the desired variables, split it to 80/20 where 20 is the test set and finally fit it onto the linear regression model.

### Result:
An 0.62 r2score is suggesting the model is sufficient of predicting the player value.

### dateset used:

https://www.kaggle.com/ekrembayar/fifa-21-complete-player-dataset?select=fifa21_male2.csv

