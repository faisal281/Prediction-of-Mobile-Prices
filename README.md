Bob has started his own mobile company. He wants to give tough fight to big companies like Apple,Samsung etc.
He does not know how to estimate price of mobiles his company creates. In this competitive mobile phone market you cannot simply assume things. To solve this problem he collects sales data of mobile phones of various companies.
Bob wants to find out some relation between features of a mobile phone(eg:- RAM,Internal Memory etc) and its selling price.

AIM: In this problem you do not have to predict actual price but a price range indicating how high the price is.

ABOUT THE DATASET: The dataset is about the mobile specifications. The dataset is very small containing of 2000 rows and 21 columns. The dataset has complete numerical features i.e there is no Categorical data in it which is very helpful in building the machine learning model.

TASKS TO BE PERFORMED: 
1. Analysing the Data
2. Cleaning the Data
3. Data Visualization
4. Various ML models
5. Decision Tree
6. Random Forest
7. KNN(K-Nearest Neighbour)

Analysing the Data: According to the information,the data has 20 columns of different categories. By descrribing it,I have found the 25% and 75% of the data and as well the mean of every column of complete  data.

Cleaning the Data: By the application of different pandas functions, there are no null values present in the data. There are no outliers as well. This implies that the data is already cleaned.

Data Visualization: By the use of Correlation Heatmap,it is very understandable the how well the features are correlated with eachother. With the help of plotly.express module the realtion between RAM and PRICE RANGE can be seen so that it will be helpfull to understand the impact of RAM on price of the mobiles. A scatter plot is drawn to visualize the relationship between BATTERY POWER and RAM.

Various ML models: I have built 3 various machine learning models to deeply understand the accuracy of the models on a single dataframe.

Decision Tree: The first algorithm is Decision Tree classifier. The criterion is gini and the maximum depth is 3. The data has been split into Test and Train.The accuracy I got from the DT is 84.3% which is quite good.

Random Forest: I have use RandomisedsearchCV for the model and I have used iteration to be 10,verbose to be 2 and for calculating scoring,negative mean square error is used.By this the accuracy of the model got increased,the accuracy recorded is 87.2%

KNN: While building a model on KNN,the test size is assigned as 0.33 and the reandom state is 101.After splitting the data into train and test,the accuracy recorded is 92.12% which is high when compared to other 2 algorithms.
