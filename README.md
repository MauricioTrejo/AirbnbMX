# Airbnb data for Mexico city

Alaysis of Airbnb's prices in Mexico city

## Index

1. [Motivation](#motivation)
2. [Requirements and Installation](#requirements)
3. [Project](#project)
4. [Files](#files)
5. [Results](#results)
6. [Acknowledgements](#acknowledgements)

<a name="motivation"></a>
### Motivation

Mexico is one of the biggest cities in the world and as such, it has a lot of different attractions, neighborhoods and of course, prices in Airbnb listings, our intention is to find the drivers of properties prices, you can find a a Medium post in [here](https://medium.com/@mtrejosantamaria/5-questions-i-wanted-to-answer-about-airbnb-in-mexico-223a0fd5aab6?source=friends_link&sk=6fbf162da54dc4b3356cf27c9837a722)

<a name="requirements"></a>
### Requirements

The database used in this notebook is in the file listings from this repository, data from different cities accross the globe can be found [here](http://insideairbnb.com/get-the-data.html).

The libraries used in this project are:

* pandas version 1.0.1
* numpy version 1.18.1
* plotly version 4.8.2
* scikit-learn version 0.22.1

Since plotly graphs are heavy, the notebook may not load, it is important to clone the project in order to see and follow the results.

<a name="projects"></a>
### Project

This project aims to answer 5 questions:
* Which neighborhood is the more expensive?
* Which neighborhood has more super hosts?
* Is there a relationship between super hosts and price in the neighborhoods?
* Why are these neighborhoods more expensive?
* Are there other variables that drive the price?

The answer to each question can be found [here](https://github.com/MauricioTrejo/AirbnbMX/blob/dev/Notebook.ipynb).

<a name="files"></a>
### Files

This repository contains the following files:

* Images. A folder with the output images from plotly.
* Notebook. A jupyter notebook containing the project.
* listings. A csv file with the database

<a name="results"></a>
### Results

We found that the most expensive neighborhoods (municipalities) to stay are Cuauhtémoc and Miguel Hidalgo, they also are the neighborhoods with more super hosts and turistic attarctions in or near them.

The neighboorhood of the property and if the host is a super host is relevant to determine the price. Other important variables are the number of listings of a host, calendar never updated, review scores rating and cleaning fee.

<a name="acknowledgements"></a>
### Acknowledgements

We want to thank Airbnb for the data used in this project.
