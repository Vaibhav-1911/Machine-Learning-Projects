
## Dataset
#### Dataset Name: wildlife.accdb
#### Dataset Source: https://wildlife.faa.gov/search
#### Description: The dataset contains data with respect to the aircraft vs wildlife collisions reported to the Federal Avaiation Administration between the years 1990 to 2021
#### Content:
##### The dataset contains 100 Columns and 256679 rows
##### Link to Readme.xlsx file for column reference: https://github.com/Vaibhav-1911/DATA-602/blob/main/Project/data/read_me.xls


## Business Problem
#### - To Predict whether or not a strike between an aircraft and wildlife cause damage to the aircraft
#### - To understand what factors influence the level of damage given a case of collision between wildlife and an aircraft
#### - To throw light on the cost of repair borne by the US Civil Aviation Industry when such collisions happen 

## EDA Findings
#### - The relationship between the number of strikes and the cost incurred is somewhat directly propotional
#### - Cases of strikes are significantly high when struck by small birds as compared to medium and large sized birds
#### - Most of the strikes happen during the approach phase of flight in a distance less than 40 Nautical miles from the airport
#### - Flights have more cases of collisions during the day and night times as compared to dusk and dawn
#### - Damages requiring Major Repairs or Replacement of Parts count for almost 72.5% of the cost that is incurred by the US Civil Aviation Industry
#### - The highest number of strikes is reported between the months of July and October followed by a peak in the month of May for every year.
#### - There is a sharp dip in the number of cases reported in 2020, possibly due to lesser number of flights running during the pandemic.
#### - The number of reported cases has been almost persistently increasing over the years

## Summary

#### - We conducted EDA on the FAA Wildlife Strikes Dataset and were able to identify categorical variables to build our prediction model
#### - We imputed numerical columns using median values
#### - We used SMOTE algorithm to handle imbalance in our target variable
#### - We used Standard Scaler to Scale our numerical columns to tackle any outliers
#### - We used OneHotEncoder to convert categorical variables to boolean strings to be fed to the model
#### - We ran three different types of models i.e Decision Tree, Random Forest Classifier and Naive Bayes
#### - We compared the performance of each of these models and found the performance of Random Forest Classifier optimum
#### - We tried to improve the model performance using grid search
#### - We were able to successfully build a binary classification random forest model predicting whether an aircraft-wildlife collision will cause damage to the aircraft or not with a 85.15% recall score


## References

- https://www.kaggle.com/alexisbcook/cross-validation
- https://www.simplilearn.com/tutorials/machine-learning-tutorial/random-forest-algorithm
- https://www.python-graph-gallery.com/11-grouped-barplot
- https://scikit-learn.org/stable/index.html
- https://www.kite.com/blog/python/smote-python-imbalanced-learn-for-oversampling/
