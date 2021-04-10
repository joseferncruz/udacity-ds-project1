# Udacity Nanodegree in Data Science - Project 1
This repository is part of the learning objectives of the [nanodegree in data science](https://www.udacity.com/course/data-scientist-nanodegree--nd025) provided by Udacity.


## Table of Contents

1. [Introduction](#project-motivation)
2. [The data](the-data)
3. [Installation](#installation)
4. [The code](#the-code)
5. [Results](#results)
6. [Licensing and Acknowledgements](#Licensing-and-acknowledgements)

## Introduction

**New York City** is well known for the excellent cultural and gastronomical scene. When the pandemic hit, some restaurants were forced to close and others started to provide outdoor dinning under [Phase Two of the State’s New York Forward Plan](). The measure became very popular and provided the opportunity to sustain the recover of the business and attract new costumers with better social distancing conditions. Using the dataset provided by NYC, I wanted to understand:

1. Which borough and neighborhoods contains the highest amount of restaurants with outdoor dinning available?

2. Where is located the highest amount of restaurants in close proximity to a landmark building or location?

3. What is the proportion of restaurants providing outdoor dinning that offer alcoholic beverages in the neighborhood with the highest density of landmark locations?

## The data

The dataset is publicly available through the [New York City Open Data Initiative](https://data.cityofnewyork.us/Transportation/Open-Restaurant-Applications/pitm-atqc). The version available in the directory `dataset/` was downloaded on April 9th, 2021.

In order to generate choropleth maps, I downloaded a [geojson](https://data.beta.nyc/dataset/pediacities-nyc-neighborhoods) containing the geographic limits of the [NYC Neighborhood Tabulation Areas (NTA)](https://www1.nyc.gov/site/planning/data-maps/open-data/dwn-nynta.page). The geojson file can be found in the directory `dataset/`.


## Installation

In order to view the code of this project, you can use of options:

__A)__ Run the code in a local machine:

1. Download or clone this repository using git on bash:
```
$ git clone ...
```
2. Install a python environment with jupyter notebooks/lab such (e.g., [anaconda distribution](https://www.anaconda.com/products/individual)).

3. Create an environment with the required packages by running on the anaconda shell:
```
$ conda env create -f ...
```

__B)__ Open the notebook on Binder:

```
add binder
```


## The code

The included in this project can be found in the notebook `udacity-course1.ipynb`.


## Results

The main results can be found at this [blog post]().


## Licensing and Acknowledgements

The analysis and code generated during this project are licensed under a MIT License.

Acknowledgements are mostly to the effort of the NYC city hall to provide the datasets with accurate and updated information.  



---
_**Disclaimer**_
 The author is not affiliated with any of the entities mentioned nor received any kind of compensation. The information contained in this work is provided on an "as is" basis with no guarantees of completeness, accuracy, usefulness or timeliness.
