ACM Reasearch Application Project - Star Types

* This project took in a dataset of 240 stars each with features such as the Temperature, Luminosity, Radius, Absolute Magnitude, Star color, and spectral class
* I first used the pandas library to get an insight as to what the dataset is about by using functions such as describe and info which showed me the mean, 
standard deviation, min, max, etc. of every column/feature which were grouped by Spectral Class.
* I also implemented a pairplot using seaborn to visualize any sort of correlation with the data. The graph showed a reltionship with the size of the star compared to it's absolute magnitude and the temperature. The larger stars tended to have a lower absolute magnitude as well as a higher temperature.
* The ML models (K Nearest Neighbors and Random Forest Classifier) used were the best given the dataset they had to test, train, and run predictions on. 
* The results of KNN showed a high to average weighted score however the macro average was low, resulting in me using the RFC algorithm as well.
