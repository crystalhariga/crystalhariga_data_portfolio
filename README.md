# Data Analytics Portfolio
This page consists of a comprehensive archive of my data-related projects:
* Data Quality
* Data Visualization
* Data Modelling
* And others!


## Data Quality (2)
#### [P1: Movie Catalog Database Design](https://github.com/crystalhariga/movie-catalog)
- Designed a data dictionary from 4 datasets for ease of accessibility to display movie information onto Movie Catalog web app
- Designed the front-end of web app using Dash, incorporating interactive buttons to search through database
- Implemented movie images using API from [themoviedb](https://www.themoviedb.org/)


#### [P2: COVID Dashboard](https://htmlpreview.github.io/?https://github.com/crystalhariga/covid-19_wrangling/blob/main/data_wrangling.nb.html)
- Built a data pipeline to transform 3 datasets with 171K+ observations into a usable format for a visualization dashboard web app to display time series data using R's tidyverse
<br/>

## Data Visualization (1)
#### [P1: Post-COVID Small Business Launch Strategy](https://github.com/crystalhariga/data_visualization_consultancy)
* Performed data preparation on 5 datasets (joining, aggregating, changing data types) using Tableau Prep and R
* Conducted Exploratory Data Analysis (EDA) to determine impact of COVID on small business owners and identify largest opportunities for upcoming small business owners using R and Tableau
* Recommended upcoming small business owners:
    1. Ideal location: states with lower new COVID case rates (either west coast or central US); lower-income neighborhoods; near parks, transit stations, grocery stores, pharmacies
    2. Ideal industry: transportation supersector, including trade & utilities
    3. Ideal strategy: provide online experiences for customers and alternative options (pick-up, delivery, return, cancellation)
<br/>

## Data Modelling (2)
#### [P1: Predicting Cancer Cases in the US](https://github.com/crystalhariga/cancer_ml)
* Performed data preparation (transformed variables, clustering) and EDA (descriptive statistics, simple visualization) to understand more about the dataset
* Built Prediction (Regression Tree, Linear Regression) and Classification (KNN, Logistic Regression, Boosted Tree, Bagged Tree) models to predict annual cancer cases
* Compared best hand-crafted models with DataRobot's -- resulting in:
    * __Best Classification Model__: Hand-crafted Bagging Tree with 0.93 Accuracy score (_successfully beat DataRobot!_)
    * __Best Prediction Model__: DataRobot's Random Forest Regressor with RMSE of 418.02

#### [P2: Predicting Customer's Response to a Digital Marketing Campaign](https://github.com/crystalhariga/predictive-modeling_digital-marketing/blob/main/ML_marketing_project.ipynb)
* Prepared data (removing null values, feature selection) for model building
* Evaluated Regression (Linear, Logistic) and Support Vector Machines on the dataset to determine the best model to predict a customer's response
* Predicted a potential customer's response based on a case study of a customer profile using the __best model (Support Vector Classifier)__

