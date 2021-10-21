# Flight_Fare_Prediction
The main goal of this project is to predict the fares of the flights based on different factors available in the provided dataset.

## Table of Content
  * [Demo](#demo)
  * [Problem Statement](#problem-statement)
  * [Approach](#approach)
  * [Technologies Used](#technologies-used)
  * [Installation](#installation)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Detailed Project Reports](#detailed-project-reports)
  * [Bugs & Logs](#bugs--logs)
  * [Contributors](#contributors)

## Demo
Link: [https://flightprice-predict.herokuapp.com/](https://flightprice-predict.herokuapp.com/)
![image](https://user-images.githubusercontent.com/63100086/135015307-22fb5e2b-9753-42ba-9716-23a6f145ec3c.png)
![image1](https://user-images.githubusercontent.com/63100086/135015834-6babff17-39aa-4516-8471-dfb5a3d82083.png)
![image2](https://user-images.githubusercontent.com/63100086/135015891-36209d42-586c-48ea-832a-8434d28eaab3.png)



## Problem Statement
Travelling through flights has become an integral part of today’s lifestyle as more and more people are opting for faster travelling options. The flight ticket prices increase or decrease every now and then depending on various factors like timing of the flights, destination, and duration of flights various occasions such as vacations or festive season. Therefore, having some basic idea of the flight fares before planning the trip will
surely help many people save money and time.

## Approach
Data Exploration : I started exploring dataset using pandas,numpy,matplotlib and seaborn.

Data visualization : Ploted graphs to get insights about dependend and independed variables.

Feature Engineering : Removed missing values and created new features as per insights.

Model Building & Testing : Tried many machine learning algorithms and checked the base accuracy to find the best fit.

Pickle File : Selected model as per best accuracy and created pickle file.

User Interface & deployment :  Created an UI with a form that takes all the necessary inputs from user and shows the output.
                          After that I have deployed project on heroku.
## Technologies Used
 
   1. Python 
   2. Sklearn
   3. Flask
   4. Html
   5. Css
   6. Pandas, Numpy 

## Installation
Click here to install [python](https://www.python.org/downloads/). To install the required packages and libraries, run this pip command in the project directory after cloning the repository:
```bash
git clone https://github.com/jpkelvin/Flight_Fare_Prediction.git
pip install -r requirements.txt
```
If pip is not already installed, Follow this [link](https://pip.pypa.io/en/stable/installation/)

## Deployement on Heroku
Create a virtual app on Heroku website. You can either connect your github profile or download cli to manually deploy this project.
Follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.


## Detailed Project Reports
 ```
 https://drive.google.com/drive/folders1FX0wJvoAn0aRRl7v0YPIsthDLkdpM2BM?usp=sharing
 ```

## Bugs & Logs

1. If you find a bug, kindly open an issue and it will be addressed as early as possible. [Open](https://github.com/jpkelvin/Flight_Fare_Prediction/issues)
2. Under localhost, logging is performed for all the actions and its stored onto logs.txt file
3. When the app is deployed on heroku, logs can be viewed on  heroku dashboard or CLI.

## Contributors
1. [J Prince Kelvin](https://github.com/jpkelvin)
2. [Sandra V](https://github.com/sandrasanu)
3. [Sreerang R](https://github.com/sreerang2014)
