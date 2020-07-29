# BangloreRealEstate-
Basic Start to End working project for Data Science 

Step by step process of how to build a real estate price prediction website locally

Firstly We will first build a model using sklearn and linear regression using banglore home prices dataset from kaggle.com. 
Second step would be to write a python flask server that uses the saved model to serve http requests. 
Third component is the website built in html, css and javascript that allows user to enter home square ft area, bedrooms etc and it will call python flask server to retrieve the predicted price. 

We will cover almost all data science concepts such as data load and cleaning, outlier detection and removal, feature engineering, dimensionality reduction, gridsearchcv for hyperparameter tunning, k fold cross validation etc.

Technology and tools wise this project covers,
Python
Numpy and Pandas for data cleaning
Matplotlib for data visualization
Sklearn for model building
Jupyter notebook, visual studio code and pycharm as IDE
Python flask for http server
HTML/CSS/Javascript for UI

There are 2 sub Folders inside Banglore RealEstate
1. Data Analysing
2. Code

Data Analysing contains 4 files
1. datasets_20710_26737_Bengaluru_House_Data.csv  - This is the file which is downloaded from Kaggle (We run our model on this file to get output)
2. bhp.ipynb - This is out notebook which we have created for Analysing data we have used Python, Numpy, Pandas , Matplotlib , SKlearn in this
3. banglore_home_prices_model.pickle - This is the pickle file  which is exported from bhp.ipynb file (converting an object in memory to a byte stream)
4. columns_json - This is the file which in which we have exported every columns

Code Contains 3 Folders
1. model - This folder contains the file which we have copied from Data analysing Folder 
2. server - This contains  server.py (which is used to start server) ,util.py (Which has utilties code) , artifacts (contains pickle and json file)
3. client - This folder contains front end code this has htl,css,js file




