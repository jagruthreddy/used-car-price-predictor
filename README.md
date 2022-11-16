# used-car-price-predictor
Programmed an ML model
## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Local Setup](#local-setup)
  * [Directory Tree](#directory-tree)


## Demo
Link: [https://ask-car-price.herokuapp.com](https://ask-car-price.herokuapp.com)

[![](https://i.imgur.com/Dynlly3.png)](https://ask-car-price.herokuapp.com)

[![](https://i.imgur.com/GqErsg7.png)](https://ask-car-price.herokuapp.com)

## Overview
This is a Flask web app which predicts the selling price of a car using multiple linear regression model made by me and my friend [Nishith](https://github.com/Nishith-Reddy) 

Dataset: [![](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho)](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho)

## Local Setup
Clone the repository on your local environment <br>

```bash
git clone https://github.com/Nishith-Reddy/Ml_Car_Price_Prediction
```
Navigate to the folder <br>
```bash 
cd ML_Car_Price_Prediction
```
Install the required dependencies <br>
```bash
pip install -r requirements.txt 
```
Run the localhost-server <br>
```bash 
flask run
```
The web-app will be available at `127.0.0.1:5000` on your browser. 
## Directory Tree 
```
├── Procfile
├── app
│   ├── main.py
│   ├── static
│   │   └── css
│   │       └── styles.css
│   └── templates
│       └── home.html
├── model.pkl
├── requirements.txt
├── runtime.txt
└── wsgi.py
```
## Technologies Used
![](https://forthebadge.com/images/badges/made-with-python.svg)
[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 
