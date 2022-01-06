# Portfolio 1 ,2 ,and 3

![Image](data/macquarie-university-building.jpg)[link](https://www.timeshighereducation.com/world-university-rankings/macquarie-university)

Portfolio repository for COMP6200: Data Science at Macquarie University

|Student ID: 46199551|
| ----------------------- |
|Student Name: Aditya Sharma   |




| Sr. No. | Portfolio                                  | Work Done                                                                                                                                                                                                                    |
| ------- | ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1       | Portfolio 1          | 1.Plotting and Analysis of cycling data and other workout data using 4 datasets - weather 18-19 ,Strava ,and cheetah. data  |
| 2       | Protfolio 2     |Predicting the energy usage of a house based on Internet of Things (IoT) measurements of temperature and humidity and weather observations. Using the [research paper](https://linkinghub.elsevier.com/retrieve/pii/S0378778816308970) provided. |
| 3       |Portfolio 3 |   Predicting the genere of books with the summary provided in txt format. |



![beyondtheory](data/BeyondT.png)[Source](https://beyondtheory.co.uk/employee-data-analysis-service)

### Introduction and Steps Involved in these Portfolios.
  
  `Portfolio 1 :`
  
#### Inroduction
           
The first dataset is an export of my ride data from [Strava](https://strava.com/), an online social network site for cycling and other sports.This data is a log of every ride since the start of 2018 and contains summary data like the distance and average speed.The second dataset comes from an application called [GoldenCheetah](https://www.goldencheetah.org/) which provides
some analytics services over ride data.  This has some of the same fields but adds a lot of analysis of the 
power, speed and heart rate data in each ride.This data overlaps with the Strava data but doesn't include all 
of the same rides. 

`Steps Involved`

    1.Combining and adding new data files (weather 18-19)
    2.Adding both columns and drop function from pandas.
    3.Removing "false' values in the data given.
    4.Comparing both datas strava and cheetah using correlation and scatter plots.
    5.combining the weather data together which is for year 2018-2019 and then combining with starva+cheetah data.
    6.Analysis using various sns plots and finding a Correlation between values.
    7.Reporting the conclusion and the summary of the merged data.
    
 ![Machinelearning](data/1_RIrPOCyMFwFC-XULbja3rw.png)[Source](https://towardsdatascience.com/best-python-libraries-for-machine-learning-and-deep-learning-b0bd40c7e8c)


    
  `Portfolio 2 :`
  
#### Inroduction
The goal of the second portfolio is to reproduce some work on predicting the energy usage of a house based on Internet of Things (IoT) measurements of temperature and humidity and weather observations. This Data is Driven from [Data driven prediction models of energy use of appliances in a low-energy house](http://dx.doi.org/10.1016/j.enbuild.2017.01.083).The dataset is provided in the form of two csv files  named **training.csv and testing.csv**.We need to a report linear regression model results both on training and testing set and the analysis of this data. 
  
  
  `Steps Involved`
  
    1.Splitting Dates and time for both the datasets Testing and Traning
    2.Analysing the trend between the month and appliences usage
    3.Making Different plots for the analysis of training data for example line graph , heatmaps ,Corr graphs etc.
    4.Dropping columns and rows for further analysis 
    5.Using various machine learning techniques like  R squre, RMSE, and others for predicting model.
    6.Producing RFE graph using Regression Methods.
    7.Predicting and analysisng each and every plot for conclusion.
    8.Adding new Regression methods like Random Forest Regression and labeling all the plots and analysis.
    9.Adding Summary ,conclusion and Final Analysis and testing of codes.
   

![TEXT mining](data/text-mining-steps.png)[Source](https://www.fosteropenscience.eu/content/text-mining-101)
 
  
 `Portfolio 3 :`

#### Inroduction
The goal of the third portfolio is to build predictive models for the genre of a book based on a summary.This contains the starter notebook and the [data](https://github.com/MQCOMP6200/portfolio-s1-2021-iamadisharma/blob/main/data/booksummaries.txt) which is in the text format. The notebook selects a subset of the books and labels them with a single Genre label.Our task is to build models to predict the genre from the summary text and report your results. 
  
    1.Importing libraries which will be used in the portfolio and Loading the text data provided (txt format)
    2.Data prepration-Including only those columns that are in need like wid, fid, title, author, date, genres,summary.
    3.Selecting and Working With summary data to find different attributes such as word count , upper lower case words, numbers etc.
    4.Seperating the english and non english words and seperating commas and vocab words to make the model.
    5.checking the most repeated words used in the summary 
    6.Using Test train split and splitting the data into testing and training (80-20%) for the modelling purpose.
    7.producing a Matrix of the array of the top 1000 words used in the summary.
    8.Plotting the bar ghaph for the genre of the books to see which is genre has the most books.
    9.Using different regression and modelling methods for the analysis and model prediction
    10.Evaluating the predicting model.
    11.Conclusion.

 


### Refrences

1.[Pandas](https://pandas.pydata.org/)
2.[Seaborn](https://seaborn.pydata.org/)
3.[Scikit](https://scikit-learn.org/)
4.[Numpy](https://numpy.org/)
5.[Analytics Vidhya](https://www.analyticsvidhya.com/)
6.[Geeks For Geeks](https://practice.geeksforgeeks.org/)
7.[GitHub](https://github.com/)
8.[Kaggle](https://www.kaggle.com/)
9.[Stack Overflow](https://stackoverflow.com/)
10.[Towards Data Science](https://towardsdatascience.com/)



        
             
           
