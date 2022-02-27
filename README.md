# Car-Price-Prediction-Using-Linear-Regression-Model
In statistics, linear regression is a linear approach for modelling the relationship between a scalar response and one or more explanatory variables (also known as the dependent and independent variables). Linear regression was the first type of regression analysis to be studied rigorously, and to be used extensively in practical applications. This is because models which depend linearly on their unknown parameters are easier to fit than models which are non-linearly related to their parameters. Also because the statistical properties of the resulting estimators are easier to determine. Linear regression has many practical uses.

1. If the goal is prediction, forecasting, or error reduction, linear regression can be used to fit a predictive model to an observed data set of values of the response and explanatory variables.

2. If the goal is to explain variation in the response variable that can be attributed to variation in the explanatory variables, linear regression analysis can be applied to quantify the strength of the relationship between the response and the explanatory variables.

# Car Price Prediction Raw data for the evaluation

![raw excel data](https://user-images.githubusercontent.com/92935923/155865541-4afb6a71-1064-45d9-81e9-8c9ac2b8c465.PNG)

![dataset vis](https://user-images.githubusercontent.com/92935923/155865856-d4595682-36b6-4596-ad33-e2af2cf552a4.PNG)


You can access the DATASET from here --[Automobile price data _Raw_.csv](https://github.com/KARTHIK22031999/Car-Price-Prediction-Using-Linear-Regression-Model/files/8147866/Automobile.price.data._Raw_.csv)

# The Microsoft Machine learning studio:

![final car price prediction](https://user-images.githubusercontent.com/92935923/155865687-ac357667-5d6a-4fc0-ada9-25852855755d.PNG)

You can view my experiment in AZURE MACHINE LEARNING STUDIO from here -- https://gallery.azure.ai/Experiment/Car-Price-Prediction-Using-Linear-Regression-Model  

An automobile company aspires to enter the market by setting up their manufacturing unit and producing cars locally to give competition to their counterparts. Specifically, they want to understand the factors affecting the pricing of cars. The company wants to know:

-- Which variables are significant in predicting the price of a car?

-- How well those variables describe the price of a car?

# The Procedure followed for deploying this project

## 1. Selecting the Raw data and checking for any outliers,exceptions,Missing values,NULL values .Data cleaning has been done as replacing the missed value with that respective column mean or median or mode.When the erorrs are more from a specific Row/Column we will eliminate that Row /Column.

![columns](https://user-images.githubusercontent.com/92935923/155866086-8a6c302d-87c9-4914-8eba-da56db9e23e5.PNG)


## 2. Splitting the data for training set and evaluating set. We have done with 70% of training set and 30% of remaining data for predicting the score. For the Training data set we use appropriate MACHINE LEARNING ALGORITHM for training the data set. In this case ,we have used the LINEAR REGRESSION MODEL for predicting the car price.

![linear regression](https://user-images.githubusercontent.com/92935923/155866073-c09b573b-2181-4672-bb1d-c07c9def632a.PNG)

## 3. In training model,the training has been done using the columns of features which we have selected for the prediction.

![trained model](https://user-images.githubusercontent.com/92935923/155866154-2cb447e0-a068-405c-b4c2-f108f6d79c40.PNG)

## 4. After training the dataset,we get the score model which results the score for each car which helps in getting evaluated.

![score model](https://user-images.githubusercontent.com/92935923/155866221-2d06da43-9cc4-494d-b0e5-ca1712d153d0.PNG)

## 5. So finally,by using evaluating model for the scored model set,we get the scores of each CAR PRICE PREDICTION.

![evaluation result](https://user-images.githubusercontent.com/92935923/155866265-46d6e494-ff8a-4df4-8324-6bf0ccda3e97.PNG)

![error histogram](https://user-images.githubusercontent.com/92935923/155866270-758dcbe1-b755-463a-8c03-0736611271a4.PNG)

![final car price prediction](https://user-images.githubusercontent.com/92935923/155866281-57549bac-77ae-43e4-b48a-14e4a050d1fe.PNG)


# It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

##                                           ** THANK YOU **







