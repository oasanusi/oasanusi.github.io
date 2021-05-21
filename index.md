# Projects        

##### Title:

[Fake News Detection using ML Classifiers](https://oasanusi.github.io/fake_news_detection) | ***Natural Language Processing (NLP)\***

<img src="/images/models.png" alt="ML classifiers" style="zoom:150%;" />

##### Description:

This project focused on using supervised ML classifiers to detect patterns in fake news articles. A very large fake news corpus was subsetted to obtain a raw dataset that consist of a balanced distribution of fake and real news articles (approximately 1 million instances each)                

- Data preprocessing steps performed on the dataset include noise removal, lemmatization and feature vectorization.

- Twelve ML classifiers (logistics regression, multinomial naive bayes, linear SVC, SGD classifier, decision tree, random forest, extra trees, adaboost, lightGBM, xgboost, MLP classifier and deep neural network) were used in this project.

- Model performances were evaluated by comparing the accuracy score, recall and true positive of each model. Majority of the ML algorithms have accuracy greater than 80%. However, the neural networks algorithms performed the best with accuracy score of over 90%. When all the other evaluation criteria was considered, the deep neural network was found to be the best at distinguishing patterns between fake and real news articles.

  

##### Technologies:

Pandas, NLTK, Gensim, Scikit-Learn, Keras, Yellowbrick, Regular Expression, Seaborn

​                              

Check out full codes and notebook on [github](https://github.com/oasanusi/Fake-News-Detection-Using-Machine-Learning-Classifiers/blob/main/notebooks/Fake%20News%20Detection_new.ipynb)

​        

------

##### Title:

[Analysis of Crime Types in Baltimore City, MD](https://oasanusi.github.io/analysis_of_baltimore_crimes) | ***Exploratory Data Analysis (EDA)\***

<img src="/images/baltimore_crime.png" alt="baltimore" style="zoom:72%;" />

##### Description:

The purpose of this project is to  use exploratory data analysis (EDA) to draw inferences on historical crime data of Baltimore City, MD. As a result of sparsity in data from 1063 to 2013, only data covering 7 years period (2014 to 2020) was considered. The investigation reveals that the top three crimes in the city are: larceny (22%), common assault (17%) and burglary (14%). The overall crime increased gradually from 2014 to the highest in 2017 and has been decreasing steadily. Most of the crimes occurs during the summer and the northeast police district has the highest occurrence with the most dangerous neighborhoods being Downtown and Frankford. Out of the 14 reported crime types, five crime types (agg. assault, homicide, rape, robbery-carjacking, shooting) shows increasing trends when comparing the counts from 2014 to 2020. For all the crime types with increasing trends, the following neighborhoods are very dangerous: Downtown, Sandtown-Winchester, Brooklyn, Frankford, Broadway East.

##### Technologies:

Python, NumPy, Pandas, Seaborn, Matplotlib, Calender, Squarify

​                                

Check out full codes and notebook on [github](https://github.com/oasanusi/Fake-News-Detection-Using-Machine-Learning-Classifiers/blob/main/notebooks/Fake%20News%20Detection_new.ipynb)

​            

------

##### Title:

Predicting Baltimore City (MD) Crimes using Time Series SARIMAX model | ***Time Series Forecasting\***        

<img src="/images/ts_baltimore.png" alt="time series" style="zoom:150%;" />

##### Description:

In this project, time series (S)ARIMA(X) model was used to predict crime occurring in Baltimore City, MD. The  data obtained from [Baltimore Open Data Website](https://data.baltimorecity.gov/datasets/part1-crime-data/data?geometry=-86.354%2C37.108%2C-71.534%2C40.112) was subsetted to cover a 7 years period from January 2014 to December 2020. The overall crime with decreasing trend and three crime types (agg. assault, homicide, robbery-carjacking and shooting) with increasing trends were considered in this investigation. 

##### Technologies:

Pandas, Numpy, Scikit learn, Seaborn, Statsmodels, Sktime, Pyramid Arima 

​                           

Check out full codes and notebook on github
