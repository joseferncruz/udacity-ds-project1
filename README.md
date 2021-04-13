# Udacity Nanodegree in Data Science - Project 1
This repository is part of the learning objectives of the [nanodegree in data science](https://www.udacity.com/course/data-scientist-nanodegree--nd025) provided by Udacity.


## Table of Contents

- [Introduction](#introuduction)
- [The data](#the-data)
- [Installation](#installation)
- [The code](#the-code)
- [Results](#results)
- [Licensing and Acknowledgements](#licensing-and-acknowledgements)

## Introduction

**New York City** is well known for the excellent cultural and gastronomic scene. When the pandemic hit, some restaurants were forced to close and others started to provide outdoor dining under Phase Two of the State’s New York Forward Plan. The measure became very popular and provided the opportunity to sustain the recovery of the business and attract new customers with better social distancing conditions. Using the dataset provided by NYC, I wanted to understand:

1. Which borough and neighborhoods contains the highest number of restaurants with outdoor dining available?

2. Where is located the highest number of restaurants in close proximity to a landmark building or location?

3. What is the proportion of restaurants providing outdoor dining that offer alcoholic beverages in the neighborhood with the highest density of landmark locations?


## The data

The dataset is publicly available through the [New York City Open Data Initiative](https://data.cityofnewyork.us/Transportation/Open-Restaurant-Applications/pitm-atqc). The version available in the directory `dataset/` was downloaded on April 9th, 2021.

In order to generate choropleth maps, I used this [geojson](https://data.beta.nyc/dataset/pediacities-nyc-neighborhoods) containing the geographic limits of the [NYC Neighborhood Tabulation Areas (NTA)](https://www1.nyc.gov/site/planning/data-maps/open-data/dwn-nynta.page). The geojson file can be found in the directory `dataset/`.


## Installation

In order to view and run the code of this project, you can use two options:

__A)__ Run the code in a local machine:

1. Download or clone this repository using git:
```
git clone github.com/joseferncruz/udacity-ds-project1
cd udacity-ds-project1/
```
2. Install a python environment with jupyter notebooks (e.g., [anaconda distribution](https://www.anaconda.com/products/individual)).

3. Create an environment with the required packages by running on the anaconda shell:
```
conda env create -f environment.yml
conda activate jc-udacity-ds-project1
```

__B)__ Open the notebook on [Binder](addlink):



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
