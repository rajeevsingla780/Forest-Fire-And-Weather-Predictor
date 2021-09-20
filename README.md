# Foresty

# Nowadays, forest fires became one of the foremost important problems that cause damage to several areas around the world.

This webapp can be used to predict the probability of forest fire by entering the forest and the location.
## Built Using
* Flask API - hosted on Heroku
* sklearn for predicting and sklearn for pre-processing
* JS and HTML for the websites
* Darksky API for the weather data
* Pandas, Numpy for csv reading, linear algebra respectively.
* Integrated and hosted on Heroku
## How it works
* When the user clicks the button on the web page, the Darksky API  sent the latitude and longitude
of the place entered and collects the raw data of the forest.
* The python script then fetches weather data from the Darksky API.
* This data is used to calculate the Humidity, Temperature and Oxygen.
  
## Requirements
* `sklearn` for machine learning
* `flask`, `flask-cors` for the API
* `numpy` for linear algebra
* `pandas` for reading the training data in the form of `*.csv`
