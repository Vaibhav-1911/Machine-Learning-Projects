## Dataset
#### Dataset Name: insurance.csv
#### Dataset Source: https://www.kaggle.com/mirichoi0218/insurance
#### Description: The dataset contains data with respect to the medical insurance charges based on different considerable factors
#### Content:
##### Columns

###### age: age of primary beneficiary
###### sex: insurance contractor gender, female, male
###### bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height,
###### objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9
###### children: Number of children covered by health insurance / Number of dependents
###### smoker: Smoking
###### region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.
###### charges: Individual medical costs billed by health insurance


## Business Problem
#### To understand what factors influence the Insurance charges that people incur. Being able to predict which factors are more powerful determinants of the insurance charges than others and which of these factors people can control in order to have a lesser insurance spends and a better overall lifestyle

## EDA Findings
#### - The relationship between No. of Children a person has with respect to the instances where insurance rates are high is inversely propotional. This could very easily be due to lesser people having a higher number of children
#### - Charges seem to be on the higher side for people as their age increses
#### - Most of our data is right skewed when it comes to charges. Mostly people have insurance charges between the 5000 - 25000 dollars range
#### - A person who smokes and has a BMI above 30 tends to have a higher medical cost
#### - Older people who are also smokers, have a higher insurance charge
#### - There is no significant difference between insurance charges between males and females. However, it must be noted that people with 5 children have significantly less insurance charges when compared to people with 0-4 children
#### - People who are obese and also smoke have very expensive insurance charges on an average. Also, smokers in general have higher insurance charges as compared to non-smokers
