# Used Car Price Prediction: 

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Installation](#installation)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)
  * [Bug / Feature Request](#bug---feature-request)
  * [Future scope of project](#future-scope)


## Demo
Visit My live site for [UsedcarPricePrediction](https://usedcarpriceprediction1.herokuapp.com).

<img width="1434" alt="HomePage" src="https://user-images.githubusercontent.com/45511185/167059700-7ef618a1-2df1-41e0-96ef-50aa52241771.png" href="https://usedcarpriceprediction1.herokuapp.com">

<img width="1438" alt="Price" src="https://user-images.githubusercontent.com/45511185/167059901-37a663f9-b34e-4f82-baff-892225a18333.png" href="https://usedcarpriceprediction1.herokuapp.com">


## Overview
This is a Flask web app which predicts the price of the Used car.And for prediction I have used GrandientBoosting to train the model.

## Motivation
Everyone has dreams, But only few work for their dreams & I'm in that few !.Playing games is fun but solving errors is adventurous and this is the real deal. And important thing If you need a Motivation to get started then you should change a little bit !

## Installation
The Code is written in Python. No python in your local [install it](https://www.python.org/downloads/). 
You want use this repo the start to [clone](https://github.com/BHariKrishnaReddy/UsedCarPricePrediction.git) it by doing ...
```bash
pip install -r requirements.txt
```

## Deployement on Heroku
Login or signup in order to deploy and create virtual app in Heroku. You can either connect your github profile or manually deploy the project using Heroku CLI.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

Our next step would be to follow the instruction given on [Heroku CLI Documentation](https://devcenter.heroku.com/articles/heroku-cli) to deploy a web app.

### Other ways to deploy
  * [Docker](https://docs.docker.com/language/java/deploy/)
  * [Streamlit](https://docs.streamlit.io/streamlit-cloud/get-started/deploy-an-app)

## Directory Tree 
```
├── static 
│   ├── css
├── template
│   ├── home.html
├── app.py
├── gb.pkl
├── notebook.ipynb
├── Procfile
├── README.md
├── requirements.txt
```

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 


## Bug / Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an [issue](https://github.com/BHariKrishnaReddy/UsedCarPricePrediction/issues) here by including your search query and the expected result.You can find an other version of notebook [here](https://www.kaggle.com/code/harikrishnareddyb/eda-and-rf).

## Future Scope

* Use multiple Algorithms to make the prediction more accurate
* Optimize Flask app.py
* Enhance Front-End for better interaction !
