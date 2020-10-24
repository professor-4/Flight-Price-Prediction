# Flight Price Prediction

### Table of content
 * [Demo](#Demo)
 * [Overview](#Overview)
 * [Installation](#Installation)
 * [Technologies Used](#Technologies-Used)
 * [Code](#Code)
 * [Dataset](#Dataset)
 * [Deployment](#Deployment)
 * [Bug / Feature Request](#Bug--Feature-Request)
 
 ### Overview
 Flask Web App for Flight Price Prediction
 
 ### Installation
This code is written in python 3.6.10. If you want to install Python You can [click here](https://realpython.com/installing-python/) to know more about it. If you have python but not having required libraries and packages, then you can install those libraries and command using this command.
 ```bash
pip install -r requirements.txt
```


### Technologies Used

* Find required package and libraries file [here](www.google.com)


![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 


### Code

After performing feature enginerring and feature selection (to find out which will contribute and have good relation with target variableI) on data set, I trained the model to predict price by Using [Random Forest](https://en.wikipedia.org/wiki/Random_forest). To serialize our python code we used pickle module. Pickel moduel Is used to convert python object into a byte stream. You can Read more about pickle Module [here](https://docs.python.org/3/library/pickle.html#:~:text=%E2%80%9CPickling%E2%80%9D%20is%20the%20process%20whereby,back%20into%20an%20object%20hierarchy.).

*Find the code [here]()* 



### Dataset
[https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh](https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh)


### Deployment
For deployment of model I used Heroku (A platform to run, build and operate application entirely in the cloud) To know more about step by step process of building and deploying our application on Heroku, you can find it [here](https://devcenter.heroku.com/articles/getting-started-with-python).

### Bug / Feature Request 
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an [issue](https://github.com/professor-4/Flight-Price-Prediction/issues) here by including your search query and the expected result




 
 
