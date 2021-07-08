# Boston_Housing_Prices
### DATASET 📊
- In this project, I will create, evaluate the performance and predictive power of your model on data collected from homes in suburbs of Boston, Massachusetts. The dataset can be accessed here: https://raw.githubusercontent.com/anhquan0412/boston_housing/master/housing.csv
- My goal is to apply a machine learning model of my choice to predict the price of houses in a Boston neighborhood (which is column 'MEDV')

### MODELS🎓
- I tried 4 different ML models here and use GridSearchCV to find the best model out of the 4. 
- Models used : KNN Regression, Lasso Regression, Ridge Regression, Elastic Net Regression.
 
 
### CONCLUSIONS⚖️
- How relevant today is data that was collected from 1978? How important is inflation?

The cumulative rate of Inflation since 1978 to 2021 is nearly 2600%, so anything cost a dollar back then would cost us almost 27 dollars in 2020. So the data in 1978 has to be adjusted for inflation to be used nowdays.

- Are the features present in the data sufficient to describe a home? Do you think factors like quality of apppliances in the home, square feet of the plot area, presence of pool or not etc should factor in?

After trying 4 ML models, all 4 of them got a very low cross validation score. While it could be the model's problem, the features are certainly insufficient to describe the price of a home. There are way more features that are more relevant for a house's price such as the area of the house in square foot, the number of bedrooms, toilets, bathrooms.

- Is the model robust enough to make consistent predictions?

The model only has around 66% cv 5 score so definitely not consistent enough.

- Would data collected in an urban city like Boston be applicable in a rural city?

No, duh.

- Is it fair to judge the price of an individual home based on the characteristics of the entire neighborhood?

It is fair to an extent, since a poorer neighbourhood may have cheaper house. However, that's only an assumption that we made. As i said earlier, more features must be taken into account for the model to be more effective at recommending house prices.
