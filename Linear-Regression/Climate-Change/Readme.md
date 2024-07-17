# Linear-Regression
- by Harshit Kandhwey

## Introduction
<img align='left' src="https://media0.giphy.com/media/l0HlMURBbyUqF0XQI/giphy.gif"  >

Climate change includes both human-induced global warming and its large-scale impacts on weather patterns. There have been previous periods of climate change, but the current changes are more rapid than any known events in Earth's history. The main cause is the emission of greenhouse gases, mostly carbon dioxide (CO
2) and methane. Burning fossil fuels for energy use creates most of these emissions. Agriculture, steel making, cement production, and forest loss are also significant sources.Temperature rise is affected by climate feedbacks as well, such as the loss of sunlight-reflecting snow cover, and the release of carbon dioxide from drought-stricken forests. Collectively, these amplify global warming.
Climate change is one of the most fiercely debated scientific issues of the past 20 years. Human-induced warming is superimposed on a naturally varying climate, the temperature rise has not been, and will not be, uniform or smooth across the country or over time.Climate change fatalities are generally linked to four different catalysts:
-Rising temperatures
-Declining air quality
-Extreme weather
-Vector-borne illnesses
In this assignment I am concentrating on the reason for Rising Temperature. For which, I have taken climate change data to visualize the temerature variation through Pandas,NumPy,MathPlotlib & Linear Regression.


## Climate Change - Preparing Data
<img align='left' src="https://www.itbusinessedge.com/wp-content/uploads/2021/03/DatawatchPreparingAnalyticData01.jpg"  >
Data preparation is the process of cleaning and transforming raw data prior to processing and analysis. It is an important step prior to processing and often involves reformatting data, making corrections to data and the combining of data sets to enrich data.

Data preparation is often a lengthy undertaking for data professionals or business users, but it is essential as a prerequisite to put data in context in order to turn it into insights and eliminate bias resulting from poor data quality.

The data for our project is chosen from https://www.kaggle.com/vageeshabudanur/riseintemp-dataset

The file climate_change.csv contains climate data from May 1985 to December 2005. The available variables include:

parameters are Year ,Month, MEI, CO2,CH4,N2O,CFC-11,CFC-12,TSI,Aerosols,Temp.But for performing linear regression we are just doing with two parameters years vs. temperature rising.

## Linear Regression Model
<img align='left' src="http://www.sthda.com/english/sthda-upload/images/machine-learning-essentials/linear-regression.png"  >

Linear regression is perhaps one of the most well known and well understood algorithms in statistics and machine learning.

Linear regression analysis is used to predict the value of a variable based on the value of another variable. The variable you want to predict is called the dependent variable. 
The variable you are using to predict the other variable's value is called the independent variable.

The aim of linear regression is to model a continuous variable y as a mathematical function of one or more x variable(s), so that we can use this regression model to predict the y when only the x is known. This mathematical equation can be generalized as follows:
```y=a+bx+ϵ```

We can make interactive plot Python library Matplotlib.

## Acknowledgment

I acknowledge https://www.kaggle.com/vageeshabudanur/riseintemp-dataset for the data set & Perform Linear Regression on the Dataset
