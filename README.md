# GA-Projects

Projects listed here are related to my 12-week study in General Assembly Sydney, Data Science Immersive Course. The course starts by covering the basics of Python programming and statistics before moving on to Exploratory Data Analysis (EDA), SQL, and web-scraping. The majority of the curriculum then covers the wide variety of machine learning models and the optimisation techniques employed for each one.

The course is incredibly detailed, with the main areas of study being:
- Python: NumPy, Pandas, data cleaning and visualization
- Github: Utilising the software in a professional setting, operating from Command Prompt and branching/pulling from Master
- Machine Learning: Regression, Classification and Clustering algorithms in detail, with a thorough understanding of the mathematical and statistical justifications for their use
- Web Scraping: Using Spiders, XPath, BeautifulSoup4 and Selenium to scrape data from websites and processing using Python

Some of notable projects are:
#### 1. [Job Market Analysis](https://github.com/Angie-Sheng/GA-Projects/tree/master/Job%20Market%20Analysis):

In this project, I Performing web scraping to extract job posting information from seek.com.au and applied NLP techniques to analyze the data to gain insights about data related jobs (Data Scientist, Data Analyst and etc.). I first converted text information into word count vectors and word frequency vectors. Word embeddings were trained on a skip-gram model with negative sampling. Clustering (K-means) and PCA & t-SNE were applied to word embeddings to gain more intuitive insights. Then the text features, together with other categorical features, were fed into different classification models to predict salary range and job titles from job description.

Tag: Web Scraping / Word Cloud / Word2Vec / Tfidf / CountVectorizer / Tree-based Classifier / Logistic Regression

A detailed walk through of my model could be found [here](https://github.com/Angie-Sheng/GA-Projects/blob/master/Job%20Market%20Analysis/3.%20Data%20Analysis.ipynb) and my final Presentation could be found [here](https://github.com/Angie-Sheng/GA-Projects/blob/master/Job%20Market%20Analysis/Project%204.pdf).

#### 2. [House Price Prediction](https://github.com/Angie-Sheng/GA-Projects/tree/master/House%20Price%20Prediction):

In this project, I built a linear regression model to predict house price. I applied Lasso and Ridge regularization to avoid overfitting and perfume a residual analysis to distinguish changeable property characteristics from fixed characteristics. I also attempted to classify whether a sale is abnormal or not based on Logistic Regression, SVM and KNN models.

This project consists of three part: the [first part](https://github.com/Angie-Sheng/GA-Projects/blob/master/House%20Price%20Prediction/Project%203%20-%20Part%201%20Fixed%20Characteristics.ipynb) is dealing with fixed characteristics, followed by the [second part](https://github.com/Angie-Sheng/GA-Projects/blob/master/House%20Price%20Prediction/Project%203%20-%20Part%202%20Renovateable%20Characteristics.ipynb) to add more renovateable characteristics to predict house price. In the [final part](https://github.com/Angie-Sheng/GA-Projects/blob/master/House%20Price%20Prediction/Project%203%20-%20Part%203%20Abnormal%20%20Classifier.ipynb), I tried different classifier to justify whether we could determine which features predict the Abnorml category in the SaleCondition feature or not.

Tag: Feature Engineering / Regularisation Techniques / Generalized Linear Model / Residual analysis 

#### 3. [Predict Future Sales – A Time-Series Forecasting Task](https://github.com/Angie-Sheng/GA-Projects/tree/master/Predict%20Future%20Sales%20-%20A%20Time-Series%20Forecasting%20Task)

For feature engineering purpose, I developed basic date-time based input features and more sophisticated lag and sliding window summary statistics features. I trained 4 models, which were XGBoost, Random Forest, Linear Model and KNN Regressor. After that, I applied a simple ensemble technique by using outputs of four models as the input to a Linear Regression model for the final prediction.

A detailed walk through of my model could be found [here](https://github.com/Angie-Sheng/GA-Projects/blob/master/Predict%20Future%20Sales%20-%20A%20Time-Series%20Forecasting%20Task/Predict%20Future%20Sales.ipynb) and [here](https://github.com/Angie-Sheng/GA-Projects/blob/master/Predict%20Future%20Sales%20-%20A%20Time-Series%20Forecasting%20Task/Predict%20Future%20Sales%20-Part%202.ipynb)

Tag: Time-Series / XGBoost / RandomForestRegressor / KNNRegressor / Ensemble Method 

#### 4. [Fake News Detector](https://github.com/Angie-Sheng/GA-Projects/tree/master/Fake%20News%20Detector):

Using NLP(Natural Language Processing) techniques and several classification models to implement a machine learning pipeline to predict whether a news is fake or not.

Final presentation consists of [non-technical presentation](https://github.com/Angie-Sheng/GA-Projects/blob/master/Fake%20News%20Detector/Finding%20Real%20About%20Fake%20News%20by%20Angie%20Sheng.pdf) and [technical presentation](https://github.com/Angie-Sheng/GA-Projects/blob/master/Fake%20News%20Detector/Detecting%20fake%20news.pdf).

Tag: Web Scraping / NLP / Pipeline / GridSearchCV
